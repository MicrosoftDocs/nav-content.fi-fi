---
title: Eri valuutoissa olevien tapahtumien kohdistaminen
description: "Jos asiakkaan maksu vastaanotetaan eri valuuttana kuin myytäessä käytetty valuutta, voidaan kirjanpitotapahtumat kohdistaa useana valuuttana."
documentationcenter: 
author: edupont04
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: multiple currencies, payment, reconcile
ms.date: 06/02/2017
ms.author: edupont
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: f323b98472f3e2ef0f28000f8a9140b066206945
ms.contentlocale: fi-fi
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-enable-application-of-ledger-entries-in-different-currencies"></a><span data-ttu-id="6a3ef-103">Toimintaohje: Tapahtumakirjausten kohdistamisen ottaminen käyttöön eri valuutoissa</span><span class="sxs-lookup"><span data-stu-id="6a3ef-103">How to: Enable Application of Ledger Entries in Different Currencies</span></span>
<span data-ttu-id="6a3ef-104">Jos ostat toimittajalta yhdessä valuutassa ja maksat maksun toisessa valuutassa, maksu voidaan kohdistaa ostoon.</span><span class="sxs-lookup"><span data-stu-id="6a3ef-104">If you purchase from a vendor in one currency and submit payment in another currency, you can apply the payment to the purchase.</span></span>

<span data-ttu-id="6a3ef-105">Ja jos asiakkaalle myydään yhdessä valuutassa ja maksu vastaanotetaan toisessa valuutassa, maksu voidaan kohdistaa myyntilaskuun.</span><span class="sxs-lookup"><span data-stu-id="6a3ef-105">Likewise, if you sell to a customer in one currency and receive payment in another currency, you can apply the payment to the sales invoice.</span></span>

<span data-ttu-id="6a3ef-106">Seuraavassa kuvataan, miten tämä määritetään toimittajatapahtumille **Ostojen ja ostovelkojen asetukset** -ikkunassa.</span><span class="sxs-lookup"><span data-stu-id="6a3ef-106">The following procedure describes how to set this up for vendor ledger entries in the **Purchases & Payables Setup** window.</span></span> <span data-ttu-id="6a3ef-107">Asetukset tehdään samoin kuin asiakastapahtumille **Myyntien ja myyntisaamisten asetukset** -ikkunassa.</span><span class="sxs-lookup"><span data-stu-id="6a3ef-107">The setup is similar for customer ledger entries in the **Sales & Receivables Setup** window.</span></span>

## <a name="to-enable-application-of-vendor-ledger-entries-in-different-currencies"></a><span data-ttu-id="6a3ef-108">Toimittajatapahtumien kohdistamisen ottaminen käyttöön eri valuutoissa</span><span class="sxs-lookup"><span data-stu-id="6a3ef-108">To enable application of vendor ledger entries in different currencies</span></span>
1. <span data-ttu-id="6a3ef-109">Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, syötä **Ostojen ostovelkojen asetukset** ja valitse sitten aiheeseen liittyvä linkki.</span><span class="sxs-lookup"><span data-stu-id="6a3ef-109">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Purchases & Payables Setup**, and then choose the related link.</span></span>
2. <span data-ttu-id="6a3ef-110">Valitse **Valuuttojen välinen kohdistus** -kentässä jokin seuraavista vaihtoehdoista.</span><span class="sxs-lookup"><span data-stu-id="6a3ef-110">In the **Appln. between Currencies** field, select one of the following options.</span></span>

| <span data-ttu-id="6a3ef-111">Asetus</span><span class="sxs-lookup"><span data-stu-id="6a3ef-111">Option</span></span> | <span data-ttu-id="6a3ef-112">Kuvaus</span><span class="sxs-lookup"><span data-stu-id="6a3ef-112">Description</span></span> |
| --- | --- |
| <span data-ttu-id="6a3ef-113">Ei yhtään</span><span class="sxs-lookup"><span data-stu-id="6a3ef-113">None</span></span> |<span data-ttu-id="6a3ef-114">Valuuttojen välistä kohdistusta ei sallita.</span><span class="sxs-lookup"><span data-stu-id="6a3ef-114">Application between currencies is not allowed.</span></span> |
| <span data-ttu-id="6a3ef-115">EMU</span><span class="sxs-lookup"><span data-stu-id="6a3ef-115">EMU</span></span> |<span data-ttu-id="6a3ef-116">EMU-valuuttojen välinen kohdistus sallitaan.</span><span class="sxs-lookup"><span data-stu-id="6a3ef-116">Application between EMU currencies is allowed.</span></span> |
| <span data-ttu-id="6a3ef-117">Kaikki</span><span class="sxs-lookup"><span data-stu-id="6a3ef-117">All</span></span> |<span data-ttu-id="6a3ef-118">Kaikkien valuuttojen välinen kohdistus sallitaan.</span><span class="sxs-lookup"><span data-stu-id="6a3ef-118">Application between all currencies is allowed.</span></span> |

