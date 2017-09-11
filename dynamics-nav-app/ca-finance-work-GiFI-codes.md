---
title: "Toimintaohje: Kanadan GIFI-koodien käyttäminen"
author: SorenGP
ms.custom: na
ms.date: 09/21/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 695bca0a6836c47610210b759ae48af27484761f
ms.contentlocale: fi-fi
ms.lasthandoff: 06/26/2017

---

#<a name="how-to-work-with-gifi-codes-in-canada"></a><span data-ttu-id="1a2fe-102">Toimintaohje: Kanadan GIFI-koodien käyttäminen</span><span class="sxs-lookup"><span data-stu-id="1a2fe-102">How to: Work With GIFI Codes in Canada</span></span>
<span data-ttu-id="1a2fe-103">Taloustiedot voivat sisältää kirjanpitotilejä, raportteja, tuloslaskelmia, taseita ja jakamattoman voiton tiliotteita.</span><span class="sxs-lookup"><span data-stu-id="1a2fe-103">Fiscal information can include general ledger accounts, reports, income statements, balance sheets, and statements of retained earnings.</span></span> <span data-ttu-id="1a2fe-104">Taloustiedot luokitellaan koodien avulla.</span><span class="sxs-lookup"><span data-stu-id="1a2fe-104">Fiscal information is classified using codes.</span></span> <span data-ttu-id="1a2fe-105">Viranomaiset käyttävät koodeja tietojen käsittelemiseen, sähköiseen arkistoimiseen ja verotietojen sähköiseen tarkistamiseen.</span><span class="sxs-lookup"><span data-stu-id="1a2fe-105">The use of codes helps the government to process information, prepare for electronic filing, and validate tax information electronically.</span></span> <span data-ttu-id="1a2fe-106">Koodit auttavat myös tilastotietojen tehokkaassa käsittelyssä, koska taloustiedot ovat helpommin käytettävissä.</span><span class="sxs-lookup"><span data-stu-id="1a2fe-106">The use of codes also helps statistical organizations to work more efficiently, as financial information is more readily available.</span></span> <span data-ttu-id="1a2fe-107">Lisätietoja on [Kanadan CRA:n (Canada Revenue Agency) verkkosivustossa](http://www.cra-arc.gc.ca/).</span><span class="sxs-lookup"><span data-stu-id="1a2fe-107">For more information, see the [Canada Revenue Agency website](http://www.cra-arc.gc.ca/).</span></span>

<span data-ttu-id="1a2fe-108">Kanadan CRA käyttää tilinpäätösten kirjanpitotietojen yleisindeksikoodeja eli GIFI (General Index of Financial Information) -koodeja talous- ja verotietojen sähköisessä keräämiseen, tarkistamiseen ja käsittelyyn.</span><span class="sxs-lookup"><span data-stu-id="1a2fe-108">The Canada Revenue Agency uses General Index of Financial Information (GIFI) codes to collect, validate, and process financial and tax information electronically.</span></span> <span data-ttu-id="1a2fe-109">GIFI-koodit kannattaa liittää vain kirjaustileihin niin, että verojen valmistelussa käytettävä ohjelmisto suorittaa summauksen.</span><span class="sxs-lookup"><span data-stu-id="1a2fe-109">It is a best practice to assign GIFI codes only to posting accounts, so that all totaling is done by your tax preparation software.</span></span>

<span data-ttu-id="1a2fe-110">Kun tili on liitetty GIFI-koodiin, kyseistä koodia käytetään verotoimiston raporteissa.</span><span class="sxs-lookup"><span data-stu-id="1a2fe-110">When an account is associated with a GIFI code, it is reported to the revenue agency under that code.</span></span> <span data-ttu-id="1a2fe-111">Sama GIFI-koodi voi olla useilla tileillä, mutta tilillä voi olla vain yksi GIFI-koodi.</span><span class="sxs-lookup"><span data-stu-id="1a2fe-111">Multiple accounts can all have the same GIFI code, but each account can have only one GIFI code.</span></span>

<span data-ttu-id="1a2fe-112">Saldotiedot voidaan viedä GIFI-koodin avulla, ja viety tiedosto voidaan tallentaa Exceliin. Tämä on hyödyllistä silloin, kun tietoja siirretään verojen valmistelussa käytettävään ohjelmistoon.</span><span class="sxs-lookup"><span data-stu-id="1a2fe-112">You can export balance information by GIFI code and save the exported file in Excel, which is useful for transferring information to your tax preparation software.</span></span>

## <a name="to-set-up-gifi-codes"></a><span data-ttu-id="1a2fe-113">GIFI-koodien määrittäminen</span><span class="sxs-lookup"><span data-stu-id="1a2fe-113">To set up GIFI codes</span></span>
<span data-ttu-id="1a2fe-114">Dynamics NAV -ohjelmassa GIFI-koodit on määritettävä kirjanpitotileille, raporteille, taseille, tuloslaskelmille ja jakamattoman voiton tiliotteille.</span><span class="sxs-lookup"><span data-stu-id="1a2fe-114">In Dynamics NAV, you must set up GIFI codes for general ledger accounts, reports, balance sheets, income sheets, and statements of retained earnings.</span></span>

1. <span data-ttu-id="1a2fe-115">Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **GIFI-koodit** ja valitse sitten aiheeseen liittyvä linkki.</span><span class="sxs-lookup"><span data-stu-id="1a2fe-115">In the top right corner, choose the **Search for Page or Report** icon, enter **GIFI Codes**, and then choose the related link.</span></span>
2. <span data-ttu-id="1a2fe-116">Valitse **GIFI-koodit**-ikkunassa **Uusi**-toiminto.</span><span class="sxs-lookup"><span data-stu-id="1a2fe-116">In the **GIFI Codes** window, choose the **New** action.</span></span>
3. <span data-ttu-id="1a2fe-117">Määritä GIFI-koodit täyttämällä kentät.</span><span class="sxs-lookup"><span data-stu-id="1a2fe-117">Set up GIFI codes by filling the fields.</span></span> <span data-ttu-id="1a2fe-118">Lue kentän lyhyt kuvaus valitsemalla kenttä tai siirry lisätietoihin valitsemalla linkki.</span><span class="sxs-lookup"><span data-stu-id="1a2fe-118">Choose a field to read a short description of the field or link to more information.</span></span>

## <a name="to-associate-gifi-codes-with-gl-accounts"></a><span data-ttu-id="1a2fe-119">GIFI-koodien liittäminen kirjanpitotileihin</span><span class="sxs-lookup"><span data-stu-id="1a2fe-119">To associate GIFI codes with G/L accounts</span></span>
<span data-ttu-id="1a2fe-120">Voit raportoida taloustiedot GIFI-koodien mukaan, kun kukin GIFI-koodi on liitetty tilikartan asianmukaiseen tiliin.</span><span class="sxs-lookup"><span data-stu-id="1a2fe-120">To report financial information by GIFI code, each GIFI code must be associated with the appropriate accounts in the chart of accounts.</span></span>

1. <span data-ttu-id="1a2fe-121">Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Tilikartta** ja valitse sitten aiheeseen liittyvä linkki.</span><span class="sxs-lookup"><span data-stu-id="1a2fe-121">In the top right corner, choose the **Search for Page or Report** icon, enter **Chart of Accounts**, and then choose the related link.</span></span>
2. <span data-ttu-id="1a2fe-122">Valitse asiaankuuluva kirjanpitotili ja valitse sitten **Muokkaa**-toiminto.</span><span class="sxs-lookup"><span data-stu-id="1a2fe-122">Select a relevant general ledger account, and then choose the **Edit** action.</span></span>
3. <span data-ttu-id="1a2fe-123">Valitse **Kustannuslaskenta**-pikavälilehden **GIFI-koodi**-kenttään asiaankuuluva GIFI-koodi.</span><span class="sxs-lookup"><span data-stu-id="1a2fe-123">On the **Cost Accounting** FastTab, in the **GIFI Code** field, select an appropriate GIFI code.</span></span>

## <a name="to-view-account-balances-using-the-gifi-code-report"></a><span data-ttu-id="1a2fe-124">Tilien saldojen tarkasteleminen GIFI-koodiraportin avulla</span><span class="sxs-lookup"><span data-stu-id="1a2fe-124">To view account balances using the GIFI code report</span></span>
<span data-ttu-id="1a2fe-125">Voit tarkastella tilien saldoja GIFI-koodin mukaan **Tilien saldot GIFI-koodin mukaan** -raportin avulla.</span><span class="sxs-lookup"><span data-stu-id="1a2fe-125">You can review your account balances by GIFI code by using the **Account Balances by GIFI Code** report.</span></span>

1. <span data-ttu-id="1a2fe-126">Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Tilien saldot GIFI-koodin mukaan** ja valitse sitten aiheeseen liittyvä linkki.</span><span class="sxs-lookup"><span data-stu-id="1a2fe-126">In the top right corner, choose the **Search for Page or Report** icon, enter **Account Balances by GIFI Code**, and then choose the related link.</span></span>
2. <span data-ttu-id="1a2fe-127">Määritä raporttiin sisällytettävät tiedot täyttämällä kentät.</span><span class="sxs-lookup"><span data-stu-id="1a2fe-127">Specify what to include in the report by filling the fields.</span></span> <span data-ttu-id="1a2fe-128">Lue kentän lyhyt kuvaus valitsemalla kenttä tai siirry lisätietoihin valitsemalla linkki.</span><span class="sxs-lookup"><span data-stu-id="1a2fe-128">Choose a field to read a short description of the field or link to more information.</span></span>
3. <span data-ttu-id="1a2fe-129">Valitse **Tulosta**- tai **Esikatsele**-painike.</span><span class="sxs-lookup"><span data-stu-id="1a2fe-129">Choose the **Print** or the **Preview** button.</span></span>

## <a name="to-export-balance-information-using-gifi-codes"></a><span data-ttu-id="1a2fe-130">Saldotietojen vieminen GIFI-koodien avulla</span><span class="sxs-lookup"><span data-stu-id="1a2fe-130">To export balance information using GIFI codes</span></span>
<span data-ttu-id="1a2fe-131">Voit viedä saldotiedot GIFI-koodien avulla ja tallentaa viedyn tiedoston Excelissä.</span><span class="sxs-lookup"><span data-stu-id="1a2fe-131">You can export balance information using GIFI codes and save the exported file in Excel.</span></span> <span data-ttu-id="1a2fe-132">Voit muokata tiedostoa tai tallentaa tai poistaa sen.</span><span class="sxs-lookup"><span data-stu-id="1a2fe-132">You can modify, save, or delete the file.</span></span> <span data-ttu-id="1a2fe-133">Tiedoston avulla voit siirtää tietoja verojen valmistelussa käytettävään ohjelmistoon.</span><span class="sxs-lookup"><span data-stu-id="1a2fe-133">You can use the file to transfer information to your tax preparation software.</span></span>

1. <span data-ttu-id="1a2fe-134">Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Vie GIFI-tiedot Exceliin** ja valitse sitten aiheeseen liittyvä linkki.</span><span class="sxs-lookup"><span data-stu-id="1a2fe-134">In the top right corner, choose the **Search for Page or Report** icon, enter **Export GIFI Info. to Excel**, and then choose the related link.</span></span>
2. <span data-ttu-id="1a2fe-135">Määritä Exceliin vietävät tiedot täyttämällä kentät.</span><span class="sxs-lookup"><span data-stu-id="1a2fe-135">Specify what to export to Excel by filling the fields.</span></span> <span data-ttu-id="1a2fe-136">Lue kentän lyhyt kuvaus valitsemalla kenttä tai siirry lisätietoihin valitsemalla linkki.</span><span class="sxs-lookup"><span data-stu-id="1a2fe-136">Choose a field to read a short description of the field or link to more information.</span></span>
3. <span data-ttu-id="1a2fe-137">Valitse **OK**-painike.</span><span class="sxs-lookup"><span data-stu-id="1a2fe-137">Choose the **OK** button.</span></span>

<span data-ttu-id="1a2fe-138">**Huomautus:** Excel-tiedostolla on seuraavat ominaisuudet:</span><span class="sxs-lookup"><span data-stu-id="1a2fe-138">**Note:** The Excel file has the following characteristics:</span></span>

* <span data-ttu-id="1a2fe-139">Saldo pyöristetään lähimpään prosenttilukuun, mutta solun arvona pidetään pääkirjanpidossa oleva prosenttiluku.</span><span class="sxs-lookup"><span data-stu-id="1a2fe-139">The balance is rounded to the nearest percentage, but the cell value maintains the same percentage as it does in the general ledger.</span></span>

* <span data-ttu-id="1a2fe-140">Negatiiviset luvut esitetään suluissa olevina positiivisina lukuina.</span><span class="sxs-lookup"><span data-stu-id="1a2fe-140">Negative numbers are represented as positive number in brackets.</span></span> <span data-ttu-id="1a2fe-141">Luku -123 on siis (123).</span><span class="sxs-lookup"><span data-stu-id="1a2fe-141">Accordingly, -123 is represented as (123).</span></span>

## <a name="see-also"></a><span data-ttu-id="1a2fe-142">Katso myös</span><span class="sxs-lookup"><span data-stu-id="1a2fe-142">See Also</span></span>
<span data-ttu-id="1a2fe-143">[Rahoitus](finance-setup.md) </span><span class="sxs-lookup"><span data-stu-id="1a2fe-143">[Finance](finance-setup.md) </span></span>  
[<span data-ttu-id="1a2fe-144">Tärkeimpien talousprosessien määrittäminen</span><span class="sxs-lookup"><span data-stu-id="1a2fe-144">Set Up Core Financial Processes</span></span>](finance-setup-setup-finance-setup.md)

