---
title: 'Toimintaohje: Toimittajan maksujen kohdistaminen manuaalisesti'
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
ms.openlocfilehash: d3aaafc9ac3dcfd1fba3802b1158bde890e09110
ms.contentlocale: fi-fi
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-apply-vendor-payments-manually"></a><span data-ttu-id="4aea1-102">Toimintaohje: Toimittajan maksujen kohdistaminen manuaalisesti</span><span class="sxs-lookup"><span data-stu-id="4aea1-102">How to: Apply Vendor Payments Manually</span></span>

<span data-ttu-id="4aea1-103">Kun lähetät maksukuitin toimittajalle tai saat hyvityksen toimittajalta, päätä, kohdistetaanko maksu tai hyvitys yhteen avoimeen debet- tai kredit-tapahtumaan vai useaan tällaiseen tapahtumaan.</span><span class="sxs-lookup"><span data-stu-id="4aea1-103">When you send a payment or receive a refund from a vendor, you must decide whether to apply the payment or refund to one or more open entries.</span></span> <span data-ttu-id="4aea1-104">Voit määrittää tarkasti summan, jota käytetään maksukuitin tai hyvityksen kohdistuksessa, eli toimittajapahtumat kohdistetaan tällöin vain osittain.</span><span class="sxs-lookup"><span data-stu-id="4aea1-104">You can specify the exact amount that you want to apply to the payment receipt or refund, and then only partially apply vendor ledger entries.</span></span> <span data-ttu-id="4aea1-105">Kaikki toimittajatapahtumat täytyy sulkea (kohdistaa), jotta toimittajatilastot sekä tiliotteiden ja rahoituksen käyttöönottokulujen raportit ovat virheettömiä.</span><span class="sxs-lookup"><span data-stu-id="4aea1-105">You must apply all vendor ledger entries to obtain correct vendor statistics and reports of the account statements and finance-setup charges.</span></span>

<span data-ttu-id="4aea1-106">**Huomautus**: Toimittajat voivat toisinaan antaa maksuhyvityksen tulevia laskuja vastaan kirjattavan hyvityslaskun sijasta etenkin silloin, kun palautat nimikkeitä, jotka olet jo maksanut, tai olet maksanut enemmän kuin laskun summan.</span><span class="sxs-lookup"><span data-stu-id="4aea1-106">**Note**: Vendors may sometimes give a payment refund instead of a credit memo to offset against future invoices, especially when you return items that you have already paid for or when you have overpaid an invoice.</span></span>

<span data-ttu-id="4aea1-107">Voit kohdistaa toimittajatapahtumia seuraavilla kolmella tavalla:</span><span class="sxs-lookup"><span data-stu-id="4aea1-107">You can apply vendor ledger entries in three different ways:</span></span>

- <span data-ttu-id="4aea1-108">syöttämällä tiedot niille tarkoitettuihin ikkunoihin, kuten **Maksupäiväkirja**- ja **Maksujen täsmäytyskirjauskansio** -ikkunaan</span><span class="sxs-lookup"><span data-stu-id="4aea1-108">By entering information in dedicated windows, such as the **Payment Journal** window and the **Payment Reconciliation Journal** window.</span></span>
- <span data-ttu-id="4aea1-109">ostohyvityslaskuasiakirjoista</span><span class="sxs-lookup"><span data-stu-id="4aea1-109">From purchase credit memo documents.</span></span>
- <span data-ttu-id="4aea1-110">toimittajatapahtumista sen jälkeen, kun ostoasiakirjat on kirjattu, mutta ei kohdistettu.</span><span class="sxs-lookup"><span data-stu-id="4aea1-110">From vendor ledger entries after purchase documents are posted but not applied.</span></span>

