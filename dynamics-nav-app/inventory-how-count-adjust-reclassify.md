---
title: Varaston laskeminen, muuttaminen ja uudelleenluokitus
description: "Ohjeaiheessa kerrotaan, miten nimiketapahtumien tai varastotapahtumien inventointi suoritetaan, tehdään negatiivisia tai positiivisia oikaisuja ja muutetaan tietoja, kuten sijaintia tai erän numeroa."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: adjustment, negative, positive, increase, decrease
ms.date: 08/16/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 4d53e6e9b64e0f5c790abb0f62f66a2b28c12c50
ms.contentlocale: fi-fi
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-count-adjust-and-reclassify-inventory"></a>Varaston laskeminen, muuttaminen ja uudelleenluokitus
Vähintään kerran tilikauden aikana tulee suorittaa inventointi (eli laskea kaikki varastossa olevat nimikkeet), jotta nähtäisiin, onko tietokantaan rekisteröity määrä sama kuin varaston fyysinen määrä. Kun varaston fyysinen määrä on tiedossa, se on kirjattava pääkirjanpitoon osana kauden lopun varaston arvostusta.

Vaikka lasket kaikki varaston nimikkeet vähintään kerran vuodessa, voit päättää laskevasi joitain nimikkeitä useammin, koska ne ovat ehkä arvokkaampia tai ne liikkuvat nopeasti varastosta ja ovat suuri osa liiketoimintaa. Voit määrittää tätä varten erityisiä laskentajaksoja. Lisätietoja on kohdassa Inventoinnin suorittaminen.

Jos kirjattuja varastomääriä pitää muuttaa laskennan yhteydessä tai muita tarkoituksia varten, inventointitapahtumia voi muuttaa suoraan nimikepäiväkirjan avulla liiketoimintatapahtumia kirjaamatta. Vaihtoehtoisesti voit muuttaa yhden nimikkeen nimikekortissa.

Jos sekä nimiketapahtumien määritteitä että määriä pitää muuttaa, voidaan käyttää nimikkeen uudelleenluokituspäiväkirjaa. Tyypillisiä uudelleenluokiteltavia määritteitä ovat sarja- ja eränumerot, vanhentumispäivämäärät ja dimensiot.

> [!NOTE]
> Laajennetussa varastointimäärityksessä nimikkeet rekisteröidään varastopaikoissa nimiketapahtumien sijaan fyysisen varastoinnin tapahtumina. Niinpä laskenta, muutokset ja uudelleenluokittelu tehdään tavarapaikkoja tukevissa erityisissä fyysisen varastoinnin päiväkirjoissa. Voit sitten synkronoida uudet tai muuttuneet fyysisen varastoinnin tapahtumat erityistoiminnoilla tapahtumiin liittyviin nimeketapahtumiin siten, että vastaavat varaston määrissä ja arvoissa tapahtuneita muutoksia. Tätä käsitellään tarvittaessa jäljempänä olevissa toimenpidekuvauksissa.

## <a name="to-perform-a-physical-inventory"></a>Inventoinnin suorittaminen
Sinun tulee tehdä inventointi (eli laskea saatavilla olevat nimikkeet) nähdäksesi, onko ohjelmaan rekisteröity määrä sama kuin varaston fyysinen määrä, tilikauden lopussa ellei useamminkin. Jos löytyy eroja, ne tulee kirjata nimiketileille ennen varaston arvostusta.

Fyysisen laskentajakson lisäksi täydellinen prosessi käsittää seuraavat kolme tehtävää:

- Laske oletettu varasto.
- Tulosta raportti, jota käytetään laskennassa.
- Syötä ja kirjaa todellinen laskettu varasto.

Voit tehdä inventoinnin jommallakummalla tavalla fyysisen varastoinnin asetusten mukaan. Lisätietoja on kohdassa [Varastoinninhallinnan määrittäminen](warehouse-setup-warehouse.md).  

