---
title: "Kontaktiyritysten toimialaryhmien määrittäminen"
description: "Tässä ohjeaiheessa kerrotaan, miten toimialaryhmä määritetään ja miten sille sitten määritetään kontaktiryhmä, kuten vähittäistavarakauppa tai autoteollisuus."
documentationcenter: 
author: jswymer
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: relationship, prospect
ms.date: 06/06/2017
ms.author: jswymer
ms.translationtype: HT
ms.sourcegitcommit: 1dfba8b14019991c95f40ffd5f7fbaed5df414eb
ms.openlocfilehash: 303b619c4188a1b74a9c325c3458e244b364cd37
ms.contentlocale: fi-fi
ms.lasthandoff: 12/01/2017

---
# <a name="how-to-set-up-industry-groups-for-contact-companies"></a><span data-ttu-id="017c0-103">Toimintaohje: Toimialaryhmien määrittäminen kontaktiyrityksille</span><span class="sxs-lookup"><span data-stu-id="017c0-103">How to: Set Up Industry Groups for Contact Companies</span></span>
<span data-ttu-id="017c0-104">Toimialaryhmien avulla osoitetaan, minkä tyyppiseen toimialaryhmään (esimerkiksi vähittäistavarakauppa ja autoteollisuus) kontaktit kuuluvat.</span><span class="sxs-lookup"><span data-stu-id="017c0-104">You use industry groups to indicate the type of industry to which your contacts belong, for example, the retail industry or the automobile industry.</span></span>

<span data-ttu-id="017c0-105">Kontaktien toimialaryhmien käyttäminen on kaksivaiheinen prosessi.</span><span class="sxs-lookup"><span data-stu-id="017c0-105">Using industry groups on contacts is a two-step process.</span></span> <span data-ttu-id="017c0-106">Ensin määritetään toimialaryhmän koodi.</span><span class="sxs-lookup"><span data-stu-id="017c0-106">First, you define the industry group code.</span></span> <span data-ttu-id="017c0-107">Tämä vaihe suoritetaan vain kerran jokaiselle toimialaryhmälle.</span><span class="sxs-lookup"><span data-stu-id="017c0-107">You only have to perform this step one time for each industry group.</span></span> <span data-ttu-id="017c0-108">Kun toimialaryhmän koodi on määritetty, voit aloittaa koodin liittämisen kontaktiyrityksille.</span><span class="sxs-lookup"><span data-stu-id="017c0-108">Once you have an industry group code, you can start to assign the code to contact companies.</span></span>

> [!NOTE]  
>   <span data-ttu-id="017c0-109">Jos aiot synkronisoida kontaktisi ohjelman muissa osissa olevien toimittajien, asiakkaiden tai pankkitilien kanssa, haluat ehkä määrittää niille liikesuhteen.</span><span class="sxs-lookup"><span data-stu-id="017c0-109">If you plan to synchronize your contacts with vendors, customers, or bank accounts in other parts of the application, you may want to set up a business relation for them.</span></span>

## <a name="to-define-an-industry-group-code"></a><span data-ttu-id="017c0-110">Toimialaryhmän koodin määrittäminen</span><span class="sxs-lookup"><span data-stu-id="017c0-110">To define an industry group code</span></span>
<span data-ttu-id="017c0-111">Toimialaryhmän koodi määrittää ryhmän tyypin tai luokan, joka voi olla esimerkiksi mainonnalle MAINOS tai televisiolle ja radiolle TIED.VÄL.</span><span class="sxs-lookup"><span data-stu-id="017c0-111">The industry group code defines the type or category of the group, such as ADVERT for advertising, or PRESS, for TV and radio.</span></span> <span data-ttu-id="017c0-112">Toimialaryhmän koodeja voi olla useita.</span><span class="sxs-lookup"><span data-stu-id="017c0-112">You can have several industry group codes.</span></span> <span data-ttu-id="017c0-113">Voit määrittää toimialaryhmät **Toimialaryhmät**-ikkunan avulla.</span><span class="sxs-lookup"><span data-stu-id="017c0-113">To define the industry groups, you use the **Industry Groups** window.</span></span>

