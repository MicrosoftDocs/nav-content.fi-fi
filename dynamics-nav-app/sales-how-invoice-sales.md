---
title: 'Toimintaohje: Myynnin laskutus'
author: SorenGP
ms.custom: na
ms.date: 11/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: cba338ec6469ea0ac22f024571664a718988e827
ms.contentlocale: fi-fi
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-invoice-sales"></a>Toimintaohje: Myynnin laskutus

Luo myyntilasku tai -tilaus tallentaaksesi sopimuksesi asiakkaan kanssa ja myydäksesi määrätyt tuotteet määrätyillä toimitus- ja maksuehdoilla.

**Huomautus**: Myyntitilauksia on käytettävä, jos myyntiprosessi vaatii tilausmäärän osittaisen toimittamisen esimerkiksi silloin, kun koko määrä ei ole kerralla käytettävissä. Jos myyt nimikkeitä toimittamalla ne suoraan toimittajalta asiakkaalle (suoratoimituksena), myyntitilauksia on käytettävä. Lisätietoja on kohdassa [Toimintaohje: Suoratoimitusten tekeminen](sales-how-drop-shipment.md). Kaikilta muilta osin myyntitilaukset toimivat samalla tavalla kuin myyntilaskut. Lisätietoja on kohdassa [Toimintaohje: Tuotteiden myyminen](sales-how-sell-products.md).

Voit neuvotella asiakkaan kanssa luomalla ensin myyntitarjoukseen, jonka voit muuntaa myyntilaskuksi, kun hyväksyt myynnin. Lisätietoja on kohdassa [Toimintaohje: Tarjousten tekeminen](sales-how-make-offers.md).

Kun asiakas on vahvistanut sopimuksen esimerkiksi tarjousprosessin jälkeen, voit kirjata myyntilaskun ja luoda järjestelmään liittyvän määrän ja arvotapahtumat. Kun kirjaat myyntilaskun, voit myös lähettää asiakirjan PDF-liitteenä sähköpostitse. Sähköpostin perusteksti voidaan esitäyttää laskun ja maksun tietojen yhteenvedolla. Tietoihin voi kuulua esimerkiksi PayPal-linkki. Lisätietoja on kohdassa [Toimintaohje: Asiakirjojen lähettäminen sähköpostitse](ui-how-send-documents-email.md).

Liiketoimintaympäristöissä, joissa asiakkaan on maksettava ennen kuin tuotteet toimitetaan, kuten vähittäismyynti, sinun on odotettava maksukuittia ennen kuin toimitat tuotteet. Useimmissa tapauksissa saapuvia maksuja käsitellään joitakin viikkoja toimituksen jälkeen kohdistamalla maksut niihin liittyviin kirjattuihin ja maksamattomiin myyntilaskuihin. Lisätietoja on kohdassa [Toimintaohje: Maksujen täsmäyttäminen käyttämällä automaattista kohdistusta](receivables-how-reconcile-payments-auto-application.md).

Jos kirjattu myyntilasku maksetaan, sinun on luotava myyntihyvityslasku kaupan peruuttamiseksi. Lisätietoja on kohdassa [Toimintaohje: Myyntipalautusten tai -peruutusten käsitteleminen](sales-how-process-sales-returns-cancellations.md).

Tuotteet voivat olla sekä varastonimikkeitä että palveluita. Lisätietoja on kohdassa [Toimintaohje: Uusien tuotteiden rekisteröiminen](inventory-how-register-new-products.md). Myyntilaskuprosessi on sama molemmille tuotetyypeille.

**Huomautus**: Dynamics NAV -ohjelmassa tuotteeseen viitataan termillä “nimike”.

Voit täyttää myyntilaskun asiakkaan kentät kahdella tavalla sen mukaan, onko asiakas jo rekisteröity.

## <a name="to-create-a-sales-invoice"></a>Myyntilaskujen luominen
1. Valitse kotisivulla **Myyntilasku**-toiminto.  
3. Syötä **Asiakas**-kenttään nykyisen asiakkaan nimi.

    Muut **Myyntilasku**-ikkunan kentät täytetään nyt valitun asiakkaan vakiotiedoilla. Jos asiakasta ei ole rekisteröity, toimi seuraavasti:
4. Syötä **Asiakas**-kenttään uuden asiakkaan nimi.
5. Valitse uuden asiakkaan rekisteröimisen valintaikkunassa **Kyllä**-painike.
6. Valitse **Valitse uuden asiakkaan malli** -ikkunassa malli uuden asiakkaan kortin perusteella ja valitse sitten **OK**-painike.
7. Uuden asiakkaan kortti avautuu esitäytettynä valitun asiakasmallin tiedoilla. **Nimi**-kenttään esitäytetään myyntilaskuun syöttämäsi uuden asiakkaan nimi.
8. Jatka täyttämällä asiakkaan kortin jäljellä olevat kentät. Lisätietoja on kohdassa [Toimintaohje: Uusien asiakkaiden rekisteröiminen](sales-how-register-new-customers.md).  
9. Kun olet määrittänyt asiakaskortin, valitse **OK**-painike palataksesi **Myyntilasku**-ikkunaan.

    Myyntilaskun useat kentät täytetään nyt tiedoilla, jotka olet määrittänyt uuden asiakkaan kortissa.
