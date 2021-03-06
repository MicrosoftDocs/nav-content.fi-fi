---
title: Kokoonpanon hallinta
description: "Tue yrityksiä, jotka toimittavat asiakkailleen tuotteita yhdistämällä osia yksinkertaisilla prosesseilla ilman tuotantotoimintojen tarvetta mutta jonka ominaisuuksilla voi koota aiemmin luotuja ominaisuuksia, kuten myynti, suunnittelu, varaukset ja varastointi, integroivia nimikkeitä."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 09/26/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 4e0490e63268edd68a22e61b25311aa133c507c1
ms.contentlocale: fi-fi
ms.lasthandoff: 10/16/2017

---
# <a name="assembly-management"></a>Kokoonpanon hallinta
Tukeakseen yrityksiä, jotka toimittavat asiakkailleen tuotteita yhdistämällä osia yksinkertaisissa prosesseissa ilman tuotantotoimintojen tarvetta, [!INCLUDE[d365fin](includes/d365fin_md.md)] sisältää ominaisuuksia, jotka kokoavat nimikkeitä, joissa on olemassa olevia ominaisuuksia, kuten myynti, suunnittelu, varaukset, ja varastointi.  

 Kokoonpanon nimike määritetään myytävänä kohteena, joka sisältää kokoonpanon tuoterakenteen. Lisätietoja on kohdassa [Toimintaohje: Tuoterakenteen käyttäminen](inventory-how-work-BOMs.md).

 Kokoonpanotilaukset ovat sisäisiä tilauksia, aivan kuten tuotantotilaukset, joita käytetään kokoonpanoprosessin hallinnassa sekä myyntivaatimusten liittämiseksi asianmukaisiin varastotoimintoihin. Kokoonpanotilaukset eroavat muista tilaustyypeistä, sillä ne kattavat sekä tuotoksen että kulutuksen, kun ne kirjataan. Kokoonpanotilauksen otsikko toimii samaan tapaan kuin myyntitilausrivi ja kokoonpanotilauksen rivit toimivat samalla tavalla kuin kulutuspäiväkirjan rivit.  

 Just-In-Time -varastostrategian ja kyvyn mukauttaa tuotteet asiakkaan vaatimusten mukaisiksi tukemiseksi kokoonpanotilauksia voidaan automaattisesti luoda ja linkittää heti kun myyntitilausrivi on luotu. Linkki myyntikysynnän ja kokoonpanotarjonnan kokoonpanon välillä mahdollistaa myyntitilauksen käsittelijöille kokoonpano-osan mukauttamisen lennossa, toimituspäivien lupaamisen osan saatavuuden mukaan, ja tuotoksen ja toimituksen kirjaamisen valmiille nimikkeelle suoraan myyntitilausliittymästä. Lisätietoja on kohdassa [Kokoonpano tilausta varten -nimikkeiden myyminen](assembly-how-to-sell-items-assembled-to-order.md).  

 Yhdellä myyntitilauksen rivillä voit myydä määrän, joka on saatavissa ja joka on poimittava varastosta, yhdessä sen määrän kanssa, joka on kokoonpantava tilausta varten. Tietyt säännöt hallinnoivat sellaisten määrien jakelua, jotta varmistetaan, että kokoonpano tilausta varten -määrät ohittavat tärkeysjärjestyksessä varastomäärät osatoimituksissa. Lisätietoja on ohjeaiheen [Tietoja Kokoonpano tilausta varten- tai Kokoonpano varastoon -toiminnoista](assembly-assemble-to-order-or-assemble-to-stock.md) kohdassa Skenaarioiden yhdistelmä.  

 Erityinen toiminto koskee tilausta varten kokoonpantujen määrien toimitusta. Kun kokoonpano tilausta varten -määrä on toimitusvalmis, varastotyöntekijä kirjaa varastopoiminnan myyntitilauksen kyseiselle riville tai riveille. Tämä puolestaan luo varastosiirron osille, kirjaa kokoonpanon tuotoksen ja myyntitilauksen toimituksen. Lisätietoja on ohjeaiheen [Toimintaohje: Nimikkeiden poiminta varaston poiminnoissa](warehouse-how-to-pick-items-with-inventory-picks.md) kohdassa Kokoonpano tilausta varten -nimikkeiden käsitteleminen varaston poiminnoissa.

