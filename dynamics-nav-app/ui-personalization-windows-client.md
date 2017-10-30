---
title: Sivujen mukauttaminen Dynamicsin Windows-asiakasohjelmassa
description: "Lisätietoja käyttöliittymän mukauttamisesta omaan työskentelytapaan sopivaksi."
author: jswymer
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.date: 07/26/2017
ms.author: jswymer
ms.prod: dynamics-nav-2018
ms.translationtype: HT
ms.sourcegitcommit: b9b1f062ee6009f34698ea2cf33bc25bdd5b11e4
ms.openlocfilehash: e22f3464c6a4dd917880ad0b903880fe5f57a37d
ms.contentlocale: fi-fi
ms.lasthandoff: 10/23/2017

---
# <a name="personalizing-your-workspace-in-the-dynamics-windows-client"></a>Työtilan mukauttaminen Dynamicsin Windows-asiakasohjelmassa
Voit mukauttaa työtilan työskentelyysi ja valintoihisi sopivaksi muuttamalla sivujen ulkoasua siten, että vain tarvitsemasi tiedot näkyvät siellä, missä niitä tarvitset. Mukauttamalla tehdyt muutokset koskevat vain omaa näkymääsi; muut käyttäjät eivät siis näe mukautuksiasi. Voit mukauttaa useita käyttöliittymän osia, kuten valintanauhaan valittavia toimintoja, kenttien sijoittelua pikavälilehdissä tai tietoruuduissa ja siirtymisruutuun sisällytettäviä valikkovaihtoehtoja.

> [!NOTE]  
> Voit mukauttaa sivuja myös [!INCLUDE[nav_web_md](includes/nav_web_md.md)]in avulla. Lisätietoja mukauttamisen käytöstä kahden asiakasohjelman välillä on kohdassa [Mukauttamisen yleiskatsaus](ui-personalization-overview.md).

## <a name="how-to-personalize-your-workspace"></a>Työtilan mukauttaminen
Voit suorittaa suorimman osan mukautuksista **Mukauta**-toiminnolla, johon voi siirtyä lähes kaikenlaisilta sivuilta seuraavasti:

1.  Avaa mukautettava sivu.
2.  Valitse ensin ylhäällä vasemmalla **Sovellus**-valikon ![Valikko rivin sovellusvalikon painike](media/applicationmenuicon.png "ApplicationMenuIcon") kuvake, sitten **Mukauta** ja lopuksi jokin mukautusvaihtoehto.

**Mukauta**-vaihtoehdon lisäksi sivulla voi tehdä myös suoraan tiettyjä peruskäyttöliittymän muutoksia, kuten säätää ikkunan kokoa tai leventää sarakkeita.

## <a name="general-information"></a>Yleiset tiedot
Käyttöliittymää mukautettaessa on hyvä muistaa seuraavat asiat:

-   Voit tallentaa samasta sivusta useita mukautuksia sivun eri liitäntäpisteiden perusteella. Esimerkiksi Myyntitilaukset-ikkuna on mahdollista mukauttaa niin, että se näyttää erilaiselta avattaessa Asiakaskortti-ikkunasta ja Myyntitilauksen käsittelijä-roolikeskuksesta. Kohta, josta käytät muokattavaa sivua, tallennetaan tähän erityiseen sivun muokkaukseen. Niinpä tietokannassa saattaa olla useita sivun mukautustietueita samalle, mistä on esimerkki **Poista käyttäjän mukautus** -ikkunassa.

-   Sovellus voidaan määrittää näyttämään tai piilottamaan käyttöliittymäelementit (kuten kentät, pikavälilehdet ja tietoruudut) käyttöoikeussopimuksen tai käyttöoikeuksien perusteella. Voit tarkastella ja mukauttaa vain niiden elementtien kenttiä, joiden käyttöoikeus sinulla on.

## <a name="customize-ribbons"></a>Valintanauhan mukauttaminen
Valintanauhan kautta voi käyttää useita toimintoja. Valintanauhaa mukauttamalla voit optimoida sen työprosesseihin ja asetuksiin sopiviksi. Jos käytät usein esimerkiksi **Dimensiot**-ikkunaa, voit lisätä **Dimensiot**-toiminnon **Prosessi**-toimintojen ryhmään. Yleiskuvan parantamiseksi voit myös poistaa toimintoja, joita et koskaan käytä.  

Voit suorittaa seuraavat tehtävät muokataksesi nauhoja sivuilla:  

-   Lisää, nimeä uudelleen tai poista välilehtiä, ryhmiä, toimintoja ja valikoita.  
-   Vaihda toimintojen järjestystä.  
-   Palauta valintanauhan oletusasetukset.  

