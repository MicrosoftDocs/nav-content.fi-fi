---
title: "Ohjeet: Maksujen täsmäyttäminen käyttämällä automaattista kohdistusta"
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
ms.openlocfilehash: 2936d9491beab1f022e520f7687ec9938c7da47e
ms.contentlocale: fi-fi
ms.lasthandoff: 07/19/2017

---

# <a name="how-to-reconcile-payments-using-automatic-application"></a><span data-ttu-id="5064d-102">Ohjeet: Maksujen täsmäyttäminen käyttämällä automaattista kohdistusta</span><span class="sxs-lookup"><span data-stu-id="5064d-102">How to: Reconcile Payments Using Automatic Application</span></span>
<span data-ttu-id="5064d-103">**Maksujen täsmäytyskirjauskansio** -ikkuna määrittää tulevat tai lähtevät maksut, jotka on tallennettu tapahtumina verkkopankkitilille ja jotka voit kohdistaa niihin liittyviin avoimiin asiakas-, toimittaja- ja pankkitilitapahtumiin.</span><span class="sxs-lookup"><span data-stu-id="5064d-103">The **Payment Reconciliation Journal** window specifies payments, either incoming or outgoing, that have been recorded as transactions on your online bank account and that you can apply to their related open customer, vendor, and bank account ledger entries.</span></span> <span data-ttu-id="5064d-104">Päiväkirjan rivit täytetään tuomalla pankin tiliote syötteenä tai tiedostona.</span><span class="sxs-lookup"><span data-stu-id="5064d-104">The lines in the journal are filled by importing a bank statement as a bank feed or file.</span></span>

<span data-ttu-id="5064d-105">Täsmäytyksen maksukirjauskansion liittyy Dynamics NAV -ohjelmassa yksi pankkitili, joka vastaa verkkopankkitiliä, jolle maksutapahtumat kirjataan.</span><span class="sxs-lookup"><span data-stu-id="5064d-105">A payment reconciliation journal is related to one bank account in Dynamics NAV that reflects the online bank account where the payment transactions are recorded.</span></span> <span data-ttu-id="5064d-106">Kaikki kohdistettuun asiakas- tai toimittajatapahtumaan liittyvät avoimet pankkitilitapahtumat suljetaan, kun valitset **Kirjaa maksut ja täsmäytä pankkitili** -toiminnon.</span><span class="sxs-lookup"><span data-stu-id="5064d-106">Any open bank account ledger entries related to the applied customer or vendor ledger entries will be closed when you choose the **Post Payments and Reconcile Bank Account** action.</span></span> <span data-ttu-id="5064d-107">Tämä tarkoittaa sitä, että pankkitili täsmäytetään automaattisesti päiväkirjaan kirjattaville maksuille.</span><span class="sxs-lookup"><span data-stu-id="5064d-107">This means that the bank account is automatically reconciled for payments that you post with the journal.</span></span>

<span data-ttu-id="5064d-108">Jos haluat ottaa pankin tiliotteet käyttöön pankkisyötteinä, määritä ensin Envestnet Yodlee -pankkisyötepalvelu ja linkitä sitten pankkitili siihen liittyvään verkkopankkitiliin.</span><span class="sxs-lookup"><span data-stu-id="5064d-108">If you want to import bank statements as bank feeds, you must first enable the Envestnet Yodlee Bank Feeds service and then link the bank account to its related online bank account.</span></span> <span data-ttu-id="5064d-109">Maksujen täsmäytyskirjauskansio havaitsee automaattisesti pankkisyötteet, kun valitset **Tuo pankkitapahtumat** -toiminnon.</span><span class="sxs-lookup"><span data-stu-id="5064d-109">The payment reconciliation journal will then automatically detect bank feeds when you choose the **Import Bank Transactions** action.</span></span> <span data-ttu-id="5064d-110">Lisäksi voit määrittää pankkitilin niin, että se tuo uudet tiliotesyötteet tunnin välein automaattisesti.</span><span class="sxs-lookup"><span data-stu-id="5064d-110">In addition, you can set a bank account up to automatically import new bank statement feeds every hour.</span></span> <span data-ttu-id="5064d-111">Niiden maksujen tapahtumia, jotka on jo kohdistettu ja/tai täsmäytetty, ei tuoda.</span><span class="sxs-lookup"><span data-stu-id="5064d-111">Transactions for payments that have already been posted as applied and/or reconciled will not be imported.</span></span> <span data-ttu-id="5064d-112">Lisätietoja on kohdassa [Toimintaohje: Envestnet Yodlee -pankkisyötepalvelun määrittäminen](bank-how-setup-bank-statement-service.md).</span><span class="sxs-lookup"><span data-stu-id="5064d-112">For more information, see [How to: Set Up the Envestnet Yodlee Bank Feeds Service](bank-how-setup-bank-statement-service.md).</span></span>

