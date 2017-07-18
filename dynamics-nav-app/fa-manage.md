---
title: "Käyttöomaisuuden hallinta"
author: SorenGP
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 4fd7f0f5bb37a90583f292a8d8b680f826d1a8da
ms.contentlocale: fi-fi
ms.lasthandoff: 06/26/2017

---

# <a name="manage-fixed-assets"></a>Käyttöomaisuuden hallinta
Dynamics NAV -ohjelman Käyttöomaisuus-sovellusalueesta saat yleiskuvan käyttöomaisuudestasi, ja se takaa oikeat jaksottaiset poistot. Se mahdollistaa myös kunnossapitokulujen seuraamisen, vakuutussopimusten hallinnoimisen, käyttöomaisuustransaktioiden kirjaamisen sekä monenlaisten raporttien ja tilastojen luomisen.

Kunkin käyttöomaisuuserän osalta tulee määrittää kortti, joka sisältää tietoja kyseisestä käyttöomaisuuserästä. Voit määrittää rakennuksia tai tuotantolaitoksia pääkäyttöomaisuuseräksi. Voit myös ryhmitellä niitä eri tavoin, kuten esimerkiksi luokan, osaston ja sijainnin mukaan. Tämän jälkeen voit aloittaa käyttöomaisuuden hankinnan, kunnossapidon ja myynnin. Voit myös määrittää budjetoitua käyttöomaisuutta. Tämän ansiosta raportteihin voidaan sisällyttää mitä tahansa ennakoituja hankintoja ja myyntejä.

Voit seurata käyttöomaisuuden poistoja sekä muita käyttöomaisuuteen liittyviä rahoitustapahtumia määrittämällä jokaiselle yrityksen käyttöomaisuuserälle vähintään yhden poistokirjan. Poisto tehdään suorittamalla raportti, joka laskee kausittaisen poiston ja täyttää päiväkirjaan tapahtumat, jotka ovat valmiita kirjattaviksi. Dynamics NAV tukee useita poistotapoja. Lisätietoja on kohdassa [Poistotavat](fa-depreciation-methods.md). Voit määrittää useita poistokirjoja käyttöomaisuutta kohti eri tarkoituksia varten. Poistokirjat voivat käsitellä esimerkiksi veroraportointia tai sisäistä raportointia.

Kunkin käyttöomaisuuserän osalta voidaan tallentaa kunnossapitokulut ja seuraava huoltopäivämäärä. Kunnossapitokulujen seuraaminen voi olla tärkeää budjetointitarkoituksia varten ja käyttöomaisuuden vaihtamista koskevia päätöksiä varten.

Jokainen käyttöomaisuuserä voidaan liittää yhteen tai useampaan vakuutussopimukseen. Tämä helpottaa sen tarkastamista, että vakuutussopimussummat vastaavat sopimukseen linkitettyjen käyttöomaisuuserien arvoa. Tämä helpottaa myös vuosittaisten vakuutusmaksujen seuraamista.

**Huomautus**: Voit tallentaa käyttöomaisuustapahtumat **Käyttöomaisuuden KP-päiväkirja**- tai **Käyttöomaisuuspäiväkirja**-ikkunaan riippuen siitä, koskevatko tapahtumat talousraportointia vai sisäistä hallintaa. Käyttöomaisuuden ohje sisältää tietoja vain **Käyttöomaisuuden KP-päiväkirja** -ikkunan käyttämisestä. Lisätietoja on kohdassa [Toimintaohje: Käyttöomaisuuden poiston määrittäminen](fa-how-setup-depreciation.md).

Seuraavassa taulukossa on tehtäväsarja ja linkit tehtäviä kuvaaviin aiheisiin.

| Vastaanottaja | Katso |
|----|-----|
|Määritä oletusarvot, käyttöomaisuuden laskenta, kirjausryhmät, kohdistusavaimet, päiväkirjat ja kirjaustyypit.|[Käyttöomaisuuserien määrittäminen](fa-setup.md)|
|Luo käyttöomaisuus, liitä poistomenetelmät, kirjaa hankinnat ja jäännösarvot ja tulosta käyttöomaisuusluettelot.|[Toimintaohje: Käyttöomaisuuden hankinta](fa-how-acquire.md)|
|Tallenna huoltokäynnit ja kirjaa kunnossapitokustannukset sekä seuraa niitä.|[Toimintaohje: Käyttöomaisuuden kunnossapito](fa-how-maintain.md)|
|Päivitä vakuutustiedot, kirjaa hankintakustannukset vakuutussopimuksiin, muokkaa vakuutuksen kattavuutta, katsele vakuutustilastoja ja luetteloi vakuutussopimukset.|[Toimintaohje: Käyttöomaisuuden vakuuttaminen](fa-how-insure.md)|
|Luokittele käyttöomaisuus uudelleen, siirrä käyttöomaisuus eri sijainteihin, jaa käyttöomaisuuseriä tai yhdistä niitä.|[Toimintaohje: Käyttöomaisuuden siirtäminen, jakaminen tai yhdistäminen](fa-how-trans-split-combine.md)|
|Muuta käyttöomaisuuserien arvoja ja kirjaa arvonkorotus- sekä arvonalennustransaktiot.|[Toimintaohje: Käyttöomaisuuden uudelleenarvostus](fa-how-revalue.md)|
|Laske ja kirjaa poisto sekä analysoi poisto käyttöomaisuusraporteissa.|[Toimintaohje: Käyttöomaisuuden poisto tai kuolettaminen](fa-how-depreciate-amortize.md)|
|Kirjaa luovutustransaktiot, tarkastele luovutustapahtumia ja kirjaa osittaisia luovutuksia.|[Toimintaohje: Käyttöomaisuuden luovuttaminen tai poistaminen käytöstä](fa-how-dispose-retire.md)||
|Hallitse käyttöominaisuuserien budjetteja, budjetin hankintamenoja, käyttöomaisuuden luovutusten budjetointia ja poistojen budjetointia.|[Toimintaohje: Käyttöomaisuuden budjettien hallinta](fa-how-manage-budgets.md)|

## <a name="see-also"></a>Katso myös
[Käyttöomaisuuserien määrittäminen](fa-setup.md)  
[Rahoitus](finance-setup.md)  
[Tervetuloa Dynamics NAV -ohjelmaan](across-get-started.md)

