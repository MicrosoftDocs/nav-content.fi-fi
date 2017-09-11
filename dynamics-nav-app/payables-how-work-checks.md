---
title: "Toimintaohje: Sekkien käsitteleminen"
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
ms.openlocfilehash: 421516a7580a90d6eabc8ecfcc841215839994c9
ms.contentlocale: fi-fi
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-work-with-checks"></a><span data-ttu-id="d576f-102">Toimintaohje: Sekkien käsitteleminen</span><span class="sxs-lookup"><span data-stu-id="d576f-102">How to: Work With Checks</span></span>
<span data-ttu-id="d576f-103">Dynamics NAV tukee sekkien sähköistä ja manuaalista myöntämistä.</span><span class="sxs-lookup"><span data-stu-id="d576f-103">Dynamics NAV supports electronic and manual check issuance.</span></span> <span data-ttu-id="d576f-104">Molemmissa menetelmissä sekit myönnetään toimittajille maksupäiväkirjaa käyttäen.</span><span class="sxs-lookup"><span data-stu-id="d576f-104">Both methods use the payment journal to issue checks to vendors.</span></span> <span data-ttu-id="d576f-105">Ohjelman avulla voit myös mitätöidä sekkejä ja tarkastella sekkitapahtumia.</span><span class="sxs-lookup"><span data-stu-id="d576f-105">You can also void checks and view check ledger entries.</span></span>

<span data-ttu-id="d576f-106">Sekkien myöntämiskäsittelyyn kuuluvat maksujen ehdottaminen, tapahtumien luominen ja tietokonesekkien tulostaminen.</span><span class="sxs-lookup"><span data-stu-id="d576f-106">The process of issuing checks suggests payments, creates ledger entries, and prints the computer checks.</span></span>

<span data-ttu-id="d576f-107">Tulostin on määritettävä oikein sekkimuotoja varten. Myös käytettävä sekkien asettelu on määritettävä.</span><span class="sxs-lookup"><span data-stu-id="d576f-107">Your printer must be correctly set up with the check forms, and you must define which check layout to use.</span></span> <span data-ttu-id="d576f-108">Lisätietoja on kohdassa [Toimintaohje: Sekkien asetteluiden määrittäminen](finance-setup-how-define-check-layouts.md)</span><span class="sxs-lookup"><span data-stu-id="d576f-108">For more information, see [How to: Define Check Layouts](finance-setup-how-define-check-layouts.md)</span></span>

