---
title: 'Toimintaohje: Projektin edistymisen ja suorituskyvyn valvonta'
author: SorenGP
ms.custom: na
ms.date: 11/01/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 05b990dd93ddff12581efdc2918ada69681482a1
ms.contentlocale: fi-fi
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-monitor-job-progress-and-performance"></a><span data-ttu-id="7f5b4-102">Toimintaohje: Projektin edistymisen ja suorituskyvyn valvonta</span><span class="sxs-lookup"><span data-stu-id="7f5b4-102">How to: Monitor Job Progress and Performance</span></span>
<span data-ttu-id="7f5b4-103">Projektin edetessä kulutetaan materiaaleja, resursseja ja muita kuluja, ja nämä on kirjattava projektiin.</span><span class="sxs-lookup"><span data-stu-id="7f5b4-103">As a job progresses, materials, resources, and other expenses are consumed and must be posted to the job.</span></span> <span data-ttu-id="7f5b4-104">Keskeneräinen työ (KET) on ominaisuus, jonka avulla voit arvioida kirjanpidossa olevien projektien taloudellisen arvon projektin ollessa meneillään.</span><span class="sxs-lookup"><span data-stu-id="7f5b4-104">Work in Process (WIP) is a feature that enables you to estimate the financial value of jobs in the general ledger while the jobs are ongoing.</span></span> <span data-ttu-id="7f5b4-105">Monissa tapauksissa saatat kirjata projektille kuluja ennen projektin laskuttamista.</span><span class="sxs-lookup"><span data-stu-id="7f5b4-105">In many cases, you might post expenses for a job before invoicing a job.</span></span> <span data-ttu-id="7f5b4-106">Kun projektista on kirjattu vain kuluja, rahoituslaskelma on epätarkka.</span><span class="sxs-lookup"><span data-stu-id="7f5b4-106">When only expenses have been posted, your financial statement will be inaccurate.</span></span> <span data-ttu-id="7f5b4-107">Lisätietoja on kohdassa [Tietoja KET-menetelmistä](projects-understanding-wip.md).</span><span class="sxs-lookup"><span data-stu-id="7f5b4-107">For more information, see [Understanding WIP Methods](projects-understanding-wip.md).</span></span>

<span data-ttu-id="7f5b4-108">Voit seurata arvoa kirjanpidossa laskemalla KET:n ja kirjaamalla arvon kirjanpitoon.</span><span class="sxs-lookup"><span data-stu-id="7f5b4-108">To track the value in the general ledger, you can calculate WIP and post the value to the general ledger.</span></span>

<span data-ttu-id="7f5b4-109">Voit laskea KET:n seuraavien arvojen perusteella:</span><span class="sxs-lookup"><span data-stu-id="7f5b4-109">You can calculate WIP based on the following:</span></span>

- <span data-ttu-id="7f5b4-110">kustannusarvo</span><span class="sxs-lookup"><span data-stu-id="7f5b4-110">Cost Value</span></span>
- <span data-ttu-id="7f5b4-111">myyntiarvo</span><span class="sxs-lookup"><span data-stu-id="7f5b4-111">Sales Value</span></span>
- <span data-ttu-id="7f5b4-112">tuloutettavat kustannukset</span><span class="sxs-lookup"><span data-stu-id="7f5b4-112">Recognizable Cost</span></span>
- <span data-ttu-id="7f5b4-113">valmistumisen prosenttiosuus</span><span class="sxs-lookup"><span data-stu-id="7f5b4-113">Percentage of Completion</span></span>
- <span data-ttu-id="7f5b4-114">valmis sopimus.</span><span class="sxs-lookup"><span data-stu-id="7f5b4-114">Completed Contract</span></span>

