---
title: Kokoonpanon kirjauksen kumoaminen
description: "Voit joutua joskus kumoamaan kirjatun kokoonpanotilauksen, jos esimerkiksi tilaukseen kirjattiin virheitä, jotka on korjattava, tai jos kyseistä kirjausta ei olisi pitänyt tehdä lainkaan ja se on palautettava."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 08/15/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 3ba93dd182aa1591f5d24398d4b749942d38bb4b
ms.contentlocale: fi-fi
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-undo-assembly-posting"></a>Kokoonpanon kirjauksen kumoaminen
Voit joutua joskus kumoamaan kirjatun kokoonpanotilauksen, jos esimerkiksi tilaukseen kirjattiin virheitä, jotka on korjattava, tai jos kyseistä kirjausta ei olisi pitänyt tehdä lainkaan ja se on palautettava.

Kun kumoat kirjatun kokoonpanotilauksen, joukko korjaavia nimiketapahtumia luodaan alkuperäisten tapahtumien palauttamiseksi. Kokoonpanonimikkeen kukin positiivinen kulutustapahtuma kumotaan negatiivisella kulutustapahtumalla. Kokoonpano-osan kukin negatiivinen kulutustapahtuma kumotaan positiivisella kulutustapahtumalla. Kiinteiden kustannusten kohdistaminen luodaan korjaavien ja alkuperäisten tapahtumien välille automaattisesti. Näin varmistetaan todellisten kustannusten peruuttaminen.  

Kun kumoat täysin kirjatun kokoonpanotilauksen, voit valita kokoonpanotilauksen uudelleen luomisen sen alkuperäisessä tilassa, esimerkiksi korjausten tekemiseksi ennen uudelleenkirjausta. Vaihtoehtoisesti voit olla luomatta uudelleen kokoonpanotilausta.  

Kun kumoat osittain kirjatun kokoonpanojärjestyksen, kaikki vaikutetut määrä-kentät, kuten **Kokoonpantu määrä**, **Kulutettu määrä** ja **Jäljellä oleva määrä** -kentät palautetaan arvoihin, jotka niissä oli ennen kyseistä kirjausta.  

Kokoonpanotilausten uudelleen luomiseksi tai palauttamiseksi seuraavia edellytyksiä tulee soveltaa kokoonpanon nimikkeeseen, joka oli alkuperäisen kirjauksen tuloste:  

-   Sen on oltava vielä varastossa, eli se ei saa olla myyty eikä muuten kulutettu lähtevissä tapahtumissa.  
-   Se ei saa olla varattu.  
-   Se on oltava varastopaikassa, johon se on alun perin sijoitettu.  

Lisäksi olemassa olevia kokoonpanotilauksista voi palauttaa vain, jos alkuperäisen kokoonpanotilauksen rivien määrää ja järjestystä ei ole muutettu.  

> [!TIP]  
>  Ratkaistaksesi ristiriitoja rivimuutosten vuoksi, voit palauttaa manuaalisesti kyseiset rivimuutokset kumoamalla liittyvät kirjatut kokoonpanotilaukset. Voit myös kirjata kokoonpanotilauksen täysin ja valita sen sitten luodaksesi sen uudelleen, kun  kumoat kirjauksen.  

Seuraavassa ohjeessa neuvotaan, miten perutaan jo kirjattuja kokoonpanotilauksia, joiden nimikkeet on koottu varastoon. Jos haluat peruuttaa kirjatut kokoonpanotilaukset, joissa nimikkeet on koottu myyntitilausta varten, käytä kirjatun toimituksen **Peruuta toimitus** -funktiota kirjatun kokoonpanotilauksen vapauttamiseksi. Lisätietoja on kohdassa [Toimintaohje: Kirjauksien peruuttaminen](finance-how-reverse-journal-posting.md). Kirjatun kokoonpanotilauksen peruuttaminen tapahtuu sitten automaattisesti samalla tavalla, kuin tässä ohjeaiheessa on kuvattu.  

## <a name="to-undo-posting-of-an-assembly-order"></a>Kumoa kokoonpanotilauksen kirjaus  
1.  Voit kumota kirjatun kokoonpanotilauksen osittain tai kokonaan valitsemalla ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvakkeen, kirjoittamalla **Kirjatut kokoonpanotilaukset** ja valitsemalla liittyvän linkin.  

    Avautuvassa **Kirjatut kokoonpanotilaukset** -ikkunassa esitetään yksi tai useampi kirjattu kokoonpanotilaus, joka on kirjattu kyseisestä kokoonpanotilauksesta. Jokainen osittainen kirjaus luo erillisen kirjatun kokoonpanotilauksen.  
2.  Avaa kumottava kirjattu kokoonpanotilaus ja valitse sitten **Kumoa kokoonpano** -toiminto.  

    Jos kirjattu kokoonpanotilaus, jonka haluat kumota, liittyy kokonaan kirjattuun poistettuun kokoonpanotilaukseen, voit luoda sen uudelleen uudelleenkäsittelyä varten.  
3.  Jos haluat luoda kokoonpanotilauksen uudelleen, valitse **Kyllä**-painike. Kumoa kirjaus luomatta uudestaan liittyvää kokoonpanotilausta valitsemalla **ei** -painike.  

Kokoonpanotilauksen **Peruutettu**-otsikkokentän arvoksi tulee **Kyllä**. Kokoonpanotilauksen kirjaus on nyt palautettu, voit jatkaa koko tilauksen käsittelyä jos loit sen uudelleen, tai avata alkuperäiseen tilaan palautetun tilauksen.  

> [!NOTE]  
>  Palauttaaksesi määrät kokoonpanotilauksen useista osittaisista kirjauksista sinun täytyy kumota kaikki kyseessä olevat kirjatut kokoonpanotilaukset seuraamalla vaiheita 1-3 kunkin kirjatun kokoonpanotilauksen yläpuolella.  

## <a name="see-also"></a>Katso myös  
[Kokoonpanon hallinta](assembly-assemble-items.md)  
[Toimintaohje: Kirjausten peruuttaminen](finance-how-reverse-journal-posting.md)  
[Toimintaohje: myynnin palautuksen tai peruutuksen käsittely](sales-how-process-sales-returns-cancellations.md)    
[Toimintaohje: Tuoterakenteen käyttäminen](inventory-how-work-BOMs.md)  
[Vaihto-omaisuus](inventory-manage-inventory.md)  
[Rakennetiedot: Fyysisen varaston hallinta](design-details-warehouse-management.md)  
[[!INCLUDE[d365fin](includes/d365fin_md.md)] -ohjelman käyttäminen](ui-work-product.md)

