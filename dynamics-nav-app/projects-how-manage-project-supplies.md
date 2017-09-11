---
title: 'Toimintaohje: Projektin tarvikkeiden hallinta'
author: SorenGP
ms.custom: na
ms.date: 11/01/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 00b9ed8480f6b5ab9265beb0fe2dc0060b1c3192
ms.contentlocale: fi-fi
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-manage-job-supplies"></a><span data-ttu-id="d158c-102">Toimintaohje: Projektin tarvikkeiden hallinta</span><span class="sxs-lookup"><span data-stu-id="d158c-102">How to: Manage Job Supplies</span></span>
<span data-ttu-id="d158c-103">Projektin nimikkeiden, palveluiden ja kulujen tarvikkeiden hallinta on olennainen ja tärkeä osa kaikkia projekteja.</span><span class="sxs-lookup"><span data-stu-id="d158c-103">Managing project supplies of items, services, and expenses is an integral and critical aspect of the execution of all jobs.</span></span> <span data-ttu-id="d158c-104">Voit käyttää varastomääriä tai tehdä projektikohtaisia ostoja ostotilausten tai ostolaskujen avulla.</span><span class="sxs-lookup"><span data-stu-id="d158c-104">You can use inventory quantities or make job-specific purchases using purchase orders or purchase invoices.</span></span> <span data-ttu-id="d158c-105">Oletetaan esimerkiksi, että tietokoneen huoltoprojektia varten tarvitaan uusi levy.</span><span class="sxs-lookup"><span data-stu-id="d158c-105">For example, a service job on a computer requires a new disk.</span></span> <span data-ttu-id="d158c-106">Tällöin luot ostolaskun uuden levyn ostamista varten ja kirjaat projektin, jossa sitä käytetään.</span><span class="sxs-lookup"><span data-stu-id="d158c-106">You create a purchase invoice to buy a new disk and record the job that it will be used on.</span></span>

<span data-ttu-id="d158c-107">Jos ostoprosessi ei edellytä, että fyysinen tapahtuma kirjataan erikseen, osto voidaan käsitellä vain ostolaskussa tai **Projektin KP-päiväkirja** -ikkunassa.</span><span class="sxs-lookup"><span data-stu-id="d158c-107">If the purchase process does not require that the physical transaction be recorded separately, then a purchase may be processed in the **Job G/L Journal** window.</span></span> <span data-ttu-id="d158c-108">Lisätietoja on kohdassa [Toimintaohje: Projektien käytön kirjaaminen](projects-how-record-job-usage.md).</span><span class="sxs-lookup"><span data-stu-id="d158c-108">For more information, see [How to: Record Usage for Jobs](projects-how-record-job-usage.md).</span></span>

## <a name="to-purchase-items-or-services-for-a-job"></a><span data-ttu-id="d158c-109">Nimikkeiden tai palveluiden ostaminen projektille</span><span class="sxs-lookup"><span data-stu-id="d158c-109">To purchase items or services for a job</span></span>
<span data-ttu-id="d158c-110">Seuraavassa kerrotaan, miten projektille ostetaan tuotteita ostolaskun avulla.</span><span class="sxs-lookup"><span data-stu-id="d158c-110">The following procedure shows how to use a purchase invoice to purchase products for a job.</span></span> <span data-ttu-id="d158c-111">Samat vaiheet toimivat myös silloin, kun käytetään ostotilausta.</span><span class="sxs-lookup"><span data-stu-id="d158c-111">The same steps apply when using a purchase order.</span></span>  

