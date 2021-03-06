---
title: "Huoltosopimusten määrittäminen"
description: "Lisätietoja huoltosopimusten määrittämisestä."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: service, cost, service order
ms.date: 08/22/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 07c0cb570b6d05dc7915f526b6c8ea2ade217465
ms.contentlocale: fi-fi
ms.lasthandoff: 10/16/2017

---

# <a name="how-to-set-up-service-contracts"></a>Toimintaohje: Huoltosopimusten määrittäminen
Seuraavat on määritettävä, ennen kuin sopimuksia voi käyttää: 

* **Huoltosopimusryhmät** kerää yhteen toisiinsa jollain tavoin liittyvät huoltosopimukset.
* **Huoltosopimuksen tiliryhmiä** käytetään ryhmittelemään yhteen huoltosopimuksille luotujen huoltolaskujen huoltosopimustilit. Voit määrittää nämä ryhmät huoltosopimuksille.  
* **Sopimusmallit** määrittävät sopimusten asettelut sopimuksille, jotka sisältävät yleisimmin käytetyt huoltosopimusten tiedot. Kun luot huoltosopimustarjouksia, voit luoda ne käyttämällä malleja. Kun luot sopimustarjouksen, kentissä on automaattisesti mallikenttien sisältö.
* **Asiakasmallien** avulla voit luoda tarjouksia yhteyshenkilöille tai mahdollisille asiakkaille, joita ei ole rekisteröity asiakkaiksi [!INCLUDE[d365fin](includes/d365fin_md.md)]issa.  

## <a name="to-set-up-a-service-contract-group"></a>Huoltosopimusryhmien määrittäminen  
1. Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, kirjoita **Huoltosopimuksen ryhmät** ja valitse sitten aiheeseen liittyvä linkki.  
2. Täytä tarvittavat kentät. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]
3. Valitse **Alennus vain sopimustil.** -valintaruutu, jos haluat, että sopimus- tai huoltoalennukset ovat voimassa vain sopimushuoltotilauksille, kuten ylläpidolle.  

## <a name="to-set-up-a-service-contract-account-group"></a>Huoltosopimusten tiliryhmien määrittäminen  
1. Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, kirjoita **Huoltosopimuksen tiliryhmät** ja valitse sitten aiheeseen liittyvä linkki.  
2. Luo uusi huoltosopimuksen tiliryhmä.   
3. Täytä **Koodi**- ja **Kuvaus**-kentät. Nämä kentät muodostavat huoltotiliryhmän kuvauksen.  
4. Täytä  **Ei ennak. maksettu sop. tili** -kenttä ja valitse muiden kuin ennakkoon maksettujen sopimusten tilin KP-tilinumero.  
5. Valitse **Ennak.maksetun sopimuksen tili** -kentässä ennakkoon maksettujen sopimusten tilin KP-tilinumero.  

## <a name="to-set-up-a-contract-template"></a>Sopimusmallien määrittäminen  
1. Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, kirjoita **Huoltosopimuksen mallit** ja valitse sitten aiheeseen liittyvä linkki.  
2. Luo uusi huoltosopimusmalli.  
3. Valitse **Nro**-kenttään sopimusmallin numero.  
  
     Vaihtoehtoisesti, jos olet määrittänyt sopimusmalleille numerosarjan **Huoltohallinnon asetukset** -ikkunaan, voit painaa Enter-painiketta, niin ohjelma lisää seuraavan saatavilla olevan sopimusmallin numeron. Täytä muut kentät tarpeen mukaan.  
  
4. Täytä **Lasku**-pikavälilehden **Huoltosop. tilir.koodi** -kenttään **laskutuskausi** ja muut tiedot. Täytä muut kentät tarpeen mukaan.  
5. Lisää sopimusalennukset valitsemalla **Huoltoalennukset**-toiminto.  

## <a name="to-set-up-a-customer-template"></a>Asiakasmallien määrittäminen  
1. Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, kirjoita **Asiakasmallit** ja valitse sitten aiheeseen liittyvä linkki.  
2. Luo uusi asiakasmallin kortti.  
3. Anna **Yleinen**-pikavälilehden **Koodi**- ja **Kuvaus**-kentissä asiakasmallin koodi ja kuvaus. 
4. Määritä hakuehdot täyttämällä muut kentät, kuten **Maa-/aluekoodi**, **Territorion koodi** ja **Kielikoodi**.  
5. Täytä **Yleinen liiketoim. kirjausryhmä**- ja **Asiakkaan kirjausryhmä** -kentät.  

## <a name="see-also"></a>Katso myös
[Huoltohallinnon määrittäminen](service-setup-service.md)
