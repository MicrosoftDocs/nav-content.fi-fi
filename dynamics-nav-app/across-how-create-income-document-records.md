---
title: 'Toimintaohje: Saapuvien asiakirjatietueiden luominen'
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
ms.openlocfilehash: 10ba191b197be8b98b2d5d5ab9ac4bc3baf0d82b
ms.contentlocale: fi-fi
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-create-incoming-document-records"></a>Toimintaohje: Saapuvien asiakirjatietueiden luominen
**Saapuvat asiakirjat** -ikkunassa voit käyttää erilaisia toimintoja, joilla voit tarkistaa kulutositteita, hallita OCR-tehtäviä ja muuntaa saapuvia asiakirjatiedostoja manuaalisesti tai automaattisesti sekä siirtää niistä tietoja asiakirjoihin tai kirjanpitoriveille. Ulkoisia tiedostoja voi liittää missä tahansa prosessin vaiheessa myös kirjattuihin asiakirjoihin ja muodostuviin toimittaja-, asiakas- ja pääkirjamerkintöihin.

Voit tallentaa ulkoisen asiakirjan Dynamics NAV -ohjelmassa, kun luot ensin saapuvan asiakirjatietueen tai teet sen valmiiksi. Voit tehdä tämän manuaalisesti tai ottaa valokuvan ulkoisesta asiakirjasta ja luoda sitten saapuva asiakirjatietue, johon on liitetty kuvatiedosto.

Ennen kuin voit käyttää Saapuvat asiakirjat -ominaisuutta, sinun on tehtävä tarvittavat asetukset. Lisätietoja on kohdassa [Toimintaohje: Saapuvien asiakirjojen määrittäminen](across-how-setup-income-documents.md).

## <a name="to-approve-or-reject-an-incoming-document"></a>Saapuvan asiakirjan hyväksyminen tai hylkääminen
Jos haluat, että käyttäjät voivat luoda laskuja tai yleisen päiväkirjan rivejä saapuvista asiakirjatietueista vasta, kun ne on hyväksytty, voit määrittää hyväksyjät, joiden on hyväksyttävä tietueet ennen niiden käsittelyä.

1. Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Saapuvat asiakirjat** ja valitse sitten aiheeseen liittyvä linkki.
2. Valitse rivi, jolla hyväksyttävä tai hylättävä asiakirja on, ja valitse sitten **Hyväksy**- tai **Hylkää**-toiminto.

Jos hyväksyt saapuvan asiakirjatietueen, saapuvan asiakirjan rivin **Vapautettu**-valintaruutu on valittuna. Esimerkiksi ostolaskujen luonnista vastaava henkilö voi nyt aloittaa tietueen käsittelemisen.

## <a name="to-create-an-incoming-document-record-by-taking-a-photo"></a>Saapuvien asiakirjatietueiden luominen valokuva ottamalla
**Huomautus**: Seuraavat toimet koskevat vain Dynamics NAV -ohjelman taulutietokone- ja puhelinasiakasohjelmaa.

1. Valitse sovellusriviltä **luo saapuva asiakirja kamerasta** ruutu ja siirry sitten vaiheeseen 4.
2. Voit myös valita sovellusrivin, valita asetukset-painikkeen, valita **saapuvat asiakirjat**, ja valita sitten **kaikki**.
3. Valitse **Saapuvat asiakirjat** -ikkunassa ellipsipainike ja valitse sitten **Luo kamerasta**. Tabletin tai puhelimen kamera ativoituu.
4. Ota valokuva asiakirjasta, kuten tavaran vastaanotto, jonka haluat käsitellä saapuvana asiakirjana,ja valitse sitten **OK**.

Luo uuden saapuvan asiakirjan tietueen ja liittää kuvan.

## <a name="to-attach-an-image-to-an-incoming-document-record-by-taking-a-photo"></a>Kuvan liittäminen saapuvien asiakirjatietueiden tietueeseen valokuva ottamalla
**Huomautus**: Seuraavat toimet koskevat vain Dynamics NAV -ohjelman taulutietokone- ja puhelinasiakasohjelmaa.

1. Voit valita sovellusrivin, valita asetukset-painikkeen, valita **saapuvat asiakirjat**, ja valita sitten **kaikki**.
2. Avaa aiemmin luotu saapuvan asiakirjan tietue kortti.
3. Valitse **Saapuva asiakirja** -ikkunassa ellipsipainike ja valitse sitten **Liitä kuva kamerasta**. Tabletin tai puhelimen kamera ativoituu.
4. Ota valokuva asiakirjasta, kuten tavaran vastaanotto, jonka haluat käsitellä saapuvana asiakirjana,ja valitse sitten **OK**.

Kuva liitetään saapuvan asiakirjan tietueeseen.

## <a name="to-create-an-incoming-document-record-manually"></a>Saapuvan asiakirjatietueen luominen manuaalisesti
1. Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Saapuvat asiakirjat** ja valitse sitten aiheeseen liittyvä linkki.
2. Valitse **Luo tiedostosta** -toiminto.  
3. **Lisää tiedosto** -ikkunassa valitse tiedosto ja valitse sitten **Avaa**.

    Tiedosto liitetään automaattisesti.
4. Vaihtoehtoisesti voit valita **Uusi**-toiminnon.
5. Voit liittää tiedoston valitsemalla **Liitä tiedosto** -toiminto.
6. Valitse **Lisää tiedosto** -ikkunassa tiedosto, joka vastaa kyseistä saapuvaa asiakirjaa, ja valitse sitten **Avaa**.
7. Täytä **Saapuva asiakirja** -ikkunassa tarvittavat kentät. Lue kentän lyhyt kuvaus valitsemalla kenttä tai siirry lisätietoihin valitsemalla linkki.

##<a name="see-also"></a>Katso myös  
[Saapuvien asiakirjojen käsitteleminen](across-process-income-documents.md)  
[Saapuvat asiakirjat](across-income-documents.md)  
[Ostojen hallinta](purchasing-manage-purchasing.md)  
[Dynamics NAV -ohjelman käyttäminen](ui-work-product.md)