### <a name="to-customize-a-ribbon"></a>Valintanauhan mukauttaminen
1. Avaa muutettava sivu.
2. Valitse ylhäällä vasemmalla ensin **Sovellus**-valikon ![Valikkorivin sovellusvalikon painike](media/applicationmenuicon.png "ApplicationMenuIcon") kuvake, sitten **Mukauta** ja lopuksi **Muokkaa valintanauhaa**.

**Järjestä valintanauhan toiminnot** -valintaikkuna on jaettu kahteen ruutuun. **Käytettävissä olevat toiminnot** -ruudussa on luettelo kaikista sivulle lisättävistä toiminnoista. **Näytä toiminnot seuraavassa järjestyksessä** -ruudussa on kaikkien sivulla näkyvien toimintojen rakenne.

-   Päätason vaihtoehdon määrittävät välilehdet.

    -   Toisen tason vaihtoehdot määrittävät välilehden ryhmän.

        -   Kolmannen tason vaihtoehdot määrittävän ryhmän toimintojen valikon.

### <a name="add-a-group"></a>Ryhmän lisääminen
Valitse ensin ryhmitettävä välilehti ja sitten **Luo ryhmä**. Ryhmää ei voi lisätä valikkoon.

### <a name="add-a-menu"></a>Valikon lisääminen
Valitse ensin ryhmä, johon haluat luoda valikon, ja valitse sitten **Luo valikko**. Voit lisätä valikon vain toiseen ryhmään tai valikkoon.

#### <a name="add-an-action"></a>Toiminnon lisääminen
Lisää toiminto **Näytä toiminnot seuraavassa järjestyksessä** -ruutuun valitsemalla **Käytettävissä olevat toiminnot** -ruudussa **Lisää**. Sijoita toiminto sitten haluamaasi kohtaan **Siirrä ylös**- ja **Siirrä alas** -painikkeilla.

Et lisätä toimintoa välilehteen, sillä sen voi lisätä vain ryhmään tai valikkoon.

###  <a name="limitations-and-recommendations"></a>Rajoitukset ja suositukset
Huomaa seuraavat rajoitukset, kun mukautat valintanauhaa:  

-   Järjestelmän välilehtiä ja ryhmiä, kuten **Kotisivu** tai **Uusi** ei voida siirtää tai nimetä uudelleen. Joidenkin ryhmien sijainti, kuten **Uuden asiakirjaa**, on kiinteä.  
-   Toimintoja tai ryhmiä, joilla on dynaamista näkyvyyttä, ei voi lisätä tai poistaa.
-   Voit luoda valikoita vain ryhmien, et välilehtien sisälle.  
-   Voit tehdä valikosta sisäkkäisen toisen valikon kanssa, mutta tämä ei ole suositeltava toimi.  
-   Toimi seuraavasti, jos näet odottamatonta käyttäytymistä ryhmissä ja toiminnoissa nauhan mukauttamisen jälkeen:  

    1.  Tyhjennä ryhmä, jossa on ongelmia, mutta älä poista sitä.  
    2.  Sulje valintaikkuna **OK**-painikkeella.  
    3.  Avaa valintaikkuna uudelleen ja lisää toimintoja uudelleen ryhmään.  

> [!IMPORTANT]  
>  Kaikki muokkaukset, jotka muuttavat valintanauhaan, voivat vaikuttaa [!INCLUDE[navnow_md](includes/navnow_md.md)] -järjestelmän ohjeisiin, koska ohjeen vaihekuvaukset saattavat viitata erilaiseen valintanauhan asetteluun.

## <a name="customize-fasttabs"></a>Pikavälilehtien mukauttaminen
Pikavälilehtien avulla sivujen tiedot voi järjestää yksinkertaisiksi ja hallittaviksi ryhmiksi. Voit mukauttaa pikavälilehdet sivuilla siten, että ne tukevat työnkulkua. Haluat ehkä näyttää vähemmän pikavälilehtiä tai piilottaa tietyt pikavälilehtien kentät. Voit myös määrittää, että tärkeimmät kentät näkyvät pikavälilehtien otsikoissa, kun pikavälilehdet ovat supistettuina.  

### <a name="to-customize-a-fasttab"></a>Pikavälilehden räätälöiminen  

1.  Avaa muutettava sivu.
2.  Valitse ensin **Sovellus**-valikon ![Valikkorivin sovellusvalikon painike](media/applicationmenuicon.png "ApplicationMenuIcon") kuvake, sitten **Mukauta** ja lopuksi **Mukauta tämä sivu**.  
3.  Valitse **Mukauta <Page Name>** -valintaikkunassa **Pikavälilehdet**.  

