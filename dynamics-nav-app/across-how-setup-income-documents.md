---
title: "Toimintaohje: Saapuvien asiakirjojen määrittäminen"
author: SorenGP
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 2bce97c76876c86a576ec6a281a306a46881027c
ms.contentlocale: fi-fi
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-set-up-incoming-documents"></a>Toimintaohje: Saapuvien asiakirjojen määrittäminen
Jos luot pääkirjan rivejä saapuvista asiakirjatietueista, **Saapuvien asiakirjojen asetukset** -ikkunassa on määritettävä käytettävä päiväkirjan malli sekä erä.

Jos haluat, etteivät käyttäjät voi luoda laskuja tai yleisen päiväkirjan rivejä saapuvista asiakirjatietueista ennen asiakirjojen hyväksymistä, määritä hyväksyjät **Saapuvan asiakirjan hyväksyjät** -ikkunassa.

Kun haluat muuntaa PDF- ja kuvatiedostoja sähköisiksi asiakirjoiksi, jotka voi muuntaa esimerkiksi ostolaskuiksi Dynamics NAV -ohjelmassa, määritä ensin OCR-ominaisuus ja ota palvelu käyttöön.

Kun Saapuvat asiakirjat -ominaisuus on määritetty, voit käyttää erilaisia toimintoja, joilla voit tarkistaa kulutositteita, hallita OCR-tehtäviä ja muuntaa saapuvia asiakirjatiedostoja manuaalisesti tai automaattisesti sekä siirtää niistä tietoja asiakirjoihin tai kirjanpitoriveille. Ulkoisia tiedostoja voi liittää missä tahansa prosessin vaiheessa myös kirjattuihin asiakirjoihin ja muodostuviin toimittaja-, asiakas- ja pääkirjamerkintöihin. Lisätietoja on kohdassa [Toimintaohje: Saapuvien asiakirjojen käsitteleminen](across-process-income-documents.md).

## <a name="to-set-up-the-incoming-documents-feature"></a>Saapuvat asiakirjat -ominaisuuden määrittäminen
1. Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Saapuvien asiakirjojen asetukset** ja valitse sitten aiheeseen liittyvä linkki.
2. Täytä tarvittavat kentät. Lue kentän lyhyt kuvaus valitsemalla kenttä tai siirry lisätietoihin valitsemalla linkki.

## <a name="to-set-up-approvers-of-incoming-document-records"></a>Saapuvien asiakirjatietueiden hyväksyjien määrittäminen
1. Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Saapuvien asiakirjojen asetukset** ja valitse sitten aiheeseen liittyvä linkki.  
2. Valitse **Saapuvien asiakirjojen asetukset** -ikkunassa **Hyväksyjät**-toiminto.

    **Saapuvan asiakirjan hyväksyjät** -ikkunassa näkyvät kaikki Dynamics NAV -ohjelmaan rekisteröityneet käyttäjät.  
3. Valitse vähintään yksi käyttäjä, joka voi hyväksyä saapuvan asiakirjan ennen liittyvän asiakirjan tai päiväkirjarivin luomista.

Kun hyväksyjät on määritetty **Saapuvien asiakirjojen hyväksyjät** -ikkunassa, vain kyseiset käyttäjät voivat hyväksyä saapuvan asiakirjan, jos **Saapuvien asiakirjojen asetukset** -ikkunan **Edellytä hyväksyntää luomista varten** -valintaruutu on valittu.

**Huomautus**: Nämä hyväksynnän asetukset eivät liity hyväksymistyönkulkuihin. Lisätietoja on kohdassa [Toimintaohje: Hyväksyntätyönkulkujen käyttäminen](across-how-use-approval-workflows.md).

## <a name="to-set-up-an-ocr-service"></a>OCR-palvelun määrittäminen
1. Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **OCR-palvelun asetukset** ja valitse sitten aiheeseen liittyvä linkki.
2. Täytä tarvittavat kentät. Lue kentän lyhyt kuvaus valitsemalla kenttä tai siirry lisätietoihin valitsemalla linkki.


## <a name="to-encrypt-your-login-information"></a>Kirjautumistietojen salaaminen
Suosittelemme, että suojaat **OCR-palvelun asetukset** -ikkunaan kirjoittamasi kirjautumistiedot. Palvelimen tiedot voi salata luomalla uusia salausavaimia tai tuomalla olemassa olevia salausavaimia, jotka otetaan käyttöön tietokantayhteyden muodostavassa palvelininstanssissa.

1. Valitse **OCR-palvelun asetukset** -ikkunassa **Salauksen hallinta** -toiminto.
2. Ota tietojen salaus käyttöön **Tietojen salauksen hallinta** -ikkunassa.

## <a name="see-also"></a>Katso myös  
[Saapuvien asiakirjojen käsitteleminen](across-process-income-documents.md)  
[Saapuvat asiakirjat](across-income-documents.md)  
[Ostojen hallinta](purchasing-manage-purchasing.md)  
[Dynamics NAV -ohjelman käyttäminen](ui-work-product.md)

