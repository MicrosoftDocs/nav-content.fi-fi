---
title: "Pankin viitetiedostojen määrittäminen"
description: "Elektronisten maksujen käsittelyä varten on ensin määritettävä pankin viitetiedostot, joiden avulla määritetään, miten maksutiedot tuodaan tai viedään."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 07/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 1dfba8b14019991c95f40ffd5f7fbaed5df414eb
ms.openlocfilehash: 10e5c62af9dc454c2c16f9848fc440d6b29c20a9
ms.contentlocale: fi-fi
ms.lasthandoff: 12/01/2017

---
# <a name="how-to-set-up-bank-reference-files"></a><span data-ttu-id="45c07-103">Toimintaohje: Pankin viitetiedostojen määrittäminen</span><span class="sxs-lookup"><span data-stu-id="45c07-103">How to: Set Up Bank Reference Files</span></span>
<span data-ttu-id="45c07-104">Elektronisten maksujen käsittelyä varten on ensin määritettävä pankin viitetiedostot, joiden avulla määritetään, miten maksutiedot tuodaan tai viedään.</span><span class="sxs-lookup"><span data-stu-id="45c07-104">To process electronic payments, you must first set up bank reference files to determine how payment data should be imported or exported.</span></span>  

## <a name="to-set-up-a-bank-reference-file"></a><span data-ttu-id="45c07-105">Pankin viitetiedoston määrittäminen</span><span class="sxs-lookup"><span data-stu-id="45c07-105">To set up a bank reference file</span></span>  

