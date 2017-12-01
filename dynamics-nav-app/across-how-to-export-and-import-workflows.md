---
title: "Työnkulkujen vieminen ja tuominen"
description: "Voit siirtää työnkulkuja muihin [!INCLUDE[d365fin](includes/d365fin_md.md)]in tietokantoihin. Esimerkiksi uusia työnkuluja luotaessa työnkulkujen vienti ja tuonti säästää aikaa."
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
ms.openlocfilehash: 80eaf43988e603f6624e5b1eb23af993bb6ce5f5
ms.contentlocale: fi-fi
ms.lasthandoff: 12/01/2017

---
# <a name="how-to-export-and-import-workflows"></a><span data-ttu-id="93937-103">Toimintaohje: työnkulkujen vienti ja tuonti</span><span class="sxs-lookup"><span data-stu-id="93937-103">How to: Export and Import Workflows</span></span>
<span data-ttu-id="93937-104">Voit siirtää työnkulkuja muihin [!INCLUDE[d365fin](includes/d365fin_md.md)] tietokantoihin. esimerkiksi luotaessa uusia työnkuluja voidaan aikaa säästääksesi viedä ja tuoda työnkulkuja.</span><span class="sxs-lookup"><span data-stu-id="93937-104">To transfer workflows to other [!INCLUDE[d365fin](includes/d365fin_md.md)] databases, for example to save time when creating new workflows, you can export and import workflows.</span></span>  

 <span data-ttu-id="93937-105">Toinen tapa luoda nopeasti työnkulut on työnkulkujen luominen työnkulkumalleista.</span><span class="sxs-lookup"><span data-stu-id="93937-105">Another way to quickly create workflows is to create workflows from workflow templates.</span></span> <span data-ttu-id="93937-106">Lisätietoja on kohdassa [Työnkulkujen luominen työnkulkumalleista](across-how-to-create-workflows-from-workflow-templates.md).</span><span class="sxs-lookup"><span data-stu-id="93937-106">For more information, see [How to: Create Workflows from Workflow Templates](across-how-to-create-workflows-from-workflow-templates.md).</span></span>  

 <span data-ttu-id="93937-107">**Työnkulku**-ikkunassa voit luoda työnkulun luetteloimalla liittyvät toimet riveillä.</span><span class="sxs-lookup"><span data-stu-id="93937-107">In the **Workflow** window, you create a workflow by listing the involved steps on the lines.</span></span> <span data-ttu-id="93937-108">Jokainen vaihe koostuu työnkulun tapahtumasta, jota valvotaan tapahtuman ehtojen mukaan, ja työnkulun vastauksesta, jota valvotaan vastausvaihtoehtojen mukaan.</span><span class="sxs-lookup"><span data-stu-id="93937-108">Each step consists of a workflow event, moderated by event conditions, and a workflow response, moderated by response options.</span></span> <span data-ttu-id="93937-109">Työnkulku määritetään täyttämällä työnkulkurivien kentät tapahtumien kiinteistä luetteloista ja vastausarvot, jotka edustavat sovelluskoodin tukemia skenaarioita.</span><span class="sxs-lookup"><span data-stu-id="93937-109">You define workflow steps by filling fields on workflow lines from fixed lists of event and response values representing scenarios that are supported by the application code.</span></span> <span data-ttu-id="93937-110">Lisätietoja on kohdassa [Toimintaohje: Työnkulkujen luominen](across-how-to-create-workflows.md).</span><span class="sxs-lookup"><span data-stu-id="93937-110">For more information, see [How to: Create Workflows](across-how-to-create-workflows.md).</span></span>  

## <a name="to-export-a-workflow"></a><span data-ttu-id="93937-111">Työnkulun vieminen</span><span class="sxs-lookup"><span data-stu-id="93937-111">To export a workflow</span></span>  
1.  <span data-ttu-id="93937-112">Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, kirjoita **Työnkulut** ja valitse sitten aiheeseen liittyvä linkki.</span><span class="sxs-lookup"><span data-stu-id="93937-112">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Workflows**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="93937-113">Valitse ensin työnkulku ja sitten **Vie tiedostoon** -toiminto.</span><span class="sxs-lookup"><span data-stu-id="93937-113">Select a workflow, and then choose the **Export to File** action.</span></span>  
3.  <span data-ttu-id="93937-114">Valitse **Vie tiedosto** -ikkunassa **Tallenna**.</span><span class="sxs-lookup"><span data-stu-id="93937-114">In the **Export File** window, choose the **Save** button.</span></span>  
4.  <span data-ttu-id="93937-115">Valitse tiedostosijainti **Vie**-ikkunassa ja valitse sitten **Tallenna**-painike.</span><span class="sxs-lookup"><span data-stu-id="93937-115">In the **Export** window, select a file location, and then choose the **Save** button.</span></span>  

