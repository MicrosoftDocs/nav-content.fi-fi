---
title: KP-raporttimalleihin perustuvan KPI-verkkopalvelun asettaminen ja julkaiseminen
description: "Voit määrittää **KP-raporttimallin KPI-verkkopalvelun asetukset** -ikkunassa, miten KP-raporttimallin KPI-tiedot näytetään ja mihin tiettyihin KP-raporttimalleihin KPI:t perustuvat."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 09/08/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: b45fe6e1e5d4e5be00a6e8a34b7b4fea39b5d75b
ms.contentlocale: fi-fi
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-set-up-and-publish-kpi-web-services-based-on-account-schedules"></a>Toimintaohje: KP-raporttimalleihin perustuvan KPI-verkkopalvelun asettaminen ja julkaiseminen
Voit määrittää **KP-raporttimallin KPI-verkkopalvelun asetukset** -ikkunassa, miten KP-raporttimallin KPI-tiedot näytetään ja mihin tiettyihin KP-raporttimalleihin KPI:t perustuvat. Kun valitset **Julkaise verkkopalvelu** -painikkeen, määritellyt KP-raporttimallin KPI-tiedot lisätään julkaistujen verkkopalveluiden luetteloon **Verkkopalvelut**-ikkunassa.  

## <a name="to-set-up-and-publish-a-kpi-web-service-that-is-based-on-account-schedules"></a>KP-raporttimalleihin perustuvan KPI-verkkopalvelun määrittäminen ja julkaiseminen  

1.  Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, kirjoita **KP-raporttimallin KPI-verkkopalvelun asetukset** ja valitse sitten aiheeseen liittyvä linkki.  
2.  Täytä **Yleinen**-pikavälilehden kentät seuraavassa taulukossa kuvatulla tavalla.  

    |Kenttä|Description|  
    |---------------------------------|---------------------------------------|  
    |**Ennustettujen arvojen alku**|Määritä, missä vaiheessa ennustetut arvot näytetään KP-raporttimallin KPI-kuvaajassa.<br /><br /> Ennustetut arvot haetaan pääkirjanpidon budjetista, jonka valitset **KP-budjetin nimi** -kentässä. **Huomautus:** Jos haluat saada ennustettuja lukuja tietyn päivämäärän jälkeen osoittavat KPI-tiedot ja toteutuneet luvut ennen päivämäärää, voit muuttaa **Ensimm. sallittu kirjauspvm** -kenttää **Pääkirjanpidon asetukset** -ikkunassa. Lisätietoja on kohdassa Ensimm. sallittu kirjauspvm.|  
    |**KP-budjetin nimi**|Määritä sen pääkirjanpidon budjetin nimi, joka tarjoaa ennustettuja arvoja KP-raporttimallin KPI-verkkopalveluun.|  
    |**Jakso**|Määritä ajanjakso, jolle KP-raporttimallin KPI-verkkopalvelu perustuu.|  
    |**Näyttöperuste**|Määritä, millä aikavälillä KP-raporttimallin KPI-tiedot näytetään.|  
    |**Verkkopalvelun nimi**|Määritä KP-raporttimallin KPI-verkkopalvelun nimi.<br /><br /> Tämä nimi näkyy **Palvelun nimi** -kentässä **Verkkopalvelut** -ikkunassa.|  

    Määritä KP-raporttimalleja, jotka haluat julkaista KPI-verkkopalveluna edellisen taulukon asetusten mukaisesti.  

3.  Täytä **Raporttimallit**-pikavälilehden kentät seuraavassa taulukossa kuvatulla tavalla.  

    |Kenttä|Description|  
    |---------------------------------|---------------------------------------|  
    |**KP-raporttimallin nimi**|Määritä KP-raporttimalli, jolle KPI-verkkopalvelu perustuu.|  
    |**KP-raporttimallin kuvaus**|Määritä KP-raporttimalli kuvaus, jolle KPI-verkkopalvelu perustuu.|  

4.  Toista vaihe 3 kaikille KP-raporttimalleille, joille haluat KP-raporttimallin KPI-verkkopalvelun perustuvan.  
5.  Tarkastele tai muokkaa valittua KP-raporttimallia valitsemalla **KP-raporttimalli**-välilehdessä **Muokkaa KP-raporttimallia** -toiminnon.  
6.  Voit tarkastella luomiasi KP-raporttimallin KPI-tietoja valitsemalla **KP-raporttimallin KPI-verkkopalvelu** -toiminnon.  
7.  Julkaise KP-raporttimalli KPI-verkkopalveluna valitsemalla **Julkaise verkkopalvelu** -toiminto. Verkkopalvelu lisätään julkaistujen verkkopalveluiden luetteloon **Verkkopalvelut** -ikkunassa.  

    > [!NOTE]  
    >  Voit myös julkaista KPI-verkkopalvelun osoittamalla **KP-raporttimallin KPI-verkkopalvelun asetukset** -sivukohdetta **Verkkopalvelut** -ikkunassa. Lisätietoja on MSDN-artikkelissa [Toimintaohje: Verkkopalvelun julkaiseminen](https://msdn.microsoft.com/en-us/library/dd338978.aspx).  

## <a name="see-also"></a>Katso myös  
[Business Intelligence](bi.md)  
[Rahoitus](finance.md)  
[Rahoituksen määrittäminen](finance-setup-finance.md)  
[Pääkirjanpito ja tilikartta](finance-general-ledger.md)  
[[!INCLUDE[d365fin](includes/d365fin_md.md)] -ohjelman käyttäminen](ui-work-product.md)

