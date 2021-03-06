---
title: "Vaihekuvaus – Tuotepakettien myynti, kokoaminen ja toimitus"
description: "Just-In-Time -varastoinnin ja kyvyn mukauttaa tuotteet asiakkaan vaatimusten mukaisiksi tukemiseksi kokoonpanotilauksia voidaan automaattisesti luoda ja linkittää heti kun myyntitilausrivi on luotu. Linkki myyntikysynnän ja kokoonpanotarjonnan välillä mahdollistaa myyntitilauksen käsittelijöille kokoonpanonimikkeen mukauttamisen sekä toimituspäivien lupaamisen osan saatavuuden mukaan. Lisäksi linkitetyn myyntitilauksen toimitukseen kirjataan automaattisesti kokoonpanon kulutus ja tuotos."
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
ms.openlocfilehash: 7cc4a50a981041d066e029da7e6a2666241e38eb
ms.contentlocale: fi-fi
ms.lasthandoff: 10/16/2017

---
# <a name="walkthrough-selling-assembling-and-shipping-kits"></a>Vaihekuvaus: pakettien myynti, kokoaminen ja toimitus
Jotta just-in-time-varastointia ja tuotteiden mukauttamista asiakkaan pyyntöjen mukaan voitaisiin tukea, kokoonpanotilaukset voidaan luoda ja linkittää automaattisesti heti, kun myyntitilausrivi on luotu. Linkki myyntikysynnän ja kokoonpanotarjonnan välillä mahdollistaa myyntitilauksen käsittelijöille kokoonpanonimikkeen mukauttamisen sekä toimituspäivien lupaamisen osan saatavuuden mukaan. Lisäksi linkitetyn myyntitilauksen toimitukseen kirjataan automaattisesti kokoonpanon kulutus ja tuotos.  

Erityinen toiminto koskee tilausta varten kokoonpantujen määrien toimitusta sekä perus- että edistyneissä fyysisen varaston määritystiedoissa. Kun kokoonpanon työntekijät saavat valmiiksi osien kokoamisen tai koko Kokoonpano tilausta varten -määrän, he tallentavat sen laajennetuissa määrityksissä **Toimitettava määrä** -kenttään ja valitsevat sitten **Kirjaa toimitus**. Tulos on, että vastaavan kokoonpanon tuotos kirjataan osien kulutuksen kanssa, ja linkitetylle myyntitilaukselle kirjataan toimitettu määrä. Tässä vaihekuvauksessa kuvataan laajennettu varastoprosessi.  

Kun fyysisen varaston perusmääritysten kokoonpano tilausta varten -määrä on toimitusvalmis, varastotyöntekijä kirjaa varastopoiminnan myyntitilausriveille. Tämä luo varastosiirron osille ja kirjaa kokoonpanon tuotoksen ja myyntitilauksen toimituksen. Lisätietoja on Varaston poiminta -ohjeaiheen kohdassa Kokoonpano tilausta varten -nimikkeiden käsitteleminen varaston poiminnoissa.  

## <a name="about-this-walkthrough"></a>Tietoja tästä vaihekuvauksesta  
Tässä vaihekuvauksessa käsitellään seuraavia tehtäviä:  

### <a name="setting-up-assembly-items"></a>Kokoonpanon nimikkeiden määrittäminen  
Kokoonpanon osat määrittää niiden täydennysjärjestelmä ja kokoonpanon tuoterakenne. Nimikkeen kokoonpanokäytäntö voi olla joko koonti tilauksesta (ATO) tai koonti varastoon (ATS). Tässä osassa käsitellään seuraavia tehtäviä:  

-   Sopivan täydennysjärjestelmän ja kokoonpanokäytännön määrittäminen uudelle nimikekortille.  
-   Kokoonpanon tuoterakenteen luominen, joka listaa kokoonpanon osat ja resurssin, joka siirtyy kokoonpanon nimikkeeseen.  

### <a name="selling-customized-assembly-items"></a>Mukautetun kokoonpanon nimikkeiden myynti  
[!INCLUDE[d365fin](includes/d365fin_md.md)]issa voi kirjata joustavasti sekä varastomäärän että Kokoonpano tilausta varten -määrän yhdelle myyntitilausriville. Tässä osassa käsitellään seuraavia tehtäviä:  

-   Puhtaan ATO-myyntitilausrivin luominen, jossa koko määrä ei ole käytettävissä ja on koottava ennen lähetystä.  
-   ATO-kohteiden mukauttaminen.  
-   Mukautetun kokoonpanonimikkeen yksikköhinnan laskeminen uudelleen.  
-   Yhdistelmämyyntitilausrivin luominen, jossa osa myyntimäärtästä tulee varastosta ja muu osa on koottava ennen toimitusta.  
-   Tietoja ATO:n saatavuusvaroituksista.  

### <a name="planning-for-assembly-items"></a>Kokoonpanon nimikkeiden suunnittelu  
Kokoonpanon kysynnän ja tarjonnan käsittelee suunnittelujärjestelmä, aivan kuten ostoa, siirtoa ja tuotantoa varten. Tässä osassa käsitellään seuraavia tehtäviä:  

