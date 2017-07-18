---
title: "Toimintaohje: Envestnet Yodlee -pankkisyötepalvelun määrittäminen"
author: SorenGP
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 270568214afd2ca8af15f0fa7640337c77ec2f1e
ms.contentlocale: fi-fi
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-set-up-the-envestnet-yodlee-bank-feeds-service"></a>Toimintaohje: Envestnet Yodlee -pankkisyötepalvelun määrittäminen
Voit tuoda pankistasi sähköisiä tiliotteita ja täyttää nopeasti **Maksujen täsmäytyskirjauskansio** -ikkunan maksujen kohdistamiseksi ja pankkitilin täsmäyttämiseksi. Lisätietoja on kohdassa [Maksujen kohdistaminen automaattisesti ja pankkitilien täsmäyttäminen](receivables-apply-payments-auto-reconcile-bank-accounts.md).

**Huomautus**: Envestnet Yodlee -pankkisyötepalvelu tai toisen palveluntarjoajan pankkisyötepalvelu ei ehkä ole käytettävissä järjestelmässäsi. Jos haluat käyttää pankkisyötepalvelua tiliotteiden tuomiseen, ota yhteys Microsoft-yhteistyökumppaniisi.

Kun pankkisyötepalvelu on otettu käyttöön, liittyvä pankkitili on linkitettävä siihen verkkopankkitiliin, josta syöte tulee. Voit linkittää pankkitilit verkkopankkitileihin seuraavissa erilaisissa skenaarioissa:

- Dynamics NAV -ohjelman verkkopankkitilille ei ole määritetty pankkitiliä. Tämän vuoksi luodaan pankkitili linkittämällä se verkkopankkitilistä.
- Dynamics NAV sisältää pankkitilin, jonka haluat linkittää verkkopankkitiliin.
- Linkitetyn pankkitilin linkitys on peruutettava, koska haluat lopettaa tilin pankkisyötepalvelun käyttämisen.
- Verkkopankkitilejä on muutettu, ja haluat päivittää Dynamics NAV -ohjelman pankkitilien tiedot.

Kun pankkisyötepalvelu on otettu käyttöön, voit määrittää pankkitilille uusien tiliotteiden automaattisen tuonnin **Maksujen täsmäytyskirjauskansio** -ikkunaan kahden tunnin välein. Niiden maksujen tapahtumia, jotka on jo kohdistettu ja/tai täsmäytetty **Maksujen täsmäytyskirjauskansio** -ikkunassa, ei tuoda. Lisätietoja on “Pankin tiliotteiden automaattisen tuonnin ottaminen käyttöön” -osassa.

**Huomautus**: Jos käytössä on yrityksen määrittämisen avustettu asennus, jotkin seuraavien toimenpiteiden yrityksen pankkitilin asennusvaiheet suoritetaan automaattisesti. Lisätietoja on kohdassa [Tervetuloa Dynamics NAV -ohjelmaan](across-get-started.md).

## <a name="to-enable-the-bank-feed-service"></a>Pankkisyötepalvelun ottaminen käyttöön
1. Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Pankkitilit** ja valitse sitten aiheeseen liittyvä linkki.
2. Avaa pankkisyötepalvelussa käytettävä pankkitili.
3. Valitse **Pankkitili**-ikkunan **Pankin tiliotteen tuontimuoto** -kenttään YODLEEBANKFEED.  

Pankkisyötepalvelu otetaan käyttöön, kun linkität pankkitilin siihen liittyvään verkkopankkitiliin. Tutustu seuraaviin toimiin.  

