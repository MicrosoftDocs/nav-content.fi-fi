---
title: "Rakennetiedot - enimmäismäärä"
description: "Enimmäismääräkäytäntö on tapa ylläpitää varastoa uudelleentilauspisteen avulla."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 07/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: eb2dfa933cd80400e3143c2c0b5bc44691170baf
ms.contentlocale: fi-fi
ms.lasthandoff: 10/16/2017

---
# <a name="design-details-maximum-qty"></a>Rakennetiedot: enimmäismäärä
Enimmäismääräkäytäntö on tapa ylläpitää varastoa uudelleentilauspisteen avulla.  
  
 Kaikki kiinteää uusintatilausmäärän käytäntöä koskeva koskee myös tätä käytäntöä. Ainoa ero on ehdotetun tarjonnan määrä. Kun käytetään enimmäismääräkäytäntöä, uusintatilausmäärä määritetään dynaamisesti oletetun varaston tason perusteella. Sen vuoksi se yleensä on eri kuin tilausten välinen määrä.  
  
## <a name="calculated-per-time-bucket"></a>Laskettu aikavälikohtaisesti  
 Jälkitilausmäärä määritetään siihen ajankohtaan (ajanjakson loppu), kun suunnittelujärjestelmä havaitsee, että jälkitilauspiste on ylitetty. Tällä hetkellä järjestelmä mittaa välin nykyisestä arvioidusta varastotasosta määritettyyn enimmäisvarastoon asti. Tämä kuvaa määrää, joka tulisi järjestää uudelleen. Järjestelmä tarkistaa, onko tarjonta jo tilattu muualle vastaanotettavaksi nimikkeen toimitusaikana. Jos näin on, järjestelmä pienentää uuden toimitustilauksen määrää jo tilattujen määrien verran.  
  
 Järjestelmä varmistaa, että oletettu varasto saavuttaa vähintään uusintatilauspisteen tason. Tämä tehdään siltä varalta, että käyttäjä unohtaa määrittää varaston enimmäismäärän.  
  
## <a name="combines-with-order-modifiers"></a>Yhdistää tilausmääritteiden kanssa  
 Asetuksesta riippuen saattaa olla parasta yhdistää enimmäismäärän käytäntö tilauksen muuttujien kanssa, jotta varmistetaan tilauksen vähimmäismäärä tai sen pyöristäminen oston mittayksikön kokonaislukuun, tai jotta se jaetaan useampiin eriin tilauksen enimmäismäärän määrityksen mukaan.  
  
## <a name="combines-with-calendars"></a>Yhdistäminen kalentereihin  
 Ennen kuin uusintatilauspisteen täyttämiseen ehdotetaan uutta toimitustilausta, suunnittelujärjestelmä tarkistaa, onko tilaus ajoitettu **Yritystiedot**- ja **Sijaintikortti**-ikkunoiden **Peruskalenterin koodi** -kentässä määritettyjen kalenterien mukaiselle ei-työskentelypäivälle.  
  
 Jos suunniteltu päivämäärä ei ole työpäivä, suunnittelujärjestelmä siirtää tilauksen seuraavalle työpäivälle. Tämä voi johtaa tilaukseen, joka täyttää uusintatilauspisteen, mutta ei täytä mitään tiettyä kysyntää. Suunnittelujärjestelmä luo ylimääräisen tarjonnan vastaamaan epätasapainoiseen kysyntään.  
  
## <a name="see-also"></a>Katso myös  
 [Rakennetiedot: uusintatilauskäytännöt](design-details-reordering-policies.md)   
 [Rakennetiedot: suunnittelun parametrit](design-details-planning-parameters.md)   
 [Rakennetiedot: uusintatilauskäytäntöjen käsittely](design-details-handling-reordering-policies.md)   
 [Rakennetiedot: Tarjonnan suunnittelu](design-details-supply-planning.md)