-   Sellaisten nimikkeiden uudelleensuunnittelun suorittaminen, joiden kokoonpanotarjonnalla on myyntikysyntä.  
-   Kokoonpanotilauksen myyntirivin luominen tarpeen täyttämiseksi vaaditun toimituspäivämäärän mukaan.  

### <a name="assembling-items"></a>Nimikkeiden kokoonpano  
Kokoonpanotilaukset toimivat samalla tavoin kuin tuotantotilaukset, paitsi kulutus ja tuotos tallennetaan ja kirjataan suoraan tilauksesta. Kun kohteet on koottu varastoon, varastotyöntekijällä on täydet käyttöoikeudet kaikkiin otsikko- ja rivikenttiin. Kun nimikkeet on koottu tilaukseen, jossa määrä ja päivämäärä on luvattu asiakkaalle, tietyt kokoonpanotilauksen kentät eivät ole muokattavia. Tässä tapauksessa kokoonpanotoimitus suoritetaan linkitetyn myyntitilauksen fyysisen varastoinnin toimituksen mukaan. Tässä osassa käsitellään seuraavia tehtäviä.  

-   Kokoonpanon kulutuksen ja varastoon tuotoksen tallennus ja kirjaaminen.  
-   Varastoinnin toimitusrivin käyttäminen ATO-kokoonpanotilauksesta kokoonpanotyön kirjaamiseksi.  
-   ATO-kokoonpanotilauksen käyttäminen varastotoimitusriviltä automaattisesti kirjoitettujen tietojen arvioimiseksi.  

### <a name="shipping-assembly-items-from-stock-and-assembled-to-order"></a>Toimitetaan kokoonpanon nimikkeet varastosta ja kokoonpano tilausta varten  
Erityinen toiminto koskee tilausta varten kokoonpantujen määrien toimitusta. Tässä osassa käsitellään seuraavia tehtäviä:  

-   Varastoinnin poiminnan luominen, varastonimikkeiden kokoonpanolle ja kokoonpanon osille, jotka kootaan ennen lähetystä.  
-   Rekisteröidään fyysisen varastoinnin poiminnat kokoonpanokomponenteille ja sitten kokoonpanonimikkeille.  
-   Kokoonpanotilauksen käyttäminen varastotoimituksesta poimittujen tai kulutettujen osien arvioimiseksi.  
-   Toimitetaan kokoonpano tilausta varten -määrät.  
-   Toimitetaan kokoonpanon varastonimikkeitä.  

## <a name="roles"></a>Roolit  
Tässä vaihekuvauksessa havainnollistetaan seuraavien käyttäjäroolien tehtäviä:  

-   myyntitilausten käsittelijä  
-   Suunnittelija  
-   Kokoonpanotyöntekijä  
-   Valitsin  
-   Toimitusvastaava  

## <a name="prerequisites"></a>Vaatimukset  
Tee seuraavat toimet ennen tämän vaihekuvauksen tehtävien suorittamista:  

-   Asenna [!INCLUDE[d365fin](includes/d365fin_md.md)].  
-   Tee itsestäsi fyysisen varaston työntekijä VALKOISESSA sijainnissa tekemällä seuraavat toimet:  

1.  Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, kirjoita **Varaston työntekijät** ja valitse sitten aiheeseen liittyvä linkki.  
2.  Valitse ensin **Käyttäjätunnus**-kenttä ja valitse oma käyttäjätilisi **Käyttäjät**-ikkunassa.  
3.  Kirjoita **Sijaintikoodi**-kenttään VALKOINEN.  
4.  Valitse **Oletus**-kenttä.  

Valmistele VALKOINEN-sijainti kokoonpanon käsittelyä varten seuraavasti:  

1.  Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, kirjoita **Sijainnit** ja valitse sitten aiheeseen liittyvä linkki.  
2.  Avaa sijaintikortti VALKOINEN-sijaintia varten.  
3.  Anna **W-10-0001** **Varastopaikat**-pikavälilehden **Kokoonpanoon-varastop.koodi**-kentässä.  

    Syöttämällä tämän ei-poiminta-varastopaikkakoodin kokoonpanotilauksen kaikki rivit ovat valmiina vastaanottamaan niiden osat varastopaikassa.  

4.  Anna **Kokoonpanosta-varastop.koodi**-kentässä **W-01-0001**.  

    Syöttämällä tämän poimintavarastopaikkakoodin, valmiit kokoonpannut nimikkeet siirretään varastopaikkaan.  

Poista sisäisten prosessien oletusläpimenoaika seuraavasti:  

1.  Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, kirjoita **Tuotannon asetukset** ja valitse sitten aiheeseen liittyvä linkki.  
2.  Poista **Tuotannon asetukset** -ikkunan **Suunnittelu**-pikavälilehden **Oletus toimitusajan varmistus** -kentän arvo.  

Luo varasto kokoonpanon osille noudattamalla näiden vaihekohtaisten ohjeiden osaa "Esimerkkitietojen valmisteleminen".  

