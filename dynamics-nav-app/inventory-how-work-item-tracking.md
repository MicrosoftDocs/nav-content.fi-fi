---
title: "Sarja- ja eränumeroiden määrittäminen nimikkeille seurantaa varten"
description: "Voit lisätä sarja- ja eränumeroita mihin tahansa lähtevään tai saapuvaan asiakirjaan, ja sen kirjatut nimikeseurantatapahtumat näkyvät niihin liittyvissä nimiketapahtumissa."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 08/22/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: b9b1f062ee6009f34698ea2cf33bc25bdd5b11e4
ms.openlocfilehash: fa6677e2f856fd22ff56139332aa307919b0ab96
ms.contentlocale: fi-fi
ms.lasthandoff: 10/23/2017

---
# <a name="how-to-work-with-serial-and-lot-numbers"></a>Toimintaohje: Sarja- ja eränumeroiden käsitteleminen
Voit määrittää sarja- ja eränumeroita mihin tahansa lähtevään tai saapuvaan asiakirjaan, ja sen kirjatut nimikeseurantatapahtumat näkyvät niihin liittyvissä nimiketapahtumissa. Käsittely tehdään **Nimikkeen seurantarivit** -ikkunassa.

**Nimikkeen seurantarivit** -ikkunan yläosassa olevassa määräkenttien taulukossa näkyy rivillä määritettävien nimikkeen seurantanumeroiden määrät ja summat. Määrien on vastattava asiakirjarivejä. Sen osoituksena **Määrittelemätön**-kentässä on 0.

Suorituskyvyn mittaamiseksi ohjelma kerää saatavuustietoja **Nimikkeen seurantarivit** -ikkunassa vain kerran, kun ikkuna avataan. Tällöin ohjelma ei päivitä saatavuustietoja ikkunan ollessa avoinna, vaikka varastotiedoissa tai muissa asiakirjoissa tapahtuisi muutoksia kyseisenä aikana.

Nimikkeet, joiden sarja- tai eränumeroita voi jäljittää toimitusketjussa eteen- ja taaksepäin. Tämä kätevää yleisessä laadunvarmistuksessa ja tuotteen takaisinvedossa. Lisätietoja on ohjeaiheessa [Toimintaohje: Nimikeseurannan nimikkeiden jäljittäminen](inventory-how-to-trace-item-tracked-items.md)

## <a name="about-picking-serial-or-lot-numbers-in-the-warehouse"></a>Tietoja sarja- tai eränumeroiden poimimisesta varastossa
Sarja-/eränumeroiden lähtevä käsittely on tehtävä, jota käytetään useiden eri fyysisen varaston prosessien aikana.  

Joissakin prosesseissa varastonimikkeillä ei ole sarja- tai eränumeroita ja varastotyöntekijän on määritettävä lähtevän käsittelyn aikana uudet numerot (yleensä ennalta määritetystä numerosarjasta).

Yksinkertaisissa prosesseissa varastonimikkeillä on jo sarja- tai eränumerot, jotka on määritetty esimerkiksi hyllytyksen aikana, ja nämä luvut siirtyvät automaattisesti kaikkien lähtevien varastotoimintojen kautta ilman varastotyöntekijöiden vuorovaikutusta.

Tietyissä tilanteissa, joissa varastossa on käytetty sarja- tai eränumeroita, erikoissarja- tai eränumerot määritetään lähdeasiakirjassa, kuten myyntitilauksessa. Varastotyöntekijän on sitten käytettävä tätä numeroa lähtevän varaston käsittelyn aikana. Tämä voi johtua siitä, että asiakas on pyytänyt tietyn erän tilauksen käsittelyn aikana. Kun varaston poiminta-asiakirjan tai fyysisen varaston poiminta-asiakirja on luotu lähtevästä lähdeasiakirjasta, jossa sarja- tai eränumerot on jo määritelty, kaikki **Nimikkeen seurantarivit** -ikkunan varastopoiminnan kentät on lukittu eikä niihin voi kirjoittaa. Poikkeuksena on **Käsiteltävä määrä** -kenttä. Siinä tapauksessa varaston poimintarivit määrittelevät nimikkeen seurantanumerot yksittäisillä ottamis- ja asettamisriveillä. Määrä on jo jaettu yksilöllisiin sarja-/eränumeroyhdistelmiin, koska myyntitilaus määrittää toimitettavat nimikkeen seurantanumerot.  

