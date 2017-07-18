---
title: "Toimintaohje: Asiakkaan maksujen täsmäyttäminen manuaalisesti"
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
ms.openlocfilehash: de0c94386ad5a0bbfba5cc0516fa7faa5cdcc0b4
ms.contentlocale: fi-fi
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-reconcile-customer-payments-manually"></a>Toimintaohje: Asiakkaan maksujen täsmäyttäminen manuaalisesti
Kun asiakkaalta saadaan kassaanmaksu tai asiakkaalle tehdään käteishyvitys, on päätettävä, kohdistetaanko maksu tai hyvitys yhteen vai useaan avoimeen debet- tai kredit-tapahtumaan. Voit määrittää tarkan summan, jota sovelletaan. Saatat haluta kohdistaa vain osan maksusta, jolloin asiakastapahtumat kohdistetaan vain osittain. On tärkeää, että jossakin vaiheessa kaikki asiakastapahtumat suljetaan, jotta saadaan oikeat asiakastilastot sekä tiliotteiden ja rahoituksen käyttöönoton tulosteet.

Voit kohdistaa asiakastapahtumia seuraavilla kolmella tavalla:

- syöttämällä tiedot niille tarkoitettuihin ikkunoihin, kuten **Kassapäiväkirja**- ja **Maksujen täsmäytyskirjauskansio** -ikkunaan.
- myyntihyvityslaskuasiakirjoista
- asiakastapahtumista sen jälkeen, kun myyntiasiakirjat on kirjattu, mutta ei kohdistettu.

**Huomautus**: Jos asiakkaan kortin **Kohdistustapa**-kentän arvo on **Kohdista vanhimpaan**, maksut kohdistetaan automaattisesti vanhimpaan avoimeen kredit-tapahtumaan, jos tapahtumaa, johon kohdistetaan, ei määritetä manuaalisesti. Jos asiakkaan kohdistustapa on **Manuaalinen**, tapahtumat on kohdistettava manuaalisesti.

Voit kohdistaa asiakkaan maksut manuaalisesti **Kassapäiväkirja**-ikkunassa. Kassapäiväkirja on yleisen päiväkirjan tyyppi, joten sitä voidaan käyttää kirjaamaan myyntitapahtumia yleinen päiväkirja -, pankki-, asiakas-, toimittaja- ja käyttöomaisuustileille. Voit kohdistaa maksun yhteen tai useampaan debet-tapahtumaan, kun kirjaat maksun, tai tehdä kohdistuksen myöhemmin kirjatuista tapahtumista.

Voit kohdistaa asiakas- ja toimittajamaksuja myös **Maksujen täsmäytyskirjauskansio** -ikkunassa pankin tiliotteen tuonnin, automaattisen kohdistamisen ja pankkitilin täsmäyttämisen toimintojen avulla. Lisätietoja on kohdassa [Maksujen täsmäyttäminen käyttämällä automaattista kohdistusta](receivables-how-reconcile-payments-auto-application.md). Vaihtoehtoisesti voit täsmäyttää asiakasmaksut **Maksurekisteröinti**-ikkunan maksamattomien myyntiasiakirjojen luettelon perusteella. Lisätietoja on kohdassa [Toimintaohje: Asiakasmaksujen täsmäyttäminen maksamattomien myyntiasiakirjojen luettelosta](receivables-how-reconcile-customer-payments-list-unpaid-sales-documents.md).

## <a name="to-fill-and-post-a-cash-receipt-journal"></a>Kassapäiväkirjan täyttäminen ja kirjaaminen
1. Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Kassapäiväkirja** ja valitse sitten aiheeseen liittyvä linkki.
2. Valitse haluamasi erä **Erän nimi** -kentässä.
3. Täytä **Kirjauspvm.**-kentän tiedot.  
4. Valitse **Asiakirjatyyppi**-kentässä **Maksu**.

    **Asiakirjan nro** -kenttään syötetään erälle määritetty numerosarja.
5. Käytä **Ulkoisen asiakirjan nro** -kenttää, kun tallennat tunnuksen, kuten asiakkaan sekin numeron.
6. Valitse **Tilityyppi**-kentässä **Asiakas**.
7. Valitse **Tilinumero**-kenttään asianmukainen KP-tili.
8. Jos haluat kirjata kohdistuksen samaan aikaan päiväkirjan kirjaamisen yhteydessä, valitse jokin seuraavista menetelmistä:
9. Valitse **Vastatilin tyyppi** -kentässä kassamaksuille **KP-tili** ja muille maksuille **Pankkitili**.
10. Valitse **Vastatilin nro** -kentässä kassamaksujen kassatili tai muiden maksujen asianmukainen pankkitili.
11. Kirjaa päiväkirja.

