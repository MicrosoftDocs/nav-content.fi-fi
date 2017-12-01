---
title: Verkkopankkitoiminta Suomessa
description: "[!INCLUDE[navnow](../../includes/navnow_md.md)] -ohjelman verkkopankkitoimintojen avulla voi käsitellä elektronisia asiakas- ja toimittajamaksuja. Toiminto tukee verkkopankkimaksujen siirron kotimaan maksuja (LM03) ja ulkomaan maksuja (LUM2). Verkkopankkimaksujen vientiä tai tuontia varten on ensin määritettävä pankin viitetiedostot, joissa määritetään maksutiedostojen käsittelytapa."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 07/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 1dfba8b14019991c95f40ffd5f7fbaed5df414eb
ms.openlocfilehash: b4361108125674cbc37be78adee91abca8d64dc2
ms.contentlocale: fi-fi
ms.lasthandoff: 12/01/2017

---
# <a name="electronic-banking-in-finland"></a><span data-ttu-id="1c743-105">Verkkopankkitoiminta Suomessa</span><span class="sxs-lookup"><span data-stu-id="1c743-105">Electronic Banking in Finland</span></span>
<span data-ttu-id="1c743-106">[!INCLUDE[navnow](../../includes/navnow_md.md)] -ohjelman verkkopankkitoimintojen avulla voi käsitellä elektronisia asiakas- ja toimittajamaksuja.</span><span class="sxs-lookup"><span data-stu-id="1c743-106">The [!INCLUDE[navnow](../../includes/navnow_md.md)] electronic banking feature allows you to process electronic customer and vendor payments.</span></span> <span data-ttu-id="1c743-107">Toiminto tukee verkkopankkimaksujen siirron kotimaan maksuja (LM03) ja ulkomaan maksuja (LUM2).</span><span class="sxs-lookup"><span data-stu-id="1c743-107">This feature supports domestic payments (LM03) and foreign payments (LUM2) for transferring electronic bank payments.</span></span> <span data-ttu-id="1c743-108">Verkkopankkimaksujen vientiä tai tuontia varten on ensin määritettävä pankin viitetiedostot, joissa määritetään maksutiedostojen käsittelytapa.</span><span class="sxs-lookup"><span data-stu-id="1c743-108">To export or import electronic payments, you must first set up bank reference files to determine how payment files are processed.</span></span>  

## <a name="customer-payments"></a><span data-ttu-id="1c743-109">Asiakasmaksut</span><span class="sxs-lookup"><span data-stu-id="1c743-109">Customer Payments</span></span>  
<span data-ttu-id="1c743-110">Kotimaan asiakasmaksut voidaan tuoda pankista ja linkittää liittyvään myyntisaatavatapahtumaan viitenumeron avulla.</span><span class="sxs-lookup"><span data-stu-id="1c743-110">Domestic customer payments can be imported from the bank and linked to the associated accounts receivable entry with a reference number.</span></span> <span data-ttu-id="1c743-111">Tämä automaattinen toiminto mahdollistaa saapuvien maksujen linkittämisen suoraan avoimiin myyntisaataviin ilman manuaalisen käsittelyn aiheuttamaa viivettä.</span><span class="sxs-lookup"><span data-stu-id="1c743-111">This type of automation enables incoming payments to be linked directly to open receivables without a delay in manual processing.</span></span> <span data-ttu-id="1c743-112">Seuraavissa vaiheissa kuvataan, miten asiakasmaksut tuodaan pankista tiedostoon ja miten nämä maksut linkitetään laskuihin viitenumeroiden avulla.</span><span class="sxs-lookup"><span data-stu-id="1c743-112">The following steps explain how to import customer payments into a file from the bank and how to link these payments to invoices through their reference numbers.</span></span>  

- <span data-ttu-id="1c743-113">Luo myyntilasku ja liitä laskuun yksilöivä viitenumero.</span><span class="sxs-lookup"><span data-stu-id="1c743-113">Create a sales invoice and assign a unique reference number to the invoice.</span></span> <span data-ttu-id="1c743-114">Asiakas käyttää tätä viitenumeroa maksaessaan laskun.</span><span class="sxs-lookup"><span data-stu-id="1c743-114">This reference number will be used by the customer when paying the invoice.</span></span>  

- <span data-ttu-id="1c743-115">Tuo asiakasmaksut sisältävät maksutiedostot kassapäiväkirjaan.</span><span class="sxs-lookup"><span data-stu-id="1c743-115">Import the payment files that contain customer payments into the cash receipt journal.</span></span> <span data-ttu-id="1c743-116">Nämä tiedostot sisältävät pankilta saadut viitenumerot.</span><span class="sxs-lookup"><span data-stu-id="1c743-116">These files contain the reference numbers received from the bank.</span></span> <span data-ttu-id="1c743-117">Maksut linkitetään myyntisaatavatapahtumaan viitenumeroiden avulla.</span><span class="sxs-lookup"><span data-stu-id="1c743-117">The payments are linked to the accounts receivable entry through their reference numbers.</span></span>  

- <span data-ttu-id="1c743-118">Kirjaa tiedot kassapäiväkirjaan ja sulje avoimet myyntisaatavatapahtumat tiedoston kohdistettujen maksujen avulla.</span><span class="sxs-lookup"><span data-stu-id="1c743-118">Post the cash receipt journal and close the open accounts receivable entries with the applied payments from the file.</span></span>  

