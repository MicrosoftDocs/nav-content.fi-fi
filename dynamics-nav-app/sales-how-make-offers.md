---
title: 'Toimintaohje: Tarjousten tekeminen'
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
ms.openlocfilehash: e126c755a9121c3a91f3af72f3f1ae14702a4701
ms.contentlocale: fi-fi
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-make-offers"></a>Toimintaohje: Tarjousten tekeminen
Luot myyntitarjouksen tallentaaksesi tarjouksen asiakkaalle myydäksesi määrätyt tuotteet määrätyillä toimitus- ja maksuehdoilla. Voit lähettää myyntitarjouksen asiakkaalle kommunikoidaksenne tarjouksesta. Voit lähettää asiakirjan sähköpostitse PDF-liitteenä. Sähköpostin perusteksti voidaan esitäyttää tarjouksen yhteenvedolla. Lisätietoja on kohdassa [Toimintaohje: Asiakirjojen lähettäminen sähköpostitse](ui-how-send-documents-email.md).

Kun neuvottelet asiakkaan kanssa, voit muuttaa ja lähettää myyntitarjouksen uudelleen niin paljon kuin tarvitaan. Kun asiakas hyväksyy tarjouksen, voit muuntaa myyntitarjouksen myyntilaskuksi tai -tilaukseksi, jossa myynti käsitellään. Lisätietoja on kohdassa [Toimintaohje: Myynnin laskuttaminen](sales-how-invoice-sales.md) tai [Toimintaohje: Tuotteiden myyminen](sales-how-sell-products.md).

Tuotteet voivat olla sekä varastonimikkeitä että palveluita. Lisätietoja on kohdassa [Toimintaohje: Uusien tuotteiden rekisteröiminen](inventory-how-register-new-products.md). Myyntitarjousprosessi on sama molemmille tuotetyypeille.

**Huomautus**: Dynamics NAV -ohjelmassa tuotteeseen viitataan termillä “nimike”.

Voit täyttää myyntitarjouksen asiakkaan kentät kahdella tavalla sen mukaan, onko asiakas jo rekisteröity.

## <a name="to-create-a-sales-quote"></a>Myyntitarjousten luominen
1. Valitse kotisivulla **Myyntitarjous**-toiminto.  
2. Syötä **Asiakas**-kenttään nykyisen asiakkaan nimi.

    Muut **Myyntitarjous**-ikkunan kentät täytetään nyt valitun asiakkaan vakiotiedoilla. Jos asiakasta ei ole rekisteröity, toimi seuraavasti:

3. Syötä **Asiakas**-kenttään uuden asiakkaan nimi.
4. Valitse uuden asiakkaan rekisteröimisen valintaikkunassa **Kyllä**-painike.
5. Valitse **Valitse uuden asiakkaan malli** -ikkunassa malli uuden asiakkaan kortin perusteella ja valitse sitten **OK**-painike.
6. Uuden asiakkaan kortti avautuu esitäytettynä valitun asiakasmallin tiedoilla. **Nimi**-kenttään esitäytetään myyntilaskuun syöttämäsi uuden asiakkaan nimi.
7. Jatka täyttämällä asiakkaan kortin jäljellä olevat kentät. Lisätietoja on kohdassa [Toimintaohje: Uusien asiakkaiden rekisteröiminen](sales-how-register-new-customers.md).  
8. Kun olet määrittänyt asiakaskortin, valitse **OK**-painike palataksesi **Myyntitarjous**-ikkunaan.

    Myyntitarjouksen useat kentät täytetään nyt tiedoilla, jotka olet määrittänyt uuden asiakkaan kortissa.
9. Täytä tarvittaessa jäljellä olevat kentät **Myyntitarjous**-ikkunassa. Lue kentän lyhyt kuvaus valitsemalla kenttä tai siirry lisätietoihin valitsemalla linkki.

    Nyt voit täyttää myyntitarjousrivit varastonimikkeillä tai palveluilla, joita haluat tarjota asiakkaalle.

    **Huomautus**: Jos olet määrittänyt toistuvien myyntien rivin asiakkaalle, kuten kuukausittainen täydennystilaus, voit lisätä nämä rivit tarjoukseen valitsemalla **Nouda toistuvat myyntirivit** -toiminto.
