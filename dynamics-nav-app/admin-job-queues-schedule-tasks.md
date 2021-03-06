---
title: "Töiden aikatauluttaminen automaattisesti suoritettavaksi"
description: "Ajoitettuja tehtäviä hallitaan työjonon avulla. Näillä töillä suoritetaan raportteja ja codeuniteja. Voit määrittää töitä suoritettavaksi yhtä aikaa tai toistuvasti."
author: edupont04
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 09/01/2017
ms.author: edupont
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: d88b2157892a60fb74a5dcfcd83524895485689f
ms.contentlocale: fi-fi
ms.lasthandoff: 10/16/2017

---
# <a name="use-job-queues-to-schedule-tasks"></a>Käytä työjonoja ajoitustehtäviin
[!INCLUDE[d365fin](includes/d365fin_md.md)]:n työjonojen avulla käyttäjät voivat ajoittaa ja suorittaa tiettyjä raportteja ja koodiyksiköitä. Voit määrittää töitä suoritettavaksi yhtä aikaa tai toistuvasti. Esimerkiksi **Myyjä - Myyntitilasto** -raportti saatetaan haluta suorittaa viikoittain myyjän viikkokohtaisen myynnin seurantaa varten. **Käsittele huoltosähköpostijono** -koodiyksikkö voidaan taas suorittaa päivittäin ja varmistaa näin, että huoltotilauksiin liittyvät odottavat sähköpostit lähetetään asiakkaille ajallaan.  

## <a name="add-jobs-to-the-job-queue"></a>Töiden lisääminen työjonoon
**Työjonon tapahtumat** -ikkunassa on luettelo kaikista aiemmin luoduista töistä. Jos lisäät uuden aikataulutettavan työjonotapahtuman tiedot, sinun on ilmoitettava minkä tyyppisen objektin, kuten raportin tai codeunitin, haluat suorittaa, sekä suoritettavan objektin nimen ja tunnuksen. Voit myös lisätä parametrit, joilla määritetään työjonotapahtuman käytös. Voit esimerkiksi lisätä parametrin vain kirjattujen myyntitilausten lähettämistä varten. Sinulla tulee olla tietyn raportin tai koodiyksikön suoritusoikeus tai muutoin järjestelmä palauttaa virheen, kun työjonoa suoritetaan.  

Vaihtoehtoisesti voit määrittää suodattimen **Työjonoluokan suodatin** -kentässä. Luettelon töitä voi ryhmitellä työjonoluokkien avulla.

[!INCLUDE[d365fin](includes/d365fin_md.md)] suorittaa työt automaattisesti kullekin työjonotapahtumalle määritetyn aikataulun mukaan. Työjonotapahtuman voi myös käynnistää, pysäyttää ja asettaa pitoon manuaalisesti.

### <a name="log-files"></a>Lokitiedostot
Virheet näkyvät **Työjonon lokitapahtumat** -ikkunassa, jonka voi avata valintanauhasta. Voit myös määrittää vian työjonon virheissä. Työjonon suorituksen yhteydessä luodut tiedot tallennetaan tietokantaan.  

### <a name="background-posting-with-job-queues"></a>Taustakirjaus työjonojen avulla
Työjonot ovat tehokas väline liiketoiminnan prosessien suorituksen ajoittamiseen. Esille voi tulla instanssi, jossa useat käyttäjät yrittävät kirjata myyntitilauksia samanaikaisesti, mutta käsittelyssä voi olla vain yksi tilaus kerrallaan. Määrittämällä taustakirjausrutiinin, voit sijoittaa kirjauksia jonoon taustalla käsittelyä varten.  

 Vaihtoehtoisesti voit ajoittaa kirjaukset tunneille, jotka sopivat parhaiten organisaatiollesi. Saattaa olla hyödyllistä ajaa yrityksessä tietyt toiminnot sen jälkeen, kun suurin osa päivän tietojen syötöistä on suoritettu. Tämä on mahdollista, kun asetat työjonon ajamaan useita eräkirjausraportteja, kuten **Eräkirjaa myyntitilaukset**-, **Eräkirjaa ostotilaukset**- ja **Eräkirjaa myyntihyvityslaskut** -raportit.  

 [!INCLUDE[d365fin](includes/d365fin_md.md)] tukee taustakirjausta seuraavilla asiakirjatyypeillä:  

-   Myynti: myyntitilaus, palautustilaus, hyvityslasku, lasku  

-   Ostot: ostotilaus, palautustilaus, hyvityslasku, lasku  

 Jos työjono ei voi kirjata myyntitilausta, tilaksi muutetaan **Virhe** ja myyntitilaus lisätään niiden myyntitilausten luetteloon, jotka käyttäjän on käsiteltävä.  

