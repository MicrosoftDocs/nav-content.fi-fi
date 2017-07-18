---
title: "Dynamics NAV -ohjelman Power BI -sisältöpaketin käyttäminen"
author: edupont04
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 6351e4819a2f3665cc561b5b1f868eea5d435f75
ms.contentlocale: fi-fi
ms.lasthandoff: 06/26/2017

---

# <a name="using-the-dynamics-nav-content-pack-for-power-bi"></a>Dynamics NAV -ohjelman Power BI -sisältöpaketin käyttäminen
Lisätietojen hakeminen Dynamics NAV -ohjelman tietoihin on helppoa Power BI- ja Dynamics NAV -sisältöpaketin avulla. Power BI hakee tiedot ja muodostaa näiden tietojen perusteella valmiin koontinäytön ja raportit.  

Sisältöpaketti on määritetty etukäteen niin, että sitä voidaan käyttää Dynamics NAV -ohjelman esikatseluun rekisteröitymisessä saatavan esittely-yrityksen myynti- ja taloustietojen kanssa.  

- Valitse koontinäytöstä mikä tahansa visuaalinen kohde, kun haluat käsitellä jotakin seitsemästä perustana olevasta raportista.  
- Suodata raportti tai lisää seurattavia kenttiä.  
- Kiinnitä tämä mukautettu näkymä koontinäyttöön, kun haluat jatkaa seuraamista.  
Koontinäyttö ja perustana olevat raportit päivitetään päivittäin. Voit hallita päivitysaikataulua ja muokata tietojoukon esiintymistiheyttä.  

## <a name="accessing-dynamics-nav-in-power-bi"></a>Dynamics NAV -ohjelman käyttäminen Power BI:ssä
Voit tarkastella Dynamics NAV -ohjelman tietoja Power BI:ssä, kun seuraavat vaatimukset toteutuvat:  

