---
title: "Ehdotettujen kenttien arvojen määrittäminen"
description: "Voit välttää manuaaliset laskutoimitukset sekä suorittaa tehtävät nopeasti ja tarkasti määrittämällä tietojen antamisen automaattisen, jolloin Dynamics NAV täyttää valitut kentät."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.date: 08/15/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 7c68019ff32d6fbe700975b0897dff9474da7bc1
ms.contentlocale: fi-fi
ms.lasthandoff: 10/16/2017

---
# <a name="letting-included365finincludesd365finmdmd-suggest-values"></a>[!INCLUDE[d365fin](includes/d365fin_md.md)] voi ehdottaa arvoja
[!INCLUDE[d365fin](includes/d365fin_md.md)] voi auttaa tehtävien suorittamisessa nopeammin ja tarkemmin täyttämällä kentät tai rivit tiedoilla, jotka muussa tapauksessa olisi laskettava ja annettava manuaalisesti. Vaikka automaattinen tietojen syöte on aina oikea, voit halutessasi muuttaa arvoja myöhemmin.

Toiminto, joka syöttää arvot puolestasi, sisältyy yleensä tehtäviin, joissa syötetään suuria määriä tapahtumatietoja. Niissä halutaan välttää virheet ja säästää aikaa. Tämä ohjeaihe sisältää näiden toimintojen valikoiman. [!INCLUDE[d365fin](includes/d365fin_md.md)]in tulevat päivitykset sisältävät uusia osia.

## <a name="the-suggest-balancing-amount-check-box-in-the-general-journal-batches-window"></a>**Ehdota vastasummaa** -valintaruutu **Yleisen päiväkirjan erät** -ikkunassa
Kun esimerkiksi syötät yleisen päiväkirjan riveille useita kuluja, jotka on kirjattava samalle pankkitilille, kulun uuden päiväkirjan rivin syöttämisen yhteydessä pankkitilin rivin **Summa**-kenttään täytetään automaattisesti kulut täsmäyttävä summa. Lisätietoja yleisten päiväkirjojen käsittelemisestä on ohjeaiheessa [Yleisten päiväkirjojen käyttäminen](ui-work-general-journals.md).

### <a name="to-have-the-amount-field-on-balancing-general-journal-lines-filled-automatically"></a>**Summa**-kentän täyttäminen automaattisesti yleisen päiväkirjan rivien täsmäyttämistä varten
1. Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, syötä **Yleiset päiväkirjat** ja valitse sitten aiheeseen liittyvä linkki.
2. Valitse haluamasi yleisen päiväkirjan erän rivillä **Ehdota vastasummaa** -valintaruutu.
3. Avaa yleinen päiväkirja ja jatka rekisteröitymiseen. Kirjaa tapahtumia edellä esiteltyjen toimintojen avulla, kun haluat, että kentän arvo syötetään automaattisesti.       

Lisätietoja henkilökohtaisen yleisen päiväkirjan erän määrittämisestä esimerkiksi kulujen käsittelemistä varten on ohjeaiheessa [Yleisten päiväkirjojen käyttäminen](ui-work-general-journals.md).

## <a name="the-automatically-fill-date-received-field-in-the-payment-registration-window"></a>**Täytä vastaanottopäivämäärä automaattisesti** -kenttä **Maksurekisteröinti**-ikkunassa
**Maksurekisteröinti**-ikkuna näyttää avoimet saapuvat maksut riveinä, jotka edustavat myyntiasiakirjoja, joiden summa on erääntynyt maksettavaksi. Lisätietoja asiakkaan maksujen kohdistamisesta on kohdassa [Toimintaohje: Asiakasmaksujen täsmäyttäminen manuaalisesti maksamattomien myyntiasiakirjojen luettelosta](receivables-how-reconcile-customer-payments-list-unpaid-sales-documents.md)

Tärkein ikkunassa tehtävät toiminnot ovat **Maksu suoritettu** -valintaruudun valitseminen ja **Vastaanottopvm**-kentän täyttäminen. Voit määrittää [!INCLUDE[d365fin](includes/d365fin_md.md)]in siten, että se lisää päivämäärän automaattisesti **Vastaanottopvm**-kenttään silloin, kun valitset **Maksu suoritettu** -valintaruudun.

### <a name="to-have-the-date-received-field-in-the-payment-registration-window-filled-automatically"></a>**Maksurekisteröinti**-ikkunan **Täytä vastaanottopäivämäärä automaattisesti** -kentän automaattinen täyttäminen
1. Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, kirjoita **Maksurekisteröinnin asetukset** ja valitse sitten aiheeseen liittyvä linkki.
2. Valitse **Täytä vastaanottopäivämäärä automaattisesti** -valintaruutu.
3. Avaa **Maksurekisteröinti**-ikkuna ja jatka saapuvien asiakkaiden maksujen käsittelyyn edellä esiteltyjen toimintojen avulla, kun haluat, että kentän arvo syötetään automaattisesti.

## <a name="see-also"></a>Katso myös
[[!INCLUDE[d365fin](includes/d365fin_md.md)] -ohjelman käyttäminen](ui-work-product.md)  
[Rahoitus](finance.md)

