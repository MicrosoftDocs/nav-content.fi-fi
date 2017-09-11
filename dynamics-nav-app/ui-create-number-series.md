---
title: Numerosarjojen luominen
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
ms.openlocfilehash: e42e5ed139b2487fea13ef0fd57757035764addd
ms.contentlocale: fi-fi
ms.lasthandoff: 07/19/2017

---

# <a name="create-number-series"></a><span data-ttu-id="fd579-102">Numerosarjojen luominen</span><span class="sxs-lookup"><span data-stu-id="fd579-102">Create Number Series</span></span>

<span data-ttu-id="fd579-103">Jokaiselle yritykselle on määritettävä ainutkertaiset tunnuskoodit esimerkiksi pääkirjanpidon tilejä, asiakas- ja toimittajatilejä, laskuja ja asiakirjoja varten.</span><span class="sxs-lookup"><span data-stu-id="fd579-103">For each company that you set up, you need to assign unique identification codes to things such as general ledger accounts, customer and vendor accounts, invoices, and documents.</span></span> <span data-ttu-id="fd579-104">Numerointi ei ole tärkeää pelkästään tunnistamisen kannalta.</span><span class="sxs-lookup"><span data-stu-id="fd579-104">Numbering is important not only for identification.</span></span> <span data-ttu-id="fd579-105">Hyvin suunniteltu numerointijärjestelmä helpottaa myös yrityksen hallittavuutta ja analysointia ja voi vähentää tietojen syötössä tapahtuvien virheiden määrää.</span><span class="sxs-lookup"><span data-stu-id="fd579-105">A well-designed numbering system also makes the company more manageable and easy to analyze, and can reduce the number of errors that occur in data entry.</span></span>

<span data-ttu-id="fd579-106">Voit määrittää täydellisen numerointijärjestelmän, jossa on rajoittamaton määrä numerosarjoja.</span><span class="sxs-lookup"><span data-stu-id="fd579-106">You can set up a complete numbering system with an unlimited number of number series.</span></span> <span data-ttu-id="fd579-107">Numerosarjoja voi käyttää kaikentyyppisille asiakirjoille ja päiväkirjoille sekä perustiedoille, kuten asiakkaille, nimikkeille ja projekteille.</span><span class="sxs-lookup"><span data-stu-id="fd579-107">You can use number series for all types of documents and journals, as well as for master data such as customers, items, and jobs.</span></span>

<span data-ttu-id="fd579-108">Voit yhdistää numerosarjojen käytön manuaaliseen numerointiin.</span><span class="sxs-lookup"><span data-stu-id="fd579-108">You can combine the use of number series with manual numbering.</span></span>

<span data-ttu-id="fd579-109">Numerointijärjestelmä luodaan määrittämällä koodeja kullekin perustietotyypille tai asiakirjalle.</span><span class="sxs-lookup"><span data-stu-id="fd579-109">You create a numbering system by setting up one or more codes for each type of master data or document.</span></span> <span data-ttu-id="fd579-110">Voit määrittää koodin esimerkiksi asiakkaiden, myyntilaskujen ja yleisten päiväkirjojen numerointia varten.</span><span class="sxs-lookup"><span data-stu-id="fd579-110">For example, you can set up one code for numbering customers, another code for numbering sales invoices, and another code for numbering documents in general journals.</span></span>

<span data-ttu-id="fd579-111">Kun olet määrittänyt koodin, sinun on määritettävä vähintään yksi numerosarjarivi.</span><span class="sxs-lookup"><span data-stu-id="fd579-111">After you have set up a code, you set must set up at least one number series line.</span></span> <span data-ttu-id="fd579-112">Numerosarjarivit sisältävät erilaisia tietoja, kuten sarjan ensimmäisen ja viimeisen numeron sekä alkupäivämäärän.</span><span class="sxs-lookup"><span data-stu-id="fd579-112">The number series line contains information such as the first and last number in the series and the starting date.</span></span> <span data-ttu-id="fd579-113">Voit määrittää yhtä numerosarjakoodia kohti useita numerosarjarivejä, joilla kullakin on eri alkupäivämäärä.</span><span class="sxs-lookup"><span data-stu-id="fd579-113">You can set up more than one number series line per number series code, with a different starting date for each line.</span></span> <span data-ttu-id="fd579-114">Numerosarjoja käytetään peräkkäin kulloisestakin alkupäivämäärästä alkaen.</span><span class="sxs-lookup"><span data-stu-id="fd579-114">The series will be used consecutively, starting each series on the respective starting date.</span></span>

