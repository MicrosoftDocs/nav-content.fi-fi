---
title: Ei-varastoitavien nimikkeiden luominen ja hallinta
description: "Tässä ohjeaiheessa kerrotaan, miten käydään kauppaa ei-varastoitavilla nimikkeillä tai nimikkeillä, joita ei säilytetä varastossa."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: non-inventoriable
ms.date: 06/02/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: dd1497d0727935d4954f826eceb303761850dada
ms.contentlocale: fi-fi
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-work-with-nonstock-items"></a>Toimintaohje: Ei-varastoitavien nimikkeiden käsitteleminen
Voit tarjota asiakkaille tiettyjä nimikkeitä, joita et halua varastoida ennen kuin niitä myydään. Kun haluat alkaa varastoida tällaisia nimikkeitä, voit muuntaa ne normaaleiden nimikkeiden korteiksi kahdella eri tavalla.

* Luo ei-varastoitavan nimikkeen kortille uusi nimikekortti mallin mukaan.
* Valitse ei-varastoitava nimike **Nimike**-tyyppiseltä myyntitilausriviltä, jolla on tyhjä *Nro*-kenttä. Nimikekortti luodaan automaattisesti ei-varastoitavalle nimikkeelle.

> [!NOTE]  
>   Ei-varastoitavaa nimikettä ei voi valita **Myyntilasku**-ikkunassa. Voit valita ei-varastoitavan nimikkeen **Myyntitarjous**-ikkunassa, mutta ei-varastoitavaa nimikettä ei muunneta normaaliksi nimikkeeksi, jos käytössä on **Tee tilaus** -toiminto.

Ei-varastoitavalla nimikkeellä on yleensä sen toimittavan toimittajan nimikenumero. Voit ottaa ei-varastoitavan nimikkeen kortin muuntamisen käyttöön normaalin nimikkeen kortille määrittämällä ensin, miten toimittajan nimikenumerointi muunnetaan omaksi nimikenumeroinniksesi.   

## <a name="to-create-a-nonstock-item"></a>Ei-varastoitavan nimikkeen luominen
Ei-varastoitavien nimikkeiden korteissa on paljon vähemmän tietoja kuin normaalien nimikkeiden korteissa, koska niitä käytetään tarjouksissa ja tehtäessä muita tilauksia. Tämän vuoksi ne on muunnettava normaaleiden nimikkeiden korteiksi, ennen kuin niille voidaan kirjata myyntitapahtumat.

1. Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, anna **Ei-varastoitavat nimikkeet** ja valitse sitten aiheeseen liittyvä linkki.
2. Valitse **Uusi**-toiminto.
3. Täytä tarvittavat kentät. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]

## <a name="to-set-up-how-nonstock-item-numbers-are-converted-to-your-own-numbering"></a>Määritetään, miten ei-varastoitavat nimikenumerot muunnetaan omaksi numeroinniksi
Voit ottaa ei-varastoitavan nimikkeen kortin muuntamisen käyttöön normaalin nimikkeen kortille määrittämällä ensin, miten toimittajan nimikenumerointi muunnetaan omaksi numeromuodoksi.

1. Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, anna **Ei-varastoitavien nimikkeiden asetukset** ja valitse sitten aiheeseen liittyvä linkki.
2. Täytä tarvittavat kentät.

## <a name="to-convert-a-nonstock-item-to-a-normal-item"></a>Ei-varastoitavan nimikkeen muuntaminen normaaliksi nimikkeeksi
1. Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, anna **Ei-varastoitavat nimikkeet** ja valitse sitten aiheeseen liittyvä linkki.
2. Avaa sen ei-varastoitavan nimikkeen kortti, jonka haluat muuntaa normaaliksi nimikkeeksi.
3. Valitse **Ei-varastoitavan nimikkeen kortti**-ikkunassa **Luo nimike** -toiminto.

Luodaan uusi nimikekortti, johon on täytetty ei-varastoitavan nimikkeen tiedot, ja asiaankuuluva nimikemalli. Tämän jälkeen voit täyttää uuden nimikekortin kentät tai muokata niitä tarvittaessa. Lisätietoja on kohdassa [Toimintaohje: Uusien nimikkeiden rekisteröiminen](inventory-how-register-new-items.md).

## <a name="to-sell-a-nonstock-item-and-convert-it-to-a-normal-item"></a>Ei-varastoitavan nimikkeen myyminen ja muuntaminen normaaliksi nimikkeeksi
1. Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, anna **Myyntitilaukset** ja valitse sitten aiheeseen liittyvä linkki.
2. Valitse **Uusi**-toiminto. Täytä **Yleinen**-pikavälilehden kentät samalla tavalla kuin myyntitilauksen kentät. Lisätietoja on kohdassa [Toimintaohje: Tuotteiden myyminen](sales-how-sell-products.md).
3. Valitse uuden tilausrivin **Tyyppi**-kentässä **Nimike**, mutta jätä **Nro**-kenttä tyhjäksi.
4. Valitse ensin **Rivi**-toiminto ja sitten **Valitse ei-varastoitavat nimikkeet** -toiminto.

    Ei-varastoitava nimike muunnetaan normaaliksi nimikkeeksi. Luodaan uusi nimikekortti, johon on täytetty ei-varastoitavan nimikkeen tiedot, ja asiaankuuluva nimikemalli.
5. Valitse **Ei-varastoitavat nimikkeet** -ikkunassa ei-varastoitava nimike, jonka haluat myydä, ja valitse sitten **OK**-painike.
6. Kun myyntitilaus on valmis, valitse **Kirjaa**-toiminto.

Tämän jälkeen voit täyttää uuden nimikekortin kentät tai muokata niitä tarvittaessa. Lisätietoja on ohjeaiheessa [Toimintaohje: Uusien nimikkeiden rekisteröiminen](inventory-how-register-new-items.md).

> [!NOTE]  
>   Toimittajalle luodaan automaattisesti nimikkeen viittaustietue nimikkeelle, jonka numero on toimittajan nimikenumeron ja uuden nimikenumeron välissä.

## <a name="see-also"></a>Katso myös
[Toimintaohje: Uusien nimikkeiden rekisteröiminen](inventory-how-register-new-items.md)  
[Erikoistilausten luominen](sales-how-to-create-special-orders.md)|  
[Vaihto-omaisuus](inventory-manage-inventory.md)  
[[!INCLUDE[d365fin](includes/d365fin_md.md)] -ohjelman käyttäminen](ui-work-product.md)

