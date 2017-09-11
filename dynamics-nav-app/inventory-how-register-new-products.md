---
title: "Toimintaohje: Uusien tuotteiden rekisteröiminen"
author: SorenGP
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: df84a4d3e15035cd956c7612a12069844f5601d2
ms.contentlocale: fi-fi
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-register-new-products"></a><span data-ttu-id="6f692-102">Toimintaohje: Uusien tuotteiden rekisteröiminen</span><span class="sxs-lookup"><span data-stu-id="6f692-102">How to: Register New Products</span></span>

<span data-ttu-id="6f692-103">Tuotteet, eli tavarat tai palvelut, joilla käyt kauppaa, ovat liiketoimintasi perusta.</span><span class="sxs-lookup"><span data-stu-id="6f692-103">Products are the basis of your business, the goods or services that you trade in.</span></span> <span data-ttu-id="6f692-104">Jokainen tuote on rekisteröitävä nimikekorttina.</span><span class="sxs-lookup"><span data-stu-id="6f692-104">Each product must be registered as an item card.</span></span>

<span data-ttu-id="6f692-105">**Huomautus**: Dynamics NAV -ohjelmassa tuotteeseen viitataan termillä “nimike”.</span><span class="sxs-lookup"><span data-stu-id="6f692-105">**Note**: In Dynamics NAV, a product is referred to using the term “item”.</span></span>

<span data-ttu-id="6f692-106">Nimikekortti sisältää tiedot, jotka tarvitaan tuotteiden ostamista, tallentamista, myymistä ja toimittamista varten.</span><span class="sxs-lookup"><span data-stu-id="6f692-106">Item cards hold the information that is required to buy, store, sell, deliver, and account for products.</span></span>

<span data-ttu-id="6f692-107">Nimikekortin tyyppi voi olla Varasto tai Palvelu, jolloin voidaan määritellä, onko tuote fyysinen yksikkö vai työaikayksikkö.</span><span class="sxs-lookup"><span data-stu-id="6f692-107">The item card can be of type Inventory or Service to specify if the product is a physical unit or labor time unit.</span></span> <span data-ttu-id="6f692-108">Lukuun ottamatta kenttiä, jotka liittyvät nimikkeen fyysisiin osa-alueisiin, kaikki nimikkeen kortin kentät toimivat samalla tavalla varastonimikkeille ja palveluille.</span><span class="sxs-lookup"><span data-stu-id="6f692-108">Apart from some fields that relate to the physical aspects of an item, all fields on an item card function in the same way for inventory items and services.</span></span> <span data-ttu-id="6f692-109">Lisätietoja nimikkeen myymisestä on kohdassa [Toimintaohje: Tuotteiden myyminen](sales-how-sell-products.md) ja [Toimintaohje: Myynnin laskuttaminen](sales-how-invoice-sales.md).</span><span class="sxs-lookup"><span data-stu-id="6f692-109">For more information about selling an item, see [How to: Sell Products](sales-how-sell-products.md) or [How to: Invoice Sales](sales-how-invoice-sales.md).</span></span>

<span data-ttu-id="6f692-110">**Huomautus**: Jos eri nimikkeen on olemassa asiakasmalleja, ikkuna tulee näkyviin, kun luot uuden nimikkeen kortin, jossa voit valita haluamasi mallin.</span><span class="sxs-lookup"><span data-stu-id="6f692-110">**Note**: If item templates exist for different item types, then a window appears when you create a new item card from where you can select an appropriate template.</span></span> <span data-ttu-id="6f692-111">Jos vain yksi nimikemalli on olemassa, uudet nimikekortit käyttävät aina kyseistä mallia.</span><span class="sxs-lookup"><span data-stu-id="6f692-111">If only one item template exists, then new item cards always use that template.</span></span>

