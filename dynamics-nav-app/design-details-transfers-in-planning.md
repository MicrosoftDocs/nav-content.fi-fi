---
title: Rakennetiedot - siirrot suunnittelussa
description: "Tässä ohjeaiheessa käsitellään siirtotilausten käyttöä toimituslähteenä varastomääriä suunniteltaessa."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: design, transfer, sku, locations, warehouse
ms.date: 07/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: b2c59ce5c37d5a99135b68ca63d0a2d06e871d7f
ms.contentlocale: fi-fi
ms.lasthandoff: 10/16/2017

---
# <a name="design-details-transfers-in-planning"></a>Rakennetiedot: siirrot suunnittelussa
Siirtotilaukset ovat myös tarjonnan lähde, kun työskennellään varastointiyksikön tasolla. Kun käytössä on useita sijainteja (fyysisiä varastoja), varastointiyksikön täydennysjärjestelmän arvoksi voi määrittää Siirto. Tällöin sijainnin täydennys tehdään siirtämällä tavaroita toisesta sijainnista. Yrityksillä voi olla useita varastoja ja yhdistettyjä siirtoja, joissa toimitus VIHREÄÄN sijaintiin siirretään KELTAISESTA ja toimitus KELTAISEEN siirretään PUNAISESTA ja niin edelleen. Ketjun alussa on täydennysjärjestelmänä Tuotantotilaus tai Osto.  
  
![](media/nav_app_supply_planning_7_transfers1.png "NAV_APP_supply_planning_7_transfers1")  
  
Jos verrataan tilannetta, jossa toimitustilaus liittyy suoraan kysyntätilaukseen tilanteeseen, jossa myyntitilaus toimitetaan varastointiyksiköiden siirtoketjun kautta, suunnittelutehtävä voi jälkimmäisessä tapauksessa olla hyvin monimutkainen. Jos kysyntä muuttuu, tämä saattaa aiheuttaa heijastusvaikutuksen ketjun läpi, koska ketjun toisessa päässä olevia kaikkia siirtotilauksia sekä osto/tuotantotilausta on muutettava kysynnän ja tarjonnan välisen tasapainon palauttamiseksi.  
  
![](media/nav_app_supply_planning_7_transfers2.png "NAV_APP_supply_planning_7_transfers2")  
  
## <a name="why-is-transfer-a-special-case"></a>Miksi siirto on erikoistapaus?  
Siirtotilaus on pitkälti samanlainen kuin kaikki muut ohjelman tilaukset. Taustalla se on kuitenkin hyvin erilainen.  
  
Yksi olennainen asia, joka erottaa siirtojen suunnittelun osto- ja tuotantotilauksista on, että siirtorivi kuvaa kysyntää ja tarjontaa samaan aikaan. Lähtevä osa, joka lähetetään vanhasta sijainnista, on kysyntä. Tuleva osa, joka tulee vastaanottaa uudessa sijainnissa, on tämän sijainnin tarjonta.  
  
![](media/nav_app_supply_planning_7_transfers3.png "NAV_APP_supply_planning_7_transfers3")  
  
Tämä tarkoittaa sitä, että kun järjestelmä muuttaa siirron tarjontapuolta, sen on tehtävä samanlainen muutos kysyntäpuoleen.  
  
## <a name="transfers-are-dependent-demand"></a>Siirrot ovat riippuvaisia kysynnästä  
Liittyvällä kysynnällä ja tarjonnalla on jotain samankaltaista tuotantotilausrivin osien kanssa, mutta ero on se, että osat ovat seuraavalla suunnittelutasolla eri nimikkeen kanssa, kun taas siirron kaksi osaa sijaitsevat samalla tasolla samaan nimikkeeseen liittyen.  
  
Tärkeä samankaltaisuus on se, että siirtokysyntä riippuu kysynnästä vastaavasti kuin komponentit ovat riippuvaisia kysynnästä. Siirron tarjontapuoli sanelee siirtorivin kysynnän siinä mielessä, että jos tarjontaa vaihdetaan, se vaikuttaa suoraan kysyntään.  
  
Jos suunnittelun joustavuuden arvoksi ei ole määritetty Ei mitään, siirtoriviä ei saa koskaan käsitellä itsenäisenä tarpeena suunnittelussa.  
  
