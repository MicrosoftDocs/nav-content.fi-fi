---
title: Toimittajamaksujen ehdottaminen
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
ms.openlocfilehash: 3ede5942798e34fd0e4b3ab8cc48ca94eed3d1a4
ms.contentlocale: fi-fi
ms.lasthandoff: 07/19/2017

---

# <a name="how-to-suggest-vendor-payments"></a><span data-ttu-id="61d5c-102">Toimittajamaksujen ehdottaminen</span><span class="sxs-lookup"><span data-stu-id="61d5c-102">How to: Suggest Vendor Payments</span></span>
<span data-ttu-id="61d5c-103">**Maksupäiväkirja**-ikkunassa voit ehdottaa toiminnon avulla maksurivejä asetusten, kuten pian erääntyvien maksujen tai maksualennuksen omaavien maksujen, mukaan.</span><span class="sxs-lookup"><span data-stu-id="61d5c-103">In the **Payment Journal** window, you can use a function to suggest payment lines according to your settings, such as payments that are due soon or payments where a payment discount is available.</span></span>

<span data-ttu-id="61d5c-104">Ehdota toimittajamaksuja -toiminnosta on hyötyä eniten, jos priorisoit toimittajat ensin.</span><span class="sxs-lookup"><span data-stu-id="61d5c-104">To benefit fully from the Suggest Vendor Payments function, you must first prioritize your vendors.</span></span> <span data-ttu-id="61d5c-105">Lisätietoja on ohjeaiheessa [Toimintaohje: Toimittajien priorisoiminen](purchasing-how-prioritize-vendors.md).</span><span class="sxs-lookup"><span data-stu-id="61d5c-105">For more information, see [How to: Prioritize Vendors](purchasing-how-prioritize-vendors.md).</span></span>

<span data-ttu-id="61d5c-106">Toimittajatapahtumia, joita ei ole merkitty **Estossa**-merkinnällä, ei sisällytetä eräajoon.</span><span class="sxs-lookup"><span data-stu-id="61d5c-106">Vendor entries that are not marked **On Hold** are not included in the batch job.</span></span>  

<span data-ttu-id="61d5c-107">**Tärkeää**: Jos haluat hyötyä maksualennuksista, ja jos olet syöttänyt saatavilla olevan summan, summaa käytetään priorisoiduille erääntyneille toimittajatapahtumille, joilla on korkein prioriteetti, ja sitten erääntyneille toimittajatapahtumille, joita ei ole priorisoitu, ja lopuksi avoimille toimittajatapahtumille, jotka kelpuutetaan maksualennuksiin toimittajanumeron mukaan.</span><span class="sxs-lookup"><span data-stu-id="61d5c-107">**Important**: If you want to take advantage of payment discounts and have entered an available amount, the amount will be used for prioritized overdue vendor entries first in order of priority, and then for overdue vendor entries that are not prioritized, and finally for open vendor entries that qualify for payment discounts in order of vendor number.</span></span>

## <a name="to-use-the-suggest-vendor-payments-function"></a><span data-ttu-id="61d5c-108">Ehdota toimittajamaksuja -toiminnon käyttäminen</span><span class="sxs-lookup"><span data-stu-id="61d5c-108">To use the Suggest Vendor Payments function</span></span>
1. <span data-ttu-id="61d5c-109">Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Maksupäiväkirjat** ja valitse sitten aiheeseen liittyvä linkki.</span><span class="sxs-lookup"><span data-stu-id="61d5c-109">In the top right corner, choose the **Search for Page or Report** icon, enter **Payment Journals**, and then choose the related link.</span></span>
2. <span data-ttu-id="61d5c-110">Avaa asianmukainen päiväkirja ja valitse **Ehdota toimittajamaksuja** -toiminto.</span><span class="sxs-lookup"><span data-stu-id="61d5c-110">Open the relevant journal, and then choose the **Suggest Vendor Payments** action.</span></span>
3. <span data-ttu-id="61d5c-111">Täytä tarvittavat kentät.</span><span class="sxs-lookup"><span data-stu-id="61d5c-111">Fill in the fields as necessary.</span></span> <span data-ttu-id="61d5c-112">Lue kentän lyhyt kuvaus valitsemalla kenttä tai siirry lisätietoihin valitsemalla linkki.</span><span class="sxs-lookup"><span data-stu-id="61d5c-112">Choose a field to read a short description of the field or link to more information.</span></span>
4. <span data-ttu-id="61d5c-113">Valitse **OK**-painike.</span><span class="sxs-lookup"><span data-stu-id="61d5c-113">Choose the **OK** button.</span></span>

