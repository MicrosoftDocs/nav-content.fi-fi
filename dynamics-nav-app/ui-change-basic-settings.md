---
title: Dynamics NAV -ohjelman perusasetusten tarkasteleminen ja muokkaaminen
description: "Tutustu, miten joitakin Dynamics NAV -ohjelman perusasetuksia voi muuttaa. Tällaisia perusasetuksia ovat esimerkiksi roolikeskus, yritys ja käsittelypäivämäärä."
documentationcenter: 
author: SusanneWindfeldPedersen
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: change Role Center, notification, change company, change work date
ms.date: 03/29/2017
ms.author: solsen
ms.translationtype: HT
ms.sourcegitcommit: b9b1f062ee6009f34698ea2cf33bc25bdd5b11e4
ms.openlocfilehash: cf5a74cea6d7906845a0e087576ab090c319f297
ms.contentlocale: fi-fi
ms.lasthandoff: 10/23/2017

---
# <a name="changing-basic-settings"></a>Perusasetusten muuttaminen
Voit tarkastella **Omat asetukset** -ikkunassa [!INCLUDE[d365fin](includes/d365fin_md.md)]in perusasetuksia ja muuttaa niitä.  

## <a name="role-center"></a>Roolikeskus
Roolikeskus edustaa kotisivua eli aloitussivua, joka on suunniteltu roolia varten. Kotisivu sisältää liiketoiminnan yleiskuvauksen. Vasemmalla olevan siirtymispalkin avulla voit helposti käsitellä asiakkaita, toimittajia, nimikkeitä jne.

Keskellä ovat toimenpideruudut. Toimenpiteet näyttää nykyiset tiedot. Valitun asiakirjan saa helposti käyttöön toimenpiteitä napsauttamalla tai napauttamalla. Suorituskykyilmaisimet voidaan määrittää niin, että ne näyttävät visuaalisesti esimerkiksi kassavirran tai tuottojen ja kulujen valitun kaavion.

Voit luoda kotisivulla myös suosikkiasiakkaiden luettelon niitä asiakkaita varten, joiden kanssa käyt kauppaa usein tai jotka vaativat erityishuomiota. Nuolten avulla voit supistaa osan sivusta, jolloin haluamillesi tiedoille jää enemmän tilaa. Kotisivun yläosassa ovat toiminnot, joita voit käyttää nykyisen sisällön käsittelemisessä. Sekin voidaan supistaa. Voit jatkaa supistetun alueen tarkastelemista valitsemalla alue tai napauttamalla sitä.

Oletusroolikeskus on **Liiketoimintajohtaja**, mutta voit valita tarvittaessa toisen roolikeskuksen. Lisätietoja on kohdassa [Toimintaohje: Roolikeskuksen vaihtaminen](change-role.md).

## <a name="company"></a>Oma yritys
Yritystoiminnot [!INCLUDE[d365fin](includes/d365fin_md.md)]in tietojen säilönä. Tietokannassa voi olla useita yrityksiä. Kerralla on kuitenkin mahdollista valita vain yksi yritys.

Oletusyrityksen nimi on CRONUS, ja se sisältää vain esittelytietoja.

> [!TIP]  
>   Jos haluat, että yritys näkyy sovelluksessa toisella nimellä (esimerkiksi aloitussivulla), määritä **Nimi**-kenttä **Yritystiedot**-sivulla tai **Näyttönimi**-kenttä **Yritykset**-sivulla.  

## <a name="work-date"></a>Työn päivämäärä
Oletuskäsittelypäivä on yleensä kuluvan päivän päivämäärä. Saatat joutua muuttamaan käsittelypäivämäärän väliaikaisesti, jotta voit suorittaa tehtäviä, kuten sellaisten tapahtumien täydentäminen, joiden päivämäärä ei ole kuluvan päivän päivämäärä.

> [!TIP]  
>   Kirjoita **w**, kun haluat antaa käsittelypäivämäärän nopeasti päivämääräkenttään. Kirjoita **t**, kun haluat syöttää nopeasti nykyisen päivämäärän päivämääräkenttään.

> [!IMPORTANT]  
>   Käsittelypäivämäärää muutetaan vain siihen asti, kunnes yritys suljetaan, tai siihen asti, kunnes päivämäärä muuttuu. Jos avaat toisen yrityksen tai jos avaat saman yrityksen uudestaan seuraavana päivänä, käsittelypäivämäärä täytyy määrittää uudestaan, jos tarvitset vielä järjestelmäpäivämäärästä poikkeavan päivämäärän.

## <a name="region"></a>Alue
**Alue**-asetus määrittää, miten päivämäärät, ajat, luvut ja valuutat näkyvät tai miten ne on muotoiltu.   

## <a name="change-when-i-receive-notifications"></a>Ilmoitusten vastaanottoajankohdan muuttaminen
Valitsemalla tämän linkin voit tarkastella tai muuttaa ilmoituksia, joita saat tietyistä tapahtumista tai tilamuutoksista esimerkiksi silloin, kun olet laskuttamassa asiakasta, jolla on erääntynyttä saldoa, tai kun käytettävissä oleva varasto on pienempi kuin myytävä määrä. Lisätietoja on kohdassa [Älykkäät ilmoitukset](ui-smart-notifications.md).

## <a name="see-also"></a>Katso myös
[[!INCLUDE[d365fin](includes/d365fin_md.md)] -ohjelman käyttäminen](ui-work-product.md)  
[Toimintaohje: Roolikeskuksen vaihtaminen](change-role.md)  
[[!INCLUDE[d365fin](includes/d365fin_md.md)] -sovelluksen mukauttaminen](ui-customizing-overview.md)  

