---
title: "Toimintaohje: Käyttöomaisuuden vakuuttaminen"
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
ms.openlocfilehash: a3a59bc091042f72775b56fdd5bbe37ffa1a6d80
ms.contentlocale: fi-fi
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-insure-fixed-assets"></a><span data-ttu-id="a3b26-102">Toimintaohje: Käyttöomaisuuden vakuuttaminen</span><span class="sxs-lookup"><span data-stu-id="a3b26-102">How to: Insure Fixed Assets</span></span>
<span data-ttu-id="a3b26-103">Vakuutuskortti edustaa käyttöomaisuuden vakuutussopimusta.</span><span class="sxs-lookup"><span data-stu-id="a3b26-103">An insurance policy for a fixed asset is represented by an insurance card.</span></span> <span data-ttu-id="a3b26-104">Voit liittää yhteen vakuutussopimukseen yhden käyttöomaisuuserän tai useita käyttöomaisuuseriä.</span><span class="sxs-lookup"><span data-stu-id="a3b26-104">You can assign one fixed asset to one insurance policy or multiple fixed assets to one insurance policy.</span></span>

<span data-ttu-id="a3b26-105">Voit liittää käyttöomaisuuserän vakuutussopimukseen kirjaamalla vakuutuksen kattavuustapahtuman **Vakuutuspäiväkirja**-ikkunasta.</span><span class="sxs-lookup"><span data-stu-id="a3b26-105">You assign a fixed asset to an insurance policy by posting to the insurance coverage ledger from the **Insurance Journal** window.</span></span>

<span data-ttu-id="a3b26-106">Lisäksi voit liittää käyttöomaisuuserän vakuutussopimukseen ja luoda kattavuustapahtumia sen hankintamenon kirjaamisen yhteydessä.</span><span class="sxs-lookup"><span data-stu-id="a3b26-106">In addition, you can assign a fixed asset to an insurance policy and create coverage ledger entries when you post its acquisition cost.</span></span> <span data-ttu-id="a3b26-107">Tämä tehdään kirjaamalla käyttöomaisuuserän hankintameno niin, että **Vakuutusnro**-kenttä</span><span class="sxs-lookup"><span data-stu-id="a3b26-107">You do this by posting an acquisition cost from the fixed asset journal with the **Insurance No.**</span></span> <span data-ttu-id="a3b26-108">on täytetty.</span><span class="sxs-lookup"><span data-stu-id="a3b26-108">field filled in.</span></span> <span data-ttu-id="a3b26-109">**Automaattinen vakuutuskirjaus** -valintaruutu **Käyttöomaisuuden asetukset** -ikkunassa on valittava.</span><span class="sxs-lookup"><span data-stu-id="a3b26-109">The **Automatic Insurance Posting** check box in the **Fixed Asset Setup** window must be selected.</span></span> <span data-ttu-id="a3b26-110">Lisätietoja on Käyttöomaisuuden hankinnan kirjaaminen manuaalisesti käyttöomaisuuden KP-päiväkirjan avulla -osan kohdassa [Toimintaohje: Käyttöomaisuuden hankinta](fa-how-acquire.md).</span><span class="sxs-lookup"><span data-stu-id="a3b26-110">For more information, see the "To post a fixed asset acquisition manually with the fixed asset G/L journal" section in [How to: Acquire Fixed Assets](fa-how-acquire.md).</span></span>

<span data-ttu-id="a3b26-111">Jos **Automaattinen vakuutuskirjaus** -valintaruutua **Käyttöomaisuuden asetukset** -ikkunassa ei ole valittu, hankintojen kirjaaminen käyttöomaisuuspäiväkirjasta luo rivit **Vakuutuspäiväkirja**-ikkunaan. Rivit on tämän jälkeen kirjattava manuaalisesti.</span><span class="sxs-lookup"><span data-stu-id="a3b26-111">If the **Automatic Insurance Posting** check box in the **Fixed Asset Setup** window is not selected, then posting acquisitions from the fixed asset journal will create lines in the **Insurance Journal** window, which you must then post manually.</span></span>