## <a name="to-create-a-new-linked-bank-account"></a>Uuden linkitetyn pankkitilin luominen
1. Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Pankkitilit** ja valitse sitten aiheeseen liittyvä linkki.
2. Valitse asianmukainen pankkitili ja valitse sitten **Luo uusi linkitetty pankkitili**. Hetken kuluttua näyttöön avautuu **Pankkitilin linkitys** -ikkuna.

    **Huomautus**: Tässä ikkunassa näytetään Envestnet Yodlee -pankkisyötepalvelun todellinen verkkosivu. Ikkunassa näkyvät termit ja toiminnot eivät ehkä vastaa tämän ohjeaiheen ohjeita.  
3. Käytä **Verkkopankkitilin linkitys** -ikkunan **Linkitä tili** -ruudun hakutoimintoa, kun etsit pankin, jossa sinulla on vähintään yksi verkkopankkitili.
4. Valitse pankin nimi. **Kirjaudu sisään** -ruutu avautuu.
5. Syötä käyttäjätunnus ja salasana, jota käytät kirjautuessasi verkkopankkiin, ja valitse sitten **Seuraava**-painike.  
6. Pankkisyötepalvelu valmistelee määritetyn pankin ensimmäisen verkkopankkitiliin ja Dynamics NAV -ohjelman uuden pankkitilin linkityksen.

    **Huomautus**: Jos sinulla on pankissa useita verkkopankkitilejä, luo näille verkkopankkitileille lisäpankkitilit Dynamics NAV -ohjelmaan. Katso vaiheet 8–10.

    Kun prosessi on valmis, pankin nimi näkyy **Linkitetty**-välilehden **Omat tilit**-ruudussa. Sulkeissa oleva luku osoittaa linkitettyjen verkkopankkien määrän.
7. Valitse **OK**-painike.

    Jos linkitettyjä verkkopankkitilejä on vain yksi, näyttöön avautuu uuden pankkitilin **Pankkitilin kortti** -ikkuna, johon on täytetty verkkopankkitilin nimi. Nyt pankkitilin linkitystehtävä on valmis. Jäljellä on enää pankkitilin määrittäminen. Lisätietoja on kohdassa [Toimintaohje: Pankkitilien määrittäminen](bank-how-setup-bank-accounts.md).

    Jos linkitettyjä verkkopankkitilejä on useita, näyttöön avautuu **Pankkitilin linkitys** -ikkuna, joka sisältää ne lisäverkkopankkitilit, joita ei ole vielä linkitetty Dynamics NAV -ohjelman pankkitileihin. Noudata tällaisessa tapauksessa seuraavaa vaihetta.  
8. Valitse **Pankkitilin linkitys** -ikkunassa verkkopankkitilin rivi ja valitse sitten **Linkitä uuteen pankkitiliin** -toiminto.

    Näyttöön avautuu uuden pankkitilin **Pankkitilin kortti** -ikkuna, johon on täytetty verkkopankkitilin nimi.

    Jos Dynamics NAV -ohjelmassa on jo pankkitili, johon haluat linkittää lisäverkkopankkitilin, noudata seuraavia ohjeita.  
9. Valitse **Pankkitilin linkitys** -ikkunassa verkkopankkitilin rivi ja valitse sitten **Linkitä olemassa olevaan pankkitiliin** -toiminto.
10. Valitse **Pankkitililuettelo**-ikkunassa pankkitili, johon linkitys tehdään, ja valitse sitten **OK**-painike.

## <a name="to-link-a-bank-account-to-an-online-bank-account"></a>Pankkitilin linkittäminen verkkopankkitiliin
1. Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Pankkitilit** ja valitse sitten aiheeseen liittyvä linkki.
2. Valitse sen pankkitilin rivi, jota ei ole linkitetty verkkopankkitiliin, ja valitse sitten **Linkitä verkkopankkitiliin** -toiminto. Näyttöön avautuu **Verkkopankkitilin linkitys** -ikkuna, joka sisältää **Linkitä tili** -ruudussa annetun pankin nimen.
3. Valitse pankin nimi. **Kirjaudu sisään** -ruutu avautuu.
4. Syötä käyttäjätunnus ja salasana, jota käytät kirjautuessasi verkkopankkiin, ja valitse sitten **Seuraava**-painike.

    Pankkisyötepalvelu valmistelee Dynamics NAV -ohjelman pankkitilin ja liittyvän verkkopankkitilin linkityksen.

    Kun prosessi on valmis, pankin nimi näkyy **Linkitetty**-välilehden **Omat tilit**-ruudussa. Jos pankissa on useita pankkitilejä, vain vaiheessa 2 valittu pankkitili linkitetään.
