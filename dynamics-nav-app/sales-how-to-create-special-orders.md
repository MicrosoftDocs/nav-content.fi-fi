---
title: Erikoistilausten luominen
description: "Erikoistilauksen voi luoda tietylle ei-varastoitavalle nimikkeelle, joka toimitetaan tietylle asiakkaalle. Toimittajasi toimittaa nimikkeen fyysiseen varastoosi, ja sen jälkeen voit toimittaa nimikkeen asiakkaallesi joko erikseen tai yhdessä muiden, toisen tilauksen nimikkeiden kanssa."
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 09/08/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 6460c643a07f92e478aafb84044c90ff3ed3a236
ms.contentlocale: fi-fi
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-create-special-orders"></a><span data-ttu-id="8cbfa-104">Erikoistilausten luominen</span><span class="sxs-lookup"><span data-stu-id="8cbfa-104">How to: Create Special Orders</span></span>
<span data-ttu-id="8cbfa-105">Voit luoda erikoistilauksen tietylle ei-varastoitavalle nimikkeelle, joka toimitetaan tietylle asiakkaalle.</span><span class="sxs-lookup"><span data-stu-id="8cbfa-105">You can create a special order for a specific nonstock item to be shipped to a specific customer.</span></span> <span data-ttu-id="8cbfa-106">Toimittajasi toimittaa nimikkeen fyysiseen varastoosi, ja sen jälkeen voit toimittaa nimikkeen asiakkaallesi joko erikseen tai yhdessä muiden, toisen tilauksen nimikkeiden kanssa.</span><span class="sxs-lookup"><span data-stu-id="8cbfa-106">Your vendor ships the item to your warehouse and you can then ship the item on to your customer either independently or together with other items on another order.</span></span>  

<span data-ttu-id="8cbfa-107">Erikoistilaukset ilmaisevat, että osto- ja myyntitilaus on linkitetty toisiinsa. Näin varmistetaan, että tietty ei-varastoistava nimike poimitaan ja toimitetaan kyseiselle asiakkaalle.</span><span class="sxs-lookup"><span data-stu-id="8cbfa-107">Special orders imply that the purchase and sales order are linked to ensure that the specific nonstock item is picked and delivered to the customer.</span></span>  

<span data-ttu-id="8cbfa-108">Ennen kuin tätä ominaisuutta voi käyttää, tilaukselle tarpeelliset asiakas-, myyjä- ja nimikekortit tulee määrittää.</span><span class="sxs-lookup"><span data-stu-id="8cbfa-108">Before you can use this feature, you must first set up the customer, vendor, and item cards necessary for the order.</span></span>  

## <a name="to-create-a-special-order"></a><span data-ttu-id="8cbfa-109">Erikoistilausten luominen</span><span class="sxs-lookup"><span data-stu-id="8cbfa-109">To create a special order</span></span>  
1.  <span data-ttu-id="8cbfa-110">Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, kirjoita **Myyntitilaus** ja valitse sitten aiheeseen liittyvä linkki.</span><span class="sxs-lookup"><span data-stu-id="8cbfa-110">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Sales Order**, and then choose the related link.</span></span>  
2. <span data-ttu-id="8cbfa-111">Valitse **Uusi**-toiminto.</span><span class="sxs-lookup"><span data-stu-id="8cbfa-111">Choose the **New** action.</span></span> <span data-ttu-id="8cbfa-112">Luo nimikkeelle  myyntitilaus ja täytä se.</span><span class="sxs-lookup"><span data-stu-id="8cbfa-112">Create and fill in a  sales order for the item.</span></span> <span data-ttu-id="8cbfa-113">Lisätietoja on kohdassa [Toimintaohje: Tuotteiden myyminen](sales-how-sell-products.md).</span><span class="sxs-lookup"><span data-stu-id="8cbfa-113">For more information, see [How to: Sell Products](sales-how-sell-products.md).</span></span>
3.  <span data-ttu-id="8cbfa-114">Täytä myyntirivi **Rivit**-pikavälilehdessä.</span><span class="sxs-lookup"><span data-stu-id="8cbfa-114">On the **Lines** FastTab, fill in the sales line.</span></span> <span data-ttu-id="8cbfa-115">Valitse **Ostamisen koodi** -kentässä ostokoodi, jonka **Erikoistilaus**-kenttä on valittuna.</span><span class="sxs-lookup"><span data-stu-id="8cbfa-115">In the **Purchasing Code** field, select a purchasing code that has the **Special Order** field selected.</span></span>

    <span data-ttu-id="8cbfa-116">Luo seuraavaksi ostotilaus hankintalistasta.</span><span class="sxs-lookup"><span data-stu-id="8cbfa-116">You must now create a purchase order from a requisition worksheet.</span></span>  
