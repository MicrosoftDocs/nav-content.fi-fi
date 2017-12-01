---
title: Maksuosoitusehdotuksen tulostaminen
description: "Voit auttaa toimittajia täsmäytysten suorittamisessa, kun tulostat maksuosoitusehdotuksen ennen maksupäiväkirjan kirjaamista ja maksun kirjaamisen jälkeen."
documentationcenter: 
author: bholtorf
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 10/26/2017
ms.author: bholtorf
ms.translationtype: HT
ms.sourcegitcommit: 1dfba8b14019991c95f40ffd5f7fbaed5df414eb
ms.openlocfilehash: 7c7004ac5ded9436861bf5034f59a9c2bcd99dd0
ms.contentlocale: fi-fi
ms.lasthandoff: 12/01/2017

---

#<a name="how-to-print-remittance-advice"></a><span data-ttu-id="c01fe-103">Toimintaohje: Maksuosoitusehdotuksen tulostaminen</span><span class="sxs-lookup"><span data-stu-id="c01fe-103">How to: Print Remittance Advice</span></span>
<span data-ttu-id="c01fe-104">Voit tulostaa maksuosoitusehdotuksen ennen maksupäiväkirjan kirjaamista ja maksun kirjaamisen jälkeen.</span><span class="sxs-lookup"><span data-stu-id="c01fe-104">You can print remittance advice before posting a payment journal and after posting a payment.</span></span> <span data-ttu-id="c01fe-105">Tämä ehdotus näyttää toimittajan laskunumerot. Näin toimittajien on helpompi suorittaa täsmäytykset.</span><span class="sxs-lookup"><span data-stu-id="c01fe-105">This advice displays vendor invoice numbers, which helps vendors to perform reconciliations.</span></span>

##<a name="to-print-remittance-advice"></a><span data-ttu-id="c01fe-106">Maksuosoitusehdotuksen tulostaminen</span><span class="sxs-lookup"><span data-stu-id="c01fe-106">To print remittance advice</span></span>
1. <span data-ttu-id="c01fe-107">Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, kirjoita **Maksupäiväkirjat** ja valitse sitten aiheeseen liittyvä linkki.</span><span class="sxs-lookup"><span data-stu-id="c01fe-107">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Payment Journals**, and then choose the related link.</span></span>  
2. <span data-ttu-id="c01fe-108">Valitse **Maksupäiväkirja**-ikkunassa maksu, jonka maksuosoitusehdotus tulostetaan.</span><span class="sxs-lookup"><span data-stu-id="c01fe-108">In the **Payment Journal** window, select the payment for which remittance advice must be printed.</span></span>  
3. <span data-ttu-id="c01fe-109">Valitse **Tulosta maksuosoitusehdotus** -toiminto.</span><span class="sxs-lookup"><span data-stu-id="c01fe-109">Choose the **Print Remittance Advice** action.</span></span>  
4. <span data-ttu-id="c01fe-110">Valitse **Maksuosoitusehdotus – päiväkirja** -erätyön **Yleisen päiväkirjan rivi** -pikavälilehdessä soveltuvat suodattimet.</span><span class="sxs-lookup"><span data-stu-id="c01fe-110">In the **Remittance Advice - Journal** batch job, on the **Fen. Journal Line** FastTab, choose the appropriate filters.</span></span>  
  
    >[!Note]
    > <span data-ttu-id="c01fe-111">Voit suodattaa käyttämällä toimittajan ulkoisen asiakirjan numeroa, kun haluat kohdistaa maksut laskuihin.</span><span class="sxs-lookup"><span data-stu-id="c01fe-111">You can filter using the vendor's external document number to match payments with invoices.</span></span>

5. <span data-ttu-id="c01fe-112">Valitse **Toimittaja**-pikavälilehdessä soveltuvat suodattimet.</span><span class="sxs-lookup"><span data-stu-id="c01fe-112">On the **Vendor** FastTab, choose the appropriate filters.</span></span>  
6. <span data-ttu-id="c01fe-113">Valitse **Tulosta**, kun haluat tulostaa raportin. Valitse **Esikatsele**, kun haluat tarkastella sitä nyt.</span><span class="sxs-lookup"><span data-stu-id="c01fe-113">Choose **Print** to print the report, or choose **Preview** to view it now.</span></span>  

## <a name="using-remittance-advice-reports"></a><span data-ttu-id="c01fe-114">Maksuosoitusehdotusten raporttien käyttäminen</span><span class="sxs-lookup"><span data-stu-id="c01fe-114">Using Remittance Advice Reports</span></span>
<span data-ttu-id="c01fe-115">Seuraavassa taulukossa esitellään maksuosoitusehdotuksen kanssa käytettävät raportit:</span><span class="sxs-lookup"><span data-stu-id="c01fe-115">The following table describes the reports that you can use with remittance advice:</span></span>

