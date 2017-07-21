---
title: "Itsepalvelun rekisteröitymisen vianmääritys"
author: SusanneWindfeldPedersen
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 931c427518694cbd0003ea82735292a019b388d5
ms.contentlocale: fi-fi
ms.lasthandoff: 06/26/2017

---

# <a name="troubleshooting-self-service-sign-up"></a>Itsepalvelun rekisteröitymisen vianmääritys
Dynamics NAV -ohjelmaan rekisteröityminen on helppoa ja nopeaa. Voit luoda ilmaisen tilin myös silloin, jos organisaatio on olemassa. Tässä artikkelissa kerrotaan ongelmista, joita rekisteröitymisen aikana voi ilmetä.

## <a name="what-email-address-can-i-use-with-dynamics-nav"></a>Mitä sähköpostiosoitetta voin käyttää Dynamics NAV -ohjelman kanssa?
Dynamics NAV vaatii työ- tai opiskelupaikan antaman sähköpostiosoitteen käyttämistä rekisteröitymisen yhteydessä. Dynamics NAV ei tue kuluttajille tarkoitettujen sähköpostipalveluiden ja tietoliikennepalveluiden tarjoajien sähköpostiosoitteita. Näitä ovat esimerkiksi outlook.com, hotmail.com ja gmail.com.

Jos yrität rekisteröityä käyttämällä henkilökohtaista sähköpostiosoitetta, saat viestin, jossa pyydetään käyttämään työ- tai opiskelupaikan antamaa sähköpostiosoitetta.

## <a name="troubleshooting"></a>Vianetsintä
Usein Dynamics NAV -ohjelmaan voidaan rekisteröityä rekisteröitymisprosessin avulla. Itsepalvelun rekisteröityminen voi kuitenkin keskeytyä useasta eri syystä. Seuraavassa taulukossa esitellään yleisimpiä syitä, joiden vuoksi rekisteröityminen ei onnistu, sekä ratkaisuja näihin ongelmiin.

|Oire/virhesanoma                                                                             |Syy ja ratkaisu|
|--------------------------------------------------------------------------------------------------|--------------------|
|Jos Office 365 -sähköpostiosoitteita ei ole rekisteröity Yhdysvalloissa, sinulle lähetetään rekisteröitymisen yhteydessä seuraava viesti: <br>**Toiminto ei onnistunut. Microsoft ei vielä tue maatasi tai aluettasi.**<br> |Dynamics NAV tukee tällä hetkellä vain Office 365:n Yhdysvalloissa rekisteröityjä sähköpostitilejä.|
|Henkilökohtaisia sähköpostiosoitteita, kuten nancy@gmail.com, ei tueta. Näyttöön tulee rekisteröitymisen yhteydessä seuraavan tyyppinen viesti: <br>**Annoit henkilökohtaisen sähköpostiosoitteen: anna työsähköpostiosoite, jotta yrityksen tiedot voidaan tallentaa turvallisesti.**<br> tai <br> **Tämä näyttää henkilökohtaiselta sähköpostiosoitteelta. Anna työsähköpostiosoite, jotta voimme yhdistää sinut muihin yrityksesi henkilöihin. Eikä hätää; Microsoft ei jaa osoitettasi kenenkään kanssa.** | Dynamics NAV ei tue kuluttajille tarkoitettujen sähköpostipalveluiden ja tietoliikennepalveluiden tarjoajien sähköpostiosoitteita. Tee rekisteröityminen valmiiksi yrittämällä uudelleen työpaikan tai koulun myöntämällä sähköpostiosoitteella. Jos rekisteröityminen ei onnistu vieläkään, ja haluat kokeilla monimutkaisempaa asetusprosessia, voit rekisteröityä uuteen Office 365 -kokeiluversioon ja rekisteröityä kyseisellä sähköpostiosoitteella.
|sähköpostiosoitteet .gov tai .mil. Rekisteröitymisen yhteydessä saat seuraavan tyyppisen viestin: <br>**Dynamics NAV ei ole käytettävissä: Dynamics NAV ei ole tällä hetkellä niiden käyttäjien käytettävissä, joiden sähköpostiosoitteen pääte on .gov tai .mil. Käytä toista työsähköpostiosoitetta tai yritä myöhemmin uudelleen.** <br>tai <br>**Rekisteröityminen ei onnistu. Näyttää siltä, että Dynamics NAV ei ole tällä hetkellä työpaikkasi tai koulusi käytettävissä.**|Dynamics NAV ei tue tällä hetkellä sähköpostiosoitteita, joiden pääte on .gov tai .mil.|
|Itsepalvelun rekisteröityminen ei ole käytössä. Näyttöön tulee rekisteröitymisen yhteydessä seuraavan tyyppinen viesti: <br>**Rekisteröityminen ei onnistu. IT-osasto on poistanut Dynamics NAViin kirjautumisen käytöstä. Ota IT-osastoon yhteys, kun haluat viimeistellä rekisteröitymisen.** <br>tai <br> **Tämä näyttää henkilökohtaiselta sähköpostiosoitteelta. Anna työsähköpostiosoite, jotta voimme yhdistää sinut muihin yrityksesi henkilöihin. Eikä hätää; Microsoft ei jaa osoitettasi kenenkään kanssa.**|Organisaation IT-järjestelmänvalvoja on ottanut Dynamics NAV -ohjelman itsepalvelun rekisteröitymisen pois käytöstä. Tee rekisteröityminen valmiiksi ottamalla yhteys IT-osastoon ja pyytämällä heitä seuraamaan alla olevan sivun ohjeita. Niiden avulla olemassa olevat käyttäjät voivat rekisteröityä Dynamics NAV -ohjelmaan ja uudet käyttäjät voivat liittyä olemassa olevaan vuokraajaan. Tämä ongelma saattaa esiintyä myös silloin, kun rekisteröidyt Office 365:een kumppanin kautta.|
|Sähköpostiosoite ei ole Office 365:n tunnus. Näyttöön tulee rekisteröitymisen yhteydessä seuraavan tyyppinen viesti: <br>**Sähköpostiosoitettasi ei löydy contoso.com-tiedoista. Käytätkö eri tunnusta töissä tai koulussa? Yritä rekisteröityä tällä toisella tunnuksella. Jos rekisteröityminen ei onnistu, ota yhteys yrityksen IT-osastoon.**|Organisaatiosi käyttää sähköpostiosoitteiden sijaan tunnuksia Office 365:een ja muihin Microsoft-palveluihin rekisteröitymisessä. Sähköpostiosoitteesi voi olla esimerkiksi Nancy.Smith@contoso.com, kun taas tunnuksesi voi olla nancys@contoso.com. Voit tehdä rekisteröitymisen valmiiksi käyttämällä tunnusta, jonka organisaatio on määrittänyt Office 365:een tai muihin Microsoft-palveluihin rekisteröitymistä varten. Jos et tiedä tunnusta, ota yhteys IT-järjestelmänvalvojaan. Jos rekisteröityminen ei onnistu vieläkään, ja voit kokeilla monimutkaisempaa asetusprosessia, voit rekisteröityä uuteen Office 365 -kokeiluversioon ja rekisteröityä kyseisellä sähköpostiosoitteella.|


## <a name="see-also"></a>Katso myös
[Tervetuloa Dynamics NAV -ohjelmaan](across-get-started.md)  
[Dynamics NAV -ohjelman käyttäminen](ui-work-product.md)