## <a name="story"></a>Taustatietoja  
23. tammikuuta myyntitilausten käsittelijä Sanna ottaa Laitekauppa-yritykseltä tilauksen kolmesta tuotepaketti B:stä, joka on ATO-nimike. Kaikki kolme yksikköä on mukautettu, ja niissä on oltava tehokas grafiikkakorttti ja ylimääräistä RAM-muistia. Levyasemat päivitetään DVD-asemiksi, koska CD-asemia ei ole saatavilla. Sanna tietää, että yksiköt voidaan koota heti, joten hän jättää ehdotetuksi toimituspäiväksi tammikuun 23. päivän.  

Samaan aikaan asiakas tilaa 15 yksikköä sarjaa A erityispyynnöllä, jonka mukaan viisi yksikköä mukautetaan tehokkaammalla grafiikkakortilla. Vaikka sarja A Kit on yleensä kokoonpano varastoon -nimike, tilausten käsittelijä yhdistää myyntirivimäärät myydäkseen kymmenen yksikköä varastosta ja kootakseen viisi mukautettua yksikköä tilaukseen. Sarjan A kymmenen yksikköä eivät ole käytettävissä ja kokoonpanotilauksen pitää toimittaa ne ensin varastoon nimikkeen kokoonpanokäytännön mukaisesti. Sanna kuulee kokoonpano-osastolta, että A-sarjan yksiköitä ei voida saada kuluvan viikon aikana valmiiksi. Hän asettaa yhdistelmä-ATO:n ja varaston määrän kohdalle toisen myyntitilausrivin toimituspäivämääräksi 27. tammikuuta ja ilmoittaa asiakkaalle, että paketti A:n 15 yksikköä toimitetaan neljä päivää paketti B:n kolmen yksikön jälkeen. Sanna ilmoittaa lähetysosastolle, että tämä myyntitilaus edellyttää kokoonpanon käsittelyä. Hän luo fyysisen varastoinnin toimituksen asiakirjan myyntitilauksesta.  

Suunnittelija Eduardo ajaa suunnittelutyökirjan ja luo kokoonpanotilauksen kymmenelle paketin A vakioyksikölle, jonka sisäinen eräpäivä on 27. tammikuuta.  

Sammy, joka on vastuussa toimituksesta, saa kolme fyysisen varastoinnin toimitusriviä myyntitilaukselle: yksi rivi kolmelle ATO-yksikölle, yksi rivi viidelle ATO-yksikölle yhdistelmämyyntitilausriville ja yksi rivi kymmenelle ATS-yksikölle yhdistelmämyyntitilausrivillä. Hän luo fyysisen varastoinnin poiminta-asiakirjan kaikista kokoonpanon komponenteista, jotka vaaditaan fyysisen varastoinnin toimituksen asiakirjan kahdeksan ATO-yksikön kokoonpanoa varten.  

Joakim, poimija, hakee osat kaikkia fyysisen varastoinnin toimituksen asiakirjassa olevia ATO-määriä varten ja tuo ne kokoonpanoalueelle. Hän syöttää käsiteltävän määrän ja rekisteröi fyysisen varastoinnin poiminnan.  

Linda kokoaa paketti B:n kolme ATO-yksikköä. Osat on jo poimittu, eikä hän tallenna tuotos- ja kulutusmääriä eikä kirjaa tilausta, koska molemmat näistä toimista suoritetaan automaattisesti vastaavan fyysisen varastoinnin toimitusriveillä.  

Sammy tallentaa fyysisen varastoinnin toimitusrivin kokoonpannun määrän ja kirjaa kolmen Kit B -yksikön toimituksen. Ensimmäinen myyntitilauksen rivi päivitetään toimituksen yhteydessä. Linkitetty kokoonpanotilaus pysyy avoimena, kunnes myyntitilaus on täysin laskutettu. Kaksi fyysisen varastoinnin toimitusriviä yksikölle A, yksi ATO ja yksi ATS, joiden eräpäivät ovat 27.1., jäävät avoimiksi.  

Linda käsittelee 27.1. kaksi tuotepakettia A koskevaa kokoonpanotilausta. Ensimmäinen tilaus on viiden yksikön ATO-tilaus, jonka hän käsittelee eri tavalla kuin 23.1. käsitellyn tuotepaketin B ATO-tilauksen. Hänelle on valtuudet käyttää tässä tilauksessa itse varaston toimitusriviä valmistuneen kokoonpanotyön kirjaamiseen. Tarvittavat osat ovat valmiina kokoonpano-osastolla, koska ne on poimittu yhdessä B-tuotepaketin osien kanssa.  

Toinen kokoonpanotilaus on suunnittelujärjestelmän luoma ATS-tilaus kymmenestä yksiköstä. Tässä ATS-tilauksessa Linda suorittaa kaikki siihen liittyvät toiminnot kokoonpanotilauksesta. Hän luo fyysisen varastoinnin poiminta-asiakirjan kokoonpanon osille, joita tarvitaan kymmenen yksikön kokoamista varten. Kun tietokoneet on yhdistetty, Linda kirjaa kokoonpanotilauksen ja ilmoittaa näin, että nimikkeet ovat käytettävissä varastossa ja ne voi kerätä toimitusta varten.  

