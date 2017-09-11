---
title: "Kohdistustunnusten käyttäminen yleisissä päiväkirjoissa"
author: edupont04
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 6b60b1344a1e18ad91863046110df880f75f7c04
ms.openlocfilehash: ca21d9d129dbc98d75371d1b2b7a0ffad4aa2848
ms.contentlocale: fi-fi
ms.lasthandoff: 07/19/2017

---

#  <a name="how-to-use-allocation-keys-in-general-journals"></a><span data-ttu-id="81659-102">Kohdistustunnusten käyttäminen yleisissä päiväkirjoissa</span><span class="sxs-lookup"><span data-stu-id="81659-102">How to: Use Allocation Keys in General Journals</span></span>
<span data-ttu-id="81659-103">Voit kohdistaa yleisen päiväkirjan tapahtuman useille eri tileille päiväkirjan kirjaamisen yhteydessä.</span><span class="sxs-lookup"><span data-stu-id="81659-103">You can allocate an entry in a general journal to several different accounts when you post the journal.</span></span> <span data-ttu-id="81659-104">Kohdistus voidaan tehdä määrän, prosentin tai summan mukaan.</span><span class="sxs-lookup"><span data-stu-id="81659-104">The allocation can be made by quantity, percentage, or amount.</span></span>

## <a name="to-set-up-allocation-keys"></a><span data-ttu-id="81659-105">Kohdistustunnusten määrittäminen</span><span class="sxs-lookup"><span data-stu-id="81659-105">To set up allocation keys</span></span> 
1. <span data-ttu-id="81659-106">Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Toistuva yleinen päiväkirja** ja valitse sitten aiheeseen liittyvä linkki.</span><span class="sxs-lookup"><span data-stu-id="81659-106">In the top right corner, choose the **Search for Page or Report** icon, enter **Recurring General Journal**, and then choose the related link.</span></span>
2. <span data-ttu-id="81659-107">Valitse **Erän nimi** -kenttä, kun haluat avata **Yleisen päiväkirjan erät** -ikkunan.</span><span class="sxs-lookup"><span data-stu-id="81659-107">Choose the **Batch Name** field to open the **General Journal Batches** window.</span></span>
3. <span data-ttu-id="81659-108">Voit muokata luettelon olemassa olevan erän kohdistuksia tai luoda uuden erän ja kohdistukset.</span><span class="sxs-lookup"><span data-stu-id="81659-108">You can either modify allocations on an existing batch in the list or create a new batch with allocations.</span></span>
  * <span data-ttu-id="81659-109">Luo uusi erä valitsemalla **Uusi**-toiminto ja siirtymällä seuraavaan vaiheeseen.</span><span class="sxs-lookup"><span data-stu-id="81659-109">To create a new batch, choose the **New** action, and go to the next step.</span></span>
  * <span data-ttu-id="81659-110">Voit muuttaa olemassa olevan päiväkirjan kohdistuksia valitsemalla päiväkirjan ja siirtymällä vaiheeseen 7.</span><span class="sxs-lookup"><span data-stu-id="81659-110">To change the allocations of an existing journal, select the journal and go to step 7.</span></span>    
