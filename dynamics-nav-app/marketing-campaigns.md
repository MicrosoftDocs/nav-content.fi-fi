---
title: "Markkinointikampanjoiden määrittäminen Dynamics NAV -ohjelmassa"
description: "Ohjeaiheessa käsitellään, miten markkinointikampanjat määritetään ja toteutetaan Dynamics NAV -ohjelmassa ja miten ne auttavat tunnistamaan ja houkuttelemaan prospekteja sekä säilyttämään asiakkaita."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: marketing, campaign, promo, prospect
ms.date: 06/06/2017
ms.author: edupont
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 3f8fd64397161f00a289b0d0435ebcf2de76de80
ms.contentlocale: fi-fi
ms.lasthandoff: 10/16/2017

---
# <a name="managing-marketing-campaigns"></a>Markkinointikampanjoiden hallinta
Vahvan markkinointisuunnitelman avulla yritys voi tunnistaa, houkutella ja säilyttää asiakkaita. Markkinointisuunnitelma sisältää erilaisia kampanjoita ja muita myyntiin ja markkinointiin liittyviä vuorovaikutustapoja. Kampanjan suunnitteluvaiheessa on päätettävä kohteena olevat kontaktit, kampanjan tyyppi (kuten messut tai suoramainonta) ja myyjien tehtävät.

Jokainen kampanja koostuu eri toiminnoista tai tehtävistä. Voit yhdistää toiminnoissa useita tehtäviä, kuten kutakin vaihetta koskeva tehtävän. Toiminnon tehtävät liittyvät toisiinsa päivämääräkaavan avulla. Yksittäiset tehtävät voidaan määrittää vain myyjille. Toiminnot voidaan määrittää mahdollisuuksille, myyjille, myyjäryhmille tai kontakteille. Lisätietoja on ohjeaiheessa [Toimintaohje: Mahdollisuuden myyntisyklien ja syklin vaiheiden määrittäminen](marketing-how-setup-opportunity-sales-cycles-stages.md).

## <a name="defining-individual-campaigns"></a>Yksittäisten kampanjoiden määrittäminen
Ennen kampanjan luomista on määritettävä *kampanjan tilakoodit*. Näiden koodien avulla kampanjoiden hallinta on helpompaa, koska kampanjalle määritetään tila. Kun kampanja etenee, näet nopeasti, missä vaiheessa kampanja on ja mikä on seuraava vaihe. Kampanjan tilakoodit määritetään **Kampanjan tila** -ikkunassa.

Voit luoda jokaiselle seurattavalle kampanjalle kampanjan kortin. Näiden korttien avulla voit myös tarkastella kampanjoiden yleistietoja.
Voit poistaa kampanjatapahtumia, esimerkiksi jos tapahtumassa on kyse toiminnosta, jotka on peruutettu. Vain peruutettuja kampanjatapahtumia voi poistaa.

### <a name="selecting-the-target-audience"></a>Kohderyhmän valitseminen
Kampanjan luomisen jälkeen voit luoda kampanjassa käytettävät segmentit, jotka määrittävät kampanjan kohdeyleisön. Lisätietoja on myös kohdassa [Segmenttien hallinta](marketing-segments.md).

### <a name="registering-discount-percentages"></a>Alennusprosenttien rekisteröiminen
Kun olet asettanut **kampanjan**, päättänyt mitä segmenttejä haluat kampanjan kattavan ja asettanut Aloitus- ja Lopetuspvm:t, rekisteröit alennus -%, jonka asiakkaat saavat yksittäisille nimikkeille Myyntirivialennukset -ikkunassa. Voit rekisteröidä myös rivien yksittäisten nimikkeiden myyntihinnat **Myyntihinnat**-ikkunassa. Voit käyttää molempia ikkunoita kampanjan kortista.

 Kun olet asettanut myyntihinnat/rivialennukset ja kampanjakortin segmentit, sinun tulee aktivoida ne niin, että kampanjan hinnat/alennukset tulevat esille myös riveille.

> [!NOTE]  
>   Voit aktivoida myyntihinnat ja rivialennukset määrittämällä, onko kampanjan kohteena koko segmentti vai vain osa kontakteista. Jos myyntihinta/rivialennus kattaa kaikki segmentin kontaktit, lisää valintamerkki **Segmentti**-kortin **Kampanja**-pikavälilehden **Kampanjan kohde** -kenttään.

Jos myyntihintaa tai rivialennuksia ei tarjota segmentin kaikille kontakteille, voit poistaa valintamerkin kyseisten kontaktien **Kampanjan kohde** -kentästä. Jos tämä kenttä ei ole näkyvissä, voit lisätä sen näkymään. Lisätietoja on kohdassa [Käyttäjän mukautus](ui-user-personalization.md).

## <a name="conducting-campaigns"></a>Kampanjoiden toteuttaminen
Kaikki kampanjan aikainen kontaktin tai segmentin kanssa tapahtuva yhteydenpito tallennetaan. Tällä tavoin saat käyttöösi kampanjaa sekä kustannuksia ja onnistumisprosentteja koskevia tilastotietoja ja muita tietoja.

Myyjät hoitavat kampanjoita, ja sinun onkin luotava kutakin tehtävää vastaa toiminto ja määritettävä se soveltuvalle myyjälle. Lisätietoja on ohjeaiheessa [Toimintaohje: Mahdollisuuden myyntisyklien ja syklin vaiheiden määrittäminen](marketing-how-setup-opportunity-sales-cycles-stages.md).

## <a name="see-also"></a>Katso myös
[Kontaktien hallinta](marketing-contacts.md)  
[Segmenttien hallinta](marketing-segments.md)  
[Myyntimahdollisuuksien hallinta](marketing-manage-sales-opportunities.md)  
[Dynamics NAV -ohjelman käyttäminen](ui-work-product.md)  

