---
title: Dynamics NAV -ohjelman SEPA-suoraveloitus
description: "Voit periä maksut suoraan asiakkaan pankkitililtä SEPA-muodon mukaisesti."
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
ms.openlocfilehash: 9ead1f76883e3c8d98bef8c61175766ccf1414e7
ms.contentlocale: fi-fi
ms.lasthandoff: 10/16/2017

---
# <a name="collecting-payments-with-sepa-direct-debit"></a>Maksujen periminen SEPA-suoraveloituksena
Asiakkaan suostumuksella voit kerätä maksut suoraan asiakkaan pankkitililtä SEPA-muodon mukaisesti.  

 Määritä ensin pankkitiedoston vientimuoto, joka ohjaa pankkia suorittamaan suoraveloituksen. Määritä sitten asiakkaan maksutapa. Määritä lopuksi asiakkaasi kanssa sovitun mukainen suoraveloitusvaltakirja, jolla heidän maksunsa peritään tietyllä sopimusjaksolla.  

 Jos haluat ohjata pankkia siirtämään maksusumman asiakkaan pankkitililtä yrityksesi tilille, loit suoraveloitusperintämerkinnän, joka säilyttää tiedot pankkitileistä ja kyseessä olevista myyntilaskuista sekä suoraveloitusvaltakirjasta. Syntyvästä suoraveloitusperintämerkinnästä viet sitten perintämerkintään perustuvan XML-tiedoston, jonka lähetät tai lataat verkkopankkiin käsittelyä varten. Kaikista maksuista, joita ei voitu käsitellä, tiedotetaan sinulle pankin toimesta. Sinun täytyy sitten manuaalisesti hylätä kyseessä olevat suoraveloitusmerkinnät.  

 Voit määrittää vakioasiakasmyyntikoodin suoraveloitusmaksumenetelmällä ja valtakirjatiedoilla. Voit sitten käyttää **Luo vakioasiakaslaskut** -eräajoa ja luoda useita myyntilaskuja, joissa suoraveloitustiedot on täytetty valmiiksi. Tämä voidaan tehdä manuaalisesti tai automaattisesti maksun eräpäivän mukaisesti.  

 Kun maksut on käsitelty onnistuneesti pankin tiedottamalla tavalla, voit kirjata maksukuitit joko suoraan **Suoraveloitusperintätapahtumat**-ikkunassa tai siirtää maksurivit päiväkirjaan, johon kirjaat maksukuitit, kuten **Kassapäiväkirja**-ikkuna. Vaihtoehtoisesti kassanhallintamenetelmästäsi riippuen, voit odottaa ja kohdistaa maksut osana pankin täsmäytystä.  

> [!NOTE]  
>  Kun maksut kerätään SEPA-suoraveloituksen avulla, myyntilaskun valuutan on oltava EURO.  

 Seuraavassa taulukossa on tehtäväsarja ja linkit tehtäviä käsitteleviin aiheisiin.   

|**Tehtävä**|**Katso**|  
|------------|-------------|  
|Valmistele pankkitilimuodot, maksutavat ja asiakkaan SEPA-suoraveloitussopimukset.|[Toimintaohje: SEPA-suoraveloituksen määrittäminen](finance-how-to-set-up-sepa-direct-debit.md)|  
|Ohjaa pankkiasi siirtämään maksusummat asiakkaan pankkitileiltä yrityksesi pankkitilille SEPA-suoraveloitusasetustesi mukaisesti.|[Toimintaohjeet: SEPA-suoraveloitusperintätapahtumien luominen ja vieminen pankkitiedostoon](finance-how-create-sepa-direct-debit-collection-entries-export-bank-file.md)|  
|Määritä asiakkaan vakiomyyntikoodit suoraveloituslaskuille ja luo myyntilaskuja suoraveloitustiedoilla, kun laskut erääntyvät maksettavaksi.|[Toimintaohje: Toistuvien myynti- ja ostorivien luominen](sales-how-work-standard-lines.md)|  
|Kirjaa SEPA-suoraveloituksina suoritetut maksut.|[Toimintaohje: SEPA-suoraveloitusmaksujen kirjaaminen](finance-how-to-post-sepa-direct-debit-payment-receipts.md)|  

## <a name="see-also"></a>Katso myös  
[Myyntisaamisten hallinta](receivables-manage-receivables.md)

