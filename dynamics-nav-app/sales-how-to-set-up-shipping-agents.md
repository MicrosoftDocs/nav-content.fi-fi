---
title: "Kuljetusliikkeiden määrittäminen"
description: "Voit määrittää koodin jokaiselle kuljetusliikkeelle, ja syöttää tietoja niistä."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 08/23/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: aa35d295c4c4f527a55394ca3777b978bd33e0b9
ms.contentlocale: fi-fi
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-set-up-shipping-agents"></a><span data-ttu-id="79f1c-103">Kuljetusliikkeiden määrittäminen</span><span class="sxs-lookup"><span data-stu-id="79f1c-103">How to: Set Up Shipping Agents</span></span>
<span data-ttu-id="79f1c-104">Voit määrittää koodin jokaiselle kuljetusliikkeelle ja antaa niitä koskevia tietoja.</span><span class="sxs-lookup"><span data-stu-id="79f1c-104">You can set up a code for each of your shipping agents and enter information about them.</span></span>  

<span data-ttu-id="79f1c-105">Jos syötät Internet-osoitteen kuljetusliikkeen kohdalle, ja jos kuljetusliike tarjoaa kollinseurantapalveluja Internetissä, voit käyttää ohjelman automaattista kollin seuranta -ominaisuutta.</span><span class="sxs-lookup"><span data-stu-id="79f1c-105">If you enter an Internet address for the shipping agent, and the agent provides package tracking services on the Internet, you can use the automatic package tracking feature.</span></span> <span data-ttu-id="79f1c-106">Lisätietoja on kohdassa [Toimintaohje: Kollien seuraaminen](sales-how-track-packages.md).</span><span class="sxs-lookup"><span data-stu-id="79f1c-106">For more information, see [How to: Track Packages](sales-how-track-packages.md).</span></span>

<span data-ttu-id="79f1c-107">Kun määrität kuljetusliikkeitä myyntitilauksillesi, voit määrittää myös kunkin kuljetusliikkeen tarjoamat palvelut.</span><span class="sxs-lookup"><span data-stu-id="79f1c-107">When you set up shipping agents on your sales orders, you can also specify the services that each shipping agent offers.</span></span>  
<span data-ttu-id="79f1c-108">Voit määrittää rajoittamattoman määrän palveluita jokaiselle kuljetusliikkeelle ja voit määrittää toimitusajan jokaiselle palvelulle.</span><span class="sxs-lookup"><span data-stu-id="79f1c-108">For each shipping agent, you can set up an unlimited number of services, and you can specify a shipping time for each service.</span></span>  

<span data-ttu-id="79f1c-109">Kun olet määrittänyt kuljetusliikkeen palvelun myyntitilausriville, palvelun toimitusaika sisällytetään sille riville toimituksen lupaamisen laskentaan.</span><span class="sxs-lookup"><span data-stu-id="79f1c-109">When you have assigned a shipping agent service to a sales order line, the shipping time of the service will be included in the order promising calculation, for that line.</span></span> <span data-ttu-id="79f1c-110">Lisätietoja on kohdassa [Toimintaohje: Toimituksen lupaamisen päivämäärän laskeminen](sales-how-to-calculate-order-promising-dates.md).</span><span class="sxs-lookup"><span data-stu-id="79f1c-110">For more information, see [How to: Calculate Order Promising Dates](sales-how-to-calculate-order-promising-dates.md).</span></span>

## <a name="to-set-up-a-shipping-agent"></a><span data-ttu-id="79f1c-111">Kuljetusliikkeiden määrittäminen</span><span class="sxs-lookup"><span data-stu-id="79f1c-111">To set up a shipping agent</span></span>  
1.  <span data-ttu-id="79f1c-112">Valitse ![Etsiä sivu tai raportti](media/ui-search/search_small.png "Etsiä sivu tai raportti -kuvake") -kuvake, kirjoita **Kuljetusliikkeet** ja valitse sitten aiheeseen liittyvät linkki.</span><span class="sxs-lookup"><span data-stu-id="79f1c-112">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Shipping Agents**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="79f1c-113">Täytä tarvittavat kentät.</span><span class="sxs-lookup"><span data-stu-id="79f1c-113">Fill in the fields as necessary.</span></span> [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]<span data-ttu-id="79f1c-114">.</span><span class="sxs-lookup"><span data-stu-id="79f1c-114">.</span></span>  
3.  <span data-ttu-id="79f1c-115">Valitse **Kuljetusliikkeen palvelut** -toiminto.</span><span class="sxs-lookup"><span data-stu-id="79f1c-115">Choose the **Shipping Agent Services** action.</span></span>
4. <span data-ttu-id="79f1c-116">Täytä tarvittavat **Kuljetusliikkeen palvelut** -kentät.</span><span class="sxs-lookup"><span data-stu-id="79f1c-116">In the **Shipping Agent Services**, fill in the fields as necessary.</span></span>

> [!NOTE]  
>  <span data-ttu-id="79f1c-117">Jos poistat kuljetusliikkeen tilausriviltä, ohjelma poistaa riviltä myös kuljetusliikkeen palvelukoodin.</span><span class="sxs-lookup"><span data-stu-id="79f1c-117">If you delete the shipping agent on the order line, the shipping agent service code is also deleted.</span></span> <span data-ttu-id="79f1c-118">Ohjelma laskee sen jälkeen uudelleen kenttien tiedot, jotka perustuivat osittain kuljetusliikkeiden palveluihin.</span><span class="sxs-lookup"><span data-stu-id="79f1c-118">The contents of fields that were based in part on the shipping agent service are recalculated.</span></span>  

## <a name="see-also"></a><span data-ttu-id="79f1c-119">Katso myös</span><span class="sxs-lookup"><span data-stu-id="79f1c-119">See Also</span></span>
<span data-ttu-id="79f1c-120">[Kollien seuraaminen](sales-how-track-packages.md)  </span><span class="sxs-lookup"><span data-stu-id="79f1c-120">[How to: Track Packages](sales-how-track-packages.md)  </span></span>  
[<span data-ttu-id="79f1c-121">Varastoinninhallinta</span><span class="sxs-lookup"><span data-stu-id="79f1c-121">Warehouse Management</span></span>](warehouse-manage-warehouse.md)  
[<span data-ttu-id="79f1c-122">Vaihto-omaisuus</span><span class="sxs-lookup"><span data-stu-id="79f1c-122">Inventory</span></span>](inventory-manage-inventory.md)  
<span data-ttu-id="79f1c-123">[Varastoinninhallinnan määrittäminen](warehouse-setup-warehouse.md)   </span><span class="sxs-lookup"><span data-stu-id="79f1c-123">[Setting Up Warehouse Management](warehouse-setup-warehouse.md)   </span></span>  
<span data-ttu-id="79f1c-124">[Kokoonpanon hallinta](assembly-assemble-items.md)  </span><span class="sxs-lookup"><span data-stu-id="79f1c-124">[Assembly Management](assembly-assemble-items.md)  </span></span>  
[<span data-ttu-id="79f1c-125">Rakennetiedot: Fyysisen varaston hallinta</span><span class="sxs-lookup"><span data-stu-id="79f1c-125">Design Details: Warehouse Management</span></span>](design-details-warehouse-management.md)  
<span data-ttu-id="79f1c-126">[[!INCLUDE[d365fin](includes/d365fin_md.md)] -ohjelman käyttäminen](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="79f1c-126">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>  