<span data-ttu-id="5064d-113">**Huomautus**: Envestnet Yodlee -pankkisyötepalvelu tai toisen palveluntarjoajan pankkisyötepalvelu ei ehkä ole käytettävissä järjestelmässäsi.</span><span class="sxs-lookup"><span data-stu-id="5064d-113">**Note**: The Envestnet Yodlee Bank Feeds service, or anther provider's bank feed service, may not be available in your system.</span></span> <span data-ttu-id="5064d-114">Jos haluat käyttää pankkisyötepalvelua tiliotteiden tuomiseen, ota yhteys Microsoft-yhteistyökumppaniisi.</span><span class="sxs-lookup"><span data-stu-id="5064d-114">Contact your Microsoft partner if you want to use a bank feed service to import bank statements.</span></span>

<span data-ttu-id="5064d-115">**Linkitä teksti tiliin** -ikkunassa voit määrittää maksujen tekstin kohdistukset ja tietyt debet-, kredit- ja kirjanpidon vastatilit siten, että nämä maksut kirjataan tietyille tileille, jotta nämä maksut kirjataan tietyille tileille, kun kirjaat maksun täsmäytyksen päiväkirjan.</span><span class="sxs-lookup"><span data-stu-id="5064d-115">With the **Map Text to Account** action, you can set up mappings between text on payments and specific debit, credit, and balancing accounts so that such payments are posted to the specified accounts when you post the payment reconciliation journal.</span></span> <span data-ttu-id="5064d-116">Katso vaihe 9.</span><span class="sxs-lookup"><span data-stu-id="5064d-116">See step 9.</span></span> <span data-ttu-id="5064d-117">Lisätietoja on kohdassa [Toimintaohje: Toistuvien maksujen tekstin yhdistäminen tileihin automaattisen täsmäytyksen suorittamiseksi](receivables-how-map-text-recurring-payments-accounts-auto-reconcilliation.md).</span><span class="sxs-lookup"><span data-stu-id="5064d-117">For more information, see [How to: Map Text on Recurring Payments to Accounts for Automatic Reconciliation](receivables-how-map-text-recurring-payments-accounts-auto-reconcilliation.md).</span></span>

<span data-ttu-id="5064d-118">Vastaava toiminto on käytettävissä, kun maksujen täsmäytyskirjauskansion rivien ylimääräisiä summia täsmäytetään ad hoc.</span><span class="sxs-lookup"><span data-stu-id="5064d-118">Similar functionality exists to reconcile excess amounts on payment reconciliation journal lines on an ad-hoc basis.</span></span> <span data-ttu-id="5064d-119">Lisätietoja on kohdassa [Toimintaohje: Niiden maksujen täsmäyttäminen, joita ei voi kohdistaa.](receivables-how-reconcile-payments-cannot-apply-auto.md)</span><span class="sxs-lookup"><span data-stu-id="5064d-119">For more information, see [How to: Reconcile Payments That Cannot be Applied.](receivables-how-reconcile-payments-cannot-apply-auto.md)</span></span>

<span data-ttu-id="5064d-120">Voit käyttää **Kohdista automaattisesti** -toimintoa, joko automaattisesti, kun tuot pankkitiedoston tai -syötteen ja maksutapahtumat tai kun aktivoit sen maksujen kohdistamiseksi niiden vastaaviin avoimiin tapahtumiin, jotka perustuvat vastaaviin tietoihin päiväkirjarivillä, jossa on tietoja avoimista tapahtumista.</span><span class="sxs-lookup"><span data-stu-id="5064d-120">You use the **Apply Automatically** function, either automatically when you import a bank file or feed with payment transactions or when you activate it, to apply payments to their related open entries based on a matching of data on a journal line with data on one or more open entries.</span></span>