<span data-ttu-id="7f5b4-115">Jos haluat tarkastella tulosta jollakin muulla menetelmällä, voit vaihtaa menetelmää ja laskea KET:n uudelleen.</span><span class="sxs-lookup"><span data-stu-id="7f5b4-115">If you want to view the result using a different method, you can change the method and calculate WIP again.</span></span> <span data-ttu-id="7f5b4-116">KET:n laskentakertojen määrää ei ole rajoitettu.</span><span class="sxs-lookup"><span data-stu-id="7f5b4-116">There is no limit to the number of times that you calculate WIP.</span></span> <span data-ttu-id="7f5b4-117">Ohjelma laskee KET:n mutta ei kirjaa sitä kirjanpitoon.</span><span class="sxs-lookup"><span data-stu-id="7f5b4-117">WIP is only calculated, it does not get posted to the general ledger.</span></span> <span data-ttu-id="7f5b4-118">Kun olet laskenut KET:n, voit kirjata sen kirjanpitoon.</span><span class="sxs-lookup"><span data-stu-id="7f5b4-118">After you have calculated WIP, you can post to the general ledger.</span></span>

## <a name="to-create-a-job-wip-method"></a><span data-ttu-id="7f5b4-119">Projektin KET-menetelmän luominen</span><span class="sxs-lookup"><span data-stu-id="7f5b4-119">To create a job WIP method</span></span>  
<span data-ttu-id="7f5b4-120">Voit luoda projektin KET-menetelmän, joka kuvastaa organisaatiosi tarpeita.</span><span class="sxs-lookup"><span data-stu-id="7f5b4-120">You can create a job WIP method that reflects the needs of your organization.</span></span> <span data-ttu-id="7f5b4-121">Luonnin jälkeen voit määrittää sen projektin oletusarvoiseksi KET-laskentamenetelmäksi, jota käytetään organisaatiossa.</span><span class="sxs-lookup"><span data-stu-id="7f5b4-121">After you have created it, you can set it as the default job WIP calculation method that will be used in your organization.</span></span>  

<span data-ttu-id="7f5b4-122">**Huomautus**.</span><span class="sxs-lookup"><span data-stu-id="7f5b4-122">**Note**.</span></span> <span data-ttu-id="7f5b4-123">Kun olet käyttänyt uutta tapaasi luodaksesi KET-tapahtumat, et voi enää poistaa tai muokata tapaa.</span><span class="sxs-lookup"><span data-stu-id="7f5b4-123">After you have used your new method to create WIP entries, you cannot delete the method or modify it.</span></span>  

1. <span data-ttu-id="7f5b4-124">Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Projektin KET-menetelmät** ja valitse sitten aiheeseen liittyvä linkki.</span><span class="sxs-lookup"><span data-stu-id="7f5b4-124">In the top right corner, choose the **Search for Page or Report** icon, enter **Job WIP Methods**, and then choose the related link.</span></span>  
2. <span data-ttu-id="7f5b4-125">Valitse **Uusi**-toiminto ja täytä tarvittavat kentät.</span><span class="sxs-lookup"><span data-stu-id="7f5b4-125">Choose the **New** action, and then fill in the fields as necessary.</span></span> <span data-ttu-id="7f5b4-126">Lue kentän lyhyt kuvaus valitsemalla kenttä tai siirry lisätietoihin valitsemalla linkki.</span><span class="sxs-lookup"><span data-stu-id="7f5b4-126">Choose a field to read a short description of the field or link to more information.</span></span>  
3. <span data-ttu-id="7f5b4-127">Sulje ikkuna.</span><span class="sxs-lookup"><span data-stu-id="7f5b4-127">Close the window.</span></span>   
4. <span data-ttu-id="7f5b4-128">Määritä tämä uusi menetelmä oletusarvoksi valitsemalla oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syöttämällä **Projektienhallinnan asetukset** ja valitsemalla sitten aiheeseen liittyvä linkki.</span><span class="sxs-lookup"><span data-stu-id="7f5b4-128">To make this new method the default, in the top right corner, choose the **Search for Page or Report** icon, enter **Jobs Setup**, and then choose the related link.</span></span>  
5. <span data-ttu-id="7f5b4-129">Valitse **Oletus KET-menetelmä** -kentässä menetelmä luettelosta.</span><span class="sxs-lookup"><span data-stu-id="7f5b4-129">In the **Default WIP Method** field, choose the method from the list.</span></span>

