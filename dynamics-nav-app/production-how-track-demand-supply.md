---
title: "Kysynnän ja tarjonnan välisten suhteiden seuraaminen"
description: "Voit seurata tilausverkon kysyntä- tai tarjousasiakirjojen avulla tilauskysyntää (seurattu määrä), ennustetta, myyntipuitetilausta tai suunnitteluparametria (ei-seurattu määrä), joka on kiinnittänyt huomion kyseiseen suunnitteluriviin."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 09/06/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: acf030ab57c9251671900b1262dd8441c241c185
ms.contentlocale: fi-fi
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-track-relations-between-demand-and-supply"></a>Toimintaohje: Kysynnän ja tarjonnan välisten suhteiden seuraaminen
Voit seurata tilausverkon kysyntä- tai tarjousasiakirjojen avulla tilauskysyntää (seurattu määrä), ennustetta, myyntipuitetilausta tai suunnitteluparametria (ei-seurattu määrä), joka on kiinnittänyt huomion kyseiseen suunnitteluriviin.

Suunnittelutyökirjasta saa myös suunnittelua tukevia tietoja muista kuin tilattavista yksiköistä, mikä auttaa suunnittelijaa saamaa mahdollisimman hyvän toimitussuunnitelman. Lisätietoja on kohdassa Ei-seuratut suunnitteluelementit.

## <a name="to-track-linked-items"></a>Linkitettyjen kohteiden seuraaminen
Tilauksen seurannan avulla voi nähdä, miten myyntitilaukset, tuotantotilaukset ja ostotilaukset liittyvät tuotantotilaukseen suunnittelu- ja varausjärjestelmien kautta.

Seuraavaksi käsitellään linkitettyjen nimikkeiden seuraamista sitovasti suunnitellussa tuotantotilauksessa. Nämä vaiheet ovat samankaltaiset kaikilla muilla tilaustyypeillä ja suunnittelutyökirjan riveillä.

1. Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, kirjoita **Sitovasti suun. tuotantotil.** ja valitse sitten aiheeseen liittyvä linkki.
2. Avaa asianmukainen sitovasti suunniteltu tuotantotilaus luettelosta.
3. Valitse **Rivit**-pikavälilehdessä ensin **Toiminnot**-toiminto ja sitten **Tilauksen seuranta** -toiminto.

Nykyiseen tuotantotilauksen riviin liittyvät asiakirjat näkyvät **Tilauksen seuranta** -ikkunan riveillä.

## <a name="untracked-planning-elements"></a>Ei-seuratut suunnitteluelementit
**Ei-seuratut suunnitteluelementit** -ikkuna avautuu, kun valitset **Ei-seurattu määrä** -kentän **Tilauksen suunnittelu** -ikkunassa. Sillä on kaksi tarkoitusta:

1. Se sisältää tietoja ei-seuratuista määristä, jotka näytetään, kun käyttäjä etsii ei-seurattuja määriä Tilauksen seuranta -ikkunan avulla.
2. Se sisältää varoitussanomia, jotka näytetään, kun käyttäjä napsauttaa **varoituskuvaketta** **Suunnittelutyökirja**-ikkunassa.

Ikkuna sisältää tapahtumia, jotka selittävät ei-seuratun ylijäämämäärän tilauksen seurantaverkossa. Tapahtumat luodaan suunnitteluajon aikana ja ne selvittävät, mistä tilauksen seurantarivien ei-seurattu ylijäämämäärä on peräisin. Ei-seurattu ylijäämä voi olla peräisin seuraavista kohteista:

- Tuotantoennuste
- Puitetilaukset
- Varmuusvaraston määrä
- Uusintatilauspiste
- Enimmäisvarasto
- Uusintatilausmäärä
- Enimmäistilausmäärä
- Vähimmäistilausmäärä
- Tilauskerrannainen
- Vaimennin (% eräkoosta).

## <a name="see-also"></a>Katso myös  
[Suunnittelu](production-planning.md)   
[Tuotannon määrittäminen](production-configure-production-processes.md)  
[Tuotanto](production-manage-manufacturing.md)    
[Vaihto-omaisuus](inventory-manage-inventory.md)  
[Osto](purchasing-manage-purchasing.md)  
[Rakennetiedot: Varaus, seuranta ja toimenpiteiden viestitys](design-details-reservation-order-tracking-and-action-messaging.md)  
[Rakennetiedot: Toimitusten suunnittelu](design-details-supply-planning.md)   
[Parhaiden käytäntöjen määrittäminen: Toimitusten suunnittelu](setup-best-practices-supply-planning.md)  
[[!INCLUDE[d365fin](includes/d365fin_md.md)] -ohjelman käyttäminen](ui-work-product.md)