## <a name="reference-number"></a><span data-ttu-id="1c743-119">Viitenumero</span><span class="sxs-lookup"><span data-stu-id="1c743-119">Reference Number</span></span>  
<span data-ttu-id="1c743-120">Viitenumero luodaan automaattisesti, kun lasku kirjataan tai tilaus kirjataan laskutettavaksi.</span><span class="sxs-lookup"><span data-stu-id="1c743-120">A reference number is automatically created when an invoice is posted or when an order is posted for invoicing.</span></span> <span data-ttu-id="1c743-121">Myyntipäiväkirjan tapahtuman viitenumeron voi kuitenkin antaa myös manuaalisesti.</span><span class="sxs-lookup"><span data-stu-id="1c743-121">However, you can enter a reference number manually on a sales journal transaction.</span></span> <span data-ttu-id="1c743-122">Tämä viitenumero ei perustu **Myyntien asetukset** -ikkunan viitenumeroasetuksiin.</span><span class="sxs-lookup"><span data-stu-id="1c743-122">This reference number is not based on the reference number options in the **Sales & Receivables Setup** window.</span></span> <span data-ttu-id="1c743-123">Jos syötät myyntipäiväkirjaan viitenumeron, vain viitenumeron oikeellisuus tarkistetaan.</span><span class="sxs-lookup"><span data-stu-id="1c743-123">If you enter a reference number for the sales journal, only the validity of the reference number is checked.</span></span>  

## <a name="vendor-payments"></a><span data-ttu-id="1c743-124">Toimittajamaksut</span><span class="sxs-lookup"><span data-stu-id="1c743-124">Vendor Payments</span></span>  
<span data-ttu-id="1c743-125">Voit lähettää toimittajille verkkopankkimaksuja viemällä kotimaan tai ulkomaan toimittajamaksut pankille lähetettävään siirtotiedostoon.</span><span class="sxs-lookup"><span data-stu-id="1c743-125">To send electronic bank payments to vendors, you can export domestic or foreign vendor payments into a transfer file that can be sent to the bank.</span></span> <span data-ttu-id="1c743-126">Seuraavissa vaiheissa kuvataan, miten toimittajamaksut viedään.</span><span class="sxs-lookup"><span data-stu-id="1c743-126">The following steps show how to export vendor payments.</span></span>  

- <span data-ttu-id="1c743-127">Valitse **Lähetettävät pankkimaksut** -ikkunassa toimittajat, joille maksutiedostot luodaan.</span><span class="sxs-lookup"><span data-stu-id="1c743-127">Use the **Bank Payments to Send** window to select the vendors for which you want to create payment files.</span></span>  
- <span data-ttu-id="1c743-128">Syötä maksutiedot jokaiselle maksupäiväkirjan tapahtumalle tai käytä **Ehdota toimittajamaksuja** -toimintoa, joka luo ehdotetut maksut.</span><span class="sxs-lookup"><span data-stu-id="1c743-128">Enter payment information for each transaction in the payment journal or use **Suggest Vendor Payments** to create suggested payments.</span></span>  
- <span data-ttu-id="1c743-129">Luo ja esikatsele maksuraportti.</span><span class="sxs-lookup"><span data-stu-id="1c743-129">Generate and preview the payment report.</span></span>  
- <span data-ttu-id="1c743-130">Luo siirtotiedosto kotimaan tai ulkomaan toimittajamaksuille.</span><span class="sxs-lookup"><span data-stu-id="1c743-130">Create a transfer file for domestic or foreign vendor payments.</span></span>  
- <span data-ttu-id="1c743-131">Lähetä maksun siirtotiedosto pankkiin.</span><span class="sxs-lookup"><span data-stu-id="1c743-131">Send the payment transfer file to the bank.</span></span>  

## <a name="see-also"></a><span data-ttu-id="1c743-132">Katso myös</span><span class="sxs-lookup"><span data-stu-id="1c743-132">See Also</span></span>  
 <span data-ttu-id="1c743-133">[Suomen paikalliset toiminnot](finland-local-functionality.md) </span><span class="sxs-lookup"><span data-stu-id="1c743-133">[Finland Local Functionality](finland-local-functionality.md) </span></span>  
 <span data-ttu-id="1c743-134">[Toimintaohje: Pankin viitetiedostojen määrittäminen](how-to-set-up-bank-reference-files.md) </span><span class="sxs-lookup"><span data-stu-id="1c743-134">[How to: Set Up Bank Reference Files](how-to-set-up-bank-reference-files.md) </span></span>  
 <span data-ttu-id="1c743-135">[Toimintaohje: Maksutiedostojen luominen](how-to-generate-payment-files.md) </span><span class="sxs-lookup"><span data-stu-id="1c743-135">[How to: Generate Payment Files](how-to-generate-payment-files.md) </span></span>  
 [<span data-ttu-id="1c743-136">Toimintaohje: Maksualennusten ohittaminen</span><span class="sxs-lookup"><span data-stu-id="1c743-136">How to: Disregard Payment Discounts</span></span>](how-to-disregard-payment-discounts.md)   