1.  <span data-ttu-id="45c07-106">Valitse ![Etsi sivu tai raportti -kuvake](../../media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, syötä **Pankin viitetiedoston asetukset** ja valitse sitten aiheeseen liittyvä linkki.</span><span class="sxs-lookup"><span data-stu-id="45c07-106">Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Bank Reference File Setup**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="45c07-107">Täytä **Yleinen**-pikavälilehden kentät seuraavassa taulukossa kuvatulla tavalla.</span><span class="sxs-lookup"><span data-stu-id="45c07-107">On the **General** FastTab, fill in the fields as described in the following table.</span></span>  

    |<span data-ttu-id="45c07-108">Kenttä</span><span class="sxs-lookup"><span data-stu-id="45c07-108">Field</span></span>|<span data-ttu-id="45c07-109">Description</span><span class="sxs-lookup"><span data-stu-id="45c07-109">Description</span></span>|  
    |---------------------------------|---------------------------------------|  
    |<span data-ttu-id="45c07-110">**Nro**</span><span class="sxs-lookup"><span data-stu-id="45c07-110">**No.**</span></span>|<span data-ttu-id="45c07-111">Määrittää pankkitilin koodin.</span><span class="sxs-lookup"><span data-stu-id="45c07-111">Specifies a bank account code.</span></span>|  
    |<span data-ttu-id="45c07-112">**Vie viitemaksut**</span><span class="sxs-lookup"><span data-stu-id="45c07-112">**Export Reference Payments**</span></span>|<span data-ttu-id="45c07-113">Anna vietävän maksutiedoston koko polku.</span><span class="sxs-lookup"><span data-stu-id="45c07-113">Enter the full path of the payment file to export.</span></span>|  
    |<span data-ttu-id="45c07-114">**Tuo viitemaksut**</span><span class="sxs-lookup"><span data-stu-id="45c07-114">**Import Reference Payments**</span></span>|<span data-ttu-id="45c07-115">Anna tuotavan maksutiedoston koko polku.</span><span class="sxs-lookup"><span data-stu-id="45c07-115">Enter the full path of the payment file to import.</span></span>|  
    |<span data-ttu-id="45c07-116">**Valuutan vaihtokurssitiedosto**</span><span class="sxs-lookup"><span data-stu-id="45c07-116">**Currency Exchange Rate File**</span></span>|<span data-ttu-id="45c07-117">Anna valuutan vaihtokurssitiedoston koko polku.</span><span class="sxs-lookup"><span data-stu-id="45c07-117">Enter the full path of the currency exchange rate file.</span></span>|  
    |<span data-ttu-id="45c07-118">**Kohdistettujen hyvityslaskujen tiedot**</span><span class="sxs-lookup"><span data-stu-id="45c07-118">**Inform. of Appl. Cr. Memos**</span></span>|<span data-ttu-id="45c07-119">Kun valitset tämän, laskuihin kohdistetut hyvitykset näkyvät maksun vastaanottajan tiliotteessa.</span><span class="sxs-lookup"><span data-stu-id="45c07-119">Select to display credits applied to invoices on the payment recipient's account statement.</span></span>|  

3.  <span data-ttu-id="45c07-120">Täytä **Ulkomaan maksut** -pikavälilehden kentät seuraavassa taulukossa kuvatulla tavalla.</span><span class="sxs-lookup"><span data-stu-id="45c07-120">On the **Foreign Payments** FastTab, fill in the fields as described in the following table.</span></span>  

    |<span data-ttu-id="45c07-121">Kenttä</span><span class="sxs-lookup"><span data-stu-id="45c07-121">Field</span></span>|<span data-ttu-id="45c07-122">Description</span><span class="sxs-lookup"><span data-stu-id="45c07-122">Description</span></span>|  
    |---------------------------------|---------------------------------------|  
    |<span data-ttu-id="45c07-123">**Vie ulkomaan maksut**</span><span class="sxs-lookup"><span data-stu-id="45c07-123">**Export Foreign Payments**</span></span>|<span data-ttu-id="45c07-124">Anna ulkomaan pankkeihin vietävän maksutiedoston koko polku.</span><span class="sxs-lookup"><span data-stu-id="45c07-124">Enter the full path of the payment file to export to foreign banks.</span></span>|  
    |<span data-ttu-id="45c07-125">**Eräpäivän käsittely**</span><span class="sxs-lookup"><span data-stu-id="45c07-125">**Due Date Handling**</span></span>|<span data-ttu-id="45c07-126">Määritä, miten eräpäivän käsittelyä käytetään ulkomaan maksuissa.</span><span class="sxs-lookup"><span data-stu-id="45c07-126">Select how due date processing should be applied to foreign payments.</span></span><br /><br /> <span data-ttu-id="45c07-127">**Erä** – Kaikki tiedoston maksut saavat saman maksupäivämäärän.</span><span class="sxs-lookup"><span data-stu-id="45c07-127">**Batch** – All payments in the file receive the same payment date.</span></span><br /><br /> <span data-ttu-id="45c07-128">-tai-</span><span class="sxs-lookup"><span data-stu-id="45c07-128">–or–</span></span><br /><br /> <span data-ttu-id="45c07-129">**Tapahtuma** – Jokainen tiedoston maksu saa tapahtumakohtaisen maksupäivämäärän.</span><span class="sxs-lookup"><span data-stu-id="45c07-129">**Transaction** – Each payment in the file receives a transaction-specific payment date.</span></span> <span data-ttu-id="45c07-130">Kysy pankista lisätietoja tämän asetuksen käytöstä.</span><span class="sxs-lookup"><span data-stu-id="45c07-130">Contact your bank to determine whether this setting should be used.</span></span>|  
    |<span data-ttu-id="45c07-131">**Palvelumaksun oletuskoodi**</span><span class="sxs-lookup"><span data-stu-id="45c07-131">**Default Service Fee Code**</span></span>|<span data-ttu-id="45c07-132">Valitse palvelumaksun oletuskoodi ulkomaan pankkeja varten.</span><span class="sxs-lookup"><span data-stu-id="45c07-132">Select a default service fee code for foreign banks.</span></span>|  
    |<span data-ttu-id="45c07-133">**Oletusmaksutapa**</span><span class="sxs-lookup"><span data-stu-id="45c07-133">**Default Payment Method**</span></span>|<span data-ttu-id="45c07-134">Valitse oletusmaksutapa ulkomaan pankkeja varten.</span><span class="sxs-lookup"><span data-stu-id="45c07-134">Select a default payment method for foreign payments.</span></span>|  
    |<span data-ttu-id="45c07-135">**Vaihtokurssin sopimusnro**</span><span class="sxs-lookup"><span data-stu-id="45c07-135">**Exchange Rate Contract No.**</span></span>|<span data-ttu-id="45c07-136">Anna vaihtokurssin sopimusnumero.</span><span class="sxs-lookup"><span data-stu-id="45c07-136">Enter the exchange rate contract number.</span></span>|  
    |<span data-ttu-id="45c07-137">**Salli ulkomaan maksujen yhdistäminen**</span><span class="sxs-lookup"><span data-stu-id="45c07-137">**Allow Comb. Foreign Pmts.**</span></span>|<span data-ttu-id="45c07-138">Yhdistä kaikki yhdelle vastaanottajalle tietyn päivän aikana samalta pankkitililtä tehdyt ulkomaan maksut.</span><span class="sxs-lookup"><span data-stu-id="45c07-138">Select to combine all foreign payments made to one recipient in one day from the same bank account.</span></span>|  

4.  <span data-ttu-id="45c07-139">Täytä **SEPA**-pikavälilehden kentät seuraavassa taulukossa kuvatulla tavalla.</span><span class="sxs-lookup"><span data-stu-id="45c07-139">On the **SEPA** FastTab, fill in the fields as described in the following table.</span></span>  

    |<span data-ttu-id="45c07-140">Kenttä</span><span class="sxs-lookup"><span data-stu-id="45c07-140">Field</span></span>|<span data-ttu-id="45c07-141">Description</span><span class="sxs-lookup"><span data-stu-id="45c07-141">Description</span></span>|  
    |---------------------------------|---------------------------------------|  
    |<span data-ttu-id="45c07-142">**Pankin tunnus**</span><span class="sxs-lookup"><span data-stu-id="45c07-142">**Bank Party ID**</span></span>|<span data-ttu-id="45c07-143">Anna SEPA-pankin tunnus.</span><span class="sxs-lookup"><span data-stu-id="45c07-143">Enter a SEPA bank party ID.</span></span> <span data-ttu-id="45c07-144">**Huomautus:** Tätä kenttää käytetään vain SEPA-standardissa pain.001.001.02.</span><span class="sxs-lookup"><span data-stu-id="45c07-144">**Note:**  This field is only used for the SEPA pain.001.001.02 standard.</span></span>|  
    |<span data-ttu-id="45c07-145">**Tiedostonimi**</span><span class="sxs-lookup"><span data-stu-id="45c07-145">**File Name**</span></span>|<span data-ttu-id="45c07-146">Anna SEPA-maksutiedoston koko polku.</span><span class="sxs-lookup"><span data-stu-id="45c07-146">Enter the full path of the SEPA payment file.</span></span> <span data-ttu-id="45c07-147">**Huomautus:** Tätä kenttää käytetään vain SEPA-standardissa pain.001.001.02.</span><span class="sxs-lookup"><span data-stu-id="45c07-147">**Note:**  This field is only used for the SEPA pain.001.001.02 standard.</span></span>|  

    > [!IMPORTANT]  
    >  <span data-ttu-id="45c07-148">Voit viedä toimittajan maksut SEPA-standardin avulla, kun täytät **Maksun vientimuoto** -kentän **Pankkitilin kortti** -ikkunassa.</span><span class="sxs-lookup"><span data-stu-id="45c07-148">To export vendor payments using the SEPA standard, you must fill the **Payment Export Format** field in the **Bank Account Card** window.</span></span>  

5.  <span data-ttu-id="45c07-149">Valitse **OK**-painike.</span><span class="sxs-lookup"><span data-stu-id="45c07-149">Choose the **OK** button.</span></span>  

## <a name="see-also"></a><span data-ttu-id="45c07-150">Katso myös</span><span class="sxs-lookup"><span data-stu-id="45c07-150">See Also</span></span>  
 <span data-ttu-id="45c07-151">[Verkkopankkitoiminta Suomessa](electronic-banking-in-finland.md) </span><span class="sxs-lookup"><span data-stu-id="45c07-151">[Electronic Banking in Finland](electronic-banking-in-finland.md) </span></span>  
 <span data-ttu-id="45c07-152">[Toimintaohje: Maksutiedostojen luominen](how-to-generate-payment-files.md) </span><span class="sxs-lookup"><span data-stu-id="45c07-152">[How to: Generate Payment Files](how-to-generate-payment-files.md) </span></span>  
 [<span data-ttu-id="45c07-153">Toimintaohje: Maksualennusten ohittaminen</span><span class="sxs-lookup"><span data-stu-id="45c07-153">How to: Disregard Payment Discounts</span></span>](how-to-disregard-payment-discounts.md)

