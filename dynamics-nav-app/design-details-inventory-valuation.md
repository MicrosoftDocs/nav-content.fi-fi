---
title: Rakennetiedot - varaston arvostus
description: "Varaston arvostus XE Varaston arvostus on varastonimikkeeseen kohdistettu kustannuksen määritys seuraavan yhtälön mukaisesti."
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
ms.openlocfilehash: ab8f7606bf88e208a358b90fe8a9b30460201f63
ms.contentlocale: fi-fi
ms.lasthandoff: 10/16/2017

---
# <a name="design-details-inventory-valuation"></a>Rakennetiedot: varaston arvostus
Varaston arvostus XE Varaston arvostus on varastonimikkeeseen kohdistettu kustannuksen määritys seuraavan yhtälön mukaisesti.  

Varasto lopussa = varasto alussa + netto-ostot – myytyjen tuotteiden kustannus  

Varastoarvon laskelma käyttää nimikkeiden kirjausten **Kustannussumma (tämänhetkinen)** -kenttää nimikkeelle. Kirjaukset luokitellaan kirjaustyypin XE "Kirjaustyyppi" mukaan, joka vastaa kustannusosia, välittömiä kustannuksia, välillisiä kustannuksia, varianssia, uudelleenarvostusta ja pyöristystä. Katso lisätietoja kohdasta [Rakennetiedot: kustannuskomponentit](design-details-cost-components.md).  

Tapahtumat kohdistetaan toisiinsa joko kiinteällä kohdistuksella XE Application; Fixed tai yleisen arvostusmenetelmän määrittämän kustannusvirtaoletuksen XE Method; Costing; XE Costing Method mukaisesti. Yksi varaston arvon vähennystapahtuma voidaan kohdistaa useampaan kuin yhteen nousutapahtumaan erilaisilla kirjauspäivämäärillä ja mahdollisesti erilaisilla hankintakustannuksilla XE "Acquisition Cost". Katso lisätiedot kohdasta [Rakennetiedot: nimikkeen kohdistus](design-details-item-application.md). Tämän vuoksi varastoarvon XE "Inventory Value" laskenta tiettynä päivänä perustuu positiivisten ja negatiivisten arvotapahtumiin.  

## <a name="inventory-valuation-report"></a>Varaston arvostusraportti  
Kun **Varaston arvostus** -raportin varaston arvoa lasketaan, raportti laskee ensin nimikkeen varaston arvon annettuna alkupäivämääränä. Se lisää tämän jälkeen varaston arvon kasvatukset ja vähentää varaston arvon vähennykset annettuun lopetuspäivämäärään asti. Lopputulos on varaston arvo päättymispäivänä. Raportti laskee nämä arvot laskemalla yhteen arvot **Kustannussumma (nykyinen)** -kentän arvokirjauksissa käyttäen tiliöintipäiviä suodattimina.  

Tulostetussa raportissa näkyvät aina todelliset summat eli niiden tapahtumien kustannukset, jotka on kirjattu laskutetuiksi. Raporttiin tulostuvat myös niiden tapahtumien oletetut kustannukset, jotka on kirjattu vastaanotetuiksi tai toimitetuiksi, jos lisäät valintamerkin Vaihtoehdot-pikavälilehden Sisällytä oletetut kustann. -kenttään.  

> [!IMPORTANT]  
>  **Varaston arvostus** -raportin arvot on täsmäytetty pääkirjanpidon varastotiliin. Tämä tarkoittaa sitä, että kyseiset arvotapahtumat on kirjattu pääkirjanpitoon.  

> [!IMPORTANT]  
>  Määrät raportin **Arvo**-sarakkeessa perustuvat nimikkeen tapahtumien kirjauspäivämäärään.  

## <a name="inventory-valuation---wip-report"></a>Varaston arvostus - KET-raportti  
Tuotantoyrityksen on märitettävä kolmenlaisen varaston arvo:  

* Raaka-ainevarasto  
* KET-varasto  
* Valmiiden tuotteiden varasto  

KET-varaston arvo määritetään seuraavan laskutoimituksen avulla:  

* KET-varasto lopussa = KET-varasto alussa + valmistuskustannukset – valmistettujen tuotteiden kustannus  

Ostetun varaston osalta arvotapahtumat tarjoavat varaston arvostuksen perustan. Laskelma tehdään käyttämällä arvoja nimikkeen **Kustannussumma (tämänhetkinen)** -kentässä sekä kapasiteettiarvon kirjauksia, jotka liittyvät tuotantotilaukseen.  

WIP-varaston arvostuksen tarkoituksena on määritellä niiden nimikkeiden arvo, joiden valmistus ei ole päättynyt annetulla päivämäärällä. Tämän vuoksi KET-varaston arvo perustuu kulutukseen ja kapasiteettitapahtumiin liittyviin arvotapahtumiin. Kulutustapahtumat on laskutettava kokonaan arvostuspäivänä. Tämän vuoksi **Varaston arvostus - KET** -raportissa näkyvät KET-varaston arvon osoittavat kustannukset kahdessa luokassa, jotka ovat kulutus ja kapasiteetti.  

## <a name="see-also"></a>Katso myös  
[Rakennetiedot: Täsmäytys pääkirjanpidon kanssa](design-details-reconciliation-with-the-general-ledger.md)   
[Rakennetiedot: uudelleenarvostus](design-details-revaluation.md)   
[Rakennetiedot: Tuotantotilauksen kirjaus](design-details-production-order-posting.md)
[Varaston kustannusten hallinta](finance-manage-inventory-costs.md)  
[Rahoitus](finance.md)  
[[!INCLUDE[d365fin](includes/d365fin_md.md)] -ohjelman käyttäminen](ui-work-product.md)

