---
title: "Käyttöliittymän määrittäminen käyttäjiä varten"
description: "Järjestelmänvalvojana voit määrittää yrityksen oletusarvoiset käyttöliittymät mukauttamalla sivun asetteluita eri yrityksen käyttäjäprofiileille."
author: jswymer
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: customize pages, configure user interface, customize UI
ms.date: 07/01/2017
ms.author: jswymer
ms.prod: dynamics-nav-2018
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 7ba3d45a856eb38fe99fc5012b4e2f2d8609f9ce
ms.contentlocale: fi-fi
ms.lasthandoff: 10/16/2017

---
# <a name="configuring-the-user-interface-ui-for-users"></a>Käyttöliittymän määrittäminen käyttäjiä varten
Järjestelmänvalvojana voit määrittää yrityksen oletusarvoiset käyttöliittymät mukauttamalla sivun asetteluita eri yrityksen käyttäjäprofiileille. Tämän työn voi suorittaa vain järjestelmänvalvoja, jolla on SUPER-käyttöoikeudet. Lisäksi on määritettävä profiilit ja kohdistettava niihin asianmukaiset käyttäjät. Lisätietoja on kohdassa [Käyttäjien, profiilien ja roolikeskusten hallinta](admin-users-profiles-roles.md).  
  
Voit määrittää käyttöliittymän useille käyttäjille mukauttamalla sivut profiilille, johon käyttäjät on määritetty. Voit tehdä tämän [!INCLUDE[nav_windows](includes/nav_windows_md.md)] -ohjelman avulla mukauttamalla samalla tavalla kuin yksittäiset käyttäjät mukauttavat omia työtilojaan eli käyttämällä **Mukauta**-toimintoa. Erona on se, että [!INCLUDE[nav_windows](includes/nav_windows_md.md)] avataan määritystilassa. Tavallisia mukautuksia ovat toimenpiteiden valitseminen valintanauhaan, kenttien sijoittaminen pikavälilehtiin tai tietoruutuihin ja valikkonimikkeiden valitseminen siirtymisruutuun. 

