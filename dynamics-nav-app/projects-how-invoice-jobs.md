---
title: Projektin laskuttaminen luomalla projektimyynnin lasku
description: "Ohjeaiheessa kerrotaan, miten projektin kustannukset laskutetaan asiakkailta projektin edetessä."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: project invoice
ms.date: 06/06/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 74b9209216f6e62dfc9519b288adca785cdb8100
ms.contentlocale: fi-fi
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-invoice-jobs"></a>Toimintaohje: Projektien laskuttaminen
Projektin aikana voi kertyä projektin kustannuksia resurssien käytöstä, materiaaleista ja projektiin liittyvistä ostoista. Projektin edetessä nämä tapahtumat kirjataan projektipäiväkirjaan. On tärkeää, että kaikki kustannukset kirjataan projektipäiväkirjaan ennen asiakkaan laskuttamista.

Voit laskuttaa koko projektin **Projektitehtävärivit**-ikkunassa tai laskuttaa vain valitut laskutettavat rivit **Suunnittelurivit**-ikkunassa. Laskutuksen voi tehdä joko projektin valmistumisen jälkeen tai tietyin laskutusaikataulun mukaisin väliajoin projektin aikana.

> [!NOTE]  
>   Jos valitset projektiin liittyvien ostojen ostoasiakirjojen **Projektin rivityyppi** -kentässä **Laskutettava**, projektin suunnittelurivit, jotka ovat valmiita asiakkaalta laskutusta varten, luodaan. Lisätietoja on kohdassa [Toimintaohje: Projektin tarvikkeiden hallinta](projects-how-manage-project-supplies.md).

## <a name="to-create-and-post-a-job-sales-invoice"></a>Voit luoda projektin myyntilaskun seuraavasti
Voit luoda asiakkaalle laskun projektista tai vähintään yhdestä projektitehtävästä, kun laskutettava työ on valmis tai kun laskutusaikatauluun perustuva laskutuspäivämäärä on saavutettu.

Voit laskuttaa **Projektit**-ikkunassa asiakasta valitsemalla projektin ja valitsemalla sitten **Luo projektin myyntilasku** -toiminnon. Seuraavassa kerrotaan, miten eräajoa käytetään useiden projektien laskuttamisessa.  

1. Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, kirjoitta **Luo projektin myyntilasku** ja valitse sitten aiheeseen liittyvä linkki.  
2. Täytä tarvittavat kentät. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]
3. Määritä suodattimet, jos haluat rajata erätyön käsittelemien projektien määrää.
4. Luo laskut valitsemalla **OK**.  

## <a name="to-create-multiple-job-sales-invoices-from-job-planning-lines"></a>Useiden projektin myyntilaskujen luominen projektin suunnitteluriveistä
Voit luoda laskun projektin suunnitteluriveiltä ja määrittää samalla nimikkeen määrän, resurssin tai KP-tilin, jonka haluat laskuttaa.

1. Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, kirjoita **Projektit** ja valitse sitten aiheeseen liittyvä linkki.
2. Avaa asianmukainen projekti.
3. Valitse projektitehtävä, jonka **Projektitehtävätyyppi**-kentän arvo on **Kirjaus**. Valitse sitten **Projektin suunnittelurivit** -toiminto.  
4. Annan projektin suunnittelurivin **Laskuun siirrettävä määrä** -kentässä nimikkeen, resurssin tai pääkirjanpidon tilin tyyppi, jonka haluat laskuttaa.  
5. Valitse **Luo myyntilasku** -toiminto.
6. Syötä **Luo projektin myyntilasku** -ikkunaan kirjauspäivämäärä. Määritä, haluatko luoda uuden laskun vai kohdistaa tämän laskun aiemmin luotuun laskuun.
7. Valitse **OK**-painike.  

    Projektin suunnittelurivin **Laskuun siirretty määrä** -kentässä näkyy määrä.
8. Valitse **Projektin suunnittelurivit** -ikkunassa **Myyntilaskut/hyvityslaskut**-toiminto.

    Avautuvassa **Myyntilasku**-ikkunassa näkyy laskuun siirretty määrä.  
9. Tee tarvittavat muutokset ja valitse **Kirjaa**-toiminto.

> [!NOTE]  
>   Projektiin liittyvän myyntihyvityslaskun luominen, tarkistaminen ja kirjaaminen tapahtuu vastaavalla tavalla.

## <a name="to-calculate-and-post-job-completion-entries"></a>Projektin valmistumistapahtumien laskeminen ja kirjaaminen
Kun olet saanut kaikki projektin toimenpiteet, kuten käytön kirjauksen ja laskutuksen, valmiiksi, projekti on päivitettävä **tilaan** **Valmis**. Tämän jälkeen mahdollinen kirjanpitoon kirjattu KET peruuntuu.

1. Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, kirjoita **Projektit** ja valitse sitten aiheeseen liittyvä linkki.  
2. Valitse avoin projekti ja valitse sitten **Muokkaa**-toiminto.
3. Valitse **Tila**-kentässä **Valmis**.
4. Laske ja kirjaa KET ohjattujen vaiheiden avulla. Vaihtoehtoisesti voit tehdä toiminnot manuaalisesti vaiheiden 5 ja 6 mukaisesti.  
5. Valitse **Laske KET** -toiminto.
6. Täytä **Laske projektin KET** -ikkunassa tarvittavat kentät.  

     Erätyön luomien projektin KET-tapahtumien vieressä on nyt valintamerkki **Projekti valmis** -kentässä. Valintamerkki osoittaa, että kyseessä ovat valmistumistapahtumat.  
7. Valitse **Kirjaa projektin KET kirjanpitoon** -toiminto.
8. Täytä **Kirjaa projektin KET kirjanpitoon** -ikkunassa tarvittavat kentät.  

     Erätyön luomien projektin pääkirjanpidon KET-tapahtumien vieressä on nyt valintamerkki **Projekti valmis** -kentässä. Valintamerkki osoittaa, että kyseessä ovat valmistumistapahtumat.

## <a name="see-also"></a>Katso myös
[Projektien hallinta](projects-manage-projects.md)  
[Rahoitus](finance.md)  
[Osto](purchasing-manage-purchasing.md)         
[Myynti](sales-manage-sales.md)      
[[!INCLUDE[d365fin](includes/d365fin_md.md)] -ohjelman käyttäminen](ui-work-product.md)  