4. <span data-ttu-id="81659-111">Syötä **Nimi**-kenttään erän nimi, esimerkiksi SIIVOUS.</span><span class="sxs-lookup"><span data-stu-id="81659-111">In the **Name** field, enter a name for the batch, such as CLEANING.</span></span> <span data-ttu-id="81659-112">Syötä **Kuvaus**-kenttään kuvaus, esimerkiksi Siivouskulujen päiväkirja.</span><span class="sxs-lookup"><span data-stu-id="81659-112">In the **Description** field, enter a description, such as Cleaning Expenses Journal.</span></span>
5. <span data-ttu-id="81659-113">Kun olet valmis, sulje ikkuna.</span><span class="sxs-lookup"><span data-stu-id="81659-113">When you are done, close the window.</span></span> <span data-ttu-id="81659-114">Esiin tulee uusi tyhjä toistuva kirjaus.</span><span class="sxs-lookup"><span data-stu-id="81659-114">A new, empty recurring journal opens.</span></span> 
6. <span data-ttu-id="81659-115">Täytä rivin kentät.</span><span class="sxs-lookup"><span data-stu-id="81659-115">Fill in the fields in the line.</span></span>
7. <span data-ttu-id="81659-116">Valitse **Kohdistukset**-toiminto.</span><span class="sxs-lookup"><span data-stu-id="81659-116">Choose the **Allocations** action.</span></span> 
8. <span data-ttu-id="81659-117">Lisää rivi jokaista kohdistusta varten.</span><span class="sxs-lookup"><span data-stu-id="81659-117">Add a line for each allocation.</span></span> <span data-ttu-id="81659-118">Sinun täytyy täyttää jokin seuraavista kentistä: **Kohdistus- %**, **Kohdistettava määrä** tai **Summa**.</span><span class="sxs-lookup"><span data-stu-id="81659-118">You must fill in either the **Allocation %**, **Allocation Quantity**, or **Amount** field.</span></span> <span data-ttu-id="81659-119">Sinun tulee täyttää myös **Tilinro**-kenttä</span><span class="sxs-lookup"><span data-stu-id="81659-119">You must also fill in the **Account No.**</span></span> <span data-ttu-id="81659-120">ja, mikäli kohdistat tapahtuman globaaleille dimensioille, globaalin dimension kentät.</span><span class="sxs-lookup"><span data-stu-id="81659-120">field and, if you are allocating the transaction among global dimensions, the global dimension fields.</span></span>
9. <span data-ttu-id="81659-121">Jos syötät riville prosentin, ohjelma laskee **Summa**-kentän arvon automaattisesti.</span><span class="sxs-lookup"><span data-stu-id="81659-121">If you enter a percentage on a line, the amount in the **Amount** field is calculated automatically.</span></span> <span data-ttu-id="81659-122">Näillä summilla on vastakkainen merkki kuin kokonaissummalla toistuvan kirjauksen **Summa**-kentässä.</span><span class="sxs-lookup"><span data-stu-id="81659-122">These amounts have the opposite sign from the total amount in the **Amount** field in the recurring journal.</span></span>
10. <span data-ttu-id="81659-123">Kun olet syöttänyt kohdistusrivit, valitse **OK** palataksesi takaisin **Toistuva yleinen päiväkirja** -ikkunaan.</span><span class="sxs-lookup"><span data-stu-id="81659-123">After entering the allocations lines, choose **OK** to return to the **Recurring General Journal** window.</span></span> <span data-ttu-id="81659-124">**Kohdistettu summa (USD)** -kenttä on täytetty ja vastaa **Summa** -kenttää.</span><span class="sxs-lookup"><span data-stu-id="81659-124">The **Allocated Amt. (USD)** field is filled in and matches the **Amount** field.</span></span>
11. <span data-ttu-id="81659-125">Kirjaa päiväkirja.</span><span class="sxs-lookup"><span data-stu-id="81659-125">Post the journal.</span></span>

## <a name="to-change-an-allocation-key-that-has-already-been-set-up"></a><span data-ttu-id="81659-126">Aiemmin määritetyn kohdistusavaimen muuttaminen</span><span class="sxs-lookup"><span data-stu-id="81659-126">To change an allocation key that has already been set up</span></span>
1. <span data-ttu-id="81659-127">Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Toistuva yleinen päiväkirja** ja valitse sitten aiheeseen liittyvä linkki.</span><span class="sxs-lookup"><span data-stu-id="81659-127">In the top right corner, choose the **Search for Page or Report** icon, enter **Recurring General Journal**, and then choose the related link.</span></span>
2. <span data-ttu-id="81659-128">Valitse **Toistuva yleinen päiväkirja** -ikkunassa päiväkirja, jossa kohdistus on.</span><span class="sxs-lookup"><span data-stu-id="81659-128">In the **Recurring General Journal** window, select the journal with the allocation.</span></span>
3. <span data-ttu-id="81659-129">Valitse kohdistuksen rivi ja valitse sitten **Kohdistukset**-toiminto.</span><span class="sxs-lookup"><span data-stu-id="81659-129">Choose the line with the allocation, and then choose **Allocations** action.</span></span>
4. <span data-ttu-id="81659-130">Muuta asianmukaiset kentät ja sulje ikkuna.</span><span class="sxs-lookup"><span data-stu-id="81659-130">Change the relevant fields, and close the window.</span></span>

## <a name="see-also"></a><span data-ttu-id="81659-131">Katso myös</span><span class="sxs-lookup"><span data-stu-id="81659-131">See Also</span></span>
[<span data-ttu-id="81659-132">Yleisten päiväkirjojen käyttäminen</span><span class="sxs-lookup"><span data-stu-id="81659-132">Work With General Journals</span></span>](ui-work-general-journals.md)  
[<span data-ttu-id="81659-133">Asiakirjojen ja päiväkirjojen kirjaaminen</span><span class="sxs-lookup"><span data-stu-id="81659-133">Post Documents and Journals</span></span>](ui-post-documents-journals.md)




