---
title: "Toimintaohje: Käyttöomaisuuden yleisten tietojen määrittäminen"
author: SorenGP
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 8c0e33a78d47ccfbe39a78f81e31b69f61fd4f80
ms.contentlocale: fi-fi
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-set-up-general-fixed-assets-information"></a><span data-ttu-id="0c8f3-102">Toimintaohje: Käyttöomaisuuden yleisten tietojen määrittäminen</span><span class="sxs-lookup"><span data-stu-id="0c8f3-102">How to: Set Up General Fixed Assets Information</span></span>
<span data-ttu-id="0c8f3-103">Ennen kuin voit hallita käyttöomaisuuseriä, sinun on määritettävä oletusarvoiset KP-tilit, kohdistustunnukset, päiväkirjamallit ja -erät käyttöomaisuuden kirjaamista ja uudelleenluokittelua varten. Voit luokitella käyttöomaisuuserät luokkiin, kuten aineellisiin ja aineettomiin.</span><span class="sxs-lookup"><span data-stu-id="0c8f3-103">Before you can manage fixed assets, you must set up default G/L accounts, allocation keys, journal templates and batches for fixed asset posting and reclassification, and you can classify fixed assets in classes, such as Tangible and Intangible.</span></span>

## <a name="to-set-up-general-default-values-for-fixed-assets"></a><span data-ttu-id="0c8f3-104">Yleisten oletusarvojen määrittäminen käyttöomaisuudelle</span><span class="sxs-lookup"><span data-stu-id="0c8f3-104">To set up general default values for fixed assets</span></span>
<span data-ttu-id="0c8f3-105">Voit määrittää yleisen toiminnan tai käyttöomaisuuserien toiminnallisuuden ja määrittää asiakirjanumerosarjat **Käyttöomaisuuden asetukset** -ikkunassa.</span><span class="sxs-lookup"><span data-stu-id="0c8f3-105">You define the general behavior or the fixed asset functionality and set up document number series in the  in the **Fixed Assets Setup** window.</span></span>

1. <span data-ttu-id="0c8f3-106">Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Käyttöomaisuuden asetukset** ja valitse sitten aiheeseen liittyvä linkki.</span><span class="sxs-lookup"><span data-stu-id="0c8f3-106">In the top right corner, choose the **Search for Page or Report** icon, enter **Fixed Assets Setup**, and then choose the related link.</span></span>  
2. <span data-ttu-id="0c8f3-107">Täytä tarvittavat kentät.</span><span class="sxs-lookup"><span data-stu-id="0c8f3-107">Fill in the fields as necessary.</span></span> <span data-ttu-id="0c8f3-108">Lue kentän lyhyt kuvaus valitsemalla kenttä tai siirry lisätietoihin valitsemalla linkki.</span><span class="sxs-lookup"><span data-stu-id="0c8f3-108">Choose a field to read a short description of the field or link to more information.</span></span>

## <a name="to-set-up-fixed-asset-posting-groups"></a><span data-ttu-id="0c8f3-109">Käyttöomaisuuden kirjausryhmien määrittäminen</span><span class="sxs-lookup"><span data-stu-id="0c8f3-109">To set up fixed asset posting groups</span></span>  
<span data-ttu-id="0c8f3-110">Kirjausryhmiä käytetään määrittelemään käyttöomaisuusryhmiä.</span><span class="sxs-lookup"><span data-stu-id="0c8f3-110">You use posting groups to define groups of fixed assets.</span></span> <span data-ttu-id="0c8f3-111">Näiden kirjausryhmien tapahtumat kirjataan samoille KP-tileille.</span><span class="sxs-lookup"><span data-stu-id="0c8f3-111">Entries for these posting groups are posted to the same general ledger accounts.</span></span>  
1. <span data-ttu-id="0c8f3-112">Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **KO:n kirjausryhmät** ja valitse sitten aiheeseen liittyvä linkki.</span><span class="sxs-lookup"><span data-stu-id="0c8f3-112">In the top right corner, choose the **Search for Page or Report** icon, enter **FA Posting Groups**, and then choose the related link.</span></span>  
2. <span data-ttu-id="0c8f3-113">Valitse **Uusi**-toiminto.</span><span class="sxs-lookup"><span data-stu-id="0c8f3-113">Choose the **New** action.</span></span>
3. <span data-ttu-id="0c8f3-114">Täytä **KO:n kirjausryhmän kortti** -ikkunassa tarvittavat kentät.</span><span class="sxs-lookup"><span data-stu-id="0c8f3-114">In the **FA Posting Group Card** window, fill in the fields as necessary.</span></span>

    <span data-ttu-id="0c8f3-115">**Huomautus**: Varmista, että eri käyttöomaisuuserien kirjausten vastatilit lisätään automaattisesti, kun päiväkirjarivien **Syötä KO-vastatil** -toiminto valitaan, tee seuraavan vaiheen osoittamat toiminnot arvonkorotuksen kirjaamisen perusteella.</span><span class="sxs-lookup"><span data-stu-id="0c8f3-115">**Note**: To make sure that balancing accounts for different fixed assets postings are automatically inserted when you choose the **Insert FA Bal. Account** action on journal lines, follow the next step, based on appreciation posting.</span></span>
