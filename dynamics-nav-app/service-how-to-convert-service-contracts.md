---
title: Huoltosopimusten muuntaminen
description: "Koska ALV:n muutostyökalu ei voi muuntaa huoltosopimuksia, nämä sopimukset on muunnettava manuaalisesti. Tässä aiheessa kuvataan useita vaihtoehtoisia menetelmiä, joita voit käyttää palvelusopimuksen muuntamista varten."
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 09/08/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 2ae15fef88b10072a5c1dffa8e2673fe9413dd27
ms.contentlocale: fi-fi
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-convert-service-contracts-that-include-vat-amounts"></a>Toimintaohje: ALV-summia sisältävien huoltosopimusten muuntaminen
Koska ALV:n muutostyökalu ei voi muuntaa huoltosopimuksia, nämä sopimukset on muunnettava manuaalisesti. Tässä aiheessa kuvataan useita vaihtoehtoisia menetelmiä, joita voit käyttää palvelusopimuksen muuntamista varten.  

> [!NOTE]  
>  Tämä aihe tarjoaa korkeatasoisen työnkulun.  

 Seuraavassa ohjeessa neuvotaan, miten korjataan etukäteen maksetun huoltotilauksen lasku, joka on luotu vuoden etukäteen.  

> [!NOTE]  
>  Määritä tässä esimerkissä käsittelypäivämääräksi 01.01.2017.  

### <a name="to-correct-an-invoice-for-a-prepaid-service-contract"></a>Korjaa ennakkoon maksetun huoltosopimuksen lasku  
1. Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, kirjoita **Sopimuksen hallinta** ja valitse sitten aiheeseen liittyvä linkki.  
2. Valitse **Luettelot** -kohdan alta **Huoltosopimukset**.  
3. Luo uusi ennakkoon maksettu huoltosopimus. Anna aloituspäiväksi **01.01.2017** ja laskukausi asiakkaalle **20000**.  
4. Tämä sopimus on allekirjoitettava. Valitse **Kotisivu**-välilehden **Käsittely**-ryhmässä **Allekirj. sopimus**.  
5. Huoltolaskun luominen:
6. Lasku on merkitty kirjaamattomaksi huoltolaskuksi. Tarkastele huoltolaskua valitsemalla **Huolto**, valitse **Sopimuksen hallinta** ja valitse sitten **Huoltolaskut**.  
7. Kirjaa huoltolasku.  

> [!NOTE]  
>  Älä muuta kirjaamatonta huoltolaskua. Koska palvelutapahtumat luodaan laskun luonnin yhteydessä, kirjaamattoman laskun muutos ei muuta jo luotuja tapahtumia. ALV-tapahtumat luodaan laskun kirjauksen yhteydessä. Tämän avulla voi muuttaa yleisiä tuotteen kirjausryhmiä ja GSP-tuotteen kirjausryhmiä kirjaamattomassa huoltolaskussa.   

### <a name="to-create-a-credit-memo-for-vat-difference"></a>Luo ALV-erotuksen hyvityslasku  
Seuraavassa ohjeessa neuvotaan, miten luodaan hyvityslasku, joka sisältää vain jo laskutetun, **01.07.2017** alkaneen kauden ALV-erotus. Tässä esimerkissä ALV-summa kirjataan vain varainhoidon moduulin, ei palveluiden hallinta-moduuliin. Huoltotapahtumaan linkitettyjä ALV-tapahtumia ei voi korjata.  

1. Luo uusi pääkirjanpidon tili ALV-erolle. Tätä tiliä käytetään ALV-korjausten suoraan kirjaamiseen.  
2. Lisää uusi rivi ALV-kirjausasetuksiin.  

### <a name="to-create-contract-expiration-dates-in-contract-lines"></a>Luo sopimuksen vanhentumispäivämäärät sopimusriveille  
Seuraavassa ohjeessa neuvotaan, miten luodaan uusia sopimuksia käyttämällä sopimuksen vanhentumispäiviä huoltosopimusriveillä.  

1. Määritä **Huoltosopimus**-ikkunassa sopimuksen vanhenemispäivämääräksi **30.06.2017**.  
2. Valitse **Luo hyvityslasku** -toiminto, niin hyvityslasku luodaan automaattisesti aikavälille heinäkuusta 2017 joulukuuhun 2017.  
3. Koska sopimus on vanhentunut, sinun on luotava uusi sopimus uudella ALV-arvolla ajalle 1. heinäkuuta 2017 ja 31. joulukuuta 2017.  

### <a name="to-create-a-new-credit-memo"></a>Luo uusi hyvityslasku.  
Seuraavassa ohjeessa neuvotaan, miten luodaan uusi hyvityslasku käyttäen **Hae enn. maksetut sop. tapahtumat** -erä-ajoa. Vuoden 2017 tammikuun ja kesäkuun väliset tapahtumat, joita et halua korjata, poistetaan.  

1. Aja ALV-kannan muutostyökalu 1. heinäkuuta 2017. Yleinen tuotteen kirjausryhmä tai ALV-tuotteen kirjausryhmä muutetaan. Lisätietoja on kohdassa [Toimintaohje: Myynnin ja ostojen ALV:n käsitteleminen](finance-work-with-vat.md).  
2. ALV-muutostyökalun suorittamisen jälkeen, kirjoita huoltosopimuksen vanhenemispäivämäärä. Nyt voit poistaa huoltosopimuksen rivin ja luoda uuden rivin, joka on samanlainen kuin vanha.  
3. Luo uusi lasku kaudelle Tammikuu 2017 - Joulukuu 2012 uudella ALV-prosentilla.  
4. Luo toinen hyvityslasku **Huollon hyvityslaskut** -ikkunassa valitsemalla **Uusi** luodaksesi uuden huollon hyvityslaskun.  
5. Valitse **Hae enn. maksetut sop.tapaht** -toiminto.  
6. Kun muuntaminen on valmis, ALV- ja huoltotapahtumasyötteet ovat oikeat.  

## <a name="see-also"></a>Katso myös  
[Toimintaohje: Huoltosopimusten ja huoltosopimustarjousten käyttäminen](service-how-to-create-service-contracts-and-service-contract-quotes.md)  
[Rahoitus](finance.md)  
[Toimintaohje: ALV:n raportointi veroviranomaisille](finance-how-report-vat.md)  
[Toimintaohje: Myynnin ja ostojen ALV:n käsittely](finance-work-with-vat.md)  

