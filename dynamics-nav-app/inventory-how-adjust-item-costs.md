---
title: Nimikekustannusten muokkaaminen manuaalisesti
description: "Voit muuttaa nimikkeen varastonarvostusta FIFO- tai Keskiarvo-arvostusmenetelmällä, esimerkiksi silloin, kun nimikkeen kustannusten muutoksen syynä on jokin muu kuin tapahtuma."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: cost adjustment, cost forwarding, costing method, inventory valuation, costing
ms.date: 08/07/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 40647e0263b7c21c1f085cd6dde449f8210ede10
ms.contentlocale: fi-fi
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-adjust-item-costs"></a>Toimintaohje: Nimikekustannusten muokkaaminen
Nimikekustannus (varastoarvo) voi muuttua, kun ostat nimikkeen ja myyt sen myöhemmin, koska rahtikulut lisätään ostohintaan nimikkeen myynnin jälkeen. Kustannusten muuttamisella on merkitystä etenkin tilanteissa, jossa tavaroita myydään ennen tavaroiden oston laskuttamista. Jotta oikea varastoarvo on tiedossa, nimikekustannukset on mukautettava säännöllisesti. Näin varmistetaan, että tuottotilastot ovat ajan tasalla ja talouden avaintunnusluvut ovat oikein. Katso lisätietoja kohdasta [Rakennetiedot: kustannuksen muutos](design-details-cost-adjustment.md).

Perussäännön mukaan nimikekortin **Yksikkökustannus**-kentässä olevan arvon perustana on vakiokustannus niiden nimikkeiden osalta, joilla on vakioarvostusmenetelmä. Niiden nimikkeiden osalta, joilla on jokin muista arvostusmenetelmistä, arvon perustana on varastosaldo (laskutetut kustannukset ja oletetut kustannukset) jaettuna saatavilla olevalla määrällä. Lisätietoja on kohdassa Tietoja yksikkökustannuksen laskennasta.

[!INCLUDE[d365fin](includes/d365fin_md.md)]issa nimikkeiden kustannuksia muutetaan automaattisesti aina varastotapahtuman yhteydessä, kuten kirjattaessa nimikkeen ostolaskua.

Toiminnolla voi myös muuttaa manuaalisesti vähintään yhden nimikkeen kustannuksia. Tämä on kätevää esimerkiksi silloin, kun tiedät, että nimikkeen kustannukset ovat muuttuneet jonkin muun syyn kuin nimiketapahtuman vuoksi.

Nimikkeen kustannuksia muutetaan FIFO- tai Keskiarvo-arvostusmenetelmällä ohjatussa **Määritä oma yritys** -asetusten määrityksessä tai nimikkeen kortin **Arvostusmenetelmä**-kentässä tehdyn valinnan mukaan. Lisätietoja on ohjeaiheessa [Toimintaohje: Uusien nimikkeiden rekisteröiminen](inventory-how-register-new-items.md).  

Jos käytössä on FIFO-arvostusmenetelmä, nimikkeen yksikkökustannus on nimikkeen vastaanoton todellinen arvo. Varastonarvostuksessa käytetään oletusta, että ensin varastoon sijoitetut nimikkeet myydään ensin.

Jos käytät Keskiarvo-arvostusmenetelmää, nimikkeen yksikkökustannus lasketaan kussakin vaiheessa keskimääräisenä yksikkökustannuksena oston jälkeen. Varastonarvostus olettaa, että kaikki vaihto-omaisuus myydään samanaikaisesti. Jos nimike käyttää tätä arvostusmenetelmää, voit tarkastella sitä tapahtumahistoriaa, josta keskimääräinen kustannus lasketaan, valitsemalla nimikkeen kortissa **Yksikkökustannus**-kentän.

Kustannusten muuttamistoiminto käsittelee vain arvotapahtumia, joita ei ole vielä muutettu. Jos toiminto kohtaa tilanteen, jossa muutetut saapuvat kustannukset on siirrettävä niihin liittyviin lähteviin tapahtumiin, luodaan uusia muutosarvotapahtumia, jotka perustuvat alkuperäisten arvotapahtumien tietoihin, mutta sisältävät muutossumman. Kustannusten muuttamistoiminto käyttää muutostapahtumassa alkuperäisen arvotapahtuman kirjauspäivämäärää, ellei päivämäärä ole suljetulla varastokaudella. Siinä tapauksessa ohjelma käyttää seuraavan avoimen varastokauden aloituspäivämäärää. Jos varastokausia ei käytetä, **Pääkirjanpidon asetukset** -ikkunan **Ensimm. sallittu kirjauspvm** -kentässä oleva päivämäärä määrittää, milloin muutostapahtuma kirjataan.

## <a name="to-adjust-item-costs-manually"></a>Nimikekustannusten muokkaaminen manuaalisesti
1. Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, anna **Muuta kustannuksia - Nimiketapahtumat** ja valitse sitten aiheeseen liittyvä linkki.
2. Määritä **Muuta kustannuksia - Nimiketapahtumat** -ikkunassa nimikkeet, joiden kustannuksia muutetaan.
3. Valitse **OK**-painike.

