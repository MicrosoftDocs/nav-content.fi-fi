---
title: "Ehtojen syöttäminen suodattimiin"
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
ms.openlocfilehash: df386e1195db385ee053b69fec0f5082d8df4116
ms.contentlocale: fi-fi
ms.lasthandoff: 07/19/2017

---

# <a name="entering-criteria-in-filters"></a><span data-ttu-id="99ea1-102">Ehtojen syöttäminen suodattimiin</span><span class="sxs-lookup"><span data-stu-id="99ea1-102">Entering Criteria in Filters</span></span>
<span data-ttu-id="99ea1-103">Syötä ehtoja, kun haluat etsiä tiettyjä tietoja, kuten asiakkaiden nimiä, osoitteita tai tuoteryhmiä.</span><span class="sxs-lookup"><span data-stu-id="99ea1-103">When you want to search for data, such as customer names, addresses, or product groups, you enter criteria.</span></span> <span data-ttu-id="99ea1-104">Hakuehdoissa voi käyttää kaikkia numeroita ja kirjaimia, joita kentissä yleensä käytetään.</span><span class="sxs-lookup"><span data-stu-id="99ea1-104">In search criteria you can use all the numbers and letters that you normally use in the specific field.</span></span> <span data-ttu-id="99ea1-105">Lisäksi voit käyttää tulosten suodatukseen erikoismerkkejä.</span><span class="sxs-lookup"><span data-stu-id="99ea1-105">In addition, you can use special symbols to further filter the results.</span></span>

## <a name="searching-using-the-quick-filter"></a><span data-ttu-id="99ea1-106">Haku pikasuodattimen avulla</span><span class="sxs-lookup"><span data-stu-id="99ea1-106">Searching using the Quick Filter</span></span>
<span data-ttu-id="99ea1-107">Pikasuodattimen avulla voit lisätä suodattimia kaikille sivuille.</span><span class="sxs-lookup"><span data-stu-id="99ea1-107">You can add filters to all pages by using the Quick Filter.</span></span> <span data-ttu-id="99ea1-108">Pikasuodatin otetaan käyttöön valitsemalla sivun oikeassa yläkulmassa oleva suurennuslasikuvake.</span><span class="sxs-lookup"><span data-stu-id="99ea1-108">The Quick Filter is enabled by choosing the magnifier icon in the top right corner of a page.</span></span> <span data-ttu-id="99ea1-109">Tätä suodatustyyppiä käytetään ehtojen nopeassa syöttämisessä.</span><span class="sxs-lookup"><span data-stu-id="99ea1-109">This filtering type is used for a fast entry of criteria.</span></span>

<span data-ttu-id="99ea1-110">**Tärkeää**: Pikasuodatin tarjoaa helpon pääsyn tietojen suodatukseen kirjaamalla pelkkä teksti, mutta ei tarjoa paljoa hakuehtovaihtoehtoja.</span><span class="sxs-lookup"><span data-stu-id="99ea1-110">**Important**: The Quick Filter provides an easy access to filter data by entering plain text, but does also provide a lot of search criteria options.</span></span> <span data-ttu-id="99ea1-111">Pikasuodatin toimii eri tavalla riippuen siitä, kirjoitatko tekstiä tai tekstiä symboleilla.</span><span class="sxs-lookup"><span data-stu-id="99ea1-111">Depending on whether you enter plain text or text including symbols, the Quick Filter behaves differently.</span></span>  
- <span data-ttu-id="99ea1-112">Jos kirjoitat hakuehtoon pelkän tekstin, hakuehto tulkitaan hauksi, joka ei huomioi kirjainkokoa ja joka sisältää tietyn tekstin.</span><span class="sxs-lookup"><span data-stu-id="99ea1-112">If you enter plain text in the search criteria, the search criteria is interpreted as a case insensitive search that contains certain text.</span></span>  
- <span data-ttu-id="99ea1-113">Jos kirjoitat hakuehtoon tekstiä, joka sisältää symboleja, hakuehto tulkitaan juuri siten kuin kirjoitit sen ja haun kirjainkoko on merkitsevä.</span><span class="sxs-lookup"><span data-stu-id="99ea1-113">If you enter text including symbols in the search criteria, the search criteria is interpreted exactly as you entered it, and the search is case sensitive.</span></span>