-   Jos ohjattu hyllytys ja poiminta ei ole käytössä sijainnissa (varastoinnin perusmääritys), käytä **Varastopäiväkirja**-ikkunaa **Varasto**-valikossa. Menettely on lähes sama kuin silloin, kun suoritetaan inventointi ilman syklin laskentaa.  
-   Jos sijainnissa käytetään ohjattua hyllytystä ja poimintaa (laajennettu varastointimääritys), suorita **Laske f.var. muutos** -toiminto käyttämällä ensin **F.var. inventointipvk** -ikkunaa ja sitten **Nimikepäiväkirja**-ikkunaa.

### <a name="to-calculate-the-expected-inventory-in-basic-warehouse-configurations"></a>Oletetun varaston laskeminen varastoinnin perusmäärityksissä
1. Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, anna **Varastopäiväkirjat** ja valitse sitten aiheeseen liittyvä linkki.
2. Valitse **Laske varasto** -toiminto.
3. Määritä **Laske varasto** -ikkunassa ehdot, joita käytetään luotaessa päiväkirjarivejä, kuten sisällytetäänkö nimikkeet, joiden kirjattu varastomäärä on nolla.
4. Aseta suodattimia, jos haluat laskea vain varaston tiettyjä nimikkeitä, varastopaikkoja, sijainteja tai dimensioita.
5. Valitse **OK**-painike.

> [!NOTE]  
>   Ohjelma käsittelee nimiketapahtumat määrittämiesi tietojen mukaan ja luo rivejä inventointipäiväkirjaan. Huomaa, että **Määrä (inventointi)** -kenttään täytetään automaattisesti sama määrä kuin **Määrä (laskettu)** -kenttään. Tämän ominaisuuden ansiosta sinun ei tarvitse syöttää laskettua varastosaldoa niiden nimikkeiden osalta, joiden määrä on sama kuin laskettu määrä. Jos laskettu määrä kuitenkin eroaa **Määrä (laskettu)** -kenttään syötetystä määrästä, korvaa se todellisella lasketulla määrällä.

### <a name="to-calculate-the-expected-inventory-in-advanced-warehouse-configurations"></a>Oletetun varaston laskeminen laajennetuissa varastomäärityksissä
1.  Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, kirjoita **Nimikepäiväkirja** ja valitse aiheeseen liittyvä linkki.  
2.  Valitse **Laske f. var. muutos** -toiminto.  
3.  Täydennä eräajon pyyntöikkunaan niiden nimikkeiden numerot, jotka haluat laskea, sekä niiden sijainti.
4. Valitse **OK** ja kirjaa mahdolliset muutokset.

    Jos et tee tätä ennen kuin suoritat fyysisen varastoinnin inventoinnin, inventointipäiväkirjaan ja prosessin toisessa vaiheessa nimiketapahtumiin kirjaamasi tulokset ovat inventoinnin tulosten ja muiden fyysisen varastoinnin muutosten yhdistelmä laskettujen nimikkeiden osalta.  
5.  Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, kirjoita **F.var. inventointipvk** ja valitse aiheeseen liittyvä linkki.  
6. Valitse **Laske varasto** -toiminto. Näyttöön tulee **F. var. laske varasto** -eräajon pyyntöikkuna.  
7.  Aseta suodattimet rajoittamaan päiväkirjassa laskettavia nimikkeitä ja napsauta sitten **OK**.

    Ohjelma luo rivin kullekin varastopaikalle, joka täyttää suodattimen vaatimukset. Tässä vaiheessa voi vielä poistaa joitain rivejä, mutta jos haluat kirjata tulokset inventoinniksi, nimike tulee laskea kaikista varastopaikoista, jotka sisältävät sen.  

     Jos on aikaa laskea nimikkeet vain joistain varastopaikoista, voit löytää eroavaisuuksia, rekisteröidä ne ja myöhemmin kirjata ne nimikepäiväkirjaan käyttämällä **Laske f.var. muutos** -toimintoa.  