## <a name="to-make-general-changes-in-the-direct-unit-cost"></a>Yleisten muutosten tekeminen välittömään yksikkökustannukseen
Jos välitöntä yksikkökustannusta on muutettava useissa nimikkeissä, voit käyttää **Muuta nimikekustannuksia tai -hintoja** -eräajoa.  

 Eräajo muuttaa nimikekortin **Yksikköhinta**-kentän sisällön. Eräajo muuttaa kentän sisällön samalla tavalla kaikille nimikkeille tai valituille nimikkeille. Eräajo kertoo kentässä olevan arvon määrittämälläsi muutoskertoimella.  

1. Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, kirjoita **Muuta nimikkeen kustannuksia tai hintoja** ja valitse sitten aiheeseen liittyvä linkki.  
2. Määritä **Muuta kenttää** -kentässä muutettava nimikkeen tai varastointiyksikön kortin kenttä.  
3. Määritä **Muutoskerroin**-kentässä kerroin, jonka mukaan arvoa muutetaan. Syötä esimerkiksi **1,5**, kun haluat suurentaa arvoa 50 %:lla.  
4. Määritä **Nimike**-pikavälilehdessä määritettävät suodattimet, kuten se, mitä nimikkeitä eräajossa käsitellään.  
5. Valitse **OK**-painike.  

## <a name="understanding-unit-cost-calculation"></a>Tietoja yksikkökustannuksen laskennasta
Perussäännön mukaan nimikekortin **Yksikkökustannus**-kentässä olevan arvon perustana on vakiokustannus niiden nimikkeiden osalta, joilla on vakioarvostusmenetelmä. Niiden nimikkeiden osalta, joilla on jokin muista arvostusmenetelmistä, arvon perustana on varastosaldo (laskutetut kustannukset ja oletetut kustannukset) jaettuna saatavilla olevalla määrällä.  

 Se, miten **Arvostusmenetelmä**-kentän sisältö vaikuttaa myyntien ja ostojen yksikkökustannuksen laskentaan, kuvataan yksityiskohtaisemmin seuraavissa luvuissa.  

## <a name="unit-cost-calculation-for-purchases"></a>Ostojen yksikkökustannuksen laskenta  
 Aina kun ostat nimikkeitä, nimikekortin **Viimeinen välitön kustannus** -kentän arvo kopioidaan ostorivin **Välitön yksikkökustannus** -kenttään tai nimikepäiväkirjan rivin Yksikkösumma-riville.  

 Se, mitä valitset **Kustannustapa**-kentässä vaikuttaa siihen, miten [!INCLUDE[d365fin](includes/d365fin_md.md)] laskee **Yksikkökustannus**-kentän sisällön riveillä.  

### <a name="costing-method-fifo-lifo-specific-or-average"></a>Kustannusmenetelmät FIFO, LIFO, Spesifi tai Keskimäärä  
 [!INCLUDE[d365fin](includes/d365fin_md.md)] laskee ostorivin **Yksikkökustannus PVA** -kentän sisällön tai nimikepäiväkirjan rivin **Yksikkökustannus**-kentän sisällön seuraavan laskukaavan mukaan:  

 "Yksikkökustannus (PVA) = (Välitön yksikkökustannus - (Alennussumma / Määrä)) * (1 + Välillinen kustannus-% / 100) + Yleiskustannus  

### <a name="costing-method-standard"></a>Arvostusmenetelmä Vakio  
 Järjestelmä syöttää **yksikkökustannus (PVA)** -kentän ostoriville sekä **yksikkökustannus** -kentän nimikepäiväkirjalle kopioimalla arvon nimikekortin **yksikkökustannus** -kentästä. Jos arvostustapa on vakio perustuu kustannus aina vakiokustannukseen.  

 Kun kirjaat oston, ohjelma kopioi yksikkökustannuksen ostoriviltä tai nimikepäiväkirjan riviltä oston nimikelaskutapahtumaan, ja sen voi nähdä nimikkeen tapahtumaluettelossa.  

### <a name="all-costing-methods"></a>Kaikki arvostusmenetelmät  
 Lähdeasiakirjan rivin yksikkökustannusta käytetään kyseiseen nimiketapahtumaan liittyvän **Kustannussumma todellinen** -kentän (tai tarpeen mukaan **Kustannussumma oletettu** -kentän) sisällön laskennassa huolimatta siitä, mikä nimikkeen arvostusmenetelmä on.  

## <a name="unit-cost-calculation-for-sales"></a>Myyntien yksikkökustannuksen laskenta  
 Kun myyt nimikkeitä, ohjelma kopioi yksikkökustannuksen nimikekortin Yksikkökustannus-kentästä myyntiriville tai nimikepäiväkirjan riville.  

 Kirjauksen yhteydessä ohjelma kopioi yksikkökustannuksen myyntilaskun nimiketapahtumaan, ja se näkyy nimikkeen tapahtumaluettelossa. [!INCLUDE[d365fin](includes/d365fin_md.md)] käyttää lähdeasiakirjan rivin yksikkökustannusta kyseiseen nimiketapahtumaan liittyvän arvotapahtuman **Kustannussumma todellinen** -kentän (tai tarpeen mukaan **Kustannussumma oletettu** -kentän) sisällön laskennassa.  

## <a name="see-also"></a>Katso myös
[Varaston kustannusten hallinta](finance-manage-inventory-costs.md)  
[Vaihto-omaisuus](inventory-manage-inventory.md)  
[Myynti](sales-manage-sales.md)  
[Osto](purchasing-manage-purchasing.md)  
[[!INCLUDE[d365fin](includes/d365fin_md.md)] -ohjelman käyttäminen](ui-work-product.md)

