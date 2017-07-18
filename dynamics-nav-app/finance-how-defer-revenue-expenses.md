---
title: "Toimintaohje: Tuottojen ja kulujen siirtäminen"
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
ms.openlocfilehash: 865bc307e8635b5a5aba11b5bc2e2e448c05e769
ms.contentlocale: fi-fi
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-defer-revenues-and-expenses"></a>Toimintaohje: Tuottojen ja kulujen siirtäminen
Jos haluat tulouttaa tuoton tai kulun jaksoon, joka on eri kuin se, jonka aikana tapahtuma on kirjattu, käytä toimintoja, jotka siirtävät tuotot ja kulut automaattisesti tietyn aikataulun mukaan.

Voit jakaa tuotot tai kulut liittyville kirjanpitojaksoille määrittämällä sille resurssille, nimikkeelle tai KP-tilille siirtomallin, jolle tuotto tai kulu kirjataan. Kun kirjaat liittyvän myynti- tai ostoasiakirjan, tuotto tai kulu siirretään liittyville kirjanpitojaksoille sen siirron aikataulun mukaan, jota siirtomallin ja kirjauspäivämäärän asetukset koskevat.

## <a name="to-set-up-a-gl-account-for-deferral"></a>KP-tilin määrittäminen siirtoa varten
1. Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Tilikartta** ja valitse sitten aiheeseen liittyvä linkki.
2. Valitse **Uusi**-toiminto.
3. Luo siirretyille tuotoille KP-tili täyttämällä tarvittavat kentät. Lisätietoja on kohdassa [Pääkirjanpito ja tilikartta](finance-setup-general-ledger.md).
3. Luo siirretyille kuluille uusi KP-tili toistamalla vaiheet 2 ja 3.

Valitse kummallekin siirtotyypille **Tase** **Tyyppi**-kenttään. Anna tileille soveltuvat nimet, kuten esimerkiksi siirretyille tuotoille Ansaitsematon tulo ja siirretyille kuluille Maksamattomat kulut.

## <a name="to-set-up-a-deferral-template"></a>Siirtomallin määrittäminen
1. Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Siirtomallit** ja valitse sitten aiheeseen liittyvä linkki.
2. Valitse **Uusi**-toiminto.
3. Täytä tarvittavat kentät.
4. Määritä **Laskentamenetelmä**-kenttään, miten **Siirron aikataulu** -ikkunan kunkin jakson **Summa**-kentän arvo lasketaan. Voit valita seuraavista vaihtoehdoista:
    - **Tasapoisto**: Jaksoittaiset siirtosummat lasketaan jaksojen lukumäärän mukaan. Ne jaetaan jakson pituuden mukaan.
    - **Tasan jaksoittain**: Jaksoittaiset siirtosummat lasketaan jaksojen lukumäärän mukaan. Ne jaetaan tasan kaikille jaksoille.
    - **Päivät jaksoittain**: Jaksoittaiset siirtosummat lasketaan jakson päivien lukumäärän mukaan.
    - **Käyttäjän määrittämä**: Jaksottaisia siirtosummia ei lasketa. Siirron aikataulu -ikkunan kunkin jakson Summa-kenttä on täytettävä manuaalisesti. Lisätietoja on Siirron aikataulun muuttaminen myyntilaskusta -osassa.

5. Määritä **Jakson kuvaus** -kenttään kuvaus, joka näytetään siirron kirjauksen tapahtumissa. Voit syöttää tyypillisille arvoille seuraavat paikanvaraajien koodit. Ne lisätään automaattisesti, kun jakson kuvaus näytetään.
    - %1 = jakson kirjauspäivämäärän päivän numero
    - %2 = jakson kirjauspäivämäärän viikon numero
    - %3 = jakson kirjauspäivämäärän kuukauden numero
    - %4 = jakson kirjauspäivämäärän kuukauden nimi
    - %5 = jakson kirjauspäivämäärän kirjanpitojakson nimi
    - %6 = jakson kirjauspäivämäärän tilikausi

