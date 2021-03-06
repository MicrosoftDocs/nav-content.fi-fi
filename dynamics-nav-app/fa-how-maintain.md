---
title: "Käyttöomaisuuden ylläpito"
description: "Voit pitää kunnossapitokirjaa kaikista käyttöomaisuudelle tehdyistä korjauksista ja huolloista."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: repair, service
ms.date: 06/02/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: c43ed582294a5f77408e076a13d3cd07eb9f4d0f
ms.contentlocale: fi-fi
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-maintain-fixed-assets"></a>Toimintaohje: Käyttöomaisuuden kunnossapito
Kunnossapitokulut ovat ajoittaisia rutiinikustannuksia, jotka aiheutuvat käyttöomaisuuden arvon säilyttämisestä. Toisin kuin pääoman kohentaminen, kunnossapito ei lisää arvoa.

Voit tallentaa ajantasaisen tiedoston käyttöomaisuuden kunnossapidosta ja huollosta ja ylläpitää sitä, jotta käyttöomaisuudesta olisi helposti saatavilla täydelliset kunnossapitotiedot. Aina, kun käyttöomaisuus lähetetään huoltoon, tallennetaan kaikki olennaiset tiedot, kuten huoltopäivämäärä, toimittajan numero ja huoltoliikkeen puhelinnumero. Kunnossapitorekisteröinti tallennetaan kunkin käyttöomaisuuserän osalta kyseisestä käyttöomaisuuden kortista.

Indeksointia käytetään muuttamaan arvoja yleisten hintatason muutosten mukaan. **Tee indeksimuutos KO:teen** -eräajoa voidaan käyttää kunnossapitokulujen uudelleenlaskemiseen.

## <a name="to-record-maintenance-work-on-a-fixed-asset"></a>Käyttöomaisuuden kunnossapitotyön tallentaminen
Kunnossapito, kuten huoltokäynti, voidaan tallentaa sen suorittamisen yhteydessä kyseiselle käyttöomaisuudelle **Kunnossapidon rekisteröinti** -ikkunassa.  

1. Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, syötä **Käyttöomaisuus** ja valitse sitten aiheeseen liittyvä linkki.  
2. Valitse käyttöomaisuus, jolle haluat tallentaa kunnossapitotyön. Valitse sitten **Kunnossapidon rekisteröinti** -toiminto.
3. Täytä **Kunnossapidon rekisteröinti** -ikkunassa tarvittavat kentät. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]  

## <a name="to-post-maintenance-costs-from-a-fixed-asset-gl-journal"></a>Kunnossapitokustannusten kirjaaminen käyttöomaisuuden KP-päiväkirjasta
1. Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, syötä **Poistokirjaluettelo** ja valitse sitten aiheeseen liittyvä linkki.  
2. Valitse poistokirja, joka on liitetty käyttöomaisuuteen, ja valitse sitten **Muokkaa**-toiminto.
3. Varmista, että **Poistokirjakortti**-ikkunan **Kunnossapito**-valintaruutua ei ole valittu. Näin varmistetaan, että kunnossapitokustannuksia ei kirjata pääkirjanpitoon.
4. Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, syötä **KO - KP-päiväkirjat** ja valitse sitten aiheeseen liittyvä linkki.  
5. Luo alkuperäisen päiväkirjan rivi ja täytä kentät tarpeen mukaan.
6. Valitse **KO:n kirjaustyyppi** -kentässä **Kunnossapito**.
7. Valitse **Syötä KO-vastatili** -toiminto. Toinen päiväkirjan rivi luodaan vastatilille, joka on määritetty kunnossapidon kirjaamista varten.

    > [!NOTE]  
>   Vaihe 7 toimii vain, jos seuraavat arvot on määritetty: Käyttöomaisuuden kirjausryhmän **KO:n kirjausryhmän kortti** -ikkunan **Kunnossapitotili**-kenttä sisältää pääkirjanpidon debet-tilin ja **Kunnossapidon vastatili** -kenttä sisältää sen pääkirjanpitotilin, jolle arvonkorotuksen vastatilitapahtumat kirjataan. Lisätietoja on "Käyttöomaisuuden kirjausryhmien määrittäminen" -osassa kohdassa [Toimintaohje: Käyttöomaisuuden yleisten tietojen määrittäminen](fa-how-setup-general.md).
8. Valitse **Kirjaa**-toiminto.

