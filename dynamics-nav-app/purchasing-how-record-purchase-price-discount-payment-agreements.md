---
title: "Toimittajien erikoishintojen, vaihtoehtoisten hintojen ja alennusten määrittäminen"
description: "Voit määrittää eri hintoja tai vaihtoehtoisia hintoja ja alennussopimuksia ja käyttää niitä sitten toimittajien ostoasiakirjoissa."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: special price, alternate price, pricing
ms.date: 07/03/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: cc4240ea4201bd68b3c2c9c27ab91dc49583e6a6
ms.contentlocale: fi-fi
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-record-special-purchase-prices-and-discounts"></a>Toimintaohje: Erikoisostohintojen ja -alennusten kirjaaminen
Eri hinta- ja alennussopimukset, joita käytetään ostettaessa eri toimittajilta, täytyy määrittää, jotta sovittuja sääntöjä ja arvoja sovelletaan toimittajille luotaviin ostoasiakirjoihin.

Kun olet kirjannut myynnin ja ostojen erikoishinnat ja rivialennukset, [!INCLUDE[d365fin](includes/d365fin_md.md)] varmistaa, että nimikekaupan tuotto on aina optimaalinen laskemalla automaattisesti parhaan hinnan myynti- ja ostoasiakirjoille sekä työ- ja nimikepäiväkirjan riville. Lisätietoja on osiossa Parhaan hinnan laskenta.

Ostoriveille lisätään erikoisostohinta, jos tietty toimittajan, nimikkeen, vähimmäismäärän, mittayksikön sekä aloitus- ja lopetuspäivämäärän yhdistelmä on olemassa.

Voit määrittää seuraavat kaksi ostoalennustyyppiä:

| Alennustyyppi | Kuvaus |
| --- | --- |
| **Ostorivin alennus** |Ostoriveille lisättävä summa-alennus, jos tietty toimittajan, nimikkeen, vähimmäismäärän, mittayksikön sekä aloitus- ja lopetuspäivämäärän yhdistelmä on olemassa. Tätä käytetään samoin kuin ostohinnoissa. |
| **Laskualennus** |Prosenttialennus, joka vähennetään kokonaissummasta, kun ostoasiakirjan kaikkien rivien summa ylittää määritetyn vähimmäisarvon. |

Koska ostorivin alennukset ja ostohinnat perustuvat nimikkeen ja toimittajan yhdistelmään, voit lisätä tämän määrityksen myös nimikkeen kortista, jossa säännöt ja arvot on määritetty. Lisätietoja on ohjeaiheessa [Toimintaohje: Uusien nimikkeiden rekisteröiminen](inventory-how-register-new-items.md).

## <a name="to-set-up-a-special-purchase-price-for-a-vendor"></a>Tietyn ostohinnan määrittäminen toimittajalle
1. Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, syötä **Toimittajat** ja valitse sitten aiheeseen liittyvä linkki.
2. Avaa asianmukainen toimittajan kortti ja valitse **Hinnat**-toiminto.

    **Ostotyyppi**-kenttään täytetään **toimittajan** tiedot ja **Ostokoodi**-kenttään täytetään toimittajan numero.
3. Täytä tarvittaessa rivin muut kentät. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]
4. Täytä jokaisen sellaisen yhdistelmän rivi, jonka toimittaja myöntää sinulle ostorivialennuksen.

## <a name="to-set-up-a-line-discount-for-a-vendor"></a>Rivialennuksen määrittäminen toimittajalle
1. Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, syötä **Toimittajat** ja valitse sitten aiheeseen liittyvä linkki.
2. Avaa asianmukainen toimittajan kortti ja valitse **Rivialennukset**-toiminto.

    **Ostotyyppi**-kenttään täytetään **toimittajan** tiedot ja **Ostokoodi**-kenttään täytetään toimittajan numero.
3. Täytä tarvittaessa rivin muut kentät. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]
4. Täytä jokaisen sellaisen yhdistelmän rivi, jonka toimittaja myöntää sinulle ostorivialennuksen.

## <a name="to-set-up-an-invoice-discount-for-a-vendor"></a>Laskualennuksen määrittäminen toimittajalle
Kun toimittajat ovat kertoneet sinulle myöntämänsä laskualennukset, syötä laskun alennuskoodi toimittajien kortteihin ja määritä kunkin koodin ehdot.

1. Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, syötä **Toimittajat** ja valitse sitten aiheeseen liittyvä linkki.
2. Avaa sen toimittajan kortti, jolle myönnetään laskun alennuksia.
3. Valitse **Laskualennuksen koodi** -kentässä asianmukaisille laskualennuksen ehdoille koodi, jonka avulla toimittajan laskualennukset lasketaan.

    > [!NOTE]  
>   Laskualennuksen koodit löytyvät olemassa olevien toimittajien korteista. Näin voit nopeasti liittää laskualennusten ehtoja toimittajiin poimimalla sellaisten toimittajien nimet, joilla on samat ehdot.

    Jatka uuden ostolaskun alennusehtojen määrittämiseen.
4. Valitse **Toimittajan kortti** -ikkunassa **Laskualennukset**-toiminto. **Toimittajien laskualennukset** -ikkuna aukeaa.
5. Syötä **Valuutan koodi** -kenttään sen valuutan koodi, johon rivin laskualennuksen ehdot kohdistetaan. Jätä kenttä tyhjäksi, jos laskualennuksen ehdot määritetään Yhdysvaltojen dollareina.
6. Syötä **Vähimmäissumma**-kenttään laskun vähimmäissumma, joka oikeuttaa alennukseen.
7. Syötä **Alennus-%**-kohtaan laskun alennus prosentteina laskun summasta.
8. Toista vaiheet 5–7 jokaiselle valuutalle, jossa toimittaja saa eri laskualennuksen.

Laskualennus on nyt määritetty ja liitetty kyseiselle toimittajalle. Kun valitset toimittajakoodin muiden toimittajien korttien **Laskun alennuskoodi** -kentässä, sama laskualennus liitetään myös näille toimittajille.

## <a name="to-choose-a-principle-for-posting-purchase-discounts"></a>Periaatteen valitseminen ostoalennusten kirjaukselle  
Kun kirjaat ostolaskun, joka sisältää yhden tai useamman alennuksen, voit valita kahdesta periaatteesta, miten alennussummat kirjataan. Voit kirjata alennukset erikseen tai voit vähentää alennukset laskualennuksista.  

Ennen kuin voit tehdä tämän, sinun on täytynyt määrittää tarpeelliset tilit alennussummien kirjaamiseksi tilikartassa. Tarkista myös, että olet syöttänyt oikeat tilinumerot yleisiin kirjauksien asetuksiin **Oston rivialennustili** ja **Oston laskualennustili** -kentissä.

1. Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, syötä **Ostojen ostovelkojen asetukset** ja valitse sitten aiheeseen liittyvä linkki.
2. Valitse **Alennuksen kirjaus** -kentässä jokin seuraavista alennusten kirjausperiaatteista.

|**Alennuksen kirjauksen periaate**|**Laskualennus**|**Rivialennus**|  
|------------------------------------|--------------------------|-----------------------|  
|**Kaikki alennukset**|Kirjattu erikseen|Kirjattu erikseen|  
|**Laskualennukset**|Kirjattu erikseen|Vähennetty|  
|**Rivialennukset**|Vähennetty|Kirjattu erikseen|  
|**Ei alennuksia**|Vähennetty|Vähennetty|  

# <a name="purchase-invoice-discounts-and-service-charges"></a>Ostolaskualennukset ja palvelumaksut
Jos olet sopinut laskualennusehdoista joidenkin toimittajien kanssa, voit syöttää ehdot näiden toimittajien kohdalle. Tämän jälkeen ohjelma voi laskea alennuksen silloin, kun täytät ostolaskun.  

 Ennen kuin ostojen yhteydessä voidaan käyttää laskun alennuksia, sinun täytyy määrittää toimittajat, jotka tarjoavat sinulle alennuksia.  

 Voit linkittää alennusprosentit tiettyihin laskusummiin **Myyjän laskualennukset** -ikkunoissa. Voit syöttää mitä tahansa prosenttilukuja kussakin ikkunassa. Jokainen toimittaja voi olla erillisessä ikkunassa, tai samaan ikkunaan voi linkittää useita toimittajia.  

 Spesifiseen laskusummaan voi linkittää alennusprosentin lisäksi (tai sen sijaan) palvelumaksusumman.  

 Laskualennuksen ehdot voi määrittää PVA:ssa kotimaan toimittajille ja ulkomaan valuutassa ulkomaisille toimittajille.  

 [!INCLUDE[d365fin](includes/d365fin_md.md)] voi laskea laskualennukset automaattisesti tarjouksille, puitetilauksille, tilauksille, laskuille tai hyvityslaskuille.  

