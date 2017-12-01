---
title: Verkkopankkitoiminta Suomessa
description: "[!INCLUDE[navnow](../../includes/navnow_md.md)] -ohjelman verkkopankkitoimintojen avulla voi käsitellä elektronisia asiakas- ja toimittajamaksuja. Toiminto tukee verkkopankkimaksujen siirron kotimaan maksuja (LM03) ja ulkomaan maksuja (LUM2). Verkkopankkimaksujen vientiä tai tuontia varten on ensin määritettävä pankin viitetiedostot, joissa määritetään maksutiedostojen käsittelytapa."
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
ms.sourcegitcommit: a16640e014e157d4dbcaabc53d0df2d3e063f8f9
ms.openlocfilehash: f94ac30588d0e9293e25f985e91412feed16ff5c
ms.contentlocale: fi-fi
ms.lasthandoff: 10/26/2017

---
# <a name="electronic-banking-in-finland"></a>Verkkopankkitoiminta Suomessa
[!INCLUDE[navnow](../../includes/navnow_md.md)] -ohjelman verkkopankkitoimintojen avulla voi käsitellä elektronisia asiakas- ja toimittajamaksuja. Toiminto tukee verkkopankkimaksujen siirron kotimaan maksuja (LM03) ja ulkomaan maksuja (LUM2). Verkkopankkimaksujen vientiä tai tuontia varten on ensin määritettävä pankin viitetiedostot, joissa määritetään maksutiedostojen käsittelytapa.  

## <a name="customer-payments"></a>Asiakasmaksut  
Kotimaan asiakasmaksut voidaan tuoda pankista ja linkittää liittyvään myyntisaatavatapahtumaan viitenumeron avulla. Tämä automaattinen toiminto mahdollistaa saapuvien maksujen linkittämisen suoraan avoimiin myyntisaataviin ilman manuaalisen käsittelyn aiheuttamaa viivettä. Seuraavissa vaiheissa kuvataan, miten asiakasmaksut tuodaan pankista tiedostoon ja miten nämä maksut linkitetään laskuihin viitenumeroiden avulla.  

- Luo myyntilasku ja liitä laskuun yksilöivä viitenumero. Asiakas käyttää tätä viitenumeroa maksaessaan laskun.  

- Tuo asiakasmaksut sisältävät maksutiedostot kassapäiväkirjaan. Nämä tiedostot sisältävät pankilta saadut viitenumerot. Maksut linkitetään myyntisaatavatapahtumaan viitenumeroiden avulla.  

- Kirjaa tiedot kassapäiväkirjaan ja sulje avoimet myyntisaatavatapahtumat tiedoston kohdistettujen maksujen avulla.  

## <a name="reference-number"></a>Viitenumero  
Viitenumero luodaan automaattisesti, kun lasku kirjataan tai tilaus kirjataan laskutettavaksi. Myyntipäiväkirjan tapahtuman viitenumeron voi kuitenkin antaa myös manuaalisesti. Tämä viitenumero ei perustu **Myyntien asetukset** -ikkunan viitenumeroasetuksiin. Jos syötät myyntipäiväkirjaan viitenumeron, vain viitenumeron oikeellisuus tarkistetaan.  

## <a name="vendor-payments"></a>Toimittajamaksut  
Voit lähettää toimittajille verkkopankkimaksuja viemällä kotimaan tai ulkomaan toimittajamaksut pankille lähetettävään siirtotiedostoon. Seuraavissa vaiheissa kuvataan, miten toimittajamaksut viedään.  

- Valitse **Lähetettävät pankkimaksut** -ikkunassa toimittajat, joille maksutiedostot luodaan.  
- Syötä maksutiedot jokaiselle maksupäiväkirjan tapahtumalle tai käytä **Ehdota toimittajamaksuja** -toimintoa, joka luo ehdotetut maksut.  
- Luo ja esikatsele maksuraportti.  
- Luo siirtotiedosto kotimaan tai ulkomaan toimittajamaksuille.  
- Lähetä maksun siirtotiedosto pankkiin.  

## <a name="see-also"></a>Katso myös  
 [Suomen paikalliset toiminnot](finland-local-functionality.md)   
 [Toimintaohje: Pankin viitetiedostojen määrittäminen](how-to-set-up-bank-reference-files.md)   
 [Toimintaohje: Maksutiedostojen luominen](how-to-generate-payment-files.md)   
 [Toimintaohje: Maksualennusten ohittaminen](how-to-disregard-payment-discounts.md)   

