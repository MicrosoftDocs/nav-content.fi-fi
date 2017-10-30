---
title: "Rakennetiedot - suunnitellun negatiivisen varaston käsittely"
description: "Jälkitilauspiste ilmaisee ennakkokysynnän nimikkeen läpimenoajan aikana. Kun uusintatilauspiste on ohitettu, on aika tilata lisää. Mutta arvioidun varaston on oltava riittävän suuri kysynnän kattamiseksi, kunnes uusi tilaus vastaanotetaan. Tänä aikana varmuusvaraston tulisi huolehtia kysynnän vaihteluista palvelun kohdetasolle asti."
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
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 66cf357ccd0489d789ec9c2036734ec9f04aad95
ms.contentlocale: fi-fi
ms.lasthandoff: 10/16/2017

---
# <a name="design-details-handling-projected-negative-inventory"></a><span data-ttu-id="0249b-106">Rakennetiedot: suunnitellun negatiivisen varaston käsittely</span><span class="sxs-lookup"><span data-stu-id="0249b-106">Design Details: Handling Projected Negative Inventory</span></span>
<span data-ttu-id="0249b-107">Jälkitilauspiste ilmaisee ennakkokysynnän nimikkeen läpimenoajan aikana.</span><span class="sxs-lookup"><span data-stu-id="0249b-107">The reorder point expresses the anticipated demand during the lead time of the item.</span></span> <span data-ttu-id="0249b-108">Kun uusintatilauspiste on ohitettu, on aika tilata lisää.</span><span class="sxs-lookup"><span data-stu-id="0249b-108">When the reorder point is passed, it is time to order more.</span></span> <span data-ttu-id="0249b-109">Mutta arvioidun varaston on oltava riittävän suuri kysynnän kattamiseksi, kunnes uusi tilaus vastaanotetaan.</span><span class="sxs-lookup"><span data-stu-id="0249b-109">But the projected inventory must be large enough to cover the demand until the new order is received.</span></span> <span data-ttu-id="0249b-110">Tänä aikana varmuusvaraston tulisi huolehtia kysynnän vaihteluista palvelun kohdetasolle asti.</span><span class="sxs-lookup"><span data-stu-id="0249b-110">Meanwhile, the safety stock should take care of fluctuations in demand up to a targeted service level.</span></span>  

 <span data-ttu-id="0249b-111">Näin ollen suunnittelujärjestelmä katsoo sen hätätapaukseksi, jos tulevaa kysyntää ei voida toimittaa suunnitellusta varastosta tai toisella tavalla ilmaistuna, suunniteltu varasto muuttuu negatiiviseksi.</span><span class="sxs-lookup"><span data-stu-id="0249b-111">Consequently, the planning system considers it an emergency if a future demand cannot be served from the projected inventory, or expressed in another way, that the projected inventory goes negative.</span></span> <span data-ttu-id="0249b-112">Tällaisen poikkeuksen tapahtuessa järjestelmä ehdottaa uutta toimitustilausta, joka vastaa kysyntää, jota varasto tai toinen tarjonta ei täytä.</span><span class="sxs-lookup"><span data-stu-id="0249b-112">The system deals with such an exception by suggesting a new supply order to meet the part of the demand that cannot be met by inventory or other supply.</span></span> <span data-ttu-id="0249b-113">Uuden toimitustilauksen koko ei ota huomioon maksimivarastoa tai jälkitilausmäärää, eikä se ota huomioon tilauksen muokkaajia maksimitilausmäärä, minimitilausmäärä ja tilauksen moninkertaistaminen.</span><span class="sxs-lookup"><span data-stu-id="0249b-113">The order size of the new supply order will not take the maximum inventory or the reorder quantity into consideration, nor will it take into consideration the order modifiers Maximum Order Quantity, Minimum Order Quantity, and Order Multiple.</span></span> <span data-ttu-id="0249b-114">Sen sijaan se vastaa täsmällistä puutetta.</span><span class="sxs-lookup"><span data-stu-id="0249b-114">Instead, it will reflect the exact deficiency.</span></span>  

 <span data-ttu-id="0249b-115">Tämän tyyppisen toimitustilauksen suunnittelurivillä näytetään Hätävaroituskuvake ja lisätietoa annetaan sitä haettaessa tiedottamaan käyttäjää tilanteesta.</span><span class="sxs-lookup"><span data-stu-id="0249b-115">The planning line for this type of supply order will display an Emergency warning icon, and additional information will be provided upon lookup to inform the user of the situation.</span></span>  

 <span data-ttu-id="0249b-116">Seuraavassa kuvassa tarjonta D vastaa hätätilausta negatiivisen varaston muuttamiseksi.</span><span class="sxs-lookup"><span data-stu-id="0249b-116">In the following illustration, supply D represents an emergency order to adjust for negative inventory.</span></span>  

 ![](media/nav_app_supply_planning_2_negative_inventory.png "NAV_APP_supply_planning_2_negative_inventory")  

1.  <span data-ttu-id="0249b-117">Tarjonta **A**, alunperin suunniteltu varasto, on jälkitilauspisteen alapuolella.</span><span class="sxs-lookup"><span data-stu-id="0249b-117">Supply **A**, initial projected inventory, is below reorder point.</span></span>  

