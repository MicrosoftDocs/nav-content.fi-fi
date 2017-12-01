---
title: "Dynamics NAV -ohjelman Power BI -sisältöpaketin käyttäminen"
author: edupont04
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2018
ms.translationtype: HT
ms.sourcegitcommit: 6b60b1344a1e18ad91863046110df880f75f7c04
ms.openlocfilehash: ad9519b8ce9c244480308ccc99c05e78e4926b06
ms.contentlocale: fi-fi
ms.lasthandoff: 10/16/2017

---

# <a name="using-the-dynamics-nav-content-pack-for-power-bi"></a>Dynamics NAV -ohjelman Power BI -sisältöpaketin käyttäminen
Lisätietojen hakeminen Dynamics NAVin tietoihin on helppoa Power BI- ja Dynamics NAV -sisältöpaketin avulla. Power BI hakee tiedot ja muodostaa näiden tietojen perusteella valmiin koontinäytön ja raportit.  

Sisältöpaketti on määritetty etukäteen niin, että sitä voidaan käyttää Dynamics NAV -ohjelman esikatseluun rekisteröitymisessä saatavan esittely-yrityksen myynti- ja taloustietojen kanssa.  

- Valitse koontinäytöstä mikä tahansa visuaalinen kohde, kun haluat käsitellä jotakin seitsemästä perustana olevasta raportista.  
- Suodata raportti tai lisää seurattavia kenttiä.  
- Kiinnitä tämä mukautettu näkymä koontinäyttöön, kun haluat jatkaa seuraamista.  
Koontinäyttö ja perustana olevat raportit päivitetään päivittäin. Voit hallita päivitysaikataulua ja muokata tietojoukon esiintymistiheyttä.  

## <a name="accessing-dynamics-nav-in-power-bi"></a>Dynamics NAVin käyttäminen Power BI:ssä
Voit tarkastella Dynamics NAVin tietoja Power BI:ssä, kun seuraavat vaatimukset toteutuvat:  

