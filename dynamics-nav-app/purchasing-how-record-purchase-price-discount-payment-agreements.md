---
title: 'Toimintaohje: Ostohintojen ja -alennusten tallentaminen'
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
ms.openlocfilehash: af5ba3a17412ba4c123c4d3cb337b8d5df36cace
ms.contentlocale: fi-fi
ms.lasthandoff: 07/19/2017

---

#<a name="how-to-record-purchase-prices-and-discounts"></a><span data-ttu-id="a3fbc-102">Toimintaohje: Ostohintojen ja -alennusten tallentaminen</span><span class="sxs-lookup"><span data-stu-id="a3fbc-102">How to: Record Purchase Prices and Discounts</span></span>
<span data-ttu-id="a3fbc-103">Eri hinta- ja alennussopimukset, joita käytetään ostettaessa eri toimittajilta, täytyy määrittää, jotta sovittuja sääntöjä ja arvoja sovelletaan toimittajille luotaviin ostoasiakirjoihin.</span><span class="sxs-lookup"><span data-stu-id="a3fbc-103">The different price and discount agreements that apply when you buy from different vendors must be defined so that the agreed rules and values are applied to purchase documents that you create for the vendors.</span></span>

<span data-ttu-id="a3fbc-104">Ostoriveille lisätään erikoisostohinta, jos tietty toimittajan, nimikkeen, vähimmäismäärän, mittayksikön sekä aloitus- ja lopetuspäivämäärän yhdistelmä on olemassa.</span><span class="sxs-lookup"><span data-stu-id="a3fbc-104">Concerning prices, you can have a special purchase price inserted on purchase lines if a certain combination of vendor, item, minimum quantity, unit of measure, or starting/ending date exists.</span></span>

<span data-ttu-id="a3fbc-105">Voit määrittää seuraavat kaksi ostoalennustyyppiä:</span><span class="sxs-lookup"><span data-stu-id="a3fbc-105">Concerning discounts, you can set up and use two types of purchase discounts:</span></span>

|<span data-ttu-id="a3fbc-106">Alennustyyppi</span><span class="sxs-lookup"><span data-stu-id="a3fbc-106">Discount Type</span></span> |<span data-ttu-id="a3fbc-107">Kuvaus</span><span class="sxs-lookup"><span data-stu-id="a3fbc-107">Description</span></span> |
|--------------|------------|
|<span data-ttu-id="a3fbc-108">**Ostorivin alennus**</span><span class="sxs-lookup"><span data-stu-id="a3fbc-108">**Purchase Line Discount**</span></span>|<span data-ttu-id="a3fbc-109">Ostoriveille lisättävä summa-alennus, jos tietty toimittajan, nimikkeen, vähimmäismäärän, mittayksikön sekä aloitus- ja lopetuspäivämäärän yhdistelmä on olemassa.</span><span class="sxs-lookup"><span data-stu-id="a3fbc-109">An amount discount that is inserted on purchase lines if a certain combination of vendor, item, minimum quantity, unit of measure, or starting/ending date exists.</span></span> <span data-ttu-id="a3fbc-110">Tätä käytetään samoin kuin ostohinnoissa.</span><span class="sxs-lookup"><span data-stu-id="a3fbc-110">This works in the same way as for purchase prices.</span></span>|
|<span data-ttu-id="a3fbc-111">**Laskualennus**</span><span class="sxs-lookup"><span data-stu-id="a3fbc-111">**Invoice Discount**</span></span>|<span data-ttu-id="a3fbc-112">Prosenttialennus, joka vähennetään kokonaissummasta, kun ostoasiakirjan kaikkien rivien summa ylittää määritetyn vähimmäisarvon.</span><span class="sxs-lookup"><span data-stu-id="a3fbc-112">A percentage discount that is subtracted from the document total if the value amount of all lines on a purchase document exceeds a certain minimum.</span></span>|

<span data-ttu-id="a3fbc-113">Koska ostorivin alennukset ja ostohinnat perustuvat nimikkeen ja toimittajan yhdistelmään, voit lisätä tämän määrityksen myös nimikkeen kortista, jossa säännöt ja arvot on määritetty.</span><span class="sxs-lookup"><span data-stu-id="a3fbc-113">Because purchase line discounts and purchase prices are based on a combination of item and vendor, you can also enter this configuration from the item card, where the rules and values are defined.</span></span> <span data-ttu-id="a3fbc-114">Lisätietoja on kohdassa [Toimintaohje: Uusien tuotteiden rekisteröiminen](inventory-how-register-new-products.md).</span><span class="sxs-lookup"><span data-stu-id="a3fbc-114">For more information, see [How to: Register New Products](inventory-how-register-new-products.md).</span></span>