### <a name="add-move-or-remove-fasttabs"></a>Pikavälilehtien lisääminen, siirtäminen tai poistaminen
**Näytä pikavälilehdet seuraavassa järjestyksessä** -ruudussa on sivulla tällä hetkellä olevat pikavälilehdet ja niiden näyttöjärjestys. Tee muutoksia **Lisää**-, **Poista**- **Siirrä ylös**- ja **Siirrä alas** -painikkeilla.

### <a name="show-and-hide-fields-on-fasttabs"></a>Pikavälilehtien kenttien näyttäminen ja piilottaminen
Valitse **Näytä pikavälilehdet seuraavassa järjestyksessä** -ruudussa ensin muutettava pikavälilehti ja valitse **Mukauta pikavälilehti**. Mukauta painikkeilla kenttiä, joiden haluat näkyvän, ja niiden järjestystä sivulla.

Määritä **Tärkeys** seuraavasti:
-   Jos haluat näyttää kentän pikavälilehden otsikossa, kun pikavälilehti on supistettuna, määritä asetukseksi **Korkea**.
- Jos haluat, että kenttä on piilotettuna, ellei käyttäjä valitse pikavälilehdessä **Näytä lisää kenttiä** -toimintoa, määritä asetukseksi **Lisää**.
-   **Vakio** on oletus- tai normaaliasetus.

### <a name="set-up-field-for-quick-entry"></a>Pikatapahtuman kentän määrittäminen
Lisää kenttä pikatapahtuman kenttäluetteloon valitsemalla **Pikatapahtuma**. Kun käsittelet sivua ja paina Enter-näppäintä, osoitin siirtyy seuraavaan pikatapahtumakentäksi määritettyyn kenttään.

## <a name="customize-factboxes"></a>Tietoruutujen mukauttaminen
Tietoruudut sisältävät luettelosta valitsemaasi tai tehtäväsivulla avaamaasi tietueeseen liittyviä tietoja. Voit valita näytettävät tietoruudut. Voit mukauttaa tietoruutuja siten, että niissä näkyy vain tarvitsemasi kentät.  

### <a name="to-show-or-hide-the-factbox-pane"></a>Tietoruudun näyttäminen tai piilottaminen
Tietoruudut ovat tietoruudun kehyksen sisällä, jonka näyttämisen tai piilottamisen voit päättää sivukohtaisesti. Voit piilottaa tällä tavoin kätevästi useita tietoruutuja ilman, että ne pitäisi poistaa yksitellen.

1.  Avaa muutettava sivu.
2.  Valitse ensin **Sovellus**-valikon ![Valikkorivin sovellusvalikon painike](media/applicationmenuicon.png "ApplicationMenuIcon") kuvake, sitten **Mukauta** ja lopuksi **Tietoruudut**. Valintamerkki ilmaisee, että tietoruudun kehys näkyy.  

### <a name="to-customize-the-factbox-pane"></a>Tietoruudun kehyksen mukauttaminen  
1.  Avaa muutettava sivu.
2.  Valitse ensin **Sovellus**-valikon ![Valikkorivin sovellusvalikon painike](media/applicationmenuicon.png "ApplicationMenuIcon") kuvake, sitten **Mukauta** ja lopuksi **Valitse tietoruudut**.  

### <a name="add-a-factbox"></a>Tietoruudun lisääminen  

Valitse ensin tietoruudun kehykseen lisättävä tietoruutu **Käytettävissä olevat tietoruudut** -ruudussa ja sitten **Lisää**-painike.  

### <a name="remove-a-factbox"></a>Tietoruudun poistaminen  

Valitse **Näytä tietoruudut seuraavassa järjestyksessä** -ruudussa ensin tietoruutu ja sitten **Poista**-painike.   

### <a name="change-the-order-of-the-factboxes"></a>Tietoruutujen järjestyksen muuttaminen  

Valitse ensin **Näytä tietoruudut seuraavassa järjestyksessä** -ruudussa siirrettävä tietoruutu ja sijoita se sitten haluamaasi kohtaan **Siirrä ylös** - tai **Siirrä alas** -painikkeella.  

### <a name="change-the-fields-in-a-factbox"></a>Tietoruudun kenttien muuttaminen  

1.  Valitse **Näytä tietoruudut seuraavassa järjestyksessä** -ruudussa ensin tietoruutu ja sitten **Mukauta osa**.  

2.   **Käytettävissä olevat kentät** -ruudussa on luettelo valittavista kentistä. Kaikki tietoruudussa tällä hetkellä näkyvät kentät ovat **Näytettävät kentät** -ruudussa. Lisää, poista ja siirrä kenttiä painikkeiden avulla.   


## <a name="customize-columns-in-a-list-or-on-document-lines"></a>Luettelon tai asiakirjan rivien sarakkeiden mukauttaminen
Saat paremman käsityksen tarvitsemistasi tiedoista, kun mukautat luettelo- tai korttisivuja lisäämällä tai poistamalla ruudukon sarakkeita, järjestelmällä sarakkeet uudelleen ja lisäämällä kiinnitysruudun.  

