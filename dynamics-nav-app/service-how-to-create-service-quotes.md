---
title: Huoltotarjousten luominen
description: "**Huoltotarjous**-ikkunassa voidaan luoda asiakirjoja, joihin annetaan tiedot asiakkaan pyynnöstä tehtävästä huoltonimikkeiden huollosta (korjauksesta tai ylläpidosta). Voit käyttää alustavana huoltotilauksen suunnitelmana huoltotarjousta ja muuntaa tarjouksen sitten huoltotilaukseksi."
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
ms.openlocfilehash: 2b78b8c1d4331aa8825c0d1a198fc83ed85179c8
ms.contentlocale: fi-fi
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-create-service-quotes"></a><span data-ttu-id="37f74-104">Huoltotarjousten luominen</span><span class="sxs-lookup"><span data-stu-id="37f74-104">How to: Create Service Quotes</span></span>
<span data-ttu-id="37f74-105">Huoltotarjoukset voidaan mieltää huoltotilausten pohjaksi.</span><span class="sxs-lookup"><span data-stu-id="37f74-105">You can think of service quotes as the basis for service orders.</span></span> <span data-ttu-id="37f74-106">Ne ovatkin itse asiassa lähes samanlaisia.</span><span class="sxs-lookup"><span data-stu-id="37f74-106">In fact, they are almost identical.</span></span> <span data-ttu-id="37f74-107">Kummassakin on tietoja esimerkiksi asiakkaasta, tilaustyypistä, huollettavista nimikkeistä, laskutus- ja toimitustiedoista sekä tehtävästä huoltotyöstä.</span><span class="sxs-lookup"><span data-stu-id="37f74-107">They both contain information such as who the customer is, the type of order, the item that needs service, billing and shipping information, and information about the actual service work.</span></span>
 
<span data-ttu-id="37f74-108">Voit käyttää huoltotarjousta huoltotilauksen luonnoksena ja muuntaa tarjouksen sitten huoltotilaukseksi.</span><span class="sxs-lookup"><span data-stu-id="37f74-108">You can use a service quote as a preliminary draft for a service order, and then convert the quote to a service order.</span></span>  
  
## <a name="to-create-a-service-quote"></a><span data-ttu-id="37f74-109">Huoltotarjousten luominen</span><span class="sxs-lookup"><span data-stu-id="37f74-109">To create a service quote</span></span>  
1. <span data-ttu-id="37f74-110">Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, kirjoita **Huoltotarjoukset** ja valitse sitten aiheeseen liittyvä linkki.</span><span class="sxs-lookup"><span data-stu-id="37f74-110">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Service Quotes**, and then choose the related link.</span></span>  
2. <span data-ttu-id="37f74-111">Luo uusi huoltotarjous.</span><span class="sxs-lookup"><span data-stu-id="37f74-111">Create a new service quote.</span></span>  
3. <span data-ttu-id="37f74-112">Valitse **Nro**-kenttään</span><span class="sxs-lookup"><span data-stu-id="37f74-112">In the **No.**</span></span> <span data-ttu-id="37f74-113">numero huoltotarjoukselle.</span><span class="sxs-lookup"><span data-stu-id="37f74-113">field, enter a number for the service quote.</span></span> <span data-ttu-id="37f74-114">Vaihtoehtoisesti jos olet määrittänyt huoltotarjouksille numerosarjan **Huoltohallinnon asetukset**-ikkunassa, voit painaa Enter, jolloin ohjelma syöttää seuraavan saatavilla olevan huoltotarjouksen numeron.</span><span class="sxs-lookup"><span data-stu-id="37f74-114">Alternatively, if you have set up a number series for service quotes in the **Service Mgt. Setup** window, you can press Enter to select the next available service quote number.</span></span>  
4. <span data-ttu-id="37f74-115">Syötä **Asiakasnro** -kentässä</span><span class="sxs-lookup"><span data-stu-id="37f74-115">In the **Customer No.**</span></span>  <span data-ttu-id="37f74-116">asiamukainen asiakas luettelosta.</span><span class="sxs-lookup"><span data-stu-id="37f74-116">field, select the relevant customer from the list.</span></span>  

  > [!Note]  
  >  <span data-ttu-id="37f74-117">Ohjelma täyttää automaattisesti asiakkaaseen liittyvät kentät tiedoilla **Asiakas**-kortilta.</span><span class="sxs-lookup"><span data-stu-id="37f74-117">The customer fields are filled in automatically with information from the **Customer** card.</span></span> <span data-ttu-id="37f74-118">Jos asiakkaalla ei ole **asiakkaan** korttia ja asiakasmalli on määritetty, voit luoda asiakkaan huoltotarjouksesta.</span><span class="sxs-lookup"><span data-stu-id="37f74-118">If a **Customer** card does not exist for the customer, and you have set up a customer template, you can create the customer from the service quote.</span></span> <span data-ttu-id="37f74-119">Täytä tarvittavat kentät ja valitse **Luo asiakas** -toiminto.</span><span class="sxs-lookup"><span data-stu-id="37f74-119">Fill in the relevant fields, and then choose the **Create Customer** action.</span></span>  
  
5. <span data-ttu-id="37f74-120">**Huoltohallinnon asetukset** -ikkunan **Pakolliset kentät** -pikavälilehden asetusten mukaan **Huoltotilauksen tyyppi** -kenttä ja **Myyjäkoodi**-kenttä on ehkä täytettävä.</span><span class="sxs-lookup"><span data-stu-id="37f74-120">Depending on the settings on the **Mandatory Fields** FastTab in the **Service Mgt. Setup** window, you may need to fill in the **Service Order Type** field and the **Salesperson Code** field.</span></span>  
6. <span data-ttu-id="37f74-121">Täytä huoltonimikerivit.</span><span class="sxs-lookup"><span data-stu-id="37f74-121">Fill in the service item lines.</span></span>  
7. <span data-ttu-id="37f74-122">Rekisteröi arvioidut kustannukset huoltoriveille</span><span class="sxs-lookup"><span data-stu-id="37f74-122">Register estimated costs on the service lines.</span></span>  
  
## <a name="see-also"></a><span data-ttu-id="37f74-123">Katso myös</span><span class="sxs-lookup"><span data-stu-id="37f74-123">See Also</span></span>  
[<span data-ttu-id="37f74-124">Toimintaohje: Huoltotilausten luominen</span><span class="sxs-lookup"><span data-stu-id="37f74-124">How to: Create Service Orders</span></span>](service-how-to-create-service-orders.md)  
[<span data-ttu-id="37f74-125">Toimintaohje: Huoltotehtävien käsitteleminen</span><span class="sxs-lookup"><span data-stu-id="37f74-125">How to: Work on Service tasks</span></span>](service-how-to-work-on-service-tasks.md)  

 