## <a name="item-tracking-availability"></a>Nimikeseurannan saatavuus
Kun käsittelet sarja- tai eränumeroita, [!INCLUDE[d365fin](includes/d365fin_md.md)] laskee erä- ja sarjanumeroille saatavuustiedot ja näyttää ne erilaisissa nimikeseurannan ikkunoissa. Tämän avulla voi nähdä, kuinka paljon erä- tai sarjanumeroa käytetään muissa asiakirjoissa. Tämä vähentää kaksinkertaisten kohdistuksen aiheuttamia virheitä ja epävarmuutta.

**Nimikkeen seurantarivit** -ikkunan **Saatavuus, eränro**- tai **Saatavuus, sarjanro** -kentässä näkyy varoituskuvake, jos osa valitusta määrästä tai koko määrä on jo toisten asiakirjojen käytössä tai erä- tai sarjanumeroa ei ole saatavana.

**Eränro/sarjanro - luettelo**-, **Eränro/sarjanro - saatavuus**- ja **Nimikeseuranta - valitse tapahtumat** -ikkunoissa on tietoja nimikkeen käytössä olevasta määrästä. Tämä raportti sisältää seuraavat tiedot:

|Kenttä|Description|
|-----|-----------|  
|**Määrä yhteensä**|Varastossa olevan nimikkeen kokonaismäärä|
|**Pyydetty määrä yhteensä**|Tässä ja muissa asiakirjoissa käytettäväksi pyydettyjen nimikkeiden kokonaismäärä|
|**Nykyinen odottava määrä**|Tässä asiakirjassa käytettäväksi pyydettyjen mutta ei vielä tietokantaan tallennettujen nimikkeiden määrä|
|**Nykyinen pyydetty määrä**|Tässä asiakirjassa käytettäväksi pyydettyjen nimikkeiden määrä|
|**Saatavilla oleva kokonaismäärä**|Varastossa olevien nimikkeiden kokonaismäärä vähennettynä tämän ja muiden asiakirjojen pyytämien nimikkeiden määrällä (pyydetty määrä yhteensä) ja pyydetyn mutta ei vielä tämän asiakirjan käytössä olevien nimikkeiden määrällä (nykyinen odottava määrä)|

Jos käytät **Nimikkeen seurantarivit** -ikkunaa pitkään tai teet paljon muutoksia käsiteltävänä olevaan nimikkeeseen, voit valita **Päivitä saatavuus** -toiminto. Lisäksi nimikkeen saatavuus tarkistetaan automaattisesti uudelleen, kun suljet ikkunan ja vahvistat näin, että saatavuusongelmia ei ole.

## <a name="to-set-up-item-tracking-codes"></a>Nimikkeen seurantakoodien määrittäminen
Nimikkeen seurantakoodi kuvastaa niitä asioita, jotka yritys on ottanut huomioon koskien sarja-/eränumeroiden käyttöä nimikkeiden kohdalla, jotka kulkevat varaston läpi.  

1. Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, kirjoita **Nimikkeen seurantakoodit** ja valitse sitten aiheeseen liittyvä linkki.  
2. Valitse **Uusi**-toiminto.
3. Täytä tarvittavat kentät. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]  
4. Määritä sarja- ja eränroseurannan tavat valitsemalla **Sarjanro**- ja/tai **Eränro**-pikavälilehteä.  

