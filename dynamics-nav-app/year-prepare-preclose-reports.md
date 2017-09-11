---
title: Kontaktien kanssa tapahtuvien vuorovaikutusten tallentaminen automaattisesti
author: jswymer
ms.custom: na
ms.date: 09/16/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 6b60b1344a1e18ad91863046110df880f75f7c04
ms.openlocfilehash: 1be15b94abf24da46dd0c46ce217aeb74378f400
ms.contentlocale: fi-fi
ms.lasthandoff: 07/19/2017

---
# <a name="prepare-pre-closing-reports"></a><span data-ttu-id="7f8c6-102">Sulkemista edeltävien raporttien valmisteleminen</span><span class="sxs-lookup"><span data-stu-id="7f8c6-102">Prepare Pre-Closing Reports</span></span>
<span data-ttu-id="7f8c6-103">Ennen kirjojen sulkemista vuoden tai kauden lopussa voit varmistaa tilien tietojen oikeellisuuden käyttämällä useita eri vakioraportteja.</span><span class="sxs-lookup"><span data-stu-id="7f8c6-103">There are many standard reports that you can use to verify the accuracy of the accounts before closing the books at the end of a year or period.</span></span> <span data-ttu-id="7f8c6-104">Voit esimerkiksi tarkistaa **Asiakas - Alust. saldo** -raportin avulla, että asiakkaan kirjausryhmän saldo vastaa vastaavan kirjanpitotilin saldoa tiettynä päivämääränä.</span><span class="sxs-lookup"><span data-stu-id="7f8c6-104">For example, you can use the **Customer - Trial Balance** report to verify that the balance for a customer posting group is equal to the balance on the corresponding general ledger account on a certain date.</span></span>

<span data-ttu-id="7f8c6-105">Seuraavassa taulukossa on luettelo raporteista, jotka voivat olla hyödyksi tässä prosessissa yhdessä raportin nimen kanssa.</span><span class="sxs-lookup"><span data-stu-id="7f8c6-105">The following table describes a number of reports that may be useful in this process along with the report name.</span></span>

