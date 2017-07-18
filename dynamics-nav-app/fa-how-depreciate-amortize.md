---
title: "Toimintaohje: Käyttöomaisuuden poisto tai kuolettaminen"
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
ms.openlocfilehash: af71f30681d436ed5da1cd6cb3c2e13f86558631
ms.contentlocale: fi-fi
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-depreciate-or-amortize-fixed-assets"></a>Toimintaohje: Käyttöomaisuuden poisto tai kuolettaminen
Poistoja käytetään jakamaan käyttöomaisuuden, esimerkiksi koneiden ja laitteiden, kustannuksia niiden poistoajalle. Jokaisen käyttöomaisuuserän osalta tulee määrittää, miten sille tehdään poistoja.  

 Poistot voi kirjata kahdella tavalla:
- automaattisesti **Laske poisto** -eräajon avulla.
- Manuaalisesti käyttöomaisuuden KP-päiväkirjan avulla.  

Dynamics NAV voi laskea päivittäisen poiston, jolloin voit laskea poiston mille tahansa ajanjaksolle. Nykyisiä toiminnan tuloksia voi siis analysoida esimerkiksi kuukausittain, neljännesvuosittain tai vuosittain. Laskennassa käytetään 360 päivän vakiovuotta ja 30 päivän vakiokuukautta. Lisätietoja on kohdassa [Poistotavat](fa-depreciation-methods.md).

Jos useat osastot käyttävät käyttöomaisuuserää, jaksottaiset poistot voidaan kohdistaa automaattisesti näille osastoille käyttäjäkohtaisen kohdistustaulukon mukaisesti.  

Virheellisiä poistotapahtumia voi peruuttaa **Peruuta KO-tapahtumat** -eräajolla. Tämän jälkeen oikean poistosumman voi kirjata suorittamalla **Laske poisto** -eräajon uudelleen. Virheet kirjataan korjattaessa KO-virhetapahtumiksi.  

Indeksointia käytetään muuttamaan arvoja yleisten hintatason muutosten mukaan. **Tee indeksimuutos KO:teen** -eräajoa voidaan käyttää poistosummien uudelleenlaskemiseen.  

## <a name="to-calculate-a-depreciation-automatically"></a>Poistojen laskeminen automaattisesti
**Laske poisto** -eräajon voi suorittaa kerran kuukaudessa tai valitsemanasi ajankohtana. Käyttöomaisuuseriä, jotka on myyty, omaisuuseriä, jotka on suljettu tai jotka eivät ole aktiivisia sekä omaisuuseriä, joille käytetään manuaalista poistomenetelmää, ei huomioida.    

1. Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Laske poisto** ja valitse sitten aiheeseen liittyvä linkki.  
2. Täytä tarvittavat kentät. Lue kentän lyhyt kuvaus valitsemalla kenttä tai siirry lisätietoihin valitsemalla linkki.
3. Valitse **OK**-painike.  

    Eräajo laskee poiston ja luo rivejä käyttöomaisuuden KP-päiväkirjaan.  
4. Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **KO - KP-päiväkirjat** ja valitse sitten aiheeseen liittyvä linkki.

    **Käyttöomaisuuden KP-päiväkirja** -ikkunan **Poistopäivien lukumäärä** -kentän avulla nähdään, kuinka monta poistopäivää on laskettu.  
5. Valitse **Kirjaa**-toiminto.

## <a name="to-post-a-depreciation-manually-from-the-fixed-asset-gl-journal"></a>Poistojen kirjaaminen manuaalisesti käyttöomaisuuden KP-päiväkirjasta
1. Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Käyttöomaisuuden KP-päiväkirja** ja valitse sitten aiheeseen liittyvä linkki.  
2. Luo alkuperäisen päiväkirjan rivi ja täytä kentät tarpeen mukaan.
3. Valitse **KO:n kirjaustyyppi** -kentässä **Poisto**.
4. Valitse **Syötä KO-vastatili** -toiminto. Toinen päiväkirjan rivi luodaan vastatilille, joka on määritetty poiston kirjaamista varten. Lisätietoja on "Käyttöomaisuuden kirjausryhmien määrittäminen" -osassa kohdassa [Toimintaohje: Käyttöomaisuuden yleisten tietojen määrittäminen](fa-how-setup-general.md).
5. Valitse **Kotisivu**-välilehdessä **Kirjaa**, jolloin päiväkirja kirjataan.

Jos summien kohdistamiseksi eri osastoille tai projekteille on määritetty käyttöomaisuuden kohdistusavaimia, summat kohdistetaan kirjaamisen aikana. Lisätietoja on kohdassa [Toimintaohje: Käyttöomaisuuden yleisten tietojen määrittäminen](fa-how-setup-general.md).

