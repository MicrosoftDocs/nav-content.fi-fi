---
title: "Tuotantosolujen ja kuormituskeskusten määrittäminen"
description: "**Tuotantosolu**-korttiin kootaan tuotantoresurssin kiinteät arvot ja vaatimukset. Nämä tiedot ohjaavat tuotantosolussa tapahtuvan tuotannon tuotosta."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 09/19/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: b9b1f062ee6009f34698ea2cf33bc25bdd5b11e4
ms.openlocfilehash: ba71815bc7d099b7f600ab828dec579ddbf2265a
ms.contentlocale: fi-fi
ms.lasthandoff: 10/23/2017

---
# <a name="how-to-set-up-work-centers-and-machine-centers"></a>Toimintaohje: Tuotantosolujen ja kuormituskeskusten määrittäminen
Ohjelmassa erotetaan kolme eri kapasiteettityyppiä. Tyypit on järjestelty hierarkkisesti. Jokaiseen tasoon kuuluu alatasoja.  

Ylin taso on tuotantosoluryhmä. Tuotantosolut on määritelty tuotantosoluryhmiin. Jokainen tuotantosolu voi kuulua vain yhteen tuotantosoluryhmään.

Jokaiselle tuotantosolulle voi määritellä useita kuormitusryhmiä. Yksi kuormitusryhmä voi kuulua vain yhteen tuotantosoluun.  

Tuotantosolun suunniteltu kapasiteetti koostuu vastaavien kuormitusryhmien saatavuudesta ja tuotantosolun suunnitellusta lisäsaatavuudesta. Tuotantosoluryhmän suunniteltu saatavuus on siten kaikkien vastaavien kuormitusryhmien ja tuotantosolujen saatavuuksien summa.  

Saatavuus tallennetaan kalenteritapahtumiin. Tuotantokalenteri on määritettävä ennen tuotantosolujen tai kuormitusryhmien määrittämistä. Lisätietoja on kohdassa [Toimintaohje: Tuotantokalenterien luominen](production-how-to-create-work-center-calendars.md).  

## <a name="to-set-up-a-work-center"></a>Tuotantosolun määrittäminen
Seuraavaksi käsitellään ennen kaikkea tuotantosolun määrittämiseen. Kuormitusryhmän kalenterin määrittämisen vaiheet ovat vastaavanlaiset **Reitityksen asetukset** -pikavälilehteä lukuun ottamatta.  

1.  Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, kirjoita **Tuotantosolut** ja valitse sitten aiheeseen liittyvä linkki.  
2.  Valitse **Uusi**-toiminto.  
3. Täytä tarvittavat kentät. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]
4.  Valitse tarvittaessa **Tuotantosoluryhmä**-kentässä ylätason resurssiryhmä, johon tuotantosolu kuuluu. Valitse avattavassa luettelossa **Uusi**-toiminto.  
5.  Valitse **Estetty** -kenttä, jos haluat estää tuotantosolun käyttämisen käsittelyssä. Siinä tapauksessa tuotosta ei voi kirjata tuotantosolussa tuotetulle nimikkeelle. Lisätietoja on kohdassa [Toimintaohje: Tuotannon tuotoksen kirjaaminen](production-how-to-post-output-quantity.md).
6.  Anna **Välitön yksikkökustannus** -kenttään yhden yksikön tuottamiskustannus tässä tuotantosolussa muita kustannuselementtejä huomioon ottamatta. Tätä kustannusta kutsutaan usein myös *välittömäksi työkustannukseksi*.  
7.  Syötä **Välillinen kustannus-%** -kenttään yleiset tuotantosolun käytöstä syntyvät toimintakustannukset prosenttiosuutena välittömästä yksikkökustannuksesta. Tämä prosentti lisätään välittömiin kustannuksiin yksikkökustannusta laskettaessa.  
8.  Syötä **Yleiskustannus (arvo)** -kenttään tuotantosolun kaikki muut kuin toiminnasta syntyvät kustannukset, esimerkiksi kunnossapitokulut, absoluuttisena arvona.  

    **Yksikkökustannus**-kenttään lasketaan seuraavasti yhden mittayksikön tuottamisen yksikkökustannus tässä tuotantosolussa kaikki kustannuselementit huomioon ottaen:  

    Yksikkökustannus = välitön yksikkökustannus + (välitön yksikkökustannus x välillinen kustannus-%) + yleiskustannus (arvo).  