### <a name="to-set-up-expiration-rules-for-serial-or-lot-numbers"></a>Vanhentumissääntöjen määrittäminen sarja-/eränumeroille  
Voit haluta määrittää tiettyjen nimikkeiden osalta erityisiä vanhenemispäivämääriä ja sääntöjä nimikkeen seurantakoodille. Tämän ominaisuuden ansiosta voit seurata sitä, milloin tietyt sarja-/eränumerot vanhenevat.

1. Valitse ensin aiemmin luotu nimikkeen seurantakoodi ja valitse sitten **Muokkaa**-toiminto.  
2.  Valitse **Muut**-pikavälilehdessä seuraavat valintaruudut.  

    |Kenttä|Description|  
    |---------------------------------|---------------------------------------|  
    |**Tiukka vanhentumisen kirj.**|Määrittää, että nimikeseurantanumerolle varastoon tullessa määritettyä vanhentumispäivämäärää tulee noudattaa silloin, kun numero poistuu varastosta.|  
    |**Man. vanh.pvm tap. tarvitaan**|Määrittää, että nimikkeen seurantariville vanhentumispäivämäärä pitää syöttää manuaalisesti.|  

### <a name="to-set-up-warranties-for-serial-or-lot-numbers"></a>Takuiden määrittäminen sarja-/eränumeroille  
Voit haluta määrittää tiettyjen nimikkeiden osalta erityisiä takuita nimikkeen seurantakoodille. Tämän ominaisuuden avulla voit seurata sitä, milloin varastossa olevien tiettyjen sarja-/eränumeroiden takuut menevät umpeen.        
1.  Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, kirjoita **Nimikkeen seurantakoodit** ja valitse sitten aiheeseen liittyvä linkki.  

1. Valitse ensin aiemmin luotu nimikkeen seurantakoodi ja valitse sitten **Muokkaa**-toiminto.  
2.  Määritä **Sekalainen**-pikavälilehden **Takuun laskentakaava** -kentän arvo ja valitse sitten valintaruudut seuraavasti.  

    |Kenttä|Description|  
    |---------------------------------|---------------------------------------|  
    |**Takuupvm:n kaava**|Määrittää tuotteen viimeisen takuupäivän.|  
    |**Man. takuupvm tapaht. tarvit.**|Määrittää, että sinun täytyy syöttää nimikeseurantariville takuupäivämäärä manuaalisesti.|  

## <a name="to-record-serial-or-lot-number-information"></a>Sarja-/Eränumerotietojen tallentaminen  
Jos sinun täytyy linkittää erityistietoja erityiseen nimikkeen seurantanumeroon, esimerkiksi laadunvarmistuksen osalta, näin voidaan tehdä sarja- tai eränumerotietojen kortissa.

1. Avaa asiakirja, johon on määritetty sarja- tai eränumeroita.
2. Avaa asiakirjan **Nimikkeen seurantarivit** -ikkuna.
3. Valitse esimerkiksi **Sarjanumerotietojen kortti** -toiminto.  

    **Sarjanumero** ja **Eränro** -kentät esitäytetään nimikeseurantarivien perusteella.  
4. Syötä lyhyesti tietoja **Kuvaus**-kenttään, esimerkiksi tiedot kohteen kunnosta.  
5. Luo erillinen kommenttitietue valitsemalla **Kommentti**.  
6. Valitse **Estetty** -valintaruutu sulkeaksesi sarja-/eränumerot pois kaikista transaktioista.  