## <a name="to-calculate-allocations-in-the-fixed-asset-gl-journal"></a>Käyttöomaisuuden KO-päiväkirjan kohdistusten laskeminen
Jos useat osastot käyttävät käyttöomaisuuserää, jaksottaiset poistot voidaan kohdistaa automaattisesti näille osastoille käyttäjäkohtaisen kohdistustaulukon mukaisesti.  

1. Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Käyttöomaisuuden KP-päiväkirja** ja valitse sitten aiheeseen liittyvä linkki.   
Luo alkuperäinen rivi ja täytä kentät tarpeen mukaan.
3. Valitse **KO:n kirjaustyyppi** -kentässä **Kohdistus**.
4. Valitse **Syötä KO-vastatili** -toiminto. Toinen päiväkirjan rivi luodaan vastatilille, joka on määritetty kohdistuksen kirjaamista varten.
5. Valitse **Kotisivu**-välilehdessä **Kirjaa**, jolloin päiväkirja kirjataan.

## <a name="use-duplication-lists-to-prepare-to-post-to-multiple-depreciation-books"></a>Valmistele useiden poistokirjojen kirjaaminen monistusluetteloiden avulla  
Täytä poistokirjaan kirjattavat päiväkirjarivit ja monista sitten rivit erilliseen päiväkirjaan, josta ne voidaan kirjata eri poistokirjaan. Lisätietoja on "Tapahtumien kirjaaminen eri poistokirjoihin" -osassa.

1. Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Poistokirjat** ja valitse sitten aiheeseen liittyvä linkki.  
2. Avaa poistokirja ja valitse **Osa monistusluettelosta** -valintaruutu.  

**Tärkeää**: Jos olet lisännyt valintamerkin **Käytä monistusluetteloa** -kenttään, älä käytä päiväkirjassa numerosarjaa. Tämä sen vuoksi, että käyttöomaisuuden KP-päiväkirjan numerosarjat ja käyttöomaisuuspäiväkirjan numerosarjat eivät ole samoja.

## <a name="to-post-entries-to-different-depreciation-books"></a>Tapahtumien kirjaaminen eri poistokirjoihin  
1. Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Käyttöomaisuuden KP-päiväkirja** ja valitse sitten aiheeseen liittyvä linkki.
2. Valitse **Käytä monistusluetteloa** -valintaruutu siinä päiväkirjassa, johon poisto kirjataan.
3. Täytä tarvittavat jäljellä olevat kentät.
4. Valitse **Kirjaa**-toiminto.
5. Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **KO-päiväkirjat** ja valitse sitten aiheeseen liittyvä linkki.

    **Käyttöomaisuuspäiväkirja**-ikkuna sisältää uusia rivejä eri poistokirjoille monistusluettelon mukaan.   

6. Tarkista rivit tai muokkaa niitä ja valitse sitten **Kirjaa**-toiminto.

**Huomautus**: Toinen tapa monistaa tapahtuma erilliseen kirjaan on syöttää poistokirjan koodi **Monista poistokirjaan** -kenttään silloin, kun päiväkirjariviä täytetään.

Tapahtumia voidaan kopioida poistokirjasta toiseen **Kopioi poistokirja** -eräajolla. Eräajo luo päiväkirjarivejä päiväkirjan erään, jonka olet määrittänyt **KO-päiväkirjan asetukset** -ikkunassa poistokirjalle, johon haluat kopioida. Katso lisätietoja seuraavasta menettelystä.

## <a name="to-copy-fixed-asset-ledger-entries-between-depreciation-books"></a>Käyttöomaisuustapahtumien kopioiminen poistokirjojen välillä  
1. Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Poistokirjat** ja valitse sitten aiheeseen liittyvä linkki.
2. Avaa poistokirjan kortti ja valitse **Kopioi poistokirja** -toiminto.  
3. Täytä **Kopioi poistokirja** -ikkunassa tarvittavat kentät.  
4. Valitse **OK**-painike.  

Kopioidut rivit luodaan joko käyttöomaisuuden KP-päiväkirjassa tai käyttöomaisuuspäiväkirjassa sen mukaisesti, onko kopioitava poistokirja integroitu pääkirjanpitoon.

## <a name="see-also"></a>Katso myös
[Käyttöomaisuuden hallinta](fa-manage.md)  
[Käyttöomaisuuserien määrittäminen](fa-setup.md)  
[Rahoitus](finance-setup.md)  
[Tervetuloa Dynamics NAV -ohjelmaan](across-get-started.md)