## <a name="to-insert-the-due-date-as-posting-date-on-payment-journal-lines"></a><span data-ttu-id="61d5c-114">Eräpäivän lisääminen maksupäiväkirjan rivien kirjauspäivämääräksi</span><span class="sxs-lookup"><span data-stu-id="61d5c-114">To insert the due date as posting date on payment journal lines</span></span>
<span data-ttu-id="61d5c-115">Kun **Ehdota toimittajamaksuja** -eräajoa käytetään toimittajien maksurivien luomisessa, täyttämällä kaksi erikoiskenttää voi varmistaa, että luodut rivit käyttävät eräpäivää kirjauspäivämäärän laskemisessa.</span><span class="sxs-lookup"><span data-stu-id="61d5c-115">When you use the **Suggest Vendor Payments** batch job to create payment lines for your vendors, you can fill two special fields to make sure that the generated lines use the due date to calculate the posting date.</span></span> <span data-ttu-id="61d5c-116">Nämä kentät ovat **Laske kirjauspäivämäärä kohdistuksen asiakirjan eräpäivästä** ja **Kohdistuksen asiakirjan eräpäivän siirtymä**.</span><span class="sxs-lookup"><span data-stu-id="61d5c-116">These fields are **Calculate Posting Date from Applies-to-Doc Due Date** and **Applies-to-Doc Due Date Offset**.</span></span>

<span data-ttu-id="61d5c-117">**Tärkeää**: Et voi käyttää **Laske kirjauspäivämäärä kohdistuksen asiakirjan eräpäivästä** -kenttää yhdessä **Hae maksualennukset**- tai **Tee yhteenveto toimittajittain** -kentän kanssa.</span><span class="sxs-lookup"><span data-stu-id="61d5c-117">**Important**: You cannot use the **Calculate Posting Date from Applies-to-Doc Due Date** field together with the **Find Payment Discounts** field or the **Summarize per Vendor** field.</span></span> <span data-ttu-id="61d5c-118">Syy on se, että mikäli tiliöintipäivä perustuu eräpäivään, joitain maksualennuksia ei ehkä ole laskettu oikein, koska tiliöintipäivä voi olla maksualennuspäivän jälkeen.</span><span class="sxs-lookup"><span data-stu-id="61d5c-118">The reason is that if the posting date is based on the due date, then some payment discount may not be calculated correctly, because the posting date could occur after the payment discount date.</span></span>
<span data-ttu-id="61d5c-119">Jos laskettu kirjauspäivämäärä esiintyy menneisyydessä, kirjauspäivämäärää myös siirretään ylös käsittelypäivämäärään, ja näyttöön tulee varoitus.</span><span class="sxs-lookup"><span data-stu-id="61d5c-119">Also, if the calculated posting date occurs in the past, then the posting date will be moved up to the work date, and a warning is displayed.</span></span>

<span data-ttu-id="61d5c-120">Vaihtoehtoisesti voit luoda maksurivejä manuaalisesti niin, että eräpäivää käytetään kirjauspäivämäärän laskemisessa.</span><span class="sxs-lookup"><span data-stu-id="61d5c-120">Alternatively, you can also manually create payment lines using the due date to calculate the posting date.</span></span> <span data-ttu-id="61d5c-121">Kun olet kohdistanut toimittajatapahtumat, voit käyttää **Laske kirjauspäivämäärä** -toimintoa.</span><span class="sxs-lookup"><span data-stu-id="61d5c-121">After you have applied vendor ledger entries, you can use the **Calculate Posting Date** action.</span></span> <span data-ttu-id="61d5c-122">Tämä päivittää päiväkirjan rivin kirjauspäivämääräksi liittyvän ostotilauksen eräpäivän.</span><span class="sxs-lookup"><span data-stu-id="61d5c-122">This will update the posting date on the journal line with the due date of the related purchase invoice.</span></span> <span data-ttu-id="61d5c-123">Lisätietoja on kohdassa [Toimintaohje: Ostotapahtumien kohdistaminen manuaalisesti](payables-how-apply-purchase-transactions-manually.md).</span><span class="sxs-lookup"><span data-stu-id="61d5c-123">For more information, see [How to: Apply Purchase Transactions Manually](payables-how-apply-purchase-transactions-manually.md).</span></span>  

<span data-ttu-id="61d5c-124">**Huomautus**: Jos ostolasku on myöhässä, käsittelypäivämäärä asetetaan käsittelypäivämääräksi ja rivin kirjasin muuttuu punaiseksi.</span><span class="sxs-lookup"><span data-stu-id="61d5c-124">**Note**: If the purchase invoice is overdue, then the posting date will be set to the work date, and the font on the line will change to red color.</span></span>

## <a name="see-also"></a><span data-ttu-id="61d5c-125">Katso myös</span><span class="sxs-lookup"><span data-stu-id="61d5c-125">See Also</span></span>
[<span data-ttu-id="61d5c-126">Ostovelkojen hallinta</span><span class="sxs-lookup"><span data-stu-id="61d5c-126">Manage Payables</span></span>](payables-manage-payables.md)  
[<span data-ttu-id="61d5c-127">Maksujen suorittaminen</span><span class="sxs-lookup"><span data-stu-id="61d5c-127">Make Payments</span></span>](payables-make-payments.md)  
[<span data-ttu-id="61d5c-128">Yleisten päiväkirjojen käyttäminen</span><span class="sxs-lookup"><span data-stu-id="61d5c-128">Work with General Journals</span></span>](ui-work-general-journals.md)