<span data-ttu-id="a3b26-112">**Varoitus**:Jos et valitse **Automaattinen vakuutuskirjaus** -valintaruutua **Käyttöomaisuuden asetukset** -ikkunassa, vakuutuspäiväkirjan on perustuttava sellaiseen päiväkirjan malliin, jolla ei ole numerosarjoja.</span><span class="sxs-lookup"><span data-stu-id="a3b26-112">**Warning**: If you do not select the **Automatic Insurance Posting** check box in the **Fixed Asset Setup** window, then your insurance journal should be based on a journal template without a number series.</span></span> <span data-ttu-id="a3b26-113">Tämä johtuu siitä, että käyttöomaisuuspäiväkirjan rivistä lisätyt asiakirjanumerot ovat muussa tapauksessa ristiriidassa vakuutuspäiväkirjan numerosarjojen kanssa.</span><span class="sxs-lookup"><span data-stu-id="a3b26-113">This is because the inserted document numbers from the fixed asset journal line will otherwise conflict with the number series of the insurance journal.</span></span> <span data-ttu-id="a3b26-114">Lisätietoja päiväkirjojen malleista ja eristä on kohdassa [Toimintaohje: Käyttöomaisuuden yleisten tietojen määrittäminen](fa-how-setup-general.md).</span><span class="sxs-lookup"><span data-stu-id="a3b26-114">For more information about journal templates and batches, see [How to: Set Up General Fixed Assets Information](fa-how-setup-general.md).</span></span>

<span data-ttu-id="a3b26-115">Kun käyttöomaisuus on liitetty vakuutussopimukseen, käyttöomaisuuden kortin **Vakuutettu**-valintaruutu valitaan.</span><span class="sxs-lookup"><span data-stu-id="a3b26-115">After you have assigned a fixed asset to an insurance policy, the **Insured** check box is selected on the fixed asset card.</span></span> <span data-ttu-id="a3b26-116">Kun myyt käyttöomaisuuden, valintaruudun valinta poistetaan automaattisesti.</span><span class="sxs-lookup"><span data-stu-id="a3b26-116">When you sell the fixed asset, the check box is automatically deselected.</span></span>

## <a name="to-create-or-modify-an-insurance-card"></a><span data-ttu-id="a3b26-117">Vakuutuskortin luominen tai muokkaaminen</span><span class="sxs-lookup"><span data-stu-id="a3b26-117">To create or modify an insurance card</span></span>
<span data-ttu-id="a3b26-118">Vakuutuskortin on edustettava käyttöomaisuuden vakuutussopimusta.</span><span class="sxs-lookup"><span data-stu-id="a3b26-118">An insurance policy for a fixed asset must be represented by an insurance card.</span></span>

<span data-ttu-id="a3b26-119">Kun saat tiedon kattavuussumman muutoksista, uudet tiedot on syötettävä **Vakuutuskortti**-ikkunaan, jotta vakuutussopimuksen kattavuus voitaisiin analysoida oikein.</span><span class="sxs-lookup"><span data-stu-id="a3b26-119">When you receive information about changes in the coverage amount, you must enter the new information in the **Insurance Card** window to ensure that you analyze insurance policy coverage correctly.</span></span>  

1. <span data-ttu-id="a3b26-120">Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Vakuutus** ja valitse sitten aiheeseen liittyvä linkki.</span><span class="sxs-lookup"><span data-stu-id="a3b26-120">In the top right corner, choose the **Search for Page or Report** icon, enter **Insurance**, and then choose the related link.</span></span>
2. <span data-ttu-id="a3b26-121">Valitse **Uusi**-toiminto, kun haluat luoda vakuutussopimukselle uuden kortin.</span><span class="sxs-lookup"><span data-stu-id="a3b26-121">Choose the **New** action to create a new card for an insurance policy.</span></span> <span data-ttu-id="a3b26-122">Lue kentän lyhyt kuvaus valitsemalla kenttä tai siirry lisätietoihin valitsemalla linkki.</span><span class="sxs-lookup"><span data-stu-id="a3b26-122">Choose a field to read a short description of the field or link to more information.</span></span>
3. <span data-ttu-id="a3b26-123">Vaihtoehtoisesti voit valita muutettavan vakuutussopimuksen ja valita sitten **Muokkaa**-toiminnon.</span><span class="sxs-lookup"><span data-stu-id="a3b26-123">Alternatively, select the insurance policy that you want to change, and then choose the **Edit** action.</span></span>

