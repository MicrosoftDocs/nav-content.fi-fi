---
title: "Sijaintikortin ja siirtoreittien määrittäminen"
description: "Jokaisille varastoitavalle varastonimikkeelle luodaan sijaintikortti, kuten varasto tai jakelukeskus. Lisäksi sijaintien välille määritetään siirtoreitit."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: warehouse, distribution center
ms.date: 06/02/2017
ms.author: SorenGP
ms.translationtype: HT
ms.sourcegitcommit: 1dfba8b14019991c95f40ffd5f7fbaed5df414eb
ms.openlocfilehash: 2a0d35e11b6a0ee480cf0034c885157fe1de3916
ms.contentlocale: fi-fi
ms.lasthandoff: 12/01/2017

---
# <a name="how-to-set-up-locations"></a><span data-ttu-id="b536b-103">Sijaintien määrittäminen</span><span class="sxs-lookup"><span data-stu-id="b536b-103">How to: Set Up Locations</span></span>
<span data-ttu-id="b536b-104">Jos ostat, varastoit tai myyt nimikkeitä useamman varaston avulla, sijaintikortti ja siirtoreitit on määritettävä jokaiselle sijainnille.</span><span class="sxs-lookup"><span data-stu-id="b536b-104">If you buy, store, or sell items at more than one place or warehouse, you must set each location up with a location card and define transfer routes.</span></span>

<span data-ttu-id="b536b-105">Voit sitten luoda asiakirjarivejä tietylle sijainnille, tarkastella saatavuutta sijainnin perusteella ja siirtää varastonimikkeitä sijainnista toiseen.</span><span class="sxs-lookup"><span data-stu-id="b536b-105">You can then create document lines for a specific location, view availability by location, and transfer inventory between locations.</span></span> <span data-ttu-id="b536b-106">Lisätietoja on myös kohdassa [Varaston hallinta](inventory-manage-inventory.md).</span><span class="sxs-lookup"><span data-stu-id="b536b-106">For more information, see [Manage Inventory](inventory-manage-inventory.md).</span></span>

## <a name="to-create-a-location-card"></a><span data-ttu-id="b536b-107">Sijaintikortin luominen</span><span class="sxs-lookup"><span data-stu-id="b536b-107">To create a location card</span></span>
1. <span data-ttu-id="b536b-108">Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, kirjoita **Sijainnit** ja valitse sitten aiheeseen liittyvä linkki.</span><span class="sxs-lookup"><span data-stu-id="b536b-108">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Locations**, and then choose the related link.</span></span>
2. <span data-ttu-id="b536b-109">Valitse **Uusi**-toiminto.</span><span class="sxs-lookup"><span data-stu-id="b536b-109">Choose the **New** action.</span></span>
3. <span data-ttu-id="b536b-110">Täytä **Sijaintikortti**-ikkunassa tarvittavat kentät.</span><span class="sxs-lookup"><span data-stu-id="b536b-110">In the **Location Card** window, fill in the fields as necessary.</span></span> [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]
4. <span data-ttu-id="b536b-111">Toista vaiheet 2 ja 3 jokaiselle sijainnille, jossa haluat pitää varastoa.</span><span class="sxs-lookup"><span data-stu-id="b536b-111">Repeat steps 2 and 3 for every location where you want to keep inventory.</span></span>

> [!NOTE]  
> <span data-ttu-id="b536b-112">Monet sijaintikortin kentät viittaavat saapuvien ja lähtevien varastoprosessien nimikkeiden käsittelyyn.</span><span class="sxs-lookup"><span data-stu-id="b536b-112">Many fields on the location card refer to the handling of items in inbound and outbound warehouse processes.</span></span> <span data-ttu-id="b536b-113">Lisätietoja on kohdassa [Varastoinninhallinnan määrittäminen](warehouse-setup-warehouse.md).</span><span class="sxs-lookup"><span data-stu-id="b536b-113">For more information, see [Setting Up Warehouse Management](warehouse-setup-warehouse.md).</span></span>

## <a name="to-create-a-transfer-route"></a><span data-ttu-id="b536b-114">Siirtoreittien luominen</span><span class="sxs-lookup"><span data-stu-id="b536b-114">To create a transfer route</span></span>
1. <span data-ttu-id="b536b-115">Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, anna **Sijainnit** ja valitse sitten aiheeseen liittyvä linkki.</span><span class="sxs-lookup"><span data-stu-id="b536b-115">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Transfer Routes**, and then choose the related link.</span></span>
2. <span data-ttu-id="b536b-116">Voit myös valita **Siirtoreitit**-toiminnon mistä tahansa **Sijaintikortti**-ikkunasta.</span><span class="sxs-lookup"><span data-stu-id="b536b-116">Alternatively, from any **Location Card** window, choose the **Transfer Routes** action.</span></span>
3. <span data-ttu-id="b536b-117">Valitse **Uusi**-toiminto.</span><span class="sxs-lookup"><span data-stu-id="b536b-117">Choose the **New** action.</span></span>
4. <span data-ttu-id="b536b-118">Täytä **Sijaintikortti**-ikkunassa tarvittavat kentät.</span><span class="sxs-lookup"><span data-stu-id="b536b-118">In the **Location Card** window, fill in the fields as necessary.</span></span> [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]

<span data-ttu-id="b536b-119">Voit nyt siirtää varastonimikkeitä sijaintien välillä.</span><span class="sxs-lookup"><span data-stu-id="b536b-119">You can now transfer inventory items between two locations.</span></span> <span data-ttu-id="b536b-120">Lisätietoja on kohdassa [Toimintaohje: Varastonimikkeiden siirtäminen sijantien välillä](inventory-how-transfer-between-locations.md).</span><span class="sxs-lookup"><span data-stu-id="b536b-120">For more information, see [How to: Transfer Inventory Between Locations](inventory-how-transfer-between-locations.md).</span></span>    

## <a name="see-also"></a><span data-ttu-id="b536b-121">Katso myös</span><span class="sxs-lookup"><span data-stu-id="b536b-121">See Also</span></span>
[<span data-ttu-id="b536b-122">Varaston hallinta</span><span class="sxs-lookup"><span data-stu-id="b536b-122">Manage Inventory</span></span>](inventory-manage-inventory.md)  
<span data-ttu-id="b536b-123">[Toimintaohje: Varastonimikkeiden siirtäminen sijaintien välillä](inventory-how-transfer-between-locations.md)  </span><span class="sxs-lookup"><span data-stu-id="b536b-123">[How to: Transfer Inventory Between Locations](inventory-how-transfer-between-locations.md)  </span></span>  
<span data-ttu-id="b536b-124">[[!INCLUDE[d365fin](includes/d365fin_md.md)] -ohjelman käyttäminen](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="b536b-124">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>  
<span data-ttu-id="b536b-125">[[!INCLUDE[d365fin](includes/d365fin_md.md)] -sovelluksen mukauttaminen](ui-customizing-overview.md)</span><span class="sxs-lookup"><span data-stu-id="b536b-125">[Customizing [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-customizing-overview.md)</span></span>  
[<span data-ttu-id="b536b-126">Yleiset liiketoimintatoiminnot</span><span class="sxs-lookup"><span data-stu-id="b536b-126">General Business Functionality</span></span>](ui-across-business-areas.md)

