---
title: "Nimikkeiden siirtäminen"
description: "Varaston nimikkeitä pitää joskus siirtää varastopaikasta toiseen päivittäisten varastotapahtumien ja varaston nimikevirran tukemiseksi. Jotkut liikkeet tapahtuvat suorassa suhteessa sisäisiin toimintoihin, kuten tuotantotilaus, jonka komponentit täytyy toimittaa tai lopulliset nimikkeet hyllyttää. Muut siirrot tapahtuvat vain fyysisen varastoinnin tilan optimointina tai ad-hoc-siirtoina toimintoihin ja toiminnoista."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 08/22/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: ce2e6f176d2eb13c74e54e903d284a41948d87b8
ms.contentlocale: fi-fi
ms.lasthandoff: 10/16/2017

---
# <a name="moving-items"></a>Nimikkeiden siirtäminen
Nimikkeiden siirtäminen fyysisessä varastossa on varastotoiminto, joka suoritetaan eri tavoilla sen mukaan, miten varastoinninhallintajärjestelmän ominaisuudet on määritetty. Määritysten monimutkaisuus voi vaihdella: ominaisuusluettelossa ei ole varastotoimintoja lainkaan, tilauskohtaisessa fyysisen varastoinnin perusmäärityksissä käsittelytoimintoja on vain muutama toiminto, kun laajennetuissa varastomäärityksissä kaikki varastotoiminnot tehdään ohjatun työnkulun mukaisesti. Lisätietoja on kohdassa [Varastoinninhallinnan määrittäminen](warehouse-setup-warehouse.md).

Nimikkeitä on ehkä siirrettävä samassa fyysisessä varastosijainnissa varastopaikasta toiseen päivittäisten varastotapahtumien ja varaston nimikevirran tukemiseksi. Jotkut liikkeet tapahtuvat suorassa suhteessa sisäisiin toimintoihin, kuten tuotantotilaus, jonka komponentit täytyy toimittaa tai lopulliset nimikkeet hyllyttää. Muut siirrot tapahtuvat fyysisen varastoinnin tilan optimointina tai suunnittelemattomina siirtoina toimintoihin ja toiminnoista pois.

Nimikkeiden siirtäminen toiseen sijaintiin vaikuttaa nimiketapahtumiin, joten ne on tehtävä siirtotilauksen avulla. Lisätietoja on kohdassa [Toimintaohje: Varastonimikkeiden siirtäminen sijantien välillä](inventory-how-transfer-between-locations.md).  

Muita siirtotehtäviä ovat poiminnan tai tuotannon varastopaikkojen kausittainen täydennys sekä varastopaikan sisällön muuttaminen.  

 Seuraavassa taulukossa on tehtäväsarja ja linkit tehtäviä käsitteleviin aiheisiin.   

|**Tehtävä**|**Katso**|  
|------------|-------------|  
|Siirrä nimikkeitä perusvaraston määrityksten mukaisten varastopaikkojen välillä milloin tahansa ja ilman lähdeasiakirjoja.|[Toimintaohje: Nimikkeiden siirtäminen fyysisen varastoinnin perusmäärityksissä](warehouse-how-to-move-items-ad-hoc-in-basic-warehousing.md)|
|Fyysisen varastoinnin siirtotyökirjan avulla voit siirtää kohteita laajennetuissa varastointimäärityksissä, sekä lähdeasiakiroihin että ad-hoc -raportteihin.|[Toimintaohje: Nimikkeiden siirtäminen laajennetuissa varastomäärityksissä](warehouse-how-to-move-items-in-advanced-warehousing.md)|  
|Tuo komponenttinimikkeet sisäisiin toimintoihin varastoinnin määritysten mukaisesti kyseisten toimintojen lähdeasiakirjojen pyytämänä.|[Toimintaohje: Komponenttien siirtäminen toiminta-alueelle fyysisen varastoinnin perusmäärityksissä](warehouse-how-to-move-components-to-an-operation-area-in-basic-warehousing.md)|
|Suunnittele, mitä varastopaikkoja täytetään tai tyhjennetään tehokkaan nimikevirran ylläpitämiseksi (esimerkiksi irtotavaravaraston tyhjentäminen ennen suurta vastaanottoa).|[Fyysisen varaston siirtojen suunnitteleminen työkirjoissa](warehouse-how-to-plan-warehouse-movements-in-worksheets.md)|
|Päivitä taajuus, jolla varastopaikat (kuten poiminnan varastopaikat) täydennetään kysynnän vaihtelun seurauksena.|[Kuinka laskea var.paikan täydennys](warehouse-how-to-calculate-bin-replenishment.md)|
|Järjestä fyysinen varasto uudelleen uusilla varastopaikan koodeilla ja uusilla varastopaikan ominaispiirteillä sekä mahdollisesti vaihtamalla niiden paikkaa.|[Toimintaohje: Fyysisten varastojen järjesteleminen uudelleen](warehouse-how-to-restructure-warehouses.md)|  

## <a name="see-also"></a>Katso myös  
[Varastoinninhallinta](warehouse-manage-warehouse.md)  
[Vaihto-omaisuus](inventory-manage-inventory.md)  
[Varastoinninhallinnan määrittäminen](warehouse-setup-warehouse.md)     
[Kokoonpanon hallinta](assembly-assemble-items.md)    
[Rakennetiedot: Fyysisen varaston hallinta](design-details-warehouse-management.md)  
[[!INCLUDE[d365fin](includes/d365fin_md.md)] -ohjelman käyttäminen](ui-work-product.md)