<span data-ttu-id="4aea1-111">**Huomautus**: Jos toimittajan kortin **Kohdistustapa**-kentässä on **Kohdista vanhimpaan**, maksut kohdistetaan automaattisesti vanhimpaan avoimeen kredit-tapahtumaan, jos tapahtumaa, johon kohdistetaan, ei määritetä manuaalisesti.</span><span class="sxs-lookup"><span data-stu-id="4aea1-111">**Note**: If the **Application Method** field on the vendor card contains **Apply to Oldest**, then payments will automatically be applied to the oldest open credit entry if you do not manually specify which entry to apply to.</span></span> <span data-ttu-id="4aea1-112">Jos asiakkaan kohdistustapa on **Manuaalinen**, tapahtumat on kohdistettava manuaalisesti.</span><span class="sxs-lookup"><span data-stu-id="4aea1-112">If the application method for a customer is **Manual**, then you must apply entries manually.</span></span>

<span data-ttu-id="4aea1-113">Voit kohdistaa toimittajan maksut manuaalisesti liittyviin ostoasiakirjoihin, kun kirjaat maksut **Maksupäiväkirja**-ikkunassa.</span><span class="sxs-lookup"><span data-stu-id="4aea1-113">You can apply vendor payments manually to their related purchase documents when you post the payments in the **Payment Journal** window.</span></span> <span data-ttu-id="4aea1-114">Lisätietoja maksupäiväkirjan täyttämisestä on kohdassa [Toimintaohje: Maksujen suorittaminen](payables-make-payments.md).</span><span class="sxs-lookup"><span data-stu-id="4aea1-114">For information about filling the payment journal, see [How to: Make Payments](payables-make-payments.md).</span></span>

<span data-ttu-id="4aea1-115">Voit myös kohdistaa toimittajan maksuja ja asiakkaan maksuja sen jälkeen, kun maksut näkyvät negatiivisina pankkitapahtumina pankissasi.</span><span class="sxs-lookup"><span data-stu-id="4aea1-115">You can also apply vendor payments, and customer payments, after the payments appear as negative bank transactions at your bank.</span></span> <span data-ttu-id="4aea1-116">**Maksujen täsmäytyskirjauskansio** -ikkunassa voit käyttää pankin tiliotteen tuonnin, automaattisen kohdistuksen ja pankkitilin täsmäytyksen toimintoja.</span><span class="sxs-lookup"><span data-stu-id="4aea1-116">In the **Payment Reconciliation Journal** window, you can use functions for bank statement import, automatic application, and bank account reconciliation.</span></span> <span data-ttu-id="4aea1-117">Lisätietoja on kohdassa [Maksujen täsmäyttäminen käyttämällä automaattista kohdistusta](receivables-how-reconcile-payments-auto-application.md).</span><span class="sxs-lookup"><span data-stu-id="4aea1-117">For more information, see [Reconcile Payments Using Automatic Application](receivables-how-reconcile-payments-auto-application.md).</span></span>

