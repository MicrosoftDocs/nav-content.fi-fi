---
title: "Toimintaohje: Saapuvien asiakirjatietueiden yhdistäminen ja yhdistämisen poistaminen asiakirjoista ja tapahtumista"
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
ms.openlocfilehash: 1c3a0b07d9ac8e3fbd111583acf7e6f378d7644a
ms.contentlocale: fi-fi
ms.lasthandoff: 07/19/2017

---

# <a name="how-to-connect-and-disconnect-incoming-document-records-from-documents-and-entries"></a><span data-ttu-id="6b07c-102">Toimintaohje: Saapuvien asiakirjatietueiden yhdistäminen ja yhdistämisen poistaminen asiakirjoista ja tapahtumista</span><span class="sxs-lookup"><span data-stu-id="6b07c-102">How to: Connect and Disconnect Incoming Document Records from Documents and Entries</span></span>
<span data-ttu-id="6b07c-103">Voit tallentaa ulkoisia liiketoiminta-asiakirjoja Dynamics NAV -ohjelmaan liittämällä asiakirjatiedostoja asiaan kuuluviin saapuviin asiakirjatietueisiin.</span><span class="sxs-lookup"><span data-stu-id="6b07c-103">You can store external business documents in Dynamics NAV by attaching the document files to the related incoming document records.</span></span> <span data-ttu-id="6b07c-104">Vaikka asiakirja (kuten ostolasku) ei olisi ollut alun pitäen saapuva asiakirjatietue, voit silti luoda ja yhdistää siihen saapuvan asiakirjatietueen myöhemmin.</span><span class="sxs-lookup"><span data-stu-id="6b07c-104">If the document, such as a purchase invoice, did not start its existence as an incoming document record, you can still create and connect an incoming document record to it later.</span></span> <span data-ttu-id="6b07c-105">Voit myös liittää saapuvia asiakirjatiedostoja kirjattuihin osto- ja myyntiasiakirjoihin sekä toimittaja-, asiakas- ja pääkirjanpidon tapahtumiin käyttämällä **Saapuvat asiakirjatiedostot** -tietoruutua esimerkiksi **Kirjatut ostolaskut**- ja **Toimittajatapahtumat**-ikkunassa.</span><span class="sxs-lookup"><span data-stu-id="6b07c-105">You can also attach incoming document files to posted purchase and sales documents and to vendor, customer, and general ledger entries by using the **Incoming Document Files** FactBox in, for example, the **Posted Purchase Invoices** and **Vendor Ledger Entries** windows.</span></span>

<span data-ttu-id="6b07c-106">**Tilikartta**- ja **Pääkirjanpidon tapahtumat** -ikkunan hakutoiminnon avulla voit etsiä pääkirjanpidon tapahtumia kirjatuille osto- ja myyntiasiakirjoille, joilla ei ole saapuvia asiakirjatietueita. Tämän jälkeen voit keskitetysti muodostaa yhteyden olemassa oleviin tietueisiin tai luoda uusia tietueita ja niihin liittyviä asiakirjatiedostoja.</span><span class="sxs-lookup"><span data-stu-id="6b07c-106">From the **Chart of Accounts** and **General Ledger Entries** windows, you can use a search function to find general ledger entries for posted purchase and sales documents that do not have incoming document records and then centrally link to existing records or create new ones with attached document files.</span></span> <span data-ttu-id="6b07c-107">Lisätietoja on kohdassa [Toimintaohje: Sellaisten kirjattujen asiakirjojen etsiminen, joilla ei ole saapuvia asiakirjatietueita](across-how-find-posted-documents-without-income-document-records.md).</span><span class="sxs-lookup"><span data-stu-id="6b07c-107">For more information, see [How to: Find Posted Documents without Incoming Document Records](across-how-find-posted-documents-without-income-document-records.md).</span></span>