- Dynamics NAV -ohjelman käyttöoikeus. Lisätietoja on kohdassa [Dynamics NAV](http://go.microsoft.com/fwlink/?LinkID=759714).  
- Power BI:n käyttöoikeus. Lisätietoja on kohdassa [Power BI](https://powerbi.microsoft.com).

Power BI -sivustossa on lisätietoja [Dynamics NAV -sisältöpaketin lisäämisestä Power BI -ohjelmaan](http://go.microsoft.com/fwlink/?LinkID=760850).  

Voit käyttää Dynamics NAV -sisältöpakettia Power BI:ssä, kun määrität yhteysikkunassa seuraavat tiedot:

| Kenttä       | Kuvaus              |
|-------------|--------------------------|
|**OData-syötteen URL-osoite**|ODatan URL-osoite, jonka avulla Power BI voi käyttää yrityksen tietoja. Osoite voi olla esimerkiksi https://mybusiness.com:7048/MS/OData/Company('CRONUS%20US').|
|**Todennusmenetelmä**|Valitse **Perus**.|
|**Käyttäjänimi**|Dynamics NAV -ohjelmaan rekisteröitymisen yhteydessä käytettävä sähköpostitili, kuten *me@mybusiness.com*.|
|**Salasana**|Tämä on Dynamics NAV -ohjelman käyttäjätilin WWW-palvelun käyttöoikeusavain.|

Sinun on siis haettava kaksi eri tietoa Dynamics NAV -ohjelmasta: ODatan URL-osoite ja käyttäjätilin WWW-palvelun käyttöoikeusavain.  
**URL-osoitteen hakeminen**  
Kun lisäät Dynamics NAV -ohjelman Power BI -ohjelmaan, URL-osoite on määritettävä, jotta Power BI voi käyttää yrityksen tietoja. URL-osoitteeseen viitataan yhteysikkunassa **OData-syötteen URL-osoite** -nimellä. Sen on oltava seuraavassa muodossa:

         https://mybusiness.projectmadeira.com:7048/MS/OData/Company('CRONUS%20US')  
Tässä esimerkissä *mybusiness* on Dynamics NAV -palvelun nimi ja *CRONUS US* esittely-yrityksen nimi. *%20* tarkoittaa nimessä olevaa väliä.   
Voit hakea URL-osoitteen hakemalla Dynamics NAV -ohjelman **WWW-palvelut**-ikkunan ja avaamalla sen. Ikkuna sisältää tällä hetkellä käytettävissä olevat WWW-palvelut. Voit kopioida **ODatan URL-osoite** -kentän linkin johonkin ODatan oletus-WWW-palveluun.  
**WWW-palvelun käyttöoikeusavaimen hakeminen**  
Voit käyttää Dynamics NAV -ohjelman tietoja, kun määrität käyttäjänimen (eli sähköpostitilin) ja salasanan Power BI:n **Yhteyden muodostaminen Dynamics NAV -ohjelmaan** -ikkunassa. Salasana on Dynamics NAV -ohjelman käyttäjätilillä määritetty WWW-palvelun käyttöoikeusavain.  
Voit hakea WWW-palvelun käyttöoikeusavaimen Dynamics NAV -ohjelmassa tekemällä haun **Käyttäjät**-ikkunassa ja avaamalla sen jälkeen käyttäjätilin kortin. Kopioi **WWW-palvelun käyttöoikeus** -pikavälilehdessä **WWW-palvelun käyttöoikeusavain** -kenttä. Jos kenttä on tyhjä, valitse valintanauhan **Muuta WWW-palvelun käyttöoikeusavainta** -kohta, valitse sitten **Avain ei vanhene koskaan** -kenttä ja valitse lopuksi OK-painike. Tämän jälkeen voit kopioida avaimen.  

## <a name="getting-data-from-dynamics-nav"></a>Tietojen hakeminen Dynamics NAV -ohjelmasta
Dynamics NAV -ohjelman koontinäyttö sisältää tavallisimmat liiketoiminnan seuraamisessa käytettävät raportit. Tiedot puretaan Dynamics NAV -ohjelman yrityksestä WWW-palveluiden avulla oikeiden tietojen lukemista varten. Dynamics NAV -ohjelman **WWW-palvelut**-ikkunassa näkyvät sinulle määritetyt WWW-palvelut. Niihin kuuluvat myös seuraavat Power BI -sisältöpaketin käyttämät WWW-palvelut:  

- ItemSalesAndProfit  
- ItemSalesByCustomer  
- powerbifinance-setup  
- SalesDashboard  
- SalesOpportunities  
- SalesOrdersBySalesPerson  
- TopCustomerOverview  

**Huomautus**: Jos muutat näiden WWW-palveluiden nimet, tiedot eivät näy Power BI:ssä.  
Jos haluat muiden Power BI:n tietojen käytön, etsi taulukot Dynamics NAV -ohjelmasta, näytä ne WWW-palveluina ja lisää ne sisältöpakettiin. Tämä on lisäskenaario. Suosittelemme, että aloitat käsittelemisen Power BI:n valmiilla tiedoilla.  

## <a name="troubleshooting"></a>Vianetsintä
Power BI:n koontinäyttö käyttää julkaistuja yllä mainittuja WWW-palveluita. Koontinäytössä ovat esittely-yrityksen tiedot tai oman yrityksesi tiedot, jos toit tiedot nykyisestä rahoituksen käyttöönottoratkaisustasi. Tämä osa sisältää ratkaisun tyypillisempiin ongelmiin.  

**"Parametrin tarkistus epäonnistui. Varmista, että kaikki parametrit ovat sallittuja."**  
Jos näyttöön tulee tämä virhe Dynamics NAV -ohjelman URL-osoitteen syöttämisen jälkeen, varmista, että seuraavat vaatimukset täyttyvät:  

- URL-osoitteen muodon on oltava täsmälleen tämä:

    https://mybusiness.projectmadeira.com:7048/MS/OData/Company('CRONUS%20US')  
- Poista teksti, joka on sulkeissa olevan yrityksen nimen jälkeen  
- Varmista, että URL-osoitteen lopussa ei ole vinoviivaa.  
- Varmista, että URL-osoitteen alussa on suojatun yhteyden osoittava merkkijono *https*.  


**"Sisäänkirjautuminen epäonnistui"**  
Jos näyttöön tulee "sisäänkirjautuminen epäonnistui" -virhe, kun kirjaudut koontinäyttöön Dynamics NAV -ohjelman tunnistetietojen avulla, syy voi olla jonkin seuraavista:

* Käyttämälläsi tilillä ei ole Dynamics NAV -ohjelman tietojen lukuoikeuksia.

    Tarkista Dynamics NAV -ohjelman käyttäjätili ja varmista, että olet käyttänyt oikeaa WWW-palvelun käyttöoikeusavainta salasanana. Yritä tämän jälkeen uudelleen.  
* Dynamics NAV -ilmentymällä, johon yrität muodostaa yhteyden, ei ole sallittua SSL-varmennetta. Tällöin näyttöön tulee eritellympi virhesanoma ("luotetun SSL-suhteen muodostaminen ei onnistu").

    **Huomautus**: Itse allekirjoitettuja varmenteita ei tueta.  


**"Jokin meni vikaan"**  
Jos näet "Jokin meni vikaan" -virhevalintaikkunan sen jälkeen, kun todentamisvalintaikkuna on ohitettu, syy on todennäköisesti ongelma muodostettaessa yhteyttä sisältöpaketin tietoihin.

* Varmista, että URL-osoitteella on seuraava aiemmin määritetty muoto:

    https://mybusiness.projectmadeira.com:7048/MS/OData/Company('CRONUS%20US')  
* Yleinen virhe on määrittää tietyn WWW-palvelun koko URL-osoite.

    https://mybusiness.projectmadeira.com:7048/MS/OData/Company('CRONUS%20US')/powerbifinance-setup  
* Myös yrityksen nimi on saattanut unohtua.

    https://mybusiness.projectmadeira.com:7048/MS/OData/  


## <a name="see-also"></a>Katso myös
[Tervetuloa Dynamics NAV -ohjelmaan](across-get-started.md)  