## <a name="to-assign-a-fixed-asset-to-an-insurance-policy-by-posting-from-the-insurance-journal"></a><span data-ttu-id="a3b26-124">Käyttöomaisuuden liittäminen vakuutussopimukseen vakuutuspäiväkirjasta kirjaamalla</span><span class="sxs-lookup"><span data-stu-id="a3b26-124">To assign a fixed asset to an insurance policy by posting from the insurance journal</span></span>
<span data-ttu-id="a3b26-125">Liitä käyttöomaisuus vakuutussopimukseen vakuutuksen kattavuustapahtumaan kirjaamalla.</span><span class="sxs-lookup"><span data-stu-id="a3b26-125">You assign a fixed asset to an insurance policy by posting to the insurance coverage ledger.</span></span>

<span data-ttu-id="a3b26-126">Seuraavassa kerrotaan, miten vakuutuspäiväkirjan rivi luodaan manuaalisesti.</span><span class="sxs-lookup"><span data-stu-id="a3b26-126">The following procedure explains how to create an insurance journal line manually.</span></span> <span data-ttu-id="a3b26-127">Jos **Automaattinen vakuutuskirjaus** -valintaruutu on valittu **KO:n asetukset**-ikkunassa, vakuutuspäiväkirjan rivit luodaan automaattisesti hankintamenojen kirjaamisen yhteydessä.</span><span class="sxs-lookup"><span data-stu-id="a3b26-127">If the **Automatic Insurance Posting** check box is selected in the **FA Setup** window, then insurance journal lines are automatically created when you post acquisition costs.</span></span> <span data-ttu-id="a3b26-128">Tällöin ei tarvitse tehdä muuta kuin kirjata päiväkirja.</span><span class="sxs-lookup"><span data-stu-id="a3b26-128">In that case, all you have to do is to post the journal.</span></span>

1. <span data-ttu-id="a3b26-129">Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Vakuutuspäiväkirjat** ja valitse sitten aiheeseen liittyvä linkki.</span><span class="sxs-lookup"><span data-stu-id="a3b26-129">In the top right corner, choose the **Search for Page or Report** icon, enter **Insurance Journals**, and then choose the related link.</span></span>
2. <span data-ttu-id="a3b26-130">Avaa kyseessä oleva päiväkirja ja täytä vaaditut päiväkirjarivit.</span><span class="sxs-lookup"><span data-stu-id="a3b26-130">Open the relevant journal, and fill in the journal lines as necessary.</span></span>
3. <span data-ttu-id="a3b26-131">Voit liittää yhteen vakuutussopimukseen useita käyttöomaisuuseriä luomalla päiväkirjarivejä, joiden **Vakuutusnro**-kentässä</span><span class="sxs-lookup"><span data-stu-id="a3b26-131">To assign multiple fixed assets to one insurance policy, create journal lines with the same value in the **Insurance No.**</span></span> <span data-ttu-id="a3b26-132">on sama arvo ja eri arvot **KO-nro**</span><span class="sxs-lookup"><span data-stu-id="a3b26-132">field and different values in the **FA No.**</span></span> <span data-ttu-id="a3b26-133">-kentässä.</span><span class="sxs-lookup"><span data-stu-id="a3b26-133">field.</span></span>
4. <span data-ttu-id="a3b26-134">Valitse **Kirjaa**-toiminto.</span><span class="sxs-lookup"><span data-stu-id="a3b26-134">Choose the **Post** action.</span></span>