Esimerkki: Kirjauspäivämäärä on 6.2.2016. Jos syötät Kulut siirretty: %4 %6, näytettävä kuvaus on Kulut siirretty: helmikuu 2016.

## <a name="to-assign-a-deferral-template-to-an-item"></a>Siirtomallin määrittäminen nimikkeelle
1. Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Siirtomallit** ja valitse sitten aiheeseen liittyvä linkki.
2. Avaa sen nimikkeen kortti, jonka tuotot tai kulut on siirrettävä kirjanpitojaksoille nimikkeen myynnin tai oston yhteydessä.
3. Valitse **Oletussiirtomalli**-kenttään sopiva siirtomalli.

## <a name="to-change-a-deferral-schedule-from-a-sales-invoice"></a>Siirtomallin muuttaminen myyntilaskusta
**Huomautus**: Tämän menettelytavan vaiheet ovat samat kuin vaiheet silloin, kun kulun siirtomalli muutetaan ostolaskusta.

1. Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Myyntilaskut** ja valitse sitten aiheeseen liittyvä linkki.
2. Luo myyntilasku nimikkeestä, jolle on määritetty siirtomalli. Lisätietoja on kohdassa [Toimintaohje: Myynnin laskuttaminen](sales-how-invoice-sales.md).

    Huomaa, että heti, kun laskuriville on syötetty nimike (tai resurssi tai KP-tili), ohjelma syöttää **Siirron koodi** -kenttään määritetyn siirtomallin koodin.
3. Valitse **Siirron aikataulu** -toiminto.
4. Muuta **Siirron aikataulu** -ikkunan otsikon tai rivin arvojen asetuksia. Voit esimerkiksi siirtää summan lisäkirjanpitojaksoon.
5. Valitse **Laske aikataulu** -toiminto.
6. Valitse **OK**-painike. Myyntilaskun siirron aikataulu päivitetään. Liittyvää siirtomallia ei muuteta.

## <a name="to-preview-how-deferred-revenues-or-expenses-will-be-posted-to-the-general-ledger"></a>Siirrettyjen tuottojen tai kulujen kirjanpitoon kirjaamisen tarkasteleminen
**Huomautus**: Tämän menettelytavan vaiheet ovat samat kuin kulujen siirtojen kirjausten esikatselun vaiheet.

1. Valitse **Myyntilasku** -ikkunassa **Esikatsele kirjaus** -toiminto.
2. Valitse **Esikatsele kirjaus** -ikkunassa **KP-tapahtuma**-toiminto ja valitse sitten **Näytä aiheeseen liittyvät tapahtumat** -toiminto.

Tietylle siirtotilille, kuten Ansaitsematon tulo -tilille, kirjattavat KP-tapahtumat merkitään kuvauksella, joka syötettiin siirtomallin **Jakson kuvaus** -kenttään. Esimerkki: Siirretyt kulut: helmikuu 2016.

## <a name="to-review-posted-deferrals-in-the-sales-deferral-summary-report"></a>Kirjattujen siirtojen tarkasteleminen Myynnin siirron yhteenveto -raportissa
**Huomautus**: Tämän menettelytavan vaiheet ovat samat kuin Ostojen siirron yhteenveto -raportin tarkastelun vaiheet.

1. Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Myynnin siirron yhteenveto** ja valitse sitten aiheeseen liittyvä linkki.
2. Syötä **Myynnin siirron yhteenveto** -ikkunan **Saldon tilanne** -kenttään päivämäärä, johon asti siirretyt tuotot näytetään.
3. Valitse **Esikatsele**-painike.

## <a name="see-also"></a>Katso myös
[Rahoitus](finance-setup.md)  
[Tärkeimpien talousprosessien määrittäminen](finance-setup-setup-finance-setup.md)  
[Toimintaohje: Yleisten päiväkirjojen käyttäminen](ui-work-general-journals.md)