5. Valitse **OK**-painike.

**Pankkitililuettelo**-ikkunan **Linkitetty**-valintaruutu valitaan.

## <a name="to-unlink-a-bank-account"></a>Pankkitilin linkityksen poistaminen
1. Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Pankkitilit** ja valitse sitten aiheeseen liittyvä linkki.  
2. Valitse sen linkitetyn pankkitilin rivi, jonka linkityksen liittyvään verkkopankkitiliin haluat poistaa. Valitse sitten **Poista verkkopankkitilin linkitys** -toiminto.

**Huomautus**: Jos valitset vahvistusvalintaikkunassa **Kyllä**, verkkopankkitilin linkki poistetaan ja sisäänkirjaustiedot poistetaan. Voit linkittää pankkitilin uudelleen verkkopankkitiliin kirjautumalla pankkiin sisään uudelleen. Lisätietoja on “Pankkitilin linkittäminen verkkopankkitiliin“ -osassa.

## <a name="to-update-bank-account-linking"></a>Pankkitilin linkityksen päivittäminen
1. Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Pankkitilit** ja valitse sitten aiheeseen liittyvä linkki.
2. Valitse asianmukainen pankkitili ja valitse sitten **Päivitä pankkitilien linkitys** -toiminto.

Jos **Pankkitililuettelo**-ikkunan linkitetyissä pankkitileissä esiintyy ongelmia, näyttöön avautuu **Pankkitilin linkitys** -ikkuna, jossa kerrotaan pankkitili, jota ongelmat koskevat. Ongelmien ratkaiseminen tapahtuu parhaiten poistamalla verkkopankkitilin linkitys ja luomalla linkitys uudelleen. Lisätietoja on “Pankkitilin linkittäminen verkkopankkitiliin“ -osassa.

## <a name="to-enable-automatic-import-of-bank-statements"></a>Pankin tiliotteiden automaattisen tuonnin ottaminen käyttöön
1. Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Pankkitilit** ja valitse sitten aiheeseen liittyvä linkki.
2. Valitse linkitetyn pankkitilin rivi ja valitse sitten **Pankin tiliotteen automaattisen tuonnin asetukset** -toiminto.
3. Määritä **Pankin tiliotteen automaattisen tuonnin asetukset** -ikkunan **Sisällytettyjen päivien lukumäärä** -kentässä, miltä kaukaiselta ajalta uudet pankkitapahtumat haetaan.

    **Huomautus**: Suosittelemme arvoksi 7 päivää tai enemmän.
4. Valitse **Käytössä**-valintaruutu.  
**Maksujen täsmäytyskirjauskansio** -ikkunaan täytetään nyt tunneittain kaikki uudet verkkopankissa tehdyt maksut.

**Huomautus**: Niiden maksujen tapahtumia, jotka on jo kohdistettu ja/tai täsmäytetty **Maksujen täsmäytyskirjauskansio** -ikkunassa, ei tuoda.

## <a name="see-also"></a>Katso myös  
[Pankkitoiminnan määrittäminen](bank-setup-banking.md)  
[Pankkitilien hallinta](bank-manage-bank-accounts.md)  
[Maksujen kohdistaminen automaattisesti ja pankkitilien täsmäyttäminen](receivables-apply-payments-auto-reconcile-bank-accounts.md)  
[Dynamics NAV -ohjelman mukauttaminen laajennusten avulla](ui-extensions.md)