## <a name="to-define-a-wip-method-for-a-job"></a><span data-ttu-id="7f5b4-130">Määritä projektin KET-menetelmä</span><span class="sxs-lookup"><span data-stu-id="7f5b4-130">To define a WIP method for a job</span></span>  
<span data-ttu-id="7f5b4-131">Kun luot uuden projektin, määritä, mihin projektin KET-menetelmään se kohdistetaan.</span><span class="sxs-lookup"><span data-stu-id="7f5b4-131">When you create a new job, you must specify which job WIP method that applies.</span></span> <span data-ttu-id="7f5b4-132">Joissakin tapauksissa käytettävissä oleva projektin KET-menetelmä on määritetty oletusasetukseksi.</span><span class="sxs-lookup"><span data-stu-id="7f5b4-132">In some cases, which Job WIP method that you can use has been set up for you as a default.</span></span>

1. <span data-ttu-id="7f5b4-133">Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Projektit** ja valitse sitten aiheeseen liittyvä linkki.</span><span class="sxs-lookup"><span data-stu-id="7f5b4-133">In the top right corner, choose the **Search for Page or Report** icon, enter **Jobs**, and then choose the related link.</span></span>
2. <span data-ttu-id="7f5b4-134">Valitse **Uusi**-toiminto.</span><span class="sxs-lookup"><span data-stu-id="7f5b4-134">Choose the **New** action.</span></span> <span data-ttu-id="7f5b4-135">Lisätietoja on kohdassa [Toimintaohje: Projektien luominen](projects-how-create-jobs.md).</span><span class="sxs-lookup"><span data-stu-id="7f5b4-135">For more information, see [How to: Create Jobs](projects-how-create-jobs.md).</span></span>  
3. <span data-ttu-id="7f5b4-136">Valitse **Projektikortti**-ikkunan **KET-menetelmä**-kentässä KET-menetelmä luettelosta.</span><span class="sxs-lookup"><span data-stu-id="7f5b4-136">In the **Job Card** window, in the **WIP Method** field, select a WIP method from the list.</span></span> <span data-ttu-id="7f5b4-137">Vaikka oletusmenetelmä olisi määritetty, voit valita tarvittaessa toisen vaihtoehdon.</span><span class="sxs-lookup"><span data-stu-id="7f5b4-137">If a default method has been defined, you can select another option if needed.</span></span>  

## <a name="to-calculate-wip"></a><span data-ttu-id="7f5b4-138">Keskeneräisen työn laskeminen</span><span class="sxs-lookup"><span data-stu-id="7f5b4-138">To calculate WIP</span></span>  
<span data-ttu-id="7f5b4-139">Voit määrittää tasetileille kirjattavan KET-summan kauden lopussa suoritettavaa raportointia varten.</span><span class="sxs-lookup"><span data-stu-id="7f5b4-139">You can determine the WIP amount that is to be posted to balance sheet accounts for the period end reporting.</span></span> <span data-ttu-id="7f5b4-140">Tähän käytetään **Laske projektin KET** -erätyötä.</span><span class="sxs-lookup"><span data-stu-id="7f5b4-140">You use the **Job Calculate WIP** batch job to do this.</span></span>  