Sammy luo varaston noutoasiakirjan kaikille määrille, jotka ovat jäljellä ennen kuin fyysisen varaston toimitus voidaan kirjata. Poiminta-asiakirja luodaan kymmenelle yksikölle sarjaa A, joka on juuri valmis. Viiden tilatun A-paketin kokoamiseen vaaditut osat on poimittu 23. tammikuuta.  

Joakim tuo sarjan A kymmenen yksikköä fyysisestä varastosta määritetylle toimitusalueelle, tallentaa käsiteltävän määrän ja rekisteröi poiminnan.  

Sammy pakkaa kymmenen ATS-yksikköä viidellä ATO-yksiköllä, jotka Linda kokosi aikaisemmin. Hän täyttää toimitettavan määrän molempiin riveihin ja kirjaa sitten viimeisen toimituksen Laitekauppaan. Viittä A-sarjan yksikköä koskeva kokoonpanotilaus kirjataan automaattisesti. Myyntitilauksen toinen rivi päivitetään toimitetuksi. Kaksi linkitettyä kokoonpanotilausta pysyy avoimena, kunnes myyntitilaus on laskutettu ja suljettu.  

Kun myyntitilaus on myöhemmin kirjattu kokonaan laskutetuksi, myyntitilaus ja linkitetyt kokoonpanotilaukset poistetaan.  

## <a name="setting-up-the-sample-data"></a>Esimerkkitietojen määrittäminen  

1.  Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, kirjoita **F. var. nimikepvk:t** ja valitse sitten aiheeseen liittyvä linkki.  
2.  Valitse **Erän nimi** -kenttä, ja valitse sitten oletuspäiväkirja.  
3.  Luo positiiviset varastomuutokset sijainnissa VALKOINEN, käsittelypäivänä 23. tammikuuta, kirjoittamalla seuraavat tiedot.  

    |**Nimikkeen nro**|**Alueen koodi**|**Varastopaikan koodi**|**Määrä**|  
    |-----------------------------------|---------------------------------------|--------------------------------------|------------------------------------|  
    |80001|POIMINTA|W-01-0001|20|  
    |80005|POIMINTA|W-01-0001|20|  
    |80011|POIMINTA|W-01-0001|20|  
    |80014|POIMINTA|W-01-0001|20|  
    |80203|POIMINTA|W-01-0001|20|  
    |80209|POIMINTA|W-01-0001|20|  

4.  Valitse **Kotisivu**-välilehden **Rekisteröinti**-ryhmässä **Rekisteröi poiminta** ja valitse sitten **Kylllä**.  

    Synkronoi seuraavaksi uuden fyysisen varastoinnin tapahtumat varaston kanssa.  

5.  Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, kirjoita **Nimikepäiväkirjat** ja valitse sitten aiheeseen liittyvä linkki. **Nimikepäiväkirja**-ikkuna avautuu.  
6.  Valitse **Toiminnot**-välilehden **Funktiot**-ryhmässä **Laske f.var. muutos**.  
7.  Valitse **Laske f. var. muutos** -ikkunassa **OK**.  
8.  Valitse **Nimikepäiväkirja**-ikkunan **Toiminnot**-välilehden **Toiminnot**-ryhmässä **Kirjaa** ja valitse sitten **Kyllä**.  

### <a name="creating-the-assembly-items"></a>Kokoonpanon nimikkeiden luominen  

1.  Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, kirjoita **Nimikkeet** ja valitse sitten aiheeseen liittyvä linkki.  
2.  Valitse **Kotisivu**-välilehden **Hallinta**-ryhmässä **Uusi**.  
3.  Luo ensimmäinen kokoonpanonimike seuraavien tietojen perusteella.  

    |Kenttä|Arvo|  
    |---------------------------------|-----------|  
    |**Kuvaus**|Tuotepaketti A – perus-PC|  
    |**Perusmittayksikkö**|PCO|  
    |**Nimikeluokan koodi**|Sekalainen|  
    |**Täydennysjärjestelmä**|Kokoonpano|  
    |**Kokoonpanokäytäntö**|Koota ja-kaluston|  
    |**Uusintatilaustapa**|Erä-erästä|  

    > [!NOTE]  
    >  Kokoonpanossa varastoon toimitetaan yleensä tuotepaketti A, ja siinä on uusintatilaustapa, jotta se voidaan tehdä osaksi yleistä toimitusten suunnittelua.  

4.  Valitse **Navigoi**-välilehden **Kokoonpano/tuotanto**-ryhmässä **Kokoonpano** ja valitse sitten **Kokoonpanon tuoterakenne**.  
5.  Määrittää kokoonpanon tuoterakenteen paketille A seuraavilla tiedoilla.  

    |**Tyyppi**|**Nro**|**Määrä per**|  
    |-------------------------------|------------------------------|---------------------------------------|  
    |Vaihtoehto|80001|1|  
    |Vaihtoehto|80011|1|  
    |Vaihtoehto|80209|1|  
    |Resurssi|Leea|1|  

