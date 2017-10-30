---
title: "Työnkulkujen luominen työnkulkumalleista"
description: "Voit säästää aikaa uusien työnkulkujen luomisessa luomalla työnkulut työnkulkumalleista."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 07/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: b0c2143b85a7301711498ecd40d6f6685be17eda
ms.contentlocale: fi-fi
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-create-workflows-from-workflow-templates"></a><span data-ttu-id="9bf72-103">Ohje: Työnkulkujen luominen työnkulkumalleista</span><span class="sxs-lookup"><span data-stu-id="9bf72-103">How to: Create Workflows from Workflow Templates</span></span>
<span data-ttu-id="9bf72-104">Voit säästää aikaa uusien työnkulkujen luomisessa luomalla työnkulut työnkulkumalleista.</span><span class="sxs-lookup"><span data-stu-id="9bf72-104">To save time when creating new workflows, you can create workflows from workflow templates.</span></span>  

 <span data-ttu-id="9bf72-105">Työnkulkumallit ovat yleisen [!INCLUDE[d365fin](includes/d365fin_md.md)] -version työnkulkuja, joita ei voi muokata.</span><span class="sxs-lookup"><span data-stu-id="9bf72-105">Workflow templates are non-editable workflows that exist in the generic version of [!INCLUDE[d365fin](includes/d365fin_md.md)].</span></span> <span data-ttu-id="9bf72-106">Työnkulkumallien koodit, jotka Microsoft on lisännyt, sisältävät etuliitteen "MS-".</span><span class="sxs-lookup"><span data-stu-id="9bf72-106">The codes for workflow templates that are added by Microsoft are prefixed with “MS-“.</span></span>  

 <span data-ttu-id="9bf72-107">Työnkulun voi nopeasti myös tuomalla aiemmin luodun työnkulun, joka on [!INCLUDE[d365fin](includes/d365fin_md.md)]in ulkopuolisessa tiedostossa.</span><span class="sxs-lookup"><span data-stu-id="9bf72-107">Another way to quickly create a workflow is to import an existing workflow that you have on a file outside of [!INCLUDE[d365fin](includes/d365fin_md.md)].</span></span> <span data-ttu-id="9bf72-108">Lisätietoja on kohdassa [Toimintaohje: Työnkulkujen vienti ja tuonti](across-how-to-export-and-import-workflows.md).</span><span class="sxs-lookup"><span data-stu-id="9bf72-108">For more information, see [How to: Export and Import Workflows](across-how-to-export-and-import-workflows.md).</span></span>  

<span data-ttu-id="9bf72-109">**Työnkulku**-ikkunassa voit luoda työnkulun luetteloimalla liittyvät toimet riveillä.</span><span class="sxs-lookup"><span data-stu-id="9bf72-109">In the **Workflow** window, you create a workflow by listing the involved steps on the lines.</span></span> <span data-ttu-id="9bf72-110">Jokainen vaihe koostuu työnkulun tapahtumasta, jota valvotaan tapahtuman ehtojen mukaan, ja työnkulun vastauksesta, jota valvotaan vastausvaihtoehtojen mukaan.</span><span class="sxs-lookup"><span data-stu-id="9bf72-110">Each step consists of a workflow event, moderated by event conditions, and a workflow response, moderated by response options.</span></span> <span data-ttu-id="9bf72-111">Työnkulku määritetään täyttämällä työnkulkurivien kentät tapahtumien kiinteistä luetteloista ja vastausarvot, jotka edustavat sovelluskoodin tukemia skenaarioita.</span><span class="sxs-lookup"><span data-stu-id="9bf72-111">You define workflow steps by filling fields on workflow lines from fixed lists of event and response values representing scenarios that are supported by the application code.</span></span> <span data-ttu-id="9bf72-112">Lisätietoja on kohdassa [Työnkulkujen luominen](across-how-to-create-workflows.md).</span><span class="sxs-lookup"><span data-stu-id="9bf72-112">For more information, see [How to: Create Workflows](across-how-to-create-workflows.md).</span></span>  

