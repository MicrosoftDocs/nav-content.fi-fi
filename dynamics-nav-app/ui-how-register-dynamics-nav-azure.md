---
title: "Toimintaohje: Dynamics NAVin rekisteröiminen Azure Management Portalissa"
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
ms.translationtype: HT
ms.sourcegitcommit: 6b60b1344a1e18ad91863046110df880f75f7c04
ms.openlocfilehash: d41b96ab5807402a342991d5c5bc2d672db09e2f
ms.contentlocale: fi-fi
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-register-dynamics-nav-in-the-azure-management-portal"></a>Toimintaohje: Dynamics NAVin rekisteröiminen Azure Management Portalissa
Jos haluat käyttää Microsoftin Azureen perustuvia palveluita, Dynamics NAV on rekisteröitävä Azure Management Portalissa. Esimerkiksi [Myynnin ja varaston ennuste](ui-extensions-sales-forecast.md) -laajennus edellyttää API-avaimen ja API:n URL-osoitteen määrittämistä. Myös muut palvelut vaativat samat tiedot. Mistä nämä tiedot löytyvät?

Voit rekisteröidä Dynamics NAVin Azure Management Portalissa **Azure Management Portalin määrittäminen** -oppaan avulla. Voit poimia tiedot, joita tarvitaan palveluiden, kuten Myynti- ja varastoennuste -laajennuksen, Power BI:n ja Office 365:n, käyttämisessä. Azure Management Portaliin rekisteröidytään vain kerran. Sinun on oltava Dynamics NAVin järjestelmänvalvoja tai pääkäyttäjä.

Rekisteröityminen tehdään siksi, että Dynamics NAVin ja palvelun, johon haluat muodostaa yhteyden, on tiedettävä toistensa Azure Active Directory (Azure AD) -tiedot.

## <a name="to-register-dynamics-nav-in-the-azure-management-portal"></a>Dynamics NAVin rekisteröiminen Azure Management Portalissa
1. Kirjaudu Azure Management Portaliin osoitteessa [https://portal.azure.com](https://portal.azure.com). Jos Azure Management Portalin käyttö ei ole tuttua, ohjeita on [Azuren ohjekirjastossa](https://azure.microsoft.com/en-us/documentation/articles).
2. Valitse vasemmassa siirtymisruudussa **Lisää palveluita** ja valitse sitten **Sovellusten rekisteröinnit**.
3. Valitse päävalikossa **Lisää** ja täytä sitten **Luo-ruudun** kenttiin seuraavat tiedot:
    - **Nimi**: Määritä Dynamics NAV -ratkaisulle nimi, kuten *Dynamics NAV*.
    - **Sovelluksen tyyppi**: Valitse **Verkkosovellus*/API**.
    - **Kirjautumisen URL-osoite**: Anna Dynamics NAVin selaimen asiakasohjelman URL-osoite, kuten *https://MyServer:8080/DynamicsNAV/WebClient/OAuthLanding.htm*.
        Voit hallita OAuthLanding.htm-tiedoston avulla Dynamics NAVin ja muiden palveluiden tietojen siirtoa Azure AD:n kautta.
4. Valitse **Luo**-painike.
    Dynamics NAV lisätään **Sovellusten rekisteröinnit** -ruutuun, ja voit lisätä siihen nyt asetuksia.
5. Valitse uusi sovelluksesi **sovelluksen rekisteröintien luettelosta**. Jos tämä ei avaa **Asetukset**-ruutua, näkyviin tulee toiminto, joka avaa **Asetukset**-ruudun.
6. Valitse **Asetukset**-ruudussa **API:n käyttö**-osassa **Avaimet**.
7. Määritä **Avaimet**-ruutuun kuvaus ja avaimen vanhenemisajankohta. Valitse sitten **Tallenna**.
8. Kopioi luotu avain väliaikaiseen sijaintiin. Sitä tarvitaan seuraavassa vaiheessa.
9. Valitse **API:n käyttö** -osassa **Vaaditut käyttöoikeudet**.
    - Delegoitujen käyttöoikeuksien lisääminen kaikkien Power BI -palvelun raporttien tarkastelemista varten
    - Delegoitujen käyttöoikeuksien lisääminen Windows Azure Active Directoryn käyttäjäprofiileihin kirjautumista ja niiden lukemista varten
    - Vaiheet toistetaan muiden palveluiden kohdalla, joille Dynamics NAVin käyttöoikeudet myönnetään
10. Sulje **Asetukset**-ruutu. Kopioi sitten **Perustiedot**-ruudun **Sovellustunnus** väliaikaiseen sijaintiin.

Olet nyt rekisteröinyt Dynamics NAVin Azure Management Portalissa, antanut käyttöoikeuden liittyville palveluille ja poiminut Dynamics NAVissa tarvittavat tiedot.  

## <a name="to-add-the-information-to-dynamics-nav"></a>Tietojen lisääminen Dynamics NAViin
1. Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Ohjattu Azure AD -sovelluksen asennus** ja valitse sitten aiheeseen liittyvä linkki.
2. Valitse ohjatussa toiminnossa **Seuraava**.
3. Määritä **Asiakasohjelman tunnus** -kenttään **Sovellustunnus**-kentästä aiemmin kopioimasi sisältö.
4. Määritä **Salainen avain** -kenttään **Avaimet**-ruudusta aiemmin kopioimasi sisältö.
5. Valitse **Seuraava**. Jos näyttöön ei tule virhesanomaa, toiminto on valmis.

Dynamics NAV on rekisteröity ja valmis muodostamaan yhteyden esimerkiksi Cortana Intelligence- ja Power BI -palveluihin.

## <a name="see-also"></a>Katso myös
[Myynti- ja varastoennuste](ui-extensions-sales-forecast.md)  
[Omat Dynamics NAV -määritykset](setup.md)  

