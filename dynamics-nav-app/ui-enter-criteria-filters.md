---
title: "Ehtojen syöttäminen suodattimiin"
author: SusanneWindfeldPedersen
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 8eab393a0a77f9f1595ca1247c7549e68b491cb2
ms.contentlocale: fi-fi
ms.lasthandoff: 06/26/2017

---

# <a name="entering-criteria-in-filters"></a>Ehtojen syöttäminen suodattimiin
Syötä ehtoja, kun haluat etsiä tiettyjä tietoja, kuten asiakkaiden nimiä, osoitteita tai tuoteryhmiä. Hakuehdoissa voi käyttää kaikkia numeroita ja kirjaimia, joita kentissä yleensä käytetään. Lisäksi voit käyttää tulosten suodatukseen erikoismerkkejä.

## <a name="searching-using-the-quick-filter"></a>Haku pikasuodattimen avulla
Pikasuodattimen avulla voit lisätä suodattimia kaikille sivuille. Pikasuodatin otetaan käyttöön valitsemalla sivun oikeassa yläkulmassa oleva suurennuslasikuvake. Tätä suodatustyyppiä käytetään ehtojen nopeassa syöttämisessä.

**Tärkeää**: Pikasuodatin tarjoaa helpon pääsyn tietojen suodatukseen kirjaamalla pelkkä teksti, mutta ei tarjoa paljoa hakuehtovaihtoehtoja. Pikasuodatin toimii eri tavalla riippuen siitä, kirjoitatko tekstiä tai tekstiä symboleilla.  
- Jos kirjoitat hakuehtoon pelkän tekstin, hakuehto tulkitaan hauksi, joka ei huomioi kirjainkokoa ja joka sisältää tietyn tekstin.  
- Jos kirjoitat hakuehtoon tekstiä, joka sisältää symboleja, hakuehto tulkitaan juuri siten kuin kirjoitit sen ja haun kirjainkoko on merkitsevä.

### <a name="quick-filter-criteria"></a>Pikasuodattimen ehdot
<!-- html syntax because symbols conflict with MarkDown syntax -->
<TABLE>
  <TR>
    <TH>Hakuehdot</TH>
    <TH>Tulkinta...</TH>
    <TH>Palautukset...</TH>
  </TR>
  <TR>
    <TD>>man</TD>
    <TD>@*man*</TD>
    <TD>Kaikki tietueet, jotka sisältävät tekstin mies ja kirjainkokoa huomioimatta.</TD>
  </TR>
  <TR>
    <TD>>se</TD>
    <TD>@*se*</TD>
    <TD>Kaikki tietueet, jotka sisältävät tekstin se ja kirjainkokoa huomioimatta.</TD>
  </TR>
  <TR>
    <TD>>Man*</TD>
    <TD>Alkaa "Man" ja kirjainkoolla on merkitystä.</TD>
    <TD>Kaikki tietueet, jotka alkavat tekstillä Mies.</TD>
  </TR>
  <TR>
    <TD>'man'</TD>
    <TD>Täsmällinen teksti ja kirjainkoolla on merkitystä.</TD>
    <TD>Kaikki tietueet, jotka vastaavat täsmälleen tekstiä mies.</TD>
  </TR>
  <TR>
    <TD>@*man</TD>
    <TD>Päättyy ja kirjainkoolla ei ole merkitystä.</TD>
    <TD>Kaikki tietueet, jotka päättyvät tekstiin mies.</TD>
  </TR>
  <TR>
    <TD>@man*</TD>
    <TD>Alkaa ja kirjainkoolla ei ole merkitystä.</TD>
    <TD>Kaikki tietueet, jotka alkavat tekstillä mies.</TD>
  </TR>
</TABLE>

**Huomautus**: Ei voi käyttää yleismerkkejä suodattaessasi luettelointikenttiä. Tällainen kenttä on esimerkiksi myyntitilausten **Tila**-kenttä. Voit syöttää suodattimen tämäntyyppiselle kentälle kirjoittamalla numeerisen arvon suodatusparametriksi. Esimerkiksi **Tila**-kenttä myyntitilauksessa, jolla on arvot **Avoin**, **vapautettu**,**Odottaa hyväksyntää** ja **Odottaa ennakkomaksua**, suodata nämä asetukset käyttämällä arvoja **0**,**1**,**2** ja **3**.  

## <a name="see-also"></a>Katso myös
[Dynamics NAV -ohjelman käyttäminen](ui-work-product.md)