1. <span data-ttu-id="d158c-112">Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Ostolaskut** ja valitse sitten aiheeseen liittyvä linkki.</span><span class="sxs-lookup"><span data-stu-id="d158c-112">In the top right corner, choose the **Search for Page or Report** icon, enter **Purchase Invoices**, and then choose the related link.</span></span>  
2. <span data-ttu-id="d158c-113">Valitse **Uusi**-toiminto ja täytä tarvittavat kentät.</span><span class="sxs-lookup"><span data-stu-id="d158c-113">Choose the **New** action and fill in the fields as necessary.</span></span> <span data-ttu-id="d158c-114">Lisätietoja on kohdassa [Toimintaohje: Ostojen kirjaaminen](purchasing-how-record-purchases.md).</span><span class="sxs-lookup"><span data-stu-id="d158c-114">For more information, see [How to: Record Purchases](purchasing-how-record-purchases.md).</span></span>
3. <span data-ttu-id="d158c-115">Valitse **Projektin nro**-</span><span class="sxs-lookup"><span data-stu-id="d158c-115">In the **Job No.**</span></span> <span data-ttu-id="d158c-116">ja **Projektitehtävän nro**</span><span class="sxs-lookup"><span data-stu-id="d158c-116">and **Job Task No.**</span></span> <span data-ttu-id="d158c-117">-kentässä sen projektin tiedot, jolle haluat ostaa nimikkeitä tai palveluita.</span><span class="sxs-lookup"><span data-stu-id="d158c-117">fields, select the information of the job that you want to purchase items or services for.</span></span>  

    <span data-ttu-id="d158c-118">**Projektin rivityyppi** -kentässä valitsemasi arvo määrittää, luodaanko suunnittelurivi nimikkeen käytön kirjaamisen yhteydessä.</span><span class="sxs-lookup"><span data-stu-id="d158c-118">The value that you select in the **Job Line Type** field defines whether a planning line is created when you post the usage of the item.</span></span> <span data-ttu-id="d158c-119">Jos kentän arvo on **Laskutettava**, ne projektin suunnittelurivit, jotka ovat valmiita asiakkaalta laskutettaviksi, luodaan.</span><span class="sxs-lookup"><span data-stu-id="d158c-119">If the field contains **Billable**, then job planning lines that are ready to be invoiced to the customer are created.</span></span> <span data-ttu-id="d158c-120">Lisätietoja on kohdassa [Toimintaohje: Projektien laskuttaminen](projects-how-invoice-jobs.md).</span><span class="sxs-lookup"><span data-stu-id="d158c-120">For more information, see [How to: Invoice Jobs](projects-how-invoice-jobs.md).</span></span>

4. <span data-ttu-id="d158c-121">Valitse **Kirjaa**-toiminto.</span><span class="sxs-lookup"><span data-stu-id="d158c-121">Choose the **Post** action.</span></span>

## <a name="to-view-the-value-of-purchases-for-a-job"></a><span data-ttu-id="d158c-122">Projektin ostojen arvon tarkasteleminen</span><span class="sxs-lookup"><span data-stu-id="d158c-122">To view the value of purchases for a job</span></span>  

1. <span data-ttu-id="d158c-123">Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Projektit** ja valitse sitten aiheeseen liittyvä linkki.</span><span class="sxs-lookup"><span data-stu-id="d158c-123">In the top right corner, choose the **Search for Page or Report** icon, enter **Jobs**, and then choose the related link.</span></span>
2. <span data-ttu-id="d158c-124">Avaa asianmukainen projektikortti.</span><span class="sxs-lookup"><span data-stu-id="d158c-124">Open a relevant job card.</span></span>

    <span data-ttu-id="d158c-125">**Tehtävät**-pikavälilehden **Avoimet tilaukset** -kentässä näkyy projektin tehtävärivin ostoasiakirjojen varastonimikkeiden ja palveluiden avoin summa paikallisena valuuttana.</span><span class="sxs-lookup"><span data-stu-id="d158c-125">On the **Tasks** FastTab, the **Outstanding Orders** field shows the total outstanding amount, in local currency, of inventory items and services on purchase documents for the job task line.</span></span>  

    <span data-ttu-id="d158c-126">**Ei laskut. vast.ottojen summa** -kentässä näkyy ostoasiakirjoja vastaan toimitettujen, mutta vielä laskuttamattomien, nimikkeiden arvo.</span><span class="sxs-lookup"><span data-stu-id="d158c-126">The **Amt. Rec. Not Invoiced** field shows the value of items delivered on purchase documents, but not yet invoiced.</span></span>  

