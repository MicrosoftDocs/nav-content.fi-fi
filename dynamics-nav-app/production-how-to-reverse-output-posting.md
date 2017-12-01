---
title: Tuotoksen kirjaamisen peruuttaminen
description: "Tuotoksen kirjaus täytyy joissakin tilanteissa peruuttaa. Tällainen tilanne voi olla esimerkiksi, jos tiedot annettiin virheellisesti ja tuotantotilaukseen kirjataan väärä tuotoksen määrä."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 09/06/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 1dfba8b14019991c95f40ffd5f7fbaed5df414eb
ms.openlocfilehash: fab5b0a19467422736cda25fc4c087655dff532a
ms.contentlocale: fi-fi
ms.lasthandoff: 12/01/2017

---
# <a name="how-to-reverse-output-posting"></a><span data-ttu-id="a4286-104">Tuotoksen kirjaamisen peruuttaminen</span><span class="sxs-lookup"><span data-stu-id="a4286-104">How to: Reverse Output Posting</span></span>
<span data-ttu-id="a4286-105">Tuotoksen kirjaus täytyy joissakin tilanteissa peruuttaa.</span><span class="sxs-lookup"><span data-stu-id="a4286-105">There are times when output posting must be reversed.</span></span> <span data-ttu-id="a4286-106">Tällainen tilanne voi olla esimerkiksi, jos tiedot annettiin virheellisesti ja tuotantotilaukseen kirjataan väärä tuotoksen määrä.</span><span class="sxs-lookup"><span data-stu-id="a4286-106">An example of this would be if a data entry error occurred and an incorrect amount of output is posted to a production order.</span></span>  

## <a name="to-reverse-an-output-posting"></a><span data-ttu-id="a4286-107">Peruuta tuotoksen kirjaus</span><span class="sxs-lookup"><span data-stu-id="a4286-107">To reverse an output posting</span></span>  
1.  <span data-ttu-id="a4286-108">Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, kirjoita **Tuotospäiväkirja** ja valitse sitten aiheeseen liittyvä linkki.</span><span class="sxs-lookup"><span data-stu-id="a4286-108">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Output Journal**, and then choose the related link.</span></span> <span data-ttu-id="a4286-109">Valitse haluamasi erä.</span><span class="sxs-lookup"><span data-stu-id="a4286-109">Select your batch.</span></span>  
2. <span data-ttu-id="a4286-110">Täytä tarvittavat kentät.</span><span class="sxs-lookup"><span data-stu-id="a4286-110">Fill in the fields as necessary.</span></span> <span data-ttu-id="a4286-111">Lisätietoja on kohdassa [Toimintaohje: Tuotoksen ja ajoaikojen eräkirjaaminen](production-how-to-post-output-quantity.md).</span><span class="sxs-lookup"><span data-stu-id="a4286-111">For more information, see [How to: Batch Post Output and Run Times](production-how-to-post-output-quantity.md).</span></span>
3.  <span data-ttu-id="a4286-112">Valitse **Kohdistetaan tapahtumaan** -kentässä asiaan liittyvä nimiketapahtuma.</span><span class="sxs-lookup"><span data-stu-id="a4286-112">In the **Applies-To Entry** field, select the associated item ledger entry.</span></span> <span data-ttu-id="a4286-113">Tämä peruuttaa kapasiteetti- ja nimiketapahtumat.</span><span class="sxs-lookup"><span data-stu-id="a4286-113">This reverses the capacity and item ledger entries.</span></span>  
4. <span data-ttu-id="a4286-114">Kirjaa peruutus kirjaamalla päiväkirja.</span><span class="sxs-lookup"><span data-stu-id="a4286-114">Post the reversal by posting the journal.</span></span>  

<span data-ttu-id="a4286-115">Tuotospäiväkirjan tapahtumat kirjataan nimiketapahtumiin positiivisena muutoksena.</span><span class="sxs-lookup"><span data-stu-id="a4286-115">The output journal entries are posted to the item ledger as a positive adjustment.</span></span>  

## <a name="see-also"></a><span data-ttu-id="a4286-116">Katso myös</span><span class="sxs-lookup"><span data-stu-id="a4286-116">See Also</span></span>  
 <span data-ttu-id="a4286-117">[Tuotanto](production-manage-manufacturing.md)  </span><span class="sxs-lookup"><span data-stu-id="a4286-117">[Manufacturing](production-manage-manufacturing.md)  </span></span>  
 [<span data-ttu-id="a4286-118">Tuotannon määrittäminen</span><span class="sxs-lookup"><span data-stu-id="a4286-118">Setting Up Manufacturing</span></span>](production-configure-production-processes.md)  
 <span data-ttu-id="a4286-119">[Suunnittelu](production-planning.md)    </span><span class="sxs-lookup"><span data-stu-id="a4286-119">[Planning](production-planning.md)    </span></span>  
 [<span data-ttu-id="a4286-120">Vaihto-omaisuus</span><span class="sxs-lookup"><span data-stu-id="a4286-120">Inventory</span></span>](inventory-manage-inventory.md)  
 [<span data-ttu-id="a4286-121">Osto</span><span class="sxs-lookup"><span data-stu-id="a4286-121">Purchasing</span></span>](purchasing-manage-purchasing.md)  
 <span data-ttu-id="a4286-122">[[!INCLUDE[d365fin](includes/d365fin_md.md)] -ohjelman käyttäminen](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="a4286-122">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>  

