---
title: "Parhaiden käytäntöjen määrittäminen - arvostusmenetelmä"
description: "Nimikekortin **arvostusmenetelmä** määrittää nimikkeen kustannusvirran kirjaamisen. Lisäksi se määrittää, siirretäänkö todellinen vai budjetoitu arvo pääomaan ja käytetäänkö sitä kustannuslaskennassa."
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
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: a2c25ffc6c2012bac4e86ebbce0f3c33ecaf68fc
ms.contentlocale: fi-fi
ms.lasthandoff: 10/16/2017

---
# <a name="setup-best-practices-costing-method"></a>Parhaiden käytäntöjen määrittäminen: Arvostusmenetelmä
**Arvostusmenetelmä**-määrittää nimikkeen kortilla, miten nimikkeen kustannusvirta tallennetaan ja siirretäänkö todellinen tai budjetoitu arvo pääomaan ja käytetäänkö sitä kustannuslaskennassa.  

 Oikean kustannusmenetelmän määrittäminen nimikkeen tyypin ja liiketoimintaympäristön mukaan on tärkeää edullisen vaihto-omaisuuden varmistamiseksi.  

 Seuraavassa taulukossa on parhaita käytäntöjä siitä, miten voit määrittää **Arvostusmenetelmä**-kentän. Katso lisätietoja kohdasta [Rakennetiedot: arvostusmenetelmät](design-details-costing-methods.md).  

|Asetusvaihtoehto|Parhaat käytännöt|Kommentti|  
|------------------|-------------------|-------------|  
|FIFO|Käytä, jos tuotteen kustannus on vakaa.<br /><br /> Käytä nimikkeille, joilla on rajoitettu varastointiaika, koska vanhimmat tavarat täytyy myydä ennen kuin niiden viimeinen myyntipäivä ohitetaan.|Nimikkeen yksikkökustannus on FIFO-säännön perusteella valitun nimikkeen vastaanoton todellinen arvo.<br /><br /> Varastonarvostuksessa oletetaan, että ensin varastoon sijoitetut nimikkeet myydään ensin. **Huomautus:**  Kun hinnat nousevat, taseessa näkyy suurempi arvo. Tämä tarkoittaa, että verovelat kasvavat, mutta luottoluokitus ja rahanlainauskyky paranevat.|  
|LIFO|Käytä, jos varastojen tasoja pidetään jatkuvasti yllä tai nostetaan ajan mittaan.|Nimikkeen yksikkökustannus on LIFO-säännön perusteella valitun nimikkeen vastaanoton todellinen arvo.<br /><br /> Varastonarvostuksessa oletetaan, että viimeiseksi varastoon sijoitetut nimikkeet myydään ensin. **Huomautus:**  Kun hinnat nousevat, tuloslaskelman arvo pienenee. Tämä tarkoittaa, että verovelat vähenevät, mutta rahanlainauskyky heikkenee. **Tärkeää:** Tätä ei sallita monissa maissa tai monilla alueilla, koska sitä voidaan käyttää voiton alas painamiseen.|  
|Keskiarvo|Käytä, jos tuotteen kustannus on epävakaa.<br /><br /> Käytä, jos vaihto-omaisuus on pinottu tai sekoitettu yhteen, eikä niitä voida erottaa, kuten kemikaalit.|Nimikkeen yksikkökustannus on tarkka kustannus, jolloin tietty yksikkö vastaanotettiin.|  
|Määrätty|Käytä tuotannon tai kaupan helposti tunnistettavissa nimikkeissä, joilla on suhteellisen korkeat yksikkökustannukset.<br /><br /> Käytä nimikkeisiin, jotka ovat säännön alainen.<br /><br /> Käytä nimikkeille, joilla on sarjanumero.|Nimikkeen yksikkökustannus lasketaan kussakin vaiheessa keskimääräisenä yksikkökustannuksena oston jälkeen.<br /><br /> Varastonarvostus olettaa, että kaikki vaihto-omaisuus myydään samanaikaisesti.|  
|Vakio|Käytä, jos kustannusten valvonta on erittäin tärkeää.<br /><br /> Käytä toistuvassa valmistuksessa arvostaaksesi suoria materiaali- ja resurssikustannuksia sekä valmistuksen yleiskustannuksia.<br /><br /> Käytä, jos käytössä on kurinalaisuutta ja henkilöstö ylläpitää standardeja.|Nimikkeen yksikkökustannus määritetty etukäteen arvion perusteella.<br /><br /> Kun todelliset kustannukset realisoituvat myöhemmin, vakiokustannus täytyy mukauttaa todellisiin kustannuksiin varianssin arvojen kautta.|  

## <a name="see-also"></a>Katso myös  
 [Rakennetiedot: Arvostusmenetelmät](design-details-costing-methods.md)   
 [Rakennetiedot: Varaston arvostus](design-details-inventory-costing.md)   
 [Monimutkaisten sovellusalueiden määrittäminen parhaiden käytäntöjen avulla](set-up-complex-application-areas-using-best-practices.md)  
 [[!INCLUDE[d365fin](includes/d365fin_md.md)] -ohjelman käyttäminen](ui-work-product.md)

