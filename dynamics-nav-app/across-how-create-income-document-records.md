---
title: 'Toimintaohje: Saapuvien asiakirjatietueiden luominen'
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
ms.openlocfilehash: e91c4570ff60d991974ac6afd16ba3bc3e73e44f
ms.contentlocale: fi-fi
ms.lasthandoff: 07/19/2017

---

# <a name="how-to-create-incoming-document-records"></a><span data-ttu-id="25beb-102">Toimintaohje: Saapuvien asiakirjatietueiden luominen</span><span class="sxs-lookup"><span data-stu-id="25beb-102">How to: Create Incoming Document Records</span></span>
<span data-ttu-id="25beb-103">**Saapuvat asiakirjat** -ikkunassa voit käyttää erilaisia toimintoja, joilla voit tarkistaa kulutositteita, hallita OCR-tehtäviä ja muuntaa saapuvia asiakirjatiedostoja manuaalisesti tai automaattisesti sekä siirtää niistä tietoja asiakirjoihin tai kirjanpitoriveille.</span><span class="sxs-lookup"><span data-stu-id="25beb-103">In the **Incoming Documents** window, you can use different functions to review expense receipts, manage OCR tasks, and convert incoming document files, manually or automatically, to the relevant documents or journal lines.</span></span> <span data-ttu-id="25beb-104">Ulkoisia tiedostoja voi liittää missä tahansa prosessin vaiheessa myös kirjattuihin asiakirjoihin ja muodostuviin toimittaja-, asiakas- ja pääkirjamerkintöihin.</span><span class="sxs-lookup"><span data-stu-id="25beb-104">The external files can be attached at any process stage, including to posted documents and to the resulting vendor, customer, and general ledger entries.</span></span>

<span data-ttu-id="25beb-105">Voit tallentaa ulkoisen asiakirjan Dynamics NAV -ohjelmassa, kun luot ensin saapuvan asiakirjatietueen tai teet sen valmiiksi.</span><span class="sxs-lookup"><span data-stu-id="25beb-105">To record an external document in Dynamics NAV, you must first create or complete an incoming document record.</span></span> <span data-ttu-id="25beb-106">Voit tehdä tämän manuaalisesti tai ottaa valokuvan ulkoisesta asiakirjasta ja luoda sitten saapuva asiakirjatietue, johon on liitetty kuvatiedosto.</span><span class="sxs-lookup"><span data-stu-id="25beb-106">You can do this manually, or you can take a photo of the external document and then create the incoming document record with the image file attached.</span></span>

<span data-ttu-id="25beb-107">Ennen kuin voit käyttää Saapuvat asiakirjat -ominaisuutta, sinun on tehtävä tarvittavat asetukset.</span><span class="sxs-lookup"><span data-stu-id="25beb-107">Before you can use the Incoming Documents feature, you must perform the required setup.</span></span> <span data-ttu-id="25beb-108">Lisätietoja on kohdassa [Toimintaohje: Saapuvien asiakirjojen määrittäminen](across-how-setup-income-documents.md).</span><span class="sxs-lookup"><span data-stu-id="25beb-108">For more information, see [How to: Set Up Incoming Documents](across-how-setup-income-documents.md).</span></span>

## <a name="to-approve-or-reject-an-incoming-document"></a><span data-ttu-id="25beb-109">Saapuvan asiakirjan hyväksyminen tai hylkääminen</span><span class="sxs-lookup"><span data-stu-id="25beb-109">To approve or reject an incoming document</span></span>
<span data-ttu-id="25beb-110">Jos haluat, että käyttäjät voivat luoda laskuja tai yleisen päiväkirjan rivejä saapuvista asiakirjatietueista vasta, kun ne on hyväksytty, voit määrittää hyväksyjät, joiden on hyväksyttävä tietueet ennen niiden käsittelyä.</span><span class="sxs-lookup"><span data-stu-id="25beb-110">If you do want to allow users to create invoices or general journal lines from incoming document records unless they are approved, you can set up approvers who must approve the records before they can be processed.</span></span>

1. <span data-ttu-id="25beb-111">Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Saapuvat asiakirjat** ja valitse sitten aiheeseen liittyvä linkki.</span><span class="sxs-lookup"><span data-stu-id="25beb-111">In the top right corner, choose the **Search for Page or Report** icon, enter **Incoming Documents**, and then choose the related link.</span></span>
2. <span data-ttu-id="25beb-112">Valitse rivi, jolla hyväksyttävä tai hylättävä asiakirja on, ja valitse sitten **Hyväksy**- tai **Hylkää**-toiminto.</span><span class="sxs-lookup"><span data-stu-id="25beb-112">Select the line with the document that you want to approve or reject, and then choose the **Approve** or **Reject** actions.</span></span>

