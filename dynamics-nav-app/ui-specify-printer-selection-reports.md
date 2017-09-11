---
title: "Tulostimen valinnan määrittäminen raporteille"
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
ms.openlocfilehash: 56a5c1428651162293e56d71e2369fe55d291594
ms.contentlocale: fi-fi
ms.lasthandoff: 07/19/2017

---
    
# <a name="specify-printer-selection-for-reports"></a><span data-ttu-id="660b2-102">Tulostimen valinnan määrittäminen raporteille</span><span class="sxs-lookup"><span data-stu-id="660b2-102">Specify Printer Selection for Reports</span></span>
<span data-ttu-id="660b2-103">Voit määrittää raportit niin, että ne täytyy tulostaa tietyssä tulostimessa.</span><span class="sxs-lookup"><span data-stu-id="660b2-103">You can set up reports so that they must be printed on a specific printer.</span></span> <span data-ttu-id="660b2-104">Seuraavat ovat joitain tulostimen valinnen käyttötapauksia:</span><span class="sxs-lookup"><span data-stu-id="660b2-104">The following are some uses of printer selection:</span></span> 

- <span data-ttu-id="660b2-105">Voit tulostaa raportteja erityisissä julkaisuissa.</span><span class="sxs-lookup"><span data-stu-id="660b2-105">You can print reports on special company letterhead.</span></span>
- <span data-ttu-id="660b2-106">Voit tulostaa raportteja eri paperikoissa.</span><span class="sxs-lookup"><span data-stu-id="660b2-106">You can print reports on different paper sizes.</span></span>
- <span data-ttu-id="660b2-107">Voit tulostaa raportteja tietyn työntekijän oletustulostimen.</span><span class="sxs-lookup"><span data-stu-id="660b2-107">You can print reports on the default printer of a specified employee.</span></span>

<span data-ttu-id="660b2-108">Määritä **Tulostimen valinnat** -ikkunassa eri arvot eri tulosteiden saamista varten.</span><span class="sxs-lookup"><span data-stu-id="660b2-108">You use the **Printer Selections** window to set different values to obtain different output.</span></span> <span data-ttu-id="660b2-109">Jos määrität tulostinvalinnan, valinta ohittaa yleisemmän tulostinvalinnan.</span><span class="sxs-lookup"><span data-stu-id="660b2-109">If you set a specific printer selection, then it takes precedence over a more general printer selection.</span></span> <span data-ttu-id="660b2-110">Voit esimerkiksi määrittää tulostimen valinnan, jolla on arvot **Käyttäjätunnus**-, **Raportin tunnus**- ja **Tulostimen nimi** -kentässä.</span><span class="sxs-lookup"><span data-stu-id="660b2-110">For example, you can set a printer selection that has values in the **User ID**, **Report ID**, and **Printer Name** fields.</span></span> <span data-ttu-id="660b2-111">Tämän tulostimen valinta ohittaa tulostimen valinnan, jossa **Käyttäjätunnus**- tai**Raportin tunnus**-kentät ovat tyhjiä.</span><span class="sxs-lookup"><span data-stu-id="660b2-111">This printer selection takes precedence over a printer selection that has blank entries in the **User ID** or **Report ID** fields.</span></span> 

<span data-ttu-id="660b2-112">Seuraavassa taulukossa on kuvattu arvoyhdistelmät, jotka määritetään raportin tulostinvalinnassa.</span><span class="sxs-lookup"><span data-stu-id="660b2-112">The following table describes the combination of values to specify when you set up printer selections for a report.</span></span>

|<span data-ttu-id="660b2-113">Tehtävä</span><span class="sxs-lookup"><span data-stu-id="660b2-113">To</span></span>                                                 |<span data-ttu-id="660b2-114">Määritä seuraavat arvot</span><span class="sxs-lookup"><span data-stu-id="660b2-114">Set the following values</span></span>                                             |
|---------------------------------------------------|---------------------------------------------------------------------|
|<span data-ttu-id="660b2-115">Tulosta raportti tiettyyn tulostimeen kaikkia käytäjiä varten.</span><span class="sxs-lookup"><span data-stu-id="660b2-115">Print a report to a specific printer for all users</span></span> |<span data-ttu-id="660b2-116">Määritä arvot **Tunnus** ja **Tulostimen nimi** -kenttiin ja jätä **Käyttäjätunnus**-kenttä tyhjäksi.</span><span class="sxs-lookup"><span data-stu-id="660b2-116">Specify values in the **Report ID** and **Printer Name** fields and leave the **User ID** field blank.</span></span>|
|<span data-ttu-id="660b2-117">Tulosta kaikki raportit tiettyyn tulostimeen tietylle käyttäjälle</span><span class="sxs-lookup"><span data-stu-id="660b2-117">Print all reports to a specific printer for a specific user</span></span>|<span data-ttu-id="660b2-118">Määritä arvot **Käyttäjätunnus** ja **Tulostimen nimi** -kenttiin ja jätä **Tunnus**-kenttä tyhjäksi.</span><span class="sxs-lookup"><span data-stu-id="660b2-118">Specify values in the **User ID** and **Printer Name** fields and leave the **Report ID** field blank.</span></span>|
|<span data-ttu-id="660b2-119">Määritä oletustulostin kaikkiin raportteihin</span><span class="sxs-lookup"><span data-stu-id="660b2-119">Set the default printer for all reports</span></span>|<span data-ttu-id="660b2-120">Määritä arvo **Tulostimen nimi** -kenttään ja jätä **Käyttäjätunnus** ja **Tunnus** -kentät tyhjiksi.</span><span class="sxs-lookup"><span data-stu-id="660b2-120">Specify a value in the **Printer Name** field and leave the **User ID** and **Report ID** fields blank.</span></span>|
|<span data-ttu-id="660b2-121">Tulosta tietty raportti käyttäjän oletustulostimeen</span><span class="sxs-lookup"><span data-stu-id="660b2-121">Print a specific report to the user’s default printer</span></span>|<span data-ttu-id="660b2-122">Määritä arvo **Tunnus** -kenttään ja jätä **Tulostimen nimi** ja **Käyttäjätunnus** -kentät tyhjiksi.</span><span class="sxs-lookup"><span data-stu-id="660b2-122">Specify a value in the **Report ID** field and leave the **Printer Name** and **User ID** fields blank.</span></span>|
|<span data-ttu-id="660b2-123">Tulosta tietty raportti tiettyyn tulostimeen tietylle käyttäjälle</span><span class="sxs-lookup"><span data-stu-id="660b2-123">Print a specific report to a specific printer for a specific user</span></span>|<span data-ttu-id="660b2-124">Määritä arvot kaikkiin kolmeen kenttään.</span><span class="sxs-lookup"><span data-stu-id="660b2-124">Specify values in all three fields.</span></span>|

## <a name="see-also"></a><span data-ttu-id="660b2-125">Katso myös</span><span class="sxs-lookup"><span data-stu-id="660b2-125">See Also</span></span>
[<span data-ttu-id="660b2-126">Dynamics NAV -ohjelman käyttäminen</span><span class="sxs-lookup"><span data-stu-id="660b2-126">Work with Dynamics NAV</span></span>](ui-work-product.md)

