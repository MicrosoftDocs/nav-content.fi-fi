---
title: "Työtilan mukauttaminen Dynamics NAVin verkkoasiakasohjelmassa"
description: "Lisätietoja käyttöliittymän mukauttamisesta omaan työskentelytapaan sopivaksi."
documentationcenter: 
author: jswymer
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: customize, personalize, personalize page, personalization, hide columns, remove fields, move fields
ms.date: 07/26/2017
ms.prod: dynamics-nav-2018
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: c266842d4a64b62c90dab8db26f5206f9a10e4cc
ms.contentlocale: fi-fi
ms.lasthandoff: 10/16/2017

---
# <a name="personalizing-your-workspace-using-the-dynamics-nav-web-client"></a>Työtilan mukauttaminen Dynamics NAVin verkkoasiakasohjelmassa
<!--NAV in the Web client-->
Voit *mukauttaa* työtilan työskentelyysi ja valintoihisi sopivaksi muuttamalla sivujen ulkoasua siten, että vain tarvitsemasi tiedot näkyvät siellä, missä niitä tarvitset. Mukauttamalla tehdyt muutokset koskevat vain omaa näkymääsi; muut käyttäjät eivät siis näe mukautuksiasi.

Sivun tyypin ja sen sisällön perusteella voit

-   lisätä, siirtää ja poistaa kenttiä
-   lisätä, siirtää ja poistaa luettelon sarakkeita
-   muuttaa luettelon sarakkeiden kiinnitysruutua. Kiinnitysruutu lukitsee vähintään yhden sarakkeen luettelon vasemmalle puolelle siten, että se näkyy myös silloin, kun näkymää vieritetään vaakasuunnassa.
-   siirtää ja poistaa jonoja (ruutuja)
-   siirtää ja poistaa osia. Osat ovat osia tai alueita sivulla ja niissä on esimerkiksi useita kenttiä, toinen sivu, kaavio tai ruutuja.  

## <a name="to-personalize-a-page"></a>Sivun mukauttaminen

1. Valitse oikeassa yläkulmassa ensin ![Asetukset](media/ui-experience/settings_icon_small.png "Roolikeskuksen Asetukset-kuvake") -kuvake ja sitten **Mukauta**.

    **Mukautetaan**-palkki tulee yläreunaan osoittamaan, että voit aloittaa muutosten tekemisen.

    ![Mukautustila](media/ui_personalize_mode_small.png "Mukautustila")

2.  Siirry mukautettavalle sivulle.

    Jos palkissa on lukkokuvake, lisätietoja on kohdassa [Lukittu sivu](ui-personalization-locked.md).

3.  Osoita mukautettavaa aluetta, kuten kenttää tai sarakkeen otsikkoa luettelossa. Mukautettavat kohdat osoitetaan joko nuolella tai reunuksilla.
<!--
    -  If a component can be personalized, an arrow head (![Personalization indicator arrow left](media/ui_personalize_arrow_left.png "Personalization indicator arrow left") or ![Personalization indicator arrow down](media/ui_personalize_arrow_down.png "Personalization indicator arrow down")) appears.
    -   If the component is a part, the extent of the part is indicated by a border.
    -   The freeze pane in a list is indicated by a vertical line along the entire right-side of the last column of the freeze pane.
    -->