4. <span data-ttu-id="0c8f3-116">Valitse **Vastatili**-pikavälilehden **Arvonkorotuksen vastatili** -kenttään se pääkirjanpitotili, jolle haluat kirjata arvonkorotuksen vastatilitapahtumat.</span><span class="sxs-lookup"><span data-stu-id="0c8f3-116">On the **Balancing Account** FastTab, in the **Appreciation Bal. Account** field, select the general ledger account to which you want to post balancing entries for appreciation.</span></span>

<span data-ttu-id="0c8f3-117">Lisätietoja **Syötä KO-vastatili** -toiminnon käyttämisestä käyttöomaisuuden KP-päiväkirjariveillä on esimerkiksi kohdassa [Toimintaohje: Käyttöomaisuuden uudelleenarvostus](fa-how-revalue.md).</span><span class="sxs-lookup"><span data-stu-id="0c8f3-117">For more information about using the **Insert FA Bal. Account** action on fixed asset G/L journal lines, see, for example, [How to: Revalue Fixed Assets](fa-how-revalue.md).</span></span>

## <a name="to-set-up-fixed-asset-allocation-keys"></a><span data-ttu-id="0c8f3-118">Käyttöomaisuuden kohdistustunnusten määrittäminen</span><span class="sxs-lookup"><span data-stu-id="0c8f3-118">To set up fixed asset allocation keys</span></span>  
<span data-ttu-id="0c8f3-119">Transaktioita voidaan kohdistaa useille osastoille tai projekteille käyttäjäkohtaisten kohdistusavainten mukaisesti.</span><span class="sxs-lookup"><span data-stu-id="0c8f3-119">Transactions can be allocated to various departments or projects, according to user-defined allocation keys.</span></span> <span data-ttu-id="0c8f3-120">Voit määrittää esimerkiksi kohdistusavaimen kohdistamaan autojen poistokustannuksia 35 %:lla hallinto-osastolle ja 65 %:lla myyntiosastolle.</span><span class="sxs-lookup"><span data-stu-id="0c8f3-120">For example, you could set up an allocation key to allocate depreciation costs on cars with 35 percent to the administration department and 65 percent to the sales department.</span></span> <span data-ttu-id="0c8f3-121">Lisätietoja on kohdassa [Toimintaohje: Kohdistustunnusten käyttäminen yleisissä päiväkirjoissa](ui-how-use-allocation-keys-general-journals.md).</span><span class="sxs-lookup"><span data-stu-id="0c8f3-121">For more information, see [How to: Use Allocation Keys in General Journals](ui-how-use-allocation-keys-general-journals.md).</span></span>

