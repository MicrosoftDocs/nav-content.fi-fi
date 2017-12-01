---
title: "Myytävien nimikkeiden ostaminen luomalla ostolasku myyntitilauksesta"
description: Voit ostaa tuotteita luomalla toimittajan ostolaskun myyntilaskusta.
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: supply planning, sales demand, replenish
ms.date: 05/16/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 1dfba8b14019991c95f40ffd5f7fbaed5df414eb
ms.openlocfilehash: 0ba1fa771a0853c2a2cabe4d368cc09902496b01
ms.contentlocale: fi-fi
ms.lasthandoff: 12/01/2017

---
# <a name="how-to-purchase-items-for-a-sale"></a><span data-ttu-id="7d96e-103">Toimintaohje: Nimikkeiden ostaminen myyntiin</span><span class="sxs-lookup"><span data-stu-id="7d96e-103">How to: Purchase Items for a Sale</span></span>
<span data-ttu-id="7d96e-104">Voit luoda myyntitilausten ja myyntilaskujen toiminnoilla nopeasti ostoasiakirjoja myynnin edellyttämille puuttuville nimikemäärille.</span><span class="sxs-lookup"><span data-stu-id="7d96e-104">From sales orders and sales invoices, you can use functions to quickly create purchase documents for missing item quantities that are required by the sale.</span></span> <span data-ttu-id="7d96e-105">Voit käyttää asiakirjan tyypin mukaan kahta eri toimintoa.</span><span class="sxs-lookup"><span data-stu-id="7d96e-105">You can use two different functions depending on the document type.</span></span>
|<span data-ttu-id="7d96e-106">Toiminto</span><span class="sxs-lookup"><span data-stu-id="7d96e-106">Function</span></span>|<span data-ttu-id="7d96e-107">Description</span><span class="sxs-lookup"><span data-stu-id="7d96e-107">Description</span></span>|
|--------|-----------|
|<span data-ttu-id="7d96e-108">**Luo ostotilaukset**</span><span class="sxs-lookup"><span data-stu-id="7d96e-108">**Create Purchase Orders**</span></span>|<span data-ttu-id="7d96e-109">Tällä toiminnolla voi luoda myyntitilauksesta ostotilauksen kullekin myyntitilauksessa olevan nimikkeen toimittajalle.</span><span class="sxs-lookup"><span data-stu-id="7d96e-109">From a sales order, this function creates a purchase order for each vendor of items on the sales order.</span></span> <span data-ttu-id="7d96e-110">Voit muokata ostomäärää ennen ostotilausten luontia.</span><span class="sxs-lookup"><span data-stu-id="7d96e-110">You can edit the purchase quantity before you create the purchase orders.</span></span> <span data-ttu-id="7d96e-111">Vain myyntimääriä, jotka eivät ole käytettävissä, ehdotetaan.</span><span class="sxs-lookup"><span data-stu-id="7d96e-111">Only unavailable sales quantities are suggested.</span></span>
|<span data-ttu-id="7d96e-112">**Luo ostolasku**</span><span class="sxs-lookup"><span data-stu-id="7d96e-112">**Create Purchase Invoice**</span></span>|<span data-ttu-id="7d96e-113">Tällä toiminnolla voi luoda myyntitilauksesta ja myyntilaskusta ostolaskun myyntiasiakirjasta valitun toimittajan kaikille tai valituille riveille.</span><span class="sxs-lookup"><span data-stu-id="7d96e-113">From a sales order and from a sales invoice, this function creates a purchase invoice for a selected vendor for all lines or selected lines on the sales document.</span></span> <span data-ttu-id="7d96e-114">Ehdotuksena on myynnin täysi määrä.</span><span class="sxs-lookup"><span data-stu-id="7d96e-114">The full sales quantity is suggested.</span></span>|

## <a name="to-create-one-or-more-purchase-orders-from-a-sales-order"></a><span data-ttu-id="7d96e-115">Vähintään yhden ostotilauksen luominen myyntitilauksesta</span><span class="sxs-lookup"><span data-stu-id="7d96e-115">To create one or more purchase orders from a sales order</span></span>
<span data-ttu-id="7d96e-116">Voit luoda ostotilauksen kullekin myyntitilauksen nimikkeen määrälle, joka ei ole käytettävissä **Luo ostotilauksia** -toiminnolla.</span><span class="sxs-lookup"><span data-stu-id="7d96e-116">To create a purchase order for each unavailable item quantity on the sales order, you use the **Create Purchase Orders** function.</span></span>

