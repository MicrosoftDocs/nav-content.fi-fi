---
title: "Päivämääräalueiden asettaminen Dynamics NAV -ohjelmassa"
description: "Tutustu, miten luodaan raportti näyttämään tietyn ajanjakson tiedot käyttämällä Dynamics NAV -ohjelman päivämääräalueita."
documentationcenter: 
author: edupont04
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: dates, reporting, filter
ms.date: 05/29/2017
ms.author: edupont
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 2619095e8b9e48068aa9d8790a9699b4c7ff05ec
ms.contentlocale: fi-fi
ms.lasthandoff: 10/16/2017

---
# <a name="entering-date-ranges-in-dynamics-nav"></a>Päivämääräalueiden syöttäminen Dynamics NAV -ohjelmassa
Voit asettaa suodattimia, jotka sisältävät alkupäivämäärän ja loppupäivämäärän, jos haluat tarkastella vain kyseisen päivämääräalueen tai aikavälin tietoja. Päivämääräalueiden määrittämiseen liittyy erityissääntöjä: Käytetään esimerkkinä **10 pääasiakasta**:

![10 pääasiakkaan luettelon päivämääräalueen määrittäminen pyyntösivulla](./media/ui-enter-date-ranges/customer-top10-list.png)

Voit rajoittaa raportin päivämääräalueeksi viimeiset kaksi viikkoa, yhteensä kuusi viikkoa tai minkä tahansa sopivan alueen. Päivämääräalue määritetään antamalla päivämäärät ja määrittämällä alueen joko **..**- tai **|**-merkillä. Tässä esimerkissä 10 pääasiakkaan näyttäminen toukokuun kahdella ensimmäisellä viikolla edellyttää, että päivämääräsuodatin määritetään muotoon *05 01 17..05 14 17*.
Lisää esimerkkejä:

| Merkitys | Esimerkki | Sisällytetyt tapahtumat |
|---|---|---|
|Sama kuin| 12 15 16 |Vain tapahtumat, jotka on kirjattu 15.12.2016.|
|Väli| 12 15 16..01 15 17<br /><br />..12 15 16|Tapahtumat, jotka on kirjattu ajalla 15.12.2016–15.1.2017 (kyseiset päivämäärät mukaan lukien).<br /><br />Tapahtumat, jotka on kirjattu 15.12.2016 tai sitä aiemmin.|
|Joko/tai|12 15 16&#124;12 16 16|Tapahtumat, jotka on kirjattu joko 15.12. tai 16.12.2016. Jos molempina päivinä on kirjattu tapahtumia, kaikki kyseisten päivien tapahtumat näytetään.|

Eri muotoja voi myös yhdistellä:

| Esimerkki | Sisällytetyt tapahtumat |
|---|---|
|12 15 16&#124;12 01 16..05 31 17 | Tapahtumat, jotka on kirjattu joko 15.12.2011 tai ajalla 1.12.2016– 31.5.2017 (kyseiset päivämäärät mukaan lukien). |
|..12 14 16&#124;12 30 16.. | Tapahtumat, jotka on kirjattu 14.12 tai sitä ennen, tai tapahtumat, jotka on kirjattu 30.12. tai sen jälkeen – toisin sanoen kaikki muut paitsi 15.–29.12. kirjatut tapahtumat. |

Huomaa, että tässä on käytetty yhdysvaltalaista päivämäärämuoto KKPPVV. Kun [!INCLUDE[d365fin](includes/d365fin_md.md)] on saatavana muilla markkina-alueilla, saat käyttöösi tutut päivämäärämuodot.

## <a name="see-also"></a>Katso myös
[[!INCLUDE[d365fin](includes/d365fin_long_md.md)]in käyttäminen](ui-work-product.md)  
[Ehtojen antaminen suodattimiin](ui-enter-criteria-filters.md)  
[Yleiset liiketoimintatoiminnot](ui-across-business-areas.md)

