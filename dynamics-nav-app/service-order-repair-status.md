---
title: "Huoltotilausten ja -korjausten tilan määrittäminen"
description: "Sinun on määritettävä yhdeksän korjauksen tilan vaihtoehtoa, jotka ilmaisevat huoltotilauksissa olevien huoltonimikkeiden korjauksen edistymisen ja ylläpidon."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 07/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: d7dbc4cfc06d4c74476a04512bd368a0ab26f837
ms.contentlocale: fi-fi
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-set-up-statuses-for-service-orders-and-repairs"></a>Toimintaohje: Huoltotilausten ja -korjausten tilan määrittäminen
Sinun on määritettävä korjauksen tilan vaihtoehdot, jotka ilmaisevat huoltotilauksissa olevien huoltonimikkeiden korjauksen edistymisen ja ylläpidon. Sinun on määritettävä vähintään yhdeksän korjauksen tilan vaihtoehtoa, jotka ilmaisevat tilanteet tai suoritettavat toimenpiteet huoltonimikkeiden huoltamisen aikana.  

Voit määrittää huoltotilauksen tilavaihtoehtojen prioriteettitasot. Prioriteetteja on neljä: Matala, Melko matala, Melko korkea ja Korkea.  
  
Kun huoltotilauksessa olevan huoltonimikkeen korjauksen tilaa muutetaan, ohjelma päivittää huoltotilauksen tilan. Kunkin huoltonimikkeen korjauksen tila on linkitetty huoltotilauksen tilaan. Jos huoltonimikkeet on linkitetty kahteen tai useampaan huoltotilauksen tilan vaihtoehtoon, ohjelma valitsee huoltotilauksen tilan, jolla on korkein prioriteetti.  

## <a name="to-set-up-a-repair-status"></a>Korjauksen tilan määrittäminen  
1. Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, kirjoita **Korjauksen tila** ja valitse sitten aiheeseen liittyvä linkki. 2. Luo uusi korjauksen tila.  
3. Täytä **Koodi**- ja **Kuvaus**-kentät.  
4. Valitse **Huoltotilauksen tila** -kentässä tilauksen tila, johon korjaus linkitetään. Valitsemasi huoltotilauksen tilan prioriteetti näkyy **Prioriteetti**-kentässä.  
5. Valitse korjauksen tila. Voit valita vain yhden tilan.  
6. Valitse **Kirjaaminen sallittu** -kenttä, jos sallit huoltotilausten, myös huoltonimikkeiden kirjaamisen tämän korjauksen tilan yhteydessä.  
7. Valitse **Odottava-tila sallittu** -valintaruutu, jos haluat sallia, että sellaisten huoltonimikkeitä sisältävän huoltotilauksien tilaksi voidaan manuaalisesti vaihtaa **Odottava**, joiden korjaustila se on.  
8. Valitse **Työn alla -tila sallittu**-, **Valmis-tila sallittu**- ja **Estossa-tila sallittu**-valintaruudut samalla tavoin.
  
## <a name="to-set-up-service-status-priorities"></a>Huoltotilan prioriteettien määrittäminen  
1. Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, kirjoita **Huoltotilauksen tila** ja valitse sitten aiheeseen liittyvä linkki.  
2. Valitse huoltotilauksen tila, jolle haluat määrittää prioriteetin.  
3. Valitse **Prioriteetti**-kentässä kyseisen huoltotilauksen tilan prioriteetti. Toista tämä vaihe kunkin tilan kohdalla.  
  
## <a name="see-also"></a>Katso myös  
[Tietoja huoltotilauksen tilasta ja korjauksen tilasta]()  
[Huoltohallinnon määrittäminen](service-setup-service.md)  