9.  Määritä **Yksikkökustannuslaskenta**-kentässä, käytetäänkö yllä olevan laskennan perustana käytettyä aikaa ( **Aika**) vai tuotettujen yksiköiden määrää ( **Yksiköt**).  
10.  Lisää **Spesifinen yksikkökustannus** -kenttään valintamerkki, jos haluat määrittää tuotantosolun yksikkökustannuksen sitä käyttävällä reititysrivillä. Tämä saattaa olla järkevää sellaisten operaatioiden kohdalla, joiden kapasiteettikustannukset eroavat huomattavasti tuotantosolun normaaleista kustannuksista.  
11.  Valitse **Materiaalinottotapa**-kentässä, lasketaanko ja kirjataanko tämän tuotantosolun tuotoksen kirjaus manuaalisesti vai automaattisesti jommallakummalla seuraavista menetelmistä:  

    |Asetus|Description|  
    |----------------------------------|---------------------------------------|  
    |**Manuaalinen**|Kulutus kirjataan manuaalisesti tuotospäiväkirjaan tai tuotantopäiväkirjaan.|
    |**Eteenpäin**|Kulutus lasketaan ja kirjataan automaattisesti, kun tuotantotilaus vapautetaan.|  
    |**Taaksepäin**|Kulutus lasketaan ja kirjataan automaattisesti, kun tuotantotilaus on valmis.|  

    > [!NOTE]  
    >  Tässä ja **nimikkeen** kortissa valittua materiaalinottotapaa voidaan muuttaa yksittäisten operaatioiden kohdalla vaihtamalla asetus reititysriveillä.

12.  Anna **Mittayksikön koodi** -kenttään ajan yksikkö, jota käytetään tämän tuotantosolun kustannuslaskennassa ja kapasiteettisuunnittelussa.
    Jotta kulutusta voitaisiin jatkuvasti tarkkailla, ensin tulee määrittää mittaustapa. Syötettävät yksiköt ovat perusyksiköitä. Esimerkiksi käsittelyaikaa mitataan tunneissa ja minuuteissa.

    > [!NOTE]  
    > Jos valitset yksiköksi Päivää, muista, että yksi päivä tarkoittaa 24:ää tuntia, ei 8:aa tuntia (työpäivää).

13.  Määritä **Kapasiteetti**-kentässä, onko tuotantosolussa samanaikaisesti useita työntekijöitä tai koneita. Jos käyttämääsi [!INCLUDE[d365fin](includes/d365fin_md.md)] -järjestelmään ei ole asennettu Kuormitusryhmä-toimintoa, kentän arvon on oltava **1**.  
14.  Anna **Tehokkuus**-kenttään tuotantosolun todellinen tuotos prosenttiosuutena oletetusta vakiotuotoksesta. Jos annat arvoksi **100**, tämä tarkoittaa, että tuotantosolun todellinen tuotos on sama kuin vakiotuotos.  
15. Valitse **Yhdistetty kalenteriin** -valintaruutu, jos käytät myös kuormitusryhmiä. Tämä varmistaa, että kalenteritapahtumat vyörytetään kuormitusryhmän kalentereista.  
16.  Valitse **Tuotantokalenterin koodi** -kentässä tuotantokalenteri. Lisätietoja on kohdassa [Toimintaohje: Tuotantokalenterien luominen](production-how-to-create-work-center-calendars.md).  
17.  Määritä **Jonotusaika**-kenttään aika, jonka täytyy kulua, ennen kuin tuotantosolulle määritetty työ voidaan aloittaa. Huomaa, että jonotusaika lisätään muihin tuottamattomiin aikaelementteihin, kuten odotusaikaan ja siirtoaikaan, jotka voidaan määrittää tätä tuotantosolua käyttäville reititysriveille.  

## <a name="example---different-machine-centers-assigned-to-a-work-center"></a>Esimerkki - Tuotantosoluun liitetyt erilaiset kuormitusryhmät
On tärkeää suunnitella, mitkä kapasiteetit muodostavat kokonaiskapasiteetin silloin, kun määritellään kuormitusryhmiä ja tuotantosoluja.

Jos eri kuormitusryhmiä (esimerkiksi 210 Pakkausosasto 1, 310 Maalaushuone) on määritelty yhdelle tuotantosolulle, kuormitusryhmien yksittäisten kapasiteettien huomioon ottaminen on tärkeää, koska yhden kuormitusryhmän epäonnistuminen voi keskeyttää koko prosessin. Kuormitusryhmät voi syöttää niiden kapasiteetin mukaisesti, mutta niitä ei voi sisällyttää suunnitteluun. Jos **Yhdistetty kalenteriin** -kenttä deaktivoidaan, suunnitteluun määritellään vain tuotantosolun kapasiteetti, muttei kuormitusryhmän kapasiteettia.

