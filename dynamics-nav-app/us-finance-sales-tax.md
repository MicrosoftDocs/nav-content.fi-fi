---
title: "Yhdysvaltojen ja Kanadan arvonlisävero ja veroryhmät"
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
ms.openlocfilehash: f70a191fc8392bf1685c08c7e905ac96ba7ed069
ms.contentlocale: fi-fi
ms.lasthandoff: 06/26/2017

---

# <a name="sales-tax-and-tax-groups-in-the-us-and-canada"></a>Yhdysvaltojen ja Kanadan arvonlisävero ja veroryhmät
Kun aloitat Dynamics NAV -ohjelman käyttämisen, voit määrittää arvonlisäverojen tiedot nopeasti ja helposti yritykselle ja vaihtoehtoisesti myös asiakkaille ja toimittajille avustetun asennusoppaan avulla. Muutamassa minuutissa voit aloittaa myynti- ja ostoasiakirjojen luomisen niin, että arvonlisävero lasketaan oikein.
Jos siirryt tyhjään omaan yritykseen, aloita käyttämällä kutakin avustettua asennusopasta, myös arvonlisäveron asennusopasta. Tässä artikkelissa kerrotaan, mitä arvonlisäveron määrittämisessä tulee ottaa huomioon, jos haluat määrittää arvonlisäveron itse.  

## <a name="tax-groups-tax-areas-and-tax-jurisdictions"></a>Arvonlisäveroryhmät, veroalueet ja verotoimialueet
Dynamics NAV -ohjelman veroluokkaan kuuluvat sellaiset varastonimikkeet tai resurssit, joilla on keskenään identtiset verotusehdot. Voit määrittää esimerkiksi veroryhmän verotettaville nimikkeille ja toisen veroryhmän muille kuin verotettaville nimikkeille. Määritä varastonimikkeille ja pääkirjanpidon tileille veroryhmäkoodit. Samoin on määritettävä asiakkaiden, sijaintien ja oman yrityksen asetusten veroaluekoodit. Avustettu asennusopas auttaa tässä.  

Kukin veroalue on arvonlisäverotoimialueen ryhmittely, joka perustuu tiettyyn maantieteelliseen sijaintiin. Esimerkiksi Floridassa sijaitsevan Miamin veroalue sisältää kolme arvonlisäverotoimialuetta: kaupunki (Miami), lääni (Dade) ja osavaltio (Florida). Dynamics NAV -ohjelman oletusmääritys sisältää rajoitetun määrän veroalueita. Voit kuitenkin muuttaa niitä ja lisätä uusia veroalueita.  

Jos olet määrittänyt uudet veroalueet ja verotoimialueet, varmista, että täytät kentät oikein. Yhdysvalloissa osavaltiot, läänit, kaupungit ja paikkakunnat voivat kerätä arvonlisäveroa. Kanadassa liittovaltio ja provinssit voivat kerätä arvonlisäveroa. Yritykset keräävät loppukäyttäjille myytävistä tuotteista arvonlisäveron ja maksavat sen julkishallinnolle. Arvonlisäveroa voidaan kerätä myös olemassa olevasta arvonlisäverosta. Vero voidaan laskea esimerkiksi myyntilaskun summasta, joka jo sisältää muiden toimialueiden veron.  

Kanadassa verosummat on eriteltävä kunkin verotoimialueen asiakirjoissa. Asiakirjassa voi olla enintään neljä toimialuetta. Toimialueet, joilla on sama tulostusjärjestys, yhdistetään tulostamisen yhteydessä.

## <a name="tax-details"></a>Veroerittelyt
**Verotiedot**-ikkunassa näkyvät arvonlisäverotoimialueiden ja arvonlisäveroryhmien eri yhdistelmät, joiden mukaan muodostetaan arvonlisäveroprosentit. Jokaiselle verotoimialueelle kannattaa määrittää yksi veroryhmä normaalille arvonlisäverolle, toinen nimikkeille tai palveluille, joita ei veroteta, ja lisäveroryhmä jokaiselle sellaiselle nimike- tai palvelutyypille, joissa on eri arvonlisäveroprosentti kuin toimialueella.  

Kun Yhdysvalloissa myynti asiakkaalle tapahtuu paikassa, jolla ei ole *situs*-arvoa (eli juridista sijaintia kyseisessä osavaltiossa), arvonlisäveroa ei kerätä. Varmista, että sijainneilla, joilla ei ole situs-arvoa, on sekä **Enimmäisrajan alittava vero**- että **Enimmäisrajan ylittävä vero** -kentän arvoksi määritetty 0,00.  

## <a name="see-also"></a>Katso myös
[Rahoitus](finance-setup.md)  
[Rahoituksen määrittäminen](finance-setup-setup-finance-setup.md)  
[Kanadan arvonlisävero](ca-finance-setup-tax.md)  
[Helposti suoritettava arvonlisäveron määrittäminen](https://madeira.microsoft.com/en-us/blog/sales-tax-setup-made-easy)  

