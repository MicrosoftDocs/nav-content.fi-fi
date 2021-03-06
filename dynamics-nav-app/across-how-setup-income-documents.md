---
title: "Määritä saapuvat asiakirjat"
description: "Voit käyttää saapuvien asiakirjojen toimintoa sähköisten asiakirjojen luomiseen, OCR-tehtävien hallintaan, laskujen tuontiin ja kuvatiedostojen muuntamiseen."
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
ms.openlocfilehash: 80c57f6a332ace58941929811e3f3a9b1f156028
ms.contentlocale: fi-fi
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-set-up-incoming-documents"></a>Toimintaohje: Saapuvien asiakirjojen määrittäminen
Jos luot pääkirjan rivejä saapuvista asiakirjatietueista, **Saapuvien asiakirjojen asetukset** -ikkunassa on määritettävä käytettävä päiväkirjan malli sekä erä.

Jos haluat, etteivät käyttäjät voi luoda laskuja tai yleisen päiväkirjan rivejä saapuvista asiakirjatietueista ennen asiakirjojen hyväksymistä, määritä hyväksyjät **Saapuvan asiakirjan hyväksyjät** -ikkunassa.

Jos haluat muuntaa PDF- ja kuvatiedostoja sähköisiksi asiakirjoiksi, jotka voi muuntaa esimerkiksi ostolaskuiksi [!INCLUDE[d365fin](includes/d365fin_md.md)]issa, määritä ensin OCR-ominaisuus ja ota palvelu käyttöön.

Kun Saapuvat asiakirjat -ominaisuus on määritetty, voit käyttää erilaisia toimintoja, joilla voit tarkistaa kulutositteita, hallita OCR-tehtäviä ja muuntaa saapuvia asiakirjatiedostoja manuaalisesti tai automaattisesti sekä siirtää niistä tietoja asiakirjoihin tai kirjanpitoriveille. Ulkoisia tiedostoja voi liittää missä tahansa prosessin vaiheessa myös kirjattuihin asiakirjoihin ja muodostuviin toimittaja-, asiakas- ja pääkirjamerkintöihin. Lisätietoja on kohdassa [Saapuvien asiakirjojen käsitteleminen](across-process-income-documents.md).

## <a name="to-set-up-the-incoming-documents-feature"></a>Saapuvat asiakirjat -ominaisuuden määrittäminen
1. Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, syötä **Saapuvien asiakirjojen asetukset** ja valitse sitten aiheeseen liittyvä linkki.
2. Täytä tarvittavat kentät. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]

## <a name="to-set-up-approvers-of-incoming-document-records"></a>Saapuvien asiakirjatietueiden hyväksyjien määrittäminen
1. Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, syötä **Saapuvien asiakirjojen asetukset** ja valitse sitten aiheeseen liittyvä linkki.  
2. Valitse **Saapuvien asiakirjojen asetukset** -ikkunassa **Hyväksyjät**-toiminto.

    Kaikki [!INCLUDE[d365fin](includes/d365fin_md.md)]iin rekisteröityneet käyttäjät näkyvät **Saapuvan asiakirjan hyväksyjät** -ikkunassa.  
3. Valitse vähintään yksi käyttäjä, joka voi hyväksyä saapuvan asiakirjan ennen liittyvän asiakirjan tai päiväkirjarivin luomista.

Kun hyväksyjät on määritetty **Saapuvien asiakirjojen hyväksyjät** -ikkunassa, vain kyseiset käyttäjät voivat hyväksyä saapuvan asiakirjan, jos **Saapuvien asiakirjojen asetukset** -ikkunan **Edellytä hyväksyntää luomista varten** -valintaruutu on valittu.

> [!NOTE]  
>   Nämä hyväksynnän asetukset eivät liity hyväksymistyönkulkuihin. Lisätietoja on kohdassa [Toimintaohje: Hyväksyntätyönkulkujen käyttäminen](across-how-use-approval-workflows.md).

## <a name="to-set-up-an-ocr-service"></a>OCR-palvelun määrittäminen
1. Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, syötä **OCR-palvelun asetukset** ja valitse sitten aiheeseen liittyvä linkki.
2. Täytä tarvittavat kentät. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]

## <a name="to-encrypt-your-login-information"></a>Kirjautumistietojen salaaminen
Suosittelemme, että suojaat **OCR-palvelun asetukset** -ikkunaan kirjoittamasi kirjautumistiedot. Palvelimen tiedot voi salata luomalla uusia salausavaimia tai tuomalla olemassa olevia salausavaimia, jotka otetaan käyttöön tietokantayhteyden muodostavassa palvelininstanssissa.

1. Valitse **OCR-palvelun asetukset** -ikkunassa **Salauksen hallinta** -toiminto.
2. Ota tietojen salaus käyttöön **Tietojen salauksen hallinta** -ikkunassa.

## <a name="see-also"></a>Katso myös
[Saapuvien asiakirjojen käsitteleminen](across-process-income-documents.md)  
[Saapuvat asiakirjat](across-income-documents.md)  
[Osto](purchasing-manage-purchasing.md)  
[[!INCLUDE[d365fin](includes/d365fin_md.md)] -ohjelman käyttäminen](ui-work-product.md)

