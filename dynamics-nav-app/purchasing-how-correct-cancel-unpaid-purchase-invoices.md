---
title: Maksamattomien ostolaskujen korjaaminen tai peruuttaminen
description: "Tässä ohjeaiheessa kerrotaan, miten kirjattua lasku korjataan, peruutetaan tai kumotaan ja miten ostohyvityslasku luodaan automaattisesti."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: undo, credit memo, return
ms.date: 08/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 294094f8483f9b51d47ad614b8702b289b9d1862
ms.contentlocale: fi-fi
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-correct-or-cancel-unpaid-purchase-invoices"></a>Ohjeet: Korjaa tai peruuta maksamattomat myyntilaskut
Voit korjata tai peruuttaa maksamattoman ostolaskun. Tästä on hyötyä, jos haluat korjata kirjoitusvirheen tai muuttaa ostoa tilausprosessin alkuvaiheessa.

Jos olet jo maksanut kirjatun ostolaskun tuotteet, et voi korjata tai peruuttaa sitä itse kirjatusta ostolaskusta. Sen sijaan sinun on peruutettava osto luomalla ostohyvityslasku, jota voi tarvittaessa hallinta ostopalautustilauksella. Lisätietoja on kohdassa [Toimintaohje: Ostopalautusten tai -peruutusten käsitteleminen](purchasing-how-process-purchase-returns-cancellations.md).

Valitse **Kirjattu ostolasku** -ikkunassa **Korjaa**- tai **Peruuta**-painike. Kun korjaat tai peruutat kirjatun ostolaskun, korjaavaa ostohyvityslaskua käytetään kaikkiin pääkirjanpidon ja varastotapahtumiin, jotka luotiin, kun alkuperäinen ostolasku kirjattiin. Tämä kumoaa kirjatun ostolaskun kirjanpitotietueissa ja jättää korjaavan kirjatun ostohyvityslaskun kirjausketjua varten. Alla kerrotaan, miten **Korjaa**- ja **Peruuta**-painikkeita käytetään.

## <a name="to-correct-a-posted-purchase-invoice"></a>Kirjatun ostolaskun korjaamiseksi
1. Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, kirjoita **Kirjatut ostolaskut** ja valitse sitten aiheeseen liittyvä linkki.  
2. Valitse kirjattu ostolasku, jonka haluat korjata.  

    > [!NOTE]  
>   Jos **Peruutettu**-valintaruutu on valittuna, et voi korjata kirjattua ostolaskua, koska se on jo korjattu tai peruutettu.
3. Valitse **Kirjattu ostolasku** -ikkunassa **Korjaa**.

    Luodaan samoilla tiedoilla uusi ostolasku, johon voit tehdä korjauksen. Lisätietoja on kohdassa [Toimintaohje: Ostojen kirjaaminen](purchasing-how-record-purchases.md). Alkuperäisen kirjatun ostolaskun **Peruutettu**-kentän arvoksi muutetaan **Kyllä**.

    Ostohyvityslasku luodaan automaattisesti ja kirjataan mitätöimään alun perin kirjattu ostolasku.
4. Valitse **Näytä korjaava hyvityslasku**, kun haluat tarkastella kirjattua ostohyvityslaskua, joka mitätöi alkuperäisen kirjatun ostolaskun.

## <a name="to-cancel-a-posted-purchase-invoice"></a>Kirjatun ostolaskun peruuttamiseksi
1. Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, kirjoita **Kirjatut ostolaskut** ja valitse sitten aiheeseen liittyvä linkki.  
2. Valitse kirjattu ostolasku, jonka haluat peruuttaa.

    > [!NOTE]  
>   Jos **Peruutettu**-valintaruutu on valittuna, et voi peruuttaa kirjattua ostolaskua, koska se on jo peruutettu tai korjattu.
3. Valitse **Kirjattu ostolasku** -ikkunassa **Peruuta**.

    Ostohyvityslasku luodaan automaattisesti ja kirjataan mitätöimään alun perin kirjattu ostolasku. Alkuperäisen kirjatun ostolaskun **Peruutettu**-kentän arvoksi muutetaan **Kyllä**.
4. Valitse **Näytä korjaava hyvityslasku**, kun haluat tarkastella kirjattua ostohyvityslaskua, joka mitätöi alkuperäisen kirjatun ostolaskun.

## <a name="see-also"></a>Katso myös
[Osto](purchasing-manage-purchasing.md)  
[Toimintaohje: Ostojen kirjaus](purchasing-how-record-purchases.md)  
[[!INCLUDE[d365fin](includes/d365fin_md.md)] -ohjelman käyttäminen](ui-work-product.md)

