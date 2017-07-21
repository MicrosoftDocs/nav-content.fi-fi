---
title: "Toimintaohje: Asiakkaan maksujen ottaminen käyttöön PayPalin kautta"
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
ms.openlocfilehash: a2268d8454af761c40b11d89b01778a3f92090fb
ms.contentlocale: fi-fi
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-enable-customer-payments-through-paypal"></a>Toimintaohje: Asiakkaan maksujen ottaminen käyttöön PayPalin kautta#
Pankkisiirron tai luottokorttien lisäksi asiakkaille voi tarjota mahdollisuuden maksaa PayPal-tilin avulla.

Kun asiakas valitsee myyntilaskun tai myyntitilausasiakirjan PayPal-linkin, näyttöön avautuu asiakkaan PayPal-tilin palvelusivu, joka sisältää myyntiä koskevat maksutiedot. Tämän jälkeen asiakas voi maksaa laskun kuten minkä tahansa PayPal-maksun.

Voit ottaa asiakkaan maksut käyttöön PayPalin kautta seuraavasti:

1. Määritä PayPal Payments Standard maksupalveluksi **Maksupalvelut**-ikkunassa.
2. Valitse kyseisen myyntiasiakirjan **Maksupalvelu**-kentässä PayPal Payments Standard.

PayPal Payments Standard -palvelu asennetaan laajennuksena Dynamics NAV -ohjelmaan. Se on valmis otettavaksi käyttöön. Lisätietoja on kohdassa [Dynamics NAV -ohjelman mukauttaminen laajennusten avulla ](ui-extensions.md).

## <a name="to-enable-the-paypal-payments-standard-service"></a>PayPal Payments Standard -palvelun ottaminen käyttöön
1. Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Maksupalvelut** ja valitse sitten aiheeseen liittyvä linkki.  
2. Valitse **Maksupalvelut**-ikkunassa **Uusi**-toiminto.
3. Valitse **PayPal Standard** ja sulje ikkuna.
4. Valitse **Maksupalvelut**-ikkunassa **Asetus**-toiminto.
5. Täytä tarvittavat kentät. Lue kentän lyhyt kuvaus valitsemalla kenttä tai siirry lisätietoihin valitsemalla linkki.

    **Huomautus**: Valitse **Sisällytä aina asiakirjoihin** -valintaruutu, jos haluat, että PayPal-maksupalvelun hyperlinkki on näkyvissä myyntiasiakirjoissa aina silloin, kun maksaminen PayPalin kautta on käytössä.

6. Sulje ikkuna.

## <a name="to-select-paypal-payments-standard-on-a-sales-invoice"></a>PayPal Payments Standardin valitseminen myyntilaskussa
1. Valitse kotisivun **Myyntilaskut**-kohta.
2. Avaa myyntilasku, jossa haluat ottaa PayPal-maksut käyttöön.
3. Valitse **Maksupalvelu**-kentässä PayPal Payments Standard.

**Huomautus**: **Maksupalvelu**-kenttä on näkyvissä vain, jos PayPal Payments Standard -palvelu on käytössä.   

## <a name="see-also"></a>Katso myös  
[Myynnin määrittäminen](sales-setup-sales.md)  
[Myynnin hallinta](sales-manage-sales.md)  
[Dynamics NAV -ohjelman mukauttaminen laajennusten avulla](ui-extensions.md)

