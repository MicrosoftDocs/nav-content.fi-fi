---
title: 'Toimintaohje: Myyntihintojen ja -alennusten tallentaminen'
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
ms.openlocfilehash: 80a0ac1edc994f44795f7f907a647b269578bc47
ms.contentlocale: fi-fi
ms.lasthandoff: 07/19/2017

---

# <a name="how-to-record-sales-prices-and-discounts"></a><span data-ttu-id="ccf93-102">Toimintaohje: Myyntihintojen ja -alennusten tallentaminen</span><span class="sxs-lookup"><span data-stu-id="ccf93-102">How to: Record Sales Prices and Discounts</span></span>
<span data-ttu-id="ccf93-103">Eri asiakkaiden hinta- ja alennussopimukset on määritettävä, jotta asiakkaille luotavissa myyntiasiakirjoissa käytetään sovittuja sääntöjä ja arvoja.</span><span class="sxs-lookup"><span data-stu-id="ccf93-103">The different price and discount agreements that apply when selling to different customers must be defined so that the agreed rules and values are applied to sales documents that you create for the customers.</span></span>

<span data-ttu-id="ccf93-104">Myyntiriveille lisätään erikoismyyntihinta, jos tietty asiakkaan, nimikkeen, vähimmäismäärän, mittayksikön sekä aloitus- ja lopetuspäivämäärän yhdistelmä on olemassa.</span><span class="sxs-lookup"><span data-stu-id="ccf93-104">Concerning prices, you can have a special sales price inserted on sales lines if a certain combination of customer, item, minimum quantity, unit of measure, or starting/ending date exists.</span></span>

<span data-ttu-id="ccf93-105">Voit määrittää seuraavat kaksi myyntialennustyyppiä:</span><span class="sxs-lookup"><span data-stu-id="ccf93-105">Concerning discounts, you can set up and use two types of sales discounts:</span></span>

|<span data-ttu-id="ccf93-106">Alennustyyppi</span><span class="sxs-lookup"><span data-stu-id="ccf93-106">Discount Type</span></span> |<span data-ttu-id="ccf93-107">Kuvaus</span><span class="sxs-lookup"><span data-stu-id="ccf93-107">Description</span></span> |
|--------------|------------|
|<span data-ttu-id="ccf93-108">**Myyntirivin alennus**</span><span class="sxs-lookup"><span data-stu-id="ccf93-108">**Sales Line Discount**</span></span>|<span data-ttu-id="ccf93-109">Myyntiriveille lisättävä summa-alennus, jos tietty asiakkaan, nimikkeen, vähimmäismäärän, mittayksikön sekä aloitus- ja lopetuspäivämäärän yhdistelmä on olemassa.</span><span class="sxs-lookup"><span data-stu-id="ccf93-109">An amount discount that is inserted on sales lines if a certain combination of customer, item, minimum quantity, unit of measure, or starting/ending date exists.</span></span> <span data-ttu-id="ccf93-110">Tätä käytetään samoin kuin myyntihinnoissa.</span><span class="sxs-lookup"><span data-stu-id="ccf93-110">This works in the same way as for sales prices.</span></span>|
|<span data-ttu-id="ccf93-111">**Laskualennus**</span><span class="sxs-lookup"><span data-stu-id="ccf93-111">**Invoice Discount**</span></span>|<span data-ttu-id="ccf93-112">Prosenttialennus, joka vähennetään kokonaissummasta, kun myyntiasiakirjan kaikkien rivien summa ylittää määritetyn vähimmäisarvon.</span><span class="sxs-lookup"><span data-stu-id="ccf93-112">A percentage discount that is subtracted from the document total if the value amount of all lines on a sales document exceeds a certain minimum.</span></span>|

<span data-ttu-id="ccf93-113">Koska myyntihinnat ja myyntirivialennukset perustuvat nimikkeen ja asiakkaan yhdistelmään, voit tehdä tämän määrityksen myös sen nimikkeen kortissa, jota säännöt ja arvot koskevat.</span><span class="sxs-lookup"><span data-stu-id="ccf93-113">Because sales prices and sales line discounts are based on a combination of item and customer, you can also perform this configuration from the item card of the item where the rules and values apply.</span></span>

## <a name="to-set-up-a-sales-price-for-a-customer"></a><span data-ttu-id="ccf93-114">Myyntihinnan määrittäminen asiakkaalle</span><span class="sxs-lookup"><span data-stu-id="ccf93-114">To set up a sales price for a customer</span></span>
1. <span data-ttu-id="ccf93-115">Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Asiakkaat** ja valitse sitten aiheeseen liittyvä linkki.</span><span class="sxs-lookup"><span data-stu-id="ccf93-115">In the top right corner, choose the **Search for Page or Report** icon, enter **Customers**, and then choose the related link.</span></span>
2. <span data-ttu-id="ccf93-116">Avaa kyseessä olevan asiakkaan kortti ja valitse **Hinnat**-toiminto.</span><span class="sxs-lookup"><span data-stu-id="ccf93-116">Open the relevant customer card, and then choose the **Prices** action.</span></span>

    <span data-ttu-id="ccf93-117">**Myynnin tyyppi** -kentän arvoksi esitäytetään **Asiakas**. **Myyntikoodi** -kentän arvoksi esitäytetään asiakasnumero.</span><span class="sxs-lookup"><span data-stu-id="ccf93-117">The **Sales Type** field is prefilled with **Customer**, and the **Sales Code** field is prefilled with the customer number.</span></span>
