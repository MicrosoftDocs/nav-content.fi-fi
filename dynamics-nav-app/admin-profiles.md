---
title: Profiilien ja roolikeskusten hallinta
description: "Lisätietoja Dynamics NAV -ohjelman käyttäjien ja roolikeskusten hallinnasta."
author: jswymer
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: profiles, roles, role centers, user roles
ms.date: 09/01/2017
ms.author: jswymer
ms.prod: dynamics-nav-2018
ms.translationtype: HT
ms.sourcegitcommit: b9b1f062ee6009f34698ea2cf33bc25bdd5b11e4
ms.openlocfilehash: 0d99f95d7c90bae55ea139a958ca098ab10a0a7f
ms.contentlocale: fi-fi
ms.lasthandoff: 10/23/2017

---
# <a name="managing-profiles-and-role-centers"></a>Profiilien ja roolikeskusten hallinta
Profiilit ovat niiden [!INCLUDE[navnow_md](includes/navnow_md.md)] -käyttäjien kokoelmia, jotka jakavat saman roolikeskuksen. Roolikeskus on sivu, jossa voit sijoittaa eri osia. Jokainen osa on säilö, joka voi sisältää muita sivuja tai ennalta määritettyjä järjestelmän osia, kuten Outlook-osan tai osia tehtävien, ilmoitusten tai huomautusten lisäämiseksi.  

## <a name="about-profiles-and-role-centers"></a>Tietoja profiileista ja roolikeskuksista
Profiilien avulla voit linkittää käyttäjät ennalta määritettyihin roolikeskuksiin. Roolikeskus on kaikkien profiilin käyttäjien kotisivu, joka on määritetty profiilin käyttäjien tehtävien ja prioriteettien perusteella. Esimerkiksi tilausten käsittelijän roolikeskus on määritetty niin, että se muuttuu tilausten käsittelijän tehtävien prioriteettien mukaisesti. Roolikeskuksen avulla käyttäjät voivat helposti käyttää päivittäisessä työssä tarvittavia tietoja. Roolikeskus voi esimerkiksi määrittää pinot tai ruudut, jotka näytetään käyttäjälle ensimmäisen sisäänkirjauksen yhteydessä, sekä siirtymissivun linkit.

Käytettävä profiili näkyy roolikeskuksen pääsisältöalueen otsikossa. Järjestelmänvalvoja voi mukauttaa tätä roolikeskusta tietyn roolia tai tietyn yrityksen tarpeisiin. Tilausten käsittelijä -roolikeskusta voi mukauttaa edelleen tietokonekohtaisesti tietyn tilausten käsittelijän tarpeita varten. Tämä henkilö voi mukauttaa roolikeskusta tallentamalla kyselyjä, lisäämällä suodattimia ja lisäämällä tai poistamalla kenttiä.

Profiilit ja roolikeskukset edustavat rooleja ja vastuualueita organisaatiossa. [!INCLUDE[navnow_md](includes/navnow_md.md)] sisältää joukon valmiita profiileja, joista kukin vastaa tiettyä Roolikeskusta ja sisältää siihen linkin. Järjestelmänvalvojat voivat muokata luotuja profiileja tai luoda uusia profiileja.  
  
> [!NOTE]  
>  Profiileja ei ole eksplisiittisesti linkitetty rooleihin ja käyttöoikeuksiin, jotka muodostavat suojausjärjestelmän, mutta profiilien käyttäjillä on oltava käyttöoikeudet, jotka ovat yhdenmukaiset heidän rooliensa kanssa suojausjärjestelmässä. Katso lisätietoja kohdasta [Security in the Role Tailored Environment](http://go.microsoft.com/fwlink?LinkId=147633) MSDN-kirjastossa (englanninkielinen). 

## <a name="to-create-a-profile"></a>Profiilin luominen
1.  Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, syötä **Profiilit** ja valitse sitten aiheeseen liittyvä linkki.  
  
2.  Valitse **Uusi**-toiminto, kun haluat avata **Uusi profiilikortti** -ikkunan.  
  
3.  Anna **Profiilin tunnus** -kentässä nimi, joka kuvaa käyttäjän tarkoitettua roolia.  
  
4.  Kirjoita **Kuvaus**-kenttään profiilitunnuksen kuvaus, esimerkiksi **Tilausten käsittelijä**.  
  
5.  Määritä **Roolikeskuksen tunnus** -kenttäään profiiliin liitettävä roolikeskus.  
  
6.  Jos haluat määrittää tämän roolikeskuksen profiilin oletusroolikeskukseksi, valitse **Oletusroolikeskus**-valintaruutu.  
  
7.  Valitse **OK**-painike. .  
  
Olemassa olevan profiilin muokkaaminen tehdään samoin, paitsi valitset olemassa olevan profiilin Profiili-sivulla **Uusi**-painikkeen valitsemisen sijaan.  


##<a name="copying-a-profile"></a>Profiilin kopioiminen 
Profiilin kopioiminen voi säästää aikaa, jos haluat käyttää profiilissa samanlaisia asetuksia, ja haluat muuttaa vain joitakin asetuksia.

1.  Avaa kopioitava profiili ja valitse sitten **Kopioi profiili** -toiminto.

2.  Syötä **Uuden profiilin tunnus** -kenttään sen profiilin nimi, jonka haluat kopioida. 

3.  Määritä **Uuden profiilin alue** -kenttään jokin seuraavista arvoista:

    - **Järjestelmä**, kun haluat määrittää uuden profiilin kaikkien sovellusta käyttävien vuokraajatietokantojen käytettäväksi.
    - **Vuokraaja**, kun haluat määrittää profiilin vain nykyisen vuokraajatietokannan käytettäväksi. 
4. Valitse **OK**-painike, kun olet valmis.

## <a name="ExportImportProfile"></a>Profiilien vieminen ja tuominen

Voit viedä profiileja XML-tiedostoina [!INCLUDE[d365fin](includes/d365fin_md.md)] -tietokantaan ja tuoda niitä tietokannasta. Profiilin vieminen ja tuominen voi säästää aikaa, kun määrität käyttöliittymää. Voit käyttää aiemmin luotua profiilimääritystä sen sijaan, että määrittäisit profiilin alusta alkaen. Jos profiili on määritetty [!INCLUDE[d365fin](includes/d365fin_md.md)] -tietokannassa ja haluat käyttää sen tai osan samasta profiilimäärityksestä uudelleen toisessa tietokannassa, voit viedä profiilin XML-tiedostoon. Tämän jälkeen voit tuoda profiilin XML-tiedoston toiseen tietokantaan.

-   Voit viedä profiilin avaamalla hakutoiminnon ja avaamalla sitten **Vie profiilit** -sivun. Valitse profiili luettelosta ja valitse sitten **Vie**-toiminto. Tallenna XML-tiedosto tietokoneelle tai verkkoon. 
  
-   Voit tuoda profiilin avaamalla hakutoiminnon ja avaamalla sitten **Tuo profiilit** -sivun. Valitse profiilin XML-tiedosto ja valitse sitten **OK**-toiminto. 

    > [!NOTE]  
    >  Et voi tuoda profiilia, joka on jo tietokannassa, vaikka XML-tiedosto olisi eriniminen tai sillä olisi eri sisältö. Poista olemassa oleva profiili ennen kuin tuot uuden profiilin. 



## <a name="see-also"></a>Katso myös  
[Toimintaohje: Käyttäjien ja käyttöoikeuksien hallinta](ui-how-users-permissions.md)  
[Käyttöliittymän mukauttaminen](ui-customizing-overview.md)   
<!--[Security Overview](../Security%20Overview.md)-->