### <a name="quick-filter-criteria"></a><span data-ttu-id="99ea1-114">Pikasuodattimen ehdot</span><span class="sxs-lookup"><span data-stu-id="99ea1-114">Quick filter criteria</span></span>
<!-- html syntax because symbols conflict with MarkDown syntax -->
<TABLE>
  <TR>
    <TH><span data-ttu-id="99ea1-115">Hakuehdot</span><span class="sxs-lookup"><span data-stu-id="99ea1-115">Search Criteria</span></span></TH>
    <TH><span data-ttu-id="99ea1-116">Tulkinta...</span><span class="sxs-lookup"><span data-stu-id="99ea1-116">Interpreted as...</span></span></TH>
    <TH><span data-ttu-id="99ea1-117">Palautukset...</span><span class="sxs-lookup"><span data-stu-id="99ea1-117">Returns...</span></span></TH>
  </TR>
  <TR>
    <TD><span data-ttu-id="99ea1-118">>man</span><span class="sxs-lookup"><span data-stu-id="99ea1-118">>man</span></span></TD>
    <TD><span data-ttu-id="99ea1-119">@*man*</span><span class="sxs-lookup"><span data-stu-id="99ea1-119">@*man*</span></span></TD>
    <TD><span data-ttu-id="99ea1-120">Kaikki tietueet, jotka sisältävät tekstin mies ja kirjainkokoa huomioimatta.</span><span class="sxs-lookup"><span data-stu-id="99ea1-120">All records that contain the text man and case insensitive.</span></span></TD>
  </TR>
  <TR>
    <TD><span data-ttu-id="99ea1-121">>se</span><span class="sxs-lookup"><span data-stu-id="99ea1-121">>se</span></span></TD>
    <TD><span data-ttu-id="99ea1-122">@*se*</span><span class="sxs-lookup"><span data-stu-id="99ea1-122">@*se*</span></span></TD>
    <TD><span data-ttu-id="99ea1-123">Kaikki tietueet, jotka sisältävät tekstin se ja kirjainkokoa huomioimatta.</span><span class="sxs-lookup"><span data-stu-id="99ea1-123">All records that contain the text se and case insensitive.</span></span></TD>
  </TR>
  <TR>
    <TD><span data-ttu-id="99ea1-124">>Man*</span><span class="sxs-lookup"><span data-stu-id="99ea1-124">>Man*</span></span></TD>
    <TD><span data-ttu-id="99ea1-125">Alkaa "Man" ja kirjainkoolla on merkitystä.</span><span class="sxs-lookup"><span data-stu-id="99ea1-125">Starts with Man and case sensitive.</span></span></TD>
    <TD><span data-ttu-id="99ea1-126">Kaikki tietueet, jotka alkavat tekstillä Mies.</span><span class="sxs-lookup"><span data-stu-id="99ea1-126">All records that start with the text Man.</span></span></TD>
  </TR>
  <TR>
    <TD><span data-ttu-id="99ea1-127">'man'</span><span class="sxs-lookup"><span data-stu-id="99ea1-127">'man'</span></span></TD>
    <TD><span data-ttu-id="99ea1-128">Täsmällinen teksti ja kirjainkoolla on merkitystä.</span><span class="sxs-lookup"><span data-stu-id="99ea1-128">An exact text and case sensitive.</span></span></TD>
    <TD><span data-ttu-id="99ea1-129">Kaikki tietueet, jotka vastaavat täsmälleen tekstiä mies.</span><span class="sxs-lookup"><span data-stu-id="99ea1-129">All records that match man exactly.</span></span></TD>
  </TR>
  <TR>
    <TD><span data-ttu-id="99ea1-130">@*man</span><span class="sxs-lookup"><span data-stu-id="99ea1-130">@*man</span></span></TD>
    <TD><span data-ttu-id="99ea1-131">Päättyy ja kirjainkoolla ei ole merkitystä.</span><span class="sxs-lookup"><span data-stu-id="99ea1-131">Ends with and case insensitive.</span></span></TD>
    <TD><span data-ttu-id="99ea1-132">Kaikki tietueet, jotka päättyvät tekstiin mies.</span><span class="sxs-lookup"><span data-stu-id="99ea1-132">All records that end with man.</span></span></TD>
  </TR>
  <TR>
    <TD><span data-ttu-id="99ea1-133">@man*</span><span class="sxs-lookup"><span data-stu-id="99ea1-133">@man*</span></span></TD>
    <TD><span data-ttu-id="99ea1-134">Alkaa ja kirjainkoolla ei ole merkitystä.</span><span class="sxs-lookup"><span data-stu-id="99ea1-134">Starts with and case insensitive.</span></span></TD>
    <TD><span data-ttu-id="99ea1-135">Kaikki tietueet, jotka alkavat tekstillä mies.</span><span class="sxs-lookup"><span data-stu-id="99ea1-135">All records that start with man.</span></span></TD>
  </TR>
</TABLE>

<span data-ttu-id="99ea1-136">**Huomautus**: Ei voi käyttää yleismerkkejä suodattaessasi luettelointikenttiä. Tällainen kenttä on esimerkiksi myyntitilausten **Tila**-kenttä.</span><span class="sxs-lookup"><span data-stu-id="99ea1-136">**Note**: You cannot use a wildcard when filtering on enumeration fields, such as the **Status** field on sales orders.</span></span> <span data-ttu-id="99ea1-137">Voit syöttää suodattimen tämäntyyppiselle kentälle kirjoittamalla numeerisen arvon suodatusparametriksi.</span><span class="sxs-lookup"><span data-stu-id="99ea1-137">To enter a filter for this type of field, you can enter the numeric value as a filtering parameter.</span></span> <span data-ttu-id="99ea1-138">Esimerkiksi **Tila**-kenttä myyntitilauksessa, jolla on arvot **Avoin**, **vapautettu**,**Odottaa hyväksyntää** ja **Odottaa ennakkomaksua**, suodata nämä asetukset käyttämällä arvoja **0**,**1**,**2** ja **3**.</span><span class="sxs-lookup"><span data-stu-id="99ea1-138">For example, in the **Status** field on a sales order that has the values **Open**, **Released**, **Pending Approval**, and **Pending Prepayment**, use the values **0**, **1**, **2**, and **3** to filter for these options.</span></span>  

## <a name="see-also"></a><span data-ttu-id="99ea1-139">Katso myös</span><span class="sxs-lookup"><span data-stu-id="99ea1-139">See Also</span></span>
[<span data-ttu-id="99ea1-140">Dynamics NAV -ohjelman käyttäminen</span><span class="sxs-lookup"><span data-stu-id="99ea1-140">Work with Dynamics NAV</span></span>](ui-work-product.md)