<span data-ttu-id="6b07c-108">Seuraavassa kuvataan, kuinka voit liittää tiedoston olemassa olevaan ostolaskuun, jota ei ole luotu saapuvasta asiakirjatietueesta. Lisäksi kuvataan, kuinka voit liittää tiedoston toimittajatapahtumaan.</span><span class="sxs-lookup"><span data-stu-id="6b07c-108">The following procedures show how to attach a file to an existing purchase invoice that was not created from an incoming document record and how to attach a file to a vendor ledger entry.</span></span> <span data-ttu-id="6b07c-109">Tiedoston liittäminen kirjattuihin osto- tai myyntiasiakirjoihin toimii vastaavalla tavalla.</span><span class="sxs-lookup"><span data-stu-id="6b07c-109">Attaching a file to posted purchase or sales documents works in a similar way.</span></span>

## <a name="to-create-and-connect-an-incoming-document-record-from-a-purchase-invoice"></a><span data-ttu-id="6b07c-110">Saapuvan asiakirjatietueen luominen ja yhdistäminen ostolaskusta</span><span class="sxs-lookup"><span data-stu-id="6b07c-110">To create and connect an incoming document record from a purchase invoice</span></span>
1. <span data-ttu-id="6b07c-111">Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Ostolaskut** ja valitse sitten aiheeseen liittyvä linkki.</span><span class="sxs-lookup"><span data-stu-id="6b07c-111">In the top right corner, choose the **Search for Page or Report** icon, enter **Purchase Invoices**, and then choose the related link.</span></span>
2. <span data-ttu-id="6b07c-112">Valitse sen ostolaskun rivi, johon haluat liittää tiedoston, ja valitse sitten **Luo saapuva asiakirja tiedostosta** -toiminto.</span><span class="sxs-lookup"><span data-stu-id="6b07c-112">Select the line for a purchase invoice that you want to attach a file to, and then choose the **Create Incoming Document from File** action.</span></span>
3. <span data-ttu-id="6b07c-113">Vaihtoehtoisesti voit valita sen ostolaskun rivin, johon haluat liittää tiedoston, ja valita sitten **Liitä tiedosto**-toiminnon.</span><span class="sxs-lookup"><span data-stu-id="6b07c-113">Alternatively, select the line for a purchase invoice that you want to attach a file to, and then choose the **Attach File** action.</span></span>
4. <span data-ttu-id="6b07c-114">Valitse **Lisää tiedosto** -ikkunassa tiedosto, joka vastaa kyseistä saapuvaa asiakirjaa, ja valitse sitten **Avaa**.</span><span class="sxs-lookup"><span data-stu-id="6b07c-114">In the **Insert File** window, select the file that represents the incoming document in question, and then choose the **Open** button.</span></span>

## <a name="to-create-and-connect-an-incoming-document-record-from-a-vendor-ledger-entry"></a><span data-ttu-id="6b07c-115">Saapuvan asiakirjatietueen luominen ja yhdistäminen toimittajatapahtumasta</span><span class="sxs-lookup"><span data-stu-id="6b07c-115">To create and connect an incoming document record from a vendor ledger entry</span></span>
1. <span data-ttu-id="6b07c-116">Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Toimittajatapahtumat** ja valitse sitten aiheeseen liittyvä linkki.</span><span class="sxs-lookup"><span data-stu-id="6b07c-116">In the top right corner, choose the **Search for Page or Report** icon, enter **Vendor Ledger Entries**, and then choose the related link.</span></span>
2. <span data-ttu-id="6b07c-117">Valitse sen toimittajatapahtuman rivi, johon haluat liittää tiedoston, ja valitse sitten **Luo saapuva asiakirja tiedostosta** -toiminto.</span><span class="sxs-lookup"><span data-stu-id="6b07c-117">Select a line for a vendor ledger entry that you want to attach a file to, and then choose the **Create Incoming Document from File** action.</span></span>
3. <span data-ttu-id="6b07c-118">Vaihtoehtoisesti voit valita sen toimittajatapahtuman rivin, johon haluat liittää tiedoston, ja valita sitten **Liitä tiedosto**-toiminnon.</span><span class="sxs-lookup"><span data-stu-id="6b07c-118">Alternatively, select a line for a vendor ledger entry that you want to attach a file to, and then choose the **Attach File** action.</span></span>
4. <span data-ttu-id="6b07c-119">Valitse **Lisää tiedosto** -ikkunassa tiedosto, joka vastaa kyseistä saapuvaa asiakirjaa, ja valitse sitten **Avaa**.</span><span class="sxs-lookup"><span data-stu-id="6b07c-119">In the **Insert File** window, select the file that represents the incoming document in question, and then choose the **Open** button.</span></span>

