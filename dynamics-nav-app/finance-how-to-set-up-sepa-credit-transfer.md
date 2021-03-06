---
title: "SEPA-hyvityksen siirron määrittäminen"
description: "Tietoja SEPA-hyvityksen siirron määrittämisestä Dynamics NAV -ohjelmassa."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: sepa, credit, transfer, payment,
ms.date: 08/21/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 5dd85579a39fc9bfb3bb362e9573facc0c0a3977
ms.contentlocale: fi-fi
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-set-up-sepa-credit-transfer"></a>Toimintaohje: SEPA-hyvityksen siirron määrittäminen
Voit viedä maksuja **Maksupäiväkirja**-ikkunasta tiedostoon siirrettäväksi verkkopankkiisi liittyvien tilisiirtojen käsittelemiseksi. [!INCLUDE[d365fin](includes/d365fin_md.md)] tukee SEPA-hyvitysten siirtomuotoa, mutta maa- tai aluekohtaisesti voi olla käytettävissä muita sähköisiä maksumuotoja.  

Jos haluat ottaa käyttöön sellaisten pankkitiedostomuotojen viennin, joita [!INCLUDE[d365fin](includes/d365fin_md.md)] ei tue suoraan, voit määrittää tiedonsiirtomäärityksen tiedonsiirtokehyksen avulla. Lisätietoja on kohdassa [Toimintaohje: Tiedonsiirtomääritysten määrittäminen](across-how-to-set-up-data-exchange-definitions.md).  

Ennen kuin voit käsitellä maksun sähköisesti viemällä maksutiedostot SEPA-hyvityksen siirto -muodossa, sinun on suoritettava seuraavat asetukset:  

* Määritä kyseinen pankkitilin käsittelemään SEPA-hyvityksen siirtomuoto  
* Määritä toimittajan kortit, jotta voit käsitellä maksut viemällä tiedostot SEPA-hyvityksen siirtomuotoon  
* Määritä liittyvä yleisen päiväkirja erä ottamaan käyttöön maksujen vienti **Maksupäiväkirja**-ikkunasta  
* Yhdistä vähintään yhden maksutyypin tiedonsiirtomääritys liittyvään maksutapaan  

### <a name="to-set-up-a-bank-account-for-sepa-credit-transfer"></a>Pankkitilin määrittäminen SEPA-hyvityksen siirtoa varten  
1. Syötä **Etsi**-ruudussa **Pankkitilit** ja valitse sitten vastaava linkki.  
2. Avaa sen pankkitilin kortti, josta viet maksutiedostot SEPA-hyvitys siirtomuodossa.  
3. Valitse **Siirto**-välilehden **Maksun vientimuoto** -kentässä **SEPADD**.  
4. Valitse **SEPA CT -viestitunnus nrosarja** -kentässä numerosarjat, joista numerot määritetään SEPA-hyvityksen siirtotapahtumille.  
5. Varmista, että **IBAN**-kenttä on täytetty.  

    > [!NOTE]  
    >  **Valuuttakoodi**-kentän asetuksena on oltava **EUR**, koska SEPA-hyvityksen siirrot voidaan tehdä vain euroina.  

### <a name="to-set-up-a-vendor-card-for-sepa-credit-transfer"></a>Toimittajan kortin määrittäminen SEPA-hyvityksen siirtoa varten  
1. Syötä **Etsi**-ruudussa **Toimittajat** ja valitse sitten vastaava linkki.  
2. Avaa sen toimittajan kortti, josta maksat sähköisesti viemällä maksutiedostot SEPA-hyvitys siirtomuodossa.  
3. Valitse **Maksu**-pikavälilehden **Maksutavan koodi** -kentässä **PANKKI**.  
4. Valitse **Ensisijainen pankkitili** -kentässä pankki, johon rahat siirretään, kun ne käsitellään verkkopankissasi.  

     **Ensisijainen pankkitili** -kentän arvo kopioidaan **Maksupäiväkirja**-ikkunan **Vastaanottajan pankkitili** -kenttään.  

### <a name="to-set-the-payment-journal-up-to-export-payment-files"></a>Maksupäiväkirjan määrittäminen maksutiedostojen vientiä varten  
1. Syötä **Etsi**-ruudussa **Maksupäiväkirjat** ja valitse sitten vastaava linkki.  
2. Avaa maksupäiväkirja, jota käytät maksujen käsittelyyn viemällä tiedostot SEPA-hyvitys siirtomuodossa.  
3. Valitse **Erän nimi** -kentässä avattava luettelon painike.  
4. Valitse **Yleisen päiväkirjan erät** -ikkunan **Kotisivun**-välilehden **Hallinta**-ryhmässä **Muokkaa luetteloa**.  
5. Valitse sen maksupäiväkirjan rivillä, jonka avulla viet maksut, **Salli maksun vienti** -valintaruutu.  

### <a name="to-connect-the-data-exchange-definition-for-one-or-more-payment-types-with-the-relevant-payment-method-or-methods"></a>Vähintään yhden maksutyypin tiedonsiirtomäärityksen yhdistäminen liittyvään maksutapaan  
1. Syötä **Etsi**-ruudussa **Maksutavat** ja valitse sitten vastaava linkki.  
2. Valitse **Maksutavat** -ikkunassa ensin maksutapa, jolla maksut viedään, ja sitten **Maksun vientirivin määritys** -kenttä.  
3. Valitse **Maksun vientirivin määritykset** -ikkunassa koodi, jonka määritit **Rivimääritykset**-pikavälilehden **Koodi**-kentässä ohjeaiheen [Toimintaohje: Tiedonsiirtomääritysten määrittäminen](across-how-to-set-up-data-exchange-definitions.md) kohdan Tiedoston rivien ja sarakkeiden muotoilun kuvaaminen vaiheessa 4.  

    Suoraveloitusvaltakirja lisätään automaattisesti **Suoraveloitusvaltakirjan tunnus** -kenttään, kun luot myyntilaskun vaiheessa 2 valitulle asiakkaalle. Lisätietoja on kohdassa [Toimintaohje: Toistuvien myynti- ja ostorivien luominen](sales-how-work-standard-lines.md).  

## <a name="see-also"></a>Katso myös  
[Maksujen kerääminen SEPA-suoraveloitusperintänä](finance-collect-payments-with-sepa-direct-debit.md)  
[Toimintaohje: Tiedonsiirtomääritysten määrittäminen](across-how-to-set-up-data-exchange-definitions.md)  
[Toimintaohje: Toistuvien myynti- ja ostorivien luominen](sales-how-work-standard-lines.md)  
[Sähköinen tiedonsiirto](across-data-exchange.md)  