## <a name="to-set-up-gl-accounts-for-currency-application-rounding-differences"></a><span data-ttu-id="6a3ef-119">KP-tilien määrittäminen valuutan kohdistuksen pyöristyseroille</span><span class="sxs-lookup"><span data-stu-id="6a3ef-119">To set up G/L accounts for currency application rounding differences</span></span>  
<span data-ttu-id="6a3ef-120">Jos eri valuutoissa olevia tapahtumia kohdistetaan, täytyy määrittää KP-tilit, jolle haluat kirjata pyöristyserot.</span><span class="sxs-lookup"><span data-stu-id="6a3ef-120">If you apply entries in different currencies, you must set up the general ledger accounts to which you want to post rounding differences.</span></span>  

> [!NOTE]  
>  <span data-ttu-id="6a3ef-121">Sinun on määritettävä pääkirjanpidon tilit, ennen kuin viimeistelet tehtävän.</span><span class="sxs-lookup"><span data-stu-id="6a3ef-121">You must set up the general ledger accounts before you complete the task.</span></span> <span data-ttu-id="6a3ef-122">Lisätietoja on kohdassa [Tietoja pääkirjanpidosta ja tilikartasta](finance-general-ledger.md).</span><span class="sxs-lookup"><span data-stu-id="6a3ef-122">For more information, see [Understanding the General Ledger and the Chart of Accounts](finance-general-ledger.md).</span></span>

1. <span data-ttu-id="6a3ef-123">Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, kirjoita **Asiakkaan kirjausryhmät** ja valitse sitten aiheeseen liittyvä linkki.</span><span class="sxs-lookup"><span data-stu-id="6a3ef-123">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Customer Posting Groups**, and then choose the related link.</span></span>  
2. <span data-ttu-id="6a3ef-124">Anna **Debet val. kohd. pyör. tili**- ja **Kredit val. kohd. pyör. tili** -kenttiin asianmukaiset pääkirjanpitotilit, joihin pyöristyserot kirjataan.</span><span class="sxs-lookup"><span data-stu-id="6a3ef-124">In the **Debit Curr. Appln. Rndg. Acc.** and **Credit Curr. Appln. Rndg. Acc.** fields, enter the relevant general ledger accounts to post rounding differences.</span></span>  
3. <span data-ttu-id="6a3ef-125">Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, kirjoita **Toimittajan kirjausryhmät** ja valitse sitten aiheeseen liittyvä linkki.</span><span class="sxs-lookup"><span data-stu-id="6a3ef-125">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Vendor Posting Groups**, and then choose the related link.</span></span>  
4. <span data-ttu-id="6a3ef-126">Anna **Debet val. kohd. pyör. tili**- ja **Kredit val. kohd. pyör. tili** -kentissä pääkirjanpitotilit, joihin pyöristyserot kirjataan.</span><span class="sxs-lookup"><span data-stu-id="6a3ef-126">In the **Debit Curr. Appln. Rndg. Acc.** and **Credit Curr. Appln. Rndg. Acc.** fields, enter the relevant general ledger accounts to post rounding differences.</span></span>  

## <a name="see-also"></a><span data-ttu-id="6a3ef-127">Katso myös</span><span class="sxs-lookup"><span data-stu-id="6a3ef-127">See Also</span></span>
[<span data-ttu-id="6a3ef-128">Ostovelkojen hallinta</span><span class="sxs-lookup"><span data-stu-id="6a3ef-128">Managing Payables</span></span>](payables-manage-payables.md)  
[<span data-ttu-id="6a3ef-129">Myyntisaamisten hallinta</span><span class="sxs-lookup"><span data-stu-id="6a3ef-129">Managing Receivables</span></span>](receivables-manage-receivables.md)  
<span data-ttu-id="6a3ef-130">[[!INCLUDE[d365fin](includes/d365fin_md.md)] -ohjelman käyttäminen](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="6a3ef-130">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>