- Dynamics NAVin käyttöoikeus. Lisätietoja on kohdassa [Dynamics NAV](http://go.microsoft.com/fwlink/?LinkID=759714).  
- Power BI:n käyttöoikeus. Lisätietoja on kohdassa [Power BI](https://powerbi.microsoft.com).

Power BI -sivustossa on lisätietoja [Dynamics NAV -sisältöpaketin lisäämisestä Power BI -ohjelmaan](http://go.microsoft.com/fwlink/?LinkID=760850).  

Voit käyttää Dynamics NAV -sisältöpakettia Power BI:ssä, kun määrität yhteysikkunassa seuraavat tiedot:

| Kenttä       | Kuvaus              |
|-------------|--------------------------|
|**OData-syötteen URL-osoite**|ODatan URL-osoite, jonka avulla Power BI voi käyttää yrityksen tietoja. Osoite voi olla esimerkiksi https://mybusiness.com:7048/MS/OData/Company('CRONUS%20US').|
|**Todennusmenetelmä**|Valitse **Perus**.|
|**Käyttäjänimi**|Dynamics NAV -ohjelmaan rekisteröitymisen yhteydessä käytettävä sähköpostitili, kuten *me@mybusiness.com*.|
|**Salasana**|Tämä on Dynamics NAVin käyttäjätilin verkkopalvelun käyttöoikeusavain.|

Dynamics NAV -ohjelmasta on siis haettava kaksi tietoa: ODatan URL-osoite ja käyttäjätilin verkkopalvelun käyttöoikeusavain.  
**URL-osoitteen hakeminen**  
Kun lisäät Dynamics NAVin Power BI:hin, URL-osoite on määritettävä, jotta Power BI voi käyttää yrityksen tietoja. URL-osoitteeseen viitataan yhteysikkunassa **OData-syötteen URL-osoite** -nimellä. Sen on oltava seuraavassa muodossa:

         https://mybusiness.projectmadeira.com:7048/MS/OData/Company('CRONUS%20US')  
Tässä esimerkissä *mybusiness* on Dynamics NAV-palvelun nimi ja *CRONUS US* esittely-yrityksen nimi. *%20* tarkoittaa nimessä olevaa väliä.   
Voit hakea URL-osoitteen hakemalla Dynamics NAVin **WWW-palvelut**-ikkunan ja avaamalla sen. Ikkuna sisältää tällä hetkellä käytettävissä olevat WWW-palvelut. Voit kopioida **ODatan URL-osoite** -kentän linkin johonkin ODatan oletus-WWW-palveluun.  
**WWW-palvelun käyttöoikeusavaimen hakeminen**  
Voit käyttää Dynamics NAV -ohjelman tietoja, kun määrität käyttäjänimen (eli sähköpostitilin) ja salasanan Power BI:n **Yhteyden muodostaminen Dynamics NAV -ohjelmaan** -ikkunassa. Salasana on Dynamics NAVin käyttäjätilillä määritetty verkkopalvelun käyttöoikeusavain.  
Voit hakea WWW-palvelun käyttöoikeusavaimen Dynamics NAV -ohjelmassa tekemällä haun **Käyttäjät**-ikkunassa ja avaamalla sen jälkeen käyttäjätilin kortin. Kopioi **WWW-palvelun käyttöoikeus** -pikavälilehdessä **WWW-palvelun käyttöoikeusavain** -kenttä. Jos kenttä on tyhjä, valitse valintanauhan **Muuta WWW-palvelun käyttöoikeusavainta** -kohta, valitse sitten **Avain ei vanhene koskaan** -kenttä ja valitse lopuksi OK-painike. Tämän jälkeen voit kopioida avaimen.  

## <a name="getting-data-from-dynamics-nav"></a>Tietojen hakeminen Dynamics NAVista
Dynamics NAVin koontinäyttö sisältää tavallisimmat liiketoiminnan seuraamisessa käytettävät raportit. Tiedot puretaan Dynamics NAVin yrityksestä verkkopalveluiden avulla oikeiden tietojen lukemista varten. Dynamics NAVin **WWW-palvelut**-ikkunassa näkyvät sinulle määritetyt verkkopalvelut. Niihin ovat esimerkiksi myös seuraavat Power BI -sisältöpaketin käyttämät verkkopalvelut:  

- ItemSalesAndProfit  
- ItemSalesByCustomer  
- powerbifinance-setup  
- SalesDashboard  
- SalesOpportunities  
- SalesOrdersBySalesPerson  
- TopCustomerOverview  

**Huomautus**: Jos muutat näiden WWW-palveluiden nimet, tiedot eivät näy Power BI:ssä.  
Jos haluat lisätä muiden tietojen käytön Power BI:ssä, etsi taulukot Dynamics NAVista, näytä ne verkkopalveluina ja lisää ne sisältöpakettiin. Tämä on lisäskenaario. Suosittelemme, että aloitat käsittelemisen Power BI:n valmiilla tiedoilla.  

## <a name="troubleshooting"></a>Vianetsintä
Power BI:n koontinäyttö käyttää julkaistuja yllä mainittuja WWW-palveluita. Koontinäytössä ovat esittely-yrityksen tiedot tai oman yrityksesi tiedot, jos toit tiedot nykyisestä rahoituksen käyttöönottoratkaisustasi. Tämä osa sisältää ratkaisun tyypillisempiin ongelmiin.  

**"Parametrin tarkistus epäonnistui. Varmista, että kaikki parametrit ovat sallittuja."**  
Jos näyttöön tulee tämä virhe Dynamics NAVin URL-osoitteen antamisen jälkeen, varmista, että seuraavat vaatimukset täyttyvät:  

- URL-osoitteen muodon on oltava täsmälleen tämä:

    https://mybusiness.projectmadeira.com:7048/MS/OData/Company('CRONUS%20US')  
- Poista teksti, joka on sulkeissa olevan yrityksen nimen jälkeen  
- Varmista, että URL-osoitteen lopussa ei ole vinoviivaa.  
- Varmista, että URL-osoitteen alussa on suojatun yhteyden osoittava merkkijono *https*.  


**"Sisäänkirjautuminen epäonnistui"**  
Jos näyttöön tulee sisäänkirjautumisen epäonnistumista ilmoittava virhe, kun kirjaudut koontinäyttöön Dynamics NAVin tunnistetiedoilla, syy voi olla jonkin seuraavista:

* Käyttämälläsi tilillä ei ole Dynamics NAVin tietojen lukuoikeuksia.

    Tarkista Dynamics NAVin käyttäjätili ja varmista, että olet käyttänyt oikeaa verkkopalvelun käyttöoikeusavainta salasanana. Yritä tämän jälkeen uudelleen.  
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
[Tervetuloa Dynamics NAViin!](across-get-started.md)  