<span data-ttu-id="25beb-113">Jos hyväksyt saapuvan asiakirjatietueen, saapuvan asiakirjan rivin **Vapautettu**-valintaruutu on valittuna.</span><span class="sxs-lookup"><span data-stu-id="25beb-113">If you approve the incoming document record, the **Released** check box on the incoming document line is selected.</span></span> <span data-ttu-id="25beb-114">Esimerkiksi ostolaskujen luonnista vastaava henkilö voi nyt aloittaa tietueen käsittelemisen.</span><span class="sxs-lookup"><span data-stu-id="25beb-114">The user in charge of creating, for example, purchase invoices can proceed to process the record.</span></span>

## <a name="to-create-an-incoming-document-record-by-taking-a-photo"></a><span data-ttu-id="25beb-115">Saapuvien asiakirjatietueiden luominen valokuva ottamalla</span><span class="sxs-lookup"><span data-stu-id="25beb-115">To create an incoming document record by taking a photo</span></span>
<span data-ttu-id="25beb-116">**Huomautus**: Seuraavat toimet koskevat vain Dynamics NAV -ohjelman taulutietokone- ja puhelinasiakasohjelmaa.</span><span class="sxs-lookup"><span data-stu-id="25beb-116">**Note**: The following procedure only applies to the Dynamics NAV Tablet and Phone clients.</span></span>

1. <span data-ttu-id="25beb-117">Valitse sovellusriviltä **luo saapuva asiakirja kamerasta** ruutu ja siirry sitten vaiheeseen 4.</span><span class="sxs-lookup"><span data-stu-id="25beb-117">On the app bar, choose the **Create Incoming Document from Camera** tile, and then go to step 4.</span></span>
2. <span data-ttu-id="25beb-118">Voit myös valita sovellusrivin, valita asetukset-painikkeen, valita **saapuvat asiakirjat**, ja valita sitten **kaikki**.</span><span class="sxs-lookup"><span data-stu-id="25beb-118">Alternatively, on the app bar, choose the options button, choose **Incoming Documents**, and then choose **All**.</span></span>
3. <span data-ttu-id="25beb-119">Valitse **Saapuvat asiakirjat** -ikkunassa ellipsipainike ja valitse sitten **Luo kamerasta**.</span><span class="sxs-lookup"><span data-stu-id="25beb-119">In the **Incoming Documents** window, choose the ellipsis button, and then choose **Create from Camera**.</span></span> <span data-ttu-id="25beb-120">Tabletin tai puhelimen kamera ativoituu.</span><span class="sxs-lookup"><span data-stu-id="25beb-120">The camera on the tablet or phone is activated.</span></span>
4. <span data-ttu-id="25beb-121">Ota valokuva asiakirjasta, kuten tavaran vastaanotto, jonka haluat käsitellä saapuvana asiakirjana,ja valitse sitten **OK**.</span><span class="sxs-lookup"><span data-stu-id="25beb-121">Take a photo of a document, such as a purchase receipt, that you want to process as an incoming document, and then choose the **OK** button.</span></span>

<span data-ttu-id="25beb-122">Luo uuden saapuvan asiakirjan tietueen ja liittää kuvan.</span><span class="sxs-lookup"><span data-stu-id="25beb-122">A new incoming document record is created, with the image attached.</span></span>

## <a name="to-attach-an-image-to-an-incoming-document-record-by-taking-a-photo"></a><span data-ttu-id="25beb-123">Kuvan liittäminen saapuvien asiakirjatietueiden tietueeseen valokuva ottamalla</span><span class="sxs-lookup"><span data-stu-id="25beb-123">To attach an image to an incoming document record by taking a photo</span></span>
<span data-ttu-id="25beb-124">**Huomautus**: Seuraavat toimet koskevat vain Dynamics NAV -ohjelman taulutietokone- ja puhelinasiakasohjelmaa.</span><span class="sxs-lookup"><span data-stu-id="25beb-124">**Note**: The following procedure only applies to the Dynamics NAV Tablet and Phone clients.</span></span>

1. <span data-ttu-id="25beb-125">Voit valita sovellusrivin, valita asetukset-painikkeen, valita **saapuvat asiakirjat**, ja valita sitten **kaikki**.</span><span class="sxs-lookup"><span data-stu-id="25beb-125">On the app bar, choose the options button, choose **Incoming Documents**, and then choose **All**.</span></span>
2. <span data-ttu-id="25beb-126">Avaa aiemmin luotu saapuvan asiakirjan tietue kortti.</span><span class="sxs-lookup"><span data-stu-id="25beb-126">Open the card for an existing incoming document record.</span></span>
3. <span data-ttu-id="25beb-127">Valitse **Saapuva asiakirja** -ikkunassa ellipsipainike ja valitse sitten **Liitä kuva kamerasta**.</span><span class="sxs-lookup"><span data-stu-id="25beb-127">In the **Incoming Document** window, choose the ellipsis button, and then choose **Attach Image from Camera**.</span></span> <span data-ttu-id="25beb-128">Tabletin tai puhelimen kamera ativoituu.</span><span class="sxs-lookup"><span data-stu-id="25beb-128">The camera on the tablet or phone is activated.</span></span>
4. <span data-ttu-id="25beb-129">Ota valokuva asiakirjasta, kuten tavaran vastaanotto, jonka haluat käsitellä saapuvana asiakirjana,ja valitse sitten **OK**.</span><span class="sxs-lookup"><span data-stu-id="25beb-129">Take a photo of a document, such as a purchase receipt, that you want to process as an incoming document, and then choose the **OK** button.</span></span>