|<span data-ttu-id="c01fe-116">Raportti</span><span class="sxs-lookup"><span data-stu-id="c01fe-116">Report</span></span>|<span data-ttu-id="c01fe-117">Description</span><span class="sxs-lookup"><span data-stu-id="c01fe-117">Description</span></span>|
|----|----|
|<span data-ttu-id="c01fe-118">Maksuosoitusehdotus – päiväkirja -raportti</span><span class="sxs-lookup"><span data-stu-id="c01fe-118">Remittance Advice - Journal Report</span></span>|<span data-ttu-id="c01fe-119">Tämä raportti osoittaa maksuun sisällytettävät asiakirjat.</span><span class="sxs-lookup"><span data-stu-id="c01fe-119">This report indicates which documents are included in the payment.</span></span> <span data-ttu-id="c01fe-120">Voit määrittää yleisen päiväkirjan riveille päiväkirjan mallin ja päiväkirjan erän, josta maksuosoitusehdotukset tulostetaan, ensimmäisen tulostettavan päivämäärän ja asiakirjanumeron suodattimen.</span><span class="sxs-lookup"><span data-stu-id="c01fe-120">For general journal lines, you can specify the journal template and journal batch from which the remittance advices will be printed, the date of the first activity to print, and filter on a document number.</span></span> <span data-ttu-id="c01fe-121">Voit antaa toimittajille raporttiin sisällytettävät toimittajanumerot.</span><span class="sxs-lookup"><span data-stu-id="c01fe-121">For vendors, you can enter the vendor numbers to include in the report.</span></span> |
|<span data-ttu-id="c01fe-122">Maksuosoitusehdotus – tapahtumat -raportti</span><span class="sxs-lookup"><span data-stu-id="c01fe-122">Remittance Advice - Entries Report</span></span>| <span data-ttu-id="c01fe-123">Tämä raportti osoittaa maksuun sisällytettävät asiakirjat.</span><span class="sxs-lookup"><span data-stu-id="c01fe-123">This report indicates which documents are included in the payment.</span></span> <span data-ttu-id="c01fe-124">Määritä raportin sisältö suodattimien avulla.</span><span class="sxs-lookup"><span data-stu-id="c01fe-124">You define the report contents by setting filters.</span></span> <span data-ttu-id="c01fe-125">Voit määrittää lisäkenttiä välilehteen, kun valitset **Kenttä**-kentän.</span><span class="sxs-lookup"><span data-stu-id="c01fe-125">You can set additional fields on the tab by choosing the **Field** field.</span></span> <span data-ttu-id="c01fe-126">Toimittajatapahtumille voit määrittää raporttiin sisällytettävät toimittajat, ensimmäisen tulostettavan aktiviteetin päivämäärän ja sisällytettävän tapahtumanumeron.</span><span class="sxs-lookup"><span data-stu-id="c01fe-126">For vendor ledger entries, you can specify the vendors to include in the report, the date of the first activity to print, the currency, and the entry number to include.</span></span> |

> [!Note]
> <span data-ttu-id="c01fe-127">Maksuosoitusehdotus – päiväkirja -raportti ei tue valuuttojen välisiä kohdistustapauksia eikä maksutoleransseja.</span><span class="sxs-lookup"><span data-stu-id="c01fe-127">The Remittance Advice - Journal Report does not support cross currency application scenarios or payment tolerances.</span></span> <span data-ttu-id="c01fe-128">Lisätietoja on kohdassa [Toimintaohje: Tapahtumakirjausten kohdistamisen ottaminen käyttöön eri valuutoissa](finance-how-enable-application-ledger-entries-different-currencies.md).</span><span class="sxs-lookup"><span data-stu-id="c01fe-128">For more information, see [How to: Enable Application of Ledger Entries in Different Currencies](finance-how-enable-application-ledger-entries-different-currencies.md).</span></span>

> [!Tip]
> <span data-ttu-id="c01fe-129">Lisätietoja raporttien käsittelemisestä on kohdissa [Testiraporttien tarkastelu ennen kirjausta](ui-how-view-test-reports-posting.md), [Raporttien käsitteleminen](ui-work-report.md) ja [Tietojen hakeminen, suodattaminen ja lajitteleminen](ui-enter-criteria-filters.md).</span><span class="sxs-lookup"><span data-stu-id="c01fe-129">For more information about how to work with reports, see [Viewing Test Reports before Posting](ui-how-view-test-reports-posting.md), [Work with Reports](ui-work-report.md), and [Searching, Filtering, and Sorting Data](ui-enter-criteria-filters.md).</span></span>

##<a name="see-also"></a><span data-ttu-id="c01fe-130">Katso myös</span><span class="sxs-lookup"><span data-stu-id="c01fe-130">See Also</span></span>  
[<span data-ttu-id="c01fe-131">Tervetuloa Dynamics NAViin!</span><span class="sxs-lookup"><span data-stu-id="c01fe-131">Welcome to Dynamics NAV</span></span>](across-get-started.md)