<span data-ttu-id="5064d-121">Kirjauskansion riveillä, joilla maksu on kohdistettu automaattisesti yhteen tai useaan avoimeen tapahtumaan, **Vastaavuuden luotettavuus** -kentässä on arvo väliltä Alhainen ja Suuri. Se osoittaa niiden kohdistettujen tietojen laadun, joihin ehdotettu maksusovellus perustuu.</span><span class="sxs-lookup"><span data-stu-id="5064d-121">On journal lines where a payment has been applied automatically to one or more open entries, the **Match Confidence** field has a value between Low and High to indicate the quality of the data matching that the suggested payment application is based on.</span></span> <span data-ttu-id="5064d-122">Lisäksi **Tilityyppi**- ja **Tilinumero**-kenttiin</span><span class="sxs-lookup"><span data-stu-id="5064d-122">In addition, the **Account Type** and **Account No.**</span></span> <span data-ttu-id="5064d-123">täytetään asiakkaan tai toimittajan maksun kohdistamiseen liittyvät tiedot.</span><span class="sxs-lookup"><span data-stu-id="5064d-123">fields are filled with information about the customer or vendor that the payment is applied to.</span></span> <span data-ttu-id="5064d-124">Jos olet asettanut tekstistä tiliin yhdistämisen, automaattisen kohdistuksen tuloksena saattaa olla vastaavuusarvo **Suuri - tekstin ja tilin välinen yhdistäminen**.</span><span class="sxs-lookup"><span data-stu-id="5064d-124">If you have set up a text-to-account mapping, the automatic application can result in a match confidence value of **High - Text-to-Account Mapping**.</span></span>

<span data-ttu-id="5064d-125">Voit avata kullekin maksua esittävälle päiväkirjan riville **Maksujen täsmäytyskirjauskansio** -ikkunassa **Maksun kohdistus** -ikkunan ja tarkastella kaikkia mahdollisia avoimia maksuja ja yksityiskohtaisia tietoja merkintöjen täsmäytyksestä, joihin maksujen kohdistus perustuu.</span><span class="sxs-lookup"><span data-stu-id="5064d-125">For each journal line in the **Payment Reconciliation Journal** window, you can open the **Payment Application** window to see all candidate open entries for the payment and view detailed information for each entry about the data matching that a payment application is based on.</span></span> <span data-ttu-id="5064d-126">Tässä voit kohdistaa maksuja manuaalisesti tai kohdistaa uudelleen maksuja, joka kohdistettiin automaattisesti väärään merkintään.</span><span class="sxs-lookup"><span data-stu-id="5064d-126">Here, you can manually apply payments or reapply payments that were applied automatically to a wrong entry.</span></span> <span data-ttu-id="5064d-127">Lisätietoja on kohdassa [Toimintaohje: Maksujen tarkasteleminen tai kohdistaminen automaattisen kohdistuksen jälkeen](receivables-how-review-apply-payments-auto-application.md).</span><span class="sxs-lookup"><span data-stu-id="5064d-127">For more information, see [How to: Review or Apply Payments After Automatic Application](receivables-how-review-apply-payments-auto-application.md).</span></span>

<span data-ttu-id="5064d-128">**Huomautus**: Voit aloittaa pankkitapahtumien tuonnin samaan aikaan, kun avaat **Maksujen täsmäytyskirjauskansio** -ikkunan olemassa olevalle maksun täsmäytyksen kirjauskansiolle **Maksun täsmäytyksen päiväkirjat** -ikkunassa.</span><span class="sxs-lookup"><span data-stu-id="5064d-128">**Note**: You can start the bank transactions import at the same time as you open the **Payment Reconciliation** Journal window for an existing payment reconciliation journal in the **Payment Reconciliation Journals** window.</span></span> <span data-ttu-id="5064d-129">Seuraava toimenpide kuvaa kuinka pankkitapahtumat tuodaan **Maksujen täsmäytyskirjauskansio** -ikkunaan, kun olet luonut uuden päiväkirjan.</span><span class="sxs-lookup"><span data-stu-id="5064d-129">The following procedure describes how to import bank transactions into the **Payment Reconciliation Journal** window after you have created a new journal.</span></span>