<span data-ttu-id="25beb-130">Kuva liitetään saapuvan asiakirjan tietueeseen.</span><span class="sxs-lookup"><span data-stu-id="25beb-130">The image is attached to the incoming document record.</span></span>

## <a name="to-create-an-incoming-document-record-manually"></a><span data-ttu-id="25beb-131">Saapuvan asiakirjatietueen luominen manuaalisesti</span><span class="sxs-lookup"><span data-stu-id="25beb-131">To create an incoming document record manually</span></span>
1. <span data-ttu-id="25beb-132">Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Saapuvat asiakirjat** ja valitse sitten aiheeseen liittyvä linkki.</span><span class="sxs-lookup"><span data-stu-id="25beb-132">In the top right corner, choose the **Search for Page or Report** icon, enter **Incoming Documents**, and then choose the related link.</span></span>
2. <span data-ttu-id="25beb-133">Valitse **Luo tiedostosta** -toiminto.</span><span class="sxs-lookup"><span data-stu-id="25beb-133">Choose the **Create from File** action.</span></span>  
3. <span data-ttu-id="25beb-134">**Lisää tiedosto** -ikkunassa valitse tiedosto ja valitse sitten **Avaa**.</span><span class="sxs-lookup"><span data-stu-id="25beb-134">In the **Insert File** window, select a file, and then choose **Open**.</span></span>

    <span data-ttu-id="25beb-135">Tiedosto liitetään automaattisesti.</span><span class="sxs-lookup"><span data-stu-id="25beb-135">The file is automatically attached.</span></span>
4. <span data-ttu-id="25beb-136">Vaihtoehtoisesti voit valita **Uusi**-toiminnon.</span><span class="sxs-lookup"><span data-stu-id="25beb-136">Alternatively, choose the **New** action.</span></span>
5. <span data-ttu-id="25beb-137">Voit liittää tiedoston valitsemalla **Liitä tiedosto** -toiminto.</span><span class="sxs-lookup"><span data-stu-id="25beb-137">To attach a file, choose the **Attach File** action.</span></span>
6. <span data-ttu-id="25beb-138">Valitse **Lisää tiedosto** -ikkunassa tiedosto, joka vastaa kyseistä saapuvaa asiakirjaa, ja valitse sitten **Avaa**.</span><span class="sxs-lookup"><span data-stu-id="25beb-138">In the **Insert File** window, select the file that represents the incoming document in question, and then choose the **Open** button.</span></span>
7. <span data-ttu-id="25beb-139">Täytä **Saapuva asiakirja** -ikkunassa tarvittavat kentät.</span><span class="sxs-lookup"><span data-stu-id="25beb-139">In the **Incoming Document** window, fill in the fields as necessary.</span></span> <span data-ttu-id="25beb-140">Lue kentän lyhyt kuvaus valitsemalla kenttä tai siirry lisätietoihin valitsemalla linkki.</span><span class="sxs-lookup"><span data-stu-id="25beb-140">Choose a field to read a short description of the field or link to more information.</span></span>

##<a name="see-also"></a><span data-ttu-id="25beb-141">Katso myös</span><span class="sxs-lookup"><span data-stu-id="25beb-141">See Also</span></span>  
[<span data-ttu-id="25beb-142">Saapuvien asiakirjojen käsitteleminen</span><span class="sxs-lookup"><span data-stu-id="25beb-142">Process Incoming Documents</span></span>](across-process-income-documents.md)  
[<span data-ttu-id="25beb-143">Saapuvat asiakirjat</span><span class="sxs-lookup"><span data-stu-id="25beb-143">Incoming Documents</span></span>](across-income-documents.md)  
[<span data-ttu-id="25beb-144">Ostojen hallinta</span><span class="sxs-lookup"><span data-stu-id="25beb-144">Manage Purchasing</span></span>](purchasing-manage-purchasing.md)  
[<span data-ttu-id="25beb-145">Dynamics NAV -ohjelman käyttäminen</span><span class="sxs-lookup"><span data-stu-id="25beb-145">Work With Dynamics NAV</span></span>](ui-work-product.md)

