---
title: "Tietoja KET-menetelmistä"
author: SorenGP
ms.custom: na
ms.date: 11/01/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: f21357897dd730d96db7abab469d5958c6fe117c
ms.contentlocale: fi-fi
ms.lasthandoff: 06/26/2017

---

# <a name="understanding-wip-methods"></a>Tietoja KET-menetelmistä

Dynamics NAV tukee seuraavia keskeneräisen työn arvon laskennan ja kirjaamisen menetelmiä.

|KET-menetelmä |Laskentakaava |Laskennan kuvaus|
|-----------|--------------------|-----------------------|
|Kustannusarvo|Tuloutettu tuotto = laskutettava laskutettu hinta<br /><br /> Arvioidut kokonaiskustannukset = laskutettava kokonaishinta x budjetin kustannusten suhde<br /><br /> KET-kustannukset = \(valmistumisen %-osuus - laskutettu %\) x arvioidut kokonaiskustannukset<br /><br /> Valmistumisen %-osuus = käytön kokonaiskustannukset / budjetoidut kokonaiskustannukset<br /> Laskutettu % = laskutettava laskutettu hinta<br /><br /> Laskutettu tuloutettujen kokonaiskustannusten hinta = käytön kokonaiskustannukset - KET|Kustannusarvon laskelmat aloitetaan laskemalla tuotettujen arvo. Se tehdään ottamalla osa valmistumisen prosenttiosuuteen perustuvista arvioiduista kustannuksista. Laskutetut kustannukset vähennetään ottamalla osa laskutettuun prosenttiin perustuvista arvioiduista kokonaiskustannuksista.<br /><br /> Tämä laskenta vaatii, että koko projektin laskutettava kokonaishinta, budjetoitu kokonaishinta ja budjetoidut kokonaiskustannukset on syötettävä oikein.|
|Myynnin kulut|Tuloutettu tuotto = laskutettava laskutettu hinta<br /><br /> Tuloutetut kustannukset = budjetoidut kokonaiskustannukset x laskutettu prosenttiosuus<br /><br /> Laskutettu % = laskutettava laskutettu hinta / laskutettava kokonaishinta<br /><br /> \(Laskutettu % on projektitehtävärivin sarake\)<br /><br /> KET-kustannukset = käytön kokonaiskustannukset - tuloutetut kustannukset|Myynnin kulujen laskeminen alkaa tuloutettujen kustannusten laskemisella. Kustannukset tuloutetaan suhteessa budjetin kokonaiskustannuksiin.<br /><br /> Tämä laskenta vaatii, että koko projektin laskutettava kokonaishinta ja budjetin kokonaiskustannukset on syötettävä oikein.|
|Myyntiarvo|Tuloutetut kustannukset = käytön kokonaiskustannukset<br /><br /> Tuloutettu tuotto = käytön kokonaishinta x odotettu laskutuksen suhde<br /><br /> Kustannusten korvaus-% = laskutettava kokonaishinta / budjetin kokonaishinta<br /><br /> KET-myynti = tuloutettu myynti - laskutettava laskutettu hinta|Myyntiarvon laskelmat tulouttavat tuoton suhteessa käytön kokonaiskustannuksiin ja odotettuihin kustannuksiin korvaussuhteen perusteella.<br /><br /> Tämä laskenta vaatii, että koko projektin laskutettava kokonaishinta ja budjetin kokonaishinta on syötettävä oikein.|
|Valmistumisen prosenttiosuus|Tuloutetut kustannukset = käytön kokonaiskustannukset<br /><br /> Tuloutettu tuotto = laskutettava kokonaishinta x valmistumisen %-osuus<br /><br /> Valmistumisen %-osuus = käytön kokonaiskustannukset / budjetoidut kokonaiskustannukset<br /><br /> \(Projektitehtäväriveillä tätä kutsutaan kustannuksen valmistumisprosentiksi\)<br /> KET-myynti = tuloutettu myynti - laskutettava laskutettu hinta|Valmistumisen %-osuuden laskennat tulouttavat tuoton suhteessa valmistumisen prosenttiosuuteen (eli käytön kokonaiskustannuksiin ja budjetin kustannuksiin).<br /><br /> Tämä laskenta vaatii, että koko projektin laskutettava kokonaishinta ja budjetin kokonaiskustannukset on syötettävä oikein.|
|Valmis sopimus|KET-summa = KET-kustannusten summa = käyttö \(kokonaiskustannukset\)<br /><br /> KET-myynnin summa = laskutettava \(laskutettu hinta\)|Valmis sopimus ei tulouta tuottoa ja kustannuksia ennen projektin valmistumista. Tästä voi olla hyötyä, kun projektin kustannusten ja tuoton arviointi on hyvin epävarmaa.<br /><br /> Kaikki käyttö kirjataan KET-kustannusten tilille \(saatavat\) ja kaikki laskutettu myynti kirjataan laskutetun KET-myynnin tilille\(velat\), kunnes projekti on valmis.|

## <a name="see-also"></a>Katso myös
[Projektien hallinta](projects-manage-projects.md)  
[Rahoitus](finance-setup.md)  
[Ostojen hallinta](purchasing-manage-purchasing.md)         
[Myynnin hallinta](sales-manage-sales.md)      
[Dynamics NAV -ohjelman käyttäminen](ui-work-product.md)  

