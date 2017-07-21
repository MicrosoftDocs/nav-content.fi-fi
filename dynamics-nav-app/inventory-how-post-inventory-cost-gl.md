---
title: "Varaston kustannusten kirjaaminen pääkirjanpitoon"
author: SorenGP
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 59815db9c7b435ff585e1174b570029a360dea6e
ms.contentlocale: fi-fi
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-post-inventory-costs-to-the-general-ledger"></a>Varaston kustannusten kirjaaminen pääkirjanpitoon   
Kun kirjaat varastotapahtumia, kuten myyntitoimituksia, ostolaskuja tai varaston muutoksia, ohjelma kirjaa muutetut määrät ja kustannukset nimiketapahtumiin ja varaston arvojen muutokset arvotapahtumiin. Päivitä tämä varastoarvon muutos talouskirjoissa kirjaamalla varastokustannukset pääkirjanpidon liittyviin varastotileihin.

Voit kirjata varastokustannukset pääkirjanpitoon kahdella seuraavalla tavalla:

- automaattisesti, jolloin ohjelma kirjaa varastokustannukset pääkirjanpitoon aina, kun kirjaat varastotapahtuman
- manuaalisesti, jolloin varastokustannukset kirjataan pääkirjanpitoon vain, kun eräajo suoritetaan.


## <a name="to-post-inventory-costs-automatically"></a>Varaston kustannusten kirjaus automaattisesti
1. Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Varastonhallinnan asetukset** ja valitse sitten aiheeseen liittyvä linkki.
2. Valitse **Varastonhallinnan asetukset** -ikkunassa **Automaattinen kustann. kirjaus** -valintaruutu.

Ohjelma kirjaa jokaista itse kirjaamaasi varastotapahtumaa kohti sopivan arvon varastotilille, muutostilille ja myytyjen tuotteiden kustannusten tilille pääkirjanpidossa.

Vaikka käytössäsi olisi automaattinen kustannusten kirjaus, Muuta kustannuksia - Nimiketapahtumat -eräajo on silti suoritettava säännöllisesti. Se varmistaa, että tavaroiden kustannukset välitetään sopiville lähteville tapahtumille, kuten myynnille tai siirroille. Tämä on erityisen tärkeää tilanteissa, jossa tavaroita myydään ennen kuin noiden tavaroiden osto laskutetaan.

Jos varaston kustannusten pääkirjanpitoon kirjauksen aikana tapahtuu virhe ohjelman dimensioiden asetuksissa, kirjaus loppuu virheeseen.

## <a name="to-post-inventory-costs-manually"></a>Varaston kustannusten kirjaus manuaalisesti
1. Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Kirjaa varaston kustannukset kirjanpitoon** ja valitse sitten aiheeseen liittyvä linkki.
2. Kirjaa varaston kustannukset pääkirjanpitoon suorittamalla eräajo. Ohjelma luo tämän eräajon aikana KP-tapahtumia arvotapahtumien perusteella. Voit kirjata tapahtumat niin, että ne lasketaan yhteen kirjausryhmittäin.

**Huomautus**: Ohjelmassa saattaa tapahtua virhe tämän eräajon aikana, jos asetuksissa on puutteita tai dimension asetus on yhteen sopimaton. Jos dimension asetuksissa havaitaan virheitä eräajon aikana, eräajo ohittaa nämä virheet ja käyttää arvotapahtuman dimensioita. Muiden virheiden kohdalla eräajo jättää arvotapahtumat kirjaamatta ja listaa ne raportin lopussa osassa “Ohitetut tapahtumat”. Voit kirjata nämä tapahtumat korjattuasi virheet.

Saat virheluettelon näkyviin ennen kirjauksen eräajon ajoa, kun suoritat **Kirjaa varaston kustannukset kirjanpitoon - Testaa** -raportin. Testiraportissa luetteloidaan kaikki ohjelman virheet testikirjauksen aikana. Voit sitten korjata nämä virheet ja suorittaa varaston kustannusten kirjauksen eräajon niin, että tapahtumia ei ohiteta.

Jos haluat yleiskuvauksen niistä arvoista, jotka pääkirjanpitoon voi kirjata ilman kirjauksen suoritusta, voit suorittaa Kirjaa varaston kustannus KP:oon -eräajon. Arvoja ei tällöin oikeasti kirjata pääkirjanpitoon. Voit tehdä tämän poistamalla valintaruudun valinnan Kirjaa -kentässä pyyntösivulla. Näin eräajoa suoritettaessa tuotetaan raportti, jossa on arvot, jotka ovat valmiita kirjattaviksi kirjanpitoon, mutta joita ei ole kirjattu.

## <a name="see-also"></a>Katso myös
[Varaston hallinta](inventory-manage-inventory.md)    
[Toimintaohje: Nimikekustannusten muokkaaminen](inventory-how-adjust-item-costs.md)  
[Myynnin hallinta](sales-manage-sales.md)  
[Ostojen hallinta](purchasing-manage-purchasing.md)

