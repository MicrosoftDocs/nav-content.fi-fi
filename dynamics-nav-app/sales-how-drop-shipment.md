---
title: Ostotilaukseen linkitetyn myyntitilauksen luominen suoratoimitusta varten
description: "Tässä artikkelissa kerrotaan, miten ostotilaukseen linkitetty myyntitilaus luodaan. Näin toimitus voidaan tehdä suoraan toimittajalta asiakkaalle."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: direct shipment
ms.date: 03/29/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 1dfba8b14019991c95f40ffd5f7fbaed5df414eb
ms.openlocfilehash: 6be69a96ad6df401b3fedf5e0b81df870a1eedfc
ms.contentlocale: fi-fi
ms.lasthandoff: 12/01/2017

---
# <a name="how-to-make-drop-shipments"></a><span data-ttu-id="297c8-103">Toimintaohje: Suoratoimitusten tekeminen</span><span class="sxs-lookup"><span data-stu-id="297c8-103">How to: Make Drop Shipments</span></span>
<span data-ttu-id="297c8-104">Suoratoimitus on nimikkeen toimitus yhdeltä toimittajistasi suoraan yhdelle asiakkaistasi.</span><span class="sxs-lookup"><span data-stu-id="297c8-104">A drop shipment is the shipment of items from one of your vendors directly to one of your customers.</span></span>

<span data-ttu-id="297c8-105">Kun myyntitilaus merkitään suoratoimitusta varten, ja luot ostotilauksen, jossa asiakas määritetään **Tilausasiakkaan nro**</span><span class="sxs-lookup"><span data-stu-id="297c8-105">When a sales order is marked for drop shipment, and you create a purchase order specifying the customer in the **Sell-to Customer No.**</span></span> <span data-ttu-id="297c8-106">-kentässä, voit linkittää nämä kaksi asiakirjaa ja ohjeistaa toimittajaa toimittamaan nimikkeet suoraan asiakkaalle.</span><span class="sxs-lookup"><span data-stu-id="297c8-106">field, you can link the two documents and thereby instruct the vendor to ship directly to the customer.</span></span>

## <a name="to-create-a-sales-order-for-drop-shipment"></a><span data-ttu-id="297c8-107">Myyntitilauksen luominen suoratoimitusta varten</span><span class="sxs-lookup"><span data-stu-id="297c8-107">To create a sales order for drop shipment</span></span>
<span data-ttu-id="297c8-108">Voit valmistella suoratoimituksen luomalla nimikkeelle normaalisti myyntitilauksen. Myyntirivillä tulee kuitenkin määrittää, että myynti vaatii suoratoimituksen.</span><span class="sxs-lookup"><span data-stu-id="297c8-108">To prepare a drop shipment, you create a sales order for an item as normal, except you must indicate on the sales line that the sale requires drop shipment.</span></span>

1. <span data-ttu-id="297c8-109">Luo nimikkeelle myyntitilaus.</span><span class="sxs-lookup"><span data-stu-id="297c8-109">Create a sales order for an item.</span></span> <span data-ttu-id="297c8-110">Lisätietoja on kohdassa [Toimintaohje: Tuotteiden myyminen](sales-how-sell-products.md).</span><span class="sxs-lookup"><span data-stu-id="297c8-110">For more information, see [How to: Sell Products](sales-how-sell-products.md).</span></span>
2. <span data-ttu-id="297c8-111">Valitse suoratoimituksen myyntitilauksen rivillä **Suoratoimitus**-valintaruutu.</span><span class="sxs-lookup"><span data-stu-id="297c8-111">On the sales order line for the drop shipment, select the **Drop Shipment** check box.</span></span> <span data-ttu-id="297c8-112">Käytä **Valitse sarakkeita** -toiminto, jos kenttä ei ole näkyvissä.</span><span class="sxs-lookup"><span data-stu-id="297c8-112">Use the **Choose Columns** function if the field is not visible.</span></span> <span data-ttu-id="297c8-113">Lisätietoja on ohjeaiheessa [Käyttäjän mukautus](ui-user-personalization.md).</span><span class="sxs-lookup"><span data-stu-id="297c8-113">For more information, see [User Personalization](ui-user-personalization.md).</span></span>