6.  Luo toinen kokoonpanonimike seuraavien tietojen perusteella.  

    |Kenttä|Arvo|  
    |---------------------------------|-----------|  
    |**Kuvaus**|Tuotepaketti B – Ammatti-PC|  
    |**Perusmittayksikkö**|PCO|  
    |**Nimikeluokan koodi**|Sekalainen|  
    |**Täydennysjärjestelmä**|Kokoonpano|  
    |**Kokoonpanokäytäntö**|Kokoonpano tilausta varten|  

    > [!NOTE]  
    >  Kokoonpanossa tilauksen mukaan toimitetaan yleensä tuotepaketti B, eilkä siinä ole uusintatilaustapaa, koska se ei ole osa yleistä toimitusten suunnittelua.  

7.  Valitse **Navigoi**-välilehden **Kokoonpano/tuotanto**-ryhmässä **Kokoonpano** ja valitse sitten **Kokoonpanon tuoterakenne**.  
8.  Määritä kokoonpanon tuoterakenne paketille B seuraavilla tiedoilla.  

    |**Tyyppi**|**Nro**|**Määrä per**|  
    |-------------------------------|------------------------------|---------------------------------------|  
    |Vaihtoehto|80005|1|  
    |Vaihtoehto|80014|1|  
    |Vaihtoehto|80210|1|  
    |Resurssi|Leea|1|  

### <a name="selling-the-assembly-items"></a>Kokoonpanon nimikkeiden myynti  

1.  Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, kirjoita **Myyntitilaukset** ja valitse sitten aiheeseen liittyvä linkki.  
2.  Valitse **Kotisivu**-välilehden **Hallinta**-ryhmässä **Uusi**.  
3.  Luo kaksi myyntitilausriviä asiakkaalle 62000, Laitekauppa, käsittelypäivänä seuraavilla tiedoilla.  

    |**Tyyppi**|**Kuvaus**|**Määrä**|Kokoonpantava määrä tilausta varten|Lähetyksen pvm|  
    |--------------|---------------------|------------------|-------------------------------|-------------------|  
    |Nimike|Tuotepaketti B – Ammatti-PC|3|3|Tammikuu 23|  
    |Nimike|Tuotepaketti A – perus-PC|15|5|27. tammikuuta|  

    > [!NOTE]  
    >  B-sarjan myyntitilausrivillä on seuraava saatavuusongelma:  
    >   
    >  -   Kokoonpano-osaa 80210 ei ole käytettävissä. Tämä tarkoittaa, että tuotepaketin B kolmea määritettyä yksikköä ei voi koota, minkä osoittaa **0** **Kokoonpanon saatavuus**-ikkunan **Mahdollista koota** -kentässä.  
    >   
    >  A-sarjan myyntitilausrivillä on seuraava saatavuusongelma:  
    >   
    >  -   Sarjan A kymmenen yksikköä eivät ole käytettävissä. Tämä kertoo suunnittelujärjestelmälle, että määrä täytyy koota varastoon.  

    Mukauta seuraavaksi myyntitilausta.  

4.  Valitse myyntitilausrivi kolmelle B-sarjan yksikölle.  
5.  Valitse ensin **Rivit**-pikavalintalehdessä **Rivi**, sitten **Kokoonpano tilausta varten** ja lopuksi **Kokoonpano tilausta varten -rivit**.  
6.  Anna **Kokoonpano tilausta varten -rivit** -ikkunan **Määrä per** -kentässä nimikkeen 80114 kokoonpanon tilausrivillä arvo **2**.  
7.  Valitse nimikkeen 80210 kokoonpanon tilausrivillä **Nro** -kenttä ja valitse sen sijaan nimike 80209.  
8.  Luo uusi kokoonpanotilaus, jolla on seuraavat tiedot.  

    |Tyyppi|Nro|Määrä per|  
    |----------|---------|------------------|  
    |Vaihtoehto|80203|1|  

9. Sulje **Kokoonpano tilausta varten -rivit** -ikkuna.  

    Päivitä seuraavaksi paketin B yksikköhinta juuri suorittamasi mukautuksen mukaan. Huomaa nykyinen arvo kentässä **Yksikköhinta Ilman ALV**.  

10. Valitse **Rivit**-pikavalintalehdessä **Rivi**, valitse **Kokoonpano tilausta varten** ja valitse sitten **Vyörytä hinta**.  
11. Valitse **Kyllä**-painike. Huomaa suurentunut arvo kentässä **Yksikköhinta Ilman ALV**.  
12. Valitse myyntitilausrivi viidelletoista A-sarjan yksikölle.  
13. Valitse ensin **Rivit**-pikavalintalehdessä **Rivi**, sitten **Kokoonpano tilausta varten** ja lopuksi **Kokoonpano tilausta varten -rivit**.  
14. Luo **Kokoonpano tilausta varten -rivit** -ikkunassa uusi kokoonpanotilauksen rivi, jolla on seuraavat tiedot.  

    |Tyyppi|Nro|Määrä per|  
    |----------|---------|------------------|  
    |Nimike|80203|1|  

     Muuta seuraavaksi toisen myyntitilausrivin toimituspäivämäärä kokoonpanon aikataulun mukaisesti.  

