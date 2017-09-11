---
title: "Toimintaohje: Saapuvien asiakirjojen määrittäminen"
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
ms.openlocfilehash: d55329b571e4c59d4821a86a39362ea58480b86a
ms.contentlocale: fi-fi
ms.lasthandoff: 07/19/2017

---

# <a name="how-to-set-up-incoming-documents"></a><span data-ttu-id="8dd44-102">Toimintaohje: Saapuvien asiakirjojen määrittäminen</span><span class="sxs-lookup"><span data-stu-id="8dd44-102">How to: Set Up Incoming Documents</span></span>
<span data-ttu-id="8dd44-103">Jos luot pääkirjan rivejä saapuvista asiakirjatietueista, **Saapuvien asiakirjojen asetukset** -ikkunassa on määritettävä käytettävä päiväkirjan malli sekä erä.</span><span class="sxs-lookup"><span data-stu-id="8dd44-103">If you create general journal lines from incoming document records, you must specify in the **Incoming Documents Setup** window which journal template and batch to use.</span></span>

<span data-ttu-id="8dd44-104">Jos haluat, etteivät käyttäjät voi luoda laskuja tai yleisen päiväkirjan rivejä saapuvista asiakirjatietueista ennen asiakirjojen hyväksymistä, määritä hyväksyjät **Saapuvan asiakirjan hyväksyjät** -ikkunassa.</span><span class="sxs-lookup"><span data-stu-id="8dd44-104">If you do not want users to create invoices or general journal lines from incoming document records unless the documents are first approved, you must set up approvers in the **Incoming Document Approvers** window.</span></span>

<span data-ttu-id="8dd44-105">Kun haluat muuntaa PDF- ja kuvatiedostoja sähköisiksi asiakirjoiksi, jotka voi muuntaa esimerkiksi ostolaskuiksi Dynamics NAV -ohjelmassa, määritä ensin OCR-ominaisuus ja ota palvelu käyttöön.</span><span class="sxs-lookup"><span data-stu-id="8dd44-105">To turn PDF and image files into electronic documents that you can convert to, for example, purchase invoices inside Dynamics NAV, you must first set up the OCR feature and enable the service.</span></span>

<span data-ttu-id="8dd44-106">Kun Saapuvat asiakirjat -ominaisuus on määritetty, voit käyttää erilaisia toimintoja, joilla voit tarkistaa kulutositteita, hallita OCR-tehtäviä ja muuntaa saapuvia asiakirjatiedostoja manuaalisesti tai automaattisesti sekä siirtää niistä tietoja asiakirjoihin tai kirjanpitoriveille.</span><span class="sxs-lookup"><span data-stu-id="8dd44-106">When the Incoming Documents feature is set up, you can use different functions to review expense receipts, manage OCR tasks, and convert incoming document files, manually or automatically, to the relevant documents or journal lines.</span></span> <span data-ttu-id="8dd44-107">Ulkoisia tiedostoja voi liittää missä tahansa prosessin vaiheessa myös kirjattuihin asiakirjoihin ja muodostuviin toimittaja-, asiakas- ja pääkirjamerkintöihin.</span><span class="sxs-lookup"><span data-stu-id="8dd44-107">The external files can be attached at any process stage, including to posted documents and to the resulting vendor, customer, and general ledger entries.</span></span> <span data-ttu-id="8dd44-108">Lisätietoja on kohdassa [Toimintaohje: Saapuvien asiakirjojen käsitteleminen](across-process-income-documents.md).</span><span class="sxs-lookup"><span data-stu-id="8dd44-108">For more information, see [How to: Process Incoming Documents](across-process-income-documents.md).</span></span>

