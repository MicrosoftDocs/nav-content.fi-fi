---
title: "Käyttöomaisuuden poistaminen tai kuolettaminen"
description: "Määritä, miten toteutat käyttöomaisuutesi arvonalennukset, poistot tai kuoletukset."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: write down
ms.date: 06/02/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 582be0b55df7f3f353b5320080e56e4922cb789a
ms.contentlocale: fi-fi
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-depreciate-or-amortize-fixed-assets"></a>Toimintaohje: Käyttöomaisuuden poisto tai kuolettaminen
Poistoja käytetään jakamaan käyttöomaisuuden, esimerkiksi koneiden ja laitteiden, kustannuksia niiden poistoajalle. Jokaisen käyttöomaisuuserän osalta tulee määrittää, miten sille tehdään poistoja.  

 Poistot voi kirjata kahdella tavalla:  

* automaattisesti **Laske poisto** -eräajon avulla.  
* Manuaalisesti käyttöomaisuuden KP-päiväkirjan avulla.  

[!INCLUDE[d365fin](includes/d365fin_md.md)] voi laskea päivittäisen poiston, jolloin voit laskea poiston mille tahansa ajanjaksolle. Nykyisiä toiminnan tuloksia voi siis analysoida esimerkiksi kuukausittain, neljännesvuosittain tai vuosittain. Laskennassa käytetään 360 päivän vakiovuotta ja 30 päivän vakiokuukautta. Lisätietoja on kohdassa [Poistotavat](fa-depreciation-methods.md).  

Jos useat osastot käyttävät käyttöomaisuuserää, jaksottaiset poistot voidaan kohdistaa automaattisesti näille osastoille käyttäjäkohtaisen kohdistustaulukon mukaisesti.  

Virheellisiä poistotapahtumia voi peruuttaa **Peruuta KO-tapahtumat** -eräajolla. Oikean poistosumman voi kirjata tämän jälkeen suorittamalla uudelleen **Laske poisto** -eräajon. Virheet kirjataan korjattaessa KO-virhetapahtumiksi.  

Indeksointia käytetään muuttamaan arvoja yleisten hintatason muutosten mukaan. **Tee indeksimuutos KO:teen** -eräajoa voidaan käyttää poistosummien uudelleenlaskemiseen.  

## <a name="to-calculate-depreciation-automatically"></a>Poistojen laskeminen automaattisesti
**Laske poisto** -eräajon voi suorittaa kerran kuukaudessa tai valitsemanasi ajankohtana. Eräajo ei huomioi myytyjä tai suljettuja käyttöomaisuuseriä eikä käyttöomaisuuseriä, jotka eivät ole aktiivisia ja jotka käyttävät manuaalista poistomenetelmää.  

1. Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, syötä **Laske poisto** ja valitse sitten aiheeseen liittyvä linkki.  
2. Täytä tarvittavat kentät. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]  
3. Valitse **OK**-painike.  

    Eräajo laskee poiston ja luo rivejä käyttöomaisuuden KP-päiväkirjaan.  
4. Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, syötä **KO - KP-päiväkirjat** ja valitse sitten aiheeseen liittyvä linkki.  

    **Käyttöomaisuuden KP-päiväkirja** -ikkunan **Poistopäivien lukumäärä** -kentän avulla nähdään, kuinka monta poistopäivää on laskettu.  
5. Valitse **Kirjaa**-toiminto.  

## <a name="to-post-depreciation-manually-from-the-fixed-asset-gl-journal"></a>Poistojen kirjaaminen manuaalisesti käyttöomaisuuden KP-päiväkirjasta
1. Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, syötä **Käyttöomaisuuden KP-päiväkirja** ja valitse sitten aiheeseen liittyvä linkki.  
2. Luo alkuperäisen päiväkirjan rivi ja täytä kentät tarpeen mukaan.  
3. Valitse **KO:n kirjaustyyppi** -kentässä **Poisto**.  
4. Valitse **Syötä KO-vastatili** -toiminto. Toinen päiväkirjan rivi luodaan vastatilille, joka on määritetty poiston kirjaamista varten. Lisätietoja on "Käyttöomaisuuden kirjausryhmien määrittäminen" -osassa kohdassa [Toimintaohje: Käyttöomaisuuden yleisten tietojen määrittäminen](fa-how-setup-general.md).  
5. Valitse **Kotisivu**-välilehdessä **Kirjaa**, jolloin päiväkirja kirjataan.  

Jos summien kohdistamiseksi eri osastoille tai projekteille on määritetty käyttöomaisuuden kohdistusavaimia, summat kohdistetaan kirjaamisen aikana. Lisätietoja on kohdassa [Toimintaohje: Käyttöomaisuuden yleisten tietojen määrittäminen](fa-how-setup-general.md).  