## <a name="to-reconcile-payments-using-automatic-application"></a><span data-ttu-id="5064d-130">Maksujen täsmäyttäminen käyttämällä automaattista kohdistusta</span><span class="sxs-lookup"><span data-stu-id="5064d-130">To reconcile payments using automatic application</span></span>
1. <span data-ttu-id="5064d-131">Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Maksujen täsmäytyskirjauskansiot** ja valitse sitten aiheeseen liittyvä linkki.</span><span class="sxs-lookup"><span data-stu-id="5064d-131">In the top right corner, choose the **Search for Page or Report** icon, enter **Payment Reconciliation Journals**, and then choose the related link.</span></span>
2. <span data-ttu-id="5064d-132">Voit käsitellä uuden maksun täsmäytyksen päiväkirjaa valitsemalla **Uusi päiväkirja** -toiminnon.</span><span class="sxs-lookup"><span data-stu-id="5064d-132">To work in a new payment reconciliation journal, choose the **New Journal** action.</span></span>
3. <span data-ttu-id="5064d-133">Valitse **Maksun pankkitililuettelo** -ikkunassa pankkitili, johon maksut täsmäytetään, ja valitse sitten **OK**-painike.</span><span class="sxs-lookup"><span data-stu-id="5064d-133">In the **Payment Bank Account List** window, select the bank account that you want to reconcile payments for, and then choose the **OK** button.</span></span>
<span data-ttu-id="5064d-134">**Maksujen täsmäytyskirjauskansio** -ikkuna avautuu valmisteltuna valitulle pankkitilille.</span><span class="sxs-lookup"><span data-stu-id="5064d-134">The **Payment Reconciliation Journal** window opens prepared for the selected bank account.</span></span>
4. <span data-ttu-id="5064d-135">Valitse **Tuo pankkitapahtumat** -toiminto.</span><span class="sxs-lookup"><span data-stu-id="5064d-135">Choose the **Import Bank Transactions** action.</span></span>
<span data-ttu-id="5064d-136">Jos pankkitapahtumien tuontia varten ei ole määritetty valitun kirjauskansion pankkitiliä, valintaikkuna avautuu auttaen sinua täyttämään asianmukaiset kentät.</span><span class="sxs-lookup"><span data-stu-id="5064d-136">If the bank account for the selected journal is not set up for import of bank transactions, then a dialog box will open to help you fill in the relevant fields.</span></span>
5. <span data-ttu-id="5064d-137">Valitse **Valitse tuotava tiedosto** -ikkunassa tiedosto, joka sisältää täsmäytettävät pankkitapahtumat täsmäytettäville maksuille, ja valitse sitten **Avaa**-painike.</span><span class="sxs-lookup"><span data-stu-id="5064d-137">In the **Select a file to import** window, select the file that contains the bank transactions for payments that you want to reconcile, and then choose the **Open** button.</span></span>  
6. <span data-ttu-id="5064d-138">Jos pankin tiliotepalvelu on otettu käyttöön, määritä automaattisesti avautuvassa **Pankin tiliotteen suodatus** -ikkunassa pankin tiliotteiden tuonnille päivämääräväli.</span><span class="sxs-lookup"><span data-stu-id="5064d-138">If the Bank Statement service is enabled, in the **Bank Statement Filter** window that opens automatically, specify the date interval for the bank statements to be imported.</span></span>

    <span data-ttu-id="5064d-139">**Maksujen täsmäytyskirjauskansio** -ikkuna sisältää maksurivit, jotka kuvaavat tuodun pankin tiliotteen pankkitapahtumia.</span><span class="sxs-lookup"><span data-stu-id="5064d-139">The **Payment Reconciliation Journal** window is filled with lines for payments representing bank transactions in the imported bank statement.</span></span>

    <span data-ttu-id="5064d-140">Maksujen riveillä, jotka on automaattisesti kohdistettu niiden vastaaviin avoimiin tapahtumiin, **Vastaavuuden luotettavuus** -kentässä on arvo väliltä **Alhainen** ja **Suuri**. Tämä osoittaa niiden kohdistettujen tietojen laadun, joihin ehdotettu maksusovellus perustuu.</span><span class="sxs-lookup"><span data-stu-id="5064d-140">On lines for payments that have been automatically applied to their related open entries, the **Match Confidence** field has a value between **Low** and **High** to indicate the quality of the data matching that the suggested payment application is based on.</span></span> <span data-ttu-id="5064d-141">Lisäksi **Tilityyppi**- ja **Tilinumero**-kenttiin</span><span class="sxs-lookup"><span data-stu-id="5064d-141">In addition, the **Account Type** and **Account No.**</span></span> <span data-ttu-id="5064d-142">täytetään asiakkaan tai toimittajan maksun kohdistamiseen liittyvät tiedot.</span><span class="sxs-lookup"><span data-stu-id="5064d-142">fields are filled with information about the customer or vendor that the payment is applied to.</span></span>