### <a name="to-add-remove-and-arrange-columns"></a>Sarakkeiden lisääminen, poistaminen ja järjestäminen  

1.  Voit lisätä, poistaa tai järjestää sarakkeita uudelleen kahdella tavalla:

    -   Valitse ensin **Sovellus**-valikon ![Valikkorivin sovellusvalikon painike](media/applicationmenuicon.png "ApplicationMenuIcon") kuvake, sitten **Mukauta** ja lopuksi **Valitse sarakkeet**.
    -   Valitse sarakkeen otsikko hiiren kakkospainikkeella ja valitse sitten **Valitse sarakkeet**.

2.  **Valitse luettelossa näytettävät sarakkeet** -valintaikkunan **Käytettävissä olevat sarakkeet** -ruutu sisältää piilotetut sarakkeet. **Näytä sarakkeet tässä järjestyksessä** -ruutu sisältää näkyvissä olevat sarakkeet. Voit siirtää sarakkeita kentästä toiseen **Lisää**- ja **Poista**-painikkeiden avulla. Valitse sarakkeiden paikka **Siirrä ylös**- ja **Siirrä alas** -painikkeiden avulla.

>[!TIP]
>Lisää kenttä pikatapahtuman kenttäluetteloon valitsemalla **Pikatapahtuma**. Kun käsittelet sivua ja paina Enter-näppäintä, osoitin siirtyy seuraavaan pikatapahtumakentäksi määritettyyn kenttään.

### <a name="to-set-the-freeze-pane"></a>Kiinnitysruudun määrittäminen
Luettelossa voi olla useita sarakkeita, jolloin kaikkien sarakkeiden näkeminen edellyttää vierittämistä vaakasuunnassa. Osa sarakkeista voi kuitenkin olla sellaisia, että haluat nähdä ne myös vierityksen aikana. Saat sarakkeet pysymään näkyvissä lisäämällä pystysuuntaisen kiinnitysruudun, mikä estää tiettyjen sarakkeiden vierittämisen. Tällä tavoin voit varmistaa, että vain tärkeydeltään vähäiset sarakkeet siirtyvät vieritettäessä.

Määritä kiinnitysruutu valitsemalla sarake, jonka jälkeen haluat kiinnitysruudun alkavan, ja valitse sitten **Lisää kiinnitysruutu**.

## <a name="customizing-the-navigation-pane"></a>Siirtymisruudun mukauttaminen
Siirtymisruudussa on eri luettelosivuille vievien linkkien valikko. Linkit on ryhmitelty päätason painikkeisiin.

### <a name="to-customize-the-navigation-pane"></a>Siirtymisruudun mukauttaminen  

Valitse ensin **Sovellus**-valikon ![Valikkorivin sovellusvalikon painike](media/applicationmenuicon.png "ApplicationMenuIcon") kuvake, sitten **Mukauta** ja lopuksi **Mukauta siirtymisruutu**.  

### <a name="rename-or-rearrange-buttons-in-the-navigation-pane"></a>Siirtymisruudun painikkeiden nimeäminen tai järjestäminen uudelleen  
Valitse **Mukauta siirtymisruutu** -valintaikkunan vasemmassa ruudussa painike, jonka haluat siirtää, nimetä uudelleen tai poistaa, ja napsauta sitten ikkunan keskellä olevaa vastaavaa painiketta.

Et voi siirtää, nimetä uudelleen tai poistaa **Koti** -painiketta. **Osastot**-painikkeen voi poistaa siirtymisruudusta, mutta sitä ei voi nimetä uudelleen tai siirtää.

### <a name="add-a-new-menu-button"></a>Uuden valikkopainikkeen lisääminen
Voit luoda uuden päätason painikkeen ja lisätä painikkeeseen linkkivalikon eri sivujen avaamiseen.

1. Valitse **Mukauta siirtymisruutu** -valintaikkunassa **Uusi** ja kirjoita sitten nimi **Nimi**-kenttään.
2.  Valitse **OK**-painike.

Voit lisätä linkkejä painikkeeseen.  

### <a name="add-a-link-to-a-button"></a>Linkin lisääminen painikkeeseen   
Jos sinulla on luettelon, kuten myyntitilausluettelon, tarkasteluoikeus, voit lisätä luettelon linkin siirtymisruudun painikkeesta.  

1.  Valitse **Mukauta siirtymisruutu** -valintaikkunan **Siirtymisruudun painikkeet** -kentässä valikko, johon halua lisätä linkin.  

2.  Valitse **Lisää**-painike.  