8.  Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, kirjoita **F. var. inventointiluettelo** ja valitse aiheeseen liittyvä linkki.  
9.  Avaa raportin pyyntösivu ja tulosta luettelot, joihin haluat työntekijöiden kirjaavan kussakin varastopaikassa laskettujen nimikkeiden määrät.  
10. Kun laskenta on tehty, syötä lasketut määrät fyysisen varastoinnin inventointipäiväkirjan **Määrä (inventointi)** -kenttään.  

    > [!NOTE]  
    >  Ohjelma täyttää fyysisen varastoinnin inventointipäiväkirjassa automaattisesti **Määrä (laskettu)** -kentän fyysisen varaston varastopaikkatietueiden perusteella ja kopioi nämä määrät kunkin rivin **Määrä (inventointi)** -kenttään. Jos fyysisen varaston työntekijän laskema määrä poikkeaa ohjelman Määrä (inventointi) -kenttään syöttämästä määrästä, syötä tosiasiassa laskettu määrä.  

11. Kun olet antanut kaikki lasketut määrät, valitse **Rekisteröi**-toiminto.  

    Kun päiväkirja rekisteröidään, ohjelma luo kaksi fyysisen varastoinnin tapahtumaa fyysisen varaston rekisteriin kunkin rivin osalta, joka laskettiin ja rekisteröitiin:  

    -   Jos lasketut ja inventointimäärät eroavat toisistaan, varastopaikalle rekisteröidään negatiivinen tai positiivinen määrä, ja sijainnin muutoksen varastopaikkaan kirjataan vastamäärä.  
    -   Jos laskettu määrä on sama kuin inventointimäärä, ohjelma rekisteröi tapahtuman, jonka suuruus on 0, sekä varastopaikalle että muutoksen varastopaikalle. Tapahtumat ovat tallenteita siitä, että rekisteröintipäivämäärän suoritettiin fyysisen varaston inventointi, eikä nimikkeen osalta varastossa ollut eroavaisuuksia.  

Kun fyysisen varastoinnin inventointia rekisteröidään, kirjausta nimiketapahtumiin, inventointitapahtumiin tai arvotapahtumiin ei tapahdu, vaan tietueet ovat valmiina välitöntä täsmäytystä varten heti, kun sitä tarvitaan. Jos haluat kuitenkin ylläpitää tarkkoja tietueita siitä, mitä fyysisessä varastoinnissa tapahtuu, ja jos olet laskenut kaikki varastopaikat, joihin nimikkeet on rekisteröity, fyysisen varastoinnin tulokset tulisi heti kirjata inventoinniksi varastonhallinnassa. Lisätietoja on kohdassa Todellisen lasketun varaston antaminen ja kirjaaminen laajennetuissa varastomäärityksissä.

### <a name="to-print-the-report-to-be-used-when-counting"></a>Laskennassa käytettävän raportin tulostaminen
1. Valitse lasketun oletetun varaston sisältävän **Varastopäiväkirja** -ikkunassa **Tulosta**-toiminto.
2. Määritä **Inventointiluettelo**-ikkunassa, näytetäänkö raportissa laskettu määrä ja näkyykö raportissa varastonimikkeiden luettelo sarja ja eränumeroiden mukaan.
3. Määritä suodattimia, jos haluat tulostaa vain tiettyjä varastojen nimikkeiden, varastopaikkojen, sijaintien tai dimensioiden raportteja.
4. Valitse **Tulosta**-painike.

Työntekijät voivat nyt laskea varaston ja merkitä mahdolliset poikkeamat tulostettuun raporttiin.

### <a name="to-enter-and-post-the-actual-counted-inventory-in-basic-warehouse-configurations"></a>Todellisen lasketun varaston antaminen ja kirjaaminen fyysisen varastoinnin perusmäärityksissä
1. Jos jollakin **Varastopäiväkirja**-ikkunan rivillä inventoinnissa määritetty todellinen saatavissa oleva varastomäärä poikkeaa lasketusta määrästä, anna **Määrä (varastotilanne)** -kentässä todellinen saatavissa oleva varastomäärä.

    Liittyvät kentät päivitetään tämän mukaisesti.

    > [!NOTE]  