## <a name="to-calculate-allocations-in-the-fixed-asset-gl-journal"></a>Käyttöomaisuuden KO-päiväkirjan kohdistusten laskeminen
Jos useat osastot käyttävät käyttöomaisuuserää, jaksottaiset poistot voidaan kohdistaa automaattisesti näille osastoille käyttäjäkohtaisen kohdistustaulukon mukaisesti.  

1. Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, syötä **Käyttöomaisuuden KP-päiväkirja** ja valitse sitten aiheeseen liittyvä linkki.  
2. Luo alkuperäinen rivi ja täytä kentät tarpeen mukaan.
3. Valitse **KO:n kirjaustyyppi** -kentässä **Kohdistus**.  
4. Valitse **Syötä KO-vastatili** -toiminto. Toinen päiväkirjan rivi luodaan vastatilille, joka on määritetty kohdistuksen kirjaamista varten.  
5. Valitse **Kotisivu**-välilehdessä **Kirjaa**, jolloin päiväkirja kirjataan.  

## <a name="use-duplication-lists-to-prepare-to-post-to-multiple-depreciation-books"></a>Valmistele useiden poistokirjojen kirjaaminen monistusluetteloiden avulla
Kun täytät poistokirjaan kirjattavat päiväkirjarivit, voit monistaa rivit erilliseen päiväkirjaan, josta ne voidaan kirjata eri poistokirjaan. Lisätietoja on "Tapahtumien kirjaaminen eri poistokirjoihin" -osassa.

1. Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, syötä **Poistokirjat** ja valitse sitten aiheeseen liittyvä linkki.  
2. Avaa poistokirja ja valitse **Osa monistusluettelosta** -valintaruutu.  

> [!IMPORTANT]  
>   Jos olet lisännyt valintamerkin **Käytä monistusluetteloa** -kenttään, älä käytä päiväkirjassa numerosarjaa. Tämä sen vuoksi, että käyttöomaisuuden KP-päiväkirjan numerosarjat ja käyttöomaisuuspäiväkirjan numerosarjat eivät ole samoja.  

## <a name="to-post-entries-to-different-depreciation-books"></a>Tapahtumien kirjaaminen eri poistokirjoihin
1. Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, syötä **Käyttöomaisuuden KP-päiväkirja** ja valitse sitten aiheeseen liittyvä linkki.  
2. Valitse **Käytä monistusluetteloa** -valintaruutu siinä päiväkirjassa, johon poisto kirjataan.  
3. Täytä tarvittavat jäljellä olevat kentät.  
4. Valitse **Kirjaa**-toiminto.  
5. Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, syötä **KO-päiväkirjat** ja valitse sitten aiheeseen liittyvä linkki.  

    > [!NOTE]  
>   **Käyttöomaisuuspäiväkirja**-ikkuna sisältää uusia rivejä eri poistokirjoille monistusluettelon mukaan.  
6. Tarkista rivit tai muokkaa niitä ja valitse sitten **Kirjaa**-toiminto.  

    > [!NOTE]  
>   Toinen tapa monistaa tapahtuma erilliseen kirjaan on syöttää poistokirjan koodi **Monista poistokirjaan** -kenttään silloin, kun päiväkirjariviä täytetään.  

Tapahtumia voidaan kopioida poistokirjasta toiseen käyttämällä **Kopioi poistokirja** -eräajoa. Eräajo luo päiväkirjarivejä päiväkirjan erään, jonka olet määrittänyt **KO-päiväkirjan asetukset** -ikkunassa poistokirjalle, johon haluat kopioida. Katso lisätietoja seuraavasta menettelystä.  

## <a name="to-copy-fixed-asset-ledger-entries-between-depreciation-books"></a>Käyttöomaisuustapahtumien kopioiminen poistokirjojen välillä
1. Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, syötä **Poistokirjat** ja valitse sitten aiheeseen liittyvä linkki.  
2. Avaa poistokirjan kortti ja valitse **Kopioi poistokirja** -toiminto.  
3. Täytä **Kopioi poistokirja** -ikkunassa tarvittavat kentät.  
4. Valitse **OK**-painike.  

Kopioidut rivit luodaan joko käyttöomaisuuden KP-päiväkirjassa tai käyttöomaisuuspäiväkirjassa sen mukaisesti, onko kopioitava poistokirja integroitu pääkirjanpitoon.  

## <a name="see-also"></a>Katso myös
[Käyttöomaisuus](fa-manage.md)  
[Käyttöomaisuuden määrittäminen](fa-setup.md)  
[Rahoitus](finance.md)  
[[!INCLUDE[d365fin](includes/d365fin_md.md)] -ohjelman käyttäminen](ui-work-product.md)  