## <a name="to-modify-existing-serial-or-lot-number-information"></a>Aiemmin luotujen sarja- tai eränumerotietojen muokkaaminen  
1. Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, kirjoita **Nimikkeet** ja valitse sitten aiheeseen liittyvä linkki.  
2. Valitse nimike, jolla on nimikkeen seurantakoodi ja sarja- tai eränumerotietoja.
3. Valitse **Nimikkeen kortti** -ikkunassa ensin **Tapahtumat**-toiminto ja sitten **Tapahtumakirjaukset**.
4. Valitse **Eränro** tai **Sarjanumero** -kenttä. Jos nimikkeen seurantanumerolla on tietoja, **Eränumeron tietoluettelo**- tai **Sarjanumeron tietoluettelo** -ikkuna avautuu.  
5. Valitse ensin kortti ja sitten **Eränumerotietojen tai sarjanumerotietojen kortti** -toiminto.  
6. Muokkaa lyhyttä kuvaustekstiä, kommenttitietuetta tai **Suljettu**-kenttää.  

Et voi muuttaa sarja- tai eränumeroita tai määriä. Tehdäksesi näin sinun tulee uudelleenluokitella kyseinen nimiketapahtuma. Lisätietoja on kohdassa Erä- tai sarjanumeroiden uudelleenluokittelu.

## <a name="to-assign-serial-or-lot-numbers-during-an-inbound-transaction"></a>Sarja-/Eränumeroiden määritteleminen saapuvien transaktioiden aikana  
Yritykset voivat haluta seurata nimikkeitään siitä lähtien, kun ne saapuvat yritykseen. Tässä tilanteessa ostotilaus on usein keskeinen asiakirja, vaikkakin nimikeseurantaa voidaan käsitellä missä tahansa saapuvassa asiakirjassa, ja sen kirjatut tapahtumat voivat näkyä niihin liittyvissä nimiketapahtumissa.  

Tarkat säännöt siitä, miten nimikeseurantanumeroita käsitellään yrityksessäsi, löytyvät **Nimikk. seurantakoodin kortti** -ikkunan asetuksista.  

> [!NOTE]  
>  Jotta nimikeseurannan numeroita voitaisiin käyttää varastoaktiviteeteissa **Erän seuranta f.varastointi**- ja **SN F.varastoinnin seuranta** -määrityskentät täytyy olla valittuina, sillä ne määrittävät erityisperiaatteet varastoaktiviteettien sarja- ja eränumeroiden käsittelylle.  

1.  Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, kirjoita **Ostotilaukset** ja valitse sitten aiheeseen liittyvä linkki.  
2.  Valitse ensin asiakirja ja sitten **Rivit**-pikavälilehdessä **Rivi**-toiminto. Valitse lopuksi **Nimikkeen seurantarivit**.  

    Voit määrittää sarja- tai eränumeroita seuraavilla tavoilla:  

    -   Automaattisesti, napsauttamalla **määritä sarjanro** tai **määritä eränro** jotta ohjelma määrittäisi sarja/erä -numerot ennakkoon määritellystä numerosarjasta.  
    -   Automaattisesti, napsauttamalla **luo räätälöidyt sarjanrot** jotta ohjelma automaattisesti määrittää sarja-/eränumerot perustuen numerosarjoihin jotka olet määrittänyt saapuville nimikkeille.  
    -   Manuaalisesti syöttämällä sarja-/eränumeroita, esimerkiksi toimittajien numeroita, suoraan.  
    -   Manuaalisesti määrittelemällä tietyn numeron kullekin nimikeyksikölle.  

3. Valitse **Luo räätälöity SN** -toiminto, jos haluat automaattisen määrityksen.  
4. Kohteessa **räätälöity sarjanro** -kenttä, syötä sarjanumerolle kuvaava numerosarja, esim. **S/N-Toim0001**.  
5. Syötä **Lisäys**-kenttään 1 määritelläksesi, että kukin peräkkäinen numero kasvaa yhdellä.  

    Kohteen **Luotava määrä** -kenttä sisältää oletuksena rivimäärän, mutta voit muuttaa sitä.  

6. Järjestä uudet sarjanumerot selkeäksi eräksi valitsemalla **Luo uusi eränro** -valintaruutu.  
7. Valitse **OK**-painike.  