1. <span data-ttu-id="7f5b4-141">Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Laske projektin KET** ja valitse sitten aiheeseen liittyvä linkki.</span><span class="sxs-lookup"><span data-stu-id="7f5b4-141">In the top right corner, choose the **Search for Page or Report** icon, enter **Job Calculate WIP**, and then choose the related link.</span></span>  
2. <span data-ttu-id="7f5b4-142">Valitse **Laske KET** -toiminto.</span><span class="sxs-lookup"><span data-stu-id="7f5b4-142">Choose the **Calculate WIP** action.</span></span>
3. <span data-ttu-id="7f5b4-143">Täytä **Laske projektin KET** -ikkunassa tarvittavat kentät.</span><span class="sxs-lookup"><span data-stu-id="7f5b4-143">In the **Job Calculate WIP** window, fill in the fields as necessary.</span></span>
4. <span data-ttu-id="7f5b4-144">Valitse **OK**-painike.</span><span class="sxs-lookup"><span data-stu-id="7f5b4-144">Choose the **OK** button.</span></span>  

<span data-ttu-id="7f5b4-145">**Huomautus**: Eräajo laskee ainoastaan keskeneräisen työn.</span><span class="sxs-lookup"><span data-stu-id="7f5b4-145">**Note**: The batch job only calculates the WIP.</span></span> <span data-ttu-id="7f5b4-146">Sitä ei kirjata pääkirjanpitoon.</span><span class="sxs-lookup"><span data-stu-id="7f5b4-146">It is not posted to the general ledger.</span></span> <span data-ttu-id="7f5b4-147">Nämä toimet edellyttävät, että suoritat **Kirjaa KET kirjanpitoon** -eräajon, kun olet laskenut keskeneräisen työn.</span><span class="sxs-lookup"><span data-stu-id="7f5b4-147">To do so, you must run the **Post WIP to G/L** batch job when you have calculated the WIP.</span></span> <span data-ttu-id="7f5b4-148">Katso lisätietoja seuraavasta menettelystä.</span><span class="sxs-lookup"><span data-stu-id="7f5b4-148">For more information, see the following procedure.</span></span>

## <a name="to-post-wip"></a><span data-ttu-id="7f5b4-149">Keskeneräisen työn kirjaaminen</span><span class="sxs-lookup"><span data-stu-id="7f5b4-149">To post WIP</span></span>  
<span data-ttu-id="7f5b4-150">Kun keskeneräinen työ on laskettu, voit kirjata sen tasetileille jakson lopun raportointia varten.</span><span class="sxs-lookup"><span data-stu-id="7f5b4-150">When you have calculated WIP, you can post it to balance sheet accounts for the period end reporting.</span></span> <span data-ttu-id="7f5b4-151">Tähän käytetään **Kirjaa projektin KET kirjanpitoon** -erätyötä.</span><span class="sxs-lookup"><span data-stu-id="7f5b4-151">You use the **Job Post WIP to G/L** batch job to do this.</span></span>

1. <span data-ttu-id="7f5b4-152">Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Kirjaa projektin KET kirjanpitoon** ja valitse sitten aiheeseen liittyvä linkki.</span><span class="sxs-lookup"><span data-stu-id="7f5b4-152">In the top right corner, choose the **Search for Page or Report** icon, enter **Job Post WIP to G/L**, and then choose the related link.</span></span>  
2. <span data-ttu-id="7f5b4-153">Täytä **Kirjaa projektin KET kirjanpitoon** -ikkunassa tarvittavat kentät.</span><span class="sxs-lookup"><span data-stu-id="7f5b4-153">In the **Job Post WIP to G/L** window, fill in the fields as necessary.</span></span>  
3. <span data-ttu-id="7f5b4-154">Valitse **OK**-painike.</span><span class="sxs-lookup"><span data-stu-id="7f5b4-154">Choose the **OK** button.</span></span>

