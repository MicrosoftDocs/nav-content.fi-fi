---
title: Tietojen tuominen Dynamics NAV -ohjelmaan Excelin avulla
description: "Voit lisätä asiakastietoja Excelissä oletusmäärityspaketin avulla ja tuoda tiedot takaisin Dynamics NAV -ohjelmaan."
author: edupont04
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: migration, Excel
ms.date: 07/05/2017
ms.author: edupont
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: eb9b7137ee31824ba845ff336c00c6f0e59f6f5c
ms.contentlocale: fi-fi
ms.lasthandoff: 10/16/2017

---
# <a name="importing-data-from-legacy-accounting-software-using-a-configuration-package"></a>Tietojen tuominen vanhasta kirjanpito-ohjelmistosta määrityspaketin avulla
Voit tuoda päätiedot ja joitakin tapahtumatietoja muista rahoitusjärjestelmistä [!INCLUDE[d365fin](includes/d365fin_md.md)]in oletusmäärityspaketin perusteella. Voit käsitellä tuotavaa pakettia **Määrityspaketit**-ikkunassa, jossa voit myös tarkistaa tiedot ennen paketin käyttämistä.  

Jos RapidStart Services for Microsoft Dynamics on sinulle tuttu, tunnet myös määrityspaketit. Oletusmäärityspaketti tukee useimpia vanhasta järjestelmästä tuotavia tietotyyppejä. Voit sitten lisätä Excelissä vanhan järjestelmän tiedot ja käyttää [!INCLUDE[d365fin](includes/d365fin_md.md)]in liiketoimintalogiikan mukaisia määrityksiä.  

> [!TIP]  
>   Voit myös käyttää tietojen siirtotoimintoja, jos haluat tuoda tietoja QuickBooksista tai Dynamics GP:stä. Lisätietoja on kohdassa [QuickBooks-tietojen siirto](ui-extensions-quickbooks-data-migration.md) tai [Dynamics GP -tietojen siirto](ui-extensions-dynamicsgp-data-migration.md).  

## <a name="working-with-data-in-excel"></a>Tietojen käsittely Excelissä
Kun tuot oletusmäärityspaketin Exceliin, luodussa työkirjassa on kutakin paketin taulukkoa vastaava laskentataulukko. Yksinkertaistaaksesi tehtäviä voit hyödyntää XML manipulointityökaluja, jotka on sisällytetty Exceliin. Voit käyttää myös Excelin valmiita funktioita tietojen muotoilun auttamiseksi ja tiedon asettamiseksi oikeisiin soluihin. Lisää esimerkiksi tyhjä laskentataulukko ja kopioi vanhat tiedot siihen. Tee sitten Excel-kaava määrittämään muunnostyökirjan tiedot viedyn laskentataulukon kenttien ja vanhojen asiakastietojen välille. Kun olet yhdistänyt kaikki tiedot, kopioi tietoalue taulukon työkirjaan.  

> [!IMPORTANT]  
>  Älä muuta sarakkeita työkirjoissa. Jos niitä on siirretty, muutettu tai poistettu, laskentataulukkoa ei voi tuoda [!INCLUDE[d365fin](includes/d365fin_md.md)]iin.

## <a name="tables-in-the-default-configuration-package"></a>Oletusmäärityspaketin taulukot
Oletusmäärityspaketti tukee seuraavia taulukoita:

-   Maksuehdot
-   Asiakkaan hintaryhmä
-   Toimitusehto
-   Myyjä/Ostaja
-   Sijainti
-   KP-tili
-   Asiakas
-   Toimittaja
-   Vaihtoehto
-   Myynnin tunnistetiedot
-   Myyntirivi
-   Ostojen tunnistetiedot
-   Ostorivi
-   Yleisen päiväkirjan rivi
-   Nimikepäiväkirjan rivi
-   Asiakkaan kirjausryhmä
-   Toimittajan kirjausryhmä
-   Varaston kirjausryhmä
-   Mittayksikkö
-   Ylein. liiketoim. kirjausryhmä
-   Yleinen tuotteen kirjausryhmä
-   Yleiset kirjausasetukset
-   Territorio
-   Nimikeluokka
-   Myyntihinta
-   Ostohinta

## <a name="importing-customer-data"></a>Asiakastietojen tuominen
Kun asiakastiedot on annettu Excelissä, tiedot tuodaan [!INCLUDE[d365fin](includes/d365fin_md.md)]iin. Tiedot tuodaan **Määrityspaketit**-ikkunassa Excel-tiedostosta. Voit myös tarkistaa tässä ikkunassa, että tiedot ovat yhdenmukaiset [!INCLUDE[d365fin](includes/d365fin_md.md)]in kanssa ennen paketin käyttöä.

## <a name="see-also"></a>Katso myös
[Liiketoimintatietojen tuominen muista rahoitusjärjestelmistä](upload-data.md)  
[QuickBooks-tietojen siirto](ui-extensions-quickbooks-data-migration.md)  
[Dynamics GP -tietojen siirto](ui-extensions-dynamicsgp-data-migration.md)

