---
title: "Rakennetiedot - uusintatilauskäytäntöjen käsittely"
description: "Yleiskatsaus tehtävistä, joilla määritetään tuotantosuunnittelun uusintatilauskäytäntö."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 07/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 2cd1d0e770e5fd7daa92e98486038aefdb678c5a
ms.contentlocale: fi-fi
ms.lasthandoff: 10/16/2017

---
# <a name="design-details-handling-reordering-policies"></a>Rakennetiedot: uusintatilauskäytäntöjen käsittely
Uusintatilausväli on määritettävä, jotta nimike voi osallistua tarjonnan suunnitteluun. Seuraavat neljä jälkitilausohjetta on olemassa:  
  
* Kiinteä uusintatil. määrä  
* Enimmäismäärä  
* Tilaus  
* Erä-erästä  
  
Kiinteä uusintatil. määrä- ja enimmäismäärä-käytännöt liittyvät varaston suunnittelu. Vaikka varaston suunnittelu on teknisesti helpompaa kuin täsmäytys, näiden käytäntöjen tulee toimia yhdessä tarjonnan vaiheittaiseksi täsmäyttämiseksi ja tilausten seuraamiseksi. Jotta näiden kahden välisen integroinnin valvonta ja Käytetyn suunnittelulogiikan näkyvyyden määritys onnistuu, uudelleentilausmenetelmiä käsitellään tiukkojen periaatteiden avulla.  
  
## <a name="in-this-section"></a>Tämän osan sisältö  
[Rakennetiedot: uusintatilauspisteen rooli](design-details-the-role-of-the-reorder-point.md)  
[Rakennetiedot: arvioidun varastotason ja uusintatilauspisteen valvonta](design-details-monitoring-the-projected-inventory-level-and-the-reorder-point.md)  
[Rakennetiedot: aikavälin rooli](design-details-the-role-of-the-time-bucket.md)  
[Rakennetiedot: sallitun ylityksen alapuolella pysytteleminen](design-details-staying-under-the-overflow-level.md)  
[Rakennetiedot: suunnitellun negatiivisen varaston käsittely](design-details-handling-projected-negative-inventory.md)  
[Rakennetiedot: uusintatilauskäytännöt](design-details-reordering-policies.md)  
  
## <a name="see-also"></a>Katso myös  
[Rakennetiedot: suunnittelun parametrit](design-details-planning-parameters.md)   
[Rakennetiedot: suunnittelun kohdistustaulukko](design-details-planning-assignment-table.md)   
[Rakennetiedot: suunnittelujärjestelmän keskeiset käsitteet](design-details-central-concepts-of-the-planning-system.md)   
[Rakennetiedot: kysynnän ja tarjonnan täsmäytys](design-details-balancing-demand-and-supply.md)   
[Rakennetiedot: Tarjonnan suunnittelu](design-details-supply-planning.md)
