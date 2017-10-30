---
title: "Mukautuksen hallinta järjestelmänvalvojana"
description: "Lisätietoja käyttöliittymän mukauttamisesta omaan työskentelytapaan sopivaksi."
documentationcenter: 
author: jswymer
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.date: 07/26/2017
ms.author: jswymer
ms.prod: dynamics-nav-2018
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: e3d088c35efca4d62b7db1f0d44d5ef2958317d4
ms.contentlocale: fi-fi
ms.lasthandoff: 10/16/2017

---
# <a name="managing-personalization-as-an-administrator"></a>Mukautuksen hallinta järjestelmänvalvojana
Käyttäjät voivat mukauttaa työtilansa omien mieltymystensä mukaiseksi. Järjestelmänvalvojana voit ohjata ja hallita mukauttamista poistamalla sivujen mukautusmahdollisuus käyttäjiltä ja poistamalla käyttäjien mahdollisesti tekemät mukautukset.

## <a name="disable-personalization-for-a-profile"></a>Profiilin mukauttamisen poistaminen
Voit estää sivujen mukauttamisen kaikilta tiettyyn profiiliin kuuluvilta käyttäjiltä.
1.  Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, syötä **Profiilit** ja valitse sitten aiheeseen liittyvä linkki.
2.  Valitse luettelossa muokattava profiili.
3.  Valitse **Poista mukauttaminen käytöstä** -valintaruutuja valitse sitten **OK**.

## <a name="clear-user-personalizations"></a>Käyttäjän mukautusten tyhjentäminen

Mukautetun sivun muutosten tyhjentäminen palauttaa sivun mukautuksia edeltävän alkuperäisen asettelun. Käyttäjien sivulle tekemät mukautukset voi tyhjentää kahdella tavalla: käyttämällä **Poista käyttäjän mukautus** -sivua tai käyttämällä **Käyttäjän mukautuskortti** -sivua.

### <a name="clear-user-personalizations-by-using-the-delete-user-personalization-page"></a>Käyttäjän mukautusten tyhjentäminen Poista käyttäjän mukautus -sivun avulla

**Poista käyttäjän mukautus** -sivulla voit tyhjentää mukautukset sivu- ja käyttäjäkohtaisesti.

1.  Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, kirjoita **Poista käyttäjän mukautus** ja valitse sitten aiheeseen liittyvä linkki.

    Sivulla on luettelo kaikista mukautetuista sivuista ja käyttäjästä, jolle se kuuluu.

    >[!NOTE]
    > **Vanha mukautus** -sarakkeen valintamerkki ilmaisee, että mukautus on tehty ainoastaan [!INCLUDE[nav_windows_md](includes/nav_windows_md.md)] -asiakasohjelmassa ja/tai se on tehty versiota [!INCLUDE[navnow_md](includes/navnow_md.md)] edeltävässä [!INCLUDE[nav_web_md](includes/nav_web_md.md)] -asiakasohjelmassa. Mukautus estetään näiden sivujen mukautusta [!INCLUDE[nav_web_md](includes/nav_web_md.md)] -asiakasohjelmalla yrittäviltä käyttäjiltä, elleivät he ensin valitse sivun lukituksen poistamista. Lisätietoja on kohdassa [Lukituksella estetty sivun mukauttaminen](ui-personalization-locked.md). Lisätietoja [!INCLUDE[nav_windows_md](includes/nav_windows_md.md)]- ja [!INCLUDE[nav_web_md](includes/nav_web_md.md)] -asiakasohjelmien välisestä mukauttamisesta on kohdassa [Mukautuksen käsitteleminen Dynamics NAVin Windows- ja verkkoasiakasohjelmien välillä](ui-personalization-overview.md#PersonalizationWinWeb).

2. Valitse ensin poistettava tapahtuma ja sitten **Poista**-toiminto.

    Käyttäjä näkee muutokset kirjautuessaan sisään seuraavan kerran.

### <a name="clear-user-personalizations-by-using-the-user-personalization-card-page"></a>Käyttäjän mukautusten tyhjentäminen Käyttäjän mukautuskortti -sivun avulla

Voit tyhjentää **Käyttäjän mukautuskortti** -sivulla tietyn käyttäjän kaikki mukautukset. Tämä edellyttää taulukon 2000000072 **Profiili** kirjoitusoikeuksia.

1.  Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, kirjoita **Käyttäjän mukautus** ja valitse sitten aiheeseen liittyvä linkki.

    **Käyttäjän mukautus** -sivulla on luettelo kaikista käyttäjistä, joilla mahdollisesti on mukautettuja sivuja. Jos käyttäjä ei löydy luettelosta, kyseisellä käyttäjällä ei ole mukautettuja sivuja.

2. Valitse ensin käyttäjä luettelossa ja sitten **Muokkaa**-toiminto.

3.  Valitse **Toiminnot**-välilehdessä **Tyhjennä mukautetut sivut**.

    Käyttäjä näkee muutokset kirjautuessaan sisään seuraavan kerran.

## <a name="see-also"></a>Katso myös
[Mukautuksen yleiskuvaus](ui-personalization-overview.md)  
[Työtilan mukauttaminen](ui-personalization-user.md)  
[[!INCLUDE[navnow_md](includes/navnow_md.md)] -ohjelman käyttäminen](ui-work-product.md)  
[Toimintaohje: Roolikeskuksen vaihtaminen](change-role.md)  