15. Anna tuotepaketin A 15 yksikön myyntitilausrivillä **Toimituspvm** -kenttään arvo **27.1.2014**.  
16. Valitse **Toiminnot**-välilehden **Vapauta**-ryhmässä **Vapauta**.  
17. Valitse **Toiminnot**-välilehden **Fyysinen varasto** -ryhmässä **Luo f. var. toimitus**.  
18. Sulje myyntitilaus.  

### <a name="planning-for-the-unavailable-ats-items"></a>Ei käytettävissä olevien ATS-nimikkeiden suunnittelu  

1.  Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, kirjoita **Suunnittelutyökirja** ja valitse sitten aiheeseen liittyvä linkki.  
2.  Valitse **Toiminto**-välilehden **Funktiot**-ryhmässä **Laske uudelleensuunnittelu**.  
3.  Määritä **Laske suunnitelma** -ikkunassa seuraavat suodattimet.  

    |Aloituspvm|Lopetuspvm|Nro|  
    |-------------------|-----------------|---------|  
    |23.1.2014|27.1.2014|Tuotepaketti A – perus-PC|  

4.  Valitse **OK**-painike.  

    Tarvittavalle kymmenen yksikön kokoonpanotilaukselle luodaan uusi suunnittelurivi, jonka eräpäivä on 27.1. Sitä ei tarvitse muuttaa, joten voit nyt luoda tilauksen.  

5.  Valitse **Toiminnot**-välilehden **Funktiot**-ryhmässä **Toteuta toimenpideviesti**.  
6.  Valitse **Toteuta toim.pideviesti** -ikkunan **Kokoonpanotilaus**-kentässä ja valitse sitten **Tee kokoonpanotilaukset**.  
7.  Valitse **OK**-painike.  

### <a name="assembling-and-shipping-the-first-ato-quantity"></a>Ensimmäisen ATO-määrän kokoaminen ja toimitus  

1.  Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, anna **F.var. toimitus** ja valitse sitten aiheeseen liittyvä linkki.  

    > [!NOTE]  
    >  Tässä osassa toimituksesta vastaava henkilö tallentaa valmiin ATO-kokoonpanotyön fyysisen varaston toimitusriville. Tämä työnkulku voi ilmetä ympäristöissä, joissa kokoonpanotyön suorittaa henkilö, joka on vastuussa toimituksesta tai toimitusalueen kokoajat.  
    >   
    >  Tässä osassa kokoonpanotilauksen toiminnot suoritetaan epäsuorasti fyysisen varaston toimitusriviltä. Lisätietoja kokoonpanotilauksen käsittelystä suoraan on tämän vaihekuvauksen Nimikkeiden kokoonpano varastoon -osassa.  

2.  Avaa viimeisimmän fyysisen varastoinnin toimitus, joka on luotu VALKOINEN-sijainnissa.  

    Huomaa kolme fyysisen varastoinnin riviä: Yksi rivi on varattu tuotepaketin B ATO-määrälle, jonka eräpäivä on 23.1. Yksi rivi on varattu tuotepaketin A ATO-määrälle, jonka eräpäivä on 27.1. Yksi rivi on varattu tuotepaketin A varastosaldolle, jonka eräpäivä on 27.1.  

    Kokoonpanomenetelmä määritetään **Kokoonpano tilausta varten** -kentässä.

    Luo seuraavaksi poiminta-asiakirja kaikkia ATO-kokoonpanon-osia varten, joita tarvitaan fyysisen varastoinnin toimituksessa.  

3.  Valitse **Toiminnot**-välilehden **Funktiot**-ryhmässä **Luo poiminta** ja valitse sitten **OK**.  

    Suorita seuraavaksi poimijan tehtävä.  

4.  Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, kirjoita **Poiminnat** ja valitse sitten aiheeseen liittyvä linkki.  
5.  Avaa varaston poiminta-asiakirja, jonka loit tämän osan vaiheessa 3.  

    Huomaa **Lähdeasiakirja**-kentän arvo ja että kaikki poimintarivit ovat kokoonpanon komponenteille.  

    Rekisteröi seuraavaksi poiminta muuttamatta oletustietoja.  

6.  Valitse **Toiminnot**-välilehden **Funktiot**-ryhmässä **Täytä autom. käsiteltävä määrä**.  
7.  Valitse **Kotisivu**-välilehden **Rekisteröinti**-ryhmässä **Rekisteröi poiminta**.  

    Palaa toimitustehtävien suorittamiseen.  

8.  Avaa **F.var. toimitusrivit** -ikkuna.  

    Huomaa, että **Määrä poimittu** -kenttä on edelleen tyhjä kaikilla riveillä. Tämä johtuu siitä, että edelleenkään ei ole poimittu toimitettavia nimikkeitä, vaan pelkästään osia, jotka tarvitaan ATO-määrien kokoamiseen.  

    Siirry liittyvän kokoonpanotilauksen tarkistukseen.  

9. Valitse toimitusrivi kolmelle B-sarjan yksikölle.  
10. Valitse **Rivit**-pikavälilehdessä **Rivi** ja valitse sitten **Kokoonpano tilausta varten**. **Kokoonpanotilaus** -ikkuna avautuu.  

    Huomaa, että monet kokoonpanotilauksen kentät eivät ole käytettävissä, koska tilaus on linkitetty myyntitilaukseen.  

    Huomaa kokoonpanotilauksen riveillä, että **Määrä poimittu**-kenttä on täytetty. Tämä johtuu poiminnasta, joka rekisteröitiin tämän osan vaiheessa 7.  