## <a name="to-apply-a-payment-to-a-single-or-multiple-vendor-ledger-entries"></a><span data-ttu-id="4aea1-118">Maksun kohdistaminen yhteen tai useaan toimittajatapahtumaan</span><span class="sxs-lookup"><span data-stu-id="4aea1-118">To apply a payment to a single or multiple vendor ledger entries</span></span>
1. <span data-ttu-id="4aea1-119">Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Maksupäiväkirja** ja valitse sitten aiheeseen liittyvä linkki.</span><span class="sxs-lookup"><span data-stu-id="4aea1-119">In the top right corner, choose the **Search for Page or Report** icon, enter **Payment Journal**, and then choose the related link.</span></span>
2. <span data-ttu-id="4aea1-120">Syötä **Maksupäiväkirja**-ikkunassa ensimmäiselle päiväkirjariville asianmukaiset tiedot maksutapahtumasta.</span><span class="sxs-lookup"><span data-stu-id="4aea1-120">In the **Payment Journal** window, on the first journal line, enter the relevant information about the payment entry.</span></span>
3. <span data-ttu-id="4aea1-121">Voit kohdistaa yhden toimittajatapahtuman seuraavasti:</span><span class="sxs-lookup"><span data-stu-id="4aea1-121">To apply a single vendor ledger entry:</span></span>
4. <span data-ttu-id="4aea1-122">Valitse **Kohdistetaan asiakirjaan nro** -kentässä</span><span class="sxs-lookup"><span data-stu-id="4aea1-122">In the **Applies-to Doc. No.**</span></span> <span data-ttu-id="4aea1-123">kenttä, jolloin **Kohdista toimittajatapaht.** -ikkuna avautuu.</span><span class="sxs-lookup"><span data-stu-id="4aea1-123">field, choose the field to open the **Apply Vendor Entries** window.</span></span>
5. <span data-ttu-id="4aea1-124">Valitse **Kohdista toimittajatapaht.** -ikkunassa tapahtuma, johon maksu kohdistetaan.</span><span class="sxs-lookup"><span data-stu-id="4aea1-124">In the **Apply Vendor Entries** window, select the entry to apply the payment to.</span></span>
6. <span data-ttu-id="4aea1-125">Määritä tapahtumaan kohdistettava summa rivin **Kohdistettava summa** -kenttään.</span><span class="sxs-lookup"><span data-stu-id="4aea1-125">On the line in the **Amount to Apply** field, enter the amount to apply to the entry.</span></span>
7. <span data-ttu-id="4aea1-126">Vaihtoehtoisesti voit kohdistaa useita toimittajatapahtumia seuraavasti:</span><span class="sxs-lookup"><span data-stu-id="4aea1-126">Or, to apply multiple vendor ledger entries:</span></span>
8. <span data-ttu-id="4aea1-127">Valitse **Kohdista tapahtumat** -toiminto.</span><span class="sxs-lookup"><span data-stu-id="4aea1-127">Choose the **Apply Entries** action.</span></span>
9. <span data-ttu-id="4aea1-128">Valitse **Kohdista toimittajatapaht.** -ikkunassa rivit, joilla oleville tapahtumille maksu kohdistetaan.</span><span class="sxs-lookup"><span data-stu-id="4aea1-128">In the **Apply Vendor Entries** window, select the lines with the entries to apply the payment to.</span></span>
10. <span data-ttu-id="4aea1-129">Valitse **Aseta kohdistustunniste** -toiminto.</span><span class="sxs-lookup"><span data-stu-id="4aea1-129">Choose the **Set Applies-to ID** action.</span></span>  
11. <span data-ttu-id="4aea1-130">Määritä yksittäiseen tapahtumaan kohdistettava summa kunkin rivin **Kohdistettava summa** -kenttään.</span><span class="sxs-lookup"><span data-stu-id="4aea1-130">On each line in the **Amount to Apply** field, enter the amount to apply to the individual entry.</span></span>

    <span data-ttu-id="4aea1-131">Jos summaa ei määritetä, ohjelma kohdistaa automaattisesti enimmäissumman.</span><span class="sxs-lookup"><span data-stu-id="4aea1-131">If you do not enter an amount, then the maximum amount is automatically applied.</span></span> <span data-ttu-id="4aea1-132">**Kohdista toimittajatapaht.** -ikkunan alaosan Kohdistettu summa -kentästä voi tarkistaa summan sekä sen, täsmääkö kohdistus.</span><span class="sxs-lookup"><span data-stu-id="4aea1-132">At the bottom of the **Apply Vendor Entries** window, you can see the amount in the Applied Amount field, and you can see whether the application balances.</span></span>
12. <span data-ttu-id="4aea1-133">Valitse **OK**-painike.</span><span class="sxs-lookup"><span data-stu-id="4aea1-133">Choose the **OK** button.</span></span>
13. <span data-ttu-id="4aea1-134">Valitse **Kirjaa**-toiminto, kun haluat kirjata maksupäiväkirjan.</span><span class="sxs-lookup"><span data-stu-id="4aea1-134">Choose the **Post** action to post the payment journal.</span></span>