2.  <span data-ttu-id="0249b-118">Luodaan uusi eteenpäin aikataulutettu tarjonta (**C**).</span><span class="sxs-lookup"><span data-stu-id="0249b-118">A new forward-scheduled supply is created (**C**).</span></span>  

     <span data-ttu-id="0249b-119">(Määrä = enimmäisvarasto – suunniteltu varastotaso)</span><span class="sxs-lookup"><span data-stu-id="0249b-119">(Quantity = Maximum Inventory – Projected Inventory Level)</span></span>  

3.  <span data-ttu-id="0249b-120">Tarjonta **A** on suljettu kysynnän **B** johdosta, jota ei täysin katettu.</span><span class="sxs-lookup"><span data-stu-id="0249b-120">Supply **A** is closed by demand **B**, which is not fully covered.</span></span>  

     <span data-ttu-id="0249b-121">(Tarjonta **B** voi yrittää aikatauluttaa tarjontaa C, mutta se ei tapahdu aikavälikäsitteen mukaisesti.)</span><span class="sxs-lookup"><span data-stu-id="0249b-121">(Demand **B** could try to schedule Supply C in but that will not happen according to the time-bucket concept.)</span></span>  

4.  <span data-ttu-id="0249b-122">Uusi tarjonta (**D**) on luotu kattamaan jäljellä olevan määrän kysynnässä **B**.</span><span class="sxs-lookup"><span data-stu-id="0249b-122">New supply (**D**) is created to cover the remaining quantity on Demand **B**.</span></span>  

5.  <span data-ttu-id="0249b-123">Kysyntä **B** on suljettu (luodaan muistutusta suunniteltuun varastoon).</span><span class="sxs-lookup"><span data-stu-id="0249b-123">Demand **B** is closed (creating a reminder to the projected inventory).</span></span>  

6.  <span data-ttu-id="0249b-124">Uusi tarjonta **D** on suljettu.</span><span class="sxs-lookup"><span data-stu-id="0249b-124">The new supply **D** is closed.</span></span>  

7.  <span data-ttu-id="0249b-125">Suunniteltu varasto on valittuna; uusintatilauspistettä ei ole ylitetty.</span><span class="sxs-lookup"><span data-stu-id="0249b-125">Projected Inventory is checked; reorder point has not been crossed.</span></span>  

8.  <span data-ttu-id="0249b-126">Tarjonta **C** on suljettu (kysyntää ei enää ole).</span><span class="sxs-lookup"><span data-stu-id="0249b-126">Supply **C** is closed (no more demand exists).</span></span>  

9. <span data-ttu-id="0249b-127">Lopullinen tarkastus: avoimia varaston tason muistutuksia ei ole olemassa.</span><span class="sxs-lookup"><span data-stu-id="0249b-127">Final check: No outstanding inventory level reminders exist.</span></span>  

> [!NOTE]  
>  <span data-ttu-id="0249b-128">Vaihe 4 kuvaa sitä, miten järjestelmä reagoi versiota Microsoft Dynamics NAV 2009 SP1 edeltävissä versioissa.</span><span class="sxs-lookup"><span data-stu-id="0249b-128">Step 4 reflects how the system reacts in versions earlier than Microsoft Dynamics NAV 2009 SP1.</span></span>  

 <span data-ttu-id="0249b-129">Tämä päättää uusintatilaustapoihin perustuvaan varaston suunnitteluun liittyvien keskeisten periaatteiden kuvauksen.</span><span class="sxs-lookup"><span data-stu-id="0249b-129">This concludes the description of central principles relating to inventory planning based on reordering policies.</span></span> <span data-ttu-id="0249b-130">Seuraavassa osassa kuvataan neljän tuetun jälkitilausohjeen ominaisuudet.</span><span class="sxs-lookup"><span data-stu-id="0249b-130">The following section describes the characteristics of the four supported reordering policies.</span></span>  

## <a name="see-also"></a><span data-ttu-id="0249b-131">Katso myös</span><span class="sxs-lookup"><span data-stu-id="0249b-131">See Also</span></span>  
 <span data-ttu-id="0249b-132">[Rakennetiedot: uusintatilauskäytännöt](design-details-reordering-policies.md) </span><span class="sxs-lookup"><span data-stu-id="0249b-132">[Design Details: Reordering Policies](design-details-reordering-policies.md) </span></span>  
 <span data-ttu-id="0249b-133">[Rakennetiedot: suunnittelun parametrit](design-details-planning-parameters.md) </span><span class="sxs-lookup"><span data-stu-id="0249b-133">[Design Details: Planning Parameters](design-details-planning-parameters.md) </span></span>  
 <span data-ttu-id="0249b-134">[Rakennetiedot: uusintatilauskäytäntöjen käsittely](design-details-handling-reordering-policies.md) </span><span class="sxs-lookup"><span data-stu-id="0249b-134">[Design Details: Handling Reordering Policies](design-details-handling-reordering-policies.md) </span></span>  
 [<span data-ttu-id="0249b-135">Rakennetiedot: Tarjonnan suunnittelu</span><span class="sxs-lookup"><span data-stu-id="0249b-135">Design Details: Supply Planning</span></span>](design-details-supply-planning.md)

