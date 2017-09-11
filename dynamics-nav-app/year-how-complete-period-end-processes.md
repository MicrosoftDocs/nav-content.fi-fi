---
title: Kausien sulkeminen
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
ms.openlocfilehash: ac1ed2d1dcf8bf780bda91fbf0a04e5c5e8d106a
ms.contentlocale: fi-fi
ms.lasthandoff: 06/26/2017

---
# <a name="close-periods"></a><span data-ttu-id="21d09-102">Kausien sulkeminen</span><span class="sxs-lookup"><span data-stu-id="21d09-102">Close Periods</span></span>
<span data-ttu-id="21d09-103">Sovellus ei pakota sulkemaan kausia. Sovelluksessa voidaan kuitenkin suorittaa useita kauden lopun (kuukauden lopun) toimenpiteitä.</span><span class="sxs-lookup"><span data-stu-id="21d09-103">The application does not force you to close periods, however, there are many period-end (month-end) activities that can be performed in the application if you want.</span></span> <span data-ttu-id="21d09-104">Tässä ohjeaiheessa on yrityksen käytettävissä olevien prosessien ja toimenpiteiden yleiskuvaus.</span><span class="sxs-lookup"><span data-stu-id="21d09-104">This topic provides an overview of these processes and activities, which may or may not be necessary for your company.</span></span>

## <a name="general-ledger"></a><span data-ttu-id="21d09-105">Pääkirjanpito</span><span class="sxs-lookup"><span data-stu-id="21d09-105">General Ledger</span></span>
* <span data-ttu-id="21d09-106">Määritä järjestelmänlaajuinen ja käyttäjäkohtainen kirjausjakso.</span><span class="sxs-lookup"><span data-stu-id="21d09-106">Specify system-wide and user-specific posting period.</span></span>

    <span data-ttu-id="21d09-107">Tässä määritetään kirjausten sallittu päivämääräväli.</span><span class="sxs-lookup"><span data-stu-id="21d09-107">This specifies the dates between which postings are allowed.</span></span> <span data-ttu-id="21d09-108">Liiketoimintatarpeittesi mukaan haluat ehkä rajoittaa käyttäjän kirjauspäivämääräalueet kauden lopussa suoritettavan prosessin alussa tai myöhemmin jakson lopussa.</span><span class="sxs-lookup"><span data-stu-id="21d09-108">Depending on your business needs, you may want to restrict user posting date ranges at the start of the period-end process or at later time towards the end of the period.</span></span> <span data-ttu-id="21d09-109">Lisätietoja on kohdassa [Toimintaohje: Kirjausjaksojen määrittäminen](finance-setup-how-specify-posting-periods.md).</span><span class="sxs-lookup"><span data-stu-id="21d09-109">For more information, see [How to: Specify Posting Periods](finance-setup-how-specify-posting-periods.md).</span></span>
* <span data-ttu-id="21d09-110">Tee kaikki tarpeelliset KP-muutokset.</span><span class="sxs-lookup"><span data-stu-id="21d09-110">Make all necessary G/L adjustments.</span></span>
* <span data-ttu-id="21d09-111">Päivitä ja kirjaa toistuvat päiväkirjat.</span><span class="sxs-lookup"><span data-stu-id="21d09-111">Update and post Recurring Journals.</span></span>
<!--* Process Consolidations-->
* <span data-ttu-id="21d09-112">Suorita KP-raporttimallit seuraavasti:</span><span class="sxs-lookup"><span data-stu-id="21d09-112">Run account schedules as follows:</span></span>
  1. <span data-ttu-id="21d09-113">Avaa **KP-raporttimalli**-ikkuna ja valitse **Tulosta**-toiminto.</span><span class="sxs-lookup"><span data-stu-id="21d09-113">Open the **Account Schedule** window, and choose the **Print** action.</span></span>
  2. <span data-ttu-id="21d09-114">Täytä **KP-raporttimalli**-pyyntöikkuna ja valitse **Tulosta**-toiminto.</span><span class="sxs-lookup"><span data-stu-id="21d09-114">Fill the **Account Schedule** request window and choose the **Print** action.</span></span>

