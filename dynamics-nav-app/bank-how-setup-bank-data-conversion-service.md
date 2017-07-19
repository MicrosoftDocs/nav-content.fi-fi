---
title: "Toimintaohje: Pankkitietojen muuntopalvelun määrittäminen"
author: SorenGP
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 801e2abee52ec9804028a797e4f330b5e080549a
ms.contentlocale: fi-fi
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-set-up-the-bank-data-conversion-service"></a>Toimintaohje: Pankkitietojen muuntopalvelun määrittäminen
Voit viedä maksurivit **Maksupäiväkirja**-ikkunasta tietovirtaan, joka ladataan pankkiin automaattista käsittelyä varten. Sähköisiä maksuja ei siis tarvitse tehdä yksitellen. Lisätietoja on kohdassa [Toimintaohje: Maksujen vieminen pankkitiedostoon](payables-how-export-payments-bank-file.md).

Yleiset palvelut on yhdistetty Dynamics NAV -ohjelmaan ja valmis käyttöä varten. Sen avulla maksutiedot muunnetaan mihin tahansa pankkisi vaatimaan tietomuotoon.

Envestnetin pankkitietojen syötepalvelun lisäksi voit käyttää myös pankkitietojen muuntopalvelua, kun haluat muuntaa pankista saamasi tiliotetiedoston tietovirraksi, jonka voit tämän jälkeen tuoda Dynamics NAV -ohjelmaan. Lisätietoja on kohdassa [Toimintaohje: Maksujen kohdistaminen automaattisesti ja pankkitilien täsmäyttäminen](receivables-apply-payments-auto-reconcile-bank-accounts.md).

**Huomautus**: Pankkitietojen muuntopalvelu saattaa rajoittaa rivimäärää, joka voidaan viedä yhdessä tiedostossa. Näyttöön tulee virhesanoma, jos raja ylitetään. On suositeltavaa, että tiliotetiedostot sisältävät enintään 1 000 riviä, koska pankkitietojen muuntopalvelun käsittelyaika saattaa muuten kasvaa merkittävästi.

## <a name="to-sign-your-company-up-for-the-bank-data-conversion-service"></a>Yrityksen määrittäminen pankkitietojen muuntopalvelun käyttäjäksi
1. Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Pankkitiet. muuntopalvelun asetukset** ja valitse sitten aiheeseen liittyvä linkki.  
2. **Pankkitiet. muuntopalvelun asetukset** -ikkuna avautuu ja siinä on kolme esitäytettyä kenttää sisältäen pankkitietojen muuntopalvelun tarjoajan asiaankuuluvat URL-osoitteet.

    **Huomautus**: CRONUS Finland Oy -esittelytietokannan Käyttäjänimi- ja Salasana-kenttä esitäytetään kirjautumisen esittelytiedoilla, jotka vaihdat yrityksen todellisiksi tiedoiksi, kun rekisteröidyt pankkitietojen muunnospalveluun.
3. Valitse **Rekisteröitymisen URL-osoite** -kentässä selaimen painike palveluntarjoajan rekisteröitymissivun avaamiseksi.  
4. Kirjoita pankkitietojen palvelujen tarjoajan rekisteröitymissivu, kirjoita yrityksesi rekisteröitymistä vastaava käyttäjänimi ja salasana ja suorita rekisteröitymisprosessi palveluntarjoajan ohjeiden mukaisesti.

    Yrityksesi on nyt rekisteröitynyt pankkitietojen muuntopalveluun. Jatka kirjoittamalla käyttäjänimi ja salasana, jotka olet määrittänyt palvelulle vastaavissa Dynamics NAV -ohjelman asetuskentissä.
5. Kirjoita **Pankkitiet. muuntopalvelun asetukset** -ikkunassa **Käyttäjänimi**-kenttään sama arvo, jonka kirjoitit kirjautumisnimeksi palveluntarjoajan sivulla vaiheessa 4.
6. Kirjoita **Salasana**-kenttään sama arvo, jonka kirjoitit **Salasana**-kenttään palveluntarjoajan sivulla vaiheessa 4.

## <a name="to-encrypt-your-login-information"></a>Kirjautumistietojen salaaminen
Suosittelemme, että suojaat **Pankkitiet. muuntopalvelun asetukset** -ikkunaan kirjoittamasi kirjautumistiedot. Dynamics NAV -palvelimen tiedot voi salata luomalla uusia salausavaimia tai tuomalla olemassa olevia salausavaimia, jotka otetaan käyttöön tietokantayhteyden muodostavassa Dynamics NAV -palvelimessa.

1. Valitse **Pankkitiet. muuntopalvelun asetukset** -ikkunassa **Salauksen hallinta** -toiminto.
2. Ota tietojen salaus käyttöön **Tietojen salauksen hallinta** -ikkunassa.

##<a name="to-view-or-update-the-list-of-currently-supported-bank-data-formats"></a>Tällä hetkellä tuettujen pankin tietomuotojen luettelon tarkastelu tai päivitys
1. Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Pankkitiet. muuntopalvelun asetukset** ja valitse sitten aiheeseen liittyvä linkki.
2. Valitse **Pankkitiet. muuntopalvelun asetukset** -ikkunassa **Pankin nimi - tietojen muuntoluettelo** -toiminto, jolloin avautuu muuntopalvelun tukemien pankin tietomuotojen luettelo.
3. Valitse **Pankin nimi - tietojen muuntamisen luettelo** -sivulla **Päivitä pankkien nimien luettelo** -toiminto.

Pankkitietojen muuntopalvelun tukemien pankin tietomuotojen luettelo on nyt päivitetty. Tämä on luettelo pankin nimistä suodatettuna maan/alueen mukaan, jotka voit valita **Pankin nimi - tietojen muuntaminen** -kentän **Pankkitilin kortti** -ikkunassa.

**Huomautus**: Tuettujen pankin tietomuotojen päivitys tapahtuu myös silloin, kun valitset tai kirjoitat arvon **Pankin nimi - tietojen muuntaminen** -kenttään pankkitilillä.

Olet on nyt kirjautunut pankkitietojen muuntopalveluun. Jatka kirjautumistietojen käyttämistä jokaisella pankkitilillä, joka tulee käyttämään palvelua.

## <a name="to-set-up-bank-accounts-to-use-the-bank-data-conversion-service"></a>Pankkitilien määrittäminen pankkitietojen muuntopalvelun käyttämistä varten
1. Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Pankkitilit** ja valitse sitten aiheeseen liittyvä linkki.
2. Avaa sen pankkitilin kortti, josta viet tai johon tuot pankkitiedostot pankkitietojen muuntopalvelun avulla.
3. Määritä maksun vienti valitsemalla **Siirto**-pikavälilehden **Maksun vientimuoto** -kentässä **Pankkitietojen muuntopalvelu - hyvityksen siirto**.
4. Kirjoita tai valitse **Pankin nimi - tietojen muuntaminen** -kenttään pankin tietojen muodon nimi, jonka määritit vaiheen 4 “Kirjautuminen pankkitietojen muunnospalveluun” -osassa.
5. Toista vaiheet 1–4 muissa pankkitileissä, jotka käyttävät pankkitietojen muuntopalvelua.

## <a name="see-also"></a>Katso myös  
[Pankkitoiminnan määrittäminen](bank-setup-banking.md)  
[Pankkitilien hallinta](bank-manage-bank-accounts.md)