3.  Valitse valikko, johon haluat lisätä linkin, ja valitse sitten **OK**.  
> [!TIP]
> Jos löydät linkin **Osastot**-sivuilta, voit lisätä myös sen siirtymisruutuun. Lisätietoja on kohdassa Linkin lisääminen Osastot-sivulta omaan roolikeskukseen.  

### <a name="move-or-copy-a-link-from-one-button-to-another"></a>Linkin siirtäminen tai kopioiminen painikkeesta toiseen  

1.  Valitse **Mukauta siirtymisruutu** -valintaikkunan **Siirtymisruudun painikkeet** -kentässä valikko, jossa linkki tällä hetkellä näkyy.  

2.  Valitse **Luettelot**-ruudussa linkki, jonka haluat siirtää, ja valitse sitten **Siirrä kohteeseen** tai  **Kopioi kohteeseen**  

3.  Valitse siirtymispainike, johon haluat lisätä linkin, ja valitse sitten **OK**.  

### <a name="rearrange-the-order-of-a-links-under-a-button"></a>Painikkeen linkkien järjestäminen uudelleen  

1.  Valitse **Luettelot**-ruudussa linkki, jonka haluat siirtää.  

2.  Siirrä linkkiä **Siirrä ylös**- ja **Siirrä alas** -painikkeiden avulla.

## <a name="adding-department-links-to-the-role-center"></a>Osastojen linkkien lisääminen roolikeskukseen
**Osastot**-sivulla voi olla joskus linkkejä, jotka haluat lisätä omaan roolikeskukseen käyttöä helpottamaan. Linkin sijaintipaikka roolikeskuksessa määräytyy sen mukaan, mikä oli linkin luokka **Osastot** sivulla.

Seuraavassa taulukossa kuvataan **Osastot**-sivun kunkin luokan linkkien tyypit sekä Roolikeskuksen paikat, joihin linkit voi lisätä.  

|**Luokka**|**Sisältö**|**Linkin lisäyspaikka**|  
|------------------|------------------|---------------------|  
|Luettelot|Luettelosivut|Siirtymisruudun **Kotisivu**-painike|  
|Tehtävät|Tehtävä-sivut, eräajot, työkirjat, päiväkirjat|Valintanauhan **Toiminnot**-välilehti|  
|Raportit ja analyysi|Raportit, eräajot, matriisi-ikkunat|Valintanauhan **Raportit**-välilehti|  
|Asiakirjat|Erilaiset asiakirjat, kuten laskut ja muistutukset|Valintanauhan **Raportit**|  
|Arkisto/historia|Kirjatut/valmiit asiakirjat, rekisterit|Siirtymisruudun **Kotisivu**-painike|  
|Hallinta|Asetusikkunat|Valintanauhan **Toiminnot**-välilehti|  

### <a name="to-copy-department-links-to-your-role-center"></a>Osastojen linkkien kopioiminen omaan Roolikeskukseen  

1.  Avaa **Osastot**-sivu.  

2.  Napsauta linkkiä hiiren kakkospainikkeella ja valitse jokin seuraavista vaihtoehdoista (ainoastaan yksi vaihtoehto on käytettävissä).  

    |**Valitse**|**Lisää linkin kohteeseen**|  
    |----------------|----------------------------|  
    |**Lisää siirtymisruutuun**|Siirtymisruudun **Kotisivu**-painike roolikeskuksessa.|  
    |**Lisää Roolikeskus-valintanauhan toimintoihin**|Oman Roolikeskuksen valintanauhan **Toiminnot**-valikko|  
    |**Lisää Roolikeskus-valintanauhan raportteihin**|Oman Roolikeskuksen valintanauhan **Raportit**-valikko|  

3.  Vahvista näyttöön tuleva sanoma.  

 Uusi linkki näkyy nyt valikossa, johon lisäsit sen. Voit kuitenkin siirtää linkin toiseen kohtaan valikossa. Jos esimerkiksi lisäsit linkin siirtymisruutuun, se näkyy **Kotisivu**-valikossa, mutta voit siirtää linkin myös toiseen siirtymisruudun valikkoon. Lisätietoja on kohdassa Siirtymisruudun mukauttaminen.

## <a name="adding-charts-to-role-centers-and-list-pages"></a>Kaavioiden lisääminen roolikeskuksiin ja luettelosivuille
Kun sinulla on monimutkaisia tietoja, haluat ehkä tarkastella tietoja visuaalisesti nähdäksesi kehityksen ja tehdäksesi päätöksiä. Voit esimerkiksi haluta seurata yrityksen saldoja pankkitileittäin kaaviossa. Kaavioruudun avulla voit visuaalisesti näyttää tietoja luettelon tietoja seuraavan tyyppisillä sivuilla:  

-   Roolikeskuksessasi, jossa voit valita valmiita yleisiä kaavioita.  

