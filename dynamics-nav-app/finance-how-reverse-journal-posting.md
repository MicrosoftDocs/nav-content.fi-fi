---
title: Kirjauksen kumoaminen kirjaamalla palautustapahtuma
description: "Jos olet tehnyt virheellisen kirjauksen yleiseen päiväkirjaan, Peruuta tapahtuma -toiminnolla kumottu kirjaus luo oikean kirjausketjun."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: reimbursement
ms.date: 08/03/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 1dfba8b14019991c95f40ffd5f7fbaed5df414eb
ms.openlocfilehash: 5dc4bae134cb9be93e6fd026dbc88d0eab602abf
ms.contentlocale: fi-fi
ms.lasthandoff: 12/01/2017

---
# <a name="how-to-reverse-postings"></a><span data-ttu-id="a1446-103">Toimintaohje: Kirjausten peruuttaminen</span><span class="sxs-lookup"><span data-stu-id="a1446-103">How to: Reverse Postings</span></span>
<span data-ttu-id="a1446-104">Voit kumota virheellisen kirjauksen päiväkirjaan valitsemalla tapahtuman luomalla peruutustapahtuman (alkuperäistä tapahtumaa vastaava tapahtuma, jossa summakentässä on vastakkainen etumerkki), jossa on sama asiakirjanumero ja kirjauspäivämäärä kuin alkuperäisessä tapahtumassa.</span><span class="sxs-lookup"><span data-stu-id="a1446-104">To undo an erroneous journal posting, you select the entry and create a reverse entry (entries identical to the original entry but with opposite sign in the amount field) with the same document number and posting date as the original entry.</span></span> <span data-ttu-id="a1446-105">Kun olet peruuttanut tapahtuman, lisää tapahtuma korjattuna.</span><span class="sxs-lookup"><span data-stu-id="a1446-105">After reversing an entry, you must make the correct entry.</span></span>

<span data-ttu-id="a1446-106">Vain yleisen päiväkirjan riviltä kirjatut tapahtumat voi peruuttaa.</span><span class="sxs-lookup"><span data-stu-id="a1446-106">You can only reverse entries that are posted from a general journal line.</span></span> <span data-ttu-id="a1446-107">Tapahtuman voi peruuttaa vain kerran.</span><span class="sxs-lookup"><span data-stu-id="a1446-107">An entry can only be reversed once.</span></span>

<span data-ttu-id="a1446-108">Lisätietoja yleisestä päiväkirjasta tehtävistä kirjauksista on ohjeaiheessa [Tapahtumien kirjaaminen suoraan pääkirjanpitoon](finance-how-post-transactions-directly.md).</span><span class="sxs-lookup"><span data-stu-id="a1446-108">For more information about posting from a general journal, see [How to: Post Transactions Directly to the General Ledger](finance-how-post-transactions-directly.md).</span></span>

<span data-ttu-id="a1446-109">Jos olet tehnyt virheellinen negatiivisen määräkirjauksen, kuten kirjannut ostotilaukselle väärän määrän vastaanotetuksi mutta ei laskutetuksi, voit kumota kirjauksen.</span><span class="sxs-lookup"><span data-stu-id="a1446-109">If you have made an incorrect negative quantity posting, such as a purchase order with the wrong number of items and posted it as received but not invoiced, then you can undo the posting.</span></span>

<span data-ttu-id="a1446-110">Jos olet tehnyt virheellinen positiivisen määräkirjauksen, kuten kirjannut ostopalautustilaukselle väärän määrän toimitetuksi mutta ei laskutetuksi, voit kumota kirjauksen.</span><span class="sxs-lookup"><span data-stu-id="a1446-110">If you have made an incorrect positive quantity posting, such as a purchase return order with the wrong number of items and posted it as shipped but not invoiced, then you can undo the posting.</span></span>   

