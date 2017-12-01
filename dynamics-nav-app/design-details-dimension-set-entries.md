---
title: "Rakennetiedot - dimensioyhdistelmätapahtumat"
description: "Tässä dokumentaatiossa on yksityiskohtaisia teknisiä tietoja dimensiotapahtuman tallennus- ja kirjaustoiminnon uudelleenmäärityksessä käytettävistä konsepteista ja periaatteista."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: design, dimensions, codeunit
ms.date: 07/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 1dfba8b14019991c95f40ffd5f7fbaed5df414eb
ms.openlocfilehash: 6b34fde01e35cdd3178a28a787397f52a43eefab
ms.contentlocale: fi-fi
ms.lasthandoff: 12/01/2017

---
# <a name="design-details-dimension-set-entries"></a><span data-ttu-id="53a27-103">Rakennetiedot: dimensioyhdistelmä-tapahtumat</span><span class="sxs-lookup"><span data-stu-id="53a27-103">Design Details: Dimension Set Entries</span></span>
<span data-ttu-id="53a27-104">Tässä dokumentaatiossa on yksityiskohtaisia teknisiä tietoja [!INCLUDE[d365fin](includes/d365fin_md.md)] -ohjelman dimensiotapahtuman tallennus- ja kirjaustoiminnon uudelleenmäärityksessä käytettävistä konsepteista ja periaatteista.</span><span class="sxs-lookup"><span data-stu-id="53a27-104">This documentation provides detailed technical insight into the concepts and principles that are used to redesign the dimension entry storing and posting feature in [!INCLUDE[d365fin](includes/d365fin_md.md)].</span></span> <span data-ttu-id="53a27-105">Dokumentointi alkaa kuvailemalla uudelleensuunnittelun käsitteelliset yhteenvedot.</span><span class="sxs-lookup"><span data-stu-id="53a27-105">The documentation starts by describing conceptual overviews of the redesign.</span></span> <span data-ttu-id="53a27-106">Tämän jälkeen kerrotaan teknisestä arkkitehtuurista ja näytetään, miten uudelleensuunnittelu tehdään.</span><span class="sxs-lookup"><span data-stu-id="53a27-106">Then it explains the technical architecture to show how the redesign is made.</span></span> <span data-ttu-id="53a27-107">Lopuksi se tarjoaa koodiesimerkkejä, joiden avulla voit varautua dimensiokoodin siirtoon ja päivitykseen.</span><span class="sxs-lookup"><span data-stu-id="53a27-107">Finally, it provides code examples to prepare you for dimension code migration and upgrade.</span></span>  

## <a name="in-this-section"></a><span data-ttu-id="53a27-108">Tämän osan sisältö</span><span class="sxs-lookup"><span data-stu-id="53a27-108">In This Section</span></span>  
[<span data-ttu-id="53a27-109">Dimensioyhdistelmätapahtumien yleiskuva</span><span class="sxs-lookup"><span data-stu-id="53a27-109">Dimension Set Entries Overview</span></span>](design-details-dimension-set-entries-overview.md)  
[<span data-ttu-id="53a27-110">Rakennetiedot: dimensioyhdistelmien etsiminen</span><span class="sxs-lookup"><span data-stu-id="53a27-110">Design Details: Searching for Dimension Combinations</span></span>](design-details-searching-for-dimension-combinations.md)  
[<span data-ttu-id="53a27-111">Rakennetiedot: taulukkorakenne</span><span class="sxs-lookup"><span data-stu-id="53a27-111">Design Details: Table Structure</span></span>](design-details-table-structure.md)  
[<span data-ttu-id="53a27-112">Rakennetiedot: koodiyksikön 408 dimension hallinta</span><span class="sxs-lookup"><span data-stu-id="53a27-112">Design Details: Codeunit 408 Dimension Management</span></span>](design-details-codeunit-408-dimension-management.md)  
[<span data-ttu-id="53a27-113">Rakennetiedot: koodiesimerkkejä muuttuneista kuvioista muutoksissa</span><span class="sxs-lookup"><span data-stu-id="53a27-113">Design Details: Code Examples of Changed Patterns in Modifications</span></span>](design-details-code-examples-of-changed-patterns-in-modifications.md)

