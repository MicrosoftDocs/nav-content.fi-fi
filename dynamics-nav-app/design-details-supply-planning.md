---
title: Rakennetiedot - tarjonnan suunnittelu
description: "Tässä ohjeaiheessa on yleiskatsaus [!INCLUDE[d365fin](Includes/d365fin_md.MD)] -ohjelman toimitusten suunnitteluominaisuuksissa käytettäviin käsitteisiin ja periaatteisiin."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: design, supply, planning, reordering, replenishment
ms.date: 07/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: a3a5197ba727404ce7e6dea5ee529ced6dcfa68e
ms.contentlocale: fi-fi
ms.lasthandoff: 10/16/2017

---
# <a name="design-details-supply-planning"></a><span data-ttu-id="ef95e-103">Rakennetiedot: tarjonnan suunnittelu</span><span class="sxs-lookup"><span data-stu-id="ef95e-103">Design Details: Supply Planning</span></span>
<span data-ttu-id="ef95e-104">Tässä dokumentaatiossa on yksityiskohtaisia teknisiä tietoja [!INCLUDE[d365fin](includes/d365fin_md.md)] -ohjelman tarjonnan suunnittelun toimintojen kanssa käytettävistä konsepteista ja periaatteista.</span><span class="sxs-lookup"><span data-stu-id="ef95e-104">This documentation provides detailed technical insight to the concepts and principles that are used within the Supply Planning features in [!INCLUDE[d365fin](includes/d365fin_md.md)].</span></span>  

<span data-ttu-id="ef95e-105">Se kuvaa, miten suunnittelujärjestelmä toimii, ja kuinka algoritmeja voidaan muuttaa eri ympäristöjen suunnitteluvaatimuksia vastaaviksi.</span><span class="sxs-lookup"><span data-stu-id="ef95e-105">It explains how the planning system works and how to adjust the algorithms to meet planning requirements in different environments.</span></span> <span data-ttu-id="ef95e-106">Se esittelee ensin keskitetyn ratkaisun käsitteet ja kuvaa sitten keskeisen mekanismin eli tarjonnan täsmäytyksen logiikan ennen sitä, kuinka varaston suunnittelu suoritetaan uusintatilaustapojen avulla.</span><span class="sxs-lookup"><span data-stu-id="ef95e-106">It first introduces central solution concepts and then describes the logic of the central mechanism, supply balancing, before proceeding to explain how inventory planning is performed with the use of reordering policies.</span></span>  

## <a name="in-this-section"></a><span data-ttu-id="ef95e-107">Tämän osan sisältö</span><span class="sxs-lookup"><span data-stu-id="ef95e-107">In This Section</span></span>  
[<span data-ttu-id="ef95e-108">Rakennetiedot: Suunnittelujärjestelmän keskeiset käsitteet</span><span class="sxs-lookup"><span data-stu-id="ef95e-108">Design Details: Central Concepts of the Planning System</span></span>](design-details-central-concepts-of-the-planning-system.md)  
[<span data-ttu-id="ef95e-109">Rakennetiedot: varaus, tilauksen seuranta ja toimenpiteiden viestitys</span><span class="sxs-lookup"><span data-stu-id="ef95e-109">Design Details: Reservation, Order Tracking, and Action Messaging</span></span>](design-details-reservation-order-tracking-and-action-messaging.md)  
[<span data-ttu-id="ef95e-110">Rakennetiedot: kysynnän ja tarjonnan täsmäytys</span><span class="sxs-lookup"><span data-stu-id="ef95e-110">Design Details: Balancing Demand and Supply</span></span>](design-details-balancing-demand-and-supply.md)  
[<span data-ttu-id="ef95e-111">Rakennetiedot: uusintatilauskäytäntöjen käsittely</span><span class="sxs-lookup"><span data-stu-id="ef95e-111">Design Details: Handling Reordering Policies</span></span>](design-details-handling-reordering-policies.md)  
[<span data-ttu-id="ef95e-112">Rakennetiedot: suunnittelun parametrit</span><span class="sxs-lookup"><span data-stu-id="ef95e-112">Design Details: Planning Parameters</span></span>](design-details-planning-parameters.md)  
[<span data-ttu-id="ef95e-113">Rakennetiedot: suunnittelun kohdistustaulukko</span><span class="sxs-lookup"><span data-stu-id="ef95e-113">Design Details: Planning Assignment Table</span></span>](design-details-planning-assignment-table.md)  
[<span data-ttu-id="ef95e-114">Rakennetiedot: kysyntä tyhjä-sijainnissa</span><span class="sxs-lookup"><span data-stu-id="ef95e-114">Design Details: Demand at Blank Location</span></span>](design-details-demand-at-blank-location.md)  
[<span data-ttu-id="ef95e-115">Rakennetiedot: siirrot suunnittelussa</span><span class="sxs-lookup"><span data-stu-id="ef95e-115">Design Details: Transfers in Planning</span></span>](design-details-transfers-in-planning.md)