4. <span data-ttu-id="8cbfa-117">Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, kirjoita **Hankintalista** ja valitse sitten aiheeseen liittyvä linkki.</span><span class="sxs-lookup"><span data-stu-id="8cbfa-117">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Requisition Worksheet**, and then choose the related link.</span></span>  
5. <span data-ttu-id="8cbfa-118">Valitse ensin **Erikoistilaus**-toiminto ja sitten **Hae myyntitilaukset** -toiminto.</span><span class="sxs-lookup"><span data-stu-id="8cbfa-118">Choose the **Special Order** action, and then choose the **Get Sales Orders** action.</span></span>  
6.  <span data-ttu-id="8cbfa-119">Näytä **Hae myyntitilaukset** -ikkunassa tulokset, joissa **Asiakirjan nro.** on myyntitilauksen numero.</span><span class="sxs-lookup"><span data-stu-id="8cbfa-119">In the **Get Sales Orders** window, show results where the **Document No.** is the sales order number.</span></span> <span data-ttu-id="8cbfa-120">Valitse **OK**-painike.</span><span class="sxs-lookup"><span data-stu-id="8cbfa-120">Choose the **OK** button.</span></span> <span data-ttu-id="8cbfa-121">Ohjelma luo nimikkeelle hankintalistan rivin.</span><span class="sxs-lookup"><span data-stu-id="8cbfa-121">A requisition worksheet line is created for the item.</span></span>  
7.  <span data-ttu-id="8cbfa-122">Valitse hankintalistarivin  **Toimenpideviesti**-kentässä **Uusi**.</span><span class="sxs-lookup"><span data-stu-id="8cbfa-122">On the requisition worksheet line, in the **Action Message** field, select **New**.</span></span>  
8.  <span data-ttu-id="8cbfa-123">Valitse **Hankintalista**-ikkunassa **Toteuta toimenpideviesti** -toiminto.</span><span class="sxs-lookup"><span data-stu-id="8cbfa-123">In the **Req. Worksheet** window, choose the **Carry Out Action Message** action.</span></span> <span data-ttu-id="8cbfa-124">**Toteuta toim.pideviesti - hank** -ikkuna avautuu.</span><span class="sxs-lookup"><span data-stu-id="8cbfa-124">The **Carry Out Action Msg. - Req.** window opens.</span></span> <span data-ttu-id="8cbfa-125">Valitse **OK**-painike.</span><span class="sxs-lookup"><span data-stu-id="8cbfa-125">Choose the **OK** button.</span></span>  

    <span data-ttu-id="8cbfa-126">Näyttöön tulee ikkuna, jossa ilmoitetaan, että ostotilaukset on luotu.</span><span class="sxs-lookup"><span data-stu-id="8cbfa-126">A message appears telling you that the purchase orders have been created.</span></span> <span data-ttu-id="8cbfa-127">Valitse **OK**-painike.</span><span class="sxs-lookup"><span data-stu-id="8cbfa-127">Choost the **OK** button.</span></span>  

<span data-ttu-id="8cbfa-128">Suunnittelujärjestelmä säilyttää myyntitilaukselle erikoistilauksena luodun ostotilauksen, koska se tasapainottaa kysyntää ja tarjontaa.</span><span class="sxs-lookup"><span data-stu-id="8cbfa-128">A purchase order created as a special order for a sales order is respected by the planning system as it balances demand and supply.</span></span> <span data-ttu-id="8cbfa-129">Ostotilaus (tarjonta) pysyy linkitettynä myyntitilaukseen (kysyntään), vaikka ostotilauksella voisi toimittaa toisen aiemman kysynnän.</span><span class="sxs-lookup"><span data-stu-id="8cbfa-129">That is, the purchase order (supply) remains linked to the sales order (demand), even if that purchase order could supply another earlier demand.</span></span> <span data-ttu-id="8cbfa-130">Lisätietoja on kohdassa [Rakennetiedot: Uusintatilauskäytännöt](design-details-reservation-order-tracking-and-action-messaging.md).</span><span class="sxs-lookup"><span data-stu-id="8cbfa-130">For more information, see [Design Details: Reordering Policies](design-details-reservation-order-tracking-and-action-messaging.md).</span></span>  

> [!NOTE]  
>  <span data-ttu-id="8cbfa-131">Et voi käyttää erikoistilauksen toimintoja, jos nimike on jo varattu.</span><span class="sxs-lookup"><span data-stu-id="8cbfa-131">You cannot use the special order functionality if the item is already reserved.</span></span> <span data-ttu-id="8cbfa-132">Tämän varmista erikoistilauksina myydyille nimikkeille, että **Varaa**-kenttää nimikkeen kortissa ei ole määritetty arvoon **Aina**.</span><span class="sxs-lookup"><span data-stu-id="8cbfa-132">Therefore, for items that are sold on special orders, make sure the **Reserve** field on the item card is not set to **Always**.</span></span>  

## <a name="see-also"></a><span data-ttu-id="8cbfa-133">Katso myös</span><span class="sxs-lookup"><span data-stu-id="8cbfa-133">See Also</span></span>  
[<span data-ttu-id="8cbfa-134">Toimintaohje: Ei-varastoitavien nimikkeiden käsitteleminen</span><span class="sxs-lookup"><span data-stu-id="8cbfa-134">How to: Work with Nonstock Items</span></span>](inventory-how-work-nonstock-items.md)  
[<span data-ttu-id="8cbfa-135">Myynti</span><span class="sxs-lookup"><span data-stu-id="8cbfa-135">Sales</span></span>](sales-manage-sales.md)  
<span data-ttu-id="8cbfa-136">[Toimintaohje: Suoratoimitusten tekeminen](sales-how-drop-shipment.md) </span><span class="sxs-lookup"><span data-stu-id="8cbfa-136">[How to: Make Drop Shipments](sales-how-drop-shipment.md) </span></span>  
[<span data-ttu-id="8cbfa-137">Rakennetiedot: uusintatilauskäytännöt</span><span class="sxs-lookup"><span data-stu-id="8cbfa-137">Design Details: Reordering Policies</span></span>](design-details-reservation-order-tracking-and-action-messaging.md)  
<span data-ttu-id="8cbfa-138">[[!INCLUDE[d365fin](includes/d365fin_md.md)] -ohjelman käyttäminen](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="8cbfa-138">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>

