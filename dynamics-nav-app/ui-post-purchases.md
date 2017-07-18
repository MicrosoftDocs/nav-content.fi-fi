---
title: Ostojen kirjaaminen
author: SusanneWindfeldPedersen
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: c03d031e951bc185b18bedaf428d414c1fe2e7d1
ms.contentlocale: fi-fi
ms.lasthandoff: 06/26/2017

---

# <a name="posting-purchases"></a>Ostojen kirjaaminen
Kun valitset ostoasiakirjan **Kirjausryhmä**-painikkeen, voit valita seuraavista kirjaustoiminnoista:

- **Kirjaa**
- **Esikatsele kirjausta**
- **Kirjaa ja tulosta**
- **Testiraportti**
- **Kirjaa erä**

Kun olet täyttänyt kaikki rivit ja syöttänyt kaikki tiedot ostotilaukseen, voit kirjata sen eli luoda vastaanoton ja laskun.

Kun ostotilaus on kirjattu, toimittajan tili, pääkirjanpito ja nimiketapahtumat päivitetään.

Jokaiselle ostotilaukselle luodaan ostotapahtuma **KP-tapahtuma**-taulukkoon. Myös toimittajan tilille **Toimittajatapahtuma**-taulukkoon luodaan tapahtuma ja lisäksi luodaan KP-tapahtuma asianmukaiselle ostovelkatilille. Lisäksi tilauksen kirjauksen tuloksena saattaa olla ALV-tapahtuman ja KP-tapahtuman luonti alennussummalle. Se, kirjataanko alennukselle tapahtuma, määräytyy **Ostojen ja ostovelkojen asetukset** -taulukon **Alennuksen kirjaus** -kentän sisällön perusteella.

Kullekin ostotilausriville luodaan nimiketapahtuma **Nimiketapahtuma**-taulukkoon (jos ostorivit sisältävät nimikenumeroita) tai KP-tapahtuma **KP-tapahtuma**-taulukkoon (jos ostorivit sisältävät KP-tilin). Lisäksi ostotilaukset tallennetaan aina **Tavaran vastaanoton otsikko**- ja **Ostolaskun otsikko** -taulukoihin.

Ennen kirjausta voit tulostaa testiraportin, jossa on kaikki tiedot ostotilauksesta ja joka osoittaa mahdolliset virheet. Kun haluat tulostaa raportin, valitse **Kirjaus** ja valitse sitten **Testiraportti**.

**Tärkeää**: Kun kirjaat tilauksen, voit luoda sekä vastaanoton että laskun. Nämä voidaan luoda joko yhtäaikaa tai erikseen. Voit luoda osittaisen vastaanoton ja osittaisen laskutuksen täyttämällä **Vastaanotettava määrä** ja **Laskutettava määrä** -kentät yksittäisillä ostotilausriveillä ennen kirjausta. Huomaa, et voi luoda laskua jos sellaista ei ole vastaanotettu. Siispä ennen laskuttamista on täytynyt tallentaa vastaanotto, tai sinun täytyy valita samanaikainen vastaanotto ja laskutus.

Voit kirjata tai kirjata ja tulostaa. Jos valitset kirjaamisen ja tulostamisen, raportti tulostetaan tilauksen kirjaamisen yhteydessä. **Kirjaa erä** -toiminnolla voit kirjata useita tilauksia samanaikaisesti.

Kun kirjaus on päättynyt, kirjatut ostorivit poistuvat tilauksesta. Viesti kertoo, milloin kirjaus on valmis. Tämän jälkeen voit nähdä kirjatut tapahtumat useissa kirjattuja tapahtumia sisältävissä ikkunoissa, kuten **Toimittajatapahtumat**-, **KP -tapahtumat**-, **Nimiketapahtumat**-, **Ostovastaanotot**- ja **Kirjatut ostolaskut** -ikkunassa.

## <a name="see-also"></a>Katso myös
[Asiakirjojen ja päiväkirjojen kirjaaminen](ui-post-documents-journals.md)