## <a name="to-reverse-the-journal-posting-of-a-general-ledger-entry"></a><span data-ttu-id="a1446-111">Pääkirjanpidon tapahtuman päiväkirjakirjauksen peruuttaminen</span><span class="sxs-lookup"><span data-stu-id="a1446-111">To reverse the journal posting of a general ledger entry</span></span>
<span data-ttu-id="a1446-112">Tapahtumia voi peruuttaa kaikista **Tapahtumakirjaukset**-ikkunoista.</span><span class="sxs-lookup"><span data-stu-id="a1446-112">You can reverse entries from all **Ledger Entries** windows.</span></span> <span data-ttu-id="a1446-113">Seuraava menettely perustuu **Pääkirjanpidon tapahtumat** -ikkunaan.</span><span class="sxs-lookup"><span data-stu-id="a1446-113">The following procedure is based on the **General Ledger Entries** window.</span></span>
1. <span data-ttu-id="a1446-114">Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, anna **Pääkirjanpidon tapahtumat** ja valitse sitten aiheeseen liittyvä linkki.</span><span class="sxs-lookup"><span data-stu-id="a1446-114">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **General Ledger Entries**, and then choose the related link.</span></span>
2. <span data-ttu-id="a1446-115">Valitse ensin peruutettava tapahtuma ja sitten **Peruuta tapahtuma** -toiminto.</span><span class="sxs-lookup"><span data-stu-id="a1446-115">Select the entry that you want to reverse, and then choose the **Reverse Transaction** action.</span></span> <span data-ttu-id="a1446-116">Huomaa, että sen on oltava peräisin päiväkirjan kirjauksesta.</span><span class="sxs-lookup"><span data-stu-id="a1446-116">Note that is must originate from a journal posting.</span></span>
3. <span data-ttu-id="a1446-117">Valitse **Peruuta tapahtumat** -ikkunassa käsiteltävä tapahtuma ja valitse sitten **Peruuta**-toiminto.</span><span class="sxs-lookup"><span data-stu-id="a1446-117">In the **Reverse Transaction Entries** window, select the relevant entry, and then choose the **Reverse** action.</span></span>
4. <span data-ttu-id="a1446-118">Valitse vahvistusviestissä **Kyllä**.</span><span class="sxs-lookup"><span data-stu-id="a1446-118">Choose the **Yes** button on the confirmation message.</span></span>

## <a name="to-undo-a-quantity-posting-on-a-posted-purchase-receipt"></a><span data-ttu-id="a1446-119">Kirjatun ostovastaanoton määrän kirjauksen kumoaminen</span><span class="sxs-lookup"><span data-stu-id="a1446-119">To undo a quantity posting on a posted purchase receipt</span></span>  

1.  <span data-ttu-id="a1446-120">Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, kirjoita **Kirjatut ostovastaanotot** ja valitse sitten aiheeseen liittyvä linkki.</span><span class="sxs-lookup"><span data-stu-id="a1446-120">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Posted Purchase Receipts**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="a1446-121">Avaa kirjattu vastaanotto, jonka haluat kumota.</span><span class="sxs-lookup"><span data-stu-id="a1446-121">Open the posted receipt that you want to undo.</span></span>  
3.  <span data-ttu-id="a1446-122">Valitse kumottavat rivit.</span><span class="sxs-lookup"><span data-stu-id="a1446-122">Select the line or lines that you want to undo.</span></span>  
4.  <span data-ttu-id="a1446-123">Valitse **Peruuta vast.otto** -toiminto.</span><span class="sxs-lookup"><span data-stu-id="a1446-123">Choose **Undo Receipt** action.</span></span>

    <span data-ttu-id="a1446-124">Korjaava rivi lisätään valitun kuittirivin alle.</span><span class="sxs-lookup"><span data-stu-id="a1446-124">A corrective line is inserted under the selected receipt line.</span></span>  

    <span data-ttu-id="a1446-125">Jos määrä vastaanotettiin fyysisen varastoinnin vastaanottona, korjaava rivi lisätään kirjattuun fyysisen varastoinnin vastaanottoon.</span><span class="sxs-lookup"><span data-stu-id="a1446-125">If the quantity was received in a warehouse receipt, then a corrective line is inserted in the posted warehouse receipt.</span></span>  

    <span data-ttu-id="a1446-126">**Vastaanotettu määrä** ja **Vast.otettu laskuttamaton määrä** -kenttien arvoiksi liittyvällä ostotilauksella asetetaan nolla.</span><span class="sxs-lookup"><span data-stu-id="a1446-126">The **Quantity Received** and **Qty. Rcd. Not Invoiced** fields on the related purchase order are set to zero.</span></span>

