---
title: Fyysisen varastoinnin aktiviteetit
description: "Tavaroiden vastaanoton jälkeen ja ennen tavaroiden toimitusta suoritetaan joukko sisäisiä varastotoimintoja, joiden avulla varmistetaan nimikkeiden tehokas kulku varastossa sekä järjestellään ja ylläpidetään yrityksen varastoja."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 08/15/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 608dc6f0d4fcf84d5df5a7d7c0c0dc304fdcad5f
ms.contentlocale: fi-fi
ms.lasthandoff: 10/16/2017

---
# <a name="warehouse-management"></a>Varastoinninhallinta
Tavaroiden vastaanoton jälkeen ja ennen tavaroiden toimitusta suoritetaan joukko sisäisiä varastotoimintoja, joiden avulla varmistetaan nimikkeiden tehokas kulku varastossa sekä järjestellään ja ylläpidetään yrityksen varastoja.

Tyypillisiin varastotoimintoihin kuuluvat nimikkeiden hyllytys, nimikkeiden siirtäminen varaston sisällä tai varastoiden välillä sekä nimikkeiden poiminta kokoonpanoa, tuotantoa tai toimitusta varten. Myös nimikkeiden kokoamista myyntiin tai varastoon voidaan pitää varastotoimintoja, mutta niitä käsitellään toisaalla. Lisätietoja on kohdassa [Kokoonpanon hallinta](assembly-assemble-items.md).  

Suurissa fyysisissä varastoissa eri käsittelytehtävät voi erotella osastojen mukaan ja niiden integrointia voi hallita ohjatun työnkulun avulla. Yksinkertaisissa asennuksissa toiminta on epämuodollisempaa ja varastotoiminnot suoritetaan niin kutsuttuina varaston hyllytyksinä ja poimintoina. Lisätietoja fyysisen varastoinnin perusmäärityksistä ja laajennetuista varastomäärityksistä on kohdassa [Rakennetiedot: Fyysisen varaston yleiskuvaus](design-details-warehouse-overview.md).

Ennen varastotoimintojen suorittamista järjestelmään on määritettävä soveltuva fyysisen varastoinnin monimutkaisuustaso. Lisätietoja on kohdassa [Varastoinninhallinnan määrittäminen](warehouse-setup-warehouse.md).

 Seuraavassa taulukossa on tehtäväsarja ja linkit tehtäviä käsitteleviin aiheisiin.   

|**Tehtävä**|**Katso**|  
|------------|-------------|  
|Kirjaa nimikkeiden vastaanotto fyysisissä varastosijainneissa joko pelkällä ostotilauksella (yksinkertaiset sijaintimääritykset) tai fyysisen varastoinnin vastaanottona, jos sijainnissa käytetään osittain tai kokonaan automatisoitua varastokäsittelyä.|[Toimintaohje: Nimikkeiden vastaanotto](warehouse-how-receive-items.md)|
|Nopeuta nimikkeen siirtymistä vastaanotosta tai tuotannosta suoraan toimitukseen ohittamalla hyllytys- ja poimintakäsittelyt.|[Toimintaohje: Nimikkeiden laituroiminen](warehouse-how-to-cross-dock-items.md)|    
|Hyllytä ostoista, myyntipalautuksista, siirroista tai tuotannon tuotoksesta vastaanotettuja nimikkeitä määritetyn varastokäsittelyn mukaisesti.|[Nimikkeiden hyllyttäminen](warehouse-put-away-items.md)|
|Siirrä nimikkeitä fyysisen varaston varastopaikkojen välillä.|[Nimikkeiden siirtäminen](warehouse-move-items.md)|
|Poimi toimitettavia, siirrettäviä tai kokoonpanossa tai tuotannossa kulutettavia nimikkeitä määritetyn varastokäsittelyn mukaisesti.|[Nimikkeiden poiminta](warehouse-pick-items.md)|
|Kirjaa nimikkeiden toimitus fyysisistä varastosijainneista joko pelkällä myyntitilauksella (yksinkertaiset sijaintimääritykset) tai fyysisen varastoinnin toimituksena, jos sijainnissa käytetään osittain tai kokonaan automatisoitua varastokäsittelyä.|[Toimintaohje: Nimikkeiden toimittaminen](warehouse-how-ship-items.md)|  

## <a name="see-also"></a>Katso myös  
 [Vaihto-omaisuus](inventory-manage-inventory.md)  
 [Varastoinninhallinnan määrittäminen](warehouse-setup-warehouse.md)     
 [Kokoonpanon hallinta](assembly-assemble-items.md)    
[Rakennetiedot: Fyysisen varaston hallinta](design-details-warehouse-management.md)  
 [[!INCLUDE[d365fin](includes/d365fin_md.md)] -ohjelman käyttäminen](ui-work-product.md)  

