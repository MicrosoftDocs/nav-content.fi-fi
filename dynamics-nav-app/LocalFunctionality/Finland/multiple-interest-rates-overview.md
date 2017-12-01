---
title: Useiden korkoprosenttien yleiskuvaus
description: "Voit määrittää jokaiselle viivästyskuluehdolle useita korkoprosentteja. Näin voit laskea viivästyskulut useilla eri korkoprosenteilla tietylle jaksolle."
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
ms.openlocfilehash: 462b91b8871183d0b2ce09c508894d2e084f7906
ms.contentlocale: fi-fi
ms.lasthandoff: 12/01/2017

---
# <a name="multiple-interest-rates-overview"></a><span data-ttu-id="98793-103">Useiden korkoprosenttien yleiskuvaus</span><span class="sxs-lookup"><span data-stu-id="98793-103">Multiple Interest Rates Overview</span></span>
<span data-ttu-id="98793-104">Voit määrittää jokaiselle viivästyskuluehdolle useita korkoprosentteja. Näin voit laskea viivästyskulut useilla eri korkoprosenteilla tietylle jaksolle.</span><span class="sxs-lookup"><span data-stu-id="98793-104">For each finance charge term code, you can specify multiple interest rates so that you can calculate finance charges with multiple interest rates for a specific period.</span></span> <span data-ttu-id="98793-105">Tästä on hyötyä, jos laskutat myöhästyneistä maksuista eri koron.</span><span class="sxs-lookup"><span data-stu-id="98793-105">This is helpful if you charge different interest on payments that are late.</span></span> <span data-ttu-id="98793-106">Koron laskeminen on samanlaista kaikille viivästyskuluille. Ainoa ero on tietyn jakson korkoprosentti.</span><span class="sxs-lookup"><span data-stu-id="98793-106">The interest calculation is the same for each financial charge, with variation only in the rate of interest for a specific period.</span></span>  

## <a name="creating-finance-charges"></a><span data-ttu-id="98793-107">Viivästyskulujen luominen</span><span class="sxs-lookup"><span data-stu-id="98793-107">Creating Finance Charges</span></span>  
<span data-ttu-id="98793-108">Kun viivästyskululasku luodaan, laskuriveillä näkyvät viivästyskulut ja eri korkoprosentit kullekin ajanjaksolle.</span><span class="sxs-lookup"><span data-stu-id="98793-108">When you create a finance charge memo, the memo lines show the finance charges with different interest rates for each time period.</span></span> <span data-ttu-id="98793-109">Voit määrittää viivästyskuluehdoissa kunkin ehdon kuvauksen. Voit myös määrittää kuvauksen, jota käytetään tilanteessa, jossa käytössä on useita korkoprosentteja.</span><span class="sxs-lookup"><span data-stu-id="98793-109">For finance charge terms, you can define descriptions for each term, and you can define a description that is used when multiple interest rates are used.</span></span>  

<span data-ttu-id="98793-110">Voit käyttää useita korkoprosentteja, kun ensin määritätä viivästyskuluehdon. Lisää sitten ehtoihin useita korkoprosenttirivejä.</span><span class="sxs-lookup"><span data-stu-id="98793-110">To use multiple interest rates, you must first define a finance charge term, and you must then add multiple interest rate lines to the terms.</span></span> <span data-ttu-id="98793-111">Lisätietoja on kohdassa [Toimintaohje: Useiden korkoprosenttien määrittäminen](how-to-set-up-multiple-interest-rates.md).</span><span class="sxs-lookup"><span data-stu-id="98793-111">For more information, see [How to: Set Up Multiple Interest Rates](how-to-set-up-multiple-interest-rates.md).</span></span>  

<span data-ttu-id="98793-112">Jos useita korkoprosentteja ei ole, [!INCLUDE[navnow](../../includes/navnow_md.md)] käyttää **Viivästyskuluehdot**-ikkunassa määritettyä korkoprosenttia ja jaksoa kokolaskentakaudelle.</span><span class="sxs-lookup"><span data-stu-id="98793-112">If no multiple interest rates exist, [!INCLUDE[navnow](../../includes/navnow_md.md)] will use the interest rate and period that is defined in the **Finance Charge Terms** window for the whole period of calculation.</span></span>  

## <a name="delayed-payments"></a><span data-ttu-id="98793-113">Viivästyneet maksut</span><span class="sxs-lookup"><span data-stu-id="98793-113">Delayed Payments</span></span>  
<span data-ttu-id="98793-114">Useita korkoprosentteja käytetään kauppatapahtumien viivästyneissä maksuissa eri jaksoilla.</span><span class="sxs-lookup"><span data-stu-id="98793-114">Multiple interest rates are used for different periods for delayed payments in trade transactions.</span></span> <span data-ttu-id="98793-115">Esimerkiksi valtio määrittää asiakkaalta perittävän enimmäiskoron.</span><span class="sxs-lookup"><span data-stu-id="98793-115">For example, a government specifies the maximum interest to be levied for a consumer.</span></span> <span data-ttu-id="98793-116">Tätä korkoprosenttia voidaan muuttaa kahdesti vuoden aikana. Ajankohdat ovat 1.1. ja 1.7.</span><span class="sxs-lookup"><span data-stu-id="98793-116">This interest rate can be changed twice a year on 01 January and 01 July.</span></span> <span data-ttu-id="98793-117">Yritysten välinen (B2B) korkoprosentti sovitaan osapuolten kesken. Tämän asiakasryhmän korkoprosentille ei ole määritetty enimmäistasoa.</span><span class="sxs-lookup"><span data-stu-id="98793-117">The interest rate between businesses (B2B) is agreed by the parties and there is no limit to that customer group.</span></span> <span data-ttu-id="98793-118">Ilmoitettu korkoprosentti on yleensä neljä prosenttia enemmän kuin pankin normaali korko.</span><span class="sxs-lookup"><span data-stu-id="98793-118">The announced rate is usually four percent more than the normal bank interest.</span></span>  

## <a name="see-also"></a><span data-ttu-id="98793-119">Katso myös</span><span class="sxs-lookup"><span data-stu-id="98793-119">See Also</span></span>  
<span data-ttu-id="98793-120">[Toimintaohje: Useiden korkoprosenttien määrittäminen](how-to-set-up-multiple-interest-rates.md) </span><span class="sxs-lookup"><span data-stu-id="98793-120">[How to: Set Up Multiple Interest Rates](how-to-set-up-multiple-interest-rates.md) </span></span>  
[<span data-ttu-id="98793-121">Toimintaohje: Avointen saldojen perintä</span><span class="sxs-lookup"><span data-stu-id="98793-121">How to: Collect Outstanding Balances</span></span>](../../receivables-collect-outstanding-balances.md)

