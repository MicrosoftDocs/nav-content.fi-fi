---
title: "Toimintaohje: Pinojen värillisen mittarin määrittäminen"
author: SusanneWindfeldPedersen
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 6b60b1344a1e18ad91863046110df880f75f7c04
ms.openlocfilehash: 38cd904d0cf22374eac430d035e6ea6d205bcab8
ms.contentlocale: fi-fi
ms.lasthandoff: 07/19/2017

---
    
# <a name="how-to-set-up-a-colored-indicator-on-cues"></a><span data-ttu-id="e3915-102">Toimintaohje: Pinojen värillisen mittarin määrittäminen</span><span class="sxs-lookup"><span data-stu-id="e3915-102">How to: Set Up a Colored Indicator on Cues</span></span>
<span data-ttu-id="e3915-103">Voit määrittää pinot, jotka näkyvät käyttäjien **kotisivulla**, kun haluat sisällyttää ilmaisimen, joka vaihtaa väriä pinojen arvojen mukaan.</span><span class="sxs-lookup"><span data-stu-id="e3915-103">You can set up Cues that appear on the **Home** page to include an indicator that changes color based on the data values in the Cues.</span></span> 

<span data-ttu-id="e3915-104">Ilmaisin näkyy värillisenä palkkina pinon ruudun yläreunassa.</span><span class="sxs-lookup"><span data-stu-id="e3915-104">The indicator appears as a colored bar along the top border of the Cue tile.</span></span> <span data-ttu-id="e3915-105">Se antaa visuaalisen signaalin pinon toiminnan tilasta, joka voi ilmaista suotuisia tai epäsuotuisia olosuhteita ja kehottaa käyttäjää toimimaan.</span><span class="sxs-lookup"><span data-stu-id="e3915-105">It provides a visual signal of the status of the Cue's activity, which can indicate favorable or unfavorable conditions to prompt the user to take action.</span></span> <span data-ttu-id="e3915-106">Esimerkiksi, jos pino näyttää myyntilaskujen jatkuvan, voit määrittää ilmaisimen näkymään vihreänä (hyvä), kun jatkuva myyntilaskujen määrä on alle 10, ja se muuttuu punaiseksi (epäsuotuisa) kun summa on yli 20.</span><span class="sxs-lookup"><span data-stu-id="e3915-106">For example, if a Cue displays ongoing sales invoices, you can set up the indicator to appear green (favorable) when total number of ongoing sales invoices is below 10, and appears red (unfavorable) when the total is greater than 20.</span></span>

<span data-ttu-id="e3915-107">**Pinon asetukset** -ikkunasta voit asettaa ilmaisimet kaikille pinoille, jotka ovat saatavilla yhtiön tietokannassa.</span><span class="sxs-lookup"><span data-stu-id="e3915-107">From the **Cue Setup** window, you set up indicators for all the Cues that are available in the company database.</span></span>

<span data-ttu-id="e3915-108">Jotta voit määrittää ilmaisimen, sinun on määritettävä korkeintaan kaksi raja-arvoa, jotka määrittävät kolme arvoaluetta (matala, keskisuuri ja korkea), joihin voit käyttää eri värejä (tai tyyliä).</span><span class="sxs-lookup"><span data-stu-id="e3915-108">To set up the indicator, you specify up to two threshold values that define three ranges of data values (low, middle, and high) to which you can apply a different color (or style).</span></span>

## <a name="to-set-up-colored-indicators-on-cues"></a><span data-ttu-id="e3915-109">Värillisten ilmaisinten määrittäminen pinoissa</span><span class="sxs-lookup"><span data-stu-id="e3915-109">To set up colored indicators on Cues</span></span>
1. <span data-ttu-id="e3915-110">Valitse **kotisivun** **Toimenpiteet**-kohdassa **Määritä pinot**.</span><span class="sxs-lookup"><span data-stu-id="e3915-110">Under **Activities** on your **Home** page, choose **Set Up Cues**.</span></span>  
<span data-ttu-id="e3915-111">**Pinon asetukset** -ikkuna aukeaa.</span><span class="sxs-lookup"><span data-stu-id="e3915-111">The **Cue Setup** window appears.</span></span> <span data-ttu-id="e3915-112">Ikkunassa on lueteltu ilmaisimet, jotka on tällä hetkellä asetettu pinoissa.</span><span class="sxs-lookup"><span data-stu-id="e3915-112">The window lists the indicators that are currently setup up on Cues.</span></span>
2. <span data-ttu-id="e3915-113">Voit muokata ilmaisinta muokkaamalla kenttiä ja muokkaamalla esimerkiksi eri rajojen arvoja.</span><span class="sxs-lookup"><span data-stu-id="e3915-113">To modify an indicator, edit the fields and modify, for example, the values for the different thresholds.</span></span>  

<span data-ttu-id="e3915-114">Seuraava taulukko sisältää värit, jotka vastaavat **Matalan alueen tyyli**-, **Keskialueen tyyli**- ja **Korkean alueen tyyli** -kenttää.</span><span class="sxs-lookup"><span data-stu-id="e3915-114">The following table lists the colors that correspond to the options of the **Low Range Style**, **Middle Range Style**, and **High Range Style** fields.</span></span>

|<span data-ttu-id="e3915-115">Asetus</span><span class="sxs-lookup"><span data-stu-id="e3915-115">Option</span></span>|<span data-ttu-id="e3915-116">Väri</span><span class="sxs-lookup"><span data-stu-id="e3915-116">Color</span></span>|
|------|-----|
|<span data-ttu-id="e3915-117">**Ei yhtään**</span><span class="sxs-lookup"><span data-stu-id="e3915-117">**None**</span></span>|<span data-ttu-id="e3915-118">Ei väriä (sama väri kuin pinon ruutu</span><span class="sxs-lookup"><span data-stu-id="e3915-118">No color (same color as the Cue tile</span></span>|
|<span data-ttu-id="e3915-119">**Suotuisa**</span><span class="sxs-lookup"><span data-stu-id="e3915-119">**Favorable**</span></span>|<span data-ttu-id="e3915-120">Vihreä</span><span class="sxs-lookup"><span data-stu-id="e3915-120">Green</span></span>|
|<span data-ttu-id="e3915-121">**Epäsuotuisa**</span><span class="sxs-lookup"><span data-stu-id="e3915-121">**Unfavorable**</span></span>|<span data-ttu-id="e3915-122">Punainen</span><span class="sxs-lookup"><span data-stu-id="e3915-122">Red</span></span>|
|<span data-ttu-id="e3915-123">**Epäselvä**</span><span class="sxs-lookup"><span data-stu-id="e3915-123">**Ambiguous**</span></span>|<span data-ttu-id="e3915-124">Keltainen</span><span class="sxs-lookup"><span data-stu-id="e3915-124">Yellow</span></span>|
|<span data-ttu-id="e3915-125">**Alataso**</span><span class="sxs-lookup"><span data-stu-id="e3915-125">**Subordinate**</span></span>|<span data-ttu-id="e3915-126">Harmaa</span><span class="sxs-lookup"><span data-stu-id="e3915-126">Gray</span></span>|

## <a name="see-also"></a><span data-ttu-id="e3915-127">Katso myös</span><span class="sxs-lookup"><span data-stu-id="e3915-127">See Also</span></span>
[<span data-ttu-id="e3915-128">Dynamics NAV -ohjelman käyttäminen</span><span class="sxs-lookup"><span data-stu-id="e3915-128">Work with Dynamics NAV</span></span>](ui-work-product.md)