>   Jos inventointi paljastaa eroja, jotka johtuvat siitä, että nimikkeitä on kirjattu virheellisten sijaintikoodien kanssa, älä syötä eroja inventointipäiväkirjaan. Käytä sen sijaan uudelleenluokituspäiväkirjaa tai siirtotilausta nimikkeiden ohjaamiseen oikeisiin sijainteihin. Lisätietoja on ohjeaiheessa Nimikkeen uudel.luokit. pvk tai Siirtotilausten luominen.

2. Voit muokata lasketut määrät todellisten laskettujen määrien mukaiseksi valitsemalla **Kirjaus**-toiminnon.

    Sekä nimiketapahtumat että fyysiset inventointitapahtumat luodaan. Avaa nimikkeen kortti, jos halkuat tarkastella tuloksena saatavia inventointitapahtumia.

3. Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, anna **Nimikkeet** ja valitse sitten aiheeseen liittyvä linkki.
4. Voit tarkistaa inventoinnin avaamalla kyseisen nimikekortin ja valitsemalla sitten **Inventointitapahtumat** -toiminnon.

### <a name="to-enter-and-post-the-actual-counted-inventory-in-advanced-warehouse-configurations"></a>Todellisen lasketun varaston antaminen ja kirjaaminen laajennetuissa varastomäärityksissä

1.  Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, kirjoita **Nimikepäiväkirja** ja valitse aiheeseen liittyvä linkki.  
2.  Valitse **Laske f. var. muutos** -toiminto.  
3.  Valitse samat nimikkeet, jotka juuri laskit suorittamassasi syklin laskennan inventoinnissa, ja muut oikaisua vaativat kohteet. Valitse sitten **OK**-painike.  

     Näille nimikkeille luodaan rivit **Inventointipäiväkirja**-ikkunaan. Huomaa, että nettomäärät, jotka juuri laskettiin ja rekisteröitiin varastopaikka kerrallaan, voidaan nyt konsolidoida ja synkronoida nimiketapahtumiksi.  

4.  Kirjaa päiväkirja määriä muuttamatta.  

Nimikekirjausten määrät (nimiketapahtumat) ja fyysisen varastoinnin määrät (fyysisen varastoinnin tapahtumat) ovat jälleen kerran samat näiden nimikkeiden osalta, ja ohjelma on päivittänyt nimikkeen (tai varastointiyksikön) viimeksi lasketun päivämäärän.  

## <a name="to-perform-cycle-counting"></a>Inventoinnin suorittaminen
Vaikka lasket kaikki varaston nimikkeet vähintään kerran vuodessa, voit päättää laskevasi joitain nimikkeitä useammin, koska ne ovat ehkä arvokkaampia tai ne liikkuvat nopeasti varastosta ja ovat suuri osa liiketoimintaa. Voit määrittää tätä varten erityisiä laskentajaksoja.

Sykli voidaan laskea jommallakummalla tavalla määritettyjen varastoasetusten mukaan. Lisätietoja on kohdassa [Varastoinninhallinnan määrittäminen](warehouse-setup-warehouse.md).  

-   Jos ohjattu hyllytys ja poiminta ei ole käytössä sijainnissa (varastoinnin perusmääritys), käytä **Varastopäiväkirja**-ikkunaa **Varasto**-valikossa. Menettely on lähes sama kuin silloin, kun suoritetaan inventointi ilman syklin laskentaa.  
-   Jos sijainnissa käytetään ohjattua hyllytystä ja poimintaa (laajennettu varastointimääritys), suorita **Laske f.var. muutos** -toiminto käyttämällä ensin **F.var. inventointipvk** -ikkunaa ja sitten **Nimikepäiväkirja**-ikkunaa.  

