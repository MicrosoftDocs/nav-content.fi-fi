---
title: "Rakennetiedot - kysyntä ja tarjonta"
description: "Tässä ohjeaiheessa esitellään kysyntä-termi, jota käytetään kaikenlaiseen bruttokysyntään, kuten myyntitilaukseen ja komponenttitarpeeseen tuotantotilauksesta."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: design, demand, supply, inventory, planning
ms.date: 07/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 1dfba8b14019991c95f40ffd5f7fbaed5df414eb
ms.openlocfilehash: 02ed5d4d144e3c56f3e7e1a0bac212da777b8dd3
ms.contentlocale: fi-fi
ms.lasthandoff: 12/01/2017

---
# <a name="design-details-demand-and-supply"></a><span data-ttu-id="249e4-103">Rakennetiedot: kysyntä ja tarjonta</span><span class="sxs-lookup"><span data-stu-id="249e4-103">Design Details: Demand and Supply</span></span>
<span data-ttu-id="249e4-104">Kysyntä on yleinen termi, jota käytetään kaikenlaiseen bruttokysyntään, kuten myyntitilaukseen ja komponenttitarpeeseen tuotantotilauksesta.</span><span class="sxs-lookup"><span data-stu-id="249e4-104">Demand is the common term used for any kind of gross demand, such as a sales order and component need from a production order.</span></span> <span data-ttu-id="249e4-105">Lisäksi ohjelma sallii teknisemmät kysyntätyypit, kuten negatiivisen varaston ja ostopalautukset.</span><span class="sxs-lookup"><span data-stu-id="249e4-105">In addition, the program allows more technical types of demand, such as negative inventory and purchase returns.</span></span>  
  
<span data-ttu-id="249e4-106">Tarjonta on yleinen termi, jota käytetään mille tahansa positiiviselle tai tulevalle määrälle, kuten varasto, ostot, kokoonpano, tuotanto tai tulevat siirrot.</span><span class="sxs-lookup"><span data-stu-id="249e4-106">Supply is the common term used for any kind of positive or inbound quantity, such as inventory, purchases, assembly, production, or inbound transfers.</span></span> <span data-ttu-id="249e4-107">Lisäksi myyntipalautus voi myös kuvata tarjontaa.</span><span class="sxs-lookup"><span data-stu-id="249e4-107">In addition, a sales return may also represent supply.</span></span>  
  
<span data-ttu-id="249e4-108">Voit lajitella useita kysynnän ja tarjonnan lähteitä, kun suunnittelujärjestelmä järjestää ne kahdelle aikajanalle, joita kutsutaan varastoprofiileiksi.</span><span class="sxs-lookup"><span data-stu-id="249e4-108">To sort out the many sources of demand and supply, the planning system organizes them on two time lines called inventory profiles.</span></span> <span data-ttu-id="249e4-109">Yksi profiili sisältää kysyntätapahtumat ja toinen sisältää vastaavat tarjontatapahtumat.</span><span class="sxs-lookup"><span data-stu-id="249e4-109">One profile holds demand events, and the other holds the corresponding supply events.</span></span> <span data-ttu-id="249e4-110">Kukin tapahtuma edustaa yhtä tilausverkon kokonaisuutta, kuten myyntitilausriviä, nimiketapahtumaa tai tuotantotilausriviä.</span><span class="sxs-lookup"><span data-stu-id="249e4-110">Each event represents one order network entity, such as a sales order line, an item ledger entry, or a production order line.</span></span>  
  
<span data-ttu-id="249e4-111">Kun varaston profiilit ladataan, erilaiset kysyntä- ja tarjontajoukot täsmäytetään listatut tavoitteet täyttävän tarjontasuunnitelman tuotoksen saamiseksi.</span><span class="sxs-lookup"><span data-stu-id="249e4-111">When inventory profiles are loaded, the different demand-supply sets are balanced to output a supply plan that fulfills the listed goals.</span></span>  
  
<span data-ttu-id="249e4-112">Suunnitteluparametrit ja varastotasot ovat muita kysynnän ja tarjonnan tyyppejä, jotka käyvät läpi integroidun täsmäytyksen varastonimikkeiden täydentämiseksi.</span><span class="sxs-lookup"><span data-stu-id="249e4-112">Planning parameters and inventory levels are other types of demand and supply respectively, which undergo integrated balancing to replenish stock items.</span></span> <span data-ttu-id="249e4-113">Lisätietoja on kohdassa [Rakennetiedot: uusintatilauskäytäntöjen käsittely](design-details-handling-reordering-policies.md).</span><span class="sxs-lookup"><span data-stu-id="249e4-113">For more information, see [Design Details: Handling Reordering Policies](design-details-handling-reordering-policies.md).</span></span>  
  
## <a name="see-also"></a><span data-ttu-id="249e4-114">Katso myös</span><span class="sxs-lookup"><span data-stu-id="249e4-114">See Also</span></span>  
<span data-ttu-id="249e4-115">[Rakennetiedot: kysynnän ja tarjonnan täsmäytys](design-details-balancing-demand-and-supply.md) </span><span class="sxs-lookup"><span data-stu-id="249e4-115">[Design Details: Balancing Demand and Supply](design-details-balancing-demand-and-supply.md) </span></span>  
<span data-ttu-id="249e4-116">[Rakennetiedot: suunnittelujärjestelmän keskeiset käsitteet](design-details-central-concepts-of-the-planning-system.md) </span><span class="sxs-lookup"><span data-stu-id="249e4-116">[Design Details: Central Concepts of the Planning System](design-details-central-concepts-of-the-planning-system.md) </span></span>  
[<span data-ttu-id="249e4-117">Rakennetiedot: Tarjonnan suunnittelu</span><span class="sxs-lookup"><span data-stu-id="249e4-117">Design Details: Supply Planning</span></span>](design-details-supply-planning.md)