-   Luettelosivulla voit valita luettelon näytettäväksi kaaviona.  

### <a name="to-add-a-generic-chart-to-your-role-center"></a>Yleisen kaavion lisäämiseksi roolikeskukseesi  

1.  Valitse roolikeskuksessa ensin **Sovellus**-valikon ![Valikkorivin sovellusvalikon painike](media/applicationmenuicon.png "ApplicationMenuIcon") kuvake, sitten **Mukauta** ja lopuksi **Mukauta tämä sivu**.  

2.  Valitse **Mukauta Roolikeskus** -ikkunan **Käytettävissä olevat osat** -kentässä **Kaavio-osa** ja valitse sitten **Lisää**.  

3.  Sijoita kaava-osa sivulle roolikeskuksessasi **Siirrä ylös**-, **Siirrä alas**-, **Siirrä vasemmalle**- ja **Siirrä oikealle** -painikkeiden avulla.  

4.  Valitse ensin kaavio-osa ja sitten **Mukauta osa**.  

5.  Valitse ennalta määritetty kaavio **Mukauta kaavio** -ikkunassa ja valitse sitten **OK**.  

### <a name="to-view-a-list-as-a-chart"></a>Tarkastele luetteloa kaaviona  

1.  Valitse luettelosivulla **Näytä kaaviona** -toiminto.  

2.  Valitse mitta ja dimensio mukautetun kaavion luomiseen. Valitse toissijainen dimensio nähdäksesi lisätietoja. Voit luoda yksinkertaisen palkkikaavion valitsemalla X-akselin dimension ja **dimensioiden laskennan** Y-akselilla.  

> [!NOTE]  
>  Kaavioruutu on oletusarvon mukaan piilotettu, koska se voi hidastaa sovelluksen toimintaa. Näytä kaavio vain, kun sinulla on oltava tiedot.  

## <a name="handling-external-files-and-automation-objects"></a>Ulkoisten tiedostojen ja automaatio-objektien käsitteleminen
Kun [!INCLUDE[navnow_md](includes/navnow_md.md)] vastaanottaa ulkoisen tiedoston, näyttöön tulee valintaikkuna. Tiedoston käsittelyn lisäksi voit päättää, kuinka kyseistä tiedostotyyppiä käsitellään, kun se vastaanotetaan seuraavan kerran.  

Kun [!INCLUDE[navnow_md](includes/navnow_md.md)] -järjestelmän on suoritettava automaatio-objekti, näyttöön tulee valintaikkuna. Päätä, onko objektin tyyppi aina suoritettavissa vai ei koskaan.  

### <a name="to-specify-how-to-handle-external-files"></a>Ulkoisten tiedostojen käsittelemisen määrittäminen  

1.  Kun näyttöön tulee valintaikkuna, poista **Kysy aina ennen tämän tyyppisen tiedoston avaamista** -valintaruudun valinta, jos haluat, että [!INCLUDE[navnow_md](includes/navnow_md.md)] muistaa vaiheessa 2 valitsemasi vaihtoehdon. Kun tämän tyyppistä tiedostoa käsitellään seuraavan kerran, valintaikkuna ei tule näyttöön ja tiedostoa käsitellään vaiheessa 2 määritellyllä tavalla.  

     Vaihtoehtoisesti voit valita **Kysy aina ennen tämäntyyppisen tiedoston avaamista**-valintaruudun, jotta tämän tiedostotyypin vastaanoton yhteydessä avautuu valintaikkuna.  

2.  Valitse **Avaa**, **Tallenna** tai **Peruuta**. Tiedostoa käsitellään valintasi mukaan.  

### <a name="to-specify-how-to-handle-automation-objects"></a>Automaatio-objektien käsittelemisen määrittäminen  

Kun näyttöön tulee valintaikkuna, valitse **Salli aina** -valintaruutu, jos haluat, että [!INCLUDE[navnow_md](includes/navnow_md.md)] suorittaa tämän tyyppisen automaatio-objektin aina. Seuraavan kerran, kun tämän tyyppinen automaatio-objekti on tarkoitus suorittaa, valintaikkuna ei avaudu ja automaatio-objekti suoritetaan suoraan.  

Vaihtoehtoisesti voit valita **Älä salli** -valintaruudun. Seuraavan kerran, kun tämän tyyppinen automaatio-objekti on tarkoitus suorittaa, näkyville avautuu valintaikkuna ja automaatio-objektia ei suoriteta.  

## <a name="CancelPersonalization"></a>Mukauttamisen peruuttaminen
Mukauttamisen peruuttaminen voidaan jakaa kahteen luokkaan:

-   Tehtyjen muutosten peruuttaminen **Mukauta**-toiminnolla.
-   Peruskäyttöliittymän muutosten peruuttaminen.

