---
title: Rakennetiedot - aktiivisen nimikkeen seurantatapahtumat verrattuna historiallisen nimikkeen seurantatapahtumiin
description: "Kun asiakirjarivin osia on kirjattu, vain tämä määrä siirretään nimiketapahtumiin ja sen nimikkeiden seurantanumeroihin. Haluat kuitenkin käyttää kaikkia asianmukaisia nimikkeen seurantatietoja suoraan aktiiviselta asiakirjariviltä. Eli ei ainoastaan silloin, kun haluat nähdä kirjaukset, jotka liittyvät jäljellä olevaan määrään, vaan myös silloin, kun haluat tietoa yksiköistä, jotka on tiliöity. Kun **Nimikkeen seurantarivit** -ikkunaa tarkastellaan tai muokataan, **Seurannan määrittely** (T336)- ja **Varaustapahtuma** (T337) -taulukon yhteinen sisältö löytyy väliaikaisesta versiosta T336. Tämä varmistaa, että aiempia ja aktiivisia nimikkeen seurantatietoja voi käyttää yhtenä pakettina."
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
ms.openlocfilehash: 315b5317c2ac3e2cd6a56bd243e30d4e3445a6ec
ms.contentlocale: fi-fi
ms.lasthandoff: 10/16/2017

---
# <a name="design-details-active-versus-historic-item-tracking-entries"></a>Rakennetiedot: aktiivisen nimikkeen seurantatapahtumat verrattuna historiallisen nimikkeen seurantatapahtumiin
Kun asiakirjarivin osia on kirjattu, vain tämä määrä siirretään nimiketapahtumiin ja sen nimikkeiden seurantanumeroihin. Haluat kuitenkin käyttää kaikkia asianmukaisia nimikkeen seurantatietoja suoraan aktiiviselta asiakirjariviltä. Eli ei ainoastaan silloin, kun haluat nähdä kirjaukset, jotka liittyvät jäljellä olevaan määrään, vaan myös silloin, kun haluat tietoa yksiköistä, jotka on tiliöity. Kun **Nimikkeen seurantarivit** -ikkunaa tarkastellaan tai muokataan, **Seurannan määrittely** (T336)- ja **Varaustapahtuma** (T337) -taulukon yhteinen sisältö löytyy väliaikaisesta versiosta T336. Tämä varmistaa, että aiempia ja aktiivisia nimikkeen seurantatietoja voi käyttää yhtenä pakettina.  

 Seuraavassa taulukossa esitetään, kuinka T336 ja T337 käytetään ostoskenaariossa. Lihavoidut luvut edustavat arvoja, jotka käyttäjä syöttää manuaalisesti **Nimikkeen seurantarivit** -ikkunaan.  

 Vaihe 1: luo seitsemän osan ostotilausrivi nimikkeenseurantanumeroineen.  

||**Määrä (perus)**|**Käsiteltävä määrä**|**Laskutettava määrä (perus)**|**Määrä käsitelty (perus)**|**Määrä laskutettu (perus)**|  
|-|----------------------------------------------|--------------------------------------------|------------------------------------------------------|-------------------------------------------------------|--------------------------------------------------------|  
|**T337**|7|0|0|0|0|  
|**T336**|0|0|0|0|0|  

 Vaihe 2: vastaanota neljä osaa.  

||**Määrä (perus)**|**Käsiteltävä määrä**|**Laskutettava määrä (perus)**|**Määrä käsitelty (perus)**|**Määrä laskutettu (perus)**|  
|-|----------------------------------------------|--------------------------------------------|------------------------------------------------------|-------------------------------------------------------|--------------------------------------------------------|  
|**Nimikkeen seurantarivit** -ikkuna|7|**4**|**0**|0|0|  
|**T337**|3|0|0|0|0|  
|**T336**|4|0|0|4|0|  

 Vaihe 3: vastaanota kaksi osaa ja laskuta kaksi osaa.  

||**Määrä (perus)**|**Käsiteltävä määrä**|**Laskutettava määrä (perus)**|**Määrä käsitelty (perus)**|**Määrä laskutettu (perus)**|  
|-|----------------------------------------------|--------------------------------------------|------------------------------------------------------|-------------------------------------------------------|--------------------------------------------------------|  
|**Nimikkeen seurantarivit** -ikkuna|7|**2**|**2**|4|0|  
|**T337**|1|0|0|0|0|  
|**T336**|6|0|0|6|2|  

 Vaihe 4: vastaanota yksi osa.  

||**Määrä (perus)**|**Käsiteltävä määrä**|**Laskutettava määrä (perus)**|**Määrä käsitelty (perus)**|**Määrä laskutettu (perus)**|  
|-|----------------------------------------------|--------------------------------------------|------------------------------------------------------|-------------------------------------------------------|--------------------------------------------------------|  
|**Nimikkeen seurantarivit** -ikkuna|7|**1**|**0**|6|2|  
|**T336**|7|0|0|7|2|  

 Lasku, 5 kappaletta.  

||**Määrä (perus)**|**Käsiteltävä määrä**|**Laskutettava määrä (perus)**|**Määrä käsitelty (perus)**|**Määrä laskutettu (perus)**|  
|-|----------------------------------------------|--------------------------------------------|------------------------------------------------------|-------------------------------------------------------|--------------------------------------------------------|  
|**Nimikkeen seurantarivit** -ikkuna|7|0|**5**|7|2|  
|**T336**|7|0|0|7|7|  

## <a name="see-also"></a>Katso myös  
 [Rakennetiedot: nimikkeen seuranta](design-details-item-tracking.md)   
 [Rakennetiedot: nimikkeen seurantarivit -ikkuna](design-details-item-tracking-lines-window.md)