## <a name="to-apply-a-credit-memo-to-a-single-or-multiple-vendor-ledger-entries"></a><span data-ttu-id="4aea1-135">Hyvityslaskun kohdistaminen yhteen tai useaan toimittajatapahtumaan</span><span class="sxs-lookup"><span data-stu-id="4aea1-135">To apply a credit memo to a single or multiple vendor ledger entries</span></span>
1. <span data-ttu-id="4aea1-136">Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Ostohyvityslasku** ja valitse sitten aiheeseen liittyvä linkki.</span><span class="sxs-lookup"><span data-stu-id="4aea1-136">In the top right corner, choose the **Search for Page or Report** icon, enter **Purchase Credit Memo**, and then choose the related link.</span></span>
2. <span data-ttu-id="4aea1-137">Avaa hyvityslasku, jonka haluat kohdistaa.</span><span class="sxs-lookup"><span data-stu-id="4aea1-137">Open the credit memo that you want to apply.</span></span>
3. <span data-ttu-id="4aea1-138">Syötä tarvittavat tiedot otsikkoon.</span><span class="sxs-lookup"><span data-stu-id="4aea1-138">Enter the relevant information in the header.</span></span>
4. <span data-ttu-id="4aea1-139">Voit kohdistaa yhden toimittajatapahtuman seuraavasti:</span><span class="sxs-lookup"><span data-stu-id="4aea1-139">To apply a single vendor ledger entry:</span></span>
5. <span data-ttu-id="4aea1-140">Valitse **Kohdistus**-pikavälilehden **Kohdistetaan asiakirjaan nro** -kentässä</span><span class="sxs-lookup"><span data-stu-id="4aea1-140">On the **Application** FastTab, in the **Applies-to Doc. No.**</span></span> <span data-ttu-id="4aea1-141">tapahtuma, johon hyvitys kohdistetaan.</span><span class="sxs-lookup"><span data-stu-id="4aea1-141">field, select the entry to apply the credit to.</span></span>
6. <span data-ttu-id="4aea1-142">Määritä tapahtumaan kohdistettava summa rivin **Kohdistettava summa** -kenttään.</span><span class="sxs-lookup"><span data-stu-id="4aea1-142">On the line in the **Amount to Apply** field, enter the amount to apply to the entry.</span></span>
7. <span data-ttu-id="4aea1-143">Vaihtoehtoisesti voit kohdistaa useita toimittajatapahtumia seuraavasti:</span><span class="sxs-lookup"><span data-stu-id="4aea1-143">Or, to apply multiple vendor ledger entries:</span></span>
8. <span data-ttu-id="4aea1-144">Valitse **Kohdista tapahtumat** -toiminto.</span><span class="sxs-lookup"><span data-stu-id="4aea1-144">Choose the **Apply Entries** action.</span></span>
9. <span data-ttu-id="4aea1-145">Valitse rivit, joiden tapahtumiin hyvityslaskun tapahtumat kohdistetaan.</span><span class="sxs-lookup"><span data-stu-id="4aea1-145">Select the lines with the entries to apply the credit memo to.</span></span>
10. <span data-ttu-id="4aea1-146">Valitse **Aseta kohdistustunniste** -toiminto.</span><span class="sxs-lookup"><span data-stu-id="4aea1-146">Choose the **Set Applies-to ID** action.</span></span>  
11. <span data-ttu-id="4aea1-147">Määritä yksittäiseen tapahtumaan kohdistettava summa kunkin rivin **Kohdistettava summa** -kenttään.</span><span class="sxs-lookup"><span data-stu-id="4aea1-147">On each line in the **Amount to Apply** field, enter the amount to apply to the individual entry.</span></span>

    <span data-ttu-id="4aea1-148">Jos summaa ei määritetä, ohjelma kohdistaa automaattisesti enimmäissumman.</span><span class="sxs-lookup"><span data-stu-id="4aea1-148">If you do not enter an amount, then the maximum amount is automatically applied.</span></span> <span data-ttu-id="4aea1-149">**Kohdista toimittajatapaht.** -ikkunan alaosan **Kohdistettu summa** -kentästä voi tarkistaa summan sekä sen, täsmääkö kohdistus.</span><span class="sxs-lookup"><span data-stu-id="4aea1-149">At the bottom of the **Apply Vendor Entries** window, you can see the amount in the **Applied Amount** field, and you can see whether the application balances.</span></span>