## <a name="to-create-the-purchase-order-for-drop-shipment"></a><span data-ttu-id="297c8-114">Ostotilauksen luominen suoratoimitukselle</span><span class="sxs-lookup"><span data-stu-id="297c8-114">To create the purchase order for drop shipment</span></span>
<span data-ttu-id="297c8-115">Myytävän nimikkeen suoratoimitus valmistellaan luomalla ostotilaus normaalisti lukuun ottamatta sitä, että ostotilauksessa on määritettävä, että nimikkeet on toimitettava asiakkaalle, ei ostotilauksen tekijälle.</span><span class="sxs-lookup"><span data-stu-id="297c8-115">To prepare a drop shipment for the item to be sold, you create a purchase order as normal, except you must indicate on the purchase order that it must be shipped to your customer, not to yourself.</span></span>

1. <span data-ttu-id="297c8-116">Luo ostotilaus.</span><span class="sxs-lookup"><span data-stu-id="297c8-116">Create a purchase order.</span></span> <span data-ttu-id="297c8-117">Älä täytä riveillä olevia kenttiä.</span><span class="sxs-lookup"><span data-stu-id="297c8-117">Do not fill any fields on the lines.</span></span> <span data-ttu-id="297c8-118">Lisätietoja on kohdassa [Toimintaohje: Ostojen kirjaaminen](purchasing-how-record-purchases.md).</span><span class="sxs-lookup"><span data-stu-id="297c8-118">For more information, see [How to: Record Purchases](purchasing-how-record-purchases.md).</span></span>
2. <span data-ttu-id="297c8-119">Valitse **Tilausasiakkaan nro**</span><span class="sxs-lookup"><span data-stu-id="297c8-119">In the **Sell-to Customer No.**</span></span> <span data-ttu-id="297c8-120">-kenttään asiakas, jolle myydään.</span><span class="sxs-lookup"><span data-stu-id="297c8-120">field, select the customer that you are selling to.</span></span>
3. <span data-ttu-id="297c8-121">Valitse **Suoratoimitukset**-toiminto ja valitse sitten **Hae myyntitilaus** -toiminto.</span><span class="sxs-lookup"><span data-stu-id="297c8-121">Choose the **Drop Shipments** action, and then choose the **Get Sales Order** action.</span></span>
4. <span data-ttu-id="297c8-122">Valitse **Myyntiluettelo**-ikkunassa myyntitilaus, jota valmisteltiin "Myyntitilauksen luominen suoratoimitusta varten" -osassa.</span><span class="sxs-lookup"><span data-stu-id="297c8-122">In the **Sales List** window, select the sales order that you prepared in the "To create a sales order for drop shipment" section.</span></span>
5. <span data-ttu-id="297c8-123">Valitse **OK**-painike.</span><span class="sxs-lookup"><span data-stu-id="297c8-123">Choose the **OK** button.</span></span>

<span data-ttu-id="297c8-124">Myyntitilauksen rivin tiedot lisätään ostotilauksen riville/riveille.</span><span class="sxs-lookup"><span data-stu-id="297c8-124">The line information from the sales order is inserted on the purchase order line(s).</span></span>

<span data-ttu-id="297c8-125">Voit ohjeistaa toimittajaa toimittamaan nimikkeet asiakkaalle esimerkiksi lähettämällä ostotilauksen PDF-tiedostona.</span><span class="sxs-lookup"><span data-stu-id="297c8-125">You can now instruct the vendor to ship the items to your customer, for example, by mailing the purchase order as a PDF.</span></span>     

## <a name="to-view-the-linked-purchase-order-from-the-sales-order"></a><span data-ttu-id="297c8-126">Myyntitilauksesta linkitetyn ostotilauksen tarkasteleminen</span><span class="sxs-lookup"><span data-stu-id="297c8-126">To view the linked purchase order from the sales order</span></span>
* <span data-ttu-id="297c8-127">Valitse suoratoimituksen myyntitilauksen rivi ja valitse sitten **Tilaa**-toiminto. Valitse **Suoratoimitus**-toiminto ja valitse sitten **Ostotilaus**-toiminto.</span><span class="sxs-lookup"><span data-stu-id="297c8-127">Select the drop-shipment sales order line, choose the **Order** action, choose the **Drop Shipment** action, and then choose the **Purchase Order** action.</span></span>