1. <span data-ttu-id="7d96e-117">Valitse kotisivulla **Jatkuvat myyntitilaukset** -ruutu.</span><span class="sxs-lookup"><span data-stu-id="7d96e-117">On the Home page, choose the **Ongoing Sales Orders** tile.</span></span>
2. <span data-ttu-id="7d96e-118">Avaa myyntitilaus, johon haluat ostaa nimikkeitä.</span><span class="sxs-lookup"><span data-stu-id="7d96e-118">Open a sales order that you want to purchase items for.</span></span>
3. <span data-ttu-id="7d96e-119">Valitse **Luo ostotilaukset** -toiminto.</span><span class="sxs-lookup"><span data-stu-id="7d96e-119">Choose the **Create Purchase Orders** action.</span></span>

    <span data-ttu-id="7d96e-120">Avautuvassa **Luo ostotilauksia** -ikkunassa näkyy rivi kullekin myyntitilauksen nimikkeelle.</span><span class="sxs-lookup"><span data-stu-id="7d96e-120">The **Create Purchase Orders** window opens showing a line for each different item on the sales order.</span></span> <span data-ttu-id="7d96e-121">Oletusarvoisesti näkyvissä on kokonaan saatavana olevien myyntimäärien rivit sekä niiden myyntimäärien rivit, jotka eivät ole saatavana (näkyvät harmaana).</span><span class="sxs-lookup"><span data-stu-id="7d96e-121">Lines for both fully available sales quantities and unavailable sales quantities (grayed) are shown by default.</span></span> <span data-ttu-id="7d96e-122">Voit valita **Näytä ne, jotka eivät ole saatavilla** -toiminnon, jos haluat nähdä vain niiden myyntimäärien rivit, jotka eivät ole saatavilla.</span><span class="sxs-lookup"><span data-stu-id="7d96e-122">You can choose the **Show Unavailable** action to only see lines for unavailable sales quantities.</span></span>

    <span data-ttu-id="7d96e-123">**Ostojen määrä** -kenttä sisältää oletusarvoisesti myyntimäärän, joka ei ole saatavilla.</span><span class="sxs-lookup"><span data-stu-id="7d96e-123">The **Quantity to Purchase** field contains the unavailable sales quantity by default.</span></span>
4. <span data-ttu-id="7d96e-124">Voit ostaa jonkin muun määrän kuin ei saatavilla olevan myyntimäärän muokkaamalla **Ostettava määrä** -kentän arvon.</span><span class="sxs-lookup"><span data-stu-id="7d96e-124">To purchase another quantity than the unavailable sales quantity, edit the value in the **Quantity to Purchase** field.</span></span>

    > [!NOTE]  
>   <span data-ttu-id="7d96e-125">Voit muuttaa myös harmaana näkyvien rivien **Ostettava määrä** -kenttää, vaikka ne ilmaisevatkin kokonaan saatavilla olevat myyntimäärät.</span><span class="sxs-lookup"><span data-stu-id="7d96e-125">You can also change the **Quantity to Purchase** field on grayed lines even though they represent fully available sales quantities.</span></span>
5. <span data-ttu-id="7d96e-126">Valitse **OK**-painike.</span><span class="sxs-lookup"><span data-stu-id="7d96e-126">Choose the **OK** button.</span></span>

    <span data-ttu-id="7d96e-127">Kullekin myyntitilauksen nimikkeiden toimittajalle luodaan ostotilaus, mukaan lukien **Luo ostotilaukset** -ikkunassa mahdollisesti tehdyt määrän muutokset.</span><span class="sxs-lookup"><span data-stu-id="7d96e-127">A purchase order is created for each vendor of items on the sales order, including any quantity changes that you made in the **Create Purchase Orders** window.</span></span>
7. <span data-ttu-id="7d96e-128">Siirry käsittelemään ostotilauksia esimerkiksi muokkaamalla tai lisäämällä ostotilausrivejä.</span><span class="sxs-lookup"><span data-stu-id="7d96e-128">Proceed to process the purchase order or orders, for example, by editing or adding purchase order lines.</span></span> <span data-ttu-id="7d96e-129">Lisätietoja on ohjeaiheessa [Toimintaohje: Ostojen kirjaaminen](purchasing-how-record-purchases.md).</span><span class="sxs-lookup"><span data-stu-id="7d96e-129">For more information, see [How to: Record Purchases](purchasing-how-record-purchases.md).</span></span>


## <a name="to-create-a-purchase-invoice-from-a-sales-order-or-sales-invoice"></a><span data-ttu-id="7d96e-130">Ostolaskun luominen myyntitilauksesta tai myyntilaskusta</span><span class="sxs-lookup"><span data-stu-id="7d96e-130">To create a purchase invoice from a sales order or sales invoice</span></span>
<span data-ttu-id="7d96e-131">Voit luoda yhden ostolaskun yhdelle tai usealle myyntiasiakirjan riville valitsemalla ensin toimittajan, jolta nimike ostetaan, käyttämällä **Luo ostotilaus** -toimintoa.</span><span class="sxs-lookup"><span data-stu-id="7d96e-131">To create a single purchase invoice for one or more lines on a sales document by first selecting which vendor to buy from, you use the **Create Purchase Invoice** function.</span></span>

