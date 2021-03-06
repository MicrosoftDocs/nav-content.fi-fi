---
title: Analyysiraporttien luominen
description: "Kuvaa, miten uusien analyysiraporttien luominen myyntejä, ostoja ja varastoa varten sekä analyysimallien määrittäminen tapahtuu."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: bi, power BI, analysis, KPI
ms.date: 06/16/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 72f1597eb226ee2a291b21faf83f582d6bdfa3f2
ms.contentlocale: fi-fi
ms.lasthandoff: 10/16/2017

---
#  <a name="how-to-create-analysis-reports"></a>Uusien myynnin analyysiraporttien luominen
Myyntipäälliköiden on analysoitava liikevaihtoa, bruttokatetta ja muita myynnin tunnuslukuja säännöllisesti. Ostajat ovat kiinnostuneempia ostovolyymien dynamiikasta, toimittajien suorituskyvystä ja ostohinnoista. Logistiikka-/varastopäälliköt puolestaan tarvitsevat tietoja varaston kierrosta, varaston siirtoanalyysin ja tilastotietoja varaston arvosta.  

Analyysiraporttien avulla voit luoda räätälöityjä raportteja kirjattujen tapahtumien, esimerkiksi myynnin, ostojen, siirtojen ja varastonmuutosten, tietueiden perusteella. Räätälöitävän raportin lähdetietoja, jotka johdetaan nimiketapahtumista (niihin liittyvien arvotapahtumien kera), voidaan yhdistää, vertailla ja esittää mielekkäillä käyttäjän määrittämillä tavoilla. Niinpä analyysiraportti muistuttaa hyvin paljon Microsoft Excelin pivot-taulukkoraporttia.  

Voit luoda mukautetun raportin, jossa keskitytään avainasiakkaisiin kokonaisliikevaihdossa sekä summina että myytyinä määrinä, bruttokatteena ja bruttokateprosenttina kuluvana kuukautena, ja verrataan näitä lukuja edellisten kuukausien tai edellisen vuoden saman kuukauden tuloksiin sekä lasketaan poikkeamia. Kaikki tämä voidaan tehdä yhdessä ja samassa näkymässä, jossa on mahdollisuus siirtyä tunnistetun ongelman syyhyn valitsemalla avattavan luettelon painiketta. Näin pääset tietoihin yksittäisten tapahtumien tasolla.  

Analyysiraportit koostuvat analysoitavista objekteista, kuten asiakkaista, asiakasryhmistä ja myyjistä, jotka esitetään riveinä, ja analyysin parametreista eli objektin analysointitavasta, kuten katelaskelmista, myyntisummien ja -määrien jaksoittaisista vertailuista tai todellisten ja budjetoitujen lukujen jaksoittaisista vertailuista.

Analyysiraporttien lisäksi voit luoda ja tarkastella samanlaisia tietoja analyysinäkymissä, jotka perustuvat dimensioihin. Lisätietoja on kohdassa [Toimintaohje: tietojen analysointi dimensioittain](bi-how-analyze-data-dimension.md).

## <a name="example"></a>Esimerkki  
Voit määrittää seuraavanlaiset rivit:  
- Tietokoneet  
- Näytöt  
- Varaosat.  

Sen jälkeen voit määrittää seuraavanlaiset sarakkeet:  

- Kuluvan kuukauden myynti  
- Edellisen kuukauden myynti  
- Edellisen kuukauden myynti prosentteina.  

## <a name="setting-up-line-and-column-layouts"></a>Rivi- ja sarakeasettelujen määrittäminen  
 **Analyysiraportti**-ikkunan avulla voit katsella eri rivi- ja sarakeasetteluja sen mukaan, mitä olet määrittänyt. Rivit tai rivimallit määritetään **Analyysirivimallit**-ikkunassa. Tässä ikkunassa voit määrittää raportin nimen ja raportin riveillä näkyvät objektit. Sarakkeet määritetään **Analyysisarakkeen mallit** -ikkunassa. Tässä ikkunassa voit määrittää sarakkeen mallin nimen ja raportissa sarakkeina esitettävät analyysin parametrit. **Analyysisarakkeen mallit** -ikkunassa jokainen rivi vastaa raportin saraketta. Huomaa, että analyysin rivit ja sarakkeet ovat riippumattomia toisistaan.  

Ohjelma yhdistää raportin tuloksen **Analyysiraportti**-ikkunassa määrittämiesi rivien ja sarakkeiden perusteella käyttämällä esimerkiksi seuraavanlaista matriisia:  

|||||  
|-|-|-|-|  
||Kuluvan kuukauden myynti|Edellisen kuukauden myynti|Edellisen kuukauden myynti (%)|  
|Tietokoneet||||  
|Näytöt||||  
|Varaosat||||  
|Yhteensä||||  

 Voit esimerkiksi esittää kuukausiraportin määrittämällä yhden joukon riviasetteluja ja vuosiraportin määrittämällä useita joukkoja sarakeasetteluja.

 ## <a name="to-set-up-analysis-column-templates"></a>Analyysisarakkeen mallien määrittäminen
Seuraava toimenpide perustuu myynnin analyysinäkymiin. Vaiheet ovat samanlaiset ostojen ja varaston analyysinäkymille.

Analyysin parametrit näkyvät analyysiraportissa sarakkeina. Voit määrittää analyysiraporttiin sisällytettävät sarakkeet määrittämällä analyysisarakkeen malleja.  

Malli sisältää joukon rivejä, joista jokainen vastaa analyysiraportissa näkyviä analyysisarakkeita. Kun määrität sarakkeen, liitä analyysin tyyppikoodi riviin. Analyysin tyyppikoodi määrittää lähdetietojen tyypin nimiketapahtumissa, joihin analyysi perustuu. Lähdetiedot sisältävät kustannukset, myyntisumman tai määrän ja niihin liittyvät arvotapahtumat. Voit määrittää haluamasi määrän sarakkeen malleja ja luoda sen jälkeen niiden avulla uusia analyysiraportteja.    

1. Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, syötä **Myynnin sarakemallit** ja valitse sitten aiheeseen liittyvä linkki.  
2. Valitse ensimmäinen tyhjä rivi ja täytä tarvittavat kentät.
3. Valitse **Sarakkeet**-toiminto.  
4. Valitse Sarakkeet ja määritä analyysiraporttiin sisällytettävät sarakkeet täyttämällä **Analysointisarakkeet**-ikkunan kentät.  

    > [!NOTE]  
>   Kun määrität sarakkeen, täytä **Analyysin tyyppikoodi** -kenttä (kaikkien saraketyyppien osalta lukuun ottamatta tyyppiä **Kaava**). Määritä analyysin tyyppikoodi **Analyysityypit**-ikkunassa.  

    **Huomautus**. Jos valitset **Tapahtumakirjauksen tyyppi** -kentässä **Nimiketapahtumat**, ohjelma kopioi todelliset luvut nimiketapahtumasta. Jos valitset **Nimikkeiden budjettitapahtumat**, ohjelma kopioi budjetoidut luvut budjetista.  
5.  Tallenna muutokset valitsemalla **OK**-painike.  

## <a name="to-set-up-analysis-line-templates"></a>Analyysirivimallien määrittäminen  
Seuraava toimenpide perustuu myynnin analyysiraportteihin. Vaiheet ovat samanlaiset ostojen ja varaston analyysiraporteille.

Analyysin objektit näkyvät analyysiraportissa riveillä. Voit määrittää analyysiraporttiin sisällytettävät rivit määrittämällä analyysirivimalleja.  

Malli sisältää joukon rivejä, jotka vastaavat analyysiraportissa näkyviä rivejä. Rivi voi tarkoittaa yhtä nimikettä tai nimikkeiden aluetta, yhtä asiakasta tai asiakkaiden aluetta, yhtä toimittajaa tai toimittajien aluetta tai yhtä ryhmää tai ryhmien aluetta. Voit myös luoda riville kaavan, joka laskee muut rivit yhteen. Voit määrittää haluamasi määrän rivimalleja ja luoda niiden avulla sen jälkeen uusia analyysiraportteja.    

1. Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, syötä **Myynnin rivimallit** ja valitse sitten aiheeseen liittyvä linkki.  
2. Valitse ensimmäinen tyhjä rivi ja täytä tarvittavat kentät.
3. Valitse **Rivit**-toiminto.  
4. Valitse Rivit ja luo **Analyysin rivit** -ikkunassa rivejä niitä nimikkeitä, asiakkaita, toimittajia tai myyjiä varten, joiden luvut haluat näyttää analyysiraportissa. Täytä **Tyyppi**-, **Alue**- ja **Kuvaus**-kenttä.  

> [!NOTE]  
>   Voit myös luoda useita yksittäisiä rivejä jokaista nimikettä, asiakasta ja niin edelleen kohti. Valitse Toiminnot ja sitten haluamasi lisäysvaihtoehto, jolloin ohjelma täyttää rivin kaikki asiaankuuluvat kentät. Sen jälkeen voit tarvittaessa muokata rivejä manuaalisesti. Voit halutessasi muokata rivejä manuaalisesti. Voit lisätä rivejä valitsemalla **Lisää nimikkeet** tai **Lisää nimikeryhmät** -toiminnon.  

## <a name="to-create-a-new-sales-analysis-report"></a>Uusien myynnin analyysiraporttien luominen
Seuraava toimenpide perustuu myynnin analyysiraportteihin. Vaiheet ovat samanlaiset ostojen ja varaston analyysiraporteille.

Analyysiraporttien avulla voit analysoida myynnin dynamiikkaa tunnuslukujen mukaan, jotka valitset, esimerkiksi liikevaihto, sekä summat että määrät, katetuotto tai todellisen myynnin edistyminen budjettiin verraten. Raportin avulla voit myös analysoida keskimääräisiä myyntihintojasi ja arvioida myyntihenkilöstösi myyntituloksia.  

1. Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, syötä **Myynnin analyysiraportit** ja valitse sitten aiheeseen liittyvä linkki.  
2. Valitse **Analyysiraportti - Myynti** -ikkunassa **Uusi**-toiminto.
3. Täytä tarvittavat kentät. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]
4. Valitse **Muokkaa analyysiraporttia** -toiminto.
5. Valitse **Myynnin analyysiraportti** -ikkunassa **Näytä matriisi** -toiminto.  

> [!NOTE]  
>   Rivi- ja sarakemallien yhdistelmien muodostaminen raporttien luontia varten sekä yksilöivien nimien määrittäminen niille on vapaavalintaista. Jos teet näin, sinun ei tarvitse valita rivi- ja sarakemalleja **Myynnin analyysiraportti** -ikkunassa, jos valitset raportin nimen. Kun raportin nimi on valittu, voidaan rivi- ja sarakemalleja muuttaa itsenäisesti. Alkuperäinen yhdistelmä voidaan sitten myöhemmin palauttaa valitsemalla raportin nimi uudelleen.

## <a name="see-also"></a>Katso myös
[Business Intelligence](bi.md)  
[Rahoitus](finance.md)  
[Rahoituksen määrittäminen](finance-setup-finance.md)  
[Pääkirjanpito ja tilikartta](finance-general-ledger.md)  
[[!INCLUDE[d365fin](includes/d365fin_md.md)] -ohjelman käyttäminen](ui-work-product.md)  