12. <span data-ttu-id="4aea1-150">Valitse **OK**-painike.</span><span class="sxs-lookup"><span data-stu-id="4aea1-150">Choose the **OK** button.</span></span>  
<span data-ttu-id="4aea1-151">**Ostohyvityslasku**-ikkunassa näkyy tapahtuma, jonka olet valinnut **Kohdistetaan asiakirjatyyppiin**- ja **Kohdistetaan asiakirjaan nro**</span><span class="sxs-lookup"><span data-stu-id="4aea1-151">The **Purchase Credit Memo** window shows the entry that you have selected in the **Applies-to Doc. Type** field and the **Applies-to Doc. No.**</span></span> <span data-ttu-id="4aea1-152">-kentässä.</span><span class="sxs-lookup"><span data-stu-id="4aea1-152">field.</span></span> <span data-ttu-id="4aea1-153">Ikkunassa näkyy myös kirjattava hyvityslaskun summa sekä mahdolliset maksualennukset.</span><span class="sxs-lookup"><span data-stu-id="4aea1-153">The window also shows the amount of the credit memo to be posted, adjusted for any payment discounts.</span></span>
13. <span data-ttu-id="4aea1-154">Kirjaa ostohyvityslasku valitsemalla **Kirjaa**-painike.</span><span class="sxs-lookup"><span data-stu-id="4aea1-154">Choose the **Post** button to post the purchase credit memo.</span></span>

## <a name="to-apply-posted-vendor-ledger-entries"></a><span data-ttu-id="4aea1-155">Kirjattujen toimittajatapahtumien kohdistus:</span><span class="sxs-lookup"><span data-stu-id="4aea1-155">To apply posted vendor ledger entries</span></span>

1. <span data-ttu-id="4aea1-156">Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Toimittajat** ja valitse sitten aiheeseen liittyvä linkki.</span><span class="sxs-lookup"><span data-stu-id="4aea1-156">In the top right corner, choose the **Search for Page or Report** icon, enter **Vendors**, and then choose the related link.</span></span>
2. <span data-ttu-id="4aea1-157">Avaa asianmukainen toimittaja, jolla on aiemmin kirjattuja tapahtumia.</span><span class="sxs-lookup"><span data-stu-id="4aea1-157">Open the relevant vendor with entries that have already been posted.</span></span>
3. <span data-ttu-id="4aea1-158">Valitse **Tapahtumakirjaukset**-toiminto ja valitse sitten **Kohdista tapahtumat** -toiminto.</span><span class="sxs-lookup"><span data-stu-id="4aea1-158">Choose the **Ledger Entries** action, and then choose the **Apply Entries** action.</span></span>
4. <span data-ttu-id="4aea1-159">**Kohdista toimittajatapaht.** -ikkunassa näkyvät toimittajan avoimet tapahtumat.</span><span class="sxs-lookup"><span data-stu-id="4aea1-159">In the **Apply Vendor Entries** window, you can see the open entries for the vendor.</span></span>
5. <span data-ttu-id="4aea1-160">Valitse rivi, jolla kohdistettava tapahtuma on.</span><span class="sxs-lookup"><span data-stu-id="4aea1-160">Select the line with the entry that will be applied.</span></span>
6. <span data-ttu-id="4aea1-161">Valitse **Aseta kohdistustunniste** -toiminto.</span><span class="sxs-lookup"><span data-stu-id="4aea1-161">Choose the **Set Applies-to ID** action.</span></span>
7. <span data-ttu-id="4aea1-162">**Kohdistetaan tunnisteeseen** -kentässä on näkyvissä kolme tähteä, jos työskentelet yhden käyttäjän järjestelmässä, tai käyttäjätunnuksesi, jos työskentelet useamman käyttäjän järjestelmässä.</span><span class="sxs-lookup"><span data-stu-id="4aea1-162">The **Applies-to ID** field displays three asterisks if you work in a single-user system or your user ID if you work in a multiuser system.</span></span>  
8. <span data-ttu-id="4aea1-163">Määritä yksittäiseen tapahtumaan kohdistettava summa kunkin rivin **Kohdistettava summa** -kenttään.</span><span class="sxs-lookup"><span data-stu-id="4aea1-163">For each line in the **Amount to Apply** field, enter the amount to apply to the individual entry.</span></span>

    <span data-ttu-id="4aea1-164">Jos summaa ei määritetä, ohjelma kohdistaa automaattisesti enimmäissumman.</span><span class="sxs-lookup"><span data-stu-id="4aea1-164">If you do not enter an amount, then the maximum amount is automatically applied.</span></span> <span data-ttu-id="4aea1-165">Summan voi tarkistaa **Kohdista toimittajatapaht.** -ikkunan **Kohdistettu summa** -kentästä.</span><span class="sxs-lookup"><span data-stu-id="4aea1-165">You can see the amount in the **Applied Amount** field at the bottom of the **Apply Vendor Entries** window.</span></span>