11. Yritä antaa **Kokoonpantava määrä** -kentässä arvo, joka on pienempi kuin **3**.  

    Lue virhesanoma, joka selittää, miksi tämän kentän voi täyttää vain liittyvän toimituksen **Toimitettava määrä** -kentän kautta.  

    **Kokoonpantava määrä** -kenttää voi muokata sitä varten, jos haluat toimittaa suoraan varastosta uusien nimikkeiden kokoamisen sijaan. Lisätietoja on ohjeaiheen [Tietoja Kokoonpano tilausta varten- tai Kokoonpano varastoon -toiminnoista](assembly-assemble-to-order-or-assemble-to-stock.md) kohdassa Skenaarioiden yhdistelmä.  

12. Palaa **F.var. toimitus** -ikkunaan sulkemalla **Kokoonpanotilaus**-ikkuna.  
13. Anna tuotepaketin B kolmen yksikön toimitusrivillä **Toimitettava määrä** -kenttään **3**.  
14. Valitse **Toiminnot**-välilehden **Kirjaus**-ryhmässä **Kirjaa toimitus** ja valitse sitten **Toimita**.  

    Tämän fyysisen varastoinnin toimituksen kirjaamisen myötä kirjataan liittyvän kokoonpanotilauksen koko kulutus- ja tuotantomäärät ja **Jäljellä oleva määrä** -kenttä on tyhjä. B-sarjan myyntitilausrivi päivitetään näyttämään, että kolme yksikköä on toimitettu.  

    Varastoaktiviteetit täyttämään ensimmäisen myyntitilausrivin tammikuun 23. päivään mennessä on saatu valmiiksi. Täytä seuraavaksi myyntitilausrivit, jotka toimitetaan 27. tammikuuta.  

### <a name="assembling-and-recording-the-second-ato-quantity"></a>Toisen ATO-määrän kokoonpano ja tallentaminen  

1.  Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, kirjoita **Kokoonpanotilaukset** ja valitse sitten aiheeseen liittyvä linkki.  

    Huomaa, että tuotepaketin B toimitettujen yksiköiden ATO-tilaus on edelleen luettelossa, vaikka **Jäljellä oleva määrä** on tyhjä. Tämä johtuu siitä, että linkitettyä myyntitilausta ei ole vielä laskutettu kokonaan.  

    > [!NOTE]  
    >  Tässä osassa kokoonpanotyöntekijä tallentaa valmiin ATO-kokoonpanotyön fyysisen varaston toimitusriville. Tämä työnkulku voi ilmetä ympäristöissä, joissa kokoonpanotyö suoritetaan eri kokoonpano-osastolla ja kokoajilla on oikeus muuttaa fyysisen varaston toimitusriviä.  

2.  Avaa ATO-kokoonpanotilaus tuotepaketin A viiden yksikön tilausta varten.  

    Huomaa, että **Kokoonpantava määrä**- ja **Kulutettava määrä** -kentät ovat tyhjiä, koska yhtään työtä ei ole vielä kirjattu.  

    Huomaa kokoonpanotilauksen riveillä, että **Määrä poimittu**-kenttä on täytetty. Tämä johtuu poiminnasta, joka rekisteröitiin 23.1.  

    Tallenna seuraavaksi kokoonpanotilaus on valmiiksi.  

3.  Valitse **Navigoi**-välilehden **Fyysinen varasto** -ryhmässä **Kokoonpano tilausta varten: f. var. toimitusrivi**.  
4.  Anna **Kokoonpano tilausta varten: f. var. toimitusrivi** -ikkunan **Toimitettava määrä** -kentässä arvo **5** ja sulje sitten ikkuna.  

    Huomaa **Kokoonpanotilaus**-ikkunassa, että **Kokoonpantava määrä**- ja **Kulutettava määrä** -kentät on nyt täytetty toimitukseen kirjatuilla tuotos- ja kulutusmäärillä, jotka kirjataan toimitukseen.  

5.  Sulje **Kokoonapnotilaus** -ikkuna.  

### <a name="assembling-the-ats-quantity"></a>ATS-määrän kokoonpano  

1.  Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, kirjoita **Kokoonpanotilaukset** ja valitse sitten aiheeseen liittyvä linkki.  
2.  Avaa kokoonpanotilaus tuotepaketin A kymmenen yksikön tilausta varten.  

    Huomaa, että **Kokoonpantava määrä** -kenttään on täytetty oletettu määrä.  

    Luo seuraavaksi poiminta-asiakirja tarvittavien osien hakua varten.  

3.  Valitse **Toiminnot**-välilehden **Vapauta**-ryhmässä **Vapauta**.  
4.  Valitse **Toiminnot**-välilehden **Fyysinen varasto** -ryhmässä **Luo f.var. poiminta** ja valitse sitten **OK**.  

    Suorita seuraavaksi poimijan tehtävä.  

