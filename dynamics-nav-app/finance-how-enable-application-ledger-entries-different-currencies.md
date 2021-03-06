---
title: Eri valuutoissa olevien tapahtumien kohdistaminen
description: "Jos asiakkaan maksu vastaanotetaan eri valuuttana kuin myytäessä käytetty valuutta, voidaan kirjanpitotapahtumat kohdistaa useana valuuttana."
documentationcenter: 
author: edupont04
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: multiple currencies, payment, reconcile
ms.date: 06/02/2017
ms.author: edupont
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: f323b98472f3e2ef0f28000f8a9140b066206945
ms.contentlocale: fi-fi
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-enable-application-of-ledger-entries-in-different-currencies"></a>Toimintaohje: Tapahtumakirjausten kohdistamisen ottaminen käyttöön eri valuutoissa
Jos ostat toimittajalta yhdessä valuutassa ja maksat maksun toisessa valuutassa, maksu voidaan kohdistaa ostoon.

Ja jos asiakkaalle myydään yhdessä valuutassa ja maksu vastaanotetaan toisessa valuutassa, maksu voidaan kohdistaa myyntilaskuun.

Seuraavassa kuvataan, miten tämä määritetään toimittajatapahtumille **Ostojen ja ostovelkojen asetukset** -ikkunassa. Asetukset tehdään samoin kuin asiakastapahtumille **Myyntien ja myyntisaamisten asetukset** -ikkunassa.

## <a name="to-enable-application-of-vendor-ledger-entries-in-different-currencies"></a>Toimittajatapahtumien kohdistamisen ottaminen käyttöön eri valuutoissa
1. Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, syötä **Ostojen ostovelkojen asetukset** ja valitse sitten aiheeseen liittyvä linkki.
2. Valitse **Valuuttojen välinen kohdistus** -kentässä jokin seuraavista vaihtoehdoista.

| Asetus | Kuvaus |
| --- | --- |
| Ei yhtään |Valuuttojen välistä kohdistusta ei sallita. |
| EMU |EMU-valuuttojen välinen kohdistus sallitaan. |
| Kaikki |Kaikkien valuuttojen välinen kohdistus sallitaan. |

## <a name="to-set-up-gl-accounts-for-currency-application-rounding-differences"></a>KP-tilien määrittäminen valuutan kohdistuksen pyöristyseroille  
Jos eri valuutoissa olevia tapahtumia kohdistetaan, täytyy määrittää KP-tilit, jolle haluat kirjata pyöristyserot.  

> [!NOTE]  
>  Sinun on määritettävä pääkirjanpidon tilit, ennen kuin viimeistelet tehtävän. Lisätietoja on kohdassa [Tietoja pääkirjanpidosta ja tilikartasta](finance-general-ledger.md).

1. Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, kirjoita **Asiakkaan kirjausryhmät** ja valitse sitten aiheeseen liittyvä linkki.  
2. Anna **Debet val. kohd. pyör. tili**- ja **Kredit val. kohd. pyör. tili** -kenttiin asianmukaiset pääkirjanpitotilit, joihin pyöristyserot kirjataan.  
3. Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, kirjoita **Toimittajan kirjausryhmät** ja valitse sitten aiheeseen liittyvä linkki.  
4. Anna **Debet val. kohd. pyör. tili**- ja **Kredit val. kohd. pyör. tili** -kentissä pääkirjanpitotilit, joihin pyöristyserot kirjataan.  

## <a name="see-also"></a>Katso myös
[Ostovelkojen hallinta](payables-manage-payables.md)  
[Myyntisaamisten hallinta](receivables-manage-receivables.md)  
[[!INCLUDE[d365fin](includes/d365fin_md.md)] -ohjelman käyttäminen](ui-work-product.md)