## <a name="to-apply-a-payment-to-a-single-customer-ledger-entry"></a>Maksun kohdistaminen yhteen asiakastapahtumaan:
1. Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Kassapäiväkirja** ja valitse sitten aiheeseen liittyvä linkki.
2. Syötä ensimmäiselle päiväkirjariville asianmukaiset tiedot kohdistettavasta tapahtumasta.
3. Syötä **Asiakirjatyyppi**-kenttään **Maksu**.
4. Syötä **Tilityyppi**-kenttään **Asiakas**.
5. Syötä **Vastatilin tyyppi** -kenttään **Pankkitili**.
6. Valitse **Kohdistetaan asiakirjaan nro** -kentässä kenttä, jolloin **Kohdista asiakastapahtumat** -ikkuna avautuu.
7. Valitse **Kohdista asiakastapahtumat** -ikkunassa tapahtuma, johon maksu kohdistetaan.
8. Syötä tapahtumaan kohdistettava summa **Kohdistettava summa** -kenttään. Jos summaa ei määritetä, käytetään enimmäissummaa.

    **Kohdista asiakastapahtumat** -ikkunan alaosan **Kohdistettu summa** -kentässä on tietty summa sekä tieto siitä, täsmääkö kohdistus.
9. Valitse **OK**-painike. **Kassapäiväkirja**-ikkunassa näkyy nyt tapahtuma, jonka olet syöttänyt **Kohdistetaan asiakirjatyyppiin**- ja **Kohdistetaan asiakirjaan nro** - -kentät.
10. Kirjaa kassapäiväkirja.

## <a name="to-apply-a-payment-to-multiple-customer-ledger-entries"></a>Maksun kohdistaminen useaan asiakastapahtumaan:
1. Valitse oikeassa yläosassa oleva **Etsi sivua tai raporttia** -kuvake, syötä **Kassapäiväkirja** ja valitse liittyvä linkki.
2. Syötä ensimmäiselle päiväkirjariville asianmukaiset tiedot kohdistettavasta tapahtumasta.
3. Syötä **Asiakirjatyyppi**-kenttään **Maksu**.
4. Syötä **Tilityyppi**-kenttään **Asiakas**.
5. Syötä **Vastatilin tyyppi** -kenttään **Pankkitili**.
6. Syötä **Summa**-kenttään täysi maksu negatiivisena summana.
7. Voit kohdistaa maksun useaan asiakastapahtumaan kirjaamisen yhteydessä valitsemalla **Kohdista tapahtumat** -toiminto.
8. Valitse rivit, joiden tapahtumiin tapahtuma kohdistetaan, ja valitse sitten **Aseta kohdistustunniste** -toiminto.
9. Määritä yksittäiseen tapahtumaan kohdistettava summa kunkin rivin **Kohdistettava summa** -kenttään. Jos summaa ei määritetä, käytetään enimmäissummaa.

    **Kohdista asiakastapahtumat** -ikkunan alaosan **Kohdistettu summa** -kentässä on tietty summa sekä tieto siitä, täsmääkö kohdistus.
10. Valitse **OK**-painike.
11. Kirjaa kassapäiväkirja.

## <a name="to-apply-a-credit-memo-to-a-single-customer-ledger-entry"></a>Hyvityslaskun kohdistaminen yhteen asiakastapahtumaan:
1. Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Myyntihyvityslaskut** ja valitse sitten aiheeseen liittyvä linkki.
2. Avaa haluamasi myyntihyvityslasku.
3. Voit kohdistaa hyvityslaskun yksittäiseen asiakastapahtumaan kirjaamisen yhteydessä valitsemalla **Kohdistetaan asiakirjaan nro** -kentässä tapahtuma, johon haluat kohdistaa maksun.
4. Määritä tapahtumaan kohdistettava summa rivin **Kohdistettava summa** -kenttään.

    Jos summaa ei määritetä, ohjelma kohdistaa automaattisesti enimmäissumman. **Kohdista asiakastapahtumat** -ikkunan alaosan **Kohdistettu summa** -kentässä on tietty summa sekä tieto siitä, täsmääkö kohdistus.