> [!NOTE]  
>  Kun aikataulutat asiakirjan kirjaamisen ja kirjausprosessi alkaa, kirjausrutiini määritetään automaattisesti aikakatkaistavaksi kahden tunnin kuluessa, jos kirjausrutiini lopettaa vastaamisen jostakin syystä.  

Voit määrittää tällaisen työjonon käytön **Myyntien ja myyntisaamisten asetukset**- tai **Ostot ja ostovelat** -ikkunassa. Valitse **Taustakirjaus**-pikavälilehdessä **Kirjaa asiakirjat työjonon kautta** -valintaruutu ja täytä tarvittavat tiedot. Voit myös suorittaa täällä kaikki kyseisen koodin työjonotapahtumat **Työjonoluokan koodi** -kentän avulla. Voit käyttää esimerkiksi **Mkirjaus**-luokkaa suodattamaan kaikki myyntitilaukset, jotka vastaavat mitä tahansa työjonoa, jolla on sama luokkakoodi.  

> [!IMPORTANT]  
>  Jos määrität asiakirjat kirjaavan ja tulostavan työn ja tulostimessa avautuu valintaikkuna, kuten tunnistetietojen pyyntö tai tulostimen musteen loppumisesta ilmoittava varoitus, asiakirja kirjataan mutta sitä ei tulosteta. Vastaava työjonotapahtuma aikakatkaistaan lopulta, ja **Tila**-kentän arvoksi määritetään **Virhe**. Näin ollen suosittelemme, että et käytä tulostimen asetuksia, jotka edellyttävät vuorovaikutusta tulostimen näytön valintaruutujen kanssa taustakirjausten yhteydessä.  

## <a name="use-the-my-job-queue-part"></a>Oma työjono -osan käyttäminen
**Oma työjono** osaa näyttää työjonotapahtumat, jotka käyttäjä on aloittanut, mutta jotka eivät ole vielä valmiit. Oletusarvoisesti osa ei ole näkyvissä, joten se on lisättävä omaan roolikeskukseesi. Lisätietoja on kohdassa [Roolikeskusten muuttaminen](change-role.md).  

Tässä osassa näet käsiteltävinä tai jonossa olevat asiakirjat, joita varten tunnuksesi on määritetty **Määritetty käyttäjätunnus** -kentässä. Osan avulla voit seurata kaikkia työjonon tapahtumia, mukaan lukien taustakirjauksia. Osa tietää yhdellä silmäyksellä, onko asiakirjan kirjaamisessa tai työjonon tapahtumissa tapahtunut virheitä. Osan avulla voit peruuttaa kun asiakirjan kirjaamisen, jos se ei ole käynnissä.  

## <a name="security"></a>Suojaus  
Työjonon tapahtumien suoritus perustuu käyttöoikeuksiin. Kyseiset oikeudet on sallittava raportin tai koodiyksikön toteuttamiseen.  

Kun työjono on aktivoitu manuaalisesti, se suoritetaan käyttäjän tunnistetiedoilla. Kun työjono on aktivoitu ajoitettuna tehtävänä, se suoritetaan palvelininstanssin tunnistetiedoilla. Kun työ on suoritettu, se suoritetaan sen aktivoivan työjonon tunnistetiedoilla. Työjonon luoneella käyttäjällä on oltava myös käyttöoikeudet. Kun kyse suorita käyttäjäistunnossa -työnä (esimerkiksi taustakirjauksissa), se suoritetaan kyseisen työn luoneen käyttäjän tunnistetiedoilla.  

> [!IMPORTANT]  
>  Jos käytät [!INCLUDE[d365fin](includes/d365fin_md.md)]in mukana toimitettuja pääkäyttöoikeusjoukkoa, sinulla ja käyttäjillä oikeudet suorittaa kaikki objektit. Tässä tapauksessa kunkin käyttäjän käyttöoikeutta rajoittavat vain tietojen käyttöoikeudet.  

## <a name="using-job-queues-effectively"></a>Käytetään työjonoja tehokkaasti  
Työjonotapahtuma-tietueella on monta kenttää, joiden tarkoituksena on viedä parametrejä koodiyksikölle, jonka olet määrittänyt ajettavaksi työjonossa. Tämä tarkoittaa myös sitä, että koodiyksiköt, jotka suoritetaan työjonon kautta, on määritettävä työjonotapahtumatietueessa **OnRun**-käynnistimen parametrina. Tämä auttaa parantamaan tietoturvaa, sillä se estää käyttäjiä suorittamasta satunnaisia koodiyksiköitä työjonon kautta. Jos käyttäjän on välitettävä raportoitavat parametrit, raportti on suoritettava koodiyksikössä, joka jäsentää syöttöparametrit ja syöttää ne raporttiin ennen sen suoritusta.  

## <a name="see-also"></a>Katso myös  
[Asetukset ja hallinto Dynamics NAV -ohjelmassa](admin-setup-and-administration.md)  
[Dynamics NAVin määrittäminen](setup.md)  