### <a name="cancel-customization"></a>Mukauttamisen peruuttaminen
Jos haluat peruuttaa kaikki sivulle nykyisellä käyttäjätunnuksellasi tai ennen käyttöliittymämukautusten peruutusta tekemäsi käyttöliittymämukautukset, voit käyttää **Poista käyttäjän mukautus** -ikkunaa. Sivun malli, josta olet poistanut personointisi, nollataan profiilisi oletuskonfiguroinnin mukaiseksi.  

Jos haluat peruuttaa sivun tietylle käyttöliittymäalueelle, kuten valintanauha, tekemäsi käyttöliittymämukautuksen, voit käyttää **Palauta oletukset**-painiketta **Mukauta**-ikkunassa. Tämän sivun erityisen käyttöliittymäalueen malli nollataan profiilisi oletuskonfiguroinnin mukaiseksi.  

#### <a name="to-cancel-all-ui-customization-that-you-have-made-to-a-page"></a>Kaikkien sivulle tekemiesi käyttöliittymän mukautusten peruuttaminen  

1.  Anna **Haku**-ruudussa **Poista käyttäjän mukautus** ja valitse sitten vastaava linkki.  

2.  Valitse sivu, jossa haluat perua käyttöliittymän muokkauksen ja valitse sitten **Koti** -välilehdellä **Katsele** -ryhmässä **Poista**.  

> [!NOTE]  
>  Kaikki ne sivun käyttöliittymän mukautukset on peruutettu, jotka olet koskaan tehnyt tälle sivulle nykyisen käyttäjän kirjautumisen aikana tai sen jälkeen, kun viimeksi käytit **Poista käyttäjän mukautus** -painiketta. Sivun malli, josta olet poistanut personointisi, nollataan profiilisi oletuskonfiguroinnin mukaiseksi, kuten järjestelmänvalvoja on sen konfiguroinut tai kuten [!INCLUDE[navnow](includes/navnow_md.md)] on asentanut.  

#### <a name="to-cancel-ui-customization-that-you-have-made-to-a-ui-area-on-a-page"></a>Sivun käyttöliittymäalueelle tekemiesi käyttöliittymän mukautusten peruuttaminen  

1.  Valitse sivulla, jonka käyttöliittymän aluetta, kuten valintanauhaa, olet mukauttanut, **Sovellus**-valikon ![Sovellus-valikon painike valikkorivillä](media/applicationmenuicon.png "ApplicationMenuIcon") kuvake. Valitse sitten **Mukauta** ja lopuksi **Mukauta<UI area>**.  

2.  Valitse **Mukauta**-ikkunan alaosassa **Palauta oletukset** -painike.  

> [!NOTE]  
>  Kaikki ne käyttöliittymäalueen mukautukset on peruutettu, jotka olet koskaan tehnyt tälle sivulle nykyisen käyttäjän kirjautumisen aikana tai sen jälkeen, kun viimeksi käytit **Palauta oletukset** -painiketta. Sivun käyttöliittymäalueen malli, josta olet poistanut personointisi, nollataan profiilisi oletuskonfiguroinnin mukaiseksi, kuten järjestelmänvalvoja on sen konfiguroinut tai kuten [!INCLUDE[navnow](includes/navnow_md.md)] on asentanut.

### <a name="cancel-basic-ui-changes"></a>Peruskäyttöliittymän muutosten peruuttaminen
Voit peruuttaa peruskäyttöliittymän muutokset avaamalla roolikeskuksen **Palauta käyttäjän määrittämät asetukset** -ikkuna.  

Peruskäyttöliittymän muutoksia ovat esimerkiksi
 -  ikkunan koon ja sijainnin muuttaminen
 -  sarakkeiden leveyden muuttaminen
 -  sarakeotsikoiden korkeuden muuttaminen
 -  luettelon sarakkeiden lajitteleminen
 -  luetteloiden näyttäminen kaaviona
 -  ulkoisten tiedostojen ja automaatio-objektien käsittelyn määrittäminen  

#### <a name="to-cancel-basic-ui-changes"></a>Peruskäyttöliittymän muutosten peruuttaminen

1.  Siirry roolikeskukseen.  

     Valitse **Sovellus**-valikossa ![Valikkorivin sovellusvalikon painike](media/applicationmenuicon.png "ApplicationMenuIcon") **Mukauta** ja sitten **Palauta käyttäjän määrittämät asetukset**.  