5. Valitse **OK**-painike. **Myyntihyvityslasku**-ikkunassa näkyy nyt tapahtuma, jonka olet syöttänyt **Kohdistetaan asiakirjatyyppiin**- ja **Kohdistetaan asiakirjaan nro** - -kentät. -ikkunassa näkyy nyt kirjattava hyvityslaskun summa sekä mahdolliset maksualennukset.
6. Kirjaa hyvityslasku.

## <a name="to-apply-a-credit-memo-to-multiple-customer-ledger-entries"></a>Hyvityslaskun kohdistaminen useaan asiakastapahtumaan:
1. Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Myyntihyvityslaskut** ja valitse sitten aiheeseen liittyvä linkki.
2. Avaa haluamasi myyntihyvityslasku.
3. Voit kohdistaa hyvityslaskun useaan asiakastapahtumaan kirjaamisen yhteydessä valitsemalla **Kohdista tapahtumat** -toiminto.
4. Valitse rivit, joiden tapahtumiin tapahtuma kohdistetaan, ja valitse sitten **Aseta kohdistustunniste** -toiminto.
5. Määritä yksittäiseen tapahtumaan kohdistettava summa kunkin rivin **Kohdistettava summa** -kenttään. Jos summaa ei määritetä, käytetään enimmäissummaa.

  **Kohdista asiakastapahtumat** -ikkunan alaosan **Kohdistettu summa** -kentässä on tietty summa sekä tieto siitä, täsmääkö kohdistus.
6. Valitse **OK**-painike. **Myyntihyvityslasku**-ikkunassa näkyy nyt kirjattava hyvityslaskun summa sekä mahdolliset maksualennukset.
7. Kirjaa hyvityslasku.

## <a name="to-apply-posted-customer-ledger-entries"></a>Kirjattujen asiakastapahtumien kohdistaminen:
1. Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Asiakkaat** ja valitse sitten aiheeseen liittyvä linkki.
2. Avaa sen asiakkaan kortti, jonka tapahtumia haluat kohdistaa.
3. Valitse **Tapahtumakirjaukset**-toiminto ja valitse sitten sen tapahtuman rivi, johon tapahtuma kohdistetaan.
4. Valitse **Kohdista tapahtumat** -toiminto. Näyttöön avautuu **Kohdista asiakastapahtumat** -ikkuna, jossa näkyvät asiakkaan avoimet tapahtumat.
5. Valitse rivit, joiden tapahtumiin tapahtuma kohdistetaan, ja valitse sitten **Aseta kohdistustunniste** -toiminto.
6. Määritä yksittäiseen tapahtumaan kohdistettava summa kunkin rivin **Kohdistettava summa** -kenttään. Jos summaa ei määritetä, käytetään enimmäissummaa.

    Tietty summa näkyy **Kohdista asiakastapahtumat** -ikkunan alaosan **Kohdistettu summa** -kentässä.
7. Valitse **Kirjaa kohdistus** -toiminto. Näyttöön avautuu **Kirjaa kohdistus** -ikkuna, joka sisältää kohdistettavan tapahtuman asiakirjanumeron sekä viimeksi kirjatun tapahtuman kirjauspäivämäärän.  
8. Kirjaa sovellus valitsemalla **OK**.

    Jos kirjatun kohdistuksen tuloksena on suljettuja asiakastapahtumia, näiden tapahtumien **Avoin**-kentässä ei enää ole valintamerkkiä.
9. Voit tarkastella tapahtumakirjauksia valitsemalla oikeassa yläkulmassa olevan **Etsi sivu tai raportti** -kuvakkeen, syöttämällä **Asiakkaat** ja valitsemalla sitten aiheeseen liittyvän linkin. Etsi asianmukaisen asiakkaan kortti nähdäksesi tapahtumat.

**Avaa**-valintaruutua, joka sijaitsee sen tapahtumakirjausluettelon rivillä, joka sisältää kokonaan kohdistetun tapahtumakirjauksen, ei ole valittu.  

**Huomautus**: Kun **Kohdista asiakastapahtumat** -ikkunasta on valittu tapahtuma tai useita tapahtumia asettamalla **Kohdistetaan tunnisteeseen** -kohdan arvo, päiväkirjarivin **Kohdistettu summa** -kentässä näytetään valittujen kirjattujen tapahtumien jäljellä oleva yhteissumma, ellei kentässä jo ole arvoa. Jos asiakkaan kortin **Kohdistustapa**-kentässä valitaan **Kohdista vanhimpaan**, sovellus tekee kohdistuksen automaattisesti.

