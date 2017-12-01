---
title: "Vuositilinpäätöstapahtuman tarkasteleminen ja kirjaaminen"
description: "Tässä ohjeaiheessa kerrotaan, miten Sulje tuloslaskelma -eräajossa määritetty päiväkirja avataan. Sen jälkeen käsitellään vuositilinpäätöstapahtuman tarkastelua ja kirjaamista."
documentationcenter: 
author: jswymer
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: year closing, close accounting period, close fiscal year, bank account detailed trial balance
ms.date: 03/29/2017
ms.author: jswymer
ms.translationtype: HT
ms.sourcegitcommit: 1dfba8b14019991c95f40ffd5f7fbaed5df414eb
ms.openlocfilehash: 4711b6cac5e853adf8006febcfc7ef008d82d7d4
ms.contentlocale: fi-fi
ms.lasthandoff: 12/01/2017

---
# <a name="how-to-post-the-year-end-closing-entry"></a><span data-ttu-id="0a014-103">Vuositilinpäätöstapahtuman kirjaaminen</span><span class="sxs-lookup"><span data-stu-id="0a014-103">How to: Post the Year-End Closing Entry</span></span>
<span data-ttu-id="0a014-104">Kun olet luonut vuositilinpäätöstapahtuman tai -tapahtumat **Sulje tuloslaskelma** -eräajolla, sinun on avattava eräajossa määrittämäsi päiväkirja sekä tarkistettava ja kirjattava tapahtumat.</span><span class="sxs-lookup"><span data-stu-id="0a014-104">After you use the **Close Income Statement** batch job to generate the year-end closing entry or entries, you must open the journal you specified in the batch job, and then review and post the entries.</span></span>

## <a name="to-post-the-year-end-closing-entry"></a><span data-ttu-id="0a014-105">Kirjaa vuositilinpäätöstapahtuma</span><span class="sxs-lookup"><span data-stu-id="0a014-105">To post the year end closing entry</span></span>
1. <span data-ttu-id="0a014-106">Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, syötä **Yleinen päiväkirja** ja valitse sitten aiheeseen liittyvä linkki.</span><span class="sxs-lookup"><span data-stu-id="0a014-106">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **General Journal**, and then choose the related link.</span></span>
2. <span data-ttu-id="0a014-107">Valitse **Yleinen päiväkirja** -ikkunassa **Erän nimi** kenttää ja valitse erä, joka sisältää tilinpäätöstapahtumat.</span><span class="sxs-lookup"><span data-stu-id="0a014-107">In the **General Journal** window, in the **Batch Name** field, select the batch that contains the closing entries.</span></span>
3. <span data-ttu-id="0a014-108">Tarkista tapahtumat.</span><span class="sxs-lookup"><span data-stu-id="0a014-108">Review the entries.</span></span>
4. <span data-ttu-id="0a014-109">Kirjaa päiväkirja valitsemalla **Kirjaa**-toiminto.</span><span class="sxs-lookup"><span data-stu-id="0a014-109">To post the journal, choose the **Post** action.</span></span>

> [!NOTE]  
>   <span data-ttu-id="0a014-110">Jos havaitaan virhe, näyttöön tulee virhesanoma.</span><span class="sxs-lookup"><span data-stu-id="0a014-110">If an error is detected, an error message is displayed.</span></span> <span data-ttu-id="0a014-111">Jos kirjaus onnistuu, järjestelmä poistaa kirjatut tapahtumat päiväkirjasta.</span><span class="sxs-lookup"><span data-stu-id="0a014-111">If the posting is successful, the posted entries are removed from the journal.</span></span> <span data-ttu-id="0a014-112">Kirjaamisen jälkeen kullekin tuloslaskelmatilille kirjataan tapahtuma, jolloin tilin saldoksi tulee nolla ja vuoden tulos siirretään taseeseen.</span><span class="sxs-lookup"><span data-stu-id="0a014-112">After posting is complete, an entry is posted to each income statement account so that its balance becomes zero and the year's result is transferred to the balance sheet.</span></span>

## <a name="see-also"></a><span data-ttu-id="0a014-113">Katso myös</span><span class="sxs-lookup"><span data-stu-id="0a014-113">See Also</span></span>
[<span data-ttu-id="0a014-114">Kirjanpitojakson päättäminen</span><span class="sxs-lookup"><span data-stu-id="0a014-114">How to: Close Accounting Periods</span></span>](year-close-account-periods.md)  
[<span data-ttu-id="0a014-115">Kirjojen sulkeminen</span><span class="sxs-lookup"><span data-stu-id="0a014-115">Closing Books</span></span>](year-close-books.md)  
[<span data-ttu-id="0a014-116">Tuloslaskelman sulkeminen</span><span class="sxs-lookup"><span data-stu-id="0a014-116">Close Income Statement</span></span>](year-close-income-statement.md)  
<span data-ttu-id="0a014-117">[[!INCLUDE[d365fin](includes/d365fin_md.md)] -ohjelman käyttäminen](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="0a014-117">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>