4.  Voit tehdä muutoksia tämän taulukon avulla:     <table>
        <tr><th>Tehtävä toimi</td><th>Ohjeet</th></tr>
        <tr><td>Esimerkiksi kentän, luettelon sarakkeen, ruudun tai osan siirtäminen</td><td> Osoita siirron kohdetta ja vedä se uuteen sijaintiin. Sijainti osoitetaan paksulla vaaka- tai pystyviivalla.</td></tr>
        <tr><td>Kohteen poistaminen</td><td>Valitse ensin nuolenpää ja sitten <b>Poista</b>. </td></tr>
        <tr><td>Kentän tai sarakkeen lisääminen</td><td>Valitse <b>Mukautetaan</b>-palkissa ensin <b>Lisää</b> ja sitten <b>Kenttä</b>.<br /></br><b>Lisää kenttä sivulle</b> -ruutu avautuu näytössä oikealla. Siinä on luettelo sivulle lisättävistä kentistä. Jos kentässä on merkintä <b>Sijoitettu</b>, kenttä on jo sivulla. Jos kentässä on merkintä <b>Valmis</b>, kenttä ei ole vielä sivulla.<br /></br>Lisää kenttä vetämällä se ruudusta haluamaasi sijaintiin. Sijainti osoitetaan paksulla vaaka- tai pystyviivalla.</td></tr>
        <tr><td>Kiinnitysruudun muuttaminen toiseen sarakkeeseen luettelossa</td><td>Valitse sen sarakkeen nuolenpää, jonka haluat olevan kiinnitysruudun viimeinen sarake, ja valitse sitten <b>Määritä kiinnitysruutu</b>.<br /><br/>Jos haluat määrittää kiinnitysruudun takaiseen alkuperäiseen sijaintiin, valitse ensin nykyisen kiinnitysruutusarakkeen nuolenpää ja sitten <b>Tyhjennä kiinnitysruutu</b>. Huomautus: Et voi poistaa alkuperäistä kiinnitysruutua. Käytössä on aika kiinnitysruutu, jossa on vähintään yksi sarake.</td></tr>
      </table>

    > [!IMPORTANT]  
    >   Luetteloon ei voi tehdä muutoksia, jos luettelo näytetään ruutuina. Sivu on ensin vaihdettava luettelonäkymään valitsemalla ![Näytä luettelona](media/ui_show_as_list_icon.png "Vasen Näytä luettelona -nuoli") -kuvake.

5.  Voit jatkaa muutosten tekemistä samalla sivulla tai siirtyä toiselle sivulle. Muutokset tallennetaan automaattisesti samalla, kun niitä tehdään. Kun olet valmis, valitse **Mukautetaan**-palkissa **Valmis**.

## <a name="clear-personalization-to-change-a-page-back-to-its-original-layout"></a>Sivun palauttaminen alkuperäiseen asetteluun tyhjentämällä mukautukset
Haluat ehkä joissain vaiheessa kumota kaikki sivulle aiemmin tehdyt mukautusmuutokset ja palauttaa sivun alkuperäisen ulkoasun. Voit tehdä sen valitsemalla **Mukautetaan**-palkissa ensin **Lisää** ja sitten **Tyhjennä mukautus**.

## <a name="personalization-in-detail"></a>Lisätietoja mukauttamisesta
Seuraavat seikat auttavat ymmärtämään mukauttamista entistä paremmin.  
-   Kun teet muutoksia luettelosta avautuvalle korttisivulle, muutokset koskevat kaikki kyseisestä luettelosta avattavia tietueita. Oletetaan esimerkiksi, että avaat tietyn asiakkaan Asiakasluettelo-sivulta ja mukautat sivua lisäämällä siihen kentän. Kun avaat luettelossa muita asiakkaita, myös lisäämäsi kenttä on näkyvissä.
-   Tekemäsi muutokset koskevat kaikkia roolikeskuksia. Jos esimerkiksi teet muutoksen asiakasluetteloon, kun roolikeskuksen asetuksena on Liiketoimintajohtaja, asiakasluettelon muutos näkyy myös roolikeskuksessa, jonka asetuksena on Myyntitilausten käsittelijä.
-   Ruudun sivulla tehdyt muutokset koskevat sivua kaikissa tilanteissa, joissa se näytetään.  
-   Voit lisätä kenttiä ja sarakkeita vain kyseiseen sivuun perustuvasta ennaltamääritetystä luettelosta. Uusia kenttiä tai sarakkeita ei voi luoda.

## <a name="see-also"></a>Katso myös
[Mukautuksen yleiskuvaus](ui-personalization-overview.md)  
[Mukautuksen hallinta](ui-personalization-manage.md)  
[[!INCLUDE[navnow_md](includes/navnow_md.md)] -ohjelman käyttäminen](ui-work-product.md)  
[Toimintaohje: Roolikeskuksen vaihtaminen](change-role.md)  