## <a name="to-apply-customer-ledger-entries-in-different-currencies-to-one-another"></a>Erivaluuttaisten asiakastapahtumien kohdistaminen toisiinsa:
Jos asiakkaalle myydään yhdessä valuutassa ja maksu vastaanotetaan toisessa valuutassa, maksu voidaan kohdistaa laskuun.

Jos tapahtuma (tapahtuma 1) kohdistetaan eri valuuttaa käyttävään tapahtumaan (tapahtuma 2), tapahtuman 2 summien muuntamisessa käytettävä vaihtokurssi etsitään tapahtuman 1 kirjauspäivämäärän mukaan. Vaihtokurssi löytyy **Valuutan vaihtokurssit** -ikkunasta.

Asiakastapahtumien kohdistaminen eri valuutoissa on otettava käyttöön. Lisätietoja on kohdassa [Toimintaohje: Tapahtumakirjausten kohdistamisen ottaminen käyttöön eri valuutoissa](finance-setup-how-enable-application-ledger-entries-different-currencies.md).

1. Valitse oikeassa yläosassa oleva **Etsi sivua tai raporttia** -kuvake, syötä **Kassapäiväkirja** ja valitse liittyvä linkki.
2. Avaa haluamasi päiväkirja ja täytä ensimmäinen tyhjä päiväkirjan rivi valuuttakoodilla.
3. Valitse **Kohdista tapahtumat** -toiminto.
4. Valitse rivi, jonka tapahtumaan kassapäiväkirjan tapahtuma kohdistetaan. Valitse sitten **Aseta kohdistustunniste** -toiminto ja valitse tapahtuma, johon kohdistetaan.
5. Valitse **OK**-painike palataksesi kassapäiväkirjaan.
6. Kirjaa myyntipäiväkirja.

**Tärkeää**: Kun erivaluuttaisia tapahtumia kohdistetaan toisiinsa, ohjelma muuntaa tapahtumat paikallista valuuttaa (USD) käyttäen. Vaikka asianmukaisten valuuttojen vaihtokurssit ovat kiinteät (esimerkiksi Yhdysvaltain dollarin ja euron välillä), pieniä jäännössummia saattaa esiintyä, kun ohjelma muuntaa nämä ulkomaan valuutat USD:ksi. Ohjelma kirjaa nämä pienet jäännössummat voitoiksi ja tappioiksi **Valuutat**-ikkunan **Realisoitun. val.voitt. tili**- ja **Realisoitun. val.tapp. tili** -kentissä määritetyille tileille. **Summa (USD)** -kenttää muokataan myös asianmukaisten toimittajatapahtumien mukaan.

## <a name="to-unapply-an-application-of-customer-entries"></a>Asiakkaan tapahtumien kohdistuksen peruuttaminen
Kun tehdään virheellinen kohdistus, ohjelma luo ja kirjaa korjaavat tapahtumat (eli tapahtumat, jotka ovat alkuperäisten tapahtumien kanssa identtisiä mutta joiden summakentässä on vastakkainen etumerkki) kaikille tapahtumille, myös kaikille kohdistuksesta johdetuille KP-kirjauksille, kuten maksualennuksille ja valuuttavoitoille- tai tappioille. Ohjelma avaa uudelleen kohdistuksen sulkemat tapahtumat.

1. Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Asiakkaat** ja valitse sitten aiheeseen liittyvä linkki.
2. Avaa haluamasi asiakkaan kortti.
3. Valitse **Tapahtumakirjaukset**-toiminto.
4. Valitse haluamasi tapahtuma ja valitse sitten **Peruuta kohdistus** -toiminto.
5. Vaihtoehtoisesti voit valita **Yksityiskoht. tapahtumat.** -toiminnon.
6. Valitse haluamasi kohdistustapahtuma ja valitse sitten **Peruuta kohdistus** -toiminto.
7. Täytä pyyntöikkunan kentät ja valitse sitten **Peruuta kohdistus** -painike.

**Tärkeää**: Jos tapahtumaan on tehty useita kohdistuksia, on viimeisin kohdistustapahtuma poistettava ensin.

## <a name="see-also"></a>Katso myös
[Myyntisaamisten hallinta](receivables-manage-receivables.md)  
[Myynnin hallinta](sales-manage-sales.md)