Ohjelma luo nyt eränumeron, jossa ovat yksilöivät sarjanumerot asiakirjarivin nimikemäärän mukaisesti alkaen **S/N-Toim0001** -numerosta.  

Määrä-kenttien matriisissa ikkunan otsikossa näkyvät ikkunassa määritettävien nimikeseurantanumeroiden määrät ja summat dynaamisesti. Määrien tulee vastata asiakirjarivejä, nämä on merkittynä 0:lla **Määrittelemättömät** -kentässä.  

Kun asiakirja kirjataan, nimikeseurantatapahtumat viedään niihin liittyviin nimiketapahtumiin.

## <a name="to-assign-a-serial-or-lot-number-during-an-outbound-transaction"></a>Sarja- tai eränumeroiden määritteleminen lähtevän tapahtuman aikana  
Ohjelmassa on kaksi tapaa lisätä sarja- ja eränumerot lähteviin tapahtumiin:  

-   Valitseminen olemassa olevista sarja-/eränumeroista. Tätä mahdollisuutta käytetään silloin, kun nimikkeen seurantanumerot on jo määritelty saapuvan transaktion aikana. Lisätietoja on kohdassa Valinta aiemmin luoduista sarja- ja eränumeroista.
-   Sarja-/eränumeroiden määritteleminen lähtevien transaktioiden aikana. Tätä käytetään, kun nimikkeen seurantanumeroita ei määritetä nimikkeisiin ennen kuin ne myydään ja ne ovat valmiita toimitettaviksi.  

Nimikkeen seurantanumeroiden eri säännöt määritetään **Nimikk. seurantakoodin kortti** -ikkunassa.  

> [!NOTE]  
>  Kun määrität nimikeseurantanumeroita fyysisen varaston toiminnoille **SN F.varastoinnin seuranta** ja **Erän seuranta f.varastointi** valintaruutujen on oltava valittuna nimikkeen nimikeseurannan koodikortissa.    

1. Valitse ensin asiakirja ja sitten **Rivit**-pikavälilehdessä **Järjestä**-toiminto. Valitse lopuksi **Nimikkeen seurantarivit**.  

    Nimikkeen seurantanumeroita voi nyt määritellä seuraavilla tavoilla:  
    -   Automaattisesti esimääritetystä numerosarjasta: valitse **Määritä sarjanro**- tai **Määritä eränro** -toiminto.  
    -   Automaattisesti lähtevälle nimikkeelle määritettyjen parametrien mukaan: valitse **Luo räätälöity SN** -toiminto.  
    -   Manuaalisesti syöttämällä sarja-/eränumerot numerosarjoja käyttämättä.  

2.  Tässä menetelmässä sarjanumero määritetään automaattisesti valitsemalla **Määritä sarjanro**  

    Kohteen **Luotava määrä** -kenttä sisältää oletuksena rivimäärän, mutta voit muuttaa sitä.  
3.  Laita rasti kohtaan **Luo uusi eränro** - kenttään organisoidaksesi uusia sarjanumeroita tiettyyn erään.  
4.  Valitse **OK**, jotta ohjelma luo eränumeron ja uusia yksittäisiä sarjanumeroita liittyvien asiakirjarivien perusteella.  

Ikkunassa määritettävien nimikeseurannan numeroiden määrät ja summat näkyvät dynaamisesti määräkenttien taulukossa. Määrien tulee vastata asiakirjarivejä, nämä on merkittynä **0**:lla **Määrittelemättömät** -kentässä.  

Kun asiakirja kirjataan, nimikeseurantatapahtumat viedään niihin liittyviin nimiketapahtumiin.  

## <a name="to-select-from-existing-serial-or-lot-numbers"></a>Olemassa olevista sarja-/eränumeroista valitseminen  
Kun käsittelet nimikkeitä, jotka vaativat nimikkeen jäljitystä ja olet luomassa lähteviä transaktioneita (joissa nimikkeet lähtevät varastosta), tarvitset yleensä varastossa olevia erä- tai sarjanumeroita.  

 Tarkat säännöt siitä, miten nimikeseurantanumeriota käsitellään yrityksessäsi, löytyvät **Nimikkeen seurantakoodi** -taulukon asetuksista.  