> [!TIP]  
>  Ennen kuin näitä tietoja aletaan syöttää ohjelmaan, olisi hyvä tehdä luonnos alennusrakenteesta, jota haluat käyttää. Tällä tavalla on helpompi nähdä, mitkä toimittajat voidaan linkittää samaan laskualennusikkunaan. Mitä vähemmän ikkunoita täytyy määrittää, sitä nopeampaa perustietojen syöttäminen on.

## <a name="best-price-calculation"></a>Parhaan hinnan laskenta
Kun olet kirjannut myynnin ja ostojen erikoishinnat ja rivialennukset, [!INCLUDE[d365fin](includes/d365fin_md.md)] varmistaa, että nimikekaupan tuotto on aina optimaalinen laskemalla automaattisesti parhaan hinnan myynti- ja ostoasiakirjoille sekä projekti- ja nimikepäiväkirjan riville.

Paras hinta on tietyn päivän alhaisin sallittu hinta, jolla on suurin sallittu rivialennus. [!INCLUDE[d365fin](includes/d365fin_md.md)] laskee tämän automaattisesti, kun se lisää nimikkeiden yksikköhinnan ja rivialennusprosentin uuteen asiakirjaan ja päiväkirjariville.

> [!NOTE]  
>   Seuraavaksi kerrotaan, miten myynnin paras hinta lasketaan. Samaa laskentaa käytetään ostoissa.

1. [!INCLUDE[d365fin](includes/d365fin_md.md)] tarkistaa laskutusasiakas- ja nimikeyhdistelmän ja laskee sitten käytettävän yksikköhinnan ja rivialennusprosentin seuraavien ehtojen mukaisesti:

    - Onko asiakkaalla hinta- tai alennussopimus tai kuuluuko asiakas ryhmään, jolla on tällainen sopimus on?
    - Kuuluuko rivillä oleva nimike tai nimikealennusryhmä johonkin näistä hinta- tai alennussopimuksista?
    - Onko tilauspäivämäärä (tai laskun ja hyvityslaskun osalta kirjauspäivämäärä) hinta- tai alennussopimuksen aloitus- ja lopetuspäivämäärän välissä?
    - Onko mittayksikön koodia määritelty? Jos on, [!INCLUDE[d365fin](includes/d365fin_md.md)] tarkastaa hinnat tai alennukset, joilla on sama mittayksikön koodi, ja hinnat tai alennukset, joilla ei ole mittayksikön koodia.

2. [!INCLUDE[d365fin](includes/d365fin_md.md)] tarkistaa, koskeeko jokin hinta- tai alennussopimus asiakirjan tai päiväkirjarivin tietoja, ja lisää sitten käytettävän yksikköhinnan ja rivialennusprosentin seuraavien ehtojen mukaisesti:

    - Täytyykö hinta- tai alennussopimuksen vähimmäismäärävaatimus?
    - Täytyykö hinta- tai alennussopimuksen valuuttavaatimus? Jos täyttyy, kyseisen valuutan alhaisin hinta ja suurin rivialennus lisätään, vaikka paikallinen valuutta antaisi paremman hinnan. Jos määritellyllä valuuttakoodilla ei ole hinta- tai alennusopimusta, [!INCLUDE[d365fin](includes/d365fin_md.md)] lisää alhaisimman hinnan ja suurimman rivialennuksen paikallisessa valuutassa.

Jos erikoishintaa ei voi laskea rivin nimikkeelle, joko viimeinen välitön kustannus tai nimikekortin yksikköhinta lisätään.

## <a name="see-also"></a>Katso myös
[Ostojen määrittäminen](purchasing-setup-purchasing.md)  
[Osto](purchasing-manage-purchasing.md)  
[[!INCLUDE[d365fin](includes/d365fin_md.md)] -ohjelman käyttäminen](ui-work-product.md)

