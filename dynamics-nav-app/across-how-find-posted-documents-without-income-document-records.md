---
title: 'Toimintaohje: Sellaisten kirjattujen asiakirjojen etsiminen, joilla ei ole saapuvia asiakirjatietueita'
author: SorenGP
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 6b60b1344a1e18ad91863046110df880f75f7c04
ms.openlocfilehash: eca38d238361a9ac50aac117199fa97fbba4374f
ms.contentlocale: fi-fi
ms.lasthandoff: 07/19/2017

---

# <a name="how-to-find-posted-documents-without-incoming-document-records"></a><span data-ttu-id="b6481-102">Toimintaohje: Sellaisten kirjattujen asiakirjojen etsiminen, joilla ei ole saapuvia asiakirjatietueita</span><span class="sxs-lookup"><span data-stu-id="b6481-102">How to: Find Posted Documents without Incoming Document Records</span></span>
<span data-ttu-id="b6481-103">**Tilikartta**- ja **Pääkirjanpidon tapahtumat** -ikkunan hakutoiminnon avulla voit etsiä pääkirjanpidon tapahtumia kirjatuille osto- ja myyntiasiakirjoille, joilla ei ole saapuvia asiakirjatietueita. Tämän jälkeen voit keskitetysti muodostaa yhteyden olemassa oleviin tietueisiin tai luoda uusia tietueita ja niihin liittyviä asiakirjatiedostoja.</span><span class="sxs-lookup"><span data-stu-id="b6481-103">From the **Chart of Accounts** and **General Ledger Entries** windows, you can use a search function to find general ledger entries for posted purchase and sales documents that do not have incoming document records and then centrally link to existing records or create new ones with attached document files.</span></span>

## <a name="to-find-posted-documents-without-incoming-document-records"></a><span data-ttu-id="b6481-104">Sellaisten kirjattujen asiakirjojen etsiminen, joilla ei ole saapuvia asiakirjatietueita</span><span class="sxs-lookup"><span data-stu-id="b6481-104">To find posted documents without incoming document records</span></span>
1. <span data-ttu-id="b6481-105">Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Tilikartta** ja valitse sitten aiheeseen liittyvä linkki.</span><span class="sxs-lookup"><span data-stu-id="b6481-105">In the top right corner, choose the **Search for Page or Report** icon, enter **Chart of Accounts**, and then choose the related link.</span></span>
2. <span data-ttu-id="b6481-106">Valitse pääkirjanpidon tapahtumien KP-tilin rivi, kun haluat tarkastella kyseisen rivin kirjattuja osto- ja myyntiasiakirjoja, joilla ei ole saapuvia asiakirjatietueita. Valitse sitten **Kirjatut asiakirjat ilman saapuvaa asiakirjaa** -toiminto.</span><span class="sxs-lookup"><span data-stu-id="b6481-106">Select a line for a G/L account for whose general ledger entries you want to see posted purchase and sales documents without incoming document records, and then choose the **Posted Documents without Incoming Document** action.</span></span>
3. <span data-ttu-id="b6481-107">Vaihtoehtoisesti voit valita **Tapahtumakirjaukset**-toiminnon.</span><span class="sxs-lookup"><span data-stu-id="b6481-107">Alternatively, choose the **Ledger Entries** action.</span></span>
4. <span data-ttu-id="b6481-108">Valitse **Pääkirjanpidon tapahtumat** -ikkunassa **Kirjatut asiakirjat ilman saapuvaa asiakirjaa** -toiminto.</span><span class="sxs-lookup"><span data-stu-id="b6481-108">In the **General Ledger Entries** window, choose the **Posted Documents without Incoming Documents** action.</span></span>

<span data-ttu-id="b6481-109">Avautuvassa **Kirjatut asiakirjat ilman saapuvaa asiakirjaa** -ikkunassa näkyvät kirjatut osto- ja myyntiasiakirjat, joilla ei ole saapuvia asiakirjatietueita. Ikkunan tiedot koskevat määrittämäsi KP-tilin pääkirjanpidon tapahtumia.</span><span class="sxs-lookup"><span data-stu-id="b6481-109">The **Posted Documents without Incoming Document** window opens showing posted purchase and sales documents without incoming document records represented by general ledger entries on the G/L account that you opened the window for.</span></span> <span data-ttu-id="b6481-110">Ikkunassa näkyy enintään 1 000 riviä.</span><span class="sxs-lookup"><span data-stu-id="b6481-110">The window can show a maximum of 1000 lines.</span></span> <span data-ttu-id="b6481-111">Oletusarvon mukaan **Pvm-suodatus**-kentässä on suodatin, joka rajoittaa rivit tapahtumiin, joiden kirjauspäivämäärät ulottuvat tilikauden alusta käsittelypäivämäärään.</span><span class="sxs-lookup"><span data-stu-id="b6481-111">By default, the **Date Filter** field therefore contains a filter that limits the lines to entries with posting dates from the beginning of the accounting period to the work date.</span></span>