|<span data-ttu-id="7f8c6-106">Toiminta</span><span class="sxs-lookup"><span data-stu-id="7f8c6-106">To</span></span>     |<span data-ttu-id="7f8c6-107">Tarkastele tätä raporttia</span><span class="sxs-lookup"><span data-stu-id="7f8c6-107">See this report</span></span>       |
|-------|----------------------|
|<span data-ttu-id="7f8c6-108">Pankkitilien eritellyn alustavan saldoraportin tulostaminen siten, että raportissa on lisätietoja yksittäisistä tapahtumista.</span><span class="sxs-lookup"><span data-stu-id="7f8c6-108">Print a detailed trial balance report for one or more bank accounts with additional information about individual entries.</span></span>|<span data-ttu-id="7f8c6-109">Pankkitili</span><span class="sxs-lookup"><span data-stu-id="7f8c6-109">Bank Acc.</span></span> <span data-ttu-id="7f8c6-110">- Er. alust. saldo</span><span class="sxs-lookup"><span data-stu-id="7f8c6-110">- Detail Trial Bal.</span></span>|
|<span data-ttu-id="7f8c6-111">Valittujen asiakkaiden eritellyn alustavan saldoraportin tulostaminen.</span><span class="sxs-lookup"><span data-stu-id="7f8c6-111">Print a detail trial balance for selected customers.</span></span>|<span data-ttu-id="7f8c6-112">Asiakas - Alustava saldo</span><span class="sxs-lookup"><span data-stu-id="7f8c6-112">Customer - Trial Balance</span></span>|
|<span data-ttu-id="7f8c6-113">Valittujen asiakkaiden eritellyn alustavan saldoraportin tulostaminen valitulta ajalta siten, että raportissa on yksityiskohtaisia tietoja yksittäisistä tapahtumista.</span><span class="sxs-lookup"><span data-stu-id="7f8c6-113">Print a detail trial balance with detailed information about individual entries, for selected customers during a selected period.</span></span>|<span data-ttu-id="7f8c6-114">Asiakas - Erit. alustava saldo</span><span class="sxs-lookup"><span data-stu-id="7f8c6-114">Customer - Detail Trial Bal.</span></span>|
|<span data-ttu-id="7f8c6-115">Valittujen toimittajien eritellyn alustavan saldoraportin tulostaminen.</span><span class="sxs-lookup"><span data-stu-id="7f8c6-115">Print a detail trial balance for selected vendors.</span></span>|<span data-ttu-id="7f8c6-116">Toimittaja - Alustava saldo</span><span class="sxs-lookup"><span data-stu-id="7f8c6-116">Vendor - Trial Balance</span></span>|
|<span data-ttu-id="7f8c6-117">Valittujen toimittajien eritellyn alustavan saldoraportin tulostaminen valitulta ajalta siten, että raportissa on yksityiskohtaisia tietoja yksittäisistä tapahtumista.</span><span class="sxs-lookup"><span data-stu-id="7f8c6-117">Print a detail trial balance with detailed information about individual entries, for selected vendors during a selected period.</span></span>|<span data-ttu-id="7f8c6-118">Toimittaja - Er. alust. saldo</span><span class="sxs-lookup"><span data-stu-id="7f8c6-118">Vendor - Detail Trial Balance</span></span>|
|<span data-ttu-id="7f8c6-119">Alustavan saldon tulostaminen kuluvan vuoden ja edellisen vuoden luvuilla.</span><span class="sxs-lookup"><span data-stu-id="7f8c6-119">Print a trial balance with the current year's and the previous year's figures.</span></span>|<span data-ttu-id="7f8c6-120">Alustava TP-tulos ja -tase</span><span class="sxs-lookup"><span data-stu-id="7f8c6-120">Closing Trial Balance</span></span>|
|<span data-ttu-id="7f8c6-121">Eritellyn alustavan saldoraportin tulostaminen kirjanpitotilien saldoista.</span><span class="sxs-lookup"><span data-stu-id="7f8c6-121">Print a detailed trial balance report for general ledger account balances.</span></span>|<span data-ttu-id="7f8c6-122">Eritelty alustava saldo</span><span class="sxs-lookup"><span data-stu-id="7f8c6-122">Detail Trial Balance</span></span>|
|<span data-ttu-id="7f8c6-123">Kirjanpitotilien saldot ja nettomuutokset sisältävän alustavan saldoraportin tulostaminen.</span><span class="sxs-lookup"><span data-stu-id="7f8c6-123">Print a trial balance report with balances and net changes for general ledger accounts.</span></span>|<span data-ttu-id="7f8c6-124">Alustava tulos/tase</span><span class="sxs-lookup"><span data-stu-id="7f8c6-124">Trial Balance</span></span>|
|<span data-ttu-id="7f8c6-125">Konsolidoidun yrityksen alustavan saldon tulostaminen.</span><span class="sxs-lookup"><span data-stu-id="7f8c6-125">Print a trial balance for a consolidated company.</span></span>|<span data-ttu-id="7f8c6-126">Konsolidoitu alust. tulos/tase</span><span class="sxs-lookup"><span data-stu-id="7f8c6-126">Consolidated Trial Balance</span></span>|
<span data-ttu-id="7f8c6-127">Kun haluat nähdä raportin, valitse oikeassa yläkulmassa oleva **Etsi sivua tai raporttia** -kuvake, kirjoita nimi sellaisena kuin se näkyy taulukossa ja valitse vastaava linkki.</span><span class="sxs-lookup"><span data-stu-id="7f8c6-127">To see a report, in the top right corner, choose the **Search for Page or Report** icon, type the name as it appears in the table, and then choose the related link.</span></span>

## <a name="see-also"></a><span data-ttu-id="7f8c6-128">Katso myös</span><span class="sxs-lookup"><span data-stu-id="7f8c6-128">See Also</span></span>
[<span data-ttu-id="7f8c6-129">Vuosien ja kausien sulkeminen</span><span class="sxs-lookup"><span data-stu-id="7f8c6-129">Close Years and Periods</span></span>](year-close-years-periods.md)

