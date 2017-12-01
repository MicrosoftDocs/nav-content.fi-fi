---
title: "Rakenteen tiedot - kirjausliittymän rakenne"
description: "Tässä aiheessa on yleiskatsaus kirjausliittymän rakenteen yleisistä toimintaohjeista."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: posting, interface, design
ms.date: 07/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 1dfba8b14019991c95f40ffd5f7fbaed5df414eb
ms.openlocfilehash: e262cb3f6464942f6e123d8545ec4fd8d386190b
ms.contentlocale: fi-fi
ms.lasthandoff: 12/01/2017

---
# <a name="design-details-posting-interface-structure"></a><span data-ttu-id="dfed2-103">Rakenteen tiedot: Kirjausliittymän rakenne</span><span class="sxs-lookup"><span data-stu-id="dfed2-103">Design Details: Posting Interface Structure</span></span>
<span data-ttu-id="dfed2-104">[!INCLUDE[d365fin](includes/d365fin_md.md)] -kirjausliittymän rakenteessa on useita globaaleja proseduureja, jotka käyttävät samaa rakennetta:</span><span class="sxs-lookup"><span data-stu-id="dfed2-104">In the [!INCLUDE[d365fin](includes/d365fin_md.md)] posting interface structure, there are several global procedures that use the same structure:</span></span>  
  
* <span data-ttu-id="dfed2-105">RunWithCheck- ja RunWithoutCheck-kutsuproseduurin Code – yleinen vakiopäiväkirjarivin kirjausliittymä.</span><span class="sxs-lookup"><span data-stu-id="dfed2-105">RunWithCheck and RunWithoutCheck call procedure Code – generic posting interface for Gen. Jnl Line.</span></span>  
* <span data-ttu-id="dfed2-106">CustPostApplyCustLedgEntry – asiakkaan kirjaussovellus, kutsuja on koodiyksikkö 226 CustEntry-käytä kirjattuja tapahtumia.</span><span class="sxs-lookup"><span data-stu-id="dfed2-106">CustPostApplyCustLedgEntry – post customer application, called from codeunit 226 CustEntry-Apply Posted Entries.</span></span>  
* <span data-ttu-id="dfed2-107">VendPostApplyVendLedgEntry – toimittajasovelluksen kirjaus, kutsuja on koodiyksikkö 227 VendEntry-käytä kirjattuja tapahtumia.</span><span class="sxs-lookup"><span data-stu-id="dfed2-107">VendPostApplyVendLedgEntry – post vendor application, called from codeunit 227 VendEntry-Apply Posted Entries.</span></span>  
* <span data-ttu-id="dfed2-108">UnapplyCustLedgEntry – peruuta asiakassovelluksen kirjaus, kutsuja on koodiyksikkö 226 CustEntry-käytä kirjattuja tapahtumia.</span><span class="sxs-lookup"><span data-stu-id="dfed2-108">UnapplyCustLedgEntry – post unapply of customer application, called from codeunit 226 CustEntry-Apply Posted Entries</span></span>  
* <span data-ttu-id="dfed2-109">UnapplyVendLedgEntry – peruuta toimittajasovelluksen kirjaus, kutsuja on koodiyksikkö 227 VendEntry-käytä kirjattuja tapahtumia.</span><span class="sxs-lookup"><span data-stu-id="dfed2-109">UnapplyVendLedgEntry – post unapply of vendor application, called from codeunit 227 VendEntry-Apply Posted Entries</span></span>  
  
## <a name="see-also"></a><span data-ttu-id="dfed2-110">Katso myös</span><span class="sxs-lookup"><span data-stu-id="dfed2-110">See Also</span></span>  
[<span data-ttu-id="dfed2-111">Rakenteen tiedot: Kirjausohjelman rakenne</span><span class="sxs-lookup"><span data-stu-id="dfed2-111">Design Details: Posting Engine Structure</span></span>](design-details-posting-engine-structure.md)