<span data-ttu-id="a3b26-135">**Huomautus**: Vakuutuspäiväkirjan tapahtumat kirjataan vain vakuutuksen kattavuuskirjauksiin.</span><span class="sxs-lookup"><span data-stu-id="a3b26-135">**Note**: The entries from an insurance journal are only posted to the insurance coverage ledger.</span></span>  

## <a name="to-update-the-insurance-value-of-a-fixed-asset"></a><span data-ttu-id="a3b26-136">Käyttöomaisuuden vakuutusarvon päivittäminen</span><span class="sxs-lookup"><span data-stu-id="a3b26-136">To update the insurance value of a fixed asset</span></span>
<span data-ttu-id="a3b26-137">**Tee indeksimuutos vakuutuksiin** -eräajoa voidaan käyttää päivittämään katetun käyttöomaisuuden arvoa.</span><span class="sxs-lookup"><span data-stu-id="a3b26-137">You can use the **Index Insurance** batch job to update the value of the fixed assets that are covered.</span></span>

1. <span data-ttu-id="a3b26-138">Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Tee indeksimuutos vakuutuksiin** ja valitse sitten aiheeseen liittyvä linkki.</span><span class="sxs-lookup"><span data-stu-id="a3b26-138">In the top right corner, choose the **Search for Page or Report** icon, enter **Index Insurance**, and then choose the related link.</span></span>
2. <span data-ttu-id="a3b26-139">Täytä tarvittavat kentät.</span><span class="sxs-lookup"><span data-stu-id="a3b26-139">Fill in the fields as necessary.</span></span>

    <span data-ttu-id="a3b26-140">**Huomautus**: **Indeksiluku**-kenttään syötetään esimerkiksi 5 %:n pienentämistä varten 95, kun taas 2 %:n suurentamiseksi syötetään 102.</span><span class="sxs-lookup"><span data-stu-id="a3b26-140">**Note**: In the **Index Figure** field, you enter a decrease of 5%, for example, as 95, whereas you enter an increase of 2% as 102.</span></span>  
3.  <span data-ttu-id="a3b26-141">Valitse **OK**-painike.</span><span class="sxs-lookup"><span data-stu-id="a3b26-141">Choose the **OK** button.</span></span>  

    <span data-ttu-id="a3b26-142">Eräajo laskee uudeksi summaksi prosenttiosuuden vakuutetusta kokonaisarvosta **Vakuutustilastot**-ikkunan arvon mukaan. Tämän jälkeen luodaan rivi vakuutuspäiväkirjaan.</span><span class="sxs-lookup"><span data-stu-id="a3b26-142">The batch job calculates the new amount as a percentage of the total value insured, as stated in the **Insurance Statistics** window, and then creates a line in the insurance journal.</span></span>  
4. <span data-ttu-id="a3b26-143">Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Vakuutuspäiväkirjat** ja valitse sitten aiheeseen liittyvä linkki.</span><span class="sxs-lookup"><span data-stu-id="a3b26-143">In the top right corner, choose the **Search for Page or Report** icon, enter **Insurance Journals**, and then choose the related link.</span></span>
5. <span data-ttu-id="a3b26-144">Avaa kyseinen vakuutuspäiväkirja, tarkista luodut arvot ja kirjaa ne vakuutuksen kattavuustapahtumiin.</span><span class="sxs-lookup"><span data-stu-id="a3b26-144">Open the relevant insurance journal, review the created values, and then post them to the insurance coverage ledger.</span></span>

## <a name="to-monitor-insurance-coverage"></a><span data-ttu-id="a3b26-145">Vakuutuksen kattavuuden valvonta</span><span class="sxs-lookup"><span data-stu-id="a3b26-145">To monitor insurance coverage</span></span>
<span data-ttu-id="a3b26-146">Dynamics NAV sisältää vakuutussopimusten analysoimiseen ja käyttöomaisuuserien yli- ja alivakuuttamisen määrittämiseen tarkoitettuja raportti- ja tilastotietoikkunoita.</span><span class="sxs-lookup"><span data-stu-id="a3b26-146">Dynamics NAV provides dedicated reports and statistics windows for use in analyzing insurance policies and whether your fixed assets are over- or under-insured.</span></span>

