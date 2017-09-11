---
title: 'Toimintaohje: Suoratoimitusten tekeminen'
author: SorenGP
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 6b60b1344a1e18ad91863046110df880f75f7c04
ms.openlocfilehash: a726c8c24d8f843b33b4df4d85ad2b5eab3790e7
ms.contentlocale: fi-fi
ms.lasthandoff: 07/19/2017

---

# <a name="how-to-make-drop-shipments"></a><span data-ttu-id="a3892-102">Toimintaohje: Suoratoimitusten tekeminen</span><span class="sxs-lookup"><span data-stu-id="a3892-102">How to: Make Drop Shipments</span></span>
<span data-ttu-id="a3892-103">Suoratoimitus on nimikkeen toimitus yhdeltä toimittajistasi suoraan yhdelle asiakkaistasi.</span><span class="sxs-lookup"><span data-stu-id="a3892-103">A drop shipment is the shipment of items from one of your vendors directly to one of your customers.</span></span>

<span data-ttu-id="a3892-104">Kun myyntitilaus merkitään suoratoimitusta varten, ja luot ostotilauksen, jossa asiakas määritetään **Tilausasiakkaan nro**</span><span class="sxs-lookup"><span data-stu-id="a3892-104">When a sales order is marked for drop shipment, and you create a purchase order specifying the customer in the **Sell-to Customer No.**</span></span> <span data-ttu-id="a3892-105">-kentässä, voit linkittää nämä kaksi asiakirjaa ja ohjeistaa toimittajaa toimittamaan nimikkeet suoraan asiakkaalle.</span><span class="sxs-lookup"><span data-stu-id="a3892-105">field, then you can link the two documents and thereby instruct the vendor to ship directly to the customer.</span></span>

## <a name="to-create-a-sales-order-for-drop-shipment"></a><span data-ttu-id="a3892-106">Myyntitilauksen luominen suoratoimitusta varten</span><span class="sxs-lookup"><span data-stu-id="a3892-106">To create a sales order for drop shipment</span></span>
<span data-ttu-id="a3892-107">Voit valmistella suoratoimituksen luomalla nimikkeelle normaalisti myyntitilauksen. Myyntirivillä tulee kuitenkin määrittää, että myynti vaatii suoratoimituksen.</span><span class="sxs-lookup"><span data-stu-id="a3892-107">To prepare a drop shipment, you create a sales order for an item as normal, except you must indicate on the sales line that the sale requires drop shipment.</span></span>

1. <span data-ttu-id="a3892-108">Luo nimikkeelle myyntitilaus.</span><span class="sxs-lookup"><span data-stu-id="a3892-108">Create a sales order for an item.</span></span> <span data-ttu-id="a3892-109">Lisätietoja on kohdassa [Toimintaohje: Tuotteiden myyminen](sales-how-sell-products.md).</span><span class="sxs-lookup"><span data-stu-id="a3892-109">For more information, see [How to: Sell Products](sales-how-sell-products.md).</span></span>
2. <span data-ttu-id="a3892-110">Valitse suoratoimituksen nimikkeen myyntitilauksen rivillä **Suoratoimitus**-valintaruutu.</span><span class="sxs-lookup"><span data-stu-id="a3892-110">On the sales order line for the drop-shipment item, select the **Drop Shipment** check box.</span></span>

## <a name="to-create-the-purchase-order-for-drop-shipment"></a><span data-ttu-id="a3892-111">Ostotilauksen luominen suoratoimitukselle</span><span class="sxs-lookup"><span data-stu-id="a3892-111">To create the purchase order for drop shipment</span></span>
<span data-ttu-id="a3892-112">Myytävän nimikkeen suoratoimitus valmistellaan luomalla ostotilaus normaalisti lukuun ottamatta sitä, että ostotilauksessa on määritettävä, että nimikkeet on toimitettava asiakkaalle, ei ostotilauksen tekijälle.</span><span class="sxs-lookup"><span data-stu-id="a3892-112">To prepare a drop shipment for the item to be sold, you create a purchase order as normal, except you must indicate on the purchase order that it must be shipped to your customer, not to yourself.</span></span>