## <a name="to-create-a-new-item-card"></a><span data-ttu-id="6f692-112">Uuden nimikekortin luominen</span><span class="sxs-lookup"><span data-stu-id="6f692-112">To create a new item card</span></span>
1. <span data-ttu-id="6f692-113">Valitse kotisivun **Nimikkeet**-toiminto, kun haluat avata olemassa olevien nimikkeiden luettelon.</span><span class="sxs-lookup"><span data-stu-id="6f692-113">On the Home page, choose the **Items** action to open the list of existing items.</span></span>  
2. <span data-ttu-id="6f692-114">Valitse **Nimikkeet**-ikkunassa **Uusi**-toiminto.</span><span class="sxs-lookup"><span data-stu-id="6f692-114">In the **Items** window, choose the **New** action.</span></span>

    <span data-ttu-id="6f692-115">Jos vain yksi nimikemalli on olemassa, uusi nimikekortti avautuu. Kortissa on kenttiä, jotka on täytetty mallin tiedoilla.</span><span class="sxs-lookup"><span data-stu-id="6f692-115">If only one item template exists, then a new item card opens with some fields filled with information from the template.</span></span>
3. <span data-ttu-id="6f692-116">Valitse **Valitse malli uudelle nimikkeelle** -ikkunassa malli, jota haluat käyttää uudessa nimikekortissa.</span><span class="sxs-lookup"><span data-stu-id="6f692-116">In the **Select a template for a new item** window, choose the template that you want to use for the new item card.</span></span>
4. <span data-ttu-id="6f692-117">Valitse **OK**-painike.</span><span class="sxs-lookup"><span data-stu-id="6f692-117">Choose the **OK** button.</span></span> <span data-ttu-id="6f692-118">Uuden nimikekortti avautuu. Osa kortin kentistä on täytetty mallin tiedoilla.</span><span class="sxs-lookup"><span data-stu-id="6f692-118">A new item card opens with some fields filled with information from the template.</span></span>
5. <span data-ttu-id="6f692-119">Voit täyttää nimikekortin kenttiä tai muuttaa niitä tarvittaessa.</span><span class="sxs-lookup"><span data-stu-id="6f692-119">Proceed to fill or change fields on the item card as necessary.</span></span> <span data-ttu-id="6f692-120">Lue kentän lyhyt kuvaus valitsemalla kenttä tai siirry lisätietoihin valitsemalla linkki.</span><span class="sxs-lookup"><span data-stu-id="6f692-120">Choose a field to read a short description of the field or link to more information.</span></span>

<span data-ttu-id="6f692-121">**Myyntihinnat**-pikavälilehti sisältää erityiset hinnat tai alennukset, jotka haluat myöntää nimikkeelle, jos tietyt ehdot, kuten asiakas, vähimmäistilausmäärä tai päättymispäivämäärä, täyttyvät.</span><span class="sxs-lookup"><span data-stu-id="6f692-121">On the **Sales Prices** FastTab, you can view special prices or discounts that you grant for the item if certain criteria are met, such as customer, minimum order quantity, or ending date.</span></span> <span data-ttu-id="6f692-122">Kukin rivi edustaa erityistä hinnan alennusta tai rivialennusta.</span><span class="sxs-lookup"><span data-stu-id="6f692-122">Each row represents a special price or line discount.</span></span> <span data-ttu-id="6f692-123">Kukin sarake vastaa ehtoa, joka takaa **Yksikköhinta**-kenttään kirjoitetun erikoishinnan tai **Rivialennus-%**-kenttään kirjoitetun rivialennuksen.</span><span class="sxs-lookup"><span data-stu-id="6f692-123">Each column represents a criterion that must apply to warrant the special price that you enter in the **Unit Price** field, or the line discount that you enter in the **Line Discount %** field.</span></span> <span data-ttu-id="6f692-124">Lisätietoja on kohdassa [Myyntihinnan, alennuksen ja maksusopimusten tallentaminen](sales-how-record-sales-price-discount-payment-agreements.md).</span><span class="sxs-lookup"><span data-stu-id="6f692-124">For more information, see [Record Sales Price, Discount, and Payment Agreements](sales-how-record-sales-price-discount-payment-agreements.md).</span></span>

<span data-ttu-id="6f692-125">Nimike on nyt rekisteröity ja nimikekortti on valmis käytettäväksi osto- ja myyntiasiakirjoissa.</span><span class="sxs-lookup"><span data-stu-id="6f692-125">The item is now registered, and the item card is ready to be used on purchase and sales documents.</span></span>

