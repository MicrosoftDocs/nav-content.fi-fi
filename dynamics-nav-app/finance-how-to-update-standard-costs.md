---
title: "Vakiokustannusten päivittäminen"
description: "Komponenttien vakiokustannukset on päivitettävä säännöllisesti ja uudet kustannukset on vyörytettävä päänimikkeelle."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 08/09/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: b9b1f062ee6009f34698ea2cf33bc25bdd5b11e4
ms.openlocfilehash: dd2bb16af611be7f7720fdf07eb65fd268aba039
ms.contentlocale: fi-fi
ms.lasthandoff: 10/23/2017

---
# <a name="how-to-update-standard-costs"></a>Vakiokustannusten päivittäminen
Komponenttien vakiokustannukset on päivitettävä säännöllisesti ja uudet kustannukset on vyörytettävä päänimikkeelle. Prosessi sisältää yleensä seuraavat neljä vaihetta:  

1.  Päivitä kustannukset osa- ja kapasiteettitasolla. Lisätietoja on kohdassa **Ehdota nimikkeen vakiokust.** -eräajo.  
2.  Yhdistä ja kokoa osa- ja kapasiteettikustannukset laskeaksesi nimikkeiden tuotannon tai kokoonpanon kokonaiskustannuksen.  
3.  Ota käyttöön edellisten eräajojen aikana syötetyt vakiokustannukset. Vakiokustannukset eivät tule voimaan, ennen kuin ne on otettu käyttöön. Lisätietoja on ohjeaiheessa Ota käyttöön vakiokustannusten muutokset.  
4.  Ota muutokset käyttöön nimikkeen kortin **Yksikkökustannus**-kentän päivittämistä ja varaston uudelleenarvostuksen suorittamista varten. Lisätietoja on kohdassa [Toimintaohje: Varaston uudelleenarvostus](inventory-how-revalue-inventory.md).  

Lisätietoja on kohdassa [Tietoja vakiokustannusten laskennasta](finance-about-calculating-standard-cost.md).  
## <a name="to-update-standard-costs"></a>Vakiokustannusten päivittäminen  
1.  Suorita **Muuta kustannuksia - Nimiketapahtumat** -eräajo.  
2.  Suorita **Kirjaa varaston kust. KP:oon** -eräajo.  
3.  Avaa **Vakiokust. työkirja** ja käytä vähintään yhtä seuraavista toiminnoista:  

    1.  Suorita **Ehdota nimikkeen vakiokust.** -eräajo.  
    2.  Tarkasta tulokset ja tee tarvittavat muutokset.  
    3.  Suorita **Ehdota kapasiteetin vakiokustannusta** -eräajo.  
    4.  Tarkasta tulokset ja tee tarvittavat muutokset.
    5. Suorita **Vyörytä vakiokustannus** -eräajo.
    6.  Tarkasta tulokset ja tee tarvittavat muutokset.
    7.  Suorita **Ota käyttöön vakiokustannusten muutokset** -eräajo.  
4.  Tarkasta ja kirjaa **Uudelleenarvostus pvk** -ikkuna, jonka tapahtumat on täytetty tämän prosessin aiemmissa vaiheissa.  

## <a name="see-also"></a>Katso myös  
 [Tietoja standardikustannuksen laskemisesta](finance-about-calculating-standard-cost.md)   
 [Varaston kustannusten hallinta](finance-manage-inventory-costs.md)   
 [Rakennetiedot: arvostusmenetelmät](design-details-costing-methods.md) [[Rahoitus](finance.md)]  
 [[!INCLUDE[d365fin](includes/d365fin_md.md)] -ohjelman käyttäminen](ui-work-product.md)  