### <a name="overview-of-insurance-policies"></a><span data-ttu-id="a3b26-147">Yleiskuva vakuutussopimuksista</span><span class="sxs-lookup"><span data-stu-id="a3b26-147">Overview of Insurance Policies</span></span>  
<span data-ttu-id="a3b26-148">Saadaksesi yleiskuvan vakuutussopimuksista, voit esikatsella ja tulostaa **Vakuutus – Luettelo** -raportin, jossa näkyvät kaikki sopimukset sekä tärkeimmät vakuutuskorttien kentät.</span><span class="sxs-lookup"><span data-stu-id="a3b26-148">To get an overview of your insurance policies, you can preview or print the **Insurance - List** report, which shows all the policies and the most important fields from the insurance cards.</span></span>  

### <a name="insurance-coverage"></a><span data-ttu-id="a3b26-149">Vakuutuskattavuus</span><span class="sxs-lookup"><span data-stu-id="a3b26-149">Insurance Coverage</span></span>
<span data-ttu-id="a3b26-150">Tarkastele, mitä käyttöomaisuuseriä vakuutussopimukset kattavat ja millaisista summista on kyse, esikatselemalla tai tulostamalla **Vakuutus – Vakuut. arvo yht.** -raportin.</span><span class="sxs-lookup"><span data-stu-id="a3b26-150">To see which insurance policies cover each asset and by which amount, you can preview or print the **Insurance - Tot. Value Insured** report.</span></span>

### <a name="overunder-coverage"></a><span data-ttu-id="a3b26-151">Yli-/alikattavuus</span><span class="sxs-lookup"><span data-stu-id="a3b26-151">Over/Under Coverage</span></span>
<span data-ttu-id="a3b26-152">Voit tarkistaa käyttöomaisuuserien mahdollisen yli- tai alivakuuttamisen seuraavilla tavoilla:</span><span class="sxs-lookup"><span data-stu-id="a3b26-152">You can check if fixed assets are over- or under-insured in the following ways:</span></span>
- <span data-ttu-id="a3b26-153">**Vakuutustilastot**-ikkuna.</span><span class="sxs-lookup"><span data-stu-id="a3b26-153">The **Insurance Statistics** window.</span></span> <span data-ttu-id="a3b26-154">Jos **Ali-/ylivakuutus**-kentässä on positiivinen summa, käyttöomaisuus on ylivakuutettu.</span><span class="sxs-lookup"><span data-stu-id="a3b26-154">A positive amount in the **Over/Under Insured** field means that the fixed asset is over-insured.</span></span> <span data-ttu-id="a3b26-155">Negatiivinen summa tarkoittaa sitä, että se on alivakuutettu.</span><span class="sxs-lookup"><span data-stu-id="a3b26-155">A negative amount means that it is underinsured.</span></span>
- <span data-ttu-id="a3b26-156">**Käyttöomaisuustilastot**-ikkuna.</span><span class="sxs-lookup"><span data-stu-id="a3b26-156">The **Fixed Asset Statistics** window.</span></span> <span data-ttu-id="a3b26-157">Valitse **Kokonaisvakuutusarvo**-kenttä, kun haluat tarkastella **Vakuutuksen kattav.tapahtumat** -ikkunaa.</span><span class="sxs-lookup"><span data-stu-id="a3b26-157">Choose the **Total Value Insured** field to view the **Ins. Coverage Ledger Entries** window.</span></span>  
- <span data-ttu-id="a3b26-158">**Yli-/alikattavuus**-raportti.</span><span class="sxs-lookup"><span data-stu-id="a3b26-158">The **Over/Under Coverage** report.</span></span>  
- <span data-ttu-id="a3b26-159">**Vakuutusanalyysi**-raportti.</span><span class="sxs-lookup"><span data-stu-id="a3b26-159">The **Insurance Analysis** report.</span></span>