## <a name="sales--receivables"></a><span data-ttu-id="21d09-115">Myynnit ja myyntisaamiset</span><span class="sxs-lookup"><span data-stu-id="21d09-115">Sales & Receivables</span></span>
* <span data-ttu-id="21d09-116">Kirjaa kaikki myyntitilaukset, laskut, hyvityslaskut ja palautustilaukset.</span><span class="sxs-lookup"><span data-stu-id="21d09-116">Post all sales orders, invoices, credit memos, and return orders.</span></span>
* <span data-ttu-id="21d09-117">Kirjaa kaikki kassapäiväkirjat.</span><span class="sxs-lookup"><span data-stu-id="21d09-117">Post all cash receipt journals.</span></span>
* <span data-ttu-id="21d09-118">Päivitä ja kirjaa myyntiin ja myyntisaamisiin liittyvät toistuvat päiväkirjat.</span><span class="sxs-lookup"><span data-stu-id="21d09-118">Update and post recurring journals that are related to Sales & Receivables.</span></span>
* <span data-ttu-id="21d09-119">Täsmäytä myyntisaatavat pääkirjanpitoon.</span><span class="sxs-lookup"><span data-stu-id="21d09-119">Reconcile accounts receivable to the general ledger.</span></span>
* <span data-ttu-id="21d09-120">Suorita **Poista laskutetut myyntitilaukset** -eräajo.</span><span class="sxs-lookup"><span data-stu-id="21d09-120">Run the **Delete Invoiced Sales Orders** batch job.</span></span>

## <a name="purchases--payables"></a><span data-ttu-id="21d09-121">Ostot ja ostovelat</span><span class="sxs-lookup"><span data-stu-id="21d09-121">Purchases & Payables</span></span>
* <span data-ttu-id="21d09-122">Kirjaa kaikki ostotilaukset, laskut, hyvityslaskut ja palautustilaukset.</span><span class="sxs-lookup"><span data-stu-id="21d09-122">Post all purchase orders, invoices, credit memos, and return orders.</span></span>
* <span data-ttu-id="21d09-123">Kirjaa kaikki maksupäiväkirjat.</span><span class="sxs-lookup"><span data-stu-id="21d09-123">Post all payment journals.</span></span>
* <span data-ttu-id="21d09-124">Päivitä ja kirjaa ostoihin ja ostovelkoihin liittyvät toistuvat päiväkirjat.</span><span class="sxs-lookup"><span data-stu-id="21d09-124">Update and post recurring journals that are related to purchases & payables.</span></span>
* <span data-ttu-id="21d09-125">Suorita **Ostovelkojen tilanne** -raportti ja täsmäytä ostovelat pääkirjanpitoon.</span><span class="sxs-lookup"><span data-stu-id="21d09-125">Run the **Aged Accounts Payable** report and reconcile accounts payable to the general ledger.</span></span>
* <span data-ttu-id="21d09-126">Suorita **Poista laskutetut ostotilaukset** -eräajo.</span><span class="sxs-lookup"><span data-stu-id="21d09-126">Run the **Delete Invoiced Purchase Orders** batch job.</span></span>

<!-- ### Fixed Assets
* Post all maintenance costs have been posted through the fixed asset journals or invoices.
* Post adjustments.
* Post appreciation.
* Post depreciation.
* Update and post the recurring fixed asset journal.-->

<!--### Intercompany
* Process Intercompany Postings.-->

## <a name="calculate-and-process-sales-tax"></a><span data-ttu-id="21d09-127">Arvonlisäveron laskeminen ja käsitteleminen</span><span class="sxs-lookup"><span data-stu-id="21d09-127">Calculate and Process Sales Tax</span></span>
*  <span data-ttu-id="21d09-128">Täytä ALV-ilmoitukset.</span><span class="sxs-lookup"><span data-stu-id="21d09-128">Complete Tax Statements.</span></span>

## <a name="see-also"></a><span data-ttu-id="21d09-129">Katso myös</span><span class="sxs-lookup"><span data-stu-id="21d09-129">See Also</span></span>
[<span data-ttu-id="21d09-130">Vuosien ja kausien sulkeminen</span><span class="sxs-lookup"><span data-stu-id="21d09-130">Closing Years and Periods</span></span>](year-close-years-periods.md)  
[<span data-ttu-id="21d09-131">Kirjojen sulkeminen</span><span class="sxs-lookup"><span data-stu-id="21d09-131">Close Books</span></span>](year-close-books.md)