> [!NOTE]  
>  Jotta nimikeseurantanumeroita voitaisiin käsitellä fyysisen varastoinnin aktiviteeteissa, nimikkeelle tulee määrittää SN/Erän seuranta f. varastointi, koska sillä määrätään erityisperiaatteet, jotka hallinnoivat sarja-/eränumeroita fyysisessä varastossa.

1.  Valitse mistä tahansa lähtevästä asiakirjasta rivi, jolle haluat valita sarja- tai eränumeroita.  
2.  Valitse **Rivit**-pikavälilehdessä ensin **Toiminnot**-toiminto, sitten **Rivi**- tai **Nimike**-toiminto ja lopuksi **Nimikkeen seurantarivit** -toiminto.  
3.  Voit määrittää erä- tai sarjanumeron kolmella eri tavalla **Nimikkeen seurantarivit** -ikkunassa:  

    -   Valitse ensin **Eränro**- tai **Sarjanro**-kenttää ja sitten numero **Nimikeseurannan yhteenveto** -ikkunassa.  
    -   Valitse **Valitse tapahtumat** -toiminto. **Valitse tapahtumat** -ikkunassa näkyvät kaikki erä- tai sarjanumerot sekä niiden saatavuustiedot.

4. Syötä **Valittu määrä** -kenttään kunkin erä- tai sarjanumeron se määrä, jonka haluat käyttää.   
5. Valitse **OK**. Valittujen nimikkeiden seurantatiedot siirretään nyt **Nimikkeen seurantarivit** -ikkunaan.  
6. Kirjoita tai skannaa nimikkeen seurantanumero.

Määrä-kenttien matriisissa ikkunan otsikossa näkyvät ikkunassa määritettävien nimikeseurantanumeroiden määrät ja summat dynaamisesti. Määrien tulee vastata asiakirjarivejä, nämä on merkittynä **0**:lla **Määrittelemättömät** -kentässä.  

 Kun kirjaat asiakirjarivin, nimikeseurantatiedot siirretään niihin liittyviin nimiketapahtumiin.

## <a name="to-handle-serial-and-lot-numbers-on-transfer-orders"></a>Siirtotilausten sarja- ja eränumeroiden käsitteleminen  
Eri sijaintien välillä siirrettävien sarja- ja eränumeroiden käsittelyn menetelmät ovat samanlaisia kuin ne, joita käytetään silloin, kun nimikkeitä ostetaan ja myydään.  

Tulee ottaa huomioon, että siirtotilaus on ainutlaatuinen siinä suhteessa, että sekä toimitus että vastaanotto tehdään samalle siirtoriville. Tästä johtuen joudutaan käyttämään samaa **Nimikkeen seurantarivit** -ikkunaa. Tämä tarkoittaa, että nimikkeen seurantanumerot, jotka toimitettiin yhdestä paikasta, täytyy vastaanottaa muuttumattomana seuraavassa paikassa.  

 Tarkat säännöt siitä, miten nimikeseurantanumeroita käsitellään yrityksessäsi löytyvät  **Nimikkeen seurantakoodi** -taulukon asetuksista.    
1.  Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, kirjoita **Siirtotilaukset** ja valitse sitten aiheeseen liittyvä linkki.  
2.  Avaa siirtotilaus, jonka haluat käsitellä. Valitse **Rivit**-pikavälilehdessä ensin **Rivi**-toiminto, sitten **Nimikkeen seurantarivit** -toiminto ja lopuksi **Toimitus**-toiminto.  
3.  Kohteen **nimikkeen seurantarivit**-ikkunassa voit määrittää sarja-/eränumeroita kuten mille mulle tahansa lähtevälle nimiketapahtumalle.  

    Kun käsitellään siirtonimikkeiden sarja-/eränumeroita, nimikkeille on jo tavallisesti määritelty numerot. Tämän vuoksi prosessissa tavallisesti valitaan olemassa olevista sarja-/eränumeroista.  