### <a name="to-set-up-counting-periods"></a>Laskentajaksojen määrittäminen
Inventointi suoritetaan tavallisesti toistuvin aikavälein, esimerkiksi kuukausittain, neljännesvuosittain tai vuosittain. Voit määrittää mitä tahansa inventoinnin laskentajaksoja.

Määritä käytettävät inventointijaksot ja määritä yksi niistä kullekin nimikkeelle. Kun suoritat inventoinnin ja käytät inventointipäiväkirjassa **Laske laskentajakso** -vaihtoehtoa, nimikkeiden rivit luodaan automaattisesti.

1. Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, anna **Varastotilanteen laskentajaksot** ja valitse sitten aiheeseen liittyvä linkki.  
2. Täytä tarvittavat kentät. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]

### <a name="to-assign-a-counting-period-to-an-item"></a>Laskentajakson määritteleminen nimikkeelle  
1. Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, anna **Nimikkeet** ja valitse sitten aiheeseen liittyvä linkki.  
2. Valitse nimike, jolle haluat määrittää laskentajakson.  
3. Valitse **Inventointijakson koodi** -kentässä sopiva laskentajakso.  
4. Valitse **Kyllä**-painike vaihtaaksesi koodin ja laskeaksesi nimikkeelle ensimmäisen laskentajakson. Kun lasket seuraavan kerran inventointipäiväkirjassa laskentajakson, nimike näkyy rivinä **Inventoinnin nimikevalinta** -ikkunassa. Voit sitten aloittaa nimikkeen laskennan säännöllisin väliajoin.

### <a name="to-initiate-a-count-based-on-counting-periods-in-basic-warehouse-configurations"></a>Laskennan käynnistäminen laskentakauden perusteella fyysisen varastoinnin perusmäärityksissä
1. Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, anna **Varastopäiväkirja** ja valitse sitten aiheeseen liittyvä linkki.
2. Valitse **Laske laskentajakso** -toiminto.

    Avautuvassa **Inventoinnin nimikevalinta** -ikkunassa näkyvät nimikkeet, joille on määritetty laskentajaksot ja jotka on laskettava niiden laskentajaksojen mukaisesti.
3. Suorita inventointi. Lisätietoja on kohdassa Inventoinnin suorittaminen.

### <a name="to-initiate-a-count-based-on-counting-periods-in-advanced-warehouse-configurations"></a>Laskennan käynnistäminen laskentakauden perusteella laajennetuissa varastomäärityksissä
1.  Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, kirjoita **F.var. inventointipvk** ja valitse aiheeseen liittyvä linkki.  
2. Valitse **Laske laskentajakso** -toiminto.

    Avautuvassa **Inventoinnin nimikevalinta** -ikkunassa näkyvät nimikkeet, joille on määritetty laskentajaksot ja jotka on laskettava niiden laskentajaksojen mukaisesti.
3. Suorita inventointi. Lisätietoja on kohdassa Inventoinnin suorittaminen.  

    > [!NOTE]  
    >  Nimike tulee laskea kaikista varastopaikoista, jotka sisältävät kyseistä nimikettä. Jos poistat joitakin varastopaikan rivejä, jotka ohjelma on hakenut laskentaa varten **F. var. inventointi** -ikkunaan, et tule laskeneeksi kaikkia fyysisen varaston nimikkeitä. Jos kirjaat tällaisia epätäydellisiä tuloksia inventointipäiväkirjaan myöhemmin, kirjatut summat ovat virheellisiä.  

## <a name="to-adjust-the-inventory-of-one-item"></a>Yhden nimikkeen varastonimikkeen muuttaminen
Kun nimikkeen fyysinen laskenta on suoritettu varastoalueellasi, voit käyttää **Muuta varasto**-toimintoa todellisen varastomäärän kirjaamiseen.

1. Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, anna **Nimikkeet** ja valitse sitten aiheeseen liittyvä linkki.
2. Valitse nimike, jonka varastoa haluat muuttaa, ja valitse sitten **Muuta varastoa** -toimintoa.
3. Syötä **Uusi varasto** -kenttään varastomäärä, jonka haluat tallentaa nimikkeelle.
4. Valitse **OK**-painike.