1. <span data-ttu-id="a3892-113">Luo ostotilaus.</span><span class="sxs-lookup"><span data-stu-id="a3892-113">Create a purchase order.</span></span> <span data-ttu-id="a3892-114">Älä täytä riveillä olevia kenttiä.</span><span class="sxs-lookup"><span data-stu-id="a3892-114">Do not fill any fields on the lines.</span></span> <span data-ttu-id="a3892-115">Lisätietoja on kohdassa [Toimintaohje: Ostojen kirjaaminen](purchasing-how-record-purchases.md).</span><span class="sxs-lookup"><span data-stu-id="a3892-115">For more information, see [How to: Record Purchases](purchasing-how-record-purchases.md).</span></span>
2. <span data-ttu-id="a3892-116">Valitse **Tilausasiakkaan nro**</span><span class="sxs-lookup"><span data-stu-id="a3892-116">In the **Sell-to Customer No.**</span></span> <span data-ttu-id="a3892-117">-kenttään asiakas, jolle myydään.</span><span class="sxs-lookup"><span data-stu-id="a3892-117">field, select the customer that you are selling to.</span></span>
3. <span data-ttu-id="a3892-118">Valitse **Suoratoimitukset**-toiminto ja valitse sitten **Hae myyntitilaus** -toiminto.</span><span class="sxs-lookup"><span data-stu-id="a3892-118">Choose the **Drop Shipments** action, and then choose the **Get Sales Order** action.</span></span>
4. <span data-ttu-id="a3892-119">Valitse **Myyntiluettelo**-ikkunassa myyntitilaus, jota valmisteltiin "Myyntitilauksen luominen suoratoimitusta varten" -osassa.</span><span class="sxs-lookup"><span data-stu-id="a3892-119">In the **Sales List** window, select the sales order that you prepared in the "To create a sales order for drop shipment" section.</span></span>
5. <span data-ttu-id="a3892-120">Valitse **OK**-painike.</span><span class="sxs-lookup"><span data-stu-id="a3892-120">Choose the **OK** button.</span></span>

<span data-ttu-id="a3892-121">Myyntitilauksen rivin tiedot lisätään ostotilauksen riville/riveille.</span><span class="sxs-lookup"><span data-stu-id="a3892-121">The line information from the sales order is inserted on the purchase order line(s).</span></span>

<span data-ttu-id="a3892-122">Voit ohjeistaa toimittajaa toimittamaan nimikkeet asiakkaalle esimerkiksi lähettämällä ostotilauksen PDF-tiedostona.</span><span class="sxs-lookup"><span data-stu-id="a3892-122">You can now instruct the vendor to ship the items to your customer, for example, by mailing the purchase order as a PDF.</span></span>     

## <a name="to-view-the-linked-purchase-order-from-the-sales-order"></a><span data-ttu-id="a3892-123">Myyntitilauksesta linkitetyn ostotilauksen tarkasteleminen</span><span class="sxs-lookup"><span data-stu-id="a3892-123">To view the linked purchase order from the sales order</span></span>
1. <span data-ttu-id="a3892-124">Valitse suoratoimituksen myyntitilauksen rivi ja valitse sitten **Tilaa**-toiminto. Valitse **Suoratoimitus**-toiminto ja valitse sitten **Ostotilaus**-toiminto.</span><span class="sxs-lookup"><span data-stu-id="a3892-124">Select the drop-shipment sales order line, choose the **Order** action, choose the **Drop Shipment** action, and then choose the **Purchase Order** action.</span></span>

<span data-ttu-id="a3892-125">Linkitetty ostotilaus avautuu.</span><span class="sxs-lookup"><span data-stu-id="a3892-125">The linked purchase order opens.</span></span>