## <a name="to-set-up-a-special-purchase-price-for-a-vendor"></a><span data-ttu-id="a3fbc-115">Tietyn ostohinnan määrittäminen toimittajalle</span><span class="sxs-lookup"><span data-stu-id="a3fbc-115">To set up a special purchase price for a vendor</span></span>
1. <span data-ttu-id="a3fbc-116">Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Toimittajat** ja valitse sitten aiheeseen liittyvä linkki.</span><span class="sxs-lookup"><span data-stu-id="a3fbc-116">In the top right corner, choose the **Search for Page or Report** icon, enter **Vendors**, and then choose the related link.</span></span>
2. <span data-ttu-id="a3fbc-117">Avaa asianmukainen toimittajan kortti ja valitse **Hinnat**-toiminto.</span><span class="sxs-lookup"><span data-stu-id="a3fbc-117">Open the relevant vendor card, and then choose the **Prices** action.</span></span>

    <span data-ttu-id="a3fbc-118">**Ostotyyppi**-kenttään täytetään **toimittajan** tiedot ja **Ostokoodi**-kenttään täytetään toimittajan numero.</span><span class="sxs-lookup"><span data-stu-id="a3fbc-118">The **Purchase Type** field is prefilled with **Vendor**, and the **Purchase Code** field is prefilled with the vendor number.</span></span>
3. <span data-ttu-id="a3fbc-119">Täytä tarvittaessa rivin muut kentät.</span><span class="sxs-lookup"><span data-stu-id="a3fbc-119">Fill in the fields on the line as necessary.</span></span> <span data-ttu-id="a3fbc-120">Lue kentän lyhyt kuvaus valitsemalla kenttä tai siirry lisätietoihin valitsemalla linkki.</span><span class="sxs-lookup"><span data-stu-id="a3fbc-120">Choose a field to read a short description of the field or link to more information.</span></span>
4. <span data-ttu-id="a3fbc-121">Täytä jokaisen sellaisen yhdistelmän rivi, jonka toimittaja myöntää sinulle ostorivialennuksen.</span><span class="sxs-lookup"><span data-stu-id="a3fbc-121">Fill a line for each combination for which the vendor grants you a purchase line discount.</span></span>

## <a name="to-set-up-a-line-discount-for-a-vendor"></a><span data-ttu-id="a3fbc-122">Rivialennuksen määrittäminen toimittajalle</span><span class="sxs-lookup"><span data-stu-id="a3fbc-122">To set up a line discount for a vendor</span></span>
1. <span data-ttu-id="a3fbc-123">Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Toimittajat** ja valitse sitten aiheeseen liittyvä linkki.</span><span class="sxs-lookup"><span data-stu-id="a3fbc-123">In the top right corner, choose the **Search for Page or Report** icon, enter **Vendors**, and then choose the related link.</span></span>
2. <span data-ttu-id="a3fbc-124">Avaa asianmukainen toimittajan kortti ja valitse **Rivialennukset**-toiminto.</span><span class="sxs-lookup"><span data-stu-id="a3fbc-124">Open the relevant vendor card, and then choose the **Line Discounts** action.</span></span>

    <span data-ttu-id="a3fbc-125">**Ostotyyppi**-kenttään täytetään **toimittajan** tiedot ja **Ostokoodi**-kenttään täytetään toimittajan numero.</span><span class="sxs-lookup"><span data-stu-id="a3fbc-125">The **Purchase Type** field is prefilled with **Vendor**, and the **Purchase Code** field is prefilled with the vendor number.</span></span>
3. <span data-ttu-id="a3fbc-126">Täytä tarvittaessa rivin muut kentät.</span><span class="sxs-lookup"><span data-stu-id="a3fbc-126">Fill in the fields on the line as necessary.</span></span> <span data-ttu-id="a3fbc-127">Lue kentän lyhyt kuvaus valitsemalla kenttä tai siirry lisätietoihin valitsemalla linkki.</span><span class="sxs-lookup"><span data-stu-id="a3fbc-127">Choose a field to read a short description of the field or link to more information.</span></span>
4. <span data-ttu-id="a3fbc-128">Täytä jokaisen sellaisen yhdistelmän rivi, jonka toimittaja myöntää sinulle ostorivialennuksen.</span><span class="sxs-lookup"><span data-stu-id="a3fbc-128">Fill a line for each combination for which the vendor grants you a purchase line discount.</span></span>

## <a name="to-set-up-an-invoice-discount-for-a-vendor"></a><span data-ttu-id="a3fbc-129">Laskualennuksen määrittäminen toimittajalle</span><span class="sxs-lookup"><span data-stu-id="a3fbc-129">To set up an invoice discount for a vendor</span></span>
<span data-ttu-id="a3fbc-130">Kun toimittajat ovat kertoneet sinulle myöntämänsä laskualennukset, syötä laskun alennuskoodi toimittajien kortteihin ja määritä kunkin koodin ehdot.</span><span class="sxs-lookup"><span data-stu-id="a3fbc-130">When your vendors have informed you which invoice discounts they grant, enter the invoice discount code on the vendor cards and set up the terms for each code.</span></span>