## <a name="to-create-a-workflow-from-workflow-template"></a><span data-ttu-id="9bf72-113">Työnkulun luominen työnkulkumallista</span><span class="sxs-lookup"><span data-stu-id="9bf72-113">To create a workflow from workflow template</span></span>  
1.  <span data-ttu-id="9bf72-114">Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, kirjoita **Työnkulut** ja valitse sitten aiheeseen liittyvä linkki.</span><span class="sxs-lookup"><span data-stu-id="9bf72-114">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Workflows**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="9bf72-115">Valitse **Luo työnkulku mallista** -toiminto.</span><span class="sxs-lookup"><span data-stu-id="9bf72-115">Choose the **Create Workflow from Template** action.</span></span> <span data-ttu-id="9bf72-116">**Työnkulkumallit**-ikkuna avautuu.</span><span class="sxs-lookup"><span data-stu-id="9bf72-116">The **Workflow Templates** window opens.</span></span>  
3.  <span data-ttu-id="9bf72-117">Valitse työnkulkumalli ja sitten **OK**-painike.</span><span class="sxs-lookup"><span data-stu-id="9bf72-117">Select a workflow template, and then choose the **OK** button.</span></span>  

     <span data-ttu-id="9bf72-118">Uuden työnkulun avautuvassa **Työnkulku**-ikkunassa on kaikki valitun mallin tiedot.</span><span class="sxs-lookup"><span data-stu-id="9bf72-118">The **Workflow** window opens for a new workflow containing all the information of the selected template.</span></span> <span data-ttu-id="9bf72-119">**Koodi**-kentän arvoon liitetään esimerkiksi ”-01”, joka osoittaa, että kyseessä on ensimmäinen työnkulkumallista luotu työnkulku.</span><span class="sxs-lookup"><span data-stu-id="9bf72-119">The value in the **Code** field is extended with, for example, “-01” to indicate that this is the first workflow that is created from the workflow template.</span></span>  
4.  <span data-ttu-id="9bf72-120">Jatka työnkulun luontia muokkaamalla työnkulun vaiheita tai lisäämällä uusia vaiheita.</span><span class="sxs-lookup"><span data-stu-id="9bf72-120">Proceed to create the workflow by editing the workflow steps or add new steps.</span></span> <span data-ttu-id="9bf72-121">Lisätietoja on kohdassa [Toimintaohje: Työnkulkujen luominen](across-how-to-create-workflows.md).</span><span class="sxs-lookup"><span data-stu-id="9bf72-121">For more information, see [How to: Create Workflows](across-how-to-create-workflows.md).</span></span>  

## <a name="see-also"></a><span data-ttu-id="9bf72-122">Katso myös</span><span class="sxs-lookup"><span data-stu-id="9bf72-122">See Also</span></span>  
 <span data-ttu-id="9bf72-123">[Toimintaohje: Työnkulkujen luominen](across-how-to-create-workflows.md) </span><span class="sxs-lookup"><span data-stu-id="9bf72-123">[How to: Create Workflows](across-how-to-create-workflows.md) </span></span>  
 <span data-ttu-id="9bf72-124">[Toimintaohje: työnkulkujen vienti ja tuonti](across-how-to-export-and-import-workflows.md) </span><span class="sxs-lookup"><span data-stu-id="9bf72-124">[How to: Export and Import Workflows](across-how-to-export-and-import-workflows.md) </span></span>  
 <span data-ttu-id="9bf72-125">[Toimintaohje: Arkistoitujen työnkulun osavaiheen instanssien tarkasteleminen](across-how-to-view-archived-workflow-step-instances.md) </span><span class="sxs-lookup"><span data-stu-id="9bf72-125">[How to: View Archived Workflow Step Instances](across-how-to-view-archived-workflow-step-instances.md) </span></span>  
 <span data-ttu-id="9bf72-126">[Toimintaohje: Työnkulkujen poistaminen](across-how-to-delete-workflows.md) </span><span class="sxs-lookup"><span data-stu-id="9bf72-126">[How to: Delete Workflows](across-how-to-delete-workflows.md) </span></span>  
 <span data-ttu-id="9bf72-127">[Vaihekuvaus: Ostojen hyväksyntätyönkulun määrittäminen ja käyttäminen](walkthrough-setting-up-and-using-a-purchase-approval-workflow.md) </span><span class="sxs-lookup"><span data-stu-id="9bf72-127">[Walkthrough: Setting Up and Using a Purchase Approval Workflow](walkthrough-setting-up-and-using-a-purchase-approval-workflow.md) </span></span>  
 <span data-ttu-id="9bf72-128">[Työnkulkujen määrittäminen](across-set-up-workflows.md) </span><span class="sxs-lookup"><span data-stu-id="9bf72-128">[Setting Up Workflows](across-set-up-workflows.md) </span></span>  
 <span data-ttu-id="9bf72-129">[Työnkulkujen käyttäminen](across-use-workflows.md) </span><span class="sxs-lookup"><span data-stu-id="9bf72-129">[Using Workflows](across-use-workflows.md) </span></span>  
 [<span data-ttu-id="9bf72-130">Työnkulku</span><span class="sxs-lookup"><span data-stu-id="9bf72-130">Workflow</span></span>](across-workflow.md)   