9. <span data-ttu-id="4aea1-166">Valitse **Kirjaa kohdistus** -toiminto.</span><span class="sxs-lookup"><span data-stu-id="4aea1-166">Choose the **Post Application** action.</span></span>  
<span data-ttu-id="4aea1-167">Näyttöön tulee **Kirjaa kohdistus** -ikkuna, joka sisältää kohdistettavan tapahtuman asiakirjanumeron sekä viimeksi kirjatun tapahtuman kirjauspäivämäärän.</span><span class="sxs-lookup"><span data-stu-id="4aea1-167">The **Post Application** window opens with the document number of the applying entry and the posting date of the entry with the most recent posting date.</span></span>
10. <span data-ttu-id="4aea1-168">Kirjaa sovellus valitsemalla **OK**.</span><span class="sxs-lookup"><span data-stu-id="4aea1-168">Choose the **OK** button to post the application.</span></span>

## <a name="to-apply-vendor-ledger-entries-in-different-currencies-to-one-another"></a><span data-ttu-id="4aea1-169">Eri valuutoissa olevien toimittajatapahtumien kohdistaminen toisiinsa:</span><span class="sxs-lookup"><span data-stu-id="4aea1-169">To apply vendor ledger entries in different currencies to one another</span></span>
<span data-ttu-id="4aea1-170">Jos ostat toimittajalta yhdessä valuutassa ja maksat maksun toisessa valuutassa, maksu voidaan silti kohdistaa maksun laskuun.</span><span class="sxs-lookup"><span data-stu-id="4aea1-170">If you buy from a vendor in one currency and make payment in another currency, you can still apply the invoice to the payment.</span></span>

<span data-ttu-id="4aea1-171">Jos tapahtuma (tapahtuma 1) kohdistetaan eri valuuttaa käyttävään tapahtumaan (tapahtuma 2), tapahtuman 2 summien muuntamisessa käytettävä vaihtokurssi etsitään tapahtuman 1 kirjauspäivämäärän mukaan.</span><span class="sxs-lookup"><span data-stu-id="4aea1-171">If you apply an entry (Entry 1) in one currency to an entry (Entry 2) in a different currency, the posting date on Entry 1 is used to find the relevant exchange rate to convert amounts on Entry 2.</span></span> <span data-ttu-id="4aea1-172">Vaihtokurssi löytyy **Valuutan vaihtokurssit** -ikkunasta.</span><span class="sxs-lookup"><span data-stu-id="4aea1-172">The relevant exchange rate is found in the **Currency Exchange Rates** window.</span></span>

<span data-ttu-id="4aea1-173">Toimittajatapahtumien kohdistaminen eri valuutoissa on otettava käyttöön.</span><span class="sxs-lookup"><span data-stu-id="4aea1-173">Applying vendor ledger entries in different currencies must be enabled.</span></span> <span data-ttu-id="4aea1-174">Lisätietoja on kohdassa [Toimintaohje: Tapahtumakirjausten kohdistamisen ottaminen käyttöön eri valuutoissa](finance-setup-how-enable-application-ledger-entries-different-currencies.md)</span><span class="sxs-lookup"><span data-stu-id="4aea1-174">For more information, see [How to: Enable Application of Ledger Entries in Different Currencies](finance-setup-how-enable-application-ledger-entries-different-currencies.md)</span></span>