<span data-ttu-id="0c8f3-122">Kohdistusavaimet koskevat käyttöomaisuusluokkia yksittäisten omaisuuserien sijaan.</span><span class="sxs-lookup"><span data-stu-id="0c8f3-122">Allocation keys apply to fixed asset classes, not to individual assets.</span></span>  
1. <span data-ttu-id="0c8f3-123">Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **KO:n kirjausryhmät** ja valitse sitten aiheeseen liittyvä linkki.</span><span class="sxs-lookup"><span data-stu-id="0c8f3-123">In the top right corner, choose the **Search for Page or Report** icon, enter **FA Posting Groups**, and then choose the related link.</span></span>  
2. <span data-ttu-id="0c8f3-124">Valitse **KO:n kirjausryhmät** -ikkunassa **Kohdistukset**-toiminto ja valitse sitten kirjaustyyppi.</span><span class="sxs-lookup"><span data-stu-id="0c8f3-124">In the **FA Posting Groups** window, choose the **Allocations** action, and then choose a posting type.</span></span>
3. <span data-ttu-id="0c8f3-125">Täytä **KO:n kohdistukset** -ikkunassa tarvittavat kentät.</span><span class="sxs-lookup"><span data-stu-id="0c8f3-125">In the **FA Allocations** window, fill in the fields as necessary.</span></span>
4. <span data-ttu-id="0c8f3-126">Toista vaihe 2 ja 3 kunkin kirjaustyypin osalta, jolle haluat määritellä kohdistusavaimia.</span><span class="sxs-lookup"><span data-stu-id="0c8f3-126">Repeat steps 2 and 3 for each posting type that you want to define allocation keys for.</span></span>

## <a name="to-set-up-fixed-asset-journal-templates"></a><span data-ttu-id="0c8f3-127">Käyttöomaisuuden päiväkirjamallien määrittäminen</span><span class="sxs-lookup"><span data-stu-id="0c8f3-127">To set up fixed asset journal templates</span></span>  
<span data-ttu-id="0c8f3-128">Malli on päiväkirjan ennalta määritelty asettelu.</span><span class="sxs-lookup"><span data-stu-id="0c8f3-128">A template is a predefined layout for a journal.</span></span> <span data-ttu-id="0c8f3-129">Mallissa on tietoja jäljityskoodeista, raporteista ja numerosarjoista.</span><span class="sxs-lookup"><span data-stu-id="0c8f3-129">The template contains information about trace codes, reports, and number series.</span></span> <span data-ttu-id="0c8f3-130">Lisätietoja on kohdassa [Yleisten päiväkirjojen käyttäminen](ui-work-general-journals.md).</span><span class="sxs-lookup"><span data-stu-id="0c8f3-130">For more information, see [Work with General Journals](ui-work-general-journals.md).</span></span>

<span data-ttu-id="0c8f3-131">Dynamics NAV luo automaattisesti käyttöomaisuuden päiväkirjamallin, kun avaat **Käyttöomaisuuspäiväkirja**-ikkunan ensimmäisen kerran. Voit kuitenkin määrittää lisää päiväkirjamalleja.</span><span class="sxs-lookup"><span data-stu-id="0c8f3-131">Dynamics NAV automatically creates a fixed asset journal template the first time that you open the **Fixed Asset Journal** window, but you can set up additional journal templates.</span></span>  
1. <span data-ttu-id="0c8f3-132">Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **KO:n päiväkirjamallit** ja valitse sitten aiheeseen liittyvä linkki.</span><span class="sxs-lookup"><span data-stu-id="0c8f3-132">In the top right corner, choose the **Search for Page or Report** icon, enter **FA Journal Templates**, and then choose the related link.</span></span>  
2. <span data-ttu-id="0c8f3-133">Täytä tarvittavat kentät.</span><span class="sxs-lookup"><span data-stu-id="0c8f3-133">Fill in the fields as necessary.</span></span>

## <a name="to-set-up-fixed-asset-journal-batches"></a><span data-ttu-id="0c8f3-134">Käyttöomaisuuden päiväkirjaerien määrittäminen</span><span class="sxs-lookup"><span data-stu-id="0c8f3-134">To set up fixed asset journal batches</span></span>
<span data-ttu-id="0c8f3-135">Voit määrittää useita päiväkirjan eriä eli yksittäisiä päiväkirjoja kullekin päiväkirjan mallille.</span><span class="sxs-lookup"><span data-stu-id="0c8f3-135">You can set up multiple journal batches, which are individual journals for each journal template.</span></span> <span data-ttu-id="0c8f3-136">Käyttäjällä voi esimerkiksi olla oma päiväkirjan erä, jossa käytetään työntekijän nimikirjaimia päiväkirjan erän nimenä.</span><span class="sxs-lookup"><span data-stu-id="0c8f3-136">For example, employees can have their own journal batch that uses the employee’s initials as the journal batch name.</span></span> <span data-ttu-id="0c8f3-137">Lisätietoja on kohdassa [Yleisten päiväkirjojen käyttäminen](ui-work-general-journals.md).</span><span class="sxs-lookup"><span data-stu-id="0c8f3-137">For more information, see [Work with General Journals](ui-work-general-journals.md).</span></span>  
1. <span data-ttu-id="0c8f3-138">Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **KO:n päiväkirjamallit** ja valitse sitten aiheeseen liittyvä linkki.</span><span class="sxs-lookup"><span data-stu-id="0c8f3-138">In the top right corner, choose the **Search for Page or Report** icon, enter **FA Journal Templates**, and then choose the related link.</span></span>  
2. <span data-ttu-id="0c8f3-139">Valitse asiaankuuluva päiväkirjamalli ja valitse sitten **Erät**-toiminto.</span><span class="sxs-lookup"><span data-stu-id="0c8f3-139">Select the relevant journal template, and then choose the **Batches** action.</span></span>
3. <span data-ttu-id="0c8f3-140">Täytä **KO-päiväkirjan erät** -ikkunassa tarvittavat kentät.</span><span class="sxs-lookup"><span data-stu-id="0c8f3-140">In the **FA Journal Batches** window, fill in the fields as necessary.</span></span>