7. <span data-ttu-id="5064d-143">Valitse päiväkirjarivi ja valitse sitten **Kohdista manuaalisesti** -toiminto, kun haluat tarkastaa, kohdistaa uudelleen tai kohdistaa maksun manuaalisesti **Maksun kohdistus** -ikkunassa.</span><span class="sxs-lookup"><span data-stu-id="5064d-143">Select a journal line, and then, choose the **Apply Manually** action to review, reapply, or apply the payment manually in the **Payment Application** window.</span></span> <span data-ttu-id="5064d-144">Lisätietoja on kohdassa [Toimintaohje: Maksujen tarkasteleminen tai kohdistaminen automaattisen kohdistuksen jälkeen](receivables-how-review-apply-payments-auto-application.md).</span><span class="sxs-lookup"><span data-stu-id="5064d-144">For more information, see [How to: Review or Apply Payments After Automatic Application](receivables-how-review-apply-payments-auto-application.md).</span></span>

    <span data-ttu-id="5064d-145">Kun olet suorittanut manuaalisen kohdistuksen, manuaalisesti käsittelemäsi päiväkirjarivin **Vastaavuuden luotettavuus** -kentän arvo on **Hyväksytty**.</span><span class="sxs-lookup"><span data-stu-id="5064d-145">When you have finished your manual application, the **Match Confidence** field on the journal line that you have processed manually contains **Accepted**.</span></span>
8. <span data-ttu-id="5064d-146">Valitse kohdistamaton päiväkirjarivi toistuvalle kassasuoritukselle tai kululle, kuten auton polttoaineen hankinta ja valitse sitten Kotisivu-välilehden Tarkastelu-ryhmässä Linkitä teksti tiliin.</span><span class="sxs-lookup"><span data-stu-id="5064d-146">Select an unapplied journal line for a recurring cash receipt or expense, such as a car gasoline purchase, and then on the Home tab, in the Review group, choose Map Text to Account.</span></span> <span data-ttu-id="5064d-147">Lisätietoja on kohdassa [Toimintaohje: Toistuvien maksujen tekstin yhdistäminen tileihin automaattisen täsmäytyksen suorittamiseksi](receivables-how-map-text-recurring-payments-accounts-auto-reconcilliation.md)</span><span class="sxs-lookup"><span data-stu-id="5064d-147">For more information, see [How to: Map Text on Recurring Payments to Accounts for Automatic Reconciliation](receivables-how-map-text-recurring-payments-accounts-auto-reconcilliation.md)</span></span>
9. <span data-ttu-id="5064d-148">Kun olet lopettanut maksutekstin yhdistämisen tileihin, valitse **Kohdista manuaalisesti** -toiminto.</span><span class="sxs-lookup"><span data-stu-id="5064d-148">When you have finished your mapping of payment text to accounts, choose the **Apply Manually** action.</span></span>
10. <span data-ttu-id="5064d-149">Kun olet varma, että kaikki päiväkirjarivien maksut on kohdistettu oikein tai asetettu suorakirjaukselle, valitse **Kirjaa**-toiminto.</span><span class="sxs-lookup"><span data-stu-id="5064d-149">When you are content that all payments on the journal lines are correctly applied or set to direct posting, choose the **Post** action.</span></span>