Nimikkeen varasto on nyt määritetty. Uusi määrä näytetään **Nykyinen varasto** -kentässä **Muokkaa varastoa** -ikkunassa ja **Varasto**-kentässä **Nimikekortti**-ikkunassa.

Voit käyttää **Muuta varastoa** -toimintoa myös yksinkertaisena tapana asettaa ostetut nimikkeet varastoon, jos et tallenna ostoja ostolaskuina tai -tilauksina. Lisätietoja on kohdassa [Toimintaohje: Ostojen kirjaaminen](purchasing-how-record-purchases.md).

> [!NOTE]  
>   Kun olet muuttanut varastoa, se on päivitettävä nykyisellä lasketulla arvolla. Lisätietoja on kohdassa [Toimintaohje: Varaston uudelleenarvostus](inventory-how-revalue-inventory.md).

### <a name="to-adjust-the-inventory-quantity-of-multiple-items-in-basic-warehouse-configurations"></a>Useiden nimikkeiden varastosaldon muuttaminen fyysisen varastoinnin perusmäärityksissä
Voit kirjata **Nimikepäiväkirja** -ikkunassa nimiketapahtuman suoraan ja muuttaa varastoa ostojen, myyntien ja positiivisten tai negatiivisten muutosten yhteydessä asiakirjoja käyttämättä.

Jos nimikepäiväkirjaan kirjataan usein samoja tai saman tyyppisiä päiväkirjan rivejä, jotka liittyvät esimerkiksi materiaalinkulutukseen, voit helpottaa toistuvien toimien suorittamista käyttämällä **Vakionimikepäiväkirja**-ikkunaa. Lisätietoja on ohjeaiheen [Yleisten päiväkirjojen käyttäminen](ui-work-general-journals.md) kohdassa Vakiopäiväkirjat.

1. Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, anna **Nimikepäiväkirjat** ja valitse sitten aiheeseen liittyvä linkki.
2. Täytä tarvittavat kentät. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]
3. Tee muutokset varastoon valitsemalla **Kirjaa**-toiminto.

> [!NOTE]  
>   Kun olet muuttanut varastoa, se on päivitettävä nykyisellä lasketulla arvolla. Lisätietoja on kohdassa [Toimintaohje: Varaston uudelleenarvostus](inventory-how-revalue-inventory.md).

### <a name="to-adjust-bin-quantities-in-advanced-warehouse-configurations"></a>Varastopaikkamäärien muuttaminen laajennetuissa varastomäärityksissä  
Kun käytät ohjattua hyllytystä ja poimintaa, käytä muissa kuin inventointiyhteyksissä **fyysisen varastoinnin nimikepäiväkirjaa** kaikkien todellisten positiivisten muutosten (esimerkiksi puuttuneiden nimikkeiden löytymisen) ja negatiivisten muutosten (esimerkiksi nimikkeiden särkymisen) kirjaamiseen.  

Toisin kuin kirjattaessa muutoksia varaston nimikepäiväkirjaan, fyysisen varastoinnin nimikepäiväkirjaa käytettäessä käytössä on tarkempi muutostaso, jonka avulla määrätietueet pysyvät entistä paremmin ajan tasalla. Fyysisessä varastoinnissa on siis aina tarkat tiedot siitä, kuinka paljon nimikkeitä on saatavilla ja missä ne ovat varastoituina, mutta kutakin muutosrekisteröintiä ei kirjata heti nimiketapahtumiin. Rekisteröintiprosessissa ohjelma hyvittää tai veloittaa oikeaa varastopaikkaa määrän muutoksella ja tekee vastatapahtuman muutosvarastopaikkaan - virtuaalivarastopaikkaan, jossa ei ole oikeita nimikkeitä. Tämä varastopaikka on määritetty sijaintikortin **Var. muutosvarastopaikan koodi** -kentässä.