## <a name="to-set-up-fixed-asset-reclassification-journal-templates"></a><span data-ttu-id="0c8f3-141">Käyttöomaisuuden uudelleenluokituspäiväkirjamallien määrittäminen</span><span class="sxs-lookup"><span data-stu-id="0c8f3-141">To set up fixed asset reclassification journal templates</span></span>  
<span data-ttu-id="0c8f3-142">Kyseisiä uudelleenluokituspäiväkirjoja voidaan käyttää käyttöomaisuuserien siirtämisessä, jakamisessa ja yhdistämisessä.</span><span class="sxs-lookup"><span data-stu-id="0c8f3-142">You use dedicated reclassification journals when you need to transfer, split, or combine fixed assets.</span></span> <span data-ttu-id="0c8f3-143">Dynamics NAV luo automaattisesti käyttöomaisuuden uudelleenluokituspäiväkirjan mallin, kun avaat **KO:n uudelleenluokituspvk** -ikkunan ensimmäisen kerran. Voit kuitenkin määrittää lisää uudelleenluokituspäiväkirjan malleja.</span><span class="sxs-lookup"><span data-stu-id="0c8f3-143">Dynamics NAV automatically creates a fixed asset reclassification journal template the first time that you open the **FA Reclass. Journal** window, but you can set up additional reclassification journal templates.</span></span> <span data-ttu-id="0c8f3-144">Lisätietoja on kohdassa [Yleisten päiväkirjojen käyttäminen](ui-work-general-journals.md).</span><span class="sxs-lookup"><span data-stu-id="0c8f3-144">For more information, see [Work with General Journals](ui-work-general-journals.md).</span></span>  
1. <span data-ttu-id="0c8f3-145">Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **KO:n uud.luok.pvk:n mallit** ja valitse sitten aiheeseen liittyvä linkki.</span><span class="sxs-lookup"><span data-stu-id="0c8f3-145">In the top right corner, choose the **Search for Page or Report** icon, enter **FA Reclass. Journal Templates**, and then choose the related link.</span></span>  
2. <span data-ttu-id="0c8f3-146">Täytä tarvittavat kentät.</span><span class="sxs-lookup"><span data-stu-id="0c8f3-146">Fill in the fields as necessary.</span></span>

