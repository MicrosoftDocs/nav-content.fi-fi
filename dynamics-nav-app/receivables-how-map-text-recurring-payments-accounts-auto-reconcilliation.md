---
title: "Toimintaohje: toistuvien maksujen tekstin yhdistäminen tileihin automaattisen täsmäytyksen suorittamiseksi"
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
ms.openlocfilehash: 7f9bf8b0550f7da1cced995234e15ad7aab484ba
ms.contentlocale: fi-fi
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-map-text-on-recurring-payments-to-accounts-for-automatic-reconciliation"></a>Toimintaohje: toistuvien maksujen tekstin yhdistäminen tileihin automaattisen täsmäytyksen suorittamiseksi
**Tekstin yhdistäminen tiliin** -ikkunassa, joka avataan **Maksujen täsmäytyskirjauskansio** -ikkunasta, voit määrittää maksujen tekstin kohdistukset ja tietyt debet-, kredit- ja kirjanpidon vastatilit siten, että nämä maksut kirjataan tietyille tileille, jotta nämä maksut kirjataan tietyille tileille, kun kirjaat maksun täsmäytyksen päiväkirjan.

**Huomautus**: Tämä ohjeaihe koskee myös **Linkitä teksti tiliin** -toiminnon käyttämistä saapuvasta asiakirjatietueesta avustettaessa niiden sähköisten asiakirjojen muuntamisessa, jotka on vastaanotettu ulkoisista palveluista Dynamics NAV -ohjelman asiakirjoiksi. Lisätietoja on kohdassa [Toimintaohje: Käytä OCR:ää muuntamaan PDF- ja kuvatiedostoja sähköisiksi asiakirjoiksi](across-how-use-ocr-pdf-images-files.md).   

Vastaava toiminto on käytettävissä, kun maksujen täsmäytyskirjauskansion rivien ylimääräisiä summia täsmäytetään ad hoc. Lisätietoja on kohdassa [Toimintaohje: Niiden maksujen täsmäyttäminen, joita ei voi kohdistaa automaattisesti](receivables-how-reconcile-payments-cannot-apply-auto.md).

Maksuja, jotka perustuvat tekstistä tiliin yhdistämiseen, ei käytetä avoimiin tapahtumiin vaan ne kirjataan tietyille tileille pankkitilitapahtumien lisäksi. Näin ollen tekstin ja tilin välinen yhdistäminen sopii toistuviin saatuihin tuloihin tai kuluihin, kuten usein tapahtuvat auton polttoaineen ostot tai pankin kulut ja korko, jotka tapahtuvat pankin tiliotteessa säännöllisesti ja jotka eivät tarvitse niihin liittyvää liiketoiminta-asiakirjaa. Lisätietoja on tämän ohjeaiheen “Esimerkki – tekstin ja tilin yhdistäminen polttoaineen kuluissa” -osassa.

**Huomautus**: Täsmäytyksen päiväkirjarivien maksut asetetaan kirjattaviksi tekstistä tilien yhdistäminen -asetuksen mukaan, jos automaattinen kohdistus -toiminto voi tarjota kohdistuksen varmuudeksi vain **Pieni** tai **Keskisuuri**. Jos automaattisen sovellusfunktion avulla saadaan vastaavuus Suuri, maksu kohdistetaan automaattisesti yhteen tai useaan avoimeen tapahtumaan tai hyvityslaskuun, eikä maksua kirjata määritetyille tileille **Tekstin yhdistäminen tiliin** -ikkunassa. Toisin sanoen kohdistuksen **Suuri**-vastaavuus kumoaa tekstistä tiliin yhdistämisen.

Maksun täsmäytyksen päiväkirjarivillä, jossa maksu on asetettu kirjatuksi tekstistä tiliin yhdistäminen -asetuksen mukaisesti, **Vastaavuuden luotettavuus** -kentässä on **Suuri – tekstin ja tilin välinen yhdistäminen**, ja **Tilityyppi**- sekä **Tilinumero**-kenttä. sisältävät yhdistetyt tilit.