<span data-ttu-id="5064d-150">Kun kirjaat maksun täsmäytyksen päiväkirjan, kohdistetut avoimet tapahtumat suljetaan ja liittyvät asiakas- tai toimittaja- tai kirjanpitotilit päivitetään.</span><span class="sxs-lookup"><span data-stu-id="5064d-150">When you post the payment reconciliation journal, the applied open entries memos are closed, and the related customer, vendor, or general ledger accounts are updated.</span></span> <span data-ttu-id="5064d-151">Määritetyt kirjanpitotilit päivitetään tekstin tiliin yhdistämiseen perustuville asiakas-, toimittaja ja kirjanpitotileille.</span><span class="sxs-lookup"><span data-stu-id="5064d-151">For payments on journal lines based on text-to-account mapping, the specified customer, vendor, and general ledger accounts are updated.</span></span> <span data-ttu-id="5064d-152">Kaikille pankkitilitapahtumille luodaan kirjauskansiorivit.</span><span class="sxs-lookup"><span data-stu-id="5064d-152">For all journal lines, bank account ledger entries are created.</span></span> <span data-ttu-id="5064d-153">Jos valitset **Kirjaa maksut ja täsmäytä pankkitili** -toiminnon, kaikki kohdistettuun asiakas- tai toimittajatapahtumaan liittyvät avoimet pankkitilitapahtumat suljetaan.</span><span class="sxs-lookup"><span data-stu-id="5064d-153">If you choose the **Post Payments and Reconcile Bank Account** action, any open bank account ledger entries related to the applied customer or vendor ledger entries will be closed.</span></span> <span data-ttu-id="5064d-154">Tämä tarkoittaa sitä, että pankkitili täsmäytetään automaattisesti päiväkirjaan kirjattaville maksuille.</span><span class="sxs-lookup"><span data-stu-id="5064d-154">This means that the bank account is automatically reconciled for payments that you post with the journal.</span></span>

<span data-ttu-id="5064d-155">Voit verrata **Pankkitilin saldo kirjauksen jälkeen** -kentän ja **Tiliotteen loppusaldo** -kentän arvoa seurataksesi, milloin pankkitili täsmäytetään kirjaamiesi maksujen perusteella.</span><span class="sxs-lookup"><span data-stu-id="5064d-155">You can compare the value in the **Balance on Bank Account After Posting** field together with the value in the **Statement Ending Balance** field to track when the bank account is reconciled based on payments that you post.</span></span>

<span data-ttu-id="5064d-156">**Huomautus**: Jos et halua täsmäyttää pankkitiliä **Maksujen täsmäytyskirjauskansio** -ikkunassa, sinun on käytettävä **Pankkitilin täsmäytys** -ikkunaa.</span><span class="sxs-lookup"><span data-stu-id="5064d-156">**Note**: If you do not want to reconcile the bank account from the **Payment Reconciliation Journal** window, then you must use the **Bank Acc. Reconciliation** window.</span></span> <span data-ttu-id="5064d-157">Lisätietoja on kohdassa [Pankkitilien täsmäyttäminen erikseen](bank-how-reconcile-bank-accounts-separately.md).</span><span class="sxs-lookup"><span data-stu-id="5064d-157">For more information, see [Reconcile Bank Accounts Separately](bank-how-reconcile-bank-accounts-separately.md).</span></span>

## <a name="see-also"></a><span data-ttu-id="5064d-158">Katso myös</span><span class="sxs-lookup"><span data-stu-id="5064d-158">See Also</span></span>
[<span data-ttu-id="5064d-159">Myyntisaamisten hallinta</span><span class="sxs-lookup"><span data-stu-id="5064d-159">Manage Receivables</span></span>](receivables-manage-receivables.md)  
[<span data-ttu-id="5064d-160">Myynnin hallinta</span><span class="sxs-lookup"><span data-stu-id="5064d-160">Manage Sales</span></span>](sales-manage-sales.md)
