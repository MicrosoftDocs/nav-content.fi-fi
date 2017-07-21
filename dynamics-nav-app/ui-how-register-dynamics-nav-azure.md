---
title: "Toimintaohje: Dynamics NAV -ohjelman rekisteröiminen Azure Management Portal -portaalissa"
author: edupont04
manager: edupont
ms.author: edupont
ms.custom: na
ms.date: 11/15/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 225773f7f686dd6e9a79f759d520d66f7e7b9d0a
ms.contentlocale: fi-fi
ms.lasthandoff: 06/26/2017

---
# <a name="how-to-register-dynamics-nav-in-the-azure-management-portal"></a>Toimintaohje: Dynamics NAV -ohjelman rekisteröiminen Azure Management Portal -portaalissa
Jos haluat käyttää Microsoftin Azureen perustuvia palveluita, Dynamics NAV -ohjelma on rekisteröitävä Azure Management Portal -portaalissa. Esimerkiksi [Myynnin ja varaston ennuste](ui-extensions-sales-forecast.md) -laajennus edellyttää API-avaimen ja API:n URL-osoitteen määrittämistä. Myös muut palvelut vaativat samat tiedot. Mistä nämä tiedot löytyvät?

Voit rekisteröidä Dynamics NAV -ohjelman Azure Management Portal -portaalissa **Azure Management Portal -portaalin määrittäminen** -oppaan avulla. Voit poimia tiedot, joita tarvitaan palveluiden, kuten esimerkiksi Myynti- ja varastoennuste -laajennuksen, Power BI:n ja Office 365:n käyttämisessä. Azure Management Portal -portaaliin rekisteröidytään vain kerran. Sinun on oltava Dynamics NAV -ohjelman järjestelmänvalvoja tai pääkäyttäjä.

Rekisteröityminen tehdään siksi, että Dynamics NAV -ohjelman ja palvelun, johon haluat muodostaa yhteyden, on tiedettävä toisensa Azure Active Directory (Azure AD) -sovelluksen tiedot.

## <a name="to-register-dynamics-nav-in-the-azure-management-portal"></a>Dynamics NAV -ohjelman rekisteröiminen Azure Management Portal -portaalissa
1. Kirjaudu sisään Azure Management Portal -portaaliin osoitteessa [https://portal.azure.com](https://portal.azure.com).
    Jos et ole aiemmin käyttänyt Azure Management Portal -portaalia, saat ohjeita [Azuren ohjekirjastosta](https://azure.microsoft.com/en-us/documentation/articles).
2. Valitse vasemmassa siirtymisruudussa **Lisää palveluita** ja valitse sitten **Sovellusten rekisteröinnit**.
3. Valitse päävalikossa **Lisää** ja täytä sitten **Luo-ruudun** kenttiin seuraavat tiedot:
    - **Nimi**: Määritä Dynamics NAV -ratkaisulle nimi, esimerkiksi *Dynamics NAV*.
    - **Sovelluksen tyyppi**: Valitse **Verkkosovellus*/API**.
    - **Kirjautumisen URL-osoite**: Syötä Dynamics NAV -ohjelman selaimen asiakasohjelman URL-osoite, kuten *https://MyServer:8080/DynamicsNAV/WebClient/OAuthLanding.htm*.
        OAuthLanding.htm-tiedoston avulla voi hallita Dynamics NAV -ohjelman ja muiden palveluiden tietojen siirtoa Azure AD -sovelluksen kautta.
4. Valitse **Luo**-painike.
    Tämä lisää Dynamics NAV -ohjelman **Sovellusten rekisteröinnit -ruutuun**, joten voit nyt lisätä siihen asetukset.
5. Valitse uusi sovelluksesi **sovelluksen rekisteröintien luettelosta**. Jos tämä ei avaa **Asetukset**-ruutua, näkyviin tulee toiminto, joka avaa **Asetukset**-ruudun.
6. Valitse **Asetukset**-ruudussa **API:n käyttö**-osassa **Avaimet**.
7. Määritä **Avaimet**-ruutuun kuvaus ja avaimen vanhenemisajankohta. Valitse sitten **Tallenna**.
8. Kopioi luotu avain väliaikaiseen sijaintiin. Sitä tarvitaan seuraavassa vaiheessa.
9. Valitse **API:n käyttö** -osassa **Vaaditut käyttöoikeudet**.
    - Delegoitujen käyttöoikeuksien lisääminen kaikkien Power BI -palvelun raporttien tarkastelemista varten
    - Delegoitujen käyttöoikeuksien lisääminen Windows Azure Active Directoryn käyttäjäprofiileihin kirjautumista ja niiden lukemista varten
    - Niiden muiden palveluiden toistaminen, joille halutaan myöntää Dynamics NAV -ohjelman käyttöoikeus
10. Sulje **Asetukset**-ruutu. Kopioi sitten **Perustiedot**-ruudun **Sovellustunnus** väliaikaiseen sijaintiin.

Nyt olet rekisteröinyt Dynamics NAV -ohjelman Azure Management Portal -portaalissa, antanut käyttöoikeuden liittyville palveluille ja poiminut Dynamics NAV -ohjelmassa tarvittavat tiedot.  

## <a name="to-add-the-information-to-dynamics-nav"></a>Tietojen lisääminen Dynamics NAV -ohjelmaan
1. Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Ohjattu Azure AD -sovelluksen asennus** ja valitse sitten aiheeseen liittyvä linkki.
2. Valitse ohjatussa toiminnossa **Seuraava**.
3. Määritä **Asiakasohjelman tunnus** -kenttään **Sovellustunnus**-kentästä aiemmin kopioimasi sisältö.
4. Määritä **Salainen avain** -kenttään **Avaimet**-ruudusta aiemmin kopioimasi sisältö.
5. Valitse **Seuraava**. Jos näyttöön ei tule virhesanomaa, toiminto on valmis.

Dynamics NAV -ohjelma on rekisteröity ja valmis muodostamaan yhteyden esimerkiksi Cortana Intelligence- ja Power BI -palveluun.

## <a name="see-also"></a>Katso myös
[Myynnin ja varaston ennuste](ui-extensions-sales-forecast.md)  
[Dynamics NAV -ohjelman määrittäminen](setup.md)  