> [!NOTE]  
>   <span data-ttu-id="7d96e-132">Tällä toiminnolla luodaan ostolasku täsmälleen valitussa myyntiasiakirjassa olevalle nimikemäärälle.</span><span class="sxs-lookup"><span data-stu-id="7d96e-132">This function creates a purchase invoice for the exact item quantity on the selected sales document.</span></span> <span data-ttu-id="7d96e-133">Voit muuttaa oston määrää muokkaamalla ostolasku sen jälkeen, kun se on luotu.</span><span class="sxs-lookup"><span data-stu-id="7d96e-133">To change the purchase quantity, you must edit the purchase invoice after it is created.</span></span>  

1. <span data-ttu-id="7d96e-134">Valitse kotisivulla **Jatkuvat myyntilaskut** -ruutu.</span><span class="sxs-lookup"><span data-stu-id="7d96e-134">On the Home page, choose the **Ongoing Sales Invoices** tile.</span></span>
2. <span data-ttu-id="7d96e-135">Avaa myyntilasku, johon haluat ostaa nimikkeitä.</span><span class="sxs-lookup"><span data-stu-id="7d96e-135">Open a sales invoice that you want to purchase items for.</span></span>
3. <span data-ttu-id="7d96e-136">Valitse yksi tai useampi myyntilaskun rivi, joita haluat käyttää ostolaskuun.</span><span class="sxs-lookup"><span data-stu-id="7d96e-136">Select one or more sales invoice lines that you want to use on the purchase invoice.</span></span> <span data-ttu-id="7d96e-137">Voit käyttää kaikkia myyntilaskurivejä valitsemalla kaikki rivit tai jättämällä kaikki rivit valitsematta.</span><span class="sxs-lookup"><span data-stu-id="7d96e-137">To use all the sales invoice lines, select either all of them or do not select any lines.</span></span>
4. <span data-ttu-id="7d96e-138">Valitse **Luo ostolasku** -toiminto.</span><span class="sxs-lookup"><span data-stu-id="7d96e-138">Choose the **Create Purchase Invoice** action.</span></span>
5. <span data-ttu-id="7d96e-139">Valitse joko **Kaikki rivit** tai **Valitut rivit** ja valitse sitten **OK**-painike.</span><span class="sxs-lookup"><span data-stu-id="7d96e-139">Select either **All Lines** or **Selected Lines**, and then choose the **OK** button.</span></span>  
6. <span data-ttu-id="7d96e-140">Valitse avautuvasta toimittajaluettelosta toimittaja, jolta haluat ostaa kaikki nimikkeet, ja valitse sitten **OK**-painike.</span><span class="sxs-lookup"><span data-stu-id="7d96e-140">In the list of vendors that appears, select the vendor that you want to buy all the items from, and then choose the **OK** button.</span></span>

    <span data-ttu-id="7d96e-141">Luotavassa ostolaskussa on yksi myyntilaskun rivi, useita myyntilaskun rivejä tai kaikki myyntilaskun rivit.</span><span class="sxs-lookup"><span data-stu-id="7d96e-141">A purchase invoice is created that contains one, more, or all the lines on the sales invoice.</span></span>
7. <span data-ttu-id="7d96e-142">Siirry käsittelemään ostolasku, esimerkiksi lisäämällä ostolaskurivit tai muokkaamalla niitä.</span><span class="sxs-lookup"><span data-stu-id="7d96e-142">Proceed to process the purchase invoice, for example, by editing or adding purchase invoice lines.</span></span> <span data-ttu-id="7d96e-143">Lisätietoja on kohdassa [Toimintaohje: Ostojen kirjaaminen](purchasing-how-record-purchases.md).</span><span class="sxs-lookup"><span data-stu-id="7d96e-143">For more information, see [How to: Record Purchases](purchasing-how-record-purchases.md).</span></span>

## <a name="see-also"></a><span data-ttu-id="7d96e-144">Katso myös</span><span class="sxs-lookup"><span data-stu-id="7d96e-144">See Also</span></span>
[<span data-ttu-id="7d96e-145">Osto</span><span class="sxs-lookup"><span data-stu-id="7d96e-145">Purchasing</span></span>](purchasing-manage-purchasing.md)  
[<span data-ttu-id="7d96e-146">Toimintaohje: Ostojen kirjaus</span><span class="sxs-lookup"><span data-stu-id="7d96e-146">How to: Record Purchases</span></span>](purchasing-how-record-purchases.md)  
[<span data-ttu-id="7d96e-147">Toimintaohje: Myynnin laskutus</span><span class="sxs-lookup"><span data-stu-id="7d96e-147">How to: Invoice Sales</span></span>](sales-how-invoice-sales.md)  
[<span data-ttu-id="7d96e-148">Toimintaohje: Uusien toimittajien rekisteröiminen</span><span class="sxs-lookup"><span data-stu-id="7d96e-148">How to: Register New Vendors</span></span>](purchasing-how-register-new-vendors.md)  
<span data-ttu-id="7d96e-149">[[!INCLUDE[d365fin](includes/d365fin_md.md)] -ohjelman käyttäminen](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="7d96e-149">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>