5.  Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, kirjoita **Poiminnat** ja valitse sitten aiheeseen liittyvä linkki.  
6.  Avaa varaston poiminta-asiakirja, jonka loit tämän osan vaiheessa 4.  

     Rekisteröi rekisteröimään poiminta muuttamatta oletustietoja.  

7.  Valitse **Toiminnot**-välilehden **Funktiot**-ryhmässä **Täytä autom. käsiteltävä määrä**.  
8.  Valitse **Kotisivu**-välilehden **Rekisteröinti**-ryhmässä **Rekisteröi poiminta**.  

    Palaa kokoonpanotilaukseen ja suorita viimeinen kokoonpanotehtävä.  

9. Valitse **Kokoonpanotilaus**-ikkunan **Toiminnot**-välilehden **Kirjaus**-ryhmässä **Kirjaa** ja valitse sitten **Kyllä**.  

    Huomaa, että kokoonpanotilaus poistetaan avoimien tilausten luettelosta.  

### <a name="shipping-the-remaining-items-partly-from-stock-and-partly-assembled-to-the-order"></a>Toimitetaan jäljellä olevat nimikkeet osittain varastosta ja osittain kootaan tilausta varten  

1.  Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, anna **F.var. toimitus** ja valitse sitten aiheeseen liittyvä linkki.  
2.  Avaa viimeisimmän fyysisen varastoinnin toimitus, joka on luotu VALKOINEN-sijainnissa.  

    Huomaa tuotepaketin A kymmenen yksikön rivillä, että **Toimitettava määrä**- ja **Määrä poimittu** -kentät ovat tyhjiä.  

    Poimi seuraavaksi jäljellä olevat nimikkeet.  

3.  Valitse **Toiminnot**-välilehden **Toiminnot**-ryhmässä **Luo poiminta** ja valitse sitten **OK**.  

    Suorita seuraavaksi poimijan viimeinen tehtävä tätä fyysisen varastoinnin toimitusta varten.  

4.  Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, kirjoita **Poiminnat** ja valitse sitten aiheeseen liittyvä linkki.  
5.  Avaa varaston poiminta-asiakirja, jonka loit tämän osan vaiheessa 3.  

    Huomaa, että tämä poiminta-asiakirja on kokoonpanon nimikettä varten, ei kokoonpanon komponentteja varten.  

    Rekisteröi seuraavaksi poiminta muuttamatta oletustietoja.  

6.  Valitse **Toiminnot**-välilehden **Funktiot**-ryhmässä **Täytä autom. käsiteltävä määrä**.  
7.  Valitse **Kotisivu**-välilehden **Rekisteröinti**-ryhmässä **Rekisteröi poiminta** ja valitse sitten **Kylllä**.  

    Palaa varastotoimitukseen ja suorita viimeinen kokoonpanotehtävä.  

8.  Avaa **F.var. toimitus** -ikkuna.  

    Huomaa, että **F.var. toimitus** -ikkunan tuotepaketin A kymmenen yksikön rivin **Toimitettava määrä**- ja **Määrä poimittu** -kenttien arvo on nyt **10**.  

9. Valitse **Toiminnot**-välilehden **Kirjaus**-ryhmässä **Kirjaa toimitus** ja valitse sitten **Toimita**.  

    Fyysisen varastoinnin toimituksen asiakirja poistetaan, mikä ilmaisee, että asiaan liittyvät varastotoiminnot on suoritettu. Varmista seuraavaksi, että myyntitilaus on käsitelty.  

10. Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, kirjoita **Ostotilaukset** ja valitse sitten aiheeseen liittyvä linkki.  
11. Avaa myyntitilaus Laitekauppa-yritystä varten.  

    Huomaa, että **Toimitettu määrä** -kenttä sisältää täyden määrän kummallakin rivillä.  

    Kun Laitekauppa maksaa 18 CRONUKSELTA vastaanotettua tietokonetta, myyntitilaus ja sen linkitetyt kokoonpanotilaukset poistetaan.  

## <a name="see-also"></a>Katso myös  
 [Tietoja Kokoonpano tilausta varten- ja Kokoonpano varastoon -toiminnoista](assembly-assemble-to-order-or-assemble-to-stock.md)   
 [Nimikkeiden kokoaminen](assembly-how-to-assemble-items.md)   
 [Nimikkeiden poiminta fyysisen varastoinnin toimitusta varten](warehouse-how-to-pick-items-for-warehouse-shipment.md)   
 [Kokoonpano tilausta varten -nimikkeiden myyminen](assembly-how-to-sell-items-assembled-to-order.md)   
 [Nimikkeiden kokoaminen](assembly-how-to-assemble-items.md)   
 [Rakennetiedot: kokoonpanotilauksen kirjaus](design-details-assembly-order-posting.md)   
 [Rakennetiedot: sisäisen fyysisen varastoinnin virta](design-details-internal-warehouse-flows.md)   
 [Rakennetiedot: lähtevän fyysisen varastoinnin virta](design-details-outbound-warehouse-flow.md)   
 [Vaihekuvaus: Toimitusten automaattinen suunnittelu](walkthrough-planning-supplies-automatically.md)