Suunnittelutoimenpiteessä siirron kysyntä tulisi ottaa huomioon vasta, kun suunnittelujärjestelmä on käsitellyt tarjontapuolen. Ennen tätä todellinen kysyntä ei ole tiedossa. Tehtyjen muutosten sarja on siksi hyvin tärkeä, mitä tulee siirtotilauksiin.  
  
## <a name="planning-sequence"></a>Suunnittelujärjestys  
Seuraavassa kuvassa esitetään miltä siirtoketju voisi näyttää.  
  
![](media/nav_app_supply_planning_7_transfers4.png "NAV_APP_supply_planning_7_transfers4")  
  
Tässä esimerkissä asiakas tilaa nimikkeen VIHREÄSTÄ sijainnista. VIHREÄ sijainti toimitetaan siirron kautta PUNAISESTA keskusvarastosta. Siirto toimittaa päävaraston RED:in tuotannosta sijainnissa BLUE.  
  
Tässä esimerkissä suunnittelujärjestelmä aloittaa asiakkaan kysynnästä ja siirtyy taaksepäin ketjussa. Kysynnät ja tarjonnat käsitellään sijainti kerrallaan.  
  
![](media/nav_app_supply_planning_7_transfers5.png "NAV_APP_supply_planning_7_transfers5")  
  
## <a name="transfer-level-code"></a>Siirtotason koodi  
Sarja, jossa sijainteja työstetään suunnittelujärjestelmässä, on määritetty SKU:n siirtotason koodilla.  
  
Siirtotason koodi on sisäinen kenttä. Sen arvo lasketaan ja tallennetaan automaattisesti varastointiyksikköön varastointiyksikön luonnin tai muokkauksen yhteydessä. Laskelma kattaa kaikki nimikkeen/variantin annettujen yhdistelmien SKU:t ja käyttää sijaintikoodia sekä siirrä jostakin -koodia määrittääkseen reitin, joka suunnitelmalla on käytössä, kun se käy läpi SKU:t. Tällöin varmistetaan, että kaikki kysyntä prosessoidaan.  
  
Siirtotason koodi on 0, kun kyseessä ovat täydennysjärjestelmän osto- tai tuotantotilausten varastointiyksiköt. Ensimmäisellä siirtotasolla koodi on -1, toisella -2 jne. Yllä kuvatussa siirtoketjussa tasot olisivat täten -1 PUNAISELLE ja -2 VIHREÄLLE seuraavassa kuvassa esitetyllä tavalla.  
  
![](media/nav_app_supply_planning_7_transfers6.gif "NAV_APP_supply_planning_7_transfers6")  
  
Kun varastointiyksikköä päivitetään, suunnittelujärjestelmä tunnistaa varastointiyksiköt, kun täydennysjärjestelmä on Siirto ja kehäviittaukset on määritetty.  
  
## <a name="planning-transfers-without-sku"></a>Siirtojen suunnittelu ilman varastointiyksiköitä  
  
Vaikka varastointiyksikköominaisuutta ei käytetä, sijaintien käyttäminen ja sijaintien väliset siirrot ovat mahdollisia. Yritykset, joissa on käytössä vähemmän kehittynyt f. varaston asetus, suunnittelujärjestelmä tukee skenaarioita, joissa olemassa oleva varasto siirretään manuaalisesti toiseen sijaintiin, esimerkiksi myyntitilauksen kattamiseksi tässä sijainnissa. Samaan aikaan suunnittelujärjestelmän tulisi reagoida kysynnän muutoksiin.  
  
Suunnittelu tukee manuaalisia siirtoja analysoimalla olemassa olevat siirtotilaukset ja suunnittelemalla sijaintien käsittelyjärjestyksen. Suunnittelujärjestelmä toimii sisäisesti väliaikaisilla varastointiyksiköillä joilla on siirtotason koodit.  
  
![](media/nav_app_supply_planning_7_transfers7.png "NAV_APP_supply_planning_7_transfers7")  
  
Jos tietyssä sijainnissa on enemmän siirtoja, ensimmäinen siirtotilaus määrittää suunnittelun suunnan. Vastakkaiseen suuntaan suoritettavat siirrot peruutetaan.  
  
## <a name="changing-quantity-with-reservations"></a>Määrän muuttaminen varausten kanssa  
Kun olemassa olevan tarjonnan määriä muutetaan, suunnittelujärjestelmä tekee tilille varaukset niin, että varattu määrä edustaa alempaa rajaa siitä, miten paljon tarjontaa voi vähentää.  
  