1. <span data-ttu-id="4aea1-175">Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Maksupäiväkirja** ja valitse sitten aiheeseen liittyvä linkki.</span><span class="sxs-lookup"><span data-stu-id="4aea1-175">In the top right corner, choose the **Search for Page or Report** icon, enter **Payment Journal**, and choose the related link.</span></span>
2. <span data-ttu-id="4aea1-176">Avaa haluamasi päiväkirja ja täytä ensimmäinen tyhjä päiväkirjan rivi valuuttakoodilla.</span><span class="sxs-lookup"><span data-stu-id="4aea1-176">Open the journal you want, and fill in the first empty journal line using a currency code.</span></span>
3. <span data-ttu-id="4aea1-177">Valitse **Kohdista tapahtumat** -toiminto.</span><span class="sxs-lookup"><span data-stu-id="4aea1-177">Choose the **Apply Entries** action.</span></span>
4. <span data-ttu-id="4aea1-178">Valitse rivi, jonka tapahtumaan maksupäiväkirjan tapahtuma kohdistetaan. Valitse sitten **Aseta kohdistustunniste** -toiminto ja valitse tapahtuma, johon kohdistetaan.</span><span class="sxs-lookup"><span data-stu-id="4aea1-178">Select the line with the entry you want to apply to the entry in the payment journal, choose the **Set Applies-to ID** action, and then select the entry you want to apply to.</span></span>
5. <span data-ttu-id="4aea1-179">Valitse **OK**-painike palataksesi maksupäiväkirjaan.</span><span class="sxs-lookup"><span data-stu-id="4aea1-179">Choose the **OK** button to return to the payment journal.</span></span>
6. <span data-ttu-id="4aea1-180">Kirjaa maksupäiväkirja.</span><span class="sxs-lookup"><span data-stu-id="4aea1-180">Post the payment journal.</span></span>

<span data-ttu-id="4aea1-181">**Tärkeää**: Kun erivaluuttaisia tapahtumia kohdistetaan toisiinsa, ohjelma muuntaa tapahtumat paikallista valuuttaa (USD) käyttäen.</span><span class="sxs-lookup"><span data-stu-id="4aea1-181">**Important**: When you apply entries in different currencies to one another, the entries are converted to USD.</span></span> <span data-ttu-id="4aea1-182">Vaikka asianmukaisten valuuttojen vaihtokurssit ovat kiinteät (esimerkiksi Yhdysvaltain dollarin ja euron välillä), pieniä jäännössummia saattaa esiintyä, kun ohjelma muuntaa nämä ulkomaan valuutat USD:ksi.</span><span class="sxs-lookup"><span data-stu-id="4aea1-182">Even though the exchange rates for the two relevant currencies are fixed, for example between USD and EUR, there may be a small residual amount when these foreign-currency amounts are converted to USD.</span></span> <span data-ttu-id="4aea1-183">Ohjelma kirjaa nämä pienet jäännössummat voitoiksi ja tappioiksi **Valuutat**-ikkunan **Realisoitun. val.voitt. tili**- ja **Realisoitun. val.tapp. tili** -kentissä määritetyille tileille.</span><span class="sxs-lookup"><span data-stu-id="4aea1-183">These small residual amounts are posted as gains and losses to the account specified in the **Realized Gains Account** or **Realized Losses Account** field in the **Currencies** window.</span></span> <span data-ttu-id="4aea1-184">**Summa (USD)** -kenttää muokataan myös asianmukaisten toimittajatapahtumien mukaan.</span><span class="sxs-lookup"><span data-stu-id="4aea1-184">The **Amount (USD)** field is also adjusted on the relevant vendor ledger entries.</span></span>