4.  Kirjaa siirtotilaus, ensin toimita ja sitten vastaanota, tallentaaksesi sen, että nimikkeet siirretään niiden nimikkeen seurantatapahtumat mukanaan.  

Siirron aikana **nimikkeen seurantarivit** ikkuna säilyy lukittuna.  

## <a name="to-handle-serial-and-lot-numbers-when-getting-receipt-lines-from-a-purchase-invoice"></a>Sarja- ja eränumeroiden käsitteleminen, kun saat vastaanottorivit ostolaskusta  
Kun käytät toimintoa saadaksesi kirjattuja vastaanottoja tai toimitusrivejä liittyvistä laskuista tai hyvityslaskuista, mitkä tahansa nimikkeen seurantarivit varastoasiakirjoissa siirretään automaattisesti, kuitenkin, niitä käsitellään erityisellä tavalla.

Toiminto tukee seuraavia saapuvia prosesseja:  
-   **Hae vastaanottorivit** - ostolaskulta  
-   **Hae palautustoimitusrivit** - ostohyvityslaskulta  

Toiminto tukee seuraavia lähteviä prosesseja:  
-   **Hae toimitusrivit** - myyntilaskulta. (Käytetään myös yhdistetyille toimituksille.)  
-   **Hae palautusvastaanottorivit** - myyntihyvityslaskulta  

Näissä tilanteissa, olemassa olevat nimikkeen seurantarivit kopioidaan automaattisesti laskulle/hyvityslaskulle, mutta **Nimikkeen seurantarivit** -ikkuna ei salli sinun muuttaa sarja/eränumeroita - vain määriä voidaan muuttaa. Vain määriä voidaan muuttaa.  

1.  Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, kirjoita **Ostolaskut** ja valitse sitten aiheeseen liittyvä linkki.  
2.  Avaa ostolasku nimikkeille, jotka ostetaan sarja- tai eränumeroiden perusteella.  
3.  Valitse ostolaskun rivin **Rivit**-pikavälilehdessä **Hae vast.oton rivit** -toiminto.  
4.  Valitse **Hae vast.oton rivit** -ikkunassa vastaanottorivi, jolla on nimikkeen seurantarivejä, ja valitse sitten **OK**.  

    Lähdeasiakirja kopioidaan ostolaskulle uutena rivinä, ja sen nimikkeen seurantarivit kopioidaan alla olevalle **Nimikkeen seurantarivit** -ikkunaan.  

5.  Valitse ostolaskussa siirretty vastaanottorivi.  
6.  Voit tarkastella siirrettyjä nimikkeen seurantarivejä valitsemalla **Rivit**-pikavälilehdessä ensin **Rivit**-toiminto ja sitten **Nimikkeen seurantarivit** -toiminto.  

Kenttien sisältöä **Sarjanro****Eränro** ei voida muuttaa. Voit kuitenkin poistaa kokonaisia rivejä tai muuttaa määriä vastaamaan lähderivillä tehtyjä muutoksia.  

## <a name="to-reclassify-serial-or-lot-numbers"></a>Erä- tai sarjanumeroiden uudelleenluokittelu  
Nimikkeiden seurannan uudelleenluokittelu tarkoittaa erä- tai sarjanumeron muuttamista uudeksi erä- tai sarjanumeroksi tai vanhentumispäivämäärän muuttamista uudeksi vanhentumispäivämääräksi. Jos käsittelet eriä, voit myös yhdistää useita eriä yhdeksi eräksi. Voit suorittaa nämä tehtävät nimikkeen uudelleenluokituspäiväkirjassa.