1. <span data-ttu-id="017c0-114">Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, kirjoita **Toimialaryhmät** ja valitse sitten aiheeseen liittyvä linkki.</span><span class="sxs-lookup"><span data-stu-id="017c0-114">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Industry Groups**, and then choose the related link.</span></span>
2. <span data-ttu-id="017c0-115">Valitse **Uusi**-toiminto. Täytä sitten koodi ja kuvaus.</span><span class="sxs-lookup"><span data-stu-id="017c0-115">Choose the **New** action, and fill in a code and description.</span></span> <span data-ttu-id="017c0-116">Koodi voi olla enintään 11 merkkiä pitkä. Se voi sisältää numeroita ja kirjaimia.</span><span class="sxs-lookup"><span data-stu-id="017c0-116">The code can be a maximum of 11 characters, and can be any combination of numbers and letters.</span></span>

## <span data-ttu-id="017c0-117"><a name="AssignIndustryGroupContact"></a> Toimialaryhmien määrittäminen kontaktille</span><span class="sxs-lookup"><span data-stu-id="017c0-117"><a name="AssignIndustryGroupContact"></a> To assign industry groups to a contact</span></span>
<span data-ttu-id="017c0-118">Toimialaryhmiä ei voi liittää kontaktihenkilöön, vaan ainoastaan yrityksiin.</span><span class="sxs-lookup"><span data-stu-id="017c0-118">You cannot assign industry groups to a contact person - only companies.</span></span>

1. <span data-ttu-id="017c0-119">Avaa kontakti.</span><span class="sxs-lookup"><span data-stu-id="017c0-119">Open the contact.</span></span>
2. <span data-ttu-id="017c0-120">Valitse **Yritys**-toiminto ja sitten **Toimialaryhmät**-toiminto.</span><span class="sxs-lookup"><span data-stu-id="017c0-120">Choose the **Company** action, and then the **Industry Groups** action.</span></span> <span data-ttu-id="017c0-121">Näyttöön tulee **Kontaktin toimialaryhmät** -ikkuna.</span><span class="sxs-lookup"><span data-stu-id="017c0-121">The **Contact Industry Groups** window opens.</span></span>
3. <span data-ttu-id="017c0-122">Valitse **Toimialaryhmien koodi** -kentässä toimialaryhmät, jotka haluat liittää.</span><span class="sxs-lookup"><span data-stu-id="017c0-122">In the **Industry Groups Code** field, select the industry groups you want to assign.</span></span>

<span data-ttu-id="017c0-123">Toista nämä vaiheet ja luo niin monta toimialaryhmää kuin haluat.</span><span class="sxs-lookup"><span data-stu-id="017c0-123">Repeat these steps to assign as many industry groups as you want.</span></span> <span data-ttu-id="017c0-124">Voit luoda samaan tapaan toimialaryhmiä kontaktiluettelosta.</span><span class="sxs-lookup"><span data-stu-id="017c0-124">You can also assign industry groups from the contact list by following the same procedure.</span></span>

<span data-ttu-id="017c0-125">Kontaktille määritettyjen toimialaryhmien lukumäärä näkyy **Kontakti**-ikkunan **Segmentointi**-osan **Toimialaryhmien lkm** -kentässä.</span><span class="sxs-lookup"><span data-stu-id="017c0-125">The number of industry groups that you have assigned to the contact is displayed in the **No. of Industry Groups** field in the **Segmentation** section in the **Contact** window.</span></span>

<span data-ttu-id="017c0-126">Kun olet liittänyt toimialaryhmiä kontakteihisi, voit käyttää näitä tietoja valitessasi kontakteja segmentteihisi.</span><span class="sxs-lookup"><span data-stu-id="017c0-126">After you have assigned industry groups to your contacts, you can use this information to select contacts for your segments.</span></span> <span data-ttu-id="017c0-127">Lisätietoja on ohjeaiheessa [Toimintaohje: Kontaktien lisääminen segmentteihin](marketing-add-contact-segment.md).</span><span class="sxs-lookup"><span data-stu-id="017c0-127">For more information, see [How to: Add Contacts to Segments](marketing-add-contact-segment.md).</span></span>

## <a name="see-also"></a><span data-ttu-id="017c0-128">Katso myös</span><span class="sxs-lookup"><span data-stu-id="017c0-128">See Also</span></span>
[<span data-ttu-id="017c0-129">Kontaktiyrityksen luominen</span><span class="sxs-lookup"><span data-stu-id="017c0-129">Creating Contact Companies</span></span>](marketing-create-contact-companies.md)  
<span data-ttu-id="017c0-130">[[!INCLUDE[d365fin](includes/d365fin_md.md)] -ohjelman käyttäminen](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="017c0-130">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>

