---
title: Rakennetiedot - tilaus
description: "Tässä ohjeaiheessa käsitellään tilausohjautuvan ympäristön tilausten välisiä linkkejä."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: design, order
ms.date: 07/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 7e8105795f4b2a45510fc50cfed4a8fadad8f1eb
ms.contentlocale: fi-fi
ms.lasthandoff: 10/16/2017

---
# <a name="design-details-order"></a>Rakennetiedot: tilaus
Tilausohjautuvassa ympäristössä nimike ostetaan tai tuotetaan yksinomaan kattamaan tiettyä kysyntää. Yleensä tämä liittyy A-nimikkeisiin. Tämä uusintatilaustapa valitaan esimerkiksi silloin, kun kysyntä ei ole säännöllistä, toimitusajalla ei ole merkitystä tai pakolliset määritteet vaihtelevat.  
  
Ohjelma luo tilaus tilauksesta -linkin, joka toimii alustavana yhteytenä tarjonnan, toimitustilauksen tai varaston ja sen kysynnän välillä, jonka tarjonta täyttää.  
  
Riippumatta tilauskäytännön käyttämisestä, tilausten välistä linkkiä voidaan käyttää suunnittelun aikana seuraavilla tavoilla:  
  
* Kun usean tason tai projektityyppisiä tuotantotilauksia luodaan tilausohjatun tuotantotavan avulla (tarvittavat komponentit sisältyvät samaan tuotantotilaukseen).  
* Kun myyntitilauksen suunnittelutoimintoa käytetään tuotantotilauksen luomiseksi myyntitilauksesta.  
  
Vaikka valmistava yritys on mielestään tilausohjattu ympäristö, on ehkä parasta käyttää erä-erästä uusintatilaustapaa, jos nimikkeet ovat täysin vakiomuotoisia ilman määritteiden variaatioita. Tämän vuoksi järjestelmä käyttää suunnittelematonta varastoa ja vain kasvattaa myyntitilauksia samalla toimituspäivämäärällä tai määritetyllä aikavälillä.  
  
## <a name="order-to-order-links-and-past-due-dates"></a>Tilausten väliset linkit ja erääntyneet määräpäivät  
Toisin kuin useimmat tarjonta- ja kysyntäjoukot, järjestelmä suunnittelee kokonaan linkitetyt tilaukset, joiden eräpäivä on ennen suunnittelun alkupäivämäärää. Liiketoimintasyy tälle poikkeukselle on se, että erityiset kysyntä-tarjonta-asetukset täytyy synkronoida tämän toimeenpanon välityksellä. Lisätietoja useimmissa kysyntä–tarjonta-tyypeissä käytettävissä jäädytetystä alueesta on kohdassa [Rakennetiedot: Tilausten käsittely ennen suunnittelun aloituspäivää](design-details-dealing-with-orders-before-the-planning-starting-date.md).  
  
## <a name="see-also"></a>Katso myös  
[Rakennetiedot: uusintatilauskäytännöt](design-details-reordering-policies.md)   
[Rakennetiedot: suunnittelun parametrit](design-details-planning-parameters.md)   
[Rakennetiedot: uusintatilauskäytäntöjen käsittely](design-details-handling-reordering-policies.md)   
[Rakennetiedot: Tarjonnan suunnittelu](design-details-supply-planning.md)
