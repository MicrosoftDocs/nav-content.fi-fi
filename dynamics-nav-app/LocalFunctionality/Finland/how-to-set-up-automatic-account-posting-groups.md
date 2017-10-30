---
title: "Automaattisten tilin kirjausryhmien määrittäminen"
description: "Voit käyttää automaattisia tilikoodeja automaattisen tilin kirjausryhmän luonnin jälkeen."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 07/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: b9b1f062ee6009f34698ea2cf33bc25bdd5b11e4
ms.openlocfilehash: ceaf004fa0bee9383126065e5f5d680bc343291e
ms.contentlocale: fi-fi
ms.lasthandoff: 10/23/2017

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
 [Kokonaissaldo](../Sweden/total-balance.md)   
 [Kirjausryhmien määrittäminen](../../finance-posting-groups.md)  
 [Rahoitus](../../finance.md)