## <a name="to-unapply-an-application-of-vendor-entries"></a><span data-ttu-id="4aea1-185">Toimittajan tapahtumien kohdistuksen peruuttaminen</span><span class="sxs-lookup"><span data-stu-id="4aea1-185">To unapply an application of vendor entries</span></span>
<span data-ttu-id="4aea1-186">Kun tehdään virheellinen kohdistus, ohjelma luo ja kirjaa korjaavat tapahtumat (eli tapahtumat, jotka ovat alkuperäisten tapahtumien kanssa identtisiä mutta joiden summakentässä on vastakkainen etumerkki) kaikille tapahtumille, myös kaikille kohdistuksesta johdetuille KP-kirjauksille, kuten maksualennuksille ja valuuttavoitoille- tai tappioille.</span><span class="sxs-lookup"><span data-stu-id="4aea1-186">When you unapply an erroneous application, correcting entries that are identical to the original entry but with opposite sign in the amount field are created and posted for all entries, including all general ledger posting derived from the application, such as payment discount and currency gains/losses.</span></span> <span data-ttu-id="4aea1-187">Ohjelma avaa uudelleen kohdistuksen sulkemat tapahtumat.</span><span class="sxs-lookup"><span data-stu-id="4aea1-187">The entries that were closed by the application are reopened.</span></span>

1. <span data-ttu-id="4aea1-188">Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Toimittajat** ja valitse sitten aiheeseen liittyvä linkki.</span><span class="sxs-lookup"><span data-stu-id="4aea1-188">In the top right corner, choose the **Search for Page or Report** icon, enter **Vendors**, and then choose the related link.</span></span>
2. <span data-ttu-id="4aea1-189">Avaa asianmukainen toimittajan kortti.</span><span class="sxs-lookup"><span data-stu-id="4aea1-189">Open the relevant vendor card.</span></span>
3. <span data-ttu-id="4aea1-190">Valitse **Tapahtumakirjaukset**-toiminto.</span><span class="sxs-lookup"><span data-stu-id="4aea1-190">Choose the **Ledger Entries** action.</span></span>
4. <span data-ttu-id="4aea1-191">Valitse haluamasi tapahtuma ja valitse sitten **Peruuta kohdistus** -toiminto.</span><span class="sxs-lookup"><span data-stu-id="4aea1-191">Select the relevant ledger entry, and then choose the **Unapply Entries** action.</span></span>
5. <span data-ttu-id="4aea1-192">Vaihtoehtoisesti voit valita **Yksityiskoht. tapahtumat.** -toiminnon.</span><span class="sxs-lookup"><span data-stu-id="4aea1-192">Alternatively, choose the **Detailed Ledger Entry** action.</span></span>
6. <span data-ttu-id="4aea1-193">Valitse haluamasi kohdistustapahtuma ja valitse sitten **Peruuta kohdistus** -toiminto.</span><span class="sxs-lookup"><span data-stu-id="4aea1-193">Select the application entry, and then choose the **Unapply Entries** action.</span></span>
7. <span data-ttu-id="4aea1-194">Täytä pyyntöikkunan kentät ja valitse sitten **Peruuta kohdistus** -painike.</span><span class="sxs-lookup"><span data-stu-id="4aea1-194">Fill in the fields in the header, and then choose the **Unapply** action.</span></span>

<span data-ttu-id="4aea1-195">**Tärkeää**: Jos tapahtumaan on tehty useita kohdistuksia, on viimeisin kohdistustapahtuma poistettava ensin.</span><span class="sxs-lookup"><span data-stu-id="4aea1-195">**Important**: If an entry has been applied by more than one application entry, you must unapply the latest application entry first.</span></span>

## <a name="see-also"></a><span data-ttu-id="4aea1-196">Katso myös</span><span class="sxs-lookup"><span data-stu-id="4aea1-196">See Also</span></span>
[<span data-ttu-id="4aea1-197">Ostovelat</span><span class="sxs-lookup"><span data-stu-id="4aea1-197">Payables</span></span>](payables-manage-payables.md)  
[<span data-ttu-id="4aea1-198">Ostojen hallinta</span><span class="sxs-lookup"><span data-stu-id="4aea1-198">Manage Purchasing</span></span>](purchasing-manage-purchasing.md)