Kun olemassa olevan siirtotilausrivin määrää muutetaan, on muistettava, että alemmaksi määräksi määritetään lähtevän ja tulevan siirtorivin suurin varattu määrä.  
  
Esimerkiksi, jos siirtotilausrivin 117 kappaletta varataan myyntiriviä 46 ja ostoriviä 24 vastaan, siirtoriviä ei ole mahdollista vähentää alhaisemmaksi kuin 46 kappaletta, vaikka tämä saattaisi vastata ylimääräistä tarjontaa saapuvien puolella.  
  
![](media/nav_app_supply_planning_7_transfers8.png "NAV_APP_supply_planning_7_transfers8")  
  
## <a name="changing-quantity-in-a-transfer-chain"></a>Määrän muuttaminen siirtoketjussa  
Seuraavassa esimerkissä lähtökohtana on täsmäytetty tilanne, jossa siirtoketju toimittaa PUNAISESSA sijainnissa olevan 27 yksikön myyntitilauksen vastaavalla ostotilauksella sijainnissa SININEN ja siirto tapahtuu sijainnin VAALEANPUNAINEN kautta. Tämän vuoksi myyntiä ja ostoa lukuun ottamatta siirtotilauksia on kaksi: SININEN-VAALEANPUNAINEN ja VAALEANPUNAINEN-PUNAINEN.  
  
![](media/nav_app_supply_planning_7_transfers9.png "NAV_APP_supply_planning_7_transfers9")  
  
Nyt suunnittelija VAALEANPUNAISESSA sijainnissa luo varauksen ostoon.  
  
![](media/nav_app_supply_planning_7_transfers10.png "NAV_APP_supply_planning_7_transfers10")  
  
Tämä tarkoittaa yleensä sitä, että suunnittelujärjestelmä ohittaa ostotilauksen ja siirron kysynnän. Ongelmia ei ole niin kauan täsmäytys on voimassa. Mutta mitä tapahtuu, kun asiakas muuttaa tilaustaan osittain PUNAISESSA sijainnissa arvoon 22?  
  
![](media/nav_app_supply_planning_7_transfers11.png "NAV_APP_supply_planning_7_transfers11")  
  
Kun suunnittelujärjestelmä toimii jälleen, sen tulisi päästä eroon ylimääräisestä tarjonnasta. Varaus lukitsee kuitenkin oston ja siirron määrään 27.  
  
![](media/nav_app_supply_planning_7_transfers12.png "NAV_APP_supply_planning_7_transfers12")  
  
PINK-RED-siirto on vähennetty 22:een. BLUE-PINK-siirron tulevaa osaa ei ole varattu, mutta koska lähtevä osa on varattu, määrän vähennys 27:n ei ole mahdollista.  
  
## <a name="lead-time-calculation"></a>Toimitusajan laskenta  
Siirtotilauksen eräpäivän laskennassa otetaan huomioon eri toimitusajat.  
  
Läpimenoajat, jotka ovat aktiivisia, kun siirtotilauksen suunnittelu on:  
  
* Lähtevä fyysisen varastoinnin käsittelyaika  
* Toimitusaika  
* Saapuva fyysisen varastoinnin käsittelyaika  
* Suunnittelurivillä käytetään seuraavia kenttiä tarjoamaan tietoja laskennasta.  
* Siirtotoimituksen pvm  
* Aloituspvm  
* Lopetuspvm  
* Eräpäivä  
  
Siirtorivin toimituspäivämäärä näkyy Siirtotoimituspäivä-kentässä ja siirtorivin vastaanottopäivämäärä näkyy Eräpäivä-kentässä.  
  
Aloitus- ja lopetuspäivämääriä käytetään kuvaamaan nykyistä kuljetusjaksoa.  
  
Seuraavassa kuvassa esitetään aloituspäivämäärän ja ajan sekä lopetuspäivämäärän sekä ajan tulkinta siirtotilauksiin liittyvillä suunnitteluriveillä.  
  
![](media/nav_app_supply_planning_7_transfers13.png "NAV_APP_supply_planning_7_transfers13")  
  
Tässä esimerkissä se tarkoittaa, että:  
  
* Toimituspvm + Lähtevä käsittely = Aloituspvm  
* Aloituspvm + Toimitusaika = Lopetuspvm  
* Lopetuspvm + Saapuva käsittely = Vast.ott. pvm  
  