## <a name="to-set-up-fixed-asset-reclassification-journal-batches"></a><span data-ttu-id="0c8f3-147">Käyttöomaisuuden uudelleenluokituspäiväkirjaerien määrittäminen</span><span class="sxs-lookup"><span data-stu-id="0c8f3-147">To set up fixed asset reclassification journal batches</span></span>  
<span data-ttu-id="0c8f3-148">Voit määrittää useita päiväkirjan eriä eli yksittäisiä päiväkirjoja kullekin uudelleenluokituspäiväkirjan mallille.</span><span class="sxs-lookup"><span data-stu-id="0c8f3-148">You can set up multiple journal batches, which are individual journals for each reclassification journal template.</span></span> <span data-ttu-id="0c8f3-149">Käyttäjällä voi esimerkiksi olla oma uudelleenluokituspäiväkirjan erä, jossa käytetään työntekijän nimikirjaimia uudelleenluokituspäiväkirjan erän nimenä.</span><span class="sxs-lookup"><span data-stu-id="0c8f3-149">For example, employees can have their own reclassification journal batch that uses the employee’s initials as the reclassification journal batch name.</span></span> <span data-ttu-id="0c8f3-150">Lisätietoja on kohdassa [Yleisten päiväkirjojen käyttäminen](ui-work-general-journals.md).</span><span class="sxs-lookup"><span data-stu-id="0c8f3-150">For more information, see [Work with General Journals](ui-work-general-journals.md).</span></span>
1. <span data-ttu-id="0c8f3-151">Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **KO:n uud.luok.pvk:n mallit** ja valitse sitten aiheeseen liittyvä linkki.</span><span class="sxs-lookup"><span data-stu-id="0c8f3-151">In the top right corner, choose the **Search for Page or Report** icon, enter **FA Reclass. Journal Templates**, and then choose the related link.</span></span>  
2. <span data-ttu-id="0c8f3-152">Valitse asiaankuuluva päiväkirjamalli ja valitse sitten **Erät**-toiminto.</span><span class="sxs-lookup"><span data-stu-id="0c8f3-152">Select the relevant journal template, and then choose the **Batches** action.</span></span>
3. <span data-ttu-id="0c8f3-153">Täytä **KO:n uud.luok.pvk:n erät** -ikkunassa tarvittavat kentät.</span><span class="sxs-lookup"><span data-stu-id="0c8f3-153">In the **FA Reclass. Journal Batches** window, fill in the fields as necessary.</span></span>

## <a name="to-set-up-fixed-asset-class-codes"></a><span data-ttu-id="0c8f3-154">Käyttöomaisuuden luokkakoodien määrittäminen</span><span class="sxs-lookup"><span data-stu-id="0c8f3-154">To set up fixed asset class codes</span></span>  
<span data-ttu-id="0c8f3-155">Käyttöomaisuuden luokkakoodeja voidaan käyttää käyttöomaisuuserien, esimerkiksi aineellisten ja aineettomien hyödykkeiden, ryhmittelyyn.</span><span class="sxs-lookup"><span data-stu-id="0c8f3-155">Fixed asset class codes can be used to group fixed assets, for example, in tangible and intangible assets.</span></span>
1. <span data-ttu-id="0c8f3-156">Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **KO:n luokat** ja valitse sitten aiheeseen liittyvä linkki.</span><span class="sxs-lookup"><span data-stu-id="0c8f3-156">In the top right corner, choose the **Search for Page or Report** icon, enter **FA Classes**, and then choose the related link.</span></span>
2. <span data-ttu-id="0c8f3-157">Syötä koodit ja nimet niiden luokkien osalta, jotka haluat luoda.</span><span class="sxs-lookup"><span data-stu-id="0c8f3-157">Enter codes and names for the classes that you want to create.</span></span>

## <a name="to-set-up-fixed-asset-subclass-codes"></a><span data-ttu-id="0c8f3-158">Käyttöomaisuuden alaluokkakoodien määrittäminen</span><span class="sxs-lookup"><span data-stu-id="0c8f3-158">To set up fixed asset subclass codes</span></span>
<span data-ttu-id="0c8f3-159">Käyttöomaisuuden alaluokkakoodia voi käyttää ryhmittelemään käyttöomaisuus luokkiin, esimerkiksi rakennuksiin, ajoneuvoihin, huonekaluihin ja koneisiin.</span><span class="sxs-lookup"><span data-stu-id="0c8f3-159">You use fixed asset subclass codes to group your fixed assets into categories, such as buildings, vehicles, furniture, or machinery.</span></span>  
1. <span data-ttu-id="0c8f3-160">Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **KO:n alaluokat** ja valitse sitten aiheeseen liittyvä linkki.</span><span class="sxs-lookup"><span data-stu-id="0c8f3-160">In the top right corner, choose the **Search for Page or Report** icon, enter **FA Subclasses**, and then choose the related link.</span></span>
2. <span data-ttu-id="0c8f3-161">Syötä koodit ja nimet niiden luokkien osalta, jotka haluat luoda.</span><span class="sxs-lookup"><span data-stu-id="0c8f3-161">Enter codes and names for the classes that you want to create.</span></span>

