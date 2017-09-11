---
title: "Kirjanpitojakson päättäminen"
author: jswymer
ms.custom: na
ms.date: 09/16/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 929e8f1e391e868122077ad1baa72b7b170aa4d4
ms.contentlocale: fi-fi
ms.lasthandoff: 06/26/2017

---
# <a name="how-to-close-accounting-periods"></a><span data-ttu-id="9f32e-102">Kirjanpitojakson päättäminen</span><span class="sxs-lookup"><span data-stu-id="9f32e-102">How to: Close Accounting Periods</span></span>
<span data-ttu-id="9f32e-103">Kun tilikausi on ohi, sinun täytyy päättää tilikauteen sisältyvät kirjanpitojaksot.</span><span class="sxs-lookup"><span data-stu-id="9f32e-103">When a fiscal year is over, you must close the periods that comprise it.</span></span>

## <a name="to-close-accounting-periods"></a><span data-ttu-id="9f32e-104">Kirjanpitojakson päättäminen</span><span class="sxs-lookup"><span data-stu-id="9f32e-104">To close accounting periods</span></span>
1. <span data-ttu-id="9f32e-105">Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Kirjanpitojaksot** ja valitse sitten aiheeseen liittyvä linkki.</span><span class="sxs-lookup"><span data-stu-id="9f32e-105">In the top right corner, choose the **Search for Page or Report** icon, enter **Accounting Periods**, and then choose the related link.</span></span>
2. <span data-ttu-id="9f32e-106">Valitse **Kirjanpitojaksot**-ikkunassa **Sulje vuosi** -toiminto.</span><span class="sxs-lookup"><span data-stu-id="9f32e-106">In the **Accounting Periods** window, choose the **Close Year** action.</span></span>

    <span data-ttu-id="9f32e-107">Jos avoinna on useita tilikausia, niistä valitaan automaattisesti ensimmäinen suljettavaksi.</span><span class="sxs-lookup"><span data-stu-id="9f32e-107">If more than one fiscal year is open, the earliest one is automatically selected to be closed.</span></span> <span data-ttu-id="9f32e-108">Näyttöön tulee sanoma, jossa näkyy suljettava kausi ja jossa selostetaan sulkemisen seuraukset.</span><span class="sxs-lookup"><span data-stu-id="9f32e-108">A message displays identifying the year that will close and the consequences of closing the year.</span></span>
3. <span data-ttu-id="9f32e-109">Sulje vuosi valitsemalla **Kyllä** -painike.</span><span class="sxs-lookup"><span data-stu-id="9f32e-109">To close the year, choose the **Yes** button.</span></span>

<span data-ttu-id="9f32e-110">Tilikausi on päätetty, ja **Suljettu**- ja **Pvm lukittu** -kentät on valittu kaikkien kauden jaksojen osalta.</span><span class="sxs-lookup"><span data-stu-id="9f32e-110">The fiscal year is closed, and the **Closed** and **Date Locked** fields for all the periods in the year are selected.</span></span> <span data-ttu-id="9f32e-111">Nyt tilikautta ei voi avata uudestaan, eikä valintamerkkiä voi poistaa **Suljettu**- tai **Pvm lukittu** -kentistä.</span><span class="sxs-lookup"><span data-stu-id="9f32e-111">The fiscal year cannot be opened again and you cannot remove the check mark from the **Closed** or **Date Locked** fields.</span></span>

<span data-ttu-id="9f32e-112">**Huomautus:** Et voi sulkea tilikautta ennen kuin luot uuden.</span><span class="sxs-lookup"><span data-stu-id="9f32e-112">**Note:** You cannot close a fiscal year before you create a new one.</span></span> <span data-ttu-id="9f32e-113">Huomaa, että kun tilikausi on suljettu, et voi muuttaa seuraavan tilikauden aloituspäivämäärää.</span><span class="sxs-lookup"><span data-stu-id="9f32e-113">Notice that when a fiscal year has been closed, you cannot change the starting date of the following fiscal year.</span></span>

<span data-ttu-id="9f32e-114">Vaikka tilikausi on suljettu, voit silti kirjata tilikaudelle KP-tapahtumia.</span><span class="sxs-lookup"><span data-stu-id="9f32e-114">Even though a fiscal year has been closed, you can still post general ledger entries to it.</span></span> <span data-ttu-id="9f32e-115">Kun teet tämän, tapahtumat merkitään kirjatuiksi suljetulle tilikaudelle ja **Edellisen vuoden tapahtuma** -kenttä valitaan.</span><span class="sxs-lookup"><span data-stu-id="9f32e-115">When you do this, the entries will be marked as posted to a closed fiscal year and the **Prior-Year Entry** field will be selected.</span></span>

<span data-ttu-id="9f32e-116">Kun tilikausi on suljettu, tuloslaskelmatilien saldo eli tilikauden tulos tulee siirtää tasetilille.</span><span class="sxs-lookup"><span data-stu-id="9f32e-116">After a fiscal year is closed, you must close the income statement accounts and transfer the year's results to an account in the balance sheet.</span></span> <span data-ttu-id="9f32e-117">Tämä toistetaan aina, kun suljetulle tilikaudelle tehdään kirjauksia.</span><span class="sxs-lookup"><span data-stu-id="9f32e-117">You can repeat this every time that you post to the closed fiscal year.</span></span>

## <a name="see-also"></a><span data-ttu-id="9f32e-118">Katso myös</span><span class="sxs-lookup"><span data-stu-id="9f32e-118">See Also</span></span>
[<span data-ttu-id="9f32e-119">Kirjojen sulkeminen</span><span class="sxs-lookup"><span data-stu-id="9f32e-119">Close Books</span></span>](year-close-books.md)  
[<span data-ttu-id="9f32e-120">Vuositilinpäätöstapahtuman kirjaaminen</span><span class="sxs-lookup"><span data-stu-id="9f32e-120">How to: Post the Year-End Closing Entry</span></span>](year-how-post-year-end-close-entry.md)  
[<span data-ttu-id="9f32e-121">Uuden tilikauden avaaminen</span><span class="sxs-lookup"><span data-stu-id="9f32e-121">How to: Open a New Fiscal Year</span></span>](finance-setup-how-open-new-fiscal-year.md)

