---
title: "Liitteettömien asiakirjojen etsiminen"
Description: "Voit etsiä kirjanpitotapahtumia kirjatuille myynti- ja ostoasiakirjoille, joilla ei ole saapuvia sähköisiä asiakirjoja, kuten tuotuja laskuja."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: electronic document, e-invoice, incoming document, OCR, ecommerce, document exchange, import invoice
ms.date: 06/02/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 515026b4da842afeda1759f50313dc26bcfd3350
ms.contentlocale: fi-fi
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-find-posted-documents-without-incoming-document-records"></a>Toimintaohje: Sellaisten kirjattujen asiakirjojen etsiminen, joilla ei ole saapuvia asiakirjatietueita
**Tilikartta**- ja **Pääkirjanpidon tapahtumat** -ikkunan hakutoiminnon avulla voit etsiä pääkirjanpidon tapahtumia kirjatuille osto- ja myyntiasiakirjoille, joilla ei ole saapuvia asiakirjatietueita. Tämän jälkeen voit keskitetysti muodostaa yhteyden olemassa oleviin tietueisiin tai luoda uusia tietueita ja niihin liittyviä asiakirjatiedostoja.

## <a name="to-find-posted-documents-without-incoming-document-records"></a>Sellaisten kirjattujen asiakirjojen etsiminen, joilla ei ole saapuvia asiakirjatietueita
1. Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, syötä **Tilikartta** ja valitse sitten aiheeseen liittyvä linkki.
2. Valitse pääkirjanpidon tapahtumien KP-tilin rivi, kun haluat tarkastella kyseisen rivin kirjattuja osto- ja myyntiasiakirjoja, joilla ei ole saapuvia asiakirjatietueita. Valitse sitten **Kirjatut asiakirjat ilman saapuvaa asiakirjaa** -toiminto.
3. Vaihtoehtoisesti voit valita **Tapahtumakirjaukset**-toiminnon.
4. Valitse **Pääkirjanpidon tapahtumat** -ikkunassa **Kirjatut asiakirjat ilman saapuvaa asiakirjaa** -toiminto.

Avautuvassa **Kirjatut asiakirjat ilman saapuvaa asiakirjaa** -ikkunassa näkyvät kirjatut osto- ja myyntiasiakirjat, joilla ei ole saapuvia asiakirjatietueita. Ikkunan tiedot koskevat määrittämäsi KP-tilin pääkirjanpidon tapahtumia. Ikkunassa näkyy enintään 1 000 riviä. Oletusarvon mukaan **Pvm-suodatus**-kentässä on suodatin, joka rajoittaa rivit tapahtumiin, joiden kirjauspäivämäärät ulottuvat tilikauden alusta käsittelypäivämäärään.

## <a name="to-connect-found-documents-to-existing-incoming-document-records"></a>Löydettyjen asiakirjojen yhdistäminen olemassa oleviin saapuviin asiakirjatietueisiin
1. Valitse **Kirjatut asiakirjat ilman saapuvaa asiakirjaa** -ikkunassa rivi kirjatulle asiakirjalle, jonka haluat yhdistää olemassa olevaan saapuvaan asiakirjatietueeseen. Valitse sitten **Valitse saapuva asiakirja** -toiminto.
2. Valitse **Saapuvat asiakirjat** -ikkunassa saapuva asiakirjatietue, jonka haluat yhdistää löydettyyn kirjattuun asiakirjaan ja valitse sitten **OK**-painike.
3. Valittu saapuva asiakirjatietue on nyt yhdistetty **Kirjatut asiakirjat ilman saapuvaa asiakirjaa** -ikkunassa kirjattuun asiakirjaan, kuten **Saapuvat asiakirjatiedostot** -tietoruudusta voidaan nähdä.

Jos **Saapuvat asiakirjat** -ikkunassa ei ole asiaankuuluvaa saapuvaa asiakirjatietuetta, voit luoda sen. Lisätietoja on kohdassa [Toimintaohje: Saapuvien asiakirjatietueiden luominen](across-how-create-income-document-records.md).

## <a name="see-also"></a>Katso myös
[Saapuvien asiakirjojen käsitteleminen](across-process-income-documents.md)  
[Saapuvat asiakirjat](across-income-documents.md)  
[Osto](purchasing-manage-purchasing.md)  
[[!INCLUDE[d365fin](includes/d365fin_md.md)] -ohjelman käyttäminen](ui-work-product.md)