## <a name="to-connect-found-documents-to-existing-incoming-document-records"></a><span data-ttu-id="b6481-112">Löydettyjen asiakirjojen yhdistäminen olemassa oleviin saapuviin asiakirjatietueisiin</span><span class="sxs-lookup"><span data-stu-id="b6481-112">To connect found documents to existing incoming document records</span></span>
1. <span data-ttu-id="b6481-113">Valitse **Kirjatut asiakirjat ilman saapuvaa asiakirjaa** -ikkunassa rivi kirjatulle asiakirjalle, jonka haluat yhdistää olemassa olevaan saapuvaan asiakirjatietueeseen. Valitse sitten **Valitse saapuva asiakirja** -toiminto.</span><span class="sxs-lookup"><span data-stu-id="b6481-113">In the **Posted Documents without Incoming Document** window, select the line for a posted document that you want to connect to an existing incoming document record, and then choose the **Select Incoming Document** action.</span></span>
2. <span data-ttu-id="b6481-114">Valitse **Saapuvat asiakirjat** -ikkunassa saapuva asiakirjatietue, jonka haluat yhdistää löydettyyn kirjattuun asiakirjaan ja valitse sitten **OK**-painike.</span><span class="sxs-lookup"><span data-stu-id="b6481-114">In the **Incoming Documents** window, select the incoming document record that you want to connect to posted document found, and then choose the **OK** button.</span></span>
3. <span data-ttu-id="b6481-115">Valittu saapuva asiakirjatietue on nyt yhdistetty **Kirjatut asiakirjat ilman saapuvaa asiakirjaa** -ikkunassa kirjattuun asiakirjaan, kuten **Saapuvat asiakirjatiedostot** -tietoruudusta voidaan nähdä.</span><span class="sxs-lookup"><span data-stu-id="b6481-115">In the **Posted Documents without Incoming Document** window, the selected incoming document record is now connected to the posted document, as you can see in the **Incoming Document Files** FactBox.</span></span>

<span data-ttu-id="b6481-116">Jos **Saapuvat asiakirjat** -ikkunassa ei ole asiaankuuluvaa saapuvaa asiakirjatietuetta, voit luoda sen.</span><span class="sxs-lookup"><span data-stu-id="b6481-116">If a relevant incoming document record does not exist in the **Incoming Documents** window, then you can create it.</span></span> <span data-ttu-id="b6481-117">Lisätietoja on kohdassa [Toimintaohje: Saapuvien asiakirjatietueiden luominen](across-how-create-income-document-records.md).</span><span class="sxs-lookup"><span data-stu-id="b6481-117">For more information, see [How to: Create Incoming Document Records](across-how-create-income-document-records.md).</span></span>

## <a name="see-also"></a><span data-ttu-id="b6481-118">Katso myös</span><span class="sxs-lookup"><span data-stu-id="b6481-118">See Also</span></span>  
[<span data-ttu-id="b6481-119">Saapuvien asiakirjojen käsitteleminen</span><span class="sxs-lookup"><span data-stu-id="b6481-119">Process Incoming Documents</span></span>](across-process-income-documents.md)  
[<span data-ttu-id="b6481-120">Saapuvat asiakirjat</span><span class="sxs-lookup"><span data-stu-id="b6481-120">Incoming Documents</span></span>](across-income-documents.md)  
[<span data-ttu-id="b6481-121">Ostojen hallinta</span><span class="sxs-lookup"><span data-stu-id="b6481-121">Manage Purchasing</span></span>](purchasing-manage-purchasing.md)  
[<span data-ttu-id="b6481-122">Dynamics NAV -ohjelman käyttäminen</span><span class="sxs-lookup"><span data-stu-id="b6481-122">Work With Dynamics NAV</span></span>](ui-work-product.md)