1. <span data-ttu-id="a3fbc-131">Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Toimittajat** ja valitse sitten aiheeseen liittyvä linkki.</span><span class="sxs-lookup"><span data-stu-id="a3fbc-131">In the top right corner, choose the **Search for Page or Report** icon, enter **Vendors**, and then choose the related link.</span></span>
2. <span data-ttu-id="a3fbc-132">Avaa sen toimittajan kortti, jolle myönnetään laskun alennuksia.</span><span class="sxs-lookup"><span data-stu-id="a3fbc-132">Open the vendor card for a vendor that will be eligible for invoice discounts.</span></span>
3. <span data-ttu-id="a3fbc-133">Valitse **Laskualennuksen koodi** -kentässä asianmukaisille laskualennuksen ehdoille koodi, jonka avulla toimittajan laskualennukset lasketaan.</span><span class="sxs-lookup"><span data-stu-id="a3fbc-133">In the **Invoice Disc. Code** field, select a code for the relevant invoice discount terms to use to calculate invoice discounts for the vendor.</span></span>

    <span data-ttu-id="a3fbc-134">**Huomautus**: Laskualennuksen koodit löytyvät olemassa olevien toimittajien korteista.</span><span class="sxs-lookup"><span data-stu-id="a3fbc-134">**Note**: Invoice discount codes are represented by existing vendor cards.</span></span> <span data-ttu-id="a3fbc-135">Näin voit nopeasti liittää laskualennusten ehtoja toimittajiin poimimalla sellaisten toimittajien nimet, joilla on samat ehdot.</span><span class="sxs-lookup"><span data-stu-id="a3fbc-135">This enables you to quickly assign invoice discount terms to vendors by picking the name of another vendors who will have the same terms.</span></span>

    <span data-ttu-id="a3fbc-136">Jatka uuden ostolaskun alennusehtojen määrittämiseen.</span><span class="sxs-lookup"><span data-stu-id="a3fbc-136">Proceed to set up new the purchase invoice discount terms.</span></span>
4. <span data-ttu-id="a3fbc-137">Valitse **Toimittajan kortti** -ikkunassa **Laskualennukset**-toiminto.</span><span class="sxs-lookup"><span data-stu-id="a3fbc-137">In the **Vendor Card** window, choose the **Invoice Discounts** action.</span></span> <span data-ttu-id="a3fbc-138">**Toimittajien laskualennukset** -ikkuna aukeaa.</span><span class="sxs-lookup"><span data-stu-id="a3fbc-138">The **Vend. Invoice Discounts** window opens.</span></span>
5. <span data-ttu-id="a3fbc-139">Syötä **Valuutan koodi** -kenttään sen valuutan koodi, johon rivin laskualennuksen ehdot kohdistetaan.</span><span class="sxs-lookup"><span data-stu-id="a3fbc-139">In the **Currency Code** field, enter the code for a currency that the invoice discount terms on the line applies to.</span></span> <span data-ttu-id="a3fbc-140">Jätä kenttä tyhjäksi, jos laskualennuksen ehdot määritetään Yhdysvaltojen dollareina.</span><span class="sxs-lookup"><span data-stu-id="a3fbc-140">Leave the field blank to set up invoice discount terms in USD.</span></span>
6. <span data-ttu-id="a3fbc-141">Syötä **Vähimmäissumma**-kenttään laskun vähimmäissumma, joka oikeuttaa alennukseen.</span><span class="sxs-lookup"><span data-stu-id="a3fbc-141">In the **Minimum Amount** field, enter the minimum amount that an invoice must have to be eligible for the discount.</span></span>
7. <span data-ttu-id="a3fbc-142">Syötä **Alennus-%**-kohtaan laskun alennus prosentteina laskun summasta.</span><span class="sxs-lookup"><span data-stu-id="a3fbc-142">In the **Discount %** field, enter the invoice discount as a percentage of the invoice amount.</span></span>
8. <span data-ttu-id="a3fbc-143">Toista vaiheet 5–7 jokaiselle valuutalle, jossa toimittaja saa eri laskualennuksen.</span><span class="sxs-lookup"><span data-stu-id="a3fbc-143">Repeat steps 5 through 7 for each currency that the vendor will receive a different invoice discount for.</span></span>

<span data-ttu-id="a3fbc-144">Laskualennus on nyt määritetty ja liitetty kyseiselle toimittajalle.</span><span class="sxs-lookup"><span data-stu-id="a3fbc-144">The invoice discount is now set up and assigned to the vendor in question.</span></span> <span data-ttu-id="a3fbc-145">Kun valitset toimittajakoodin muiden toimittajien korttien **Laskun alennuskoodi** -kentässä, sama laskualennus liitetään myös näille toimittajille.</span><span class="sxs-lookup"><span data-stu-id="a3fbc-145">When you select the vendor code in the **Invoice Disc. Code** field on other vendor cards, the same invoice discount is assigned to those vendor.</span></span>

## <a name="see-also"></a><span data-ttu-id="a3fbc-146">Katso myös</span><span class="sxs-lookup"><span data-stu-id="a3fbc-146">See Also</span></span>  
[<span data-ttu-id="a3fbc-147">Oston määrittäminen</span><span class="sxs-lookup"><span data-stu-id="a3fbc-147">Set Up Purchasing</span></span>](purchasing-setup-purchasing.md)  
[<span data-ttu-id="a3fbc-148">Ostojen hallinta</span><span class="sxs-lookup"><span data-stu-id="a3fbc-148">Manage Purchasing</span></span>](purchasing-manage-purchasing.md)