2.  Valitse **Palauta käyttöliittymän asetukset** -painike. Voit peruuttaa myös päätöksesi liittyen tiedostojen käsittelyyn ja automaatio-objekteihin painamalla vaihtoehtoisesti **Palauta kaikki**-painiketta.  

 Kaikki ne käyttöliittymän perusmuutokset on peruutettu, jotka olet koskaan tehnyt [!INCLUDE[navnow_md](includes/navnow_md.md)] -järjestelmään nykyisen käyttäjän kirjautumisen aikana, tai sen jälkeen kun painoit viimeksi **Palauta käyttöliittymän asetukset** -painiketta. Käyttöliittymä palautetaan profiilin oletusarvojen mukaiseksi.  

#### <a name="to-cancel-your-decision-for-running-or-saving-external-files"></a>Ulkoisten tiedostojen suorittamis- tai tallentamispäätöksen peruuttaminen  

1.  Siirry roolikeskukseen.  

     Valitse **Sovellus**-valikossa ![Valikkorivin sovellusvalikon painike](media/applicationmenuicon.png "ApplicationMenuIcon") **Mukauta** ja sitten **Palauta käyttäjän määrittämät asetukset**.  

2.  Valitse **Palauta tiedoston käsittelypäätös** -painike. Voit vaihtoehtoisesti peruuttaa myös näkymän muutokset ja päätökset liittyen automaatio-objektien käsittelyyn painamalla **Palauta kaikki**-painiketta.  

 Kaikki tiedostotyyppien oletusarvoiseen käsittelyyn liittyvät päätökset, jotka olet koskaan tehnyt tällä käyttäjätunnuksella, tai sen jälkeen, kun viimeksi käytit **Asiakasohjelman tiedoston käyttöoikeus** -painiketta, peruutetaan ja palautetaan profiilisi oletusarvoihin. Seuraavan kerran, kun [!INCLUDE[navnow_md](includes/navnow_md.md)] vastaanottaa minkä tahansa tyyppisen ulkoisen tiedoston, aukeaa valintaikkuna, joka sisältää vaihtoehdot **Tallenna**, **Suorita** ja **Peruuta**.  

### <a name="to-cancel-your-decision-for-handling-automation-objects"></a>Automaatio-objektien käsittelypäätöksen peruuttaminen  

1.  Siirry roolikeskukseen.  

     Valitse **Sovellus**-valikossa ![Valikkorivin sovellusvalikon painike](media/applicationmenuicon.png "ApplicationMenuIcon") **Mukauta** ja sitten **Palauta käyttäjän määrittämät asetukset**.  

2.  Valitse **Palauta automaatiopäätökset**-painike. Voit vaihtoehtoisesti peruuttaa myös näkymän muutokset ja päätökset liittyen ulkoisten tiedostojen tallennukseen painamalla **Palauta kaikki**-painiketta.  

 Kaikki ne automaatio-objektien suorittamiseen liittyvät päätökset on peruutettu, jotka olet koskaan tehnyt nykyisen käyttäjän kirjautumisen aikana, tai sen jälkeen kun painoit viimeksi **Palauta automaatiopäätökset** -painiketta. Tiedostonkäsittelytoiminta on nollattu profiilisi oletuskonfiguroinnin mukaiseksi. Ensi kerralla, kun [!INCLUDE[navnow_md](includes/navnow_md.md)] ajaa minkä tahansa tyyppisen automaatio-objektin, ohjelma avaa valintaruudun, jossa on vaihtoehdot **Salli aina** ja **Älä salli**.    

<!--Use the following table to get more information about customizing the different elements of the UI.

| To | See |
| --- | --- |
| Change which actions to show on the ribbon and how the actions are grouped. |[How to: Customize FastTabs](purchasing-how-record-purchases.md) |
|Change which FastTabs to show and which fields to include on the FastTabs.|[How to: Request Quotes](purchasing-how-request-quotes.md)|
|Add, remove, or arrange columns in a list or document-lines that represent fields in the underlying tables. |[ How to: Add or Remove Columns in a List or on Document Lines](purchasing-how-purchase-products-sale.md) |
| Rename or rearrange buttons, create a new menu button, add a link to a menu, or rearrange the order of a menu. |[ How to: Customize the Navigation Pane](purchasing-how-correct-cancel-unpaid-purchase-invoices.md) |
| Add a link from a department page to your Role Center. |[How to: Process Purchase Returns or Cancellations](purchasing-how-register-new-vendors.md) |
|Add a chart to your Role Center or to a list page.|[How to: Combine Receipts on a Single Invoice](purchasing-how-to-combine-receipts.md)|
| Unod personalization that you have made to your user interface, either for a specific area on a page, such as a ribbon, or for the whole page.|[How to: Cancel Personalization](ui-customization-cancel.md)|
-->


## <a name="see-also"></a>Katso myös
[Työtilan mukauttaminen Dynamicsin verkkoasiakasohjelmassa](ui-personalization-user.md)  
[Mukautuksen yleiskuvaus](ui-personalization-overview.md)  