### <a name="uninsured-fixed-assets"></a><span data-ttu-id="a3b26-160">Vakuuttamaton käyttöomaisuus</span><span class="sxs-lookup"><span data-stu-id="a3b26-160">Uninsured Fixed Assets</span></span>
<span data-ttu-id="a3b26-161">Tarkastaaksesi, ettet ole unohtanut määritellä käyttöomaisuutta vakuutussopimukseen, voit tulostaa tai esikatsella **Vakuutus – Vakuuttamaton KO** -raportin.</span><span class="sxs-lookup"><span data-stu-id="a3b26-161">To check if you have forgotten to assign a fixed asset to an insurance policy, you can print or preview the **Insurance - Uninsured FAs** report.</span></span> <span data-ttu-id="a3b26-162">Tässä raportissa näkyvät käyttöomaisuuserät, joiden osalta ei ole kirjattu summia vakuutuksen kattavuustapahtumaan.</span><span class="sxs-lookup"><span data-stu-id="a3b26-162">This report displays fixed assets for which amounts have not been posted to the insurance coverage ledger.</span></span>

## <a name="to-view-insurance-coverage-ledger-entries"></a><span data-ttu-id="a3b26-163">Vakuutuksen kattavuustapahtumien katsominen</span><span class="sxs-lookup"><span data-stu-id="a3b26-163">To view insurance coverage ledger entries</span></span>
<span data-ttu-id="a3b26-164">Vakuutuksen kattavuuskirjauksiin tehtyjä tapahtumia voi katsoa.</span><span class="sxs-lookup"><span data-stu-id="a3b26-164">You can view the entries that you have made in the insurance coverage ledger.</span></span>  

1. <span data-ttu-id="a3b26-165">Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Vakuutus** ja valitse sitten aiheeseen liittyvä linkki.</span><span class="sxs-lookup"><span data-stu-id="a3b26-165">In the top right corner, choose the **Search for Page or Report** icon, enter **Insurance**, and then choose the related link.</span></span>  
2. <span data-ttu-id="a3b26-166">Valitse haluamasi vakuutussopimus ja valitse sitten **Vakuutuksen kattav.tapahtumat** -toiminto.</span><span class="sxs-lookup"><span data-stu-id="a3b26-166">Select the relevant insurance policy, and then choose the **Coverage Ledger Entries** action.</span></span>

## <a name="to-view-the-total-insurance-value-of-fixed-assets"></a><span data-ttu-id="a3b26-167">Käyttöomaisuuden kokonaisvakuutusarvon tarkasteleminen</span><span class="sxs-lookup"><span data-stu-id="a3b26-167">To view the total insurance value of fixed assets</span></span>
<span data-ttu-id="a3b26-168">Erityinen matriisi-ikkuna sisältää kunkin käyttöomaisuuserän vakuutussopimukselle rekisteröidyt vakuutusarvot, jotka saadaan vakuutukseen liittyvien kirjattujen summien tuloksena.</span><span class="sxs-lookup"><span data-stu-id="a3b26-168">A dedicated matrix window shows the insurance values that are registered for each insurance policy for each fixed asset as a result of insurance-related amounts that you have posted.</span></span>

1. <span data-ttu-id="a3b26-169">Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Vakuutus** ja valitse sitten aiheeseen liittyvä linkki.</span><span class="sxs-lookup"><span data-stu-id="a3b26-169">In the top right corner, choose the **Search for Page or Report** icon, enter **Insurance**, and then choose the related link.</span></span>  
2. <span data-ttu-id="a3b26-170">Valitse haluamasi vakuutussopimus ja valitse sitten **Vakuutusarvo KO-erää kohti** -toiminto.</span><span class="sxs-lookup"><span data-stu-id="a3b26-170">Select the relevant insurance policy, and then choose the **Total Value Insures per FA** action.</span></span>
3. <span data-ttu-id="a3b26-171">Täytä tarvittavat kentät</span><span class="sxs-lookup"><span data-stu-id="a3b26-171">Fill in the fields as necessary</span></span>  
4. <span data-ttu-id="a3b26-172">valitse **Näytä matriisi** -toiminto.</span><span class="sxs-lookup"><span data-stu-id="a3b26-172">choose the **Show Matrix** action.</span></span>  
5. <span data-ttu-id="a3b26-173">Voit tarkastella perusteena olevia vakuutuksen kattavuustapahtumia valitsemalla arvon matriisista.</span><span class="sxs-lookup"><span data-stu-id="a3b26-173">To see the underlying insurance coverage ledger entries, choose a value in the matrix.</span></span>