## <a name="to-view-job-usage-estimates-and-post-updates"></a><span data-ttu-id="7f5b4-155">Projektin käytön arvioiden tarkasteleminen ja päivitysten kirjaaminen</span><span class="sxs-lookup"><span data-stu-id="7f5b4-155">To view job usage estimates and post updates</span></span>  
<span data-ttu-id="7f5b4-156">Voit katsella projektin käyttöä projektin valmistumiseen asti yhden vaiheen avulla.</span><span class="sxs-lookup"><span data-stu-id="7f5b4-156">You can view job usage up to the completion of a project in one step.</span></span> <span data-ttu-id="7f5b4-157">Tämä tapahtuu käyttämällä **Laske projektin jäljellä oleva käyttö** -eräajoa kaikissa tehtävissä projektin alusta loppuun.</span><span class="sxs-lookup"><span data-stu-id="7f5b4-157">To do so, you use the **Job Calc. Remaining Usage** batch job for all the tasks up to and including the end of a job.</span></span>  

<span data-ttu-id="7f5b4-158">Näin voit seurata ja vertailla alkuperäisiä arvioita todellisiin tuloksiin. Voit myös tehdä tarvittaessa muutoksia tai uusia tapahtumia.</span><span class="sxs-lookup"><span data-stu-id="7f5b4-158">This lets you track and compare your original estimates against actual results and make modifications or new entries as needed.</span></span> <span data-ttu-id="7f5b4-159">Olet esimerkiksi saattanut arvioida projektin kestoksi 10 tuntia, mutta aikaa on kulunut jo 15 tuntia.</span><span class="sxs-lookup"><span data-stu-id="7f5b4-159">For example, you may have estimated that a job required 10 hours, and to date, it has taken 15 hours.</span></span> <span data-ttu-id="7f5b4-160">Voit lisätä viisi tuntia aiemmin luotuun päiväkirjariviin tai luoda uuden rivin, jolla nämä viisi tuntia raportoidaan ylityönä, joka on toinen työtyyppi.</span><span class="sxs-lookup"><span data-stu-id="7f5b4-160">You can add the extra five hours to the existing journal line or create a new journal line to report these five hours as overtime, which is another work type.</span></span> <span data-ttu-id="7f5b4-161">Sitten lasketaan oikeat kustannukset ja hinta, jotka voidaan kirjata päiväkirjaan.</span><span class="sxs-lookup"><span data-stu-id="7f5b4-161">The appropriate cost and price are calculated, and you can then post to the journal.</span></span>  

<span data-ttu-id="7f5b4-162">**Huomautus**: Nimiketapahtumat luovat nimiketapahtumia ja vähentävät varastomäärää.</span><span class="sxs-lookup"><span data-stu-id="7f5b4-162">**Note**: Item entries create item ledger entries and reduce the inventory quantity.</span></span> <span data-ttu-id="7f5b4-163">**Kirjaa varaston kustannus KP:oon** -eräajo siirtää kustannuksen varastosta pääkirjanpitoon.</span><span class="sxs-lookup"><span data-stu-id="7f5b4-163">The **Post Inventory Cost to G/L** batch job transfers the cost from inventory to the general ledger.</span></span> <span data-ttu-id="7f5b4-164">Resurssitapahtumat luovat resurssitapahtumia.</span><span class="sxs-lookup"><span data-stu-id="7f5b4-164">Resource entries create resource ledger entries.</span></span>  

1. <span data-ttu-id="7f5b4-165">Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Projektipäiväkirjat** ja valitse sitten aiheeseen liittyvä linkki.</span><span class="sxs-lookup"><span data-stu-id="7f5b4-165">In the top right corner, choose the **Search for Page or Report** icon, enter **Job Journals**, and then choose the related link.</span></span>  
2. <span data-ttu-id="7f5b4-166">Valitse asianmukaisen projektin päiväkirja ja valitse sitten **Laske jäljellä oleva käyttö** -toiminto.</span><span class="sxs-lookup"><span data-stu-id="7f5b4-166">Select a relevant job journal, and then choose the **Calc. Remaining Usage** action.</span></span>  
3. <span data-ttu-id="7f5b4-167">Syötä **Laske projektin jäljellä oleva käyttö** -ikkunassa päiväkirjaan lisättävä asiakirjan numero ja kirjauspäivämäärä. Valitse sitten **OK**-painike.</span><span class="sxs-lookup"><span data-stu-id="7f5b4-167">In the **Job Calc. Remaining Usage** window, enter the document number and posting date that is to be inserted in the journal, and then choose the **OK** button.</span></span>  
4. <span data-ttu-id="7f5b4-168">Päivitä tarvittavat muutokset päiväkirjaan.</span><span class="sxs-lookup"><span data-stu-id="7f5b4-168">Update the journal with any modifications that may be needed.</span></span>  
5. <span data-ttu-id="7f5b4-169">Valitse **Kirjaa**.</span><span class="sxs-lookup"><span data-stu-id="7f5b4-169">Choose the **Post**.</span></span>