3. <span data-ttu-id="ccf93-118">Täytä tarvittaessa rivin muut kentät.</span><span class="sxs-lookup"><span data-stu-id="ccf93-118">Fill in the fields on the line as necessary.</span></span> <span data-ttu-id="ccf93-119">Lue kentän lyhyt kuvaus valitsemalla kenttä tai siirry lisätietoihin valitsemalla linkki.</span><span class="sxs-lookup"><span data-stu-id="ccf93-119">Choose a field to read a short description of the field or link to more information.</span></span>
4. <span data-ttu-id="ccf93-120">Täytä rivi jokaiselle yhdistelmälle, jossa asiakkaalle myönnetään erikoismyyntihinta.</span><span class="sxs-lookup"><span data-stu-id="ccf93-120">Fill a line for each combination that will grant a special sales price to the customer.</span></span>

## <a name="to-set-up-a-sales-line-discount-for-a-customer"></a><span data-ttu-id="ccf93-121">Myyntirivialennuksien määrittäminen asiakkaalle</span><span class="sxs-lookup"><span data-stu-id="ccf93-121">To set up a sales line discount for a customer</span></span>
1. <span data-ttu-id="ccf93-122">Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Asiakkaat** ja valitse sitten aiheeseen liittyvä linkki.</span><span class="sxs-lookup"><span data-stu-id="ccf93-122">In the top right corner, choose the **Search for Page or Report** icon, enter **Customers**, and then choose the related link.</span></span>
2. <span data-ttu-id="ccf93-123">Avaa kyseessä olevan asiakkaan kortti ja valitse **Rivialennukset**-toiminto.</span><span class="sxs-lookup"><span data-stu-id="ccf93-123">Open the relevant customer card, and then choose the **Line Discounts** action.</span></span>

    <span data-ttu-id="ccf93-124">**Myynnin tyyppi** -kentän arvoksi esitäytetään **Asiakas**. **Myyntikoodi** -kentän arvoksi esitäytetään asiakasnumero.</span><span class="sxs-lookup"><span data-stu-id="ccf93-124">The **Sales Type** field is prefilled with **Customer**, and the **Sales Code** field is prefilled with the customer number.</span></span>
3.  <span data-ttu-id="ccf93-125">Täytä tarvittaessa rivin muut kentät.</span><span class="sxs-lookup"><span data-stu-id="ccf93-125">Fill in the fields on the line as necessary.</span></span> <span data-ttu-id="ccf93-126">Lue kentän lyhyt kuvaus valitsemalla kenttä tai siirry lisätietoihin valitsemalla linkki.</span><span class="sxs-lookup"><span data-stu-id="ccf93-126">Choose a field to read a short description of the field or link to more information.</span></span>
4. <span data-ttu-id="ccf93-127">Täytä rivi jokaiselle yhdistelmälle, jossa asiakkaalle myönnetään myyntirivialennus.</span><span class="sxs-lookup"><span data-stu-id="ccf93-127">Fill a line for each combination that will grant a sales line discount to the customer.</span></span>

## <a name="to-set-up-an-invoice-discount-for-a-customer"></a><span data-ttu-id="ccf93-128">Laskualennuksen määrittäminen asiakkaalle</span><span class="sxs-lookup"><span data-stu-id="ccf93-128">To set up an invoice discount for a customer</span></span>
<span data-ttu-id="ccf93-129">Kun olet määrittänyt asiakkaat, joille myönnetään laskun alennuksia, määritä laskun alennuskoodi asiakkaiden kortteihin ja määritä kunkin koodin ehdot.</span><span class="sxs-lookup"><span data-stu-id="ccf93-129">When you have decided which customers are eligible for invoice discounts, enter the invoice discount code on the customer cards and set up the terms for each code.</span></span>

