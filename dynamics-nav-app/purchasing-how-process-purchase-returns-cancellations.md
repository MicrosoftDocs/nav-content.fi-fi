---
title: "Toimintaohje: tavaran palautuksen tai peruutuksen käsittely"
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
ms.openlocfilehash: 94067fb3d10975c1db29d2e3f1d5d6373fcbf9f2
ms.contentlocale: fi-fi
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-process-purchase-returns-or-cancellations"></a>Toimintaohje: tavaran palautuksen tai peruutuksen käsittely
Jos haluat palauttaa nimikkeitä toimittajalle tai peruuttaa ostamiasi palveluita, voit luoda ja kirjata ostohyvityslaskun, joka määrittää pyydetyn muutoksen alkuperäisen ostolaskun suhteen. Voit lisätä oikean ostolaskun tiedot luomalla ostohyvityslaskun kirjatusta ostolaskusta tai käyttämällä kopiointitoimintoa.

Yleensä toimittajan lähettämän hyvityslaskun jälkeen luodaan ostohyvityslasku. Ostohyvityslasku toimii sisäisenä asiakirjana hyvityslaskuprosessissa kirjanpitotarkoituksessa.

Muutokset voivat liittyä alkuperäisen ostolaskun kaikkiin tuotteisiin tai vain joihinkin tuotteisiin. Näin ollen voit palauttaa osittain vastaanotetut nimikkeet tai vaatia vastaanotettujen palvelujen osittaista korvaamista. Tässä tapauksessa sinun täytyy muokata kopioituja ostolaskun tietoja.

Alkuperäisen kirjatun ostolaskun lisäksi voit kohdistaa ostohyvityslaskun muihin ostolaskuihin, kuten esimerkiksi toiseen kirjattuun ostolaskuun, koska olet palauttamassa tämän laskun kanssa toimitettuja nimikkeitä.

## <a name="to-create-a-purchase-credit-memo-from-a-posted-purchase-invoice"></a>Ostohyvityslaskun luominen kirjatusta ostolaskusta
1. Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Ostohyvityslaskut** ja valitse sitten aiheeseen liittyvä linkki.  
2. Valitse **Kirjatut ostolaskut** -ikkunassa kirjattu ostolasku, jonka haluat peruuttaa, ja valitse sitten **Luo korjaava hyvityslasku** -toiminto.

    Useimpiin ostohyvityslaskun otsikon kenttiin täytetään kirjatun ostolaskun tiedot. Voit muokata kaikkia kenttiä, kuten esimerkiksi palautussopimusta vastaavia uusia tietoja.
3. Muokkaa sopimuksen mukaan rivien tietoja, kuten palautettujen nimikkeiden määrää tai hyvitettävää summaa.
4. Valitse **Kohdista tapahtumat** -toiminto.
5. Valitse **Kohdista toimittajatapaht.** -ikkunassa rivi, joka sisältää ostohyvityslaskuun kohdistettavan kirjatun ostoasiakirjan. Valitse sitten **Kohdistetaan tunnisteeseen** -toiminto. Ostohyvityslaskun numero lisätään **Kohdistetaan tunnisteeseen** -kenttään.
6. Syötä **Kohdistettava summa** -kenttään kohdistettava summa, jos se on pienempi kuin alkuperäinen summa.

    **Kohdista toimittajatapaht.** -ikkunan alaosassa näkyy kokonaissumma, joka kohdistetaan kaikkien mukaan kuuluvien tapahtumien peruuttamiseksi, kun **Saldo**-kentän arvo on nolla.
7. Valitse **OK**-painike. Kun ostohyvityslasku kirjataan, se kohdistetaan määritettyihin kirjattuihin ostoasiakirjoihin.

    Kun olet luonut tarvittavat ostohyvityslaskun rivit tai muokannut niitä ja yksi tai useita sovelluksia on määritetty, voit siirtyä kirjaamaan ostohyvityslaskun.
8. Valitse **Kirjaa**-toiminto.

Tiliöidyt ostolaskut, joita käytät hyvityslaskuun, on nyt kumottu. Jos olet jo maksanut alkuperäisen laskun, toimittajan pitäisi nyt hyvittää maksu sinulle. Jos hyvityslasku on vain osalle alkuperäisen laskun tuotetta, voit maksaa vain alkuperäisen ostolaskun jäljellä olevan summan sen sulkemiseksi.

Ostohyvityslasku poistetaan ja korvataan uudella kirjattujen ostohyvityslaskujen luettelon asiakirjalla.

## <a name="to-create-a-purchase-credit-memo-from-scratch"></a>Uuden ostohyvityslaskun luominen alusta alkaen
1. Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Kirjatut ostolaskut** ja valitse sitten aiheeseen liittyvä linkki.
2. Avaa uusi tyhjä ostohyvityslasku valitsemalla **Uusi**-toiminto.
3. Syötä **Toimittaja**-kenttään nykyisen toimittajan nimi.
4. Valitse **Kopioi asiakirja** -toiminto.
5. Valitse **Kopioi ostoasiakirja** -ikkunan **Asiakirjan tyyppi** -kentässä **Kirjattu lasku**.
6. Valitse **Asiakirjan nro** -kenttä, jos haluat avata **Kirjatut ostolaskut** -ikkunan, ja valitse sitten peruutettavat rivit sisältävä kirjattu ostolasku.
7. Valitse **Laske rivit uudelleen** -valintaruutu, jos haluat päivittää kopioidut kirjatut ostolaskurivit nimikkeen hinta- ja yksikkökustannusten muutoksilla, jotka ovat tapahtuneet laskun kirjaamisen jälkeen.
8. Valitse **OK**-painike. Kopioidut laskurivit lisätään ostohyvityslaskuun.
9. Täytä ostohyvityslasku tämän ohjeaiheen "Ostohyvityslaskun luominen kirjatusta ostolaskusta" -osassa esitetyllä tavalla.

## <a name="see-also"></a>Katso myös
[Ostojen hallinta](purchasing-manage-purchasing.md)  
[Toimintaohje: Ostojen kirjaus](purchasing-how-record-purchases.md)  