Jos tuotantosoluksi on kuitenkin yhdistetty identtisiä kuormitusryhmiä (kuten 210 Pakkausosasto 1 ja 220 Pakkausosasto 2), tuotantosolu kannattaa käsittää määriteltyjen kuormitusryhmien summaksi. Tämän vuoksi tuotantosolu luetteloitaisiin nollakapasiteetilla. Jos **Yhdistetty kalenteriin** -kenttä aktivoidaan, yleinen kapasiteetti määritellään tuotantosolulle.

Jos tuotantosolujen kapasiteettien ei ole tarkoitus vaikuttaa kokonaiskapasiteettiin, sen voi saavuttaa asettamalla tehokkuudeksi 0.

## <a name="to-set-up-a-capacity-constrained-machine-or-work-center"></a>Kapasiteettirajoitetun kuormitusryhmän tai tuotantosolun määrittäminen
Tässä taulukossa on mahdollista määritellä tuotantoresurssit niille alueille, joita pidät kriittisinä, ja merkitä ne hyväksymään äärellinen kuormitus oletusarvoisen äärettömän kuormituksen sijaan, jotka muut tuotantoresurssit hyväksyvät. Kapasiteettirajoitettu resurssi voi olla tuotantosolu tai kuormitusryhmä, jonka olet tunnistanut pullonkaulaksi ja jolle haluaisit määritellä rajoitetun (rajallisen) kuormituksen.

[!INCLUDE[d365fin](includes/d365fin_md.md)] ei tue yksityiskohtaista työnohjausta. Se suunnittelee resurssien käytön tarjoamalla karkean aikataulun, mutta se ei luo ja ylläpidä automaattisesti tarkkoja aikatauluja prioriteetteihin tai optimointisääntöihin perustuen.

Voit tehdä **Kapasiteettirajoitetut resurssit** -ikkunassa määritykset, jotka estävät tiettyjen resurssien ylikuormituksen ja varmistaa, että kapasiteettia ei jää kohdentamatta, jos se voisi parantaa tuotantotilauksen läpimenoaikaa. Voit lisätä **Vaimennin (% koko kapasiteetista)** -kenttään resurssien puskuriajan toiminnon jaon minimoimiseksi. Tämän avulla järjestelmä ajoittaa kuormituksen viimeiseen mahdolliseen päivään niin, että kriittinen kuormitusprosentti ylittyy hieman. Tämä voi vähentää jaettavien toimintojen määrää.

Kun suunnitellaan kapasiteettirajoitettuja resursseja, järjestelmä varmistaa, että resurssia ei ole kuormitettu enempää kuin sille määritetty kapasiteetti osoittaa (kriittinen kuormitus). Tämä tehdään määrittämällä jokaiselle toiminnolle lähin mahdollinen aika. Jos ajankohta ei ole tarpeeksi suuri koko toiminnon suorittamiseksi, toiminto jaetaan kahdeksi tai useammaksi osaksi, jotka sijoitetaan lähimpiin käytettävissä oleviin ajankohtiin.

1. Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, kirjoita **Kapasiteettirajoitetut resurssit** ja valitse sitten aiheeseen liittyvä linkki.
2. Valitse **Uusi**-toiminto.
3. Täytä tarvittavat kentät.

> [!NOTE]
> Toiminnot niissä kuormitusryhmissä tai tuotantosoluissa, jotka on määritetty rajoitetuiksi resursseiksi, suunnitellaan aina sarjana. Tämä tarkoittaa, että vaikka rajoitetulla resurssilla on useita kapasiteetteja, näiden kapasiteettien suorittamia toimintoja voidaan suunnitellaan vain peräkkäin, ei rinnakkain, kuten tapahtuisi, jos tuotantosolua tai kuormitusryhmää ei olisi määritetty rajoitetuksi resurssiksi. Rajoitetun resurssin tuotantosolun tai kuormitusryhmän Kapasiteetti-kentän arvo on suurempi kuin 1.

> Jos toiminto jaetaan, asetusaika kohdistetaan vain kerran, koska oletetaan, että jotkin manuaaliset muutokset suoritetaan aikataulun optimoimiseksi.

## <a name="see-also"></a>Katso myös  
[Toimintaohje: Tuotantokalenterien luominen](production-how-to-create-work-center-calendars.md)  
[Tuotannon määrittäminen](production-configure-production-processes.md)  
[Tuotanto](production-manage-manufacturing.md)    
[Suunnittelu](production-planning.md)   
[Vaihto-omaisuus](inventory-manage-inventory.md)  
[Osto](purchasing-manage-purchasing.md)  
[[!INCLUDE[d365fin](includes/d365fin_md.md)] -ohjelman käyttäminen](ui-work-product.md)