<span data-ttu-id="fd579-115">Jos haluat käyttää useita numerosarjakoodeja yhdelle perustietotyypille (esimerkiksi silloin, kun haluat eri numerosarjoja eri nimikeluokille), voit käyttää numerosarjasuhteita.</span><span class="sxs-lookup"><span data-stu-id="fd579-115">If you want to use more than one number series code for one type of master data - for example, if you want to use different number series for different categories of items - you can use number series relationships.</span></span>

<span data-ttu-id="fd579-116">Manuaalisesti tai numerointijärjestelmän avulla määrittämiesi numeroiden lisäksi kaikille tapahtumille määritetään automaattisesti peräkkäiset numerot.</span><span class="sxs-lookup"><span data-stu-id="fd579-116">In addition to the numbers that you assign manually or by use of the numbering system, all transactions (ledger entries) are automatically assigned consecutive numbers.</span></span> <span data-ttu-id="fd579-117">Nämä luvut voidaan nähdä **Tapahtumanro.**-kentässä</span><span class="sxs-lookup"><span data-stu-id="fd579-117">These numbers can be seen in the **Entry No.**</span></span> <span data-ttu-id="fd579-118">kaikissa tapahtumaikkunoissa.</span><span class="sxs-lookup"><span data-stu-id="fd579-118">field in all the ledger entry windows.</span></span> <span data-ttu-id="fd579-119">Tapahtumanumeroita ei voi muokata tai poistaa.</span><span class="sxs-lookup"><span data-stu-id="fd579-119">You cannot modify or delete these numbers.</span></span>

## <a name="to-create-relationships-between-number-series"></a><span data-ttu-id="fd579-120">Numerosarjojen suhteiden luonti</span><span class="sxs-lookup"><span data-stu-id="fd579-120">To create relationships between number series</span></span>
<span data-ttu-id="fd579-121">Jos tietylle perustiedolle tai tapahtumalle on luotu useampia numerosarjoja, näiden koodien välille voidaan luoda suhteita.</span><span class="sxs-lookup"><span data-stu-id="fd579-121">If you have set up more than one number series code for the same kind of basic information or transactions, you can create relationships between the codes.</span></span> <span data-ttu-id="fd579-122">Tämä toiminto auttaa koodien valinnassa kun käytetään numeroa.</span><span class="sxs-lookup"><span data-stu-id="fd579-122">This feature can assist you in deciding among the codes when you use a number.</span></span>

1. <span data-ttu-id="fd579-123">Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Nrosarja** ja valitse sitten aiheeseen liittyvä linkki.</span><span class="sxs-lookup"><span data-stu-id="fd579-123">In the top right corner, choose the **Search for Page or Report** icon, enter **No. Series**, and then choose the related link.</span></span>
2. <span data-ttu-id="fd579-124">Valitse numerosarjoja sisältävä rivi, jolle haluat luoda suhteita. Valitse sitten **Suhteet**.</span><span class="sxs-lookup"><span data-stu-id="fd579-124">Select the line with the number series you want to create relationships for and then choose **Relationships**.</span></span>
3. <span data-ttu-id="fd579-125">Kirjoita **Sarjakoodi**-kenttään sen numerosarjan koodi, johon haluat luoda suhteen vaiheessa 2 valitusta sarjasta.</span><span class="sxs-lookup"><span data-stu-id="fd579-125">In the **Series Code** field, enter the code for the number series that you want to relate to the series you selected in step 2.</span></span>
4. <span data-ttu-id="fd579-126">Lisää rivi kullekin valittuun numerosarjaan liitettävälle koodille.</span><span class="sxs-lookup"><span data-stu-id="fd579-126">Add a line for each code that you want to relate to the selected number series.</span></span>
5. <span data-ttu-id="fd579-127">Sulje ikkuna.</span><span class="sxs-lookup"><span data-stu-id="fd579-127">Close the window.</span></span>

<span data-ttu-id="fd579-128">Kun tarvitset numeron voit käyttää niitä suhteita, joita on luotu numerosarjojen valitsemiseksi.</span><span class="sxs-lookup"><span data-stu-id="fd579-128">Now when you set up something that requires a number, you can use the relationships you created to select among the related number series.</span></span>

## <a name="see-also"></a><span data-ttu-id="fd579-129">Katso myös</span><span class="sxs-lookup"><span data-stu-id="fd579-129">See Also</span></span>
[<span data-ttu-id="fd579-130">Dynamics NAV -ohjelman käyttäminen</span><span class="sxs-lookup"><span data-stu-id="fd579-130">Work with Dynamics NAV</span></span>](ui-work-product.md)

