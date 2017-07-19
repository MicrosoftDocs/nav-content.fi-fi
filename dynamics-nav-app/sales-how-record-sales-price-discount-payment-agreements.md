---
title: 'Toimintaohje: Myyntihintojen ja -alennusten tallentaminen'
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
ms.openlocfilehash: 2d6438108fb2c36bb6f0d44efddc053bd628d068
ms.contentlocale: fi-fi
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-record-sales-prices-and-discounts"></a>Toimintaohje: Myyntihintojen ja -alennusten tallentaminen
Eri asiakkaiden hinta- ja alennussopimukset on määritettävä, jotta asiakkaille luotavissa myyntiasiakirjoissa käytetään sovittuja sääntöjä ja arvoja.

Myyntiriveille lisätään erikoismyyntihinta, jos tietty asiakkaan, nimikkeen, vähimmäismäärän, mittayksikön sekä aloitus- ja lopetuspäivämäärän yhdistelmä on olemassa.

Voit määrittää seuraavat kaksi myyntialennustyyppiä:

|Alennustyyppi |Kuvaus |
|--------------|------------|
|**Myyntirivin alennus**|Myyntiriveille lisättävä summa-alennus, jos tietty asiakkaan, nimikkeen, vähimmäismäärän, mittayksikön sekä aloitus- ja lopetuspäivämäärän yhdistelmä on olemassa. Tätä käytetään samoin kuin myyntihinnoissa.|
|**Laskualennus**|Prosenttialennus, joka vähennetään kokonaissummasta, kun myyntiasiakirjan kaikkien rivien summa ylittää määritetyn vähimmäisarvon.|

Koska myyntihinnat ja myyntirivialennukset perustuvat nimikkeen ja asiakkaan yhdistelmään, voit tehdä tämän määrityksen myös sen nimikkeen kortissa, jota säännöt ja arvot koskevat.

## <a name="to-set-up-a-sales-price-for-a-customer"></a>Myyntihinnan määrittäminen asiakkaalle
1. Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Asiakkaat** ja valitse sitten aiheeseen liittyvä linkki.
2. Avaa kyseessä olevan asiakkaan kortti ja valitse **Hinnat**-toiminto.

    **Myynnin tyyppi** -kentän arvoksi esitäytetään **Asiakas**. **Myyntikoodi** -kentän arvoksi esitäytetään asiakasnumero.
3. Täytä tarvittaessa rivin muut kentät. Lue kentän lyhyt kuvaus valitsemalla kenttä tai siirry lisätietoihin valitsemalla linkki.
4. Täytä rivi jokaiselle yhdistelmälle, jossa asiakkaalle myönnetään erikoismyyntihinta.

## <a name="to-set-up-a-sales-line-discount-for-a-customer"></a>Myyntirivialennuksien määrittäminen asiakkaalle
1. Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Asiakkaat** ja valitse sitten aiheeseen liittyvä linkki.
2. Avaa kyseessä olevan asiakkaan kortti ja valitse **Rivialennukset**-toiminto.

    **Myynnin tyyppi** -kentän arvoksi esitäytetään **Asiakas**. **Myyntikoodi** -kentän arvoksi esitäytetään asiakasnumero.
3.  Täytä tarvittaessa rivin muut kentät. Lue kentän lyhyt kuvaus valitsemalla kenttä tai siirry lisätietoihin valitsemalla linkki.
4. Täytä rivi jokaiselle yhdistelmälle, jossa asiakkaalle myönnetään myyntirivialennus.

## <a name="to-set-up-an-invoice-discount-for-a-customer"></a>Laskualennuksen määrittäminen asiakkaalle
Kun olet määrittänyt asiakkaat, joille myönnetään laskun alennuksia, määritä laskun alennuskoodi asiakkaiden kortteihin ja määritä kunkin koodin ehdot.

1. Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Asiakkaat** ja valitse sitten aiheeseen liittyvä linkki.
2. Avaa sen asiakkaan kortti, jolle myönnetään laskun alennuksia.
3. Valitse **Laskualennuksen koodi** -kentässä asianmukaisille laskualennuksen ehdoille koodi, jonka avulla asiakkaan laskualennukset lasketaan.

    **Huomautus**: Laskualennuksen koodit löytyvät olemassa olevien asiakkaiden korteista. Näin voit nopeasti liittää laskualennusten ehtoja asiakkaisiin poimimalla sellaisen asiakkaan nimen, jolla on samat ehdot.

    Jatka uuden myyntilaskun alennusehtojen määrittämiseen.
4. Valitse **Asiakkaan kortti** -ikkunassa **Laskualennukset**-toiminto. **Asiakkaan laskualennukset** -ikkuna aukeaa.
5. Syötä **Valuutan koodi** -kenttään sen valuutan koodi, johon rivin laskualennuksen ehdot kohdistetaan. Jätä kenttä tyhjäksi, jos laskualennuksen ehdot määritetään Yhdysvaltojen dollareina.
6. Syötä **Vähimmäissumma**-kenttään laskun vähimmäissumma, joka oikeuttaa alennukseen.
7. Syötä **Alennus-%**-kohtaan laskun alennus prosentteina laskun summasta.
8. Toista vaiheet 5–7 jokaiselle valuutalle, jossa asiakas saa eri laskualennuksen.

Laskualennus on nyt määritetty ja liitetty kyseiselle asiakkaalle. Kun valitset asiakaskoodin muiden asiakkaiden korttien **Laskun alennuskoodi** -kentässä, sama laskualennus liitetään myös näille asiakkaille.

## <a name="see-also"></a>Katso myös  
[Myynnin määrittäminen](sales-setup-sales.md)  
[Myynnin hallinta](sales-manage-sales.md)

