---
title: "Kriteerit pääkirjanpidon tapahtumien siirtämiseksi kustannustapahtumiin"
description: "On tärkeää ymmärtää ehdot, joiden mukaan pääkirjanpidon tapahtumat siirretään kustannustapahtumiin. **Siirrä KP-tapahtumat kustannuslaskentaan** -eräajo käyttää määrittää siirron aikana seuraavien kriteerien avulla, siirretäänkö pääkirjanpidon tapahtumat ja milloin ne mahdollisesti siirretään."
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
ms.openlocfilehash: 99b18cee56b6300cb1852265eed6d56206a2eaab
ms.contentlocale: fi-fi
ms.lasthandoff: 10/16/2017

---
# <a name="criteria-for-transferring-general-ledger-entries-to-cost-entries"></a>Kriteerit pääkirjanpidon tapahtumien siirtämiseksi kustannustapahtumiin
On tärkeää ymmärtää ehdot, joiden mukaan pääkirjanpidon tapahtumat siirretään kustannustapahtumiin. Siirron aikana **Siirrä KP-tapahtumat kustannuslaskentaan** -eräajo käyttää seuraavia kriteerejä määrittääkseen, jos ja miten pääkirjanpidon tapahtumat siirretään.  

Kirjanpitotapahtumat siirretään, jos:  

-   Tapahtumilla on dimensioarvot, jotka vastaavat kustannuspaikkaa tai kustannuskohdetta.  
-   Tapahtumilla on dimensioarvot, jotka vastaavat kustannuspaikkaa ja kustannuskohdetta. Kustannuspaikka ratkaisee asian näiden tapahtumien kohdalla. Näin vältetään tilanne, jossa kustannustyyppi näkyy sekä kustannuskohteessa että kustannuspaikassa ja näin ollen ne lasketaan tilastoihin kahdesti.  
-   Asiakirjan numeroa ei ole tapahtumissa, joten kustannustapahtumissa näytetään asiakirjanumeron kohdalla 0000.  
-   Tapahtumat siirretään kustannustyypille, jolla yhdistettyjä tapahtumia voidaan käsitellä, ja tapahtumat siirretään yhdistettynä joko kuukausittain tai päivittäin.  

Kirjanpitotapahtumia ei siirretä, jos:  

-   Tapahtumilla on dimensioarvot, jotka eivät vastaa kustannuspaikkaa tai kustannuskohdetta.  
-   Tapahtumien summa on nolla.  
-   Tapahtumissa on poistettu KP-tili.  
-   Tapahtumissa on KP-tili, joka ei ole **Tuloslaskelma**-tyyppiä  
-   Tapahtumissa on KP-tili, jolle ei ole määritetty kustannustyyppiä.  
-   Tapahtumien kirjauspäivämäärä on ennen **KP-siirron alkamispäivämäärää**.  
-   Tapahtumille on kirjattu sulkemispäivämäärä. Tässä on tyypillisiä tapahtumia, jotka palauttavat tuloslaskelman saldon vuoden lopussa.  

## <a name="see-also"></a>Katso myös  
[Kustannuslaskenta](finance-manage-cost-accounting.md)  
 [Pääkirjanpidon tapahtumien siirtäminen kustannustapahtumiin](finance-how-to-transfer-general-ledger-entries-to-cost-entries.md)   
 [Kustannustapahtumien siirtäminen ja kirjaaminen](finance-transfer-and-post-cost-entries.md)   
 [Tietoja kustannuslaskennasta](finance-about-cost-accounting.md)  
 [[!INCLUDE[d365fin](includes/d365fin_md.md)] -ohjelman käyttäminen](ui-work-product.md)