<span data-ttu-id="6f692-126">Jos haluat käyttää tätä nimikekorttia mallina, kun luot uusia nimikkeen kortteja, tallenna se mallina.</span><span class="sxs-lookup"><span data-stu-id="6f692-126">If you want to use this item card as a template when you create new item cards, you can save it as a template.</span></span> <span data-ttu-id="6f692-127">Lisätietoja on seuraavassa osassa.</span><span class="sxs-lookup"><span data-stu-id="6f692-127">For more information, see the following section.</span></span>

## <a name="to-save-the-item-card-as-a-template"></a><span data-ttu-id="6f692-128">Nimikekortin tallentaminen mallina</span><span class="sxs-lookup"><span data-stu-id="6f692-128">To save the item card as a template</span></span>
1. <span data-ttu-id="6f692-129">Valitse **Nimikekortti**-ikkunassa **Tallenna mallina** -toiminto.</span><span class="sxs-lookup"><span data-stu-id="6f692-129">In the **Item Card** window, choose the **Save as Template** action.</span></span> <span data-ttu-id="6f692-130">**Nimikemalli**-ikkuna avautuu ja näyttää nimikekortin mallina.</span><span class="sxs-lookup"><span data-stu-id="6f692-130">The **Item Template** window opens showing the item card as a template.</span></span>
2. <span data-ttu-id="6f692-131">Täytä tarvittavat kentät.</span><span class="sxs-lookup"><span data-stu-id="6f692-131">Fill in the fields as necessary.</span></span> <span data-ttu-id="6f692-132">Lue kentän lyhyt kuvaus valitsemalla kenttä tai siirry lisätietoihin valitsemalla linkki.</span><span class="sxs-lookup"><span data-stu-id="6f692-132">Choose a field to read a short description of the field or link to more information.</span></span>
3. <span data-ttu-id="6f692-133">Voit käyttää dimensioita malleina valitsemalla **Dimensiot**-toiminnon.</span><span class="sxs-lookup"><span data-stu-id="6f692-133">To reuse dimensions in templates, choose the **Dimensions** action.</span></span> <span data-ttu-id="6f692-134">**Dimensiomallit**-ikkuna avautuu ja esittää kaikki dimensiokoodit, jotka on määritetty nimikkeelle.</span><span class="sxs-lookup"><span data-stu-id="6f692-134">The **Dimension Templates** window opens showing any dimension codes that are set up for the item.</span></span>
4. <span data-ttu-id="6f692-135">Muokkaa tai syötä dimensiokoodit, joita käytetään mallin avulla luotuihin uusiin nimikkeen kortteihin.</span><span class="sxs-lookup"><span data-stu-id="6f692-135">Edit or enter dimension codes that will apply to new item cards created by using the template.</span></span>
5. <span data-ttu-id="6f692-136">Kun olet määrittänyt uuden nimikemallin, valitse **OK**-painike.</span><span class="sxs-lookup"><span data-stu-id="6f692-136">When you have completed the new item template, choose the **OK** button.</span></span>

<span data-ttu-id="6f692-137">Nimikemalli lisätään nimikemallien luetteloon niin, että sen avulla voit luoda uusia nimikekortteja.</span><span class="sxs-lookup"><span data-stu-id="6f692-137">The item template is added to the list of item templates, so that you can use it to create new item cards.</span></span>

## <a name="see-also"></a><span data-ttu-id="6f692-138">Katso myös</span><span class="sxs-lookup"><span data-stu-id="6f692-138">See Also</span></span>
  [<span data-ttu-id="6f692-139">Varaston hallinta</span><span class="sxs-lookup"><span data-stu-id="6f692-139">Manage Inventory</span></span>](inventory-manage-inventory.md)  
<span data-ttu-id="6f692-140">  [Ostojen hallinta](purchasing-manage-purchasing.md)</span><span class="sxs-lookup"><span data-stu-id="6f692-140">  [Manage Purchasing](purchasing-manage-purchasing.md)</span></span>  
<span data-ttu-id="6f692-141">  [Myynnin hallinta](sales-manage-sales.md)</span><span class="sxs-lookup"><span data-stu-id="6f692-141">  [Manage Sales](sales-manage-sales.md)</span></span>