Seuraavassa taulukossa on tehtäväsarja ja linkit tehtäviä käsitteleviin aiheisiin.   

|**Tehtävä**|**Katso**|  
|------------|-------------|  
|Tutustu siihen, mikä ero on nimikkeiden kokoonpanolla juuri ennen myyntitilausten toimittamista ja nimikkeiden kokoonpanolla varastoitaviksi.|[Tietoja Kokoonpano tilausta varten- ja Kokoonpano varastoon -toiminnoista](assembly-assemble-to-order-or-assemble-to-stock.md)|
|Täytä sijainnin korttien kentät ja määritä varaston asetuksissa, miten nimikkeet liikkuvat kokoonpano-osastossa.|[Fyysisten perusvarastojen ja toimintoalueiden määrittäminen](warehouse-how-to-set-up-basic-warehouses-with-operations-areas.md)|
|Muokkaa kokoonpanon nimike asiakkaan pyynnöstä myyntiprosessin aikana ja muunna se myynniksi hyväksynnän yhteydessä.|[Kokoonpano tilausta varten -myynnin tarjous](assembly-how-to-quote-an-assemble-to-order-sale.md)|
|Yhdistä osat ja luo nimike yksinkertaisessa prosessissa tilaukseen tai varastoon.|[Nimikkeiden kokoaminen](assembly-how-to-assemble-items.md)|  
|Myy kokoonpanon nimikkeet, jotka eivät ole tällä hetkellä saatavilla, luomalla linkitetty kokoonpanotilaus toimittamaan myyntilauksen koko määrä tai sen osa.|[Kokoonpano tilausta varten -nimikkeiden myyminen](assembly-how-to-sell-items-assembled-to-order.md)|
|Kun Kokoonpano tilausta varten -nimikkeet ovat jo varastossa, vähennä määrä kokoonpanotilauksesta ja varaa se varastosta.|[Varastonimikkeiden myyminen kokoonpano tilausta varten -virroissa](assembly-how-to-sell-inventory-items-in-assemble-to-order-flows.md)|  
|Kun myyt kokoonpanon nimikkeitä varastosta ja kaikki kohteet eivät ole saatavilla, toimita myyntitilauksen määrä osittain tai kokonaan käynnistämällä kokoonpanotilaus.|[Kokoonpano tilausta varten -nimikkeiden ja varastonimikkeiden myyminen yhdessä](assembly-how-to-sell-assemble-to-order-items-and-inventory-items-together.md)|
|Kumoa kirjattu kokoonpanotilaus esimerkiksi siksi, että kirjatussa tilauksessa on virheitä, jotka on korjattava.|[Kokoonpanon kirjauksen kumoaminen](assembly-how-to-undo-assembly-posting.md)|
|Tutustu siihen, mikä ero on kokoonpanon tuoterakenteella ja tuotannon tuoterakenteella, sekä niihin liittyviin käsittelyeroihin.|[Toimintaohje: Tuoterakenteen käyttäminen](inventory-how-work-BOMs.md)|
|Tutustu siihen, miten kokoonpanon kulutusta ja tuotosta käsitellään, kun kokoonpanotilauksia kirjataan, ja miten tästä koituvat nimike- ja resurssikustannukset käsitellään ja jaetaan pääkirjanpitoon.|[Rakennetiedot: kokoonpanotilauksen kirjaus](design-details-assembly-order-posting.md)|  

## <a name="see-also"></a>Katso myös  
[Toimintaohje: Tuoterakenteen käyttäminen](inventory-how-work-BOMs.md)  
[Vaihto-omaisuus](inventory-manage-inventory.md)  
[Rakennetiedot: f. varaston hallinta](design-details-warehouse-management.md)  
[[!INCLUDE[d365fin](includes/d365fin_md.md)] -ohjelman käyttäminen](ui-work-product.md)