## <a name="to-post-a-drop-shipment"></a><span data-ttu-id="a3892-126">Kirjaa suoratoimitus</span><span class="sxs-lookup"><span data-stu-id="a3892-126">To post a drop shipment</span></span>
<span data-ttu-id="a3892-127">Kun toimittaja on toimittanut nimikkeet, voit kirjata myyntitilauksen toimitetuksi.</span><span class="sxs-lookup"><span data-stu-id="a3892-127">When the vendor has shipped the items, you can post the sales order as shipped.</span></span> <span data-ttu-id="a3892-128">Voit kirjata myös ostotilauksen, mutta vain **Vastaanotto**-vaihtoehdon kanssa niin kauan, kunnes myyntitilaus on laskutettu.</span><span class="sxs-lookup"><span data-stu-id="a3892-128">You can also post the purchase order, but only with the **Receive** option until the sales order has been invoiced.</span></span>
1. <span data-ttu-id="a3892-129">Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Myyntitilaukset** ja valitse sitten aiheeseen liittyvä linkki.</span><span class="sxs-lookup"><span data-stu-id="a3892-129">In the top right corner, choose the **Search for Page or Report** icon, enter **Sales orders**, and then choose the related link.</span></span>
2. <span data-ttu-id="a3892-130">Avaa "Myyntitilauksen luominen suoratoimitukselle" -osassa luomasi myyntitilaus.</span><span class="sxs-lookup"><span data-stu-id="a3892-130">Open the sales order that you created in the "To create a sales order for a drop shipment" section.</span></span>
3. <span data-ttu-id="a3892-131">Määritä **Toimitettava määrä** -kentässä toimitettava tilausmäärä, joka voi olla koko tai osittainen tilausmäärä.</span><span class="sxs-lookup"><span data-stu-id="a3892-131">In the **Qty. to Ship** field, specify how many of the order quantity to ship, the full or a partial order quantity.</span></span>
3. <span data-ttu-id="a3892-132">Valitse **Kirjaa**- tai **Kirjaa ja lähetä** -toiminto.</span><span class="sxs-lookup"><span data-stu-id="a3892-132">Choose the **Post** or **Post and Send** action.</span></span>
4. <span data-ttu-id="a3892-133">Valitse **Toimitus**-vaihtoehto, kun haluat laskuttaa myöhemmin, tai **Toimitus ja lasku** -vaihtoehto, kun haluat laskuttaa heti.</span><span class="sxs-lookup"><span data-stu-id="a3892-133">Choose either the **Ship** option to invoice later, or the **Ship and Invoice** option to invoice immediately.</span></span>

## <a name="see-also"></a><span data-ttu-id="a3892-134">Katso myös</span><span class="sxs-lookup"><span data-stu-id="a3892-134">See Also</span></span>
<span data-ttu-id="a3892-135">[Toimintaohje: Tuotteiden myyminen](sales-how-sell-products.md)  </span><span class="sxs-lookup"><span data-stu-id="a3892-135">[How to: Sell Products](sales-how-sell-products.md)  </span></span>  
[<span data-ttu-id="a3892-136">Toimintaohje: Ostojen kirjaus</span><span class="sxs-lookup"><span data-stu-id="a3892-136">How to: Record Purchases</span></span>](purchasing-how-record-purchases.md)  
[<span data-ttu-id="a3892-137">Myynnin hallinta</span><span class="sxs-lookup"><span data-stu-id="a3892-137">Manage Sales</span></span>](sales-manage-sales.md)  
<span data-ttu-id="a3892-138">[Varaston hallinta](inventory-manage-inventory.md)    </span><span class="sxs-lookup"><span data-stu-id="a3892-138">[Manage Inventory](inventory-manage-inventory.md)    </span></span>  
[<span data-ttu-id="a3892-139">Dynamics NAV -ohjelman käyttäminen</span><span class="sxs-lookup"><span data-stu-id="a3892-139">Work with Dynamics NAV</span></span>](ui-work-product.md)

