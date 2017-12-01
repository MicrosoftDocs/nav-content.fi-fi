---
title: "Tuotannon nimikeperheiden käyttäminen"
description: "Päätehtävä peruskalenterin räätälöimisessä yrityksellesi tai yhdelle sen liiketoimintakumppaneista on syöttää kaikki työskentely- ja ei-työskentelypäivätilan muutokset."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 09/05/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 1dfba8b14019991c95f40ffd5f7fbaed5df414eb
ms.openlocfilehash: 75798af2865a646424a31626ea76baa12a5ee233
ms.contentlocale: fi-fi
ms.lasthandoff: 12/01/2017

---
# <a name="how-to-work-with-production-families"></a><span data-ttu-id="f4831-103">Toimintaohje: Tuotantoperheiden käsitteleminen</span><span class="sxs-lookup"><span data-stu-id="f4831-103">How to: Work with Production Families</span></span>
<span data-ttu-id="f4831-104">Tuoteperhe on ryhmä yksittäisiä nimikkeitä, joiden suhde perustuu niiden tuotantoprosessien samankaltaisuuteen.</span><span class="sxs-lookup"><span data-stu-id="f4831-104">A production family is a group of individual items whose relationship is based on the similarity of their manufacturing processes.</span></span> <span data-ttu-id="f4831-105">Tuoteperheitä muodostamalla joitain nimikkeitä voidaan tuottaa kaksi kertaa tai useammin yhdessä tuotannossa, joka optimoi materiaalinkulutusta.</span><span class="sxs-lookup"><span data-stu-id="f4831-105">By forming production families, some items can be manufactured twice or more in one production, which will optimize material consumption.</span></span>

<span data-ttu-id="f4831-106">Anna **Tuoteperhe**-ikkunan **Määrä**-kentässä määrä, joka tuotetaan, kun koko tuoteperhe on tuotettu kerran.</span><span class="sxs-lookup"><span data-stu-id="f4831-106">In the **Quantity** field in the **Family** window, you enter the quantity that will be produced when the whole family has been manufactured once.</span></span>

## <a name="example"></a><span data-ttu-id="f4831-107">Esimerkki</span><span class="sxs-lookup"><span data-stu-id="f4831-107">Example</span></span>
<span data-ttu-id="f4831-108">Lävistysprosessissa saman nimikkeen neljä kappaletta voidaan tuottaa yhdestä lomakkeesta ja toisen, eri nimikkeen, 10 kappaletta yhtä aikaa.</span><span class="sxs-lookup"><span data-stu-id="f4831-108">In punching processes, four pieces of the same item can be produced from one sheet and 10 pieces of another, different, item at the same time.</span></span> <span data-ttu-id="f4831-109">Lävistyskone lävistää kaikki 14 kappaletta saman työvaiheen aikana.</span><span class="sxs-lookup"><span data-stu-id="f4831-109">The punching machine will punch all 14 pieces in one step.</span></span>

<span data-ttu-id="f4831-110">Tuoteperheiden muodostamisella vähennetään hukkatavaran määrää, koska se, mikä olisi tavallisesti hylättyä tavaraa isojen kappaleiden tuotannossa, käytetäänkin pienempien nimikkeiden tuottamisessa.</span><span class="sxs-lookup"><span data-stu-id="f4831-110">Forming production families reduces the scrap quantity because what would normally be leftover scrap, when producing big pieces, will be used instead to produce small items.</span></span>

## <a name="to-set-up-a-production-family"></a><span data-ttu-id="f4831-111">Tuotantoperheen määrittäminen</span><span class="sxs-lookup"><span data-stu-id="f4831-111">To set up a production family</span></span>
1. <span data-ttu-id="f4831-112">Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, anna **Tuoteperheet** ja valitse sitten aiheeseen liittyvä linkki.</span><span class="sxs-lookup"><span data-stu-id="f4831-112">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Families**, and then choose the related link.</span></span>
2. <span data-ttu-id="f4831-113">Täytä tarvittavat kentät.</span><span class="sxs-lookup"><span data-stu-id="f4831-113">Fill in the fields as necessary.</span></span> [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]

## <a name="to-produce-based-on-a-production-familily"></a><span data-ttu-id="f4831-114">Tuotanto tuoteperheen perusteella</span><span class="sxs-lookup"><span data-stu-id="f4831-114">To produce based on a production familily</span></span>
1. <span data-ttu-id="f4831-115">Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, kirjoita **Sitovasti suunn. tuotantotil.** ja valitse sitten aiheeseen liittyvä linkki.</span><span class="sxs-lookup"><span data-stu-id="f4831-115">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Firm Planned Prod. Orders**, and then choose the related link.</span></span>
2. <span data-ttu-id="f4831-116">Luo uusi tuotantotilaus.</span><span class="sxs-lookup"><span data-stu-id="f4831-116">Create a new production order.</span></span> <span data-ttu-id="f4831-117">Lisätietoja on kohdassa [Toimintaohje: Tuotantotilausten luominen](production-how-to-create-production-orders.md).</span><span class="sxs-lookup"><span data-stu-id="f4831-117">For more information, see [How to: Create Production orders](production-how-to-create-production-orders.md).</span></span>
3. <span data-ttu-id="f4831-118">Valitse **Lähdetyyppi**-kentässä **Tuoteperhe**.</span><span class="sxs-lookup"><span data-stu-id="f4831-118">In the **Source Type** field, select **Family**.</span></span>  
4. <span data-ttu-id="f4831-119">Valitse **Lähdenro** -kentässä käsiteltävä tuotantoperhe.</span><span class="sxs-lookup"><span data-stu-id="f4831-119">In the **Source No.** field, select the relevant production family.</span></span>

## <a name="see-also"></a><span data-ttu-id="f4831-120">Katso myös</span><span class="sxs-lookup"><span data-stu-id="f4831-120">See Also</span></span>
[<span data-ttu-id="f4831-121">Toimintaohje: Uusien tuotannon tuoterakenteiden luominen</span><span class="sxs-lookup"><span data-stu-id="f4831-121">How to: Create Production BOMs</span></span>](production-how-to-create-production-boms.md)  
[<span data-ttu-id="f4831-122">Tuotannon määrittäminen</span><span class="sxs-lookup"><span data-stu-id="f4831-122">Setting Up Manufacturing</span></span>](production-configure-production-processes.md)  
<span data-ttu-id="f4831-123">[Tuotanto](production-manage-manufacturing.md)  </span><span class="sxs-lookup"><span data-stu-id="f4831-123">[Manufacturing](production-manage-manufacturing.md)  </span></span>  
<span data-ttu-id="f4831-124">[Suunnittelu](production-planning.md) </span><span class="sxs-lookup"><span data-stu-id="f4831-124">[Planning](production-planning.md) </span></span>  
[<span data-ttu-id="f4831-125">Vaihto-omaisuus</span><span class="sxs-lookup"><span data-stu-id="f4831-125">Inventory</span></span>](inventory-manage-inventory.md)  
[<span data-ttu-id="f4831-126">Osto</span><span class="sxs-lookup"><span data-stu-id="f4831-126">Purchasing</span></span>](purchasing-manage-purchasing.md)  
<span data-ttu-id="f4831-127">[[!INCLUDE[d365fin](includes/d365fin_md.md)] -ohjelman käyttäminen](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="f4831-127">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>

