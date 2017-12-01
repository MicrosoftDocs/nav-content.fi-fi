---
title: "Rakenteen tiedot - yleisen päiväkirjan kirjausrivi"
description: "Tässä ohjeaiheessa on tietoja [!INCLUDE[d365fin](includes/d365fin_md.md)]in yleisen päiväkirjan kirjausriviominaisuuden uudelleenmäärityksessä käytettävistä käsitteistä ja periaatteista."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: design, general journal, posting, codeunit 12
ms.date: 07/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 1dfba8b14019991c95f40ffd5f7fbaed5df414eb
ms.openlocfilehash: eee659ced471969fa0c5a4e453a0fec63d080204
ms.contentlocale: fi-fi
ms.lasthandoff: 12/01/2017

---
# <a name="design-details-general-journal-post-line"></a><span data-ttu-id="0e0aa-103">Rakenteen tiedot: Yleisen päiväkirjan kirjausrivi</span><span class="sxs-lookup"><span data-stu-id="0e0aa-103">Design Details: General Journal Post Line</span></span>
<span data-ttu-id="0e0aa-104">Tässä dokumentaatiossa on yksityiskohtaisia teknisiä tietoja [!INCLUDE[d365fin](includes/d365fin_md.md)] -ohjelman yleisen päiväkirjan kirjausriviominaisuuden uudelleenmäärityksessä käytettävistä konsepteista ja periaatteista.</span><span class="sxs-lookup"><span data-stu-id="0e0aa-104">This documentation provides detailed technical insight into the concepts and principles that are used to redesign the general journal posting line feature in [!INCLUDE[d365fin](includes/d365fin_md.md)].</span></span> <span data-ttu-id="0e0aa-105">Uudelleensuunnittelu tekee koodiyksikkö 12:sta yksinkertaisemman ja ylläpidettävämmän.</span><span class="sxs-lookup"><span data-stu-id="0e0aa-105">The redesign makes codeunit 12 simpler and more maintainable.</span></span> <span data-ttu-id="0e0aa-106">Dokumentointi alkaa kuvailemalla uudelleensuunnittelun käsitteelliset yhteenvedot.</span><span class="sxs-lookup"><span data-stu-id="0e0aa-106">The documentation starts by describing conceptual overviews of the redesign.</span></span> <span data-ttu-id="0e0aa-107">Tämän jälkeen kerrotaan teknisestä arkkitehtuurista ja näytetään muutokset, jotka uudelleensuunnittelu aiheuttaa.</span><span class="sxs-lookup"><span data-stu-id="0e0aa-107">Then it explains the technical architecture to show the changes that result from the redesign.</span></span>  

## <a name="in-this-section"></a><span data-ttu-id="0e0aa-108">Tämän osan sisältö</span><span class="sxs-lookup"><span data-stu-id="0e0aa-108">In This Section</span></span>  
[<span data-ttu-id="0e0aa-109">Yleisen päiväkirjan kirjausrivin yleiskuva</span><span class="sxs-lookup"><span data-stu-id="0e0aa-109">General Journal Post Line Overview</span></span>](design-details-general-journal-post-line-overview.md)  
[<span data-ttu-id="0e0aa-110">Rakenteen tiedot: Kirjausliittymän rakenne</span><span class="sxs-lookup"><span data-stu-id="0e0aa-110">Design Details: Posting Interface Structure</span></span>](design-details-posting-interface-structure.md)  
[<span data-ttu-id="0e0aa-111">Rakenteen tiedot: Kirjausohjelman rakenne</span><span class="sxs-lookup"><span data-stu-id="0e0aa-111">Design Details: Posting Engine Structure</span></span>](design-details-posting-engine-structure.md)  
[<span data-ttu-id="0e0aa-112">Koodiyksikön 12 muutokset: Yleisten muuttujien linkitys yleisen päiväkirjan kirjausriviin</span><span class="sxs-lookup"><span data-stu-id="0e0aa-112">Codeunit 12 Changes: Mapping Global Variables for General Journal Post Line</span></span>](design-details-codeunit-12-changes-mapping-global-variables-for-general-journal-post-line.md)  
[<span data-ttu-id="0e0aa-113">Koodiyksikön 12 muutokset: Päiväkirjakirjausten menettelytapojen muutokset</span><span class="sxs-lookup"><span data-stu-id="0e0aa-113">Codeunit 12 Changes: Changes in General Journal Post Procedures</span></span>](design-details-codeunit-12-changes-changes-in-general-journal-post-procedures.md)  

## <a name="see-also"></a><span data-ttu-id="0e0aa-114">Katso myös</span><span class="sxs-lookup"><span data-stu-id="0e0aa-114">See Also</span></span>  
[<span data-ttu-id="0e0aa-115">Yleisten päiväkirjojen käyttäminen</span><span class="sxs-lookup"><span data-stu-id="0e0aa-115">Working with General Journals</span></span>](ui-work-general-journals.md)

