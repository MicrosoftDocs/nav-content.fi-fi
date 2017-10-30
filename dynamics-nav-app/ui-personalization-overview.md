---
title: "Työtilan mukauttaminen – yleiskatsaus"
description: "Lisätietoja käyttöliittymän mukauttamisesta omaan työskentelytapaan sopivaksi."
documentationcenter: 
author: jswymer
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.date: 07/26/2017
ms.author: jswymer
ms.prod: dynamics-nav-2018
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 04334d3bb50b37b9643b848ca4f59b015f03ad04
ms.contentlocale: fi-fi
ms.lasthandoff: 10/16/2017

---
# <a name="personalizing-your-workspace---overview"></a>Työtilan mukauttaminen – yleiskatsaus
Voit *mukauttaa* työtilan työskentelyysi ja valintoihisi sopivaksi muuttamalla sivujen asettelua siten, että vain tarvitsemasi tiedot näkyvät siellä, missä niitä tarvitset. Mukauttamalla tehdyt muutokset koskevat vain omaa näkymääsi; muut käyttäjät eivät siis näe mukautuksiasi.

Voit mukauttaa työtilasi [!INCLUDE[nav_windows_md](includes/nav_windows_md.md)]- ja [!INCLUDE[nav_web_md](includes/nav_web_md.md)] -verkkoasiakasohjelmassa. Mukauttamalla tehtävät muutokset näkyvät myös [!INCLUDE[nav_phone_md](includes/nav_phone_md.md)]- ja [!INCLUDE[nav_web_md](includes/nav_phone_md.md)] -asiakasohjelmissa.
  
> [!NOTE]  
> Yrityksen järjestelmänvalvoja on saattanut jo muokata käyttöliittymäsi rooliriippuvaiseksi malliksi kaikille käyttäjille, joilla on sama profiili kuin sinulla ja jotka käyttävät samaa roolikeskusta. Työtilan mukautukset tallennetaan käyttäjätilille, joten ne säilyvät vaikka järjestelmänvalvoja ottaisi yrityksessä käyttöön uuden roolikohtaisen asettelujoukon. Lisätietoja on kohdassa [Käyttöliittymän määrittäminen](admin-configure-user-interface.md).

## <a name="comparing-personalization-in-the-dynamics-nav-windows-and-web-clients"></a>Dynamics NAVin Windows- ja verkkoasiakasohjelmien mukautusten vertailu
Voit sivun mukaan mukauttaa monia käyttöliittymän osia, kuten kenttien tai sarakkeiden näyttämistä ja sijoittelua sekä valintanauhaan sisällytettäviä toimintoja. Monet näistä muutoksista voidaan tehdä sekä Windows- että verkkoasiakasohjelmassa. Seuraavassa taulukossa on yleiskatsaus kuin asiakasohjelman mukautusominaisuuksista.

|  Mukauta  ||  Windows-asiakasohjelma  |  Verkkoasiakasohjelma  |
|---------------|-|------------------|--------------|
|Pikavälilehtien kentät||||
||Lisäys, siirto, poisto |x|x|
||Näytetään supistetussa otsikossa|x||
||Piilotetaan **Näytä enemmän kenttiä** -toiminnolla|x||
|Luettelot tai asiakirjarivit ||||
||Sarakkeiden lisäys, siirto, poisto  |x|x|
||Kiinnitysruudun lisäys, siirto, poisto  |x|x|
|Tietoruudut|||
||Siirto, poisto|x|x|
||Lisää|x||
||Kenttien lisäys, siirto, poisto|x|x|
|Pinot||||
||Siirto, poisto|x|x|
||Lisää |x||
|Kaaviot||||
||Siirto, poisto|x|x|
||Lisää|x| |
|Valintanauha ja toiminnot||x||
|Siirtymisruutu||x||

Erona on myös se, että Windows-asiakasohjelmalla mukautettaessa samasta sivusta voi olla useita mukautettuja versioita, jotka perustuvat sivun eri liitäntäpisteisiin. Esimerkiksi **Myyntitilaukset**-sivu on mukautettu näyttämään erilaiselta, kun se avataan **Asiakaskortti**-sivulta ja kun se avataan **Myyntitilauksen käsittelijän roolikeskus**-sivulta. Verkkoasiakasohjelmassa mukautetulla sivulla voi olla vain yksi versio, joten muutokset näkyvät sivulla riippumatta siitä, mistä se avataan.

##  <a name="PersonalizationWinWeb"></a>Mukautuksen käsitteleminen Dynamics NAVin Windows- ja verkkoasiakasohjelmien välillä
Ennen sivujen mukauttamisen aloittamista on tiedostettava, miten Windows- ja verkkoasiakasohjelmien välinen mukauttaminen tapahtuu. Jos käytät aina vain joko Windows- tai verkkoasiakasohjelmaa, tämä tieto ole yhtä olennaista. Jos kuitenkin aloitat sivun mukauttamisen kummallakin asiakasohjelmalla tai siirryt Windows-asiakasohjelman käyttäjästä pysyvästi verkkoasiakasohjelman käyttäjäksi, tällä tiedolla on merkitystä.  

-   Jos mukautat tiettyä sivua alusta alkaen Windows-asiakasohjelmassa, näet kyseisen sivun mukautukset myös [!INCLUDE[nav_web_md](includes/nav_web_md.md)] -asiakasohjelmassa.

-   Niin kauan kuin mukautat sivua Windows-asiakasohjelmassa, kaikki mukautukset otetaan käyttöön myös verkkoasiakasohjelman sivulla.

-   Kuitenkin heti kun aloitat sivun mukauttamisen verkkoasiakasohjelmalla, kyseisen sivun mukautus eriytyy kahdessa asiakasohjelmassa ja kummassakin asiakasohjelmassa on oma mukautettu versio. Sivun aiemmat mukautukset tyhjennetään verkkoasiakasohjelmassa, joten sivu palautuu alkuperäiseen asetteluun ja käytännössä joudut aloittamaan sivun mukautuksen alusta. Windows-asiakasohjelmassa olevat aiemmat mukautukset eivät muutu.

- Tämän jälkeen sivu mukautetaan Windows- ja verkkoasiakasohjelmassa erikseen, joten on mahdollista, että sivu näyttää asiakasohjelmissa erilaiselta. Samat sivun mukautukset näkyvät puhelin- ja tablettiasiakasohjelmissa kuin verkkoasiakasohjelmassa.  

> [!Tip]  
>Jos avaat **Poista käyttäjän mukautus** -sivun, näet kaikki kunkin käyttäjät mukauttamat sivut. **Vanha mukautus** -sarake ilmaisee, onko mukautus tehty Windows- vai verkkoasiakasohjelmassa. Jos sarakkeessa on valintamerkki, mukautus tehtiin Windows-asiakasohjelmassa (tai versiota [!INCLUDE[navnow_md](includes/navnow_md.md)] edeltävässä verkkoasiakasohjelmassa).

## <a name="see-also"></a>Katso myös
[Työtilan mukauttaminen Dynamics NAVin Windows-asiakasohjelmassa](ui-personalization-windows-client.md)  
[Työtilan mukauttaminen Dynamics NAVin verkkoasiakasohjelmassa](ui-personalization-user.md)  
[Mukautuksen hallinta](ui-personalization-manage.md)  
[Dynamics NAV -sovelluksen mukauttaminen](ui-customizing-overview.md)  