## <a name="to-map-text-on-recurring-payments-to-accounts-for-automatic-reconciliation"></a>Toistuvien maksujen tekstin yhdistäminen tileihin automaattisen täsmäytyksen suorittamiseksi
1. Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Maksujen täsmäytyskirjauskansiot** ja valitse sitten aiheeseen liittyvä linkki.
2. Avaa maksun täsmäytyksen päiväkirja. Lisätietoja on kohdassa [Toimintaohje: Maksujen täsmäyttäminen käyttämällä automaattista kohdistusta](receivables-how-reconcile-payments-auto-application.md).
3. Valitse **Linkitä teksti tiliin** -toiminto. **Tekstin yhdistäminen tiliin** -ikkuna avautuu.
4. Syötä **Tekstin linkitys** -kenttään mikä tahansa teksti, joka näkyy maksuissa, jotka haluat kirjata tietyille tileille kohdistamatta avoimeen tapahtumaan. Koodissa voi olla enintään 50 merkkiä.

    **Huomautus**: Jos muita maksuja tai saapuvia asiakirjoja, joissa on kyseinen linkitettävä teksti, ei ole, tekstin yhdistäminen tiliin tapahtuu, vaikka maksun tai saapuvan asiakirjan tekstistä vain osa on linkitettävänä tekstinä.
5. **Toimittajan nro** -kenttään syötetään sen toimittajan numero, jolle yhdistettävää tekstiä sisältävät saapuvat asiakirjat luodaan tai johon maksut kirjataan. Lisätietoja on kohdassa [Toimintaohje: Käytä OCR:ää muuntamaan PDF- ja kuvatiedostoja sähköisiksi asiakirjoiksi](across-how-use-ocr-pdf-images-files.md).      
6. Syötä **Debet-tilin numero** -kenttään tili johon tekstin linkityksen sisältävät maksut kirjataan, jos ne ovat saapuvia maksuja. Saapuvien maksujen arvon merkki **Tiliotteen summa** -kentässä on positiivinen.
7. Syötä **Kredit-tilin numero** -kenttään tili johon tekstin linkityksen sisältävät maksut kirjataan, jos ne ovat lähteviä maksuja. Lähtevien maksujen arvon merkki **Tiliotteen summa** -kentässä on negatiivinen.
8. Määritä **Saldon lähteen tyyppi** -kenttään, kirjataanko maksu kirjanpitotilille vai asiakkaan tai toimittajan tilille.
9. Määritä **Saldon lähteen numero** -kenttään **Saldon lähteen tyyppi** -kentän valinnan mukaisesti tili, jolle maksu kirjataan.
10. Toista vaiheet 4-8 kaikkien niiden maksujen tekstien osalta, joille haluat yhdistää tilit suoraa kirjausta varten soveltamatta.

Seuraavan kerran, kun tuot pankin tiliotetiedoston tai valitset **Kohdista automaattisesti** -toiminnon **Maksujen täsmäytyskirjauskansio** -ikkunassa, tietyn yhdistystekstin sisältävät päiväkirjan rivit sisältävät yhdistetyt tilit **Tilityyppi**- ja **Tilinumero**-. -kentät. **Vastaavuuden luotettavuus** -kenttä sisältää **Suuri - Tekstin yhdistäminen tiliin** -tekstin. Tämä on edellytys sille, että automaattinen kohdistustoiminto antaa vastaavuudeksi **Matala** tai **Keskisuuri**.

##<a name="example-text-to-account-mapping-for-fuel-expense"></a>Esimerkki: Tekstin ja tilin yhdistäminen polttoaineen kuluun

Kirjataksesi aina Shell-huoltoasemilla kertyneet polttoainekulut kirjanpitoon polttoaineelle (tili 8510), täytä rivi **Tekstin yhdistäminen tiliin** -ikkunassa seuraavasti.

|Tekstin linkitys |Debet-tilin Nro |Kredit-tilin Nro |Saldo Lähdetyyppi |Saldo Lähteen nro |
|-------------|---------------|----------------|-----------------|----------------|
|Hylly |TYHJÄ |8510 |KP-tili|TYHJÄ|

**Vihje**: Lisätietoja kenttien ja sarakkeiden käsittelemisestä on kohdassa [Dynamics NAV -ohjelman käyttäminen ](ui-work-product.md). Lisätietoja tiettyjen sivujen löytämisestä on kohdassa [Haku](ui-search.md).

## <a name="see-also"></a>Katso myös
[Myyntisaamisten hallinta](receivables-manage-receivables.md)  
[Myynnin hallinta](sales-manage-sales.md)  
[Toimintaohje: Envestnet Yodlee -pankkisyötepalvelun määrittäminen](bank-how-setup-bank-statement-service.md)  
[Dynamics NAV -ohjelman mukauttaminen laajennusten avulla](ui-extensions.md)