## <a name="to-correct-insurance-coverage-entries"></a><span data-ttu-id="a3b26-174">Vakuutuksen kattavuustapahtumien korjaaminen</span><span class="sxs-lookup"><span data-stu-id="a3b26-174">To correct insurance coverage entries</span></span>  
<span data-ttu-id="a3b26-175">Jos käyttöomaisuus on liitetty virheelliseen vakuutussopimukseen, voit korjata sen luomalla kaksi uudelleenluokittelutapahtumaa vakuutuspäiväkirjasta.</span><span class="sxs-lookup"><span data-stu-id="a3b26-175">If a fixed asset has been attached to the wrong insurance policy, you can correct it by creating two reclassification entries from the insurance journal.</span></span>  

1. <span data-ttu-id="a3b26-176">Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Vakuutuspäiväkirjat** ja valitse sitten aiheeseen liittyvä linkki.</span><span class="sxs-lookup"><span data-stu-id="a3b26-176">In the top right corner, choose the **Search for Page or Report** icon, enter **Insurance Journals**, and then choose the related link.</span></span>
2. <span data-ttu-id="a3b26-177">Luo käyttöomaisuudelle yksi päiväkirjarivi ja korjaa vakuutussopimus, jonka **Summa**-kentän arvo on positiivinen.</span><span class="sxs-lookup"><span data-stu-id="a3b26-177">Create one journal line for the fixed asset and the correct insurance policy where the value in the **Amount** field is positive.</span></span>
3. <span data-ttu-id="a3b26-178">Luo käyttöomaisuudelle toinen päiväkirjarivi ja virheellinen vakuutussopimus, jonka **Summa**-kentän arvo on negatiivinen.</span><span class="sxs-lookup"><span data-stu-id="a3b26-178">Create another journal line for the fixed asset and the incorrect insurance policy where the value in the **Amount** field is negative.</span></span>  
4. <span data-ttu-id="a3b26-179">Valitse **Kirjaa**-toiminto.</span><span class="sxs-lookup"><span data-stu-id="a3b26-179">Choose the **Post** action.</span></span>

<span data-ttu-id="a3b26-180">Käyttöomaisuus irrotetaan virheellisestä vakuutussopimuksesta toisella rivillä ja liitetään oikeaan sopimukseen ensimmäisellä rivillä.</span><span class="sxs-lookup"><span data-stu-id="a3b26-180">The fixed asset will be detached from the incorrect insurance policy, on the second line, and attached to the correct insurance policy, on the first line.</span></span>

## <a name="see-also"></a><span data-ttu-id="a3b26-181">Katso myös</span><span class="sxs-lookup"><span data-stu-id="a3b26-181">See Also</span></span>
[<span data-ttu-id="a3b26-182">Käyttöomaisuuden hallinta</span><span class="sxs-lookup"><span data-stu-id="a3b26-182">Manage Fixed Assets</span></span>](fa-manage.md)  
[<span data-ttu-id="a3b26-183">Käyttöomaisuuserien määrittäminen</span><span class="sxs-lookup"><span data-stu-id="a3b26-183">Set Up Fixed Assets</span></span>](fa-setup.md)  
[<span data-ttu-id="a3b26-184">Rahoitus</span><span class="sxs-lookup"><span data-stu-id="a3b26-184">Finance</span></span>](finance-setup.md)  
[<span data-ttu-id="a3b26-185">Tervetuloa Dynamics NAV -ohjelmaan</span><span class="sxs-lookup"><span data-stu-id="a3b26-185">Welcome to Dynamics NAV</span></span>](across-get-started.md)