## <a name="to-set-up-the-incoming-documents-feature"></a><span data-ttu-id="8dd44-109">Saapuvat asiakirjat -ominaisuuden määrittäminen</span><span class="sxs-lookup"><span data-stu-id="8dd44-109">To set up the Incoming Documents feature</span></span>
1. <span data-ttu-id="8dd44-110">Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Saapuvien asiakirjojen asetukset** ja valitse sitten aiheeseen liittyvä linkki.</span><span class="sxs-lookup"><span data-stu-id="8dd44-110">In the top right corner, choose the **Search for Page or Report** icon, enter **Incoming Document Setup**, and then choose the related link.</span></span>
2. <span data-ttu-id="8dd44-111">Täytä tarvittavat kentät.</span><span class="sxs-lookup"><span data-stu-id="8dd44-111">Fill in the fields as necessary.</span></span> <span data-ttu-id="8dd44-112">Lue kentän lyhyt kuvaus valitsemalla kenttä tai siirry lisätietoihin valitsemalla linkki.</span><span class="sxs-lookup"><span data-stu-id="8dd44-112">Choose a field to read a short description of the field or link to more information.</span></span>

## <a name="to-set-up-approvers-of-incoming-document-records"></a><span data-ttu-id="8dd44-113">Saapuvien asiakirjatietueiden hyväksyjien määrittäminen</span><span class="sxs-lookup"><span data-stu-id="8dd44-113">To set up approvers of incoming document records</span></span>
1. <span data-ttu-id="8dd44-114">Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Saapuvien asiakirjojen asetukset** ja valitse sitten aiheeseen liittyvä linkki.</span><span class="sxs-lookup"><span data-stu-id="8dd44-114">In the top right corner, choose the **Search for Page or Report** icon, enter **Incoming Document Setup**, and then choose the related link.</span></span>  
2. <span data-ttu-id="8dd44-115">Valitse **Saapuvien asiakirjojen asetukset** -ikkunassa **Hyväksyjät**-toiminto.</span><span class="sxs-lookup"><span data-stu-id="8dd44-115">In the **Incoming Documents Setup** window, choose the **Approvers** action.</span></span>

    <span data-ttu-id="8dd44-116">**Saapuvan asiakirjan hyväksyjät** -ikkunassa näkyvät kaikki Dynamics NAV -ohjelmaan rekisteröityneet käyttäjät.</span><span class="sxs-lookup"><span data-stu-id="8dd44-116">The **Incoming Document Approvers** window shows all users that are set up in your Dynamics NAV .</span></span>  
3. <span data-ttu-id="8dd44-117">Valitse vähintään yksi käyttäjä, joka voi hyväksyä saapuvan asiakirjan ennen liittyvän asiakirjan tai päiväkirjarivin luomista.</span><span class="sxs-lookup"><span data-stu-id="8dd44-117">Select one or more users that can approve an incoming document before a related document or journal line can be created.</span></span>

<span data-ttu-id="8dd44-118">Kun hyväksyjät on määritetty **Saapuvien asiakirjojen hyväksyjät** -ikkunassa, vain kyseiset käyttäjät voivat hyväksyä saapuvan asiakirjan, jos **Saapuvien asiakirjojen asetukset** -ikkunan **Edellytä hyväksyntää luomista varten** -valintaruutu on valittu.</span><span class="sxs-lookup"><span data-stu-id="8dd44-118">When approvers have been set up in the **Incoming Document Approvers** window, only those users can approve an incoming document if the **Require Approval To Create** check box in the **Incoming Documents Setup** window is selected.</span></span>

<span data-ttu-id="8dd44-119">**Huomautus**: Nämä hyväksynnän asetukset eivät liity hyväksymistyönkulkuihin.</span><span class="sxs-lookup"><span data-stu-id="8dd44-119">**Note**: This approval setup is not related to approval workflows.</span></span> <span data-ttu-id="8dd44-120">Lisätietoja on kohdassa [Toimintaohje: Hyväksyntätyönkulkujen käyttäminen](across-how-use-approval-workflows.md).</span><span class="sxs-lookup"><span data-stu-id="8dd44-120">For more information, see [How to: Use Approval Workflows](across-how-use-approval-workflows.md).</span></span>