## <a name="to-follow-up-on-fixed-assets-service-visits"></a>Käyttöomaisuuden huoltokäyntien seuraaminen
Tulosta **Kunnossapito – Seuraava huolto** -raportti, kun haluat tarkastella käyttöomaisuuseriä, joille on aikataulutettu huoltokäynti. Tätä raporttia voidaan käyttää myös silloin, kun päivitetään käyttöomaisuuskorttien **Seuraava huoltopvm** -kenttää.  

1. Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, syötä **Kunnossapidon seuraava huolto** ja valitse sitten aiheeseen liittyvä linkki.  
2. Täytä **Aloituspvm**- ja **Lopetuspvm**-kenttä.  
3. Valitse **Tulosta**- tai **Esikatsele**-painike.

## <a name="to-monitor-maintenance-costs"></a>Kunnossapitokustannusten valvonta
Kunnossapitokustannuksia voi tarkastella käyttöomaisuuden tilastossa.  

1. Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, syötä **Käyttöomaisuus** ja valitse sitten aiheeseen liittyvä linkki.
2. Valitse käyttöomaisuus, jonka kunnossapitokustannuksia haluat tarkastella. Valitse sitten **Poistokirjat**-toiminto.
3. Valitse **KO:n poistokirjat** -ikkunassa kyseinen käyttöomaisuuden poistokirja ja valitse sitten **Tilasto**-toiminto.
4. Valitse **Käyttöomaisuustilastot**-ikkunassa **Kunnossapito**-kenttä.

Avautuvassa **Kunnossapitotapahtumat**-ikkunassa näkyvät ne tapahtumat, joista summa muodostuu **Kunnossapito**-kentässä.

## <a name="to-view-or-print-maintenance-costs-for-multiple-fixed-assets"></a>Useiden käyttöomaisuuserien kunnossapitokustannusten tarkasteleminen tai tulostaminen
**Kunnossapito – Analyysi** -raportissa voidaan valita, halutaanko kunnossapitokustannukset nähdä yhdeltä, kahdelta vai kolmelta kunnossapitokoodilta tietyn päivämäärän tai jakson osalta. Voit myös tarkastella kaikkien valittujen käyttöomaisuuserien kokonaissummaa vai tietyn omaisuuserän kokonaissummaa.

1. Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, syötä **Kunnossapitoanalyysi** ja valitse sitten aiheeseen liittyvä linkki.
2. Täytä tarvittavat kentät.
3. Valitse **Tulosta**- tai **Esikatsele**-painike.

## <a name="to-view-maintenance-ledger-entries"></a>Kunnossapitotapahtumien katsominen
Voit tutkia kunnossapitokustannuksia myös tarkastelemalla kunnossapitotapahtumia.  

1. Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, syötä **Käyttöomaisuus** ja valitse sitten aiheeseen liittyvä linkki.
2. Valitse käyttöomaisuus, jonka tapahtumia haluat tarkastella. Valitse sitten **Poistokirjat**-toiminto.
3. Valitse **KO:n poistokirjat** -ikkunassa kyseinen käyttöomaisuuden poistokirja ja valitse sitten **Kunnossapitotapahtumat**-toiminto.

## <a name="to-view-or-print-maintenance-ledger-entries-for-multiple-fixed-assets"></a>Useiden käyttöomaisuuserien kunnossapitotapahtumien tarkasteleminen tai tulostaminen
**Kunnossapito - Erittely** -raportin avulla voit tarkastella ja tulostaa yhden tai usean käyttöomaisuuserän kunnossapitotapahtumia.  

1. Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, syötä **Kunnossapitotiedot** ja valitse sitten aiheeseen liittyvä linkki.
2. Täytä tarvittavat kentät.
3. Valitse **Tulosta**- tai **Esikatsele**-painike.

## <a name="see-also"></a>Katso myös
[Käyttöomaisuus](fa-manage.md)  
[Käyttöomaisuuden määrittäminen](fa-setup.md)  
[Rahoitus](finance.md)  
[Tervetuloa [!INCLUDE[d365fin_long](includes/d365fin_long_md.md)]iin!](index.md)  
[[!INCLUDE[d365fin](includes/d365fin_md.md)] -ohjelman käyttäminen](ui-work-product.md)

