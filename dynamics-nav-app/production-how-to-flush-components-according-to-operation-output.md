---
title: Komponenttien materiaalinotto toiminnan tuotoksen mukaan
description: "Jos nimikkeiden määrityksessä on käytetty Taaksepäin-materiaalinottotapaa, oletustoiminto laskee ja kirjaa kulutuksen automaattisesti, kun vapautetun tuotantotilauksen tilaksi muutetaan **Valmis**. Lisätietoja on kohdassa Materiaalinottotapa."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 09/06/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 48645ff5d943b2f7093224289ff3cad6cfa6537e
ms.contentlocale: fi-fi
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-flush-components-according-to-operation-output"></a>Komponenttien materiaalinotto toiminnan tuotoksen mukaan
Jos nimikkeiden määrityksessä on käytetty Taaksepäin-materiaalinottotapaa, oletustoiminto laskee ja kirjaa kulutuksen automaattisesti, kun vapautetun tuotantotilauksen tilaksi muutetaan **Valmis**.  

Jos määrität myös reitityslinkin koodeja, laskenta ja kirjaus tehdään toiminnon valmistuttua. Toiminnon kuluttama todellinen määrä kirjataan. Lisätietoja on kohdassa [Toimintaohje: Reititysten luominen](production-how-to-create-routings.md).  

Tuotantotilauksessa voidaan esimerkiksi määrittää, että 800 metrin tuottaminen vaatii 8 kg komponentteja. Jos tuotokseksi kirjataan 200 metriä, kulutukseksi kirjataan automaattisesti 2 kg.  

Tämä toiminto on hyödyllinen seuraavista syistä:  

-   **Varaston arvostus** - Tuotoksen ja kulutuksen arvotapahtumat luodaan rinnakkain tuotantotilauksen edetessä. Ilman reitityslinkkien koodeja varastoarvo kasvaa, kun tuotos kirjataan ja vähenee sitten myöhemmin, kun komponentin kulutusarvo kirjataan yhdessä valmiin tuotantotilauksen kanssa.  
-   **Varastosaatavuus** - Asteittaista kulutuskirjausta käytettäessä komponenttinimikkeiden saatavuus on paremmin ajan tasalla, mikä on tärkeää kysynnän ja tarjonnan välilsen sisäisen tasapainon ylläpitämiseksi. Ilman reitityslinkkien koodeja muut osan vaatimukset voivat olettaa, että se on käytettävissä, niin kauan kuin se odottaa viivästynyttä kulukirjausta.  
-   **Just-in-Time** – Voit mukauttaa tuotteita asikkaan pyyntöjen mukaan ja siten minimoida jätteet varmistamalla, että työ- ja järjestelmämuutoksia tehdään vain tarvittaessa.  

Seuraavassa ohjeessa neuvotaan, miten taaksepäin suuntautuvan materiaalinoton ja reitityslinkkien koodit voidaan yhdistää niin, että materiaalinottomäärä toimintoa kohden on verrannollinen toiminnon todelliseen tuotokseen.  

## <a name="to-flush-components-according-to-operation-output"></a>Voit tyhjentää osat toiminnon tuotoksen mukaan  
1.  Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, kirjoita **Nimikkeet** ja valitse sitten aiheeseen liittyvä linkki.  
2.  Valitse **Muokkaa** -toiminto.  
3.  Valitse **Täydennys**-pikavälilehden **Materiaalinottotapa**-kentässä select **Eteenpäin**.  

    > [!NOTE]  
    >  Valitse **Poiminta + eteenpäin**, jos komponenttia käytetään ohjatuille hyllytyksille ja poiminnoille määritetyssä sijainnissa.  

4.  Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, kirjoita **Reititykset** ja valitse sitten aiheeseen liittyvä linkki.  
5.  Määritä reitityslinkkikoodit jokaiselle työvaiheelle, joka kuluttaa komponentin. Lisätietoja on kohdassa [Uusien reititysten luominen](production-how-to-create-routings.md).  
6.  Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, kirjoita **Tuotannon tuoterakenne** ja valitse sitten aiheeseen liittyvä linkki.  
7.  Määritä reitityslinkkikoodit kustakin komponentin esiintymästä toimintoon, jossa se kulutetaan.

    > [!IMPORTANT]  
    >  Osalla on oltava reitityslinkki viimeisimpään reititysoperaatioon.  

## <a name="see-also"></a>Katso myös  
[Toimintaohje: Uusien tuotannon tuoterakenteiden luominen](production-how-to-create-production-boms.md)  
[Tuotannon määrittäminen](production-configure-production-processes.md)  
[Tuotanto](production-manage-manufacturing.md)    
[Suunnittelu](production-planning.md)   
[Vaihto-omaisuus](inventory-manage-inventory.md)  
[Osto](purchasing-manage-purchasing.md)  
[[!INCLUDE[d365fin](includes/d365fin_md.md)] -ohjelman käyttäminen](ui-work-product.md)

