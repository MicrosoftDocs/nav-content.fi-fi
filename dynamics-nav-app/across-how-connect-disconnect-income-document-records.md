---
title: Saapuvien asiakirjojen luominen asiakirjoista
description: "Voit luoda tietueita saapuvista asiakirjoista, kuten sähköisistä laskuista, ja hallita OCR-tehtäviä, sähköistä kaupankäyntiä ja asiakirjojen vaihtopalvelua."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: electronic document, e-invoice, incoming document, OCR, ecommerce, document exchange, import invoice
ms.date: 06/02/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: fd8eba03f98d4d667a25639c1c958edf6936b0cb
ms.contentlocale: fi-fi
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-create-incoming-document-records-directly-from-documents-and-entries"></a>Saapuvien asiakirjatietueiden luominen suoraan asiakirjoista ja tapahtumista
Voit tallentaa ulkoisia liiketoiminta-asiakirjoja [!INCLUDE[d365fin](includes/d365fin_md.md)]iin liittämällä asiakirjatiedostoja soveltuviin saapuviin asiakirjatietueisiin. Vaikka asiakirja (kuten ostolasku) ei olisi ollut alun pitäen saapuva asiakirjatietue, voit silti luoda ja yhdistää siihen saapuvan asiakirjatietueen myöhemmin. Voit myös liittää saapuvia asiakirjatiedostoja kirjattuihin osto- ja myyntiasiakirjoihin sekä toimittaja-, asiakas- ja pääkirjanpidon tapahtumiin käyttämällä **Saapuvat asiakirjatiedostot** -tietoruutua esimerkiksi **Kirjatut ostolaskut**- ja **Toimittajatapahtumat**-ikkunassa.

**Tilikartta**- ja **Pääkirjanpidon tapahtumat** -ikkunan hakutoiminnon avulla voit etsiä pääkirjanpidon tapahtumia kirjatuille osto- ja myyntiasiakirjoille, joilla ei ole saapuvia asiakirjatietueita. Tämän jälkeen voit keskitetysti muodostaa yhteyden olemassa oleviin tietueisiin tai luoda uusia tietueita ja niihin liittyviä asiakirjatiedostoja. Lisätietoja on kohdassa [Toimintaohje: Sellaisten kirjattujen asiakirjojen etsiminen, joilla ei ole saapuvia asiakirjatietueita](across-how-find-posted-documents-without-income-document-records.md).

Seuraavassa kuvataan, kuinka voit liittää tiedoston olemassa olevaan ostolaskuun, jota ei ole luotu saapuvasta asiakirjatietueesta. Lisäksi kuvataan, kuinka voit liittää tiedoston toimittajatapahtumaan. Tiedoston liittäminen kirjattuihin osto- tai myyntiasiakirjoihin toimii vastaavalla tavalla.

## <a name="to-create-and-connect-an-incoming-document-record-from-a-purchase-invoice"></a>Saapuvan asiakirjatietueen luominen ja yhdistäminen ostolaskusta
1. Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, syötä **Ostolaskut** ja valitse sitten aiheeseen liittyvä linkki.
2. Valitse sen ostolaskun rivi, johon haluat liittää tiedoston, ja valitse sitten **Luo saapuva asiakirja tiedostosta** -toiminto.
3. Vaihtoehtoisesti voit valita sen ostolaskun rivin, johon haluat liittää tiedoston, ja valita sitten **Liitä tiedosto**-toiminnon.
4. Valitse **Lisää tiedosto** -ikkunassa tiedosto, joka vastaa kyseistä saapuvaa asiakirjaa, ja valitse sitten **Avaa**.

## <a name="to-create-and-connect-an-incoming-document-record-from-a-vendor-ledger-entry"></a>Saapuvan asiakirjatietueen luominen ja yhdistäminen toimittajatapahtumasta
1. Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, syötä **Toimittajatapahtumat** ja valitse sitten aiheeseen liittyvä linkki.
2. Valitse sen toimittajatapahtuman rivi, johon haluat liittää tiedoston, ja valitse sitten **Luo saapuva asiakirja tiedostosta** -toiminto.
3. Vaihtoehtoisesti voit valita sen toimittajatapahtuman rivin, johon haluat liittää tiedoston, ja valita sitten **Liitä tiedosto**-toiminnon.
4. Valitse **Lisää tiedosto** -ikkunassa tiedosto, joka vastaa kyseistä saapuvaa asiakirjaa, ja valitse sitten **Avaa**.

## <a name="to-remove-a-connection-from-an-incoming-document-record-to-a-posted-document"></a>Saapuvan asiakirjan tietueen ja kirjatun asiakirjan yhteyden poistaminen
Voit poistaa liitetiedostot kirjaamattomista asiakirjoista milloin tahansa poistamalla saapuvan asiakirjan tietueen. Jos asiakirja on kirjattu, liitos saapuvan asiakirjan tietueeseen on poistettava ensin.

1. Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, syötä **Saapuvat asiakirjat** ja valitse sitten aiheeseen liittyvä linkki.
2. Valitse sen saapuvan asiakirjatietueen rivi, joka on liitetty poistettavaan kirjattuun asiakirjaan, ja valitse sitten **Poista viite tietueeseen** -toiminto.

Yhteys kirjattuun asiakirjaan poistetaan. Voit nyt liittää toisen saapuvan asiakirjatietueen kirjattuun asiakirjaan tässä ohjeaiheessa kuvatulla tavalla.

## <a name="see-also"></a>Katso myös
[Saapuvien asiakirjojen käsitteleminen](across-process-income-documents.md)  
[Saapuvat asiakirjat](across-income-documents.md)  
[Osto](purchasing-manage-purchasing.md)  
[[!INCLUDE[d365fin](includes/d365fin_md.md)] -ohjelman käyttäminen](ui-work-product.md)

