---
title: "Esimerkkiskenaario – dynaamisten kohdistamisten määrittäminen myytyjen nimikkeiden perusteella"
description: "Tässä aiheessa kuvataan esimerkki siitä, kuinka kohdistuksia määritetään käyttämällä dynaamista kohdistustapaa. Esimerkissä muutetaan MYYNTI-kustannuspaikan kustannusten dynaaminen kohdistaminen tukemaan uutta IT-LAITTEISTO -kustannuskohdetta. IT-LAITTEISTO-paketeissa ovat nimikenumerot välilä 8904-W – 8924-W. Osuus lasketaan edellisen vuoden myyntilukujen avulla. Kohdistus kirjataan apukustannuslajiin 9903."
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
ms.sourcegitcommit: a16640e014e157d4dbcaabc53d0df2d3e063f8f9
ms.openlocfilehash: 0d892099be95d52546d98bf17705df2b19f764c7
ms.contentlocale: fi-fi
ms.lasthandoff: 10/26/2017

---
# <a name="scenario-example-defining-dynamic-allocations-based-on-items-sold"></a>Esimerkkiskenaario: Dynaamisten kohdistamisten määrittäminen myytyjen nimikkeiden perusteella
Tässä aiheessa kuvataan esimerkki siitä, kuinka kohdistuksia määritetään käyttämällä dynaamista kohdistustapaa. Esimerkissä muutetaan MYYNTI-kustannuspaikan kustannusten dynaaminen kohdistaminen tukemaan uutta IT-LAITTEISTO -kustannuskohdetta. IT-LAITTEISTO-paketeissa ovat nimikenumerot välilä 8904-W – 8924-W. Osuus lasketaan edellisen vuoden myyntilukujen avulla. Kohdistus kirjataan apukustannuslajiin 9903.  

> [!NOTE]  
>  Esimerkissä käytetään demodataa [!INCLUDE[d365fin](includes/d365fin_md.md)]:sta.  

## <a name="to-define-dynamic-allocations-based-on-items-sold-in-the-previous-year"></a>Märitä edellisvuonna myyytihin nimikkeisiin perustuvat dynaamiset kohdistukset  

1.  Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, kirjoita **Kustannusten kohdistukset** ja valitse sitten aiheeseen liittyvä linkki.  
2.  Valitse **Kustannusten kohdistaminen** -ikkunassa **Uusi**-toiminto.  
3.  Paina **Tunnus**-kentässä Enter tai kirjoita tunnus.  
4.  Syötä **Taso**-kenttään **1**.  
5.  Syötä arvot **Voimassaolo alkaa**- ja **Voimassaolo päättyy** -kenttiin.  
6.  Syötä **Kustannuspaikkakoodi**-kenttään **MYYNTI**.  
7.  Syötä **Luotto kustannustyyppiin** -kenttään kustannustyyppi **9903**.  
8.  Syötä **Kohdekustannustyyppi** -kenttään kustannustyyppi **9903**.  
9. Valitse **Kohdekustannuskohde**-kentässä **Uusi**, luo uusi kustannuskohde IT-LAITTEISTO ja täytä kentät tarpeen mukaan. Valitse **IT-LAITTEET**. Jätä **Kohdekustannuspaikka**-kenttä tyhjäksi.  
10. Valitse **Kohdistuksen kohdetyyppi** -kentässä **Kaikki kustannukset** ja määritä, miten kaikki kertyneet kustannukset kohdistetaan.  
11. Valitse **Peruste**-kentässä kohdistusperuste **Nimikkeitä myyty (summa)**.  
12. Syötä **Nro suodatus** -kenttään **8904-W..8924-W**.  
13. Syötä **Päivämäärän suodatuskoodi** -kenttään **Edellinen vuosi**.  
14. Valitse **Laske kohdistusavain** -toiminto ja laske osuus.  

    > [!IMPORTANT]  
    >  [!INCLUDE[d365fin](includes/d365fin_md.md)] käyttää edellisen vuoden myyntilukuja laskettaessa 1596.50 PVA:n 100 prosentin osuus IT-LAITTEISTO -paketteja varten. Tämä tarkoittaa sitä, että kaikki viime vuonna myydyt nimikkeet kohdennetaan kustannuskohteelle IT-LAITTEISTO.  

## <a name="see-also"></a>Katso myös  
 [Suodattimien määrittäminen dynaamisen kohdistuksen perusteille.](finance-setting-filters-for-dynamic-allocation-bases.md)   
 [Toimintaohje: Kohdistuksen lähteen ja tavoitteiden määrittäminen](finance-how-to-set-up-allocation-source-and-targets.md)   
 [Kustannusten määrittäminen ja kohdistaminen](finance-define-and-allocate-costs.md)   
 [Termit kustannuslaskennassa](finance-terminology-in-cost-accounting.md)   
 [Tietoja kustannuslaskennasta](finance-about-cost-accounting.md)