> [!TIP]  
>  Voit ottaa profiilin käyttöliittymän määritykset nopeasti käyttöön, jos olet jo määrittänyt profiilin toisessa [!INCLUDE[d365fin](includes/d365fin_md.md)] -tietokannassa. Tämän jälkeen voit viedä profiilin ja tuoda sen nykyiseen tietokantaan. Lisätietoja on kohdassa [Profiilien vieminen ja tuominen](admin-profiles.md#ExportImportProfile).  
  
## <a name="general-information"></a>Yleiset tiedot
Ennen kuin aloitat käyttöliittymän määrittämisen, ota huomioon seuraavat tiedot:
-   Ennenkuin aloitat käyttöliittymän määrittämisen, sovellus voidaan määrittää näyttämään tai piilottamaan käyttöliittymäelementit (kuten kentät, pikavälilehdet ja tietoruudut) käyttöoikeussopimuksen tai käyttäjän oikeuksien perusteella. Lisätietoja tästä on kohdassa [Käyttöliittymän elementtien poistaminen käyttöoikeuksien mukaan](https://msdn.microsoft.com/en-us/dynamics-nav/removing-elements-from-the-user-interface-according-to-permissions).

    Kun haluat nähdä käyttöliittymäelementtien poistotoiminnon vaikutuksen, voit kirjautua sisään testikäyttäjänä, jolla on määritettävän profiilin käyttöoikeuksien joukko. Syy on se, että sinulla järjestelmänvalvojana on SUPER-lupasarja ja siksi et voi nähdä ja testata seurauksena olevaa käyttöliittymää oman sisäänkirjautumisesi aikana.    
-   Kun muutat käyttöliittymän määritystä käyttäjän mukauttamalle sivulle, käyttäjän tekemä käyttöliittymän mukautus säilytetään ja sitä ei korvata uuden sivun määrityksillä. Vastaavasti, kun peruutat sivulle tekemäsi käyttöliittymän määritykset, jotka käyttäjä on sen jälkeen mukauttanut, käyttäjän käyttöliittymän mukautusta ei peruuteta.
-   Ainoa tilanne, jossa käyttöliittymän konfigurointi korvaa käyttöliittymän personoinnin on silloin, kun konfigurointi siirtää käyttöliittymäelementin. Esimerkiksi, jos järjestelmänvalvoja poistaa käyttäjän uudelleen nimeämän tai siirtämän kentän, tällöin kenttä on edelleen poistettu käyttäjän käyttöliittymästä.
-   Voit tallentaa samasta sivusta useita käyttöliittymän määrityksiä sivun eri liitäntäpisteiden perusteella. Esimerkiksi **Myyntitilaukset**-ikkuna on mahdollista mukauttaa niin, että se näyttää erilaiselta avattaessa **Asiakaskortti**-ikkunasta ja **Myyntitilauksen käsittelijä**-roolikeskuksesta. Kohta, josta käytät muokattavaa sivua, tallennetaan tähän erityiseen sivun muokkaukseen. Näin ollen tietokannassa saattaa olla useita sivun mukautustietueita samalle, kuten **Poista profiilin kokoonpano** -ikkunassa näkyy.  
-   Käyttäjät voivat muuttaa ikkunoiden kokoa ja sarakkeiden leveyttä omalla tietokoneella työskennellessään. Tällaiset profiilin käyttöliittymän määrityksen aikana tehdyt muutoksia perusnäkymään ei tallenneta profiiliin. Ne eivät siis ole profiilia käyttävien käyttäjien käytettävissä. Näkymän perusmuutokset ovat tietokonekohtaisia.   

## <a name="configure-a-profile-with-the-includenavwindowsincludesnavwindowsmdmd-in-configuration-mode"></a>Profiilin määrittäminen [!INCLUDE[nav_windows](includes/nav_windows_md.md)] -ohjelman avulla määritystilassa
1.  Avaa komentokehote ja kirjoita siihen seuraava komento, joka muuttaa [!INCLUDE[nav_windows](includes/nav_windows_md.md)] -ohjelman asennuskansion. Esimerkki:  
  
    ```  
    cd C:\Program Files\(x86)\Microsoft Dynamics NAV\110\RoleTailored Client  
    ```  
  
2.  Kirjoita seuraava komento, kun haluat käynnistää [!INCLUDE[nav_windows](includes/nav_windows_md.md)] -ohjelman määritystilassa tietylle profiilille:  
  
    ```  
    Microsoft.Dynamics.Nav.Client.exe -configure -profile:"profileid"  
    ```  
  
     Korvaa **profileid** sillä profiilin nimellä, jonka haluat määrittää.  
  
     Voit määrittää esimerkiksi talouspäällikön profiilin seuraavan komennon avulla:  
  
    ```  
    Microsoft.Dynamics.Nav.Client.exe -configure -profile:"Accounting Manager"  
    ``` 

3. Nyt voit aloittaa käyttöliittymän määrittämisen. Toiminnot ovat samat kuin silloin, kun yksittäiset käyttäjät mukauttavat omia työtilojaan. Lisätietoja on kohdassa [Työtilan mukauttaminen [!INCLUDE[nav_windows](includes/nav_windows_md.md)]](ui-personalization-windows-client.md) -ohjelmassa. 

## <a name="cancel-ui-configuration"></a>Käyttöliittymän määrityksen peruuttaminen
Voit peruuttaa profiilin määrityksenä tekemäsi käyttöliittymän mukautukset kolmella tavalla.  
  
-   Peruuta kaikki profiiliin tekemäsi käyttöliittymän mukautukset käyttämällä **Tyhjennä määritetyt sivut**-painiketta **Profiilikortti** -ikkunassa.  
  
-   Peruuta käyttöliittymän mukautus, jonka olet suorittanut profiilin tietyille sivuille poistamalla rivit **Poista profiilin kokoonpano** -ikkunassa.  
  
-   Peruuta käyttöliittymämukautus, jonka olet tehnyt profiilin tietyn sivun tietylle käyttöliittymän alueelle käyttämällä **Palauta oletukset**-painiketta **Mukauta**-ikkunassa.  
  
### <a name="general-information"></a>Yleiset tiedot  
-   Käyttäjät voivat tehdä käyttöliittymän mukautuksia oman kirjautumistunnuksensa osalta ja mukauttaa käyttöliittymäänsä. Kun peruutat sivulle tekemäsi käyttöliittymän määritykset, jotka käyttäjä on sen jälkeen mukauttanut, käyttäjän käyttöliittymän mukautusta ei peruuteta. Vastaavasti, kun teet uuden käyttöliittymän mukautuksen sivulle, jonka käyttäjä on mukauttanut, käyttäjän tekemä käyttöliittymän mukautus säilytetään ja sitä ei korvata uuden sivun määrityksillä.  

    Ainoa tilanne, jossa käyttöliittymän konfigurointi korvaa käyttöliittymän personoinnin on silloin, kun konfigurointi siirtää käyttöliittymäelementin. Esimerkiksi, jos järjestelmänvalvoja poistaa käyttäjän uudelleen nimeämän tai siirtämän kentän, tällöin kenttä on edelleen poistettu käyttäjän käyttöliittymästä.  
  
-   Käyttäjät voivat peruuttaa sivuihin tekemänsä käyttöliittymän mukautukset oman kirjautumistunnuksensa osalta **Poista profiilin kokoonpano** -ikkunassa ja **Palauta oletukset** -painikkeella **Mukautus**-ikkunassa. Kun näin tehdään, sivujen asetteluksi palautetaan mikä tahansa käyttöliittymän mukautus, jonka järjestelmänvalvoja on määrittänyt profiilille. Jos profiilia ei ole määritetty, käyttäjän sivujen asetteluksi palautetaan oletusprofiilimääritys. Lisätietoja siitä, miten käyttäjät peruuttavat mukauttamisen, on kohdassa [Mukauttamisen peruuttaminen](ui-personalization-windows-client.md#CancelPersonalization).
  
### <a name="to-cancel-all-ui-customization-that-you-have-made-for-a-profile"></a>Kaikkien profiilille tekemiesi käyttöliittymän mukautusten peruuttaminen  
  
1.  Syötä **Etsi**-ruudussa **Profiilit** ja valitse sitten vastaava linkki.  
  
2.  Valitse profiili, jossa haluat perua kaikki käyttöliittymän muokkaukset ja valitse sitten **Koti** -välilehdellä **Hallitse** -ryhmässä **Muokkaa**.  
  
3.  Valitse **Profiilikortti**-ikkunassa **Toiminnot**-välilehdellä **Funktiot**-ryhmässä **Tyhjennä määritetyt sivut**.  
  
> [!NOTE]  
>  Kaikki profiilin käyttöliittymän mukautukset, sekä sovelluksen kanssa asennetut että järjestelmänvalvojan tekemät, peruutetaan. Tietokannassa ei ole profiiliin liittyviä sivuasetteluja.  
  
### <a name="to-cancel-ui-customization-that-you-have-made-for-specific-page-for-a-profile"></a>Profiilin tietylle sivulle tekemiesi käyttöliittymän mukautusten peruuttaminen  
  
1.  Syötä **Etsi**-ruudussa **Poista profiilin kokoonpano** ja valitse sitten vastaava linkki.  
  
2.  Valitse profiili/sivuasetus, jossa haluat perua käyttöliittymän muokkauksen ja valitse sitten **Koti** -välilehdellä **Hallitse** -ryhmässä **Poista**.  
  
    > [!IMPORTANT]  
    >  Jos olet määrittänyt erilaiset saman sivun käyttöliittymän mukautukset perustuen sivulle johtaviin erilaisiin polkuihin, jokainen sivun mukautus näkyy **Poista profiilin kokoonpano**-ikkunan luettelossa samoilla tiedoilla. Tietoja, joiden avulla rivin ja polun yhteys voidaan tunnistaa, ei ole. Tämän vuoksi sinun on joko poistettava rivit yksitellen ja tehtävä visuaalinen tarkistus sivulle tai poistettava kaikki profiilin/sivun käyttöliittymän mukautuksen omaavat rivit.
    >    
    >  Kaikki ne profiilin sivun käyttöliittymän mukautukset on peruutettu, jotka olet koskaan tehnyt asennuksen aikana tai sen jälkeen, kun viimeksi käytit **Poista profiilin kokoonpano** -ikkunaa. Sivun asetteluksi palautetaan sivun objektin vakioasettelu.  
  
### <a name="to-cancel-ui-customization-that-you-have-made-for-a-specific-ui-area-for-a-specific-page-for-a-profile"></a>Profiilin tietyn sivun tietylle käyttöliittymäalueelle tekemiesi käyttöliittymän mukautusten peruuttaminen  
  
Voit peruuttaa muutokset, jotka teit yksittäisille käyttöliittymäalueille, kuten valintanauhaan, **Mukauta** -ikkunan **Palauta oletusarvot** -painikkeen avulla. Vaihtoehtoisesti voit kumota kaikki käyttöliittymän muutokset, jotka olet tehnyt profiilin **Poista profiilin kokoonpano** -ikkunan avulla.  
  
Tietyn sivun käyttöliittymäalueen profiilin käyttöliittymän mukautus on peruutettu. Sivun käyttöliittymäalueen malli, josta olet poistanut personointisi, palautetaan profiilisi oletuskonfiguroinnin mukaiseksi. Tämä oletuskonfigurointi on järjestelmänvalvojan määrittämä tai sovelluksen oletusasetus.  
  
## <a name="see-also"></a>Katso myös  
[[!INCLUDE[navnow_md](includes/navnow_md.md)] -sovelluksen mukauttaminen](ui-customizing-overview.md)   