## <a name="to-view-job-ledger-entries"></a><span data-ttu-id="7f5b4-170">Projektitapahtumien katsominen</span><span class="sxs-lookup"><span data-stu-id="7f5b4-170">To view job ledger entries</span></span>
<span data-ttu-id="7f5b4-171">Kaikki projekteihin liittyvät tapahtumat on tallennettu projektirekistereihin ja numeroitu järjestyksessä numerosta 1 alkaen.</span><span class="sxs-lookup"><span data-stu-id="7f5b4-171">All job-related entries are recorded in job registers and are numbered sequentially, starting with 1.</span></span> <span data-ttu-id="7f5b4-172">Projektirekisterissä voi saada yleiskuvan kaikista projektitapahtumista.</span><span class="sxs-lookup"><span data-stu-id="7f5b4-172">From the job register, you can get an overview of all job ledger entries.</span></span>    

1. <span data-ttu-id="7f5b4-173">Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Projektirekisterit** ja valitse sitten aiheeseen liittyvä linkki.</span><span class="sxs-lookup"><span data-stu-id="7f5b4-173">In the top right corner, choose the **Search for Page or Report** icon, enter **Job Registers**, and then choose the related link.</span></span>
2. <span data-ttu-id="7f5b4-174">Valitse asianmukainen rekisteri ja valitse sitten **Projektikirjaukset**-toiminto.</span><span class="sxs-lookup"><span data-stu-id="7f5b4-174">Select a relevant register, and then choose **Job Ledger** action.</span></span>

<span data-ttu-id="7f5b4-175">**Projektitapahtumat**-ikkunassa voit tarkastella mihin tahansa projektiin liittyviä tapahtumia.</span><span class="sxs-lookup"><span data-stu-id="7f5b4-175">In the **Job Ledger Entries** window you can review the entries that are associated with any job.</span></span>  

## <a name="see-also"></a><span data-ttu-id="7f5b4-176">Katso myös</span><span class="sxs-lookup"><span data-stu-id="7f5b4-176">See Also</span></span>
[<span data-ttu-id="7f5b4-177">Projektien hallinta</span><span class="sxs-lookup"><span data-stu-id="7f5b4-177">Manage Projects</span></span>](projects-manage-projects.md)  
[<span data-ttu-id="7f5b4-178">Rahoitus</span><span class="sxs-lookup"><span data-stu-id="7f5b4-178">Finance</span></span>](finance-setup.md)  
<span data-ttu-id="7f5b4-179">[Ostojen hallinta](purchasing-manage-purchasing.md)       </span><span class="sxs-lookup"><span data-stu-id="7f5b4-179">[Manage Purchasing](purchasing-manage-purchasing.md)       </span></span>  
<span data-ttu-id="7f5b4-180">[Myynnin hallinta](sales-manage-sales.md)    </span><span class="sxs-lookup"><span data-stu-id="7f5b4-180">[Manage Sales](sales-manage-sales.md)    </span></span>  
[<span data-ttu-id="7f5b4-181">Dynamics NAV -ohjelman käyttäminen</span><span class="sxs-lookup"><span data-stu-id="7f5b4-181">Work With Dynamics NAV</span></span>](ui-work-product.md)  