## <a name="to-issue-checks"></a><span data-ttu-id="d576f-109">Sekkien myöntäminen</span><span class="sxs-lookup"><span data-stu-id="d576f-109">To issue checks</span></span>
1. <span data-ttu-id="d576f-110">Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Maksupäiväkirjat** ja valitse sitten aiheeseen liittyvä linkki.</span><span class="sxs-lookup"><span data-stu-id="d576f-110">In the top right corner, choose the **Search for Page or Report** icon, enter **Payment Journals**, and then choose the related link.</span></span>
2. <span data-ttu-id="d576f-111">Täytä asianmukaisten maksujen tiedot päiväkirjaan esimerkiksi Ehdota toimittajamaksuja -toiminnon avulla.</span><span class="sxs-lookup"><span data-stu-id="d576f-111">Fill in the journal with relevant payments, for example by using the Suggest Vendor Payments function.</span></span> <span data-ttu-id="d576f-112">Lisätietoja on kohdassa [Toimintaohje: Toimittajamaksujen ehdottaminen](payables-how-suggest-vendor-payments.md).</span><span class="sxs-lookup"><span data-stu-id="d576f-112">For more information, see [How to: Suggest Vendor Payments](payables-how-suggest-vendor-payments.md).</span></span>
3. <span data-ttu-id="d576f-113">Valitse sekkien avulla tehtävän maksun päiväkirjan rivillä **Pankkimaksun tyyppi** -kentässä jokin seuraavista vaihtoehdoista:</span><span class="sxs-lookup"><span data-stu-id="d576f-113">In the **Bank Payment Type** field on journal lines for payment that you want to make with checks, select one of the following options:</span></span>

 - <span data-ttu-id="d576f-114">**Tietokonesekki**: Valitse tämä vaihtoehto, jos haluat tulostaa sekin maksupäiväkirjan tällä rivillä olevalle summalle.</span><span class="sxs-lookup"><span data-stu-id="d576f-114">**Computer Check**: Select this option if you want to print a check for the amount on the payment journal line.</span></span> <span data-ttu-id="d576f-115">Tulosta sekit, ennen kuin kirjaat päiväkirjan rivit.</span><span class="sxs-lookup"><span data-stu-id="d576f-115">You must print the checks before you can post the journal lines.</span></span> <span data-ttu-id="d576f-116">Voit valita **Tietokonesekki**-kohdan vain, jos **Vastatilin tyyppi** tai **Tilin tyyppi** on **Pankkitili**.</span><span class="sxs-lookup"><span data-stu-id="d576f-116">You can only select **Computer Check** if the **Bal. Account Type** or the **Account Type** is **Bank Account**.</span></span>

 - <span data-ttu-id="d576f-117">**Manuaalinen sekki**: Valitse tämä vaihtoehto, jos olet luonut sekin manuaalisesti ja haluat luoda vastaavan sekkitapahtuman tälle summalle.</span><span class="sxs-lookup"><span data-stu-id="d576f-117">**Manual Check**: Select this option if you have created a check manually and want to create a corresponding check ledger entry for this amount.</span></span> <span data-ttu-id="d576f-118">Tämän vaihtoehdon avulla et voi tulostaa sekkejä Dynamics NAV -ohjelmasta.</span><span class="sxs-lookup"><span data-stu-id="d576f-118">By using this option, you cannot print checks from Dynamics NAV.</span></span> <span data-ttu-id="d576f-119">Voit valita **Manuaalinen sekki** -kohdan vain, jos **Vastatilin tyyppi** tai **Tilin tyyppi** on **Pankkitili**.</span><span class="sxs-lookup"><span data-stu-id="d576f-119">You can only select **Manual Check** if the **Bal. Account Type** or the **Account Type** is **Bank Account**.</span></span>

    <span data-ttu-id="d576f-120">**Huomautus**: Tulosta tietokonesekit, ennen kuin kirjaat liittyvät päiväkirjan rivit.</span><span class="sxs-lookup"><span data-stu-id="d576f-120">**Note**: You must print computer checks before you post the related journal lines.</span></span>
4. <span data-ttu-id="d576f-121">Jos kyseessä on tietokonesekki, valitse **Tulosta sekki**.</span><span class="sxs-lookup"><span data-stu-id="d576f-121">In case of computer checks, choose **Print Check**.</span></span>
5. <span data-ttu-id="d576f-122">Täytä **Sekki**-ikkunassa tarvittavat kentät.</span><span class="sxs-lookup"><span data-stu-id="d576f-122">In the **Check** window, fill in the fields as necessary.</span></span> <span data-ttu-id="d576f-123">Lue kentän lyhyt kuvaus valitsemalla kenttä tai siirry lisätietoihin valitsemalla linkki.</span><span class="sxs-lookup"><span data-stu-id="d576f-123">Choose a field to read a short description of the field or link to more information.</span></span>
6. <span data-ttu-id="d576f-124">Valitse **Tulosta**-painike.</span><span class="sxs-lookup"><span data-stu-id="d576f-124">Choose the **Print** button.</span></span>

<span data-ttu-id="d576f-125">**Huomautus**: Jos haluat tulostaa sekkejä monessa valuutassa eri pankkitileiltä, sinun täytyy suorittaa **Tulosta sekki** -eräajo erikseen kullekin valuutalle ja määrittää sopivat pankkitilit.</span><span class="sxs-lookup"><span data-stu-id="d576f-125">**Note**: If you want to print checks in more than one currency from different bank accounts, you must run the **Print Check** batch job separately for each currency and specify the appropriate bank account.</span></span>

