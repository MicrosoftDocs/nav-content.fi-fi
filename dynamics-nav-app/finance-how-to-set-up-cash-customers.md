---
title: "Käteisasiakkaiden määrittäminen"
description: "Tässä ohjeaiheessa käsitellään vaiheet, joilla käteisellä maksava asiakas määritetään."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 08/11/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: dca1e2b58d22a9d27766a731a085278f1200b570
ms.contentlocale: fi-fi
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-set-up-cash-customers"></a><span data-ttu-id="02e25-103">Käteisasiakkaiden määrittäminen</span><span class="sxs-lookup"><span data-stu-id="02e25-103">How to: Set Up Cash Customers</span></span>
<span data-ttu-id="02e25-104">Laskua ei voi luoda ilman asiakasnumeroa.</span><span class="sxs-lookup"><span data-stu-id="02e25-104">You cannot create an invoice without a customer number.</span></span> <span data-ttu-id="02e25-105">Näin on, vaikka teet käteismyynnin, eikä asiakastilille ole mitään tallennettavaa.</span><span class="sxs-lookup"><span data-stu-id="02e25-105">This is true, even if you make a cash sale and do not have anything to record in a customer account.</span></span>  

## <a name="to-set-up-a-cash-customer"></a><span data-ttu-id="02e25-106">Käteisasiakkaiden määrittäminen</span><span class="sxs-lookup"><span data-stu-id="02e25-106">To set up a cash customer</span></span>  
1.  <span data-ttu-id="02e25-107">Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, kirjoita **Asiakas** ja valitse sitten aiheeseen liittyvä linkki.</span><span class="sxs-lookup"><span data-stu-id="02e25-107">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Customer**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="02e25-108">Luo uusi **Asiakkaan** kortti.</span><span class="sxs-lookup"><span data-stu-id="02e25-108">Create a new **Customer** card.</span></span> <span data-ttu-id="02e25-109">Lisätietoja on kohdassa [Toimintaohje: Uusien asiakkaiden rekisteröiminen](sales-how-register-new-customers.md).</span><span class="sxs-lookup"><span data-stu-id="02e25-109">For more information, see [How to: Register New Customers](sales-how-register-new-customers.md).</span></span>
3.  <span data-ttu-id="02e25-110">Valitse **Nro**-kenttään</span><span class="sxs-lookup"><span data-stu-id="02e25-110">In the **No.**</span></span> <span data-ttu-id="02e25-111">esimerkiksi **Käteismyynti**.</span><span class="sxs-lookup"><span data-stu-id="02e25-111">field, enter **Cash**, for example.</span></span>  
4.  <span data-ttu-id="02e25-112">Syötä **Nimi**-kenttään esimerkiksi **Käteismyynti**.</span><span class="sxs-lookup"><span data-stu-id="02e25-112">In the **Name** field, enter **Cash Sale**, for example.</span></span>  
5.  <span data-ttu-id="02e25-113">Täytä **Laskutus**-pikavälilehden **Asiakkaan kirjausryhmä**- ja **Ylein. liiketoim. kirjausryhmä** -kentät.</span><span class="sxs-lookup"><span data-stu-id="02e25-113">On the **Invoicing** FastTab, fill in the **Customer Posting Group** and the **Gen. Bus. Posting Group** fields.</span></span>  

 <span data-ttu-id="02e25-114">Nyt asiakas on määritetty, ja se sisältää riittävästi tietoa laskutusta varten.</span><span class="sxs-lookup"><span data-stu-id="02e25-114">Now you have set up a customer that contains sufficient information for invoicing.</span></span>  

> [!NOTE]  
>  <span data-ttu-id="02e25-115">Olet voinut valita kirjausryhmän, jota on käytetty myös kotimaisiin luottomyynteihin.</span><span class="sxs-lookup"><span data-stu-id="02e25-115">You may have chosen a posting group that is also used for domestic credit sales.</span></span> <span data-ttu-id="02e25-116">Jos haluat ylläpitää erillistä tietoa käteismyynneistä esimerkiksi erityisellä myynti- tai myyntisaamistilillä, voit määrittää tätä varten ylimääräisen kirjausryhmän.</span><span class="sxs-lookup"><span data-stu-id="02e25-116">If you want to maintain separate data on cash sales, for example, with a special sales or receivables account, you can set up an extra posting group for this purpose.</span></span>  
>   
>  <span data-ttu-id="02e25-117">Myyntisaamistilille täytyy syöttää numero kirjausryhmää varten, vaikka tilin saldo on aina 0 laskun kirjaamisen jälkeen.</span><span class="sxs-lookup"><span data-stu-id="02e25-117">You must enter a number for a receivables account for the posting group, even though the balance in this account will always be 0 after you post an invoice.</span></span>  

## <a name="see-also"></a><span data-ttu-id="02e25-118">Katso myös</span><span class="sxs-lookup"><span data-stu-id="02e25-118">See Also</span></span>
[<span data-ttu-id="02e25-119">Myyntisaamisten hallinta</span><span class="sxs-lookup"><span data-stu-id="02e25-119">Managing Receivables</span></span>](receivables-manage-receivables.md)  
<span data-ttu-id="02e25-120">[Toimintaohje: Uusien asiakkaiden rekisteröiminen](sales-how-register-new-customers.md)  </span><span class="sxs-lookup"><span data-stu-id="02e25-120">[How to: Register New Customers](sales-how-register-new-customers.md)  </span></span>  
[<span data-ttu-id="02e25-121">Rahoitus</span><span class="sxs-lookup"><span data-stu-id="02e25-121">Finance</span></span>](finance.md)  


