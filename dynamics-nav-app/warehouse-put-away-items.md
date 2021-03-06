---
title: "Nimikkeiden hyllyttäminen"
description: "Varaston hyllytystoiminto nimikkeiden vastaanoton tai tuotoksen jälkeen suoritetaan eri tavoin sen mukaan, miten varastoinninhallintajärjestelmän ominaisuudet on määritetty."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 08/31/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 0b68ef1b4c73eef1ac82d59587011a0fcdead096
ms.contentlocale: fi-fi
ms.lasthandoff: 10/16/2017

---
# <a name="putting-items-away"></a>Nimikkeiden hyllyttäminen
Varaston hyllytystoiminto nimikkeiden vastaanoton tai tuotoksen jälkeen suoritetaan eri tavoin sen mukaan, miten varastoinninhallintajärjestelmän ominaisuudet on määritetty. Määritysten monimutkaisuus voi vaihdella: ominaisuusluettelossa ei ole varastotoimintoja lainkaan, tilauskohtaisessa fyysisen varastoinnin perusmäärityksissä käsittelytoimintoja on vain muutama toiminto, kun laajennetuissa varastomäärityksissä kaikki varastotoiminnot tehdään ohjatun työnkulun mukaisesti. Lisätietoja on kohdassa [Varastoinninhallinnan määrittäminen](warehouse-setup-warehouse.md).

Jos haluat järjestää ja kirjata hyllytystiedot fyysisen varastoinnin asiakirjojen avulla, lisää valintamerkki sijaintikortin **Vaadi hyllytys** -kenttään. Tämä tarkoittaa, että kun saapuvan lähdeasiakirjan kautta on tulossa nimikkeitä fyysisen varastoinnin sijaintiin, järjestelmä hallitsee näiden nimikkeiden hyllytystä. Saapuva lähdeasiakirja voi olla ostotilaus, myyntipalautustilaus, saapuva siirtotilaus tai tuotantotilaus, jonka tuotos odottaa hyllytystä.  

Jos sijainti on asetettu käyttämään hyllytyskäsittelyä mutta ei vastaanoton käsittelyä, voit käyttää **Varaston hyllytys** -ikkunaa hyllytyksen tietojen järjestämiseen, tulostaa sen, antaa varsinaisen hyllytyksen tuloksen ja kirjata hyllytystiedot, mikä puolestaan kirjaa myös lähdeasiakirjan vastaanottotiedot. Tuotantotilauksen yhteydessä kirjausprosessi kirjaa tilauksen tuotoksen ja päättää tuotantotilauksen.

Jos sijainnissa on määritetty pakolliseksi sekä vastaanoton että hyllytyksen käsittely eli olet lisännyt valintamerkit sijaintikortin **Vaadi vastaanotto**- ja **Vaadi hyllytys** -kenttiin, nimikkeiden hyllytykseen käytetään eri prosessia. Tällöin hyllytyksen käsittelyyn käytetään **F. varastoinnin hyllytys** -ikkunaa Fyysisen varastoinnin hyllytys toimii muuten samoin kuin varastohyllytys, mutta hyllytystietojen kirjauksen asemesta hyllytys rekisteröidään. Huomaa, että fyysisen varastoinnin hyllytyksen rekisteröinti ei kirjaa nimikkeiden vastaanottoa. Se vain päivittää varastopaikan sisällön. Varastopäällikkönä voit järjestää hyllytystiedot hyllytystyökirjojen avulla ennen yksittäisten fyysisen varastoinnin hyllytysohjeiden luontia.

Seuraavassa taulukossa on tehtäväsarja ja linkit tehtäviä käsitteleviin aiheisiin.   

|**Tehtävä**|**Katso**|  
|------------|-------------|  
|Kirjaa nimikkeiden vastaanotto suoraan saapuvasta tilausasiakirjasta. Tämä myös kirjaa hyllytyksen, sillä fyysisen varastoinnin määritystä ei ole.|[Toimintaohje: Nimikkeiden vastaanotto](warehouse-how-receive-items.md)|  
|Hyllytä nimikkeitä tilauskohtaisesti ja kirjaa vastaanotto samassa perusvarastointimäärityksen toiminnossa.  |[Nimikkeiden hyllyttäminen varastohyllytyksen avulla](warehouse-how-to-put-items-away-with-inventory-put-aways.md)|  
|Hyllytä nimikkeitä tilauksista laajennetussa varastointimäärityksessä.|[Nimikkeiden hyllyttäminen ja fyysisen varaston hyllytykset](warehouse-how-to-put-items-away-with-warehouse-put-aways.md)|  
|Hyllytä tuotettuja ja kokoonpantuja nimikkeitä fyysisen varastoinnin perusmäärityksissä tai laajennetussa varastointimäärityksessä.|[Toimintaohje: Tuotannon tai kokoonpanon tuotoksen hyllyttäminen](warehouse-how-to-put-away-production-output.md)|
|Suunnittele optimoituja hyllytysohjeita useille kirjatuille fyysisen varastoinnin vastaanotoille, jolloin varastotyöntekijöiden ei tarvitse käsitellä suoraan vastaanottoja.|[Hyllytysten suunnitteleminen työkirjoissa](warehouse-how-to-plan-put-aways-in-worksheets.md)|  
|Hyllytä uudelleen nimikkeitä, jotka on poimittu teknisesti sisäisen poiminnan avulla, esimerkiksi sellaisessa tuotantotilauksessa, joka ei ole kuluttanut odotettua määrää.|[Toimintaohje: Poimiminen ja hyllyttäminen ilman lähdeasiakirjaa](warehouse-how-to-create-put-aways-from-internal-put-aways.md)|
|Jaa hyllytysrivi, jotta osa hyllytysmäärästä voidaan sijoittaa varastopaikkoihin, koska määritetty varastopaikka on täysi.|[Toimintaohje: Varastotoimintorivien jakaminen](warehouse-how-to-split-warehouse-activity-lines.md)|
|Hae suoraan varastotyöntekijälle määritetyt hyllytykset.|[Toimintaohje: Fyysisen varaston määritysten etsiminen](warehouse-how-to-find-your-warehouse-assignments.md)|    

## <a name="see-also"></a>Katso myös  
[Varastoinninhallinta](warehouse-manage-warehouse.md)  
[Vaihto-omaisuus](inventory-manage-inventory.md)  
[Varastoinninhallinnan määrittäminen](warehouse-setup-warehouse.md)     
[Kokoonpanon hallinta](assembly-assemble-items.md)    
[Rakennetiedot: Fyysisen varaston hallinta](design-details-warehouse-management.md)  
[[!INCLUDE[d365fin](includes/d365fin_md.md)] -ohjelman käyttäminen](ui-work-product.md)  