## <a name="to-remove-a-connection-from-an-incoming-document-record-to-a-posted-document"></a><span data-ttu-id="6b07c-120">Saapuvan asiakirjan tietueen ja kirjatun asiakirjan yhteyden poistaminen</span><span class="sxs-lookup"><span data-stu-id="6b07c-120">To remove a connection from an incoming document record to a posted document</span></span>
<span data-ttu-id="6b07c-121">Voit poistaa liitetiedostot kirjaamattomista asiakirjoista milloin tahansa poistamalla saapuvan asiakirjan tietueen.</span><span class="sxs-lookup"><span data-stu-id="6b07c-121">You can remove file attachments from non-posted documents at any time by deleting the related incoming document record.</span></span> <span data-ttu-id="6b07c-122">Jos asiakirja on kirjattu, liitos saapuvan asiakirjan tietueeseen on poistettava ensin.</span><span class="sxs-lookup"><span data-stu-id="6b07c-122">If the document is posted, then you must first remove the connection from the incoming document record.</span></span>

1. <span data-ttu-id="6b07c-123">Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Saapuvat asiakirjat** ja valitse sitten aiheeseen liittyvä linkki.</span><span class="sxs-lookup"><span data-stu-id="6b07c-123">In the top right corner, choose the **Search for Page or Report** icon, enter **Incoming Documents**, and then choose the related link.</span></span>
2. <span data-ttu-id="6b07c-124">Valitse sen saapuvan asiakirjatietueen rivi, joka on liitetty poistettavaan kirjattuun asiakirjaan, ja valitse sitten **Poista viite tietueeseen** -toiminto.</span><span class="sxs-lookup"><span data-stu-id="6b07c-124">Select the line for an incoming document record connected to a posted document that you want to remove, and then choose the **Remove Reference to Record** action.</span></span>

<span data-ttu-id="6b07c-125">Yhteys kirjattuun asiakirjaan poistetaan.</span><span class="sxs-lookup"><span data-stu-id="6b07c-125">The connection to the posted document is removed.</span></span> <span data-ttu-id="6b07c-126">Voit nyt liittää toisen saapuvan asiakirjatietueen kirjattuun asiakirjaan tässä ohjeaiheessa kuvatulla tavalla.</span><span class="sxs-lookup"><span data-stu-id="6b07c-126">You can now proceed to connect another incoming document record to the posted document as described in this topic.</span></span>

## <a name="see-also"></a><span data-ttu-id="6b07c-127">Katso myös</span><span class="sxs-lookup"><span data-stu-id="6b07c-127">See Also</span></span>  
[<span data-ttu-id="6b07c-128">Saapuvien asiakirjojen käsitteleminen</span><span class="sxs-lookup"><span data-stu-id="6b07c-128">Process Incoming Documents</span></span>](across-process-income-documents.md)  
[<span data-ttu-id="6b07c-129">Saapuvat asiakirjat</span><span class="sxs-lookup"><span data-stu-id="6b07c-129">Incoming Documents</span></span>](across-income-documents.md)  
[<span data-ttu-id="6b07c-130">Ostojen hallinta</span><span class="sxs-lookup"><span data-stu-id="6b07c-130">Manage Purchasing</span></span>](purchasing-manage-purchasing.md)  
[<span data-ttu-id="6b07c-131">Dynamics NAV -ohjelman käyttäminen</span><span class="sxs-lookup"><span data-stu-id="6b07c-131">Work With Dynamics NAV</span></span>](ui-work-product.md)
