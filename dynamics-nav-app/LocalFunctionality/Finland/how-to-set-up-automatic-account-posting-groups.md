---
title: "Automaattisten tilin kirjausryhmien määrittäminen"
description: "Voit käyttää automaattisia tilikoodeja automaattisen tilin kirjausryhmän luonnin jälkeen."
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
ms.openlocfilehash: d6728cb5f5ad9a585b8d6bf8a227b169d538021d
ms.contentlocale: fi-fi
ms.lasthandoff: 10/26/2017

---
# <a name="how-to-set-up-automatic-account-posting-groups"></a>Toimintaohje: Automaattisten tilin kirjausryhmien määrittäminen
Voit käyttää automaattisia tilikoodeja automaattisen tilin kirjausryhmän luonnin jälkeen.  

## <a name="to-set-up-automatic-account-posting-groups"></a>Automaattisten tilin kirjausryhmien määrittäminen  

1.  Valitse ![Etsi sivu tai raportti -kuvake](../../media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, kirjoita **Automaattijakauma** ja valitse sitten aiheeseen liittyvä linkki.  
2.  Valitse **Uusi**-toiminto.  
3.  Täytä **Yleinen**-pikavälilehden kentät seuraavassa taulukossa kuvatulla tavalla.  

    |Kenttä|Description|  
    |-----------|-----------------|  
    |**Nro**|Anna automaattiselle tilin kirjausryhmälle yksilöivä aakkosnumeerinen numero.|  
    |**Kuvaus**|Anna automaattisen tilin kirjausryhmän kuvaus.|  

4.  Täytä **Automaattinen tilirivi** -pikavälilehden kentät seuraavassa taulukossa kuvatulla tavalla.  

    |Kenttä|Description|  
    |-----------|-----------------|  
    |**Kohdistusprosentti**|Anna lähderivin summan kohdistettava prosentti.|  
    |**KP-tilinro**|Anna kirjanpitotilin numero, jolle kohdistus kirjataan.|  

    > [!NOTE]  
    >  **Kokonaissaldo**-kentässä lasketaan yhteen kirjausryhmän automaattisten tilirivien **Kohdistusprosentti**-kentän arvot. Jos kirjausryhmän kokonaiskohdistusprosentti ei ole nolla, nimikkeen kirjauksen yhteydessä näytetään virhesanoma.  

5.  Valitse **OK**-painike.  

## <a name="see-also"></a>Katso myös  
 [Automaattiset tilikoodit](automatic-account-codes.md)   
 [Kirjausryhmien määrittäminen](../../finance-posting-groups.md)  
 [Rahoitus](../../finance.md)

