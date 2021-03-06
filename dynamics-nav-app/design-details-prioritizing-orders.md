---
title: Rakennetiedot - tilausten priorisointi
description: "Lisätietoja kysynnän ja tarjonnan vaatimusten priorisoinnista."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: design, priority, prioritize, order, sku, demand, supply
ms.date: 07/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: c01ad1bb74e01ff81f35159865eddf14e9a34910
ms.contentlocale: fi-fi
ms.lasthandoff: 10/16/2017

---
# <a name="design-details-prioritizing-orders"></a>Rakennetiedot: tilausten priorisointi
Pyydetty tai käytettävissä oleva päivämäärä edustaa annetun varastointiyksikön korkeinta prioriteettia. Tämän päivän kysyntä tulee käsitellä ennen seuraavan viikon kysyntää. Mutta tämän kokonaisprioriteetin lisäksi suunnittelujärjestelmä suosittelee myös kysynnän tyyppiä, joka olisi täytettävä ennen toisen kysynnän täyttämistä. Vastaavasti se ehdottaa mitä tarjontalähdettä olisi sovellettava ennen muiden tarjontalähteiden käyttämistä. Tämä tehdään tilauksen prioriteettien mukaan.  
  
Ladattu kysyntä ja tarjonta lisätään arvioidun varaston profiiliin seuraavilla prioriteeteilla:  
  
## <a name="priorities-on-the-demand-side"></a>Kysyntäpuolen prioriteetit  
1. Jo toimitettu: nimiketapahtuma  
2. Ostopalautustilaus  
3. Myyntitilaus  
4. Huoltotilaus  
5. Tuotannon komponenttitarve  
6. Kokoonpanotilauksen rivi  
7. Lähtevä siirtotilaus  
8. Puitetilaus (jota liittyvä myyntitilaukset eivät ole vielä käyttäneet)  
9. Ennuste (jota muut myyntitilaukset eivät ole vielä kuluttaneet)  
  
> [!NOTE]  
>  Ostopalautuksia ei tavallisesti sisällytetä tarjonnan suunnittelun, ne tulisi aina varata erästä,joka aiotaan palauttaa. Jos se ei ole varattuna, ostopalautukset vaikuttavat saatavuuteen ja ne priorisoidaan erittäin korkealle, jotta vältetään mahdollisuus, että suunnittelujärjestelmä ehdottaa toimitustilausta vain ostopalautuksen käsittelemiseksi.  
  
## <a name="priorities-on-the-supply-side"></a>Tarjontapuolen prioriteetit  
1. Jo varastossa: nimiketapahtuma (suunnittelun joustavuus = ei mitään)  
2. Myynnin palautustilaus (suunnittelun joustavuus = ei mitään)  
3. Tuleva siirtotilaus  
4. Tuotantotilaus  
5. Kokoonpanotilaus  
6. Ostotilaus  
  
## <a name="priority-related-to-the-state-of-demand-and-supply"></a>Kysynnän ja tarjonnan tilaan liittyvä prioriteetti  
Riippumatta kysynnän ja tarjonnan määrittämistä prioriteeteista, nykyinen tila suoritusprosessissa määrittää myös prioriteetin. Esimerkiksi varastoinnin aktiviteeteilla on vaikutus ja myyntien tila, osto-, siirto-, kokoonpano- ja tuotantotilaukset otetaan huomioon:  
  
1. Osittain käsitelty (suunnittelun joustavuus = ei mitään)  
2. Jo käsittelyssä varastossa (suunnittelun joustavuus = ei mitään)  
3. Julkaistu - kaikki tilaustyypit (suunnittelun joustavuus = rajoittamaton)  
4. Sitovasti suunniteltu tuotantotilaus (suunnittelun joustavuus = rajoittamaton)  
5. Suunniteltu/avoin – kaikki tilaustyypit (suunnittelun joustavuus = rajoittamaton)  
  
## <a name="see-also"></a>Katso myös  
[Rakennetiedot: kysynnän ja tarjonnan täsmäytys](design-details-balancing-demand-and-supply.md)   
[Rakennetiedot: suunnittelujärjestelmän keskeiset käsitteet](design-details-central-concepts-of-the-planning-system.md)   
[Rakennetiedot: Tarjonnan suunnittelu](design-details-supply-planning.md)
