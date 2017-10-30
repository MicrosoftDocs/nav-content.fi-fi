---
title: "Nimikkeiden siirtäminen varastosijaintien välillä"
description: "Tässä ohjeaiheessa kerrotaan, miten varastonimikkeitä siirretään varastosta toiseen joko uudelleenluokituspäiväkirjan tai siirtotilausten avulla."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: move, warehouse
ms.date: 06/02/2017
ms.author: SorenGP
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: f2be3ef1613356bb2b0d1a02c355e09a546de62d
ms.contentlocale: fi-fi
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-transfer-inventory-between-locations"></a>Toimintaohje: Varastonimikkeiden siirtäminen sijaintien välillä
Varastonimikkeitä siirretään sijaintien välillä luomalla siirtotilauksia. Vaihtoehtoisesti voit käyttää uudelleenluokituspäiväkirjaa.

Siirtotilauksissa lähtevä siirto toimitetaan yhdestä sijainnista vastaanotettavaksi toisessa sijainnissa. Tämä mahdollistaa liittyvien varastointiaktiviteettien hallinnan ja tarjoaa suuremman varmuuden siitä, että varastosaldot päivitetään oikein.

Uudelleenluokituspäiväkirjaan voit yksinkertaisesti täyttää **Sijaintikoodi**- ja **Uusi sijaintikoodi** -kentät. Kun teet kirjauksen päiväkirjaan, nimiketapahtumat oikaistaan kyseisissä sijainneissa. Varastotoimintoja ei hallita tällä menetelmällä.

> [!NOTE]  
>   Jos varastoon on kirjattu nimikkeitä ilman sijaintikoodia esimerkiksi silloin, kun käytössä oli vain yksi varasto, et voi siirtää kyseisiä nimikkeitä siirtotilauksilla. Sen sijaan sinun on käytettävä uudelleenluokittelupäiväkirjaa ja luokiteltava nimikkeet uudelleen tyhjästä sijaintikoodista todelliseen sijaintikoodiin.  Lisätietoja on Nimikkeiden siirtäminen uudelleenluokituspäiväkirjan avulla -kohdan vaiheessa 3.

Sijainnit ja siirtoreitit on määritettävä, jotta nimikkeitä voi siirtää. Lisätietoja on kohdassa [Toimintaohje: Sijaintien määrittäminen](inventory-how-setup-locations.md).

## <a name="to-transfer-items-with-a-transfer-order"></a>Nimikkeiden siirtäminen siirtotilauksella
1. Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, anna **Siirtotilaukset** ja valitse sitten aiheeseen liittyvä linkki.
2. Täytä **Siirtotilaus**-ikkunassa tarvittavat kentät. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]

    > [!NOTE]  
>   Jos olet täyttänyt **Siirtoreitin määritykset** -ikkunan **Kuljetuksessa-koodi**-, **Kuljetusliikkeen koodi**- ja **Kuljetusliikkeen palvelu** -kentät siirtoreitin määrityksen yhteydessä, ohjelma täyttää siirtotilauksen vastaavat kentät automaattisesti.

    Kun **Kuljetusliikkeen palvelu** -kenttä täytetään, kohteeseen-sijainnin vastaanottopäivämäärä lasketaan lisäämällä kuljetusliikkeen palvelun toimitusajan Kohteesta-pikavälilehden lähetyksen päivämäärään.

    Kohteesta-sijainnin varastotyöntekijänä voit siirtyä nimikkeiden toimittamiseen.
3. Valita ensin **Kirjaa**-toiminto, sitten **Toimitus**-asetus ja lopuksi **OK**-painike.

    Nimikkeet ovat nyt matkalla valittujen sijaintien välillä valitun siirtoreitin mukaisesti.

    Kohteesta-sijainnin varastotyöntekijänä voit siirtyä nimikkeiden vastaanottamiseen.
4. Valita ensin **Kirjaa**-toiminto, sitten **Vastaanotto**-asetus ja lopuksi **OK**-painike.

## <a name="to-transfer-items-with-the-item-reclassification-journal"></a>Siirrä nimikkeet nimikkeiden uudelleenluokituspäiväkirjan avulla
1. Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, anna **Nimikkeen uudell.luokit. pvk:t** ja valitse sitten aiheeseen liittyvä linkki.
2. Täytä **Nimik. uud.luok.pvk** -ikkunassa tarvittavat kentät. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]
3. Anna **Sijaintikoodi**-kentässä sijainti, jossa nimikkeet ovat varastoituna.

    > [!NOTE]  
>   Jos siirrettävillä nimikkeillä ei ole sijainkoodia, jätä **Sijaintikoodi**-kenttä tyhjäksi.
4. Anna **Uusi sijaintikoodi** -kenttään sijainti, johon haluat siirtää nimikkeet.
5. Valitse **Kirjaa**-toiminto.

## <a name="see-also"></a>Katso myös
[Varaston hallinta](inventory-manage-inventory.md)  
[Toimintaohje: Sijaintien määrittäminen](inventory-how-setup-locations.md)  

[[!INCLUDE[d365fin](includes/d365fin_md.md)] -ohjelman käyttäminen](ui-work-product.md)  
[[!INCLUDE[d365fin](includes/d365fin_md.md)] -sovelluksen mukauttaminen](ui-customizing-overview.md)  
[Yleiset liiketoimintatoiminnot](ui-across-business-areas.md)

##