10. Täytä tarvittaessa jäljellä olevat kentät **Myyntilasku**-ikkunassa. Lue kentän lyhyt kuvaus valitsemalla kenttä tai siirry lisätietoihin valitsemalla linkki.

    Nyt voit täyttää myyntilaskurivit varastonimikkeillä tai palveluilla, joita haluat myydä asiakkaalle.

    Jos olet määrittänyt toistuvien myyntien rivin asiakkaalle, kuten kuukausittainen täydennystilaus, voit lisätä nämä rivit laskuun valitsemalla **Nouda toistuvat myyntirivit** -toiminto.
11. Syötä **Rivit**-pikavälilehden **Nimike**-kenttään varastonimikkeen tai palvelun numero.  
12. Syötä myytävien nimikkeiden lukumäärä **Määrä**-kenttään.

    **Huomautus**: Kun nimikkeen tyyppi on Huolto, sen määrä on aikayksikkö, kuten tunnit, rivin **Mittayksikkökoodi**-kentän mukaan.

    **Rivisumma**-kenttä päivitetään näyttämään arvoa, joka saadaan kertomalla **Yksikköhinta**-kentän arvo **Määrä**-kentän arvolla.

    Hinta ja rivin summat näytetään ALV:n kanssa tai ilman riippuen siitä, mitä valitsit **Hinnat verojen kanssa** -kenttään asiakkaan kortissa.
13. Syötä **Rivialennus-%**-kenttään prosentti, jos haluat myöntää asiakkaalle alennuksen tuotteesta. Sama arvo päivitetään **Rivisumma**-kenttään.

    Jos olet määrittänyt asiakkaan tai nimikkeen kortin **Myyntihinnat ja myyntirivien alennukset**-pikavälilehdellä erityisiä nimikehintoja, rivialennusprosentti, hinta ja summa päivitetään automaattisesti tarjousrivillä, jos sovitut hinnan ehdot täyttyvät. Lisätietoja on kohdassa [Myyntihinnan, alennuksen ja maksusopimusten tallentaminen](sales-how-record-sales-price-discount-payment-agreements.md).
14. Voit lisätä tarjousriviä koskevan huomautuksen, jonka asiakas näkee tulostetussa myyntitarjouksessa, kirjoittamalla tekstin **Kuvaus**-kentän tyhjälle riville.  
15. Toista vaiheet 10–13 jokaiselle nimikkeelle, jonka haluat tarjota asiakkaalle.

    Rivien kokonaissummat lasketaan automaattisesti samalla, kun rivejä luodaan ja muokataan.
16. Syötä **Laskun alennussumma** -kenttään summa, joka vähennetään **Yhteensä sis. ALV:n** -kentässä olevasta arvosta.

    Jos asiakkaalle on määritetty laskualennukset, määritetty prosenttiluvun arvo lisätään automaattisesti **Asiakkaan laskun alennus-%** -kenttään, jos ehdot täyttyvät. Liittyvä summa lisätään **Laskun alennussumma ilman ALV:a** -kenttään. Lisätietoja on kohdassa [Myyntihinnan, alennuksen ja maksusopimusten tallentaminen](sales-how-record-sales-price-discount-payment-agreements.md).
17. Kun myyntilaskun rivit ovat valmiit, valitse **Kirjaa ja lähetä** -toiminto.

**Kirjaa ja lähettää vahvistuksen** -valintaikkuna avautuu, jossa näkyy suositeltu tapa lähettää asiakkaalle. Voit muuttaa lähetysmenetelmän valitsemalla **Lähetä asiakirja kohteeseen** -kentän valintapainikkeen. Lisätietoja on kohdassa [Toimintaohje: Asiakirjan lähetysprofiilien määrittäminen](sales-how-setup-document-send-profiles.md).

Nyt järjestelmässä luodaan liittyvä nimike ja asiakastapahtumat. Myyntilasku tulostetaan PDF-asiakirjana. Myyntilasku poistetaan myyntilaskujen luettelosta ja korvataan uudella asiakirjalla kirjattujen myyntilaskujen luettelosta.

## <a name="see-also"></a>Katso myös  
[Myynnin hallinta](sales-manage-sales.md)  
[Myynnin määrittäminen](sales-setup-sales.md)  
[Vaihto-omaisuus](inventory-manage-inventory.md)    
[Toimintaohje: Asiakirjojen lähettäminen sähköpostitse](ui-how-send-documents-email.md)  
[Dynamics NAV -ohjelman käyttäminen](ui-work-product.md)

