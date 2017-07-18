---
title: "Toimintaohje: Uusien tuotteiden rekisteröiminen"
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
ms.openlocfilehash: df84a4d3e15035cd956c7612a12069844f5601d2
ms.contentlocale: fi-fi
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-register-new-products"></a>Toimintaohje: Uusien tuotteiden rekisteröiminen

Tuotteet, eli tavarat tai palvelut, joilla käyt kauppaa, ovat liiketoimintasi perusta. Jokainen tuote on rekisteröitävä nimikekorttina.

**Huomautus**: Dynamics NAV -ohjelmassa tuotteeseen viitataan termillä “nimike”.

Nimikekortti sisältää tiedot, jotka tarvitaan tuotteiden ostamista, tallentamista, myymistä ja toimittamista varten.

Nimikekortin tyyppi voi olla Varasto tai Palvelu, jolloin voidaan määritellä, onko tuote fyysinen yksikkö vai työaikayksikkö. Lukuun ottamatta kenttiä, jotka liittyvät nimikkeen fyysisiin osa-alueisiin, kaikki nimikkeen kortin kentät toimivat samalla tavalla varastonimikkeille ja palveluille. Lisätietoja nimikkeen myymisestä on kohdassa [Toimintaohje: Tuotteiden myyminen](sales-how-sell-products.md) ja [Toimintaohje: Myynnin laskuttaminen](sales-how-invoice-sales.md).

**Huomautus**: Jos eri nimikkeen on olemassa asiakasmalleja, ikkuna tulee näkyviin, kun luot uuden nimikkeen kortin, jossa voit valita haluamasi mallin. Jos vain yksi nimikemalli on olemassa, uudet nimikekortit käyttävät aina kyseistä mallia.

## <a name="to-create-a-new-item-card"></a>Uuden nimikekortin luominen
1. Valitse kotisivun **Nimikkeet**-toiminto, kun haluat avata olemassa olevien nimikkeiden luettelon.  
2. Valitse **Nimikkeet**-ikkunassa **Uusi**-toiminto.

    Jos vain yksi nimikemalli on olemassa, uusi nimikekortti avautuu. Kortissa on kenttiä, jotka on täytetty mallin tiedoilla.
3. Valitse **Valitse malli uudelle nimikkeelle** -ikkunassa malli, jota haluat käyttää uudessa nimikekortissa.
4. Valitse **OK**-painike. Uuden nimikekortti avautuu. Osa kortin kentistä on täytetty mallin tiedoilla.
5. Voit täyttää nimikekortin kenttiä tai muuttaa niitä tarvittaessa. Lue kentän lyhyt kuvaus valitsemalla kenttä tai siirry lisätietoihin valitsemalla linkki.

**Myyntihinnat**-pikavälilehti sisältää erityiset hinnat tai alennukset, jotka haluat myöntää nimikkeelle, jos tietyt ehdot, kuten asiakas, vähimmäistilausmäärä tai päättymispäivämäärä, täyttyvät. Kukin rivi edustaa erityistä hinnan alennusta tai rivialennusta. Kukin sarake vastaa ehtoa, joka takaa **Yksikköhinta**-kenttään kirjoitetun erikoishinnan tai **Rivialennus-%**-kenttään kirjoitetun rivialennuksen. Lisätietoja on kohdassa [Myyntihinnan, alennuksen ja maksusopimusten tallentaminen](sales-how-record-sales-price-discount-payment-agreements.md).

Nimike on nyt rekisteröity ja nimikekortti on valmis käytettäväksi osto- ja myyntiasiakirjoissa.

Jos haluat käyttää tätä nimikekorttia mallina, kun luot uusia nimikkeen kortteja, tallenna se mallina. Lisätietoja on seuraavassa osassa.

## <a name="to-save-the-item-card-as-a-template"></a>Nimikekortin tallentaminen mallina
1. Valitse **Nimikekortti**-ikkunassa **Tallenna mallina** -toiminto. **Nimikemalli**-ikkuna avautuu ja näyttää nimikekortin mallina.
2. Täytä tarvittavat kentät. Lue kentän lyhyt kuvaus valitsemalla kenttä tai siirry lisätietoihin valitsemalla linkki.
3. Voit käyttää dimensioita malleina valitsemalla **Dimensiot**-toiminnon. **Dimensiomallit**-ikkuna avautuu ja esittää kaikki dimensiokoodit, jotka on määritetty nimikkeelle.
4. Muokkaa tai syötä dimensiokoodit, joita käytetään mallin avulla luotuihin uusiin nimikkeen kortteihin.
5. Kun olet määrittänyt uuden nimikemallin, valitse **OK**-painike.

Nimikemalli lisätään nimikemallien luetteloon niin, että sen avulla voit luoda uusia nimikekortteja.

## <a name="see-also"></a>Katso myös
  [Varaston hallinta](inventory-manage-inventory.md)  
  [Ostojen hallinta](purchasing-manage-purchasing.md)  
  [Myynnin hallinta](sales-manage-sales.md)