1.  Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, kirjoita **F.var. nimikepvk** ja valitse sitten aiheeseen liittyvä linkki.  
2.  Täytä otsikon tiedot.  
3.  Täytä rivillä oleva **Nimikkeen nro** -kenttä.  
4.  Syötä varastopaikka, johon olet panemassa ylimääräiset nimikkeet tai josta olet löytänyt puuttuvat nimikkeet.  
5.  Täytä **Määrä**-kenttään määrä, jonka olet havainnut eroavaisuudeksi. Jos olet löytänyt ylimääräisiä nimikkeitä, syötä positiivinen määrä. Jos nimikkeitä puuttuu, syötä negatiivinen määrä.  
6.  Valitse **Rekisteröi**-toiminto.

## <a name="to-synchronize-the-adjusted-warehouse-entries-with-the-related-item-ledger-entries"></a>Muutettujen fyysisen varastoinnin tapahtumien ja liittyvien nimiketapahtumien synkronointi
Fyysisen varastoinnin muutosvarastopaikan tietueet tulee kirjata yrityksen menettelytapojen mukaisin aikavälein nimiketapahtumiin. Joissakin yrityksissä muutokset on hyvä kirjata nimiketapahtumiin joka päivä, kun taas toisissa yrityksissä voi olla järkevämpää täsmäyttää muutokset harvemmin.

1.  Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, kirjoita **Nimikepäiväkirja** ja valitse sitten aiheeseen liittyvä linkki.  
2.  Kirjoita kunkin päiväkirjarivin kenttien tiedot.  
3.  Valitse **Laske f.var. muutos** -toiminto ja täytä tarvittavat suodattimet eräajon pyyntöikkunassa. Muutokset lasketaan vain Muutosvarastopaikan tapahtumille, jotka täyttävät suodattimen vaatimukset.  
4.  Täytä **Vaihtoehdot**-pikavälilehden **Asiakirjan nro** -kenttään manuaalisesti syöttämäsi numero. Koska tälle eräajolle ei ole määritetty numerosarjaa, käytä fyysisen varastoinnin määrittämää numeromallia tai syötä päivämäärä (päivä-kuukausi-vuosi) ja sen jälkeen nimikirjaimesi.  
5.  Valitse **OK**-painike. Ohjelma laskee yhteen kunkin nimikkeen positiiviset ja negatiiviset muutokset ja luo nimikepäiväkirjaan rivejä kaikille nimikkeille, joiden summa on positiivinen tai negatiivinen määrä.  
6.  Lisää määräerot nimiketapahtumiin kirjaamalla päiväkirjarivit. Fyysisen varastoinnin varastopaikkojen varasto vastaa nyt tarkasti nimiketapahtumien varastoa.  

## <a name="to-reclassify-an-items-lot-number"></a>Nimikkeen eränumeron uudelleenluokittelu
1. Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, anna **Nimikkeen uudell.luokit. pvk:t** ja valitse sitten aiheeseen liittyvä linkki.
2. Täytä **Nimik. uud.luok.pvk** -ikkunassa tarvittavat kentät.
3. Anna valittuna olevan erän numero **Eränro**-kentässä.
4. Anna uuden erän numero **Uusi eränro**-kentässä.
5. Valitse **Kirjaa**-toiminto.

Sarja- tai eränumeroiden uudelleenluokitteluun liittyy erityisiä vaiheita. Lisätietoja on kohdassa [Toimintaohje: Sarja- ja eränumeroiden käsitteleminen](inventory-how-work-item-tracking.md).

## <a name="see-also"></a>Katso myös
[Varasto](inventory-manage-inventory.md)
[Varastoinninhallinta](warehouse-manage-warehouse.md)    
[Myynti](sales-manage-sales.md)  
[Osto](purchasing-manage-purchasing.md)  
[[!INCLUDE[d365fin](includes/d365fin_md.md)] -ohjelman käyttäminen](ui-work-product.md)