1.  Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, kirjoita **Nimikkeen uudell.luokit. pvk** ja valitse sitten aiheeseen liittyvä linkki.  
2.  Täytä rivi asianmukaisilla tiedoilla. Lisätietoja on kohdassa [Toimintaohje: Varaston laskeminen, muuttaminen ja uudelleenluokitus](inventory-how-count-adjust-reclassify.md).
3.  Valitse **Nimikkeen seurantarivit** -toiminto.  
4.  Napsauta **Sarjanro**- tai **Eränro**-kentässä olevaa AssistButtonia ja valitse nykyinen sarja- tai eränumero.  
5.  Jos haluat syöttää uuden nimikeseurannan numeron, syötä se **Uusi sarjanro**- tai **Uusi eränro** -kenttään. Jos haluat, voit yhdistää eriä yhdeksi uudeksi tai olemassa olevaksi eräksi.  

    > [!NOTE]  
    >  Muista, että luokittelet uudelleen vanhenemispäivät, kohteet, joiden lähtevien tapahtumien vanhenemispäivämäärät ovat aikaisimmat, ehdotetaan ensin. Lisätietoja on kohdassa [FEFO-poiminta](warehouse-picking-by-fefo.md).  

5.  Jos haluat syöttää sarja- tai eränumerolle uuden vanhentumispäivämäärän, syötä se **Uusi vanhentumispvm** -kentässä.  

    > [!IMPORTANT]  
    >  Jos luokittelet erän uudelleen samalle eränumerolle eri vanhentumispäivämäärällä, koko erä on luokiteltava uudelleen käyttämällä vain yhtä nimikkeen uudelleenluokituspäiväkirjan riviä. Jos luokittelet uudelleen useita eriä yhdeksi uudeksi eräksi, sinun on syötettävä kaikille erille sama vanhentumispäivämäärä. Jos luokittelet yhden erän uudelleen toiseksi olemassa olevaksi eräksi, jolla on eri vanhentumispäivämäärä, sinun on käytettävä toisen erän vanhentumispäivämäärää. Jos jätät **Uusi vanhentumispvm** -kentän tyhjäksi, erä- tai sarjanumero luokitellaan uudelleen ilman vanhentumispäivämäärää.  

6.  Jos vanhalla sarja- tai eränumerolla on aiempia tietoja, voit kopioida ne uudelle sarja- tai eränumerolle.  

    1.  Valitse **Nimikkeen seurantarivit** -ikkunassa **Uuden sarjanumeron tiedot**- tai **Uuden eränumeron tiedot** -toiminto.  
    2.  Voit kopioida vanhan erä- tai sarjanumeron tiedot valitsemalla **Kopioi tiedot** -toiminnon.  
    3.  Valitse tietoluetteloikkunassa erä- tai sarjanumero, josta haluat kopioida, ja valitse sitten **OK**.  

7.  Jos haluat muokata erä- tai sarjanumeron olemassa olevia tietoja, voit tallentaa erä- tai sarjatietoja.  
8.  Kirjaamalla päiväkirjan voit linkittää uusitun nimikeseurannan numerot tai vanhentumispäivämäärät liitettyyn nimiketapahtumaan

## <a name="see-also"></a>Katso myös
[Nimikeseurannan nimikkeiden jäljittäminen](inventory-how-to-trace-item-tracked-items.md)   
[Vaihto-omaisuus](inventory-manage-inventory.md)  
[Rakennetiedot: Nimikkeen seuranta](design-details-item-tracking.md)
[Rakennetiedot: Nimikkeen seuranta ja varaukset](design-details-item-tracking-and-reservations.md)  
[Toimintaohje: Nimikkeiden varaaminen](inventory-how-to-reserve-items.md)  
[[!INCLUDE[d365fin](includes/d365fin_md.md)] -ohjelman käyttäminen](ui-work-product.md)

