---
title: Tavaroiden tai palvelujen nimikekorttien luominen
description: "Nimikekortit luodaan tunteina myytäville palveluille ja varastosta myytäville fyysisille tuotteille, kuten kokoonpanonimikkeille, valmiille tavaroille, komponenteille tai raaka-aineille."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: item, finished good, component, raw material, assembly item
ms.date: 08/31/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: f26207e07539da790a0ffab38a0fd2b732231300
ms.contentlocale: fi-fi
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-register-new-items"></a>Toimintaohje: Uusien nimikkeiden rekisteröiminen
Nimikkeet ovat muiden tuotteiden ohella liiketoimintasi perusta; ne ovat siis tavaroita ja palveluja, joilla käyt kauppaa. Jokainen nimike on rekisteröitävä nimikekorttina.

Nimikekortti sisältää tiedot, jotka tarvitaan nimikkeiden ostamista, tallentamista, myymistä ja toimittamista varten.

Nimike voi olla tuoterakenteessa päänimike, jonka alla on alinimikkeitä. [!INCLUDE[d365fin](includes/d365fin_md.md)]in tuoterakenne voi olla joko kokoonpanon tuoterakenne tai tuotannon tuoterakenne sen mukaan, miten sitä käytetään. Lisätietoja on kohdassa [Toimintaohje: Tuoterakenteen käyttäminen](inventory-how-work-BOMs.md).

> [!NOTE]  
>   Jos eri nimiketyypeillä on nimikemalleja, ikkuna avautuu, kun luot uuden nimikekortin, jossa voit valita sopivan mallin. Jos vain yksi nimikemalli on olemassa, uudet nimikekortit käyttävät aina kyseistä mallia.

Jos ostat saman nimikkeen useammalta kuin yhdeltä toimittajalta, voit yhdistää kyseiset toimittajat nimikkeen korttiin. Toimittajat näkyvät sitten **Nimikkeen toimittajaluettelo** -ikkunassa, jossa voit valita kätevästi vaihtoehtoisen toimittajan.

## <a name="to-create-a-new-item-card"></a>Uuden nimikekortin luominen
1. Valitse kotisivun **Nimikkeet**-toiminto, kun haluat avata olemassa olevien nimikkeiden luettelon.  
2. Valitse **Nimikkeet**-ikkunassa **Uusi**-toiminto.

    Jos vain yksi nimikemalli on olemassa, uusi nimikekortti avautuu. Kortissa on kenttiä, jotka on täytetty mallin tiedoilla.
3. Valitse **Valitse malli uudelle nimikkeelle** -ikkunassa malli, jota haluat käyttää uudessa nimikekortissa.
4. Valitse **OK**-painike. Uuden nimikekortti avautuu. Osa kortin kentistä on täytetty mallin tiedoilla.
5. Voit täyttää nimikekortin kenttiä tai muuttaa niitä tarvittaessa. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]

> [!NOTE]
> Määritä **Arvostusmenetelmä** -kentässä tapa, jolla nimikkeen yksikkökustannukset lasketaan tekemällä oletuksia fyysisestä tavaravirrasta yrityksen läpi. Käytössä on viisi arvostusmenetelmää nimikkeen tyypin mukaan. Lisätietoja on kohdassa [Rakennetiedot: Arvostusmenetelmät](design-details-costing-methods.md).
>
> Jos valitset **Keskiarvo**, nimikkeen yksikkökustannus lasketaan kussakin vaiheessa keskimääräisenä yksikkökustannuksena oston jälkeen. Varastonarvostus olettaa, että kaikki varastot myydään samanaikaisesti. Voit valita tällä asetuksella **Keskimääräisten kustannusten laskennan yleiskuvaus** -ikkunan **Yksikkökustannus**-kentän, jolla voit tarkastella tapahtumahistoriaa, josta keskimääräinen kustannus lasketaan.

**Hinta ja kirjaus**-pikavälilehti sisältää erityiset hinnat tai alennukset, jotka haluat myöntää nimikkeelle, jos tietyt ehdot, kuten asiakas, vähimmäistilausmäärä tai päättymispäivämäärä, täyttyvät. Kukin rivi edustaa erityistä hinnan alennusta tai rivialennusta. Kukin sarake vastaa ehtoa, joka takaa **Yksikköhinta**-kenttään kirjoitetun erikoishinnan tai **Rivialennus-%**-kenttään kirjoitetun rivialennuksen. Lisätietoja on kohdassa [Myyntihinnan, alennuksen ja maksusopimusten tallentaminen](sales-how-record-sales-price-discount-payment-agreements.md).

Nimike on nyt rekisteröity ja nimikekortti on valmis käytettäväksi osto- ja myyntiasiakirjoissa.

Jos haluat käyttää tätä nimikekorttia mallina, kun luot uusia nimikkeen kortteja, tallenna se mallina. Lisätietoja on seuraavassa osassa.

## <a name="to-save-the-item-card-as-a-template"></a>Nimikekortin tallentaminen mallina
1. Valitse **Nimikekortti**-ikkunassa **Tallenna mallina** -toiminto. **Nimikemalli**-ikkuna avautuu ja näyttää nimikekortin mallina.
2. Täytä tarvittavat kentät. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]
3. Voit käyttää dimensioita malleina valitsemalla **Dimensiot**-toiminnon. **Dimensiomallit**-ikkuna avautuu ja esittää kaikki dimensiokoodit, jotka on määritetty nimikkeelle.
4. Muokkaa tai syötä dimensiokoodit, joita käytetään mallin avulla luotuihin uusiin nimikkeen kortteihin.
5. Kun olet määrittänyt uuden nimikemallin, valitse **OK**-painike.

Nimikemalli lisätään nimikemallien luetteloon niin, että sen avulla voit luoda uusia nimikekortteja.

## <a name="to-set-up-multiple-vendors-for-an-item"></a>Useiden toimittajien määrittäminen nimikkeille  
Jos ostat saman nimikkeen useammalta kuin yhdeltä toimittajalta, sinun tulee syöttää tietoja kustakin nimikkeen toimittajasta, esimerkiksi hinnat, toimitusaika ja alennukset.  

1.  Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, kirjoita **Nimikkeet** ja valitse sitten aiheeseen liittyvä linkki.  
2.  Valitse ensin käsiteltävä nimike ja sitten **Muokkaa**-toiminto.  
3.  Valitse **Toimittajat**-toiminto.  
4.  Valitse **Toimittajan nro** -kenttä, ja valitse toimittaja, jonka haluat määrittää nimikkeelle.  
5.  Voit täyttää myös jäljellä olevat rivit.  
6.  Toista vaiheet 2–5 kullekin toimittajalle, jolta haluat ostaa nimikkeitä.

Toimittajat näkyvät nyt nimikkeen kortissa avattavassa **Nimikkeen toimittajaluettelo** -ikkunassa, jossa voit valita kätevästi vaihtoehtoisen toimittajan.

## <a name="see-also"></a>Katso myös
  [Vaihto-omaisuus](inventory-manage-inventory.md)  
  [Osto](purchasing-manage-purchasing.md)  
  [Myynti](sales-manage-sales.md)  
  [[!INCLUDE[d365fin_long](includes/d365fin_long_md.md)]in käyttäminen](ui-work-product.md)

##

