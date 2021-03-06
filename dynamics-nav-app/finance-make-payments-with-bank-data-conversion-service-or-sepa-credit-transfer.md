---
title: "Sähköisten maksujen maksutavan valitseminen"
description: "Käsittele maksut toimittajille viemällä tiedoston yhdessä maksutietojen kanssa päiväkirjan riveiltä."
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 08/21/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: baafa833fb170fb05f866aac91a05085545aaf97
ms.contentlocale: fi-fi
ms.lasthandoff: 10/16/2017

---
# <a name="make-payments-with-bank-data-conversion-service-or-sepa-credit-transfer"></a>Suorita maksut pankkitietojen muunnospalvelulla tai SEPA-hyvityksen siirrolla
**Maksupäiväkirja**-ikkunassa voit käsitellä maksut toimittajillesi viemällä tiedoston yhdessä maksutietojen kanssa päiväkirjan riveiltä. Voit sitten ladata tiedoston verkkopankkiin, jossa liittyvät rahansiirrot käsitellään. [!INCLUDE[d365fin](includes/d365fin_md.md)] tukee SEPA-hyvitysten siirtomuotoa, mutta maa- tai aluekohtaisesti voi olla käytettävissä muita sähköisiä maksumuotoja.   

 Kun haluat ottaa SEPA-hyvityksen siirrot käyttöön, määritä ensin pankkitili, toimittaja ja yleinen päiväkirja, johon maksupäiväkirja perustuu. Tämän jälkeen maksut valmistellaan toimittajia varten automaattisesti täyttämällä erääntyneet maksut ja määritetyt kirjauspäivämäärät **Maksupäiväkirja**-ikkunaan.  

> [!NOTE]  
>  Kun olet varmistanut, että pankki on käsitellyt maksut onnistuneesti, voit jatkaa maksupäiväkirjan rivien kirjaamista.  

 Seuraavassa taulukossa on tehtäväsarja ja linkit tehtäviä käsitteleviin aiheisiin.   

|**Tehtävä**|**Katso**|  
|------------|-------------|  
|Voit aktivoida pankkitietojen muuntopalvelun minkä tahansa pankin tiliotteen muuttamiseksi tuotavaan muotoon, tai voit muuttaa viedyt maksutiedostot pankkisi vaatimaan muotoon.|[Toimintaohje: Pankkitietojen muuntopalvelun määrittäminen](bank-how-setup-bank-data-conversion-service.md)|  
|Määritä pankkitili, myyjä ja maksuloki SEPA-tilisiirrolle.|[Toimintaohje: SEPA-hyvityksen siirron määrittäminen](finance-how-to-set-up-sepa-credit-transfer.md)|  
|Täytä maksupäiväkirja toimittajiin kohdistuvilla erääntyvillä maksuriveillä ja vaihtoehdolla lisätä kirjauspäivämäärät perustuen liittyvien ostoasiakirjojen eräpäivään.|[Ostovelkojen hallinta](payables-manage-payables.md)|  
|Vie maksupäiväkirjan rivit tiedostoon SEPA-hyvityksen siirtomuodossa.|[Toimintaohje: Maksujen vieminen pankkitiedostoon](payables-how-export-payments-bank-file.md)|  
|Tarkista, mitkä maksut on viety ja mihin tiedostoihin.|Hyvityksen siirron rekisterit|  
|Kirjaa maksut sen jälkeen, kun pankki on käsitellyt ne onnistuneesti.|[Yleisten päiväkirjojen käyttäminen](ui-work-general-journals.md)|  

## <a name="see-also"></a>Katso myös  
[Toimintaohje: Pankkitietojen muuntopalvelun määrittäminen](bank-how-setup-bank-data-conversion-service.md)  
[Toimintaohje: SEPA-hyvityksen siirron määrittäminen](finance-how-to-set-up-sepa-credit-transfer.md)  
[Ostovelkojen hallinta](payables-manage-payables.md)   
[Yleisten päiväkirjojen käyttäminen](ui-work-general-journals.md)  
[Maksujen kerääminen SEPA-suoraveloitusperintänä](finance-collect-payments-with-sepa-direct-debit.md)   