## <a name="to-import-a-workflow"></a><span data-ttu-id="93937-116">Työnkulun tuominen</span><span class="sxs-lookup"><span data-stu-id="93937-116">To import a workflow</span></span>  
1.  <span data-ttu-id="93937-117">Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, kirjoita **Työnkulut** ja valitse sitten aiheeseen liittyvä linkki.</span><span class="sxs-lookup"><span data-stu-id="93937-117">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Workflows**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="93937-118">Valitse **Tuo tiedostosta** -toiminto.</span><span class="sxs-lookup"><span data-stu-id="93937-118">Choose the **Import from File** action.</span></span>  
3.  <span data-ttu-id="93937-119">Valitse **Tuo** ikkunassa XML-tiedosto, joka sisältää työnkulun, ja valitse sitten **Avaa**.</span><span class="sxs-lookup"><span data-stu-id="93937-119">In the **Import** window, choose the XML file that contains the workflow, and then choose the **Open** button.</span></span>  

> [!CAUTION]  
>  <span data-ttu-id="93937-120">Jos työnkulun koodi on jo tietokannassa, työnkulun osavaiheita korvataan tuodun työnkulun vaiheilla.</span><span class="sxs-lookup"><span data-stu-id="93937-120">If the workflow code already exists in the database, the workflow steps will be overwritten with the steps in the imported workflow.</span></span>  

## <a name="see-also"></a><span data-ttu-id="93937-121">Katso myös</span><span class="sxs-lookup"><span data-stu-id="93937-121">See Also</span></span>  
 <span data-ttu-id="93937-122">[Toimintaohje: Työnkulkujen luominen](across-how-to-create-workflows.md) </span><span class="sxs-lookup"><span data-stu-id="93937-122">[How to: Create Workflows](across-how-to-create-workflows.md) </span></span>  
 <span data-ttu-id="93937-123">[Ohje: Työnkulkujen luominen työnkulkumalleista](across-how-to-create-workflows-from-workflow-templates.md) </span><span class="sxs-lookup"><span data-stu-id="93937-123">[How to: Create Workflows from Workflow Templates](across-how-to-create-workflows-from-workflow-templates.md) </span></span>  
 <span data-ttu-id="93937-124">[Toimintaohje: Arkistoitujen työnkulun osavaiheen instanssien tarkasteleminen](across-how-to-view-archived-workflow-step-instances.md) </span><span class="sxs-lookup"><span data-stu-id="93937-124">[How to: View Archived Workflow Step Instances](across-how-to-view-archived-workflow-step-instances.md) </span></span>  
 <span data-ttu-id="93937-125">[Toimintaohje: Työnkulkujen poistaminen](across-how-to-delete-workflows.md) </span><span class="sxs-lookup"><span data-stu-id="93937-125">[How to: Delete Workflows](across-how-to-delete-workflows.md) </span></span>  
 <span data-ttu-id="93937-126">[Vaihekuvaus: Ostojen hyväksyntätyönkulun määrittäminen ja käyttäminen](walkthrough-setting-up-and-using-a-purchase-approval-workflow.md) </span><span class="sxs-lookup"><span data-stu-id="93937-126">[Walkthrough: Setting Up and Using a Purchase Approval Workflow](walkthrough-setting-up-and-using-a-purchase-approval-workflow.md) </span></span>  
 <span data-ttu-id="93937-127">[Työnkulkujen määrittäminen](across-set-up-workflows.md) </span><span class="sxs-lookup"><span data-stu-id="93937-127">[Setting Up Workflows](across-set-up-workflows.md) </span></span>  
 <span data-ttu-id="93937-128">[Työnkulkujen käyttäminen](across-use-workflows.md) </span><span class="sxs-lookup"><span data-stu-id="93937-128">[Using Workflows](across-use-workflows.md) </span></span>  
 [<span data-ttu-id="93937-129">Työnkulku</span><span class="sxs-lookup"><span data-stu-id="93937-129">Workflow</span></span>](across-workflow.md)   