## <a name="to-set-up-fixed-asset-location-codes"></a><span data-ttu-id="0c8f3-162">Käyttöomaisuuden sijaintikoodien määrittäminen</span><span class="sxs-lookup"><span data-stu-id="0c8f3-162">To set up fixed asset location codes</span></span>
<span data-ttu-id="0c8f3-163">KO-sijaintikoodia voidaan käyttää rekisteröimään käyttöomaisuuden sijainti, esimerkiksi myyntiosasto, vastaanotto, hallinto, tuotanto tai fyysinen varasto.</span><span class="sxs-lookup"><span data-stu-id="0c8f3-163">You use fixed asset location codes to register the location of the fixed asset, such as sales department, reception, administration, production, or warehouse.</span></span> <span data-ttu-id="0c8f3-164">Nämä tiedot ovat tarpeen vakuutusta ja inventointia varten.</span><span class="sxs-lookup"><span data-stu-id="0c8f3-164">This information is useful for insurance and inventory purposes.</span></span>
1. <span data-ttu-id="0c8f3-165">Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **KO:n sijainnit** ja valitse sitten aiheeseen liittyvä linkki.</span><span class="sxs-lookup"><span data-stu-id="0c8f3-165">In the top right corner, choose the **Search for Page or Report** icon, enter **FA locations**, and then choose the related link.</span></span>
2. <span data-ttu-id="0c8f3-166">Syötä koodit ja nimet niiden käyttöomaisuuden sijaintien osalta, jotka haluat luoda.</span><span class="sxs-lookup"><span data-stu-id="0c8f3-166">Enter codes and names for the fixed asset locations that you want to create.</span></span>

## <a name="to-register-opening-entries"></a><span data-ttu-id="0c8f3-167">Avaustapahtumien rekisteröiminen</span><span class="sxs-lookup"><span data-stu-id="0c8f3-167">To register opening entries</span></span>  
<span data-ttu-id="0c8f3-168">Jos käytät Käyttöomaisuus-kohdistusaluetta Dynamics NAV -ohjelmassa ensimmäistä kertaa, sinun tulee määrittää Pääkirjanpito-kohdistusalue ennen kuin määrität käyttöomaisuuden.</span><span class="sxs-lookup"><span data-stu-id="0c8f3-168">If you are using the fixed assets in Dynamics NAV for the first time, you must set up the general ledger application area before you set up fixed assets.</span></span> <span data-ttu-id="0c8f3-169">Se, miten tämä tehdään, riippuu siitä, onko käyttöomaisuus on integroitu pääkirjanpidon kanssa.</span><span class="sxs-lookup"><span data-stu-id="0c8f3-169">How you do this depends on whether fixed assets is integrated with general ledger.</span></span>  

 <span data-ttu-id="0c8f3-170">Seuraavaa menetelmää käytetään, jos käyttöomaisuustransaktioita tulee kirjata pääkirjanpitoon.</span><span class="sxs-lookup"><span data-stu-id="0c8f3-170">The following procedure is used if fixed asset transactions are to be posted to the general ledger.</span></span>  