3. <span data-ttu-id="d158c-127">Valitse jompikumpi kentistä ja avaa **Ostorivit**-ikkuna, jossa voit tarkastella liittyvien ostoasiakirjarivien tietoja sekä tietoa siitä, mitkä nimikkeet tai palvelut on vastaanotettu.</span><span class="sxs-lookup"><span data-stu-id="d158c-127">Choose either of the fields to open the **Purchase Lines** window where you can review information about the related purchase document lines, including which items or services have been received.</span></span>

## <a name="to-post-a-job-related-expense"></a><span data-ttu-id="d158c-128">Projektiin liittyvän kulun kirjaaminen</span><span class="sxs-lookup"><span data-stu-id="d158c-128">To post a job-related expense</span></span>  
<span data-ttu-id="d158c-129">Jos sisällytät satunnaisen tai kertaluontoisen projektin kulut, voit käyttää **Projektin KP-päiväkirja** -ikkunaa ja kirjata ne suoraan asianmukaiseen projektitiliin.</span><span class="sxs-lookup"><span data-stu-id="d158c-129">If you incur extraordinary or one-time job expenses, you can use the **Job G/L Journal** window to post them directly to the relevant job account.</span></span>

1. <span data-ttu-id="d158c-130">Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Projektin KP-päiväkirjat** ja valitse sitten aiheeseen liittyvä linkki.</span><span class="sxs-lookup"><span data-stu-id="d158c-130">In the top right corner, choose the **Search for Page or Report** icon, enter **Job G/L Journals**, and then choose the related link.</span></span>  
2. <span data-ttu-id="d158c-131">Luo uusi rivi ja syötä kulua koskevat tiedot, kuten esimerkiksi **Projektinro**-</span><span class="sxs-lookup"><span data-stu-id="d158c-131">Create a new line and enter information about the expense, including information in the **Job No.**</span></span> <span data-ttu-id="d158c-132">ja **Projektitehtävän nro** -kentän tiedot.</span><span class="sxs-lookup"><span data-stu-id="d158c-132">and **Job Task No** fields.</span></span>  
3. <span data-ttu-id="d158c-133">Kun päiväkirja on valmis, valitse **Kirjaa**-toiminto.</span><span class="sxs-lookup"><span data-stu-id="d158c-133">When the journal is complete, choose the **Post** action.</span></span>


## <a name="see-also"></a><span data-ttu-id="d158c-134">Katso myös</span><span class="sxs-lookup"><span data-stu-id="d158c-134">See Also</span></span>
[<span data-ttu-id="d158c-135">Projektien hallinta</span><span class="sxs-lookup"><span data-stu-id="d158c-135">Manage Projects</span></span>](projects-manage-projects.md)  
[<span data-ttu-id="d158c-136">Rahoitus</span><span class="sxs-lookup"><span data-stu-id="d158c-136">Finance</span></span>](finance-setup.md)  
<span data-ttu-id="d158c-137">[Ostojen hallinta](purchasing-manage-purchasing.md)       </span><span class="sxs-lookup"><span data-stu-id="d158c-137">[Manage Purchasing](purchasing-manage-purchasing.md)       </span></span>  
<span data-ttu-id="d158c-138">[Myynnin hallinta](sales-manage-sales.md)    </span><span class="sxs-lookup"><span data-stu-id="d158c-138">[Manage Sales](sales-manage-sales.md)    </span></span>  
[<span data-ttu-id="d158c-139">Dynamics NAV -ohjelman käyttäminen</span><span class="sxs-lookup"><span data-stu-id="d158c-139">Work With Dynamics NAV</span></span>](ui-work-product.md)  

