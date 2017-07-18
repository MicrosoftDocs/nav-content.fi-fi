---
title: "Toimintaohje: myynnin palautuksen tai peruutuksen käsittely"
author: SorenGP
ms.custom: na
ms.date: 11/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 92b65379f2ec633712a2b2c0f06615c6de61cc6e
ms.contentlocale: fi-fi
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-process-sales-returns-or-cancellations"></a>Toimintaohje: myynnin palautuksen tai peruutuksen käsittely
Jos asiakas haluaa palauttaa myymiäsi nimikkeitä tai saada hyvitystä myymiisi palveluihin, joista olet saanut maksun, täytyy luoda ja kirjata myyntihyvityslaskun, joka määrittää pyydetyn muutoksen. Voit lisätä oikean myyntilaskun tiedot luomalla myyntihyvityslaskun kirjatusta myyntilaskusta tai käyttämällä kopiointitoimintoa.

Alkuperäisen kirjatun myyntilaskun lisäksi voit kohdistaa myyntihyvityslaskun muihin myyntilaskuihin, kuten esimerkiksi toiseen kirjattuun myyntilaskuun, koska asiakas on myös palauttamassa tämän laskun kanssa toimitettuja nimikkeitä.

Palautus tai hyvitys voi liittyä vain joihinkin alkuperäisen myyntilaskun nimikkeisiin tai palveluihin. Tällöin myyntihyvityslaskun riveillä olevia tietoja on muokattava. Myyntihyvityslaskun kirjaamisen yhteydessä myyntiasiakirjat, joihin muutos vaikuttaa, peruutetaan. Tämän jälkeen asiakkaalle voidaan luoda hyvitysmaksu.

Voit lähettää kirjatun myyntihyvityslaskun asiakkaalle ja vahvistaa palautuksen tai peruutuksen ja kertoa, että liittyvä arvo korvataan, esimerkiksi silloin, kun nimikkeet palautetaan.

## <a name="to-create-a-sales-credit-memo-from-a-posted-sales-invoice"></a>Myyntihyvityslaskun luominen kirjatusta myyntilaskusta
1. Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Kirjatut myyntilaskut** ja valitse sitten aiheeseen liittyvä linkki.  
2. Valitse **Kirjatut myyntilaskut** -ikkunassa kirjattu myyntilasku, jonka haluat peruuttaa, ja valitse sitten **Luo korjaava hyvityslasku** -toiminto.

    Useimpiin myyntihyvityslaskun otsikon kenttiin täytetään kirjatun myyntilaskun tiedot. Voit muokata kaikkia kenttiä, kuten esimerkiksi palautussopimusta vastaavia uusia tietoja.
3. Muokkaa sopimuksen mukaan rivien tietoja, kuten palautettujen nimikkeiden määrää tai hyvitettävää summaa.
4. Valitse **Kohdista tapahtumat** -toiminto.
5. Valitse **Kohdista asiakastapahtumat** -ikkunassa rivi, joka sisältää myyntihyvityslaskuun kohdistettavan kirjatun myyntiasiakirjan. Valitse sitten **Kohdistetaan tunnisteeseen** -toiminto.

    Myyntihyvityslaskun numero lisätään **Kohdistetaan tunnisteeseen** -kenttään.  
6. Syötä **Kohdistettava summa** -kenttään kohdistettava summa, jos se on pienempi kuin alkuperäinen summa.

    **Kohdista asiakastapahtumat** -ikkunan alaosassa näkyy kokonaissumma, joka kohdistetaan kaikkien mukaan kuuluvien tapahtumien peruuttamiseksi, kun **Saldo**-kentän arvo on nolla.  
7. Valitse **OK**-painike. Kun myyntihyvityslasku kirjataan, se kohdistetaan määritettyihin kirjattuihin myyntiasiakirjoihin.

    Kun olet luonut tarvittavat ostohyvityslaskun rivit tai muokannut niitä ja yksi tai useita sovelluksia on määritetty, voit siirtyä kirjaamaan myyntihyvityslaskun.
8. Valitse **Kirjaa ja lähetä** -toiminto.

**Kirjaa ja lähettää vahvistuksen** -valintaikkuna avautuu, jossa näkyy suositeltu tapa lähettää asiakkaalle. Voit muuttaa lähetysmenetelmän valitsemalla **Lähetä asiakirja kohteeseen** -kentän valintapainikkeen. Lisätietoja on kohdassa [Toimintaohje: Asiakirjan lähetysprofiilien määrittäminen](sales-how-setup-document-send-profiles.md).

Kirjatut myyntiasiakirjat, jotka kohdistettiin hyvityslaskuun, on nyt peruutettu, ja asiakkaalle voidaan luoda palautusmaksu. Myyntihyvityslasku poistetaan ja korvataan uudella kirjattujen myyntihyvityslaskujen luettelon asiakirjalla.

## <a name="to-create-a-sales-credit-memo-from-scratch"></a>Uuden myyntihyvityslaskun luominen alusta alkaen
1. Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Kirjatut myyntilaskut** ja valitse sitten aiheeseen liittyvä linkki.
2. Avaa uusi tyhjä myyntihyvityslasku valitsemalla **Uusi**-toiminto.
3. Syötä **Asiakas**-kenttään nykyisen asiakkaan nimi.
4. Valitse **Kopioi asiakirja** -toiminto.
5. Valitse **Kopioi myyntiasiakirja** -ikkunan **Asiakirjan tyyppi** -kentässä **Kirjattu lasku**.
6. Valitse **Asiakirjan nro** -kenttä, jos haluat avata **Kirjatut myyntilaskut** -ikkunan, ja valitse sitten peruutettavat rivit sisältävä kirjattu myyntilasku.
7. Valitse **Laske rivit uudelleen** -valintaruutu, jos haluat päivittää kopioidut kirjatut myyntilaskurivit nimikkeen hinta- ja yksikkökustannusten muutoksilla, jotka ovat tapahtuneet laskun kirjaamisen jälkeen.
8. Valitse **OK**-painike. Kopioidut laskurivit lisätään myyntihyvityslaskuun.
9. Täytä myyntihyvityslasku tämän ohjeaiheen "Myyntihyvityslaskun luominen kirjatusta myyntilaskusta" -osassa esitetyllä tavalla.

## <a name="see-also"></a>Katso myös  
[Myynnin hallinta](sales-manage-sales.md)  
[Myynnin määrittäminen](sales-setup-sales.md)  
[Toimintaohje: Asiakirjojen lähettäminen sähköpostitse](ui-how-send-documents-email.md)  
[Dynamics NAV -ohjelman käyttäminen](ui-work-product.md)