## <a name="to-set-up-an-ocr-service"></a><span data-ttu-id="8dd44-121">OCR-palvelun määrittäminen</span><span class="sxs-lookup"><span data-stu-id="8dd44-121">To set up an OCR service</span></span>
1. <span data-ttu-id="8dd44-122">Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **OCR-palvelun asetukset** ja valitse sitten aiheeseen liittyvä linkki.</span><span class="sxs-lookup"><span data-stu-id="8dd44-122">In the top right corner, choose the **Search for Page or Report** icon, enter **OCR Service Setup**, and then choose the related link.</span></span>
2. <span data-ttu-id="8dd44-123">Täytä tarvittavat kentät.</span><span class="sxs-lookup"><span data-stu-id="8dd44-123">Fill in the fields as necessary.</span></span> <span data-ttu-id="8dd44-124">Lue kentän lyhyt kuvaus valitsemalla kenttä tai siirry lisätietoihin valitsemalla linkki.</span><span class="sxs-lookup"><span data-stu-id="8dd44-124">Choose a field to read a short description of the field or link to more information.</span></span>


## <a name="to-encrypt-your-login-information"></a><span data-ttu-id="8dd44-125">Kirjautumistietojen salaaminen</span><span class="sxs-lookup"><span data-stu-id="8dd44-125">To encrypt your login information</span></span>
<span data-ttu-id="8dd44-126">Suosittelemme, että suojaat **OCR-palvelun asetukset** -ikkunaan kirjoittamasi kirjautumistiedot.</span><span class="sxs-lookup"><span data-stu-id="8dd44-126">It is recommended that you protect the logon information that you enter in the **OCR Service Setup** window.</span></span> <span data-ttu-id="8dd44-127">Palvelimen tiedot voi salata luomalla uusia salausavaimia tai tuomalla olemassa olevia salausavaimia, jotka otetaan käyttöön tietokantayhteyden muodostavassa palvelininstanssissa.</span><span class="sxs-lookup"><span data-stu-id="8dd44-127">You can encrypt data on the server by generating new or importing existing encryption keys that you enable on the server instance that connects to the database.</span></span>

1. <span data-ttu-id="8dd44-128">Valitse **OCR-palvelun asetukset** -ikkunassa **Salauksen hallinta** -toiminto.</span><span class="sxs-lookup"><span data-stu-id="8dd44-128">In the **OCR Service Setup** window, choose the **Encryption Management** action.</span></span>
2. <span data-ttu-id="8dd44-129">Ota tietojen salaus käyttöön **Tietojen salauksen hallinta** -ikkunassa.</span><span class="sxs-lookup"><span data-stu-id="8dd44-129">In the **Data Encryption Management** window, enable encryption of your data.</span></span>

## <a name="see-also"></a><span data-ttu-id="8dd44-130">Katso myös</span><span class="sxs-lookup"><span data-stu-id="8dd44-130">See Also</span></span>  
[<span data-ttu-id="8dd44-131">Saapuvien asiakirjojen käsitteleminen</span><span class="sxs-lookup"><span data-stu-id="8dd44-131">Process Incoming Documents</span></span>](across-process-income-documents.md)  
[<span data-ttu-id="8dd44-132">Saapuvat asiakirjat</span><span class="sxs-lookup"><span data-stu-id="8dd44-132">Incoming Documents</span></span>](across-income-documents.md)  
[<span data-ttu-id="8dd44-133">Ostojen hallinta</span><span class="sxs-lookup"><span data-stu-id="8dd44-133">Manage Purchasing</span></span>](purchasing-manage-purchasing.md)  
[<span data-ttu-id="8dd44-134">Dynamics NAV -ohjelman käyttäminen</span><span class="sxs-lookup"><span data-stu-id="8dd44-134">Work With Dynamics NAV</span></span>](ui-work-product.md)