1. <span data-ttu-id="0c8f3-171">Varmista, että olet saanut valmiiksi Käyttöomaisuuden asetusten perustoimenpiteet.</span><span class="sxs-lookup"><span data-stu-id="0c8f3-171">Make sure that you have completed the basic setup procedures for fixed assets.</span></span>  
2. <span data-ttu-id="0c8f3-172">Luo jokaiselle olemassa olevalle omaisuuserälle käyttöomaisuuskortti.</span><span class="sxs-lookup"><span data-stu-id="0c8f3-172">Create a fixed asset card for each existing asset.</span></span>  
3. <span data-ttu-id="0c8f3-173">Käyttöomaisuuden poistokirjojen määrittäminen.</span><span class="sxs-lookup"><span data-stu-id="0c8f3-173">Set up fixed asset depreciation books.</span></span>  
4. <span data-ttu-id="0c8f3-174">Ota käyttöön pääkirjanpidon integrointi seuraavien vaiheiden avulla.</span><span class="sxs-lookup"><span data-stu-id="0c8f3-174">Enable general ledger integration by following the next steps.</span></span>
5. <span data-ttu-id="0c8f3-175">Syötä **Etsi**-ruudussa **Poistokirjat** ja valitse sitten vastaava linkki.</span><span class="sxs-lookup"><span data-stu-id="0c8f3-175">In the **Search** box, enter **Depreciation Books**, and then choose the related link.</span></span>  
6. <span data-ttu-id="0c8f3-176">Valitse asianmukainen poistokirja.</span><span class="sxs-lookup"><span data-stu-id="0c8f3-176">Select the relevant depreciation book.</span></span> <span data-ttu-id="0c8f3-177">Valitse **Kotisivu**-välilehden **Hallinta**-ryhmässä **Muokkaa luetteloa**, jolloin **Poistokirjan kortti** -ikkuna avautuu.</span><span class="sxs-lookup"><span data-stu-id="0c8f3-177">On the **Home** tab, in the **Manage** group, choose **Edit** to open the **Depreciation Book Card** window.</span></span>
7. <span data-ttu-id="0c8f3-178">Varmista, että **Integrointi**-pikavälilehden kaikki kentät ovat tyhjiä (poista kaikki valintamerkit).</span><span class="sxs-lookup"><span data-stu-id="0c8f3-178">On the **Integration** FastTab, make sure all fields are blank by clearing all check marks.</span></span> <span data-ttu-id="0c8f3-179">Jos poistokirjoja on useita, ota jokaisessa käyttöön pääkirjanpidon integrointi.</span><span class="sxs-lookup"><span data-stu-id="0c8f3-179">If you have more than one depreciation book, turn on general ledger integration for each one.</span></span>  
8. <span data-ttu-id="0c8f3-180">Anna käyttöomaisuuden päiväkirjassa seuraavat rivit kutakin käyttöomaisuutta varten:</span><span class="sxs-lookup"><span data-stu-id="0c8f3-180">In the fixd asset journal, enter the following lines for each asset:</span></span>
    - <span data-ttu-id="0c8f3-181">Syötä rivi ja hankintameno.</span><span class="sxs-lookup"><span data-stu-id="0c8f3-181">A line with the acquisition cost.</span></span>
    - <span data-ttu-id="0c8f3-182">Rivi, jolla on kumulatiivinen poisto edellisen tilikauden loppuun.</span><span class="sxs-lookup"><span data-stu-id="0c8f3-182">A line with the accumulated depreciation to the end of the previous fiscal year.</span></span>
    - <span data-ttu-id="0c8f3-183">Rivi, jolla on kumulatiivinen poisto nykyisen tilivuoden alusta päivään, jonka Dynamics NAV määrittää poiston laskennan aloittamiseksi.</span><span class="sxs-lookup"><span data-stu-id="0c8f3-183">A line with the accumulated depreciation from the start of the current fiscal year to the date that Dynamics NAV is set to start calculating the depreciation.</span></span>

<span data-ttu-id="0c8f3-184">Jos avaussaldoja on muita, myös ne voidaan syöttää (esimerkiksi arvonalennukset ja \-korotukset).</span><span class="sxs-lookup"><span data-stu-id="0c8f3-184">If you have other opening balances you can also enter them now, such as write\-down and appreciation.</span></span>  

<span data-ttu-id="0c8f3-185">Jos käyttöomaisuutta ei ole integroitu käyttöomaisuuden kanssa, ohita työvaiheet 4–7.</span><span class="sxs-lookup"><span data-stu-id="0c8f3-185">If the fixed assets are not integrated with the general ledger, skip steps 4 through 7.</span></span>

## <a name="see-also"></a><span data-ttu-id="0c8f3-186">Katso myös</span><span class="sxs-lookup"><span data-stu-id="0c8f3-186">See Also</span></span>
[<span data-ttu-id="0c8f3-187">Käyttöomaisuuserien määrittäminen</span><span class="sxs-lookup"><span data-stu-id="0c8f3-187">Set Up Fixed Assets</span></span>](fa-setup.md)  
[<span data-ttu-id="0c8f3-188">Käyttöomaisuuden hallinta</span><span class="sxs-lookup"><span data-stu-id="0c8f3-188">Manage Fixed Assets</span></span>](fa-manage.md)  
[<span data-ttu-id="0c8f3-189">Rahoitus</span><span class="sxs-lookup"><span data-stu-id="0c8f3-189">Finance</span></span>](finance-setup.md)  
[<span data-ttu-id="0c8f3-190">Tervetuloa Dynamics NAV -ohjelmaan</span><span class="sxs-lookup"><span data-stu-id="0c8f3-190">Welcome to Dynamics NAV</span></span>](across-get-started.md)
