---
title: Ennakkomaksujen korjaaminen
description: "Joskus sinun on korjattava tilausta ennakkomaksulaskun kirjaamisen jälkeen. Voit lisätä tilaukseen uusia rivejä ennakkomaksun lähettämisen jälkeen ja voit kirjata uuden ennakkomaksulaskun, mutta et voi poistaa riviä tilauksesta sen jälkeen kun rivin ennakkomaksu on laskutettu."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 08/04/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 1dfba8b14019991c95f40ffd5f7fbaed5df414eb
ms.openlocfilehash: 3bd8e6cfd4b0309d74340840e416979021a55393
ms.contentlocale: fi-fi
ms.lasthandoff: 12/01/2017

---
# <a name="how-to-correct-prepayments"></a><span data-ttu-id="6a8eb-104">Ennakkomaksujen korjaaminen</span><span class="sxs-lookup"><span data-stu-id="6a8eb-104">How to: Correct Prepayments</span></span>
<span data-ttu-id="6a8eb-105">Joskus sinun on korjattava tilausta ennakkomaksulaskun kirjaamisen jälkeen.</span><span class="sxs-lookup"><span data-stu-id="6a8eb-105">You can make a correction to an order after you have posted a prepayment invoice for the order.</span></span> <span data-ttu-id="6a8eb-106">Voit lisätä tilaukseen uusia rivejä ennakkomaksun lähettämisen jälkeen ja voit kirjata uuden ennakkomaksulaskun, mutta et voi poistaa riviä tilauksesta sen jälkeen, kun rivin ennakkomaksu on laskutettu.</span><span class="sxs-lookup"><span data-stu-id="6a8eb-106">You can add new lines to an order after issuing a prepayment, and then you can post another prepayment invoice, but you cannot delete a line from an order after a prepayment has been invoiced for the line.</span></span>  

## <a name="to-correct-a-prepayment"></a><span data-ttu-id="6a8eb-107">Ennakkomaksujen korjaaminen</span><span class="sxs-lookup"><span data-stu-id="6a8eb-107">To correct a prepayment</span></span>
<span data-ttu-id="6a8eb-108">Seuraavaksi kerrotaan, miten kaikki myyntitilauksen laskutetut ennakkomaksut peruutetaan luomalla ennakkomaksun hyvityslasku.</span><span class="sxs-lookup"><span data-stu-id="6a8eb-108">The following procedure shows how to issue a prepayment credit memo to cancel all invoiced prepayments for a sales order.</span></span>  
1. <span data-ttu-id="6a8eb-109">Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, kirjoita **Myyntitilaukset** ja valitse sitten aiheeseen liittyvä linkki.</span><span class="sxs-lookup"><span data-stu-id="6a8eb-109">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Sales Orders**, and then choose the related link.</span></span>  
2. <span data-ttu-id="6a8eb-110">Avaa asianomainen myyntitilaus.</span><span class="sxs-lookup"><span data-stu-id="6a8eb-110">Open the relevant sales order.</span></span>
3. <span data-ttu-id="6a8eb-111">Valitse ensin **Ennakkomaksu**-toiminto, sitten **Kirjaa ennakkomaksun hyvityslasku**- tai **Kirjaa ja tulosta ennakkomaksun hyvityslasku** -toiminto.</span><span class="sxs-lookup"><span data-stu-id="6a8eb-111">Choose the **Prepayment** action, and then choose the **Post Prepayment Credit Memo** action or the **Post and Print Prepmt. Cr. Memo** action.</span></span>  
4. <span data-ttu-id="6a8eb-112">Siirry **Myyntihyvityslasku**-ikkunassa korjaamaan kyseiset tapahtumat samalla tavoin kuin muissakin myyntihyvityslaskussa.</span><span class="sxs-lookup"><span data-stu-id="6a8eb-112">In the **Sales Credit Memo** window, proceed to correct the relevant entries, as for any sales credit memo.</span></span> <span data-ttu-id="6a8eb-113">Lisätietoja on kohdassa [Toimintaohje: Myyntipalautusten tai -peruutusten käsitteleminen](sales-how-process-sales-returns-cancellations.md).</span><span class="sxs-lookup"><span data-stu-id="6a8eb-113">For more information, see [How to: Process Sales Returns or Cancellations](sales-how-process-sales-returns-cancellations.md).</span></span>     

    > [!NOTE]  
    > <span data-ttu-id="6a8eb-114">Jos haluat vähentää **Rivisumma**-kentän summaa, sinun on ensin kasvatettava rivin ennakkomaksuprosenttia, jotta **Ennakkomaksun rivisumma** -kentän arvo ei ole pienempi kuin **Laskutettu ennakkomaksun summa** -kentän arvo.</span><span class="sxs-lookup"><span data-stu-id="6a8eb-114">To Reduce the amount in the **Line Amount** field, you must first increase the prepayment percentage on the line so that the value in the **Prepmt. Line Amount** field is not decreased below the value in the **Prepmt. Amt. Inv.** field.</span></span>

5. <span data-ttu-id="6a8eb-115">Tee ennakkomaksu myyntihyvityslaskun uusille riveille valitsemalla **Ennakkomaksu**-toiminto ja valitsemalla sitten **Kirjaa ennakkomaksulasku**- tai **Kirjaa ja tulosta ennakkomaksulasku** -toiminto.</span><span class="sxs-lookup"><span data-stu-id="6a8eb-115">To make a prepayment invoice for any new lines in the sales credit memo, choose the **Prepayment** action, and then choose the **Post Prepayment Invoice** action or the **Post and Print Prepmt. Invoice** action.</span></span>  
6. <span data-ttu-id="6a8eb-116">Voit luoda ylimääräisen ennakkomaksulaskun nostamalla vähintään yhden rivin ennakkomaksua ja kirjaamalla ennakkomaksulaskun.</span><span class="sxs-lookup"><span data-stu-id="6a8eb-116">To issue an additional prepayment invoice, increase the prepayment amount on one or more lines and post the prepayment invoice.</span></span> <span data-ttu-id="6a8eb-117">Uusi lasku luodaan ennakkomaksun laskutettujen summien ja uusien ennakkomaksun summien välisen eron vuoksi.</span><span class="sxs-lookup"><span data-stu-id="6a8eb-117">A new invoice will be created for the difference between the prepayment amounts invoiced and the new prepayment amounts.</span></span>  

## <a name="see-also"></a><span data-ttu-id="6a8eb-118">Katso myös</span><span class="sxs-lookup"><span data-stu-id="6a8eb-118">See Also</span></span>  
[<span data-ttu-id="6a8eb-119">Ennakkomaksujen laskuttaminen</span><span class="sxs-lookup"><span data-stu-id="6a8eb-119">Invoicing Prepayments</span></span>](finance-invoice-prepayments.md)  
[<span data-ttu-id="6a8eb-120">Vaihekuvaus: Myynnin ennakkomaksujen määrittäminen ja laskuttaminen</span><span class="sxs-lookup"><span data-stu-id="6a8eb-120">Walkthrough: Setting Up and Invoicing Sales Prepayments</span></span>](walkthrough-setting-up-and-invoicing-sales-prepayments.md)  
[<span data-ttu-id="6a8eb-121">Rahoitus</span><span class="sxs-lookup"><span data-stu-id="6a8eb-121">Finance</span></span>](finance.md)  
<span data-ttu-id="6a8eb-122">[[!INCLUDE[d365fin](includes/d365fin_md.md)] -ohjelman käyttäminen](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="6a8eb-122">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>