1. <span data-ttu-id="ccf93-130">Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Asiakkaat** ja valitse sitten aiheeseen liittyvä linkki.</span><span class="sxs-lookup"><span data-stu-id="ccf93-130">In the top right corner, choose the **Search for Page or Report** icon, enter **Customers**, and then choose the related link.</span></span>
2. <span data-ttu-id="ccf93-131">Avaa sen asiakkaan kortti, jolle myönnetään laskun alennuksia.</span><span class="sxs-lookup"><span data-stu-id="ccf93-131">Open the customer card for a customer that will be eligible for invoice discounts.</span></span>
3. <span data-ttu-id="ccf93-132">Valitse **Laskualennuksen koodi** -kentässä asianmukaisille laskualennuksen ehdoille koodi, jonka avulla asiakkaan laskualennukset lasketaan.</span><span class="sxs-lookup"><span data-stu-id="ccf93-132">In the **Invoice Disc. Code** field, select a code for the relevant invoice discount terms to use to calculate invoice discounts for the customer.</span></span>

    <span data-ttu-id="ccf93-133">**Huomautus**: Laskualennuksen koodit löytyvät olemassa olevien asiakkaiden korteista.</span><span class="sxs-lookup"><span data-stu-id="ccf93-133">**Note**: Invoice discount codes are represented by existing customer cards.</span></span> <span data-ttu-id="ccf93-134">Näin voit nopeasti liittää laskualennusten ehtoja asiakkaisiin poimimalla sellaisen asiakkaan nimen, jolla on samat ehdot.</span><span class="sxs-lookup"><span data-stu-id="ccf93-134">This enables you to quickly assign invoice discount terms to customers by picking the name of another customer who will have the same terms.</span></span>

    <span data-ttu-id="ccf93-135">Jatka uuden myyntilaskun alennusehtojen määrittämiseen.</span><span class="sxs-lookup"><span data-stu-id="ccf93-135">Proceed to set up new the sales invoice discount terms.</span></span>
4. <span data-ttu-id="ccf93-136">Valitse **Asiakkaan kortti** -ikkunassa **Laskualennukset**-toiminto.</span><span class="sxs-lookup"><span data-stu-id="ccf93-136">In the **Customer Card** window, choose the **Invoice Discounts** action.</span></span> <span data-ttu-id="ccf93-137">**Asiakkaan laskualennukset** -ikkuna aukeaa.</span><span class="sxs-lookup"><span data-stu-id="ccf93-137">The **Cust. Invoice Discounts** window opens.</span></span>
5. <span data-ttu-id="ccf93-138">Syötä **Valuutan koodi** -kenttään sen valuutan koodi, johon rivin laskualennuksen ehdot kohdistetaan.</span><span class="sxs-lookup"><span data-stu-id="ccf93-138">In the **Currency Code** field, enter the code for a currency that the invoice discount terms on the line applies to.</span></span> <span data-ttu-id="ccf93-139">Jätä kenttä tyhjäksi, jos laskualennuksen ehdot määritetään Yhdysvaltojen dollareina.</span><span class="sxs-lookup"><span data-stu-id="ccf93-139">Leave the field blank to set up invoice discount terms in USD.</span></span>
6. <span data-ttu-id="ccf93-140">Syötä **Vähimmäissumma**-kenttään laskun vähimmäissumma, joka oikeuttaa alennukseen.</span><span class="sxs-lookup"><span data-stu-id="ccf93-140">In the **Minimum Amount** field, enter the minimum amount that an invoice must have to be eligible for the discount.</span></span>
7. <span data-ttu-id="ccf93-141">Syötä **Alennus-%**-kohtaan laskun alennus prosentteina laskun summasta.</span><span class="sxs-lookup"><span data-stu-id="ccf93-141">In the **Discount %** field, enter the invoice discount as a percentage of the invoice amount.</span></span>
8. <span data-ttu-id="ccf93-142">Toista vaiheet 5–7 jokaiselle valuutalle, jossa asiakas saa eri laskualennuksen.</span><span class="sxs-lookup"><span data-stu-id="ccf93-142">Repeat steps 5 through 7 for each currency that the customer will receive a different invoice discount for.</span></span>

<span data-ttu-id="ccf93-143">Laskualennus on nyt määritetty ja liitetty kyseiselle asiakkaalle.</span><span class="sxs-lookup"><span data-stu-id="ccf93-143">The invoice discount is now set up and assigned to the customer in question.</span></span> <span data-ttu-id="ccf93-144">Kun valitset asiakaskoodin muiden asiakkaiden korttien **Laskun alennuskoodi** -kentässä, sama laskualennus liitetään myös näille asiakkaille.</span><span class="sxs-lookup"><span data-stu-id="ccf93-144">When you select the customer code in the **Invoice Disc. Code** field on other customer cards, the same invoice discount is assigned to those customers.</span></span>

## <a name="see-also"></a><span data-ttu-id="ccf93-145">Katso myös</span><span class="sxs-lookup"><span data-stu-id="ccf93-145">See Also</span></span>  
[<span data-ttu-id="ccf93-146">Myynnin määrittäminen</span><span class="sxs-lookup"><span data-stu-id="ccf93-146">Set Up Sales</span></span>](sales-setup-sales.md)  
[<span data-ttu-id="ccf93-147">Myynnin hallinta</span><span class="sxs-lookup"><span data-stu-id="ccf93-147">Manage Sales</span></span>](sales-manage-sales.md)