## <a name="to-post-a-drop-shipment"></a><span data-ttu-id="297c8-128">Kirjaa suoratoimitus</span><span class="sxs-lookup"><span data-stu-id="297c8-128">To post a drop shipment</span></span>
<span data-ttu-id="297c8-129">Kun toimittaja toimittaa nimikkeet, voit kirjata myyntitilauksen toimitetuksi.</span><span class="sxs-lookup"><span data-stu-id="297c8-129">After the vendor ships the items, you can post the sales order as shipped.</span></span> <span data-ttu-id="297c8-130">Voit kirjata myös ostotilauksen, mutta vain **Vastaanotto**-vaihtoehdon kanssa niin kauan, kunnes myyntitilaus on laskutettu.</span><span class="sxs-lookup"><span data-stu-id="297c8-130">You can also post the purchase order, but only with the **Receive** option until the sales order has been invoiced.</span></span>

1. <span data-ttu-id="297c8-131">Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, kirjoita **Myyntitilaukset** ja valitse sitten aiheeseen liittyvä linkki.</span><span class="sxs-lookup"><span data-stu-id="297c8-131">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Sales orders**, and then choose the related link.</span></span>
2. <span data-ttu-id="297c8-132">Avaa "Myyntitilauksen luominen suoratoimitukselle" -osassa luomasi myyntitilaus.</span><span class="sxs-lookup"><span data-stu-id="297c8-132">Open the sales order that you created in the "To create a sales order for a drop shipment" section.</span></span>
3. <span data-ttu-id="297c8-133">Määritä **Toimitettava määrä** -kentässä toimitettava tilausmäärä, joka voi olla koko tai osittainen tilausmäärä.</span><span class="sxs-lookup"><span data-stu-id="297c8-133">In the **Qty. to Ship** field, specify how many of the order quantity to ship, the full or a partial order quantity.</span></span>
4. <span data-ttu-id="297c8-134">Valitse **Kirjaa**- tai **Kirjaa ja lähetä** -toiminto.</span><span class="sxs-lookup"><span data-stu-id="297c8-134">Choose the **Post** or **Post and Send** action.</span></span>
5. <span data-ttu-id="297c8-135">Valitse **Toimitus**-vaihtoehto, kun haluat laskuttaa myöhemmin, tai **Toimitus ja lasku** -vaihtoehto, kun haluat laskuttaa heti.</span><span class="sxs-lookup"><span data-stu-id="297c8-135">Choose either the **Ship** option to invoice later, or the **Ship and Invoice** option to invoice immediately.</span></span>

## <a name="see-also"></a><span data-ttu-id="297c8-136">Katso myös</span><span class="sxs-lookup"><span data-stu-id="297c8-136">See Also</span></span>
<span data-ttu-id="297c8-137">[Toimintaohje: Erikoistilausten luominen](sales-how-to-create-special-orders.md)|</span><span class="sxs-lookup"><span data-stu-id="297c8-137">[How to: Create Special Orders](sales-how-to-create-special-orders.md)|</span></span>  
[<span data-ttu-id="297c8-138">Toimintaohje: Tuotteiden myyminen</span><span class="sxs-lookup"><span data-stu-id="297c8-138">How to: Sell Products</span></span>](sales-how-sell-products.md)  
[<span data-ttu-id="297c8-139">Toimintaohje: Ostojen kirjaus</span><span class="sxs-lookup"><span data-stu-id="297c8-139">How to: Record Purchases</span></span>](purchasing-how-record-purchases.md)  
[<span data-ttu-id="297c8-140">Myynti</span><span class="sxs-lookup"><span data-stu-id="297c8-140">Sales</span></span>](sales-manage-sales.md)  
[<span data-ttu-id="297c8-141">Vaihto-omaisuus</span><span class="sxs-lookup"><span data-stu-id="297c8-141">Inventory</span></span>](inventory-manage-inventory.md)  
<span data-ttu-id="297c8-142">[[!INCLUDE[d365fin](includes/d365fin_md.md)] -ohjelman käyttäminen](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="297c8-142">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>