## <a name="safety-lead-time"></a>Toimitusajan varmistus  
Oletusarvoista varmuusläpimenoaikaa tuotantoasetukset - ikkunassa sekä liittyvää varmuusläpimenoaika -kenttää nimikkeen kortissa ei oteta huomioon siirtotilauksen laskelmassa. Toimitusajan varmistus vaikuttaa kuitenkin yhä kokonaissuunnitelmaan, kuten se vaikuttaa täydennystilaukseen (osto tai tuotanto) siirtoketjun alussa, kun nimikkeet sijoitetaan paikkaan, josta ne siirretään.  
  
![](media/nav_app_supply_planning_7_transfers14.png "NAV_APP_supply_planning_7_transfers14")  
  
Tuotantotilausrivillä, Lopetuspvm + Toimitusajan varmistus + Saapuva f.var. käsittelyaika = Eräpäivä.  
  
Ostotilausrivillä Suunniteltu vast.otto pvm + Toimitusajan varmistus + Saapuvan f.var. käsittelyaika = Oletettu vast.otto pvm.  
  
## <a name="reschedule"></a>Aikataul. uud.  
Kun olemassa oleva siirtorivi ajoitetaan uudelleen, suunnittelujärjestelmän on etsittävä lähtevä osa ja muutettava sen päivämäärä ja aika. On tärkeää huomata, että jos toimitusaika on määritetty, toimituksen ja vastaanoton välillä on aukko. Kuten on mainittu, toimitusaika voi koostua useista elementeistä, kuten kuljetusaika ja fyysisen varastoinnin käsittelyaika. Suunnittelujärjestelmä liikkuu aikajanalla takaisin, kun se täsmää elementtejä.  
  
![](media/nav_app_supply_planning_7_transfers15.png "NAV_APP_supply_planning_7_transfers15")  
  
Tämän vuoksi siirtorivin eräpäivän muuttamisen yhteydessä on laskettava toimitusaika ja päivitettävä siirron lähtevä osuus.  
  
## <a name="seriallot-numbers-in-transfer-chains"></a>Sarja-/eränumerot siirtoketjuissa  
Jos kysynnässä on sarja-/eränumeroita ja suunnittelujärjestelmä suoritetaan, se kasvattaa eräiden suoraan luotavien siirtotilausten määrää. Katso lisätietoja tästä käsitteestä Nimikkeen määritteet -kohdasta. Jos sarja-/eränumerot kuitenkin poistetaan kysynnästä, ketjun luodut siirtotilaukset sisältävät edelleen sarja-/eränumerot ja tämän vuoksi ne jätetään huomioimatta suunnittelussa (ei poisteta).  
  
## <a name="order-to-order-links"></a>Tilausten väliset linkit  
Tässä esimerkissä SININEN varastointiyksikkö on asetettu Tilaus-uusintatilaustavalla ja VAALEANPUNAINEN ja PUNAINEN käyttävät erä-erästä-uusintatilaustapaa. Kun myyntitilaus 27 luodaan sijaintiin PUNAINEN, se johtaa yhdistettyihin siirtoihin, joiden sijainnissa SININEN sijaitseva viimeinen kohta varataan sidonnan kanssa. Tässä esimerkissä varaukset eivät ole kiinteitä suunnittelijan VAALEANPUNAISESSA sijainnissa luomia varauksia, vaan suunnittelujärjestelmän luomia sidoksia. Oleellinen ero on se, että suunnittelujärjestelmä voi vaihtaa jälkimmäisen.  
  
![](media/nav_app_supply_planning_7_transfers16.png "NAV_APP_supply_planning_7_transfers16")  
  
Jos kysyntä muutetaan arvosta 27 arvoon 22, järjestelmä vähentää määrä koko ketjussa ja myös sitova varaus vähenee.  
  
## <a name="see-also"></a>Katso myös  
[Rakennetiedot: suunnittelun parametrit](design-details-planning-parameters.md)   
[Rakennetiedot: suunnittelun kohdistustaulukko](design-details-planning-assignment-table.md)   
[Rakennetiedot: uusintatilauskäytäntöjen käsittely](design-details-handling-reordering-policies.md)   
[Rakennetiedot: kysyntä tyhjä-sijainnissa](design-details-demand-at-blank-location.md)   
[Rakennetiedot: suunnittelujärjestelmän keskeiset käsitteet](design-details-central-concepts-of-the-planning-system.md)   
[Rakennetiedot: kysynnän ja tarjonnan täsmäytys](design-details-balancing-demand-and-supply.md)   
[Rakennetiedot: Tarjonnan suunnittelu](design-details-supply-planning.md)
