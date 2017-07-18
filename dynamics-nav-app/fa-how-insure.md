---
title: "Toimintaohje: Käyttöomaisuuden vakuuttaminen"
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
ms.openlocfilehash: a3a59bc091042f72775b56fdd5bbe37ffa1a6d80
ms.contentlocale: fi-fi
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-insure-fixed-assets"></a>Toimintaohje: Käyttöomaisuuden vakuuttaminen
Vakuutuskortti edustaa käyttöomaisuuden vakuutussopimusta. Voit liittää yhteen vakuutussopimukseen yhden käyttöomaisuuserän tai useita käyttöomaisuuseriä.

Voit liittää käyttöomaisuuserän vakuutussopimukseen kirjaamalla vakuutuksen kattavuustapahtuman **Vakuutuspäiväkirja**-ikkunasta.

Lisäksi voit liittää käyttöomaisuuserän vakuutussopimukseen ja luoda kattavuustapahtumia sen hankintamenon kirjaamisen yhteydessä. Tämä tehdään kirjaamalla käyttöomaisuuserän hankintameno niin, että **Vakuutusnro**-kenttä on täytetty. **Automaattinen vakuutuskirjaus** -valintaruutu **Käyttöomaisuuden asetukset** -ikkunassa on valittava. Lisätietoja on Käyttöomaisuuden hankinnan kirjaaminen manuaalisesti käyttöomaisuuden KP-päiväkirjan avulla -osan kohdassa [Toimintaohje: Käyttöomaisuuden hankinta](fa-how-acquire.md).

Jos **Automaattinen vakuutuskirjaus** -valintaruutua **Käyttöomaisuuden asetukset** -ikkunassa ei ole valittu, hankintojen kirjaaminen käyttöomaisuuspäiväkirjasta luo rivit **Vakuutuspäiväkirja**-ikkunaan. Rivit on tämän jälkeen kirjattava manuaalisesti.

**Varoitus**:Jos et valitse **Automaattinen vakuutuskirjaus** -valintaruutua **Käyttöomaisuuden asetukset** -ikkunassa, vakuutuspäiväkirjan on perustuttava sellaiseen päiväkirjan malliin, jolla ei ole numerosarjoja. Tämä johtuu siitä, että käyttöomaisuuspäiväkirjan rivistä lisätyt asiakirjanumerot ovat muussa tapauksessa ristiriidassa vakuutuspäiväkirjan numerosarjojen kanssa. Lisätietoja päiväkirjojen malleista ja eristä on kohdassa [Toimintaohje: Käyttöomaisuuden yleisten tietojen määrittäminen](fa-how-setup-general.md).

Kun käyttöomaisuus on liitetty vakuutussopimukseen, käyttöomaisuuden kortin **Vakuutettu**-valintaruutu valitaan. Kun myyt käyttöomaisuuden, valintaruudun valinta poistetaan automaattisesti.

## <a name="to-create-or-modify-an-insurance-card"></a>Vakuutuskortin luominen tai muokkaaminen
Vakuutuskortin on edustettava käyttöomaisuuden vakuutussopimusta.

Kun saat tiedon kattavuussumman muutoksista, uudet tiedot on syötettävä **Vakuutuskortti**-ikkunaan, jotta vakuutussopimuksen kattavuus voitaisiin analysoida oikein.  

1. Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Vakuutus** ja valitse sitten aiheeseen liittyvä linkki.
2. Valitse **Uusi**-toiminto, kun haluat luoda vakuutussopimukselle uuden kortin. Lue kentän lyhyt kuvaus valitsemalla kenttä tai siirry lisätietoihin valitsemalla linkki.
3. Vaihtoehtoisesti voit valita muutettavan vakuutussopimuksen ja valita sitten **Muokkaa**-toiminnon.

## <a name="to-assign-a-fixed-asset-to-an-insurance-policy-by-posting-from-the-insurance-journal"></a>Käyttöomaisuuden liittäminen vakuutussopimukseen vakuutuspäiväkirjasta kirjaamalla
Liitä käyttöomaisuus vakuutussopimukseen vakuutuksen kattavuustapahtumaan kirjaamalla.

Seuraavassa kerrotaan, miten vakuutuspäiväkirjan rivi luodaan manuaalisesti. Jos **Automaattinen vakuutuskirjaus** -valintaruutu on valittu **KO:n asetukset**-ikkunassa, vakuutuspäiväkirjan rivit luodaan automaattisesti hankintamenojen kirjaamisen yhteydessä. Tällöin ei tarvitse tehdä muuta kuin kirjata päiväkirja.

1. Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Vakuutuspäiväkirjat** ja valitse sitten aiheeseen liittyvä linkki.
2. Avaa kyseessä oleva päiväkirja ja täytä vaaditut päiväkirjarivit.
3. Voit liittää yhteen vakuutussopimukseen useita käyttöomaisuuseriä luomalla päiväkirjarivejä, joiden **Vakuutusnro**-kentässä on sama arvo ja eri arvot **KO-nro** -kentässä.
4. Valitse **Kirjaa**-toiminto.

**Huomautus**: Vakuutuspäiväkirjan tapahtumat kirjataan vain vakuutuksen kattavuuskirjauksiin.  

## <a name="to-update-the-insurance-value-of-a-fixed-asset"></a>Käyttöomaisuuden vakuutusarvon päivittäminen
**Tee indeksimuutos vakuutuksiin** -eräajoa voidaan käyttää päivittämään katetun käyttöomaisuuden arvoa.

1. Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Tee indeksimuutos vakuutuksiin** ja valitse sitten aiheeseen liittyvä linkki.
2. Täytä tarvittavat kentät.

    **Huomautus**: **Indeksiluku**-kenttään syötetään esimerkiksi 5 %:n pienentämistä varten 95, kun taas 2 %:n suurentamiseksi syötetään 102.  
3.  Valitse **OK**-painike.  

    Eräajo laskee uudeksi summaksi prosenttiosuuden vakuutetusta kokonaisarvosta **Vakuutustilastot**-ikkunan arvon mukaan. Tämän jälkeen luodaan rivi vakuutuspäiväkirjaan.  
4. Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Vakuutuspäiväkirjat** ja valitse sitten aiheeseen liittyvä linkki.
5. Avaa kyseinen vakuutuspäiväkirja, tarkista luodut arvot ja kirjaa ne vakuutuksen kattavuustapahtumiin.

## <a name="to-monitor-insurance-coverage"></a>Vakuutuksen kattavuuden valvonta
Dynamics NAV sisältää vakuutussopimusten analysoimiseen ja käyttöomaisuuserien yli- ja alivakuuttamisen määrittämiseen tarkoitettuja raportti- ja tilastotietoikkunoita.

### <a name="overview-of-insurance-policies"></a>Yleiskuva vakuutussopimuksista  
Saadaksesi yleiskuvan vakuutussopimuksista, voit esikatsella ja tulostaa **Vakuutus – Luettelo** -raportin, jossa näkyvät kaikki sopimukset sekä tärkeimmät vakuutuskorttien kentät.  

### <a name="insurance-coverage"></a>Vakuutuskattavuus
Tarkastele, mitä käyttöomaisuuseriä vakuutussopimukset kattavat ja millaisista summista on kyse, esikatselemalla tai tulostamalla **Vakuutus – Vakuut. arvo yht.** -raportin.

### <a name="overunder-coverage"></a>Yli-/alikattavuus
Voit tarkistaa käyttöomaisuuserien mahdollisen yli- tai alivakuuttamisen seuraavilla tavoilla:
- **Vakuutustilastot**-ikkuna. Jos **Ali-/ylivakuutus**-kentässä on positiivinen summa, käyttöomaisuus on ylivakuutettu. Negatiivinen summa tarkoittaa sitä, että se on alivakuutettu.
- **Käyttöomaisuustilastot**-ikkuna. Valitse **Kokonaisvakuutusarvo**-kenttä, kun haluat tarkastella **Vakuutuksen kattav.tapahtumat** -ikkunaa.  
- **Yli-/alikattavuus**-raportti.  
- **Vakuutusanalyysi**-raportti.

### <a name="uninsured-fixed-assets"></a>Vakuuttamaton käyttöomaisuus
Tarkastaaksesi, ettet ole unohtanut määritellä käyttöomaisuutta vakuutussopimukseen, voit tulostaa tai esikatsella **Vakuutus – Vakuuttamaton KO** -raportin. Tässä raportissa näkyvät käyttöomaisuuserät, joiden osalta ei ole kirjattu summia vakuutuksen kattavuustapahtumaan.

## <a name="to-view-insurance-coverage-ledger-entries"></a>Vakuutuksen kattavuustapahtumien katsominen
Vakuutuksen kattavuuskirjauksiin tehtyjä tapahtumia voi katsoa.  

1. Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Vakuutus** ja valitse sitten aiheeseen liittyvä linkki.  
2. Valitse haluamasi vakuutussopimus ja valitse sitten **Vakuutuksen kattav.tapahtumat** -toiminto.

## <a name="to-view-the-total-insurance-value-of-fixed-assets"></a>Käyttöomaisuuden kokonaisvakuutusarvon tarkasteleminen
Erityinen matriisi-ikkuna sisältää kunkin käyttöomaisuuserän vakuutussopimukselle rekisteröidyt vakuutusarvot, jotka saadaan vakuutukseen liittyvien kirjattujen summien tuloksena.

1. Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Vakuutus** ja valitse sitten aiheeseen liittyvä linkki.  
2. Valitse haluamasi vakuutussopimus ja valitse sitten **Vakuutusarvo KO-erää kohti** -toiminto.
3. Täytä tarvittavat kentät  
4. valitse **Näytä matriisi** -toiminto.  
5. Voit tarkastella perusteena olevia vakuutuksen kattavuustapahtumia valitsemalla arvon matriisista.

## <a name="to-correct-insurance-coverage-entries"></a>Vakuutuksen kattavuustapahtumien korjaaminen  
Jos käyttöomaisuus on liitetty virheelliseen vakuutussopimukseen, voit korjata sen luomalla kaksi uudelleenluokittelutapahtumaa vakuutuspäiväkirjasta.  

1. Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Vakuutuspäiväkirjat** ja valitse sitten aiheeseen liittyvä linkki.
2. Luo käyttöomaisuudelle yksi päiväkirjarivi ja korjaa vakuutussopimus, jonka **Summa**-kentän arvo on positiivinen.
3. Luo käyttöomaisuudelle toinen päiväkirjarivi ja virheellinen vakuutussopimus, jonka **Summa**-kentän arvo on negatiivinen.  
4. Valitse **Kirjaa**-toiminto.

Käyttöomaisuus irrotetaan virheellisestä vakuutussopimuksesta toisella rivillä ja liitetään oikeaan sopimukseen ensimmäisellä rivillä.

## <a name="see-also"></a>Katso myös
[Käyttöomaisuuden hallinta](fa-manage.md)  
[Käyttöomaisuuserien määrittäminen](fa-setup.md)  
[Rahoitus](finance-setup.md)  
[Tervetuloa Dynamics NAV -ohjelmaan](across-get-started.md)

