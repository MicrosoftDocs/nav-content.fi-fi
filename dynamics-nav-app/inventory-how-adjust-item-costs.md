---
title: 'Toimintaohje: Nimikekustannusten muokkaaminen'
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
ms.openlocfilehash: 59db38c159dd2810656edc668ee431c6414b9d90
ms.contentlocale: fi-fi
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-adjust-item-costs"></a>Toimintaohje: Nimikekustannusten muokkaaminen   
Nimikekustannus (varastoarvo) voi muuttua, kun ostat nimikkeen ja myyt sen myöhemmin, koska rahtikulut lisätään ostohintaan nimikkeen myynnin jälkeen. Jotta oikea varastoarvo on tiedossa, nimikekustannukset on mukautettava säännöllisesti.
Näin varmistetaan, että tuottotilastot ovat ajan tasalla ja talouden avaintunnusluvut ovat oikein.

**Huomautus**: Nimikekustannukset oikaistaan vain FIFO-arvostusmenetelmän avulla. Tämä tarkoittaa sitä, että nimikkeen yksikkökustannus on nimikkeen minkä tahansa vastaanoton todellinen arvo ja varaston arvostuksessa oletetaan, että varastoon ensimmäisenä asetetut nimikkeet myydään ensimmäisinä.

Kustannusten muuttamistoiminto käsittelee vain arvotapahtumia, joita ei ole vielä muutettu. Jos toiminto kohtaa tilanteen, jossa muutetut saapuvat kustannukset on siirrettävä niihin liittyviin lähteviin tapahtumiin, luodaan uusia muutosarvotapahtumia, jotka perustuvat alkuperäisten arvotapahtumien tietoihin, mutta sisältävät muutossumman. Kustannusten muuttamistoiminto käyttää muutostapahtumassa alkuperäisen arvotapahtuman kirjauspäivämäärää, ellei päivämäärä ole suljetulla varastokaudella. Siinä tapauksessa ohjelma käyttää seuraavan avoimen varastokauden aloituspäivämäärää. Jos varastokausia ei käytetä, **Pääkirjanpidon asetukset** -ikkunan **Ensimm. sallittu kirjauspvm** -kentässä oleva päivämäärä määrittää, milloin muutostapahtuma kirjataan.

**Huomautus**: Kun nimikekustannuksia on muutettu, varaston kustannukset on kirjattava pääkirjanpitoon automaattisesti tai manuaalisesti. Lisätietoja on kohdassa [Toimintaohje: Varaston kustannusten kirjaaminen pääkirjanpitoon](inventory-how-post-inventory-cost-gl.md).

Nimikekustannuksia voidaan muuttaa seuraavilla kahdella tavalla:
 - automaattisesti niin, että järjestelmä muuttaa kaikki kustannusmuutokset aina varastotapahtumien yhteydessä
 - manuaalisesti suorittamalla **Muuta kustannuksia - Nimiketapahtumat** -erätyön vähintään yhdelle nimikkeelle, kun tiedät, että nimikkeen kustannuksia on muutettu.  

## <a name="to-adjust-item-costs-automatically"></a>Nimikekustannusten muuttaminen automaattisesti
1. Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Varastonhallinnan asetukset** ja valitse sitten aiheeseen liittyvä linkki.
2. Valitse **Varastonhallinnan asetukset** -ikkunan **Automaattinen kustannusten muuttaminen** -kenttään jonkin seuraavista arvoista.

|Asetus |Toiminta |
|-------|---------|
|Ei koskaan|Kustannuksia ei muuteta kirjausten tekemisen yhteydessä.|
|Päivä|Kustannuksia muutetaan, jos kirjauspäivämäärän ja käsittelypäivämäärän ero on enintään yksi päivä.|
|Viikko|Kustannuksia muutetaan, jos kirjauspäivämäärän ja käsittelypäivämäärän ero on enintään yksi viikko.|
|Kuukausi|Kustannuksia muutetaan, jos kirjauspäivämäärän ja käsittelypäivämäärän ero on enintään yksi kuukausi.|
|Neljännes|Kustannuksia muutetaan, jos kirjauspäivämäärän ja käsittelypäivämäärän ero on enintään yksi vuosineljännes.|
|Vuosi|Kustannuksia muutetaan, jos kirjauspäivämäärän ja käsittelypäivämäärän ero on enintään yksi vuosi.|
|Aina|Kustannuksia muutetaan aina kirjausten yhteydessä kirjauspäivämäärästä riippumatta.|

## <a name="to-adjust-item-costs-manually"></a>Nimikekustannusten muokkaaminen manuaalisesti
1. Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Muuta kustannuksia - Nimiketapahtumat** ja valitse sitten aiheeseen liittyvä linkki.
2. Määritä **Muuta kustannuksia - Nimiketapahtumat** -ikkunassa nimikkeet, joiden kustannuksia muutetaan. Määritä myös, kirjataanko muutetut kustannukset pääkirjanpitoon samanaikaisesti.

## <a name="see-also"></a>Katso myös
[Varaston hallinta](inventory-manage-inventory.md)  
[Varaston kustannusten kirjaaminen pääkirjanpitoon](inventory-how-post-inventory-cost-gl.md)  
[Myynnin hallinta](sales-manage-sales.md)  
[Ostojen hallinta](purchasing-manage-purchasing.md)