## <a name="to-cancel-printed-checks-that-are-not-posted"></a><span data-ttu-id="d576f-126">Kirjaamattomien ja tulostettujen sekkien peruuttaminen</span><span class="sxs-lookup"><span data-stu-id="d576f-126">To cancel printed checks that are not posted</span></span>
<span data-ttu-id="d576f-127">Voit peruuttaa kirjaamattomat sekit niiden tulostamisen jälkeen **Maksupäiväkirja**-ikkunan **Mitätöi sekki** -toiminnon avulla.</span><span class="sxs-lookup"><span data-stu-id="d576f-127">You can cancel non-posted checks after they have been printed by using the **Void Check** action in the **Payment Journal** window.</span></span>
1. <span data-ttu-id="d576f-128">Valitse **Maksupäiväkirja**-ikkunassa **Mitätöi sekki** ja valitse peruutettavat sekit.</span><span class="sxs-lookup"><span data-stu-id="d576f-128">In the **Payment Journal** window, choose the **Void Check**, and then choose which checks to cancel.</span></span>

## <a name="to-void-checks"></a><span data-ttu-id="d576f-129">Sekkien mitätöiminen</span><span class="sxs-lookup"><span data-stu-id="d576f-129">To void checks</span></span>
<span data-ttu-id="d576f-130">Kun sekkimaksu on kirjattu, voit peruuttaa (mitätöidä) sekit vain tuloksena syntyvistä pankkitapahtumista.</span><span class="sxs-lookup"><span data-stu-id="d576f-130">When check payment have been posted, you can only cancel (void) checks from the resulting bank ledger entries.</span></span>

1. <span data-ttu-id="d576f-131">Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Pankkitilit** ja valitse sitten aiheeseen liittyvä linkki.</span><span class="sxs-lookup"><span data-stu-id="d576f-131">In the top right corner, choose the **Search for Page or Report** icon, enter **Bank Accounts**, and then choose the related link.</span></span>
2. <span data-ttu-id="d576f-132">Valitse oikea pankkitili, valitse **Muokkaa**-toiminto ja valitse sitten **Sekkitapahtumat**-toiminto.</span><span class="sxs-lookup"><span data-stu-id="d576f-132">Select the relevant bank account, choose the **Edit** action, and then choose the **Check Ledger Entries** action.</span></span>
3. <span data-ttu-id="d576f-133">Valitse **Sekkitapahtumat**-ikkunassa **Mitätöi sekki** -toiminto.</span><span class="sxs-lookup"><span data-stu-id="d576f-133">In the **Check Ledger Entries** window, choose the **Void Check** action.</span></span>
4. <span data-ttu-id="d576f-134">Valitse **Mitätöi vain sekki** -valintaruutu.</span><span class="sxs-lookup"><span data-stu-id="d576f-134">Select the **Void Check Only** check box.</span></span>
5. <span data-ttu-id="d576f-135">Valitse **OK**-painike.</span><span class="sxs-lookup"><span data-stu-id="d576f-135">Choose the **OK**button.</span></span>

## <a name="see-also"></a><span data-ttu-id="d576f-136">Katso myös</span><span class="sxs-lookup"><span data-stu-id="d576f-136">See Also</span></span>
[<span data-ttu-id="d576f-137">Ostovelkojen hallinta</span><span class="sxs-lookup"><span data-stu-id="d576f-137">Manage Payables</span></span>](payables-manage-payables.md)  
[<span data-ttu-id="d576f-138">Pankkitoiminnan määrittäminen</span><span class="sxs-lookup"><span data-stu-id="d576f-138">Set Up Banking</span></span>](bank-setup-banking.md)  