## <a name="to-undo-and-then-redo-a-quantity-posting-on-a-posted-return-shipment"></a><span data-ttu-id="a1446-127">Kirjatun palautustoimituksen määrän kirjauksen kumoaminen ja tekeminen uudelleen</span><span class="sxs-lookup"><span data-stu-id="a1446-127">To undo and then redo a quantity posting on a posted return shipment</span></span>

1.  <span data-ttu-id="a1446-128">Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, kirjoita **Kirjatut palautustoimitukset** ja valitse sitten aiheeseen liittyvä linkki.</span><span class="sxs-lookup"><span data-stu-id="a1446-128">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Posted Return Shipments**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="a1446-129">Avaa kumottava kirjattu palautustoimitus.</span><span class="sxs-lookup"><span data-stu-id="a1446-129">Open the posted return shipment that you want to undo.</span></span>
3. <span data-ttu-id="a1446-130">Valitse kumottavat rivit.</span><span class="sxs-lookup"><span data-stu-id="a1446-130">Select the line or lines you want to undo.</span></span>  

4.  <span data-ttu-id="a1446-131">Valitse **Peruuta palautustoimitus** -toiminto.</span><span class="sxs-lookup"><span data-stu-id="a1446-131">Choose the **Undo Return Shipment** action.</span></span>  

    <span data-ttu-id="a1446-132">Ohjelma syöttää korjaavan rivin kirjatulle asiakirjalle ja **Toimitettu palautusmäärä** ja **Pal.määrä toimitettu ei laskutettu** -kentät palautustilauksella asetetaan nollaksi.</span><span class="sxs-lookup"><span data-stu-id="a1446-132">A corrective line is inserted in the posted document, and the **Return Qty. Shipped** and **Return Shpd. Not Invd.** fields on the return order are set to zero.</span></span>  

    <span data-ttu-id="a1446-133">Palaa nyt ostopalautustilaukseen ja tee kirjaus uudelleen.</span><span class="sxs-lookup"><span data-stu-id="a1446-133">Now go back to the purchase return order to redo the posting.</span></span>  

5.  <span data-ttu-id="a1446-134">Kirjoita muistiin numero, joka on **Kirjattu palautustoimitus** -ikkunan **Palautustilauksen nro**</span><span class="sxs-lookup"><span data-stu-id="a1446-134">In the **Posted Return Shipment** window, take a note of the number in the **Return Order No.**</span></span> <span data-ttu-id="a1446-135">-kentässä.</span><span class="sxs-lookup"><span data-stu-id="a1446-135">field.</span></span>  
6.  <span data-ttu-id="a1446-136">Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, kirjoita **Ostopalautustilaukset** ja valitse sitten aiheeseen liittyvä linkki.</span><span class="sxs-lookup"><span data-stu-id="a1446-136">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Purchase Return Orders**, and then choose the related link.</span></span>  
7.  <span data-ttu-id="a1446-137">Avaa kyseinen palautustilaus ja valitse **Avaa uudelleen** -toiminto.</span><span class="sxs-lookup"><span data-stu-id="a1446-137">Open the return order in question, and then choose the **Reopen** action.</span></span>  
8.  <span data-ttu-id="a1446-138">Korjaa tapahtuma **Määrä**-kentässä ja kirjaa ostopalautustilaus uudelleen.</span><span class="sxs-lookup"><span data-stu-id="a1446-138">Correct the entry in the **Quantity** field and post the purchase return order again.</span></span>  

## <a name="see-also"></a><span data-ttu-id="a1446-139">Katso myös</span><span class="sxs-lookup"><span data-stu-id="a1446-139">See Also</span></span>
[<span data-ttu-id="a1446-140">Toimintaohje: Tapahtumien kirjaaminen suoraan pääkirjanpitoon</span><span class="sxs-lookup"><span data-stu-id="a1446-140">How to: Post Transactions Directly to the General Ledger</span></span>](finance-how-post-transactions-directly.md)  
[<span data-ttu-id="a1446-141">Yleisten päiväkirjojen käyttäminen</span><span class="sxs-lookup"><span data-stu-id="a1446-141">Working with General Journals</span></span>](ui-work-general-journals.md)  
[<span data-ttu-id="a1446-142">Rahoitus</span><span class="sxs-lookup"><span data-stu-id="a1446-142">Finance</span></span>](finance.md)  
<span data-ttu-id="a1446-143">[[!INCLUDE[d365fin](includes/d365fin_md.md)] -ohjelman käyttäminen](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="a1446-143">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>  

