---
title: Toimittajamaksujen ehdottaminen
author: SorenGP
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 11bfba9f279f6bd84c5d169f6f97fd48759bc6df
ms.contentlocale: fi-fi
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-suggest-vendor-payments"></a>Toimittajamaksujen ehdottaminen
**Maksupäiväkirja**-ikkunassa voit ehdottaa toiminnon avulla maksurivejä asetusten, kuten pian erääntyvien maksujen tai maksualennuksen omaavien maksujen, mukaan.

Ehdota toimittajamaksuja -toiminnosta on hyötyä eniten, jos priorisoit toimittajat ensin. Lisätietoja on ohjeaiheessa [Toimintaohje: Toimittajien priorisoiminen](purchasing-how-prioritize-vendors.md).

Toimittajatapahtumia, joita ei ole merkitty **Estossa**-merkinnällä, ei sisällytetä eräajoon.  

**Tärkeää**: Jos haluat hyötyä maksualennuksista, ja jos olet syöttänyt saatavilla olevan summan, summaa käytetään priorisoiduille erääntyneille toimittajatapahtumille, joilla on korkein prioriteetti, ja sitten erääntyneille toimittajatapahtumille, joita ei ole priorisoitu, ja lopuksi avoimille toimittajatapahtumille, jotka kelpuutetaan maksualennuksiin toimittajanumeron mukaan.

## <a name="to-use-the-suggest-vendor-payments-function"></a>Ehdota toimittajamaksuja -toiminnon käyttäminen
1. Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Maksupäiväkirjat** ja valitse sitten aiheeseen liittyvä linkki.
2. Avaa asianmukainen päiväkirja ja valitse **Ehdota toimittajamaksuja** -toiminto.
3. Täytä tarvittavat kentät. Lue kentän lyhyt kuvaus valitsemalla kenttä tai siirry lisätietoihin valitsemalla linkki.
4. Valitse **OK**-painike.

## <a name="to-insert-the-due-date-as-posting-date-on-payment-journal-lines"></a>Eräpäivän lisääminen maksupäiväkirjan rivien kirjauspäivämääräksi
Kun **Ehdota toimittajamaksuja** -eräajoa käytetään toimittajien maksurivien luomisessa, täyttämällä kaksi erikoiskenttää voi varmistaa, että luodut rivit käyttävät eräpäivää kirjauspäivämäärän laskemisessa. Nämä kentät ovat **Laske kirjauspäivämäärä kohdistuksen asiakirjan eräpäivästä** ja **Kohdistuksen asiakirjan eräpäivän siirtymä**.

**Tärkeää**: Et voi käyttää **Laske kirjauspäivämäärä kohdistuksen asiakirjan eräpäivästä** -kenttää yhdessä **Hae maksualennukset**- tai **Tee yhteenveto toimittajittain** -kentän kanssa. Syy on se, että mikäli tiliöintipäivä perustuu eräpäivään, joitain maksualennuksia ei ehkä ole laskettu oikein, koska tiliöintipäivä voi olla maksualennuspäivän jälkeen.
Jos laskettu kirjauspäivämäärä esiintyy menneisyydessä, kirjauspäivämäärää myös siirretään ylös käsittelypäivämäärään, ja näyttöön tulee varoitus.

Vaihtoehtoisesti voit luoda maksurivejä manuaalisesti niin, että eräpäivää käytetään kirjauspäivämäärän laskemisessa. Kun olet kohdistanut toimittajatapahtumat, voit käyttää **Laske kirjauspäivämäärä** -toimintoa. Tämä päivittää päiväkirjan rivin kirjauspäivämääräksi liittyvän ostotilauksen eräpäivän. Lisätietoja on kohdassa [Toimintaohje: Ostotapahtumien kohdistaminen manuaalisesti](payables-how-apply-purchase-transactions-manually.md).  

**Huomautus**: Jos ostolasku on myöhässä, käsittelypäivämäärä asetetaan käsittelypäivämääräksi ja rivin kirjasin muuttuu punaiseksi.

## <a name="see-also"></a>Katso myös
[Ostovelkojen hallinta](payables-manage-payables.md)  
[Maksujen suorittaminen](payables-make-payments.md)  
[Yleisten päiväkirjojen käyttäminen](ui-work-general-journals.md)