10. Valitse **Rivit**-pikavälilehdessä **Nimikenro**-kenttä ja syötä varastonimike tai palvelu.
11. Syötä tarjottavien nimikkeiden lukumäärä **Määrä**-kenttään.

    **Huomautus**: Kun nimikkeen tyyppi on Huolto, sen määrä on aikayksikkö, kuten tunnit, rivin **Mittayksikkökoodi**-kentän mukaan.

    **Rivisumma**-kenttä päivitetään näyttämään arvoa, joka saadaan kertomalla **Yksikköhinta**-kentän arvo **Määrä**-kentän arvolla.

    Hinta ja rivin summat näytetään ALV:n kanssa tai ilman riippuen siitä, mitä valitsit **Hinnat ALV:n kanssa** -kenttään asiakkaan kortissa.
12. Syötä **Rivialennus-%**-kenttään prosentti, jos haluat myöntää asiakkaalle alennuksen tuotteesta. Sama arvo päivitetään **Rivisumma**-kenttään.

    **Huomautus**: Jos olet määrittänyt asiakkaan tai nimikkeen kortin **Myyntihinnat ja myyntirivien alennukset** -pikavälilehdellä erityisiä nimikehintoja, rivialennusprosentti, hinta ja summa päivitetään automaattisesti tarjousrivillä, jos sovitut hinnan ehdot täyttyvät. Lisätietoja on kohdassa [Myyntihinnan, alennuksen ja maksusopimusten tallentaminen](sales-how-record-sales-price-discount-payment-agreements.md).
13. Voit lisätä tarjousriviä koskevan huomautuksen, jonka asiakas näkee tulostetussa myyntitarjouksessa, kirjoittamalla tekstin **Kuvaus**-kentän tyhjälle riville.  
14. Toista vaiheet 10–13 jokaiselle nimikkeelle, jonka haluat tarjota asiakkaalle.

    Rivien kokonaissummat lasketaan automaattisesti samalla, kun rivejä luodaan ja muokataan.
15. Syötä **Laskun alennussumma** -kenttään summa, joka vähennetään **Yhteensä sis. ALV:n** -kentässä olevasta arvosta.

    **Huomautus**: Jos asiakkaalle on määritetty laskualennukset, määritetty prosenttiluvun arvo lisätään automaattisesti **Asiakkaan laskun alennus-%** -kenttään, jos ehdot täyttyvät. Liittyvä summa lisätään **Laskun alennussumma ilman ALV:a** -kenttään. Lisätietoja on kohdassa [Myyntihinnan, alennuksen ja maksusopimusten tallentaminen](sales-how-record-sales-price-discount-payment-agreements.md).
16. Kun myyntitarjouksen rivit ovat valmiit, valitse **Sähköposti**- tai **Tulosta**-toiminto.

    Jos valitset **Sähköposti**-toiminnon, asiakkaalle lähetettävään sähköpostiin liitetään automaattisesti PDF-tiedosto. Voit määrittää sähköpostin niin, että se sisältää tarjouksen yhteenvedon. Lisätietoja on kohdassa [Toimintaohje: Asiakirjojen lähettäminen sähköpostitse](ui-how-send-documents-email.md).
17. Jos asiakas hyväksyy tarjouksen, valitse **Luo lasku**- tai **Tee tilaus** -toiminto.

Myyntitarjous on poistettu tietokannasta. Myyntilasku tai -tilaus luodaan myyntitarjouksen tietojen perusteella, jossa voit käsitellä myynnin. **Tarjouksen nro** -kentässä myyntilaskussa tai -tilauksessa näkyy käytetyn myyntitarjouksen numero. Lisätietoja on kohdassa [Toimintaohje: Myynnin laskuttaminen](sales-how-invoice-sales.md) tai [Toimintaohje: Tuotteiden myyminen](sales-how-sell-products.md).

## <a name="see-also"></a>Katso myös  
[Myynnin hallinta](sales-manage-sales.md)  
[Myynnin määrittäminen](sales-setup-sales.md)  
[Toimintaohje: Asiakirjojen lähettäminen sähköpostitse](ui-how-send-documents-email.md)  
[Dynamics NAV -ohjelman käyttäminen](ui-work-product.md)

