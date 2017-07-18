---
title: "Toimintaohje: Käyttöomaisuuden poiston määrittäminen"
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
ms.openlocfilehash: 7efc50c673514498de0caa5b3a2dc4b32d4f7f5d
ms.contentlocale: fi-fi
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-set-up-fixed-asset-depreciation"></a>Toimintaohje: Käyttöomaisuuden poiston määrittäminen
 Rahoituslaskelmien ja tuloveropalautusten valmistelussa voi käyttää useita poistomenetelmiä. Monet suuret yritykset käyttävät tasapoistoja rahoituslaskelmissaan, koska sen avulla voidaan yleensä raportoida suurempia tuloja. Tuloverotarkoituksia varten monet yritykset käyttävät kuitenkin degressiivistä poistomenetelmää. Lisätietoja on kohdassa [Poistotavat](fa-depreciation-methods.md).

 Kun olet luonut asianmukaiset poistokirjat, kuhunkin käyttöomaisuuserään tulee liittää yksi tai usea poistokirja. Käyttöomaisuuteen liitettyä poistokirjaa kutsutaan käyttöomaisuuden poistokirjaksi. Samaan tapaan liitettyjen poistokirjojen ikkuna on nimeltään **KO:n poistokirjat**.

## <a name="to-create-a-depreciation-book"></a>Poistokirjan luominen  
Käyttöomaisuuden poistokirjaan voidaan määrittää, miten käyttöomaisuus poistetaan. Useiden erilaisten poistomenetelmien hallitsemiseksi voidaan määrittää useita poistokirjoja.  
1.  Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Poistokirjat** ja valitse sitten aiheeseen liittyvä linkki.
2. Valitse **Poistokirjaluettelo**-ikkunassa **Uusi**-toiminto.
3. Täytä **Poistokirjakortti**-ikkunassa tarvittavat kentät. Lue kentän lyhyt kuvaus valitsemalla kenttä tai siirry lisätietoihin valitsemalla linkki.

    **Huomautus**: Voit tallentaa käyttöomaisuustapahtumat **Käyttöomaisuuden KP-päiväkirja**- tai **Käyttöomaisuuspäiväkirja**-ikkunaan riippuen siitä, koskevatko tapahtumat talousraportointia vai sisäistä hallintaa. Määritä seuraavan vaiheen mukaisesti eri käyttöomaisuustoiminnoissa oletusarvoisesti käytettävien päiväkirjojen tyypit.
4. Valitse **Integrointi**-pikavälilehdessä niiden käyttöomaisuustoimintojen valintaruudut, jotka haluat kirjata **Käyttöomaisuuden KP-päiväkirja** -ikkunan avulla.
5. Toista vaiheet 2–4 jokaisen sellaisen poisto- tai kirjaustavan kohdalla, jonka haluat liittää käyttöomaisuuserään poistokirjana.

## <a name="to-assign-a-depreciation-book-to-a-fixed-asset"></a>Poistokirjan liittäminen käyttöomaisuuteen  
1. Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Käyttöomaisuus** ja valitse sitten aiheeseen liittyvä linkki.
2. Valitse käyttöomaisuus, jolle haluat määrittää käyttöomaisuuden poistokirjan.
3. Täytä **Poistokirja**-pikavälilehden kentät tarvittaessa.
4. Jos käyttöomaisuuteen on liitettävä useita poistokirjoja, valitse **Lisää poistokirjoja** -toiminto.
5. Vaihtoehtoisesti voit valita **Poistokirjat**-toiminnon ja määrittää vähintään yhden käyttöomaisuuden poistokirjan.

**Huomautus**: Kun käytetään manuaalista poistomenetelmää, poistot tulee syöttää manuaalisesti käyttöomaisuuden KP-päiväkirjaan. **Laske poisto** -toiminto jättää huomiotta käyttöomaisuuserät, joille käytetään manuaalista poistomenetelmää. Tätä tapaa voidaan käyttää omaisuuserille, joille ei tehdä poistoja, kuten maa-alueille.

## <a name="to-assign-a-depreciation-book-to-multiple-fixed-assets-with-a-batch-job"></a>Poistokirjan liittäminen useisiin käyttöomaisuuseriin eräajon avulla
Jos haluat liittää poistokirjan moneen käyttöomaisuuteen, voit käyttää **Luo KO:n poistokirjat** -eräajoa, jolloin Dynamics NAV luo tarpeelliset käyttöomaisuuden poistokirjat automaattisesti.  
1. Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Käyttöomaisuus** ja valitse sitten aiheeseen liittyvä linkki.
2. Valitse käyttöomaisuus, jolle haluat määrittää ja liittää poistokirjan. Valitse sitten **Muokkaa**-toiminto.
3. Valitse **Poistokirjakortti**-ikkunassa **Luo KO:n poistokirjat** -toiminto.
4. Täytä **Luo KO:n poistokirjat** -ikkunan **Poistokirja**-kenttä.
5. Valitse **Kopioi KO:n nrosta** -kenttä ja valitse sen käyttöomaisuuserän numero, jota haluat käyttää pohjana luodessasi uusia käyttöomaisuuden poistokirjoja.

    Jos tämä kenttä täytetään, uusien KO-poistokirjojen poistokentissä on samat tiedot kuin kopioitavan KO-poistokirjan vastaavissa kentissä. Jätä kenttä tyhjäksi, jos haluat luoda uusia KO:n poistokirjoja, joissa on tyhjiä poistokenttiä.  
6. **Käyttöomaisuus**-pikavälilehteen voidaan asettaa suodatus valitsemaan se omaisuus, jolle halutaan luoda käyttöomaisuuden poistokirjat.
7. Valitse **OK**-painike.

## <a name="to-set-up-depreciation-posting-types"></a>Poiston kirjaustyyppien määrittäminen  
Kunkin poistokirjan osalta on määritettävä, miten Dynamics NAV -ohjelman tulee käsitellä eri kirjaustyyppejä. Voit esimerkiksi määrittää, että tuleeko kirjauksen olla debet vai kredit, ja tuleeko kirjaustyyppi sisällyttää poistopohjaan.  
1.  Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Poistokirjat** ja valitse sitten aiheeseen liittyvä linkki.  
2. Valitse poistokirja, jonka. Valitse sitten **KO:n kirjaustyypin asetukset** -toiminto.
3. Täytä **KO:n kirjaustyypin asetukset** -ikkunassa tarvittavat kentät.

**HUOMAUTUS**: **KO:n kirjaustyypin asetukset** -ikkunaan ei voi lisätä rivejä tai poistaa niitä. Ainoastaan olemassa olevia rivejä voi muuttaa.

On hyvin suositeltavaa, ettei niiden poistokirjojen asetuksia muuteta, joiden osalta on jo kirjattu tapahtumia. Muutokset eivät vaikuta jo kirjattuihin tapahtumiin, mikä tekee poistokirjatilastoista harhaanjohtavia.

## <a name="to-set-up-default-templates-and-batches-for-fixed-asset-depreciation"></a>Käyttöomaisuuden poiston oletusmallien ja -erien määrittäminen  
Kunkin poistokirjan osalta määritellään mallien ja erien oletusasetukset. Käytä näitä oletuksia:
- Monista rivejä päiväkirjasta toiseen.
- Luo päiväkirjarivejä **Laske poisto**- tai **Tee indeksimuutos KO:teen** -eräajoja käyttämällä.
- Monista hankintamenoja vakuutuspäiväkirjassa.

1. Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Poistokirjat** ja valitse sitten aiheeseen liittyvä linkki.
2. Valitse poistokirja, jolle haluat määrittää oletuspäiväkirjat. Valitse sitten **KO-päiväkirjan asetukset** -toiminto.
3. Jos haluat, että jokaisella käyttäjällä on oletusasetukset, valitse **Käyttäjätunnus**-kenttä, jotta voit tehdä valinnan **Käyttäjät**-ikkunassa.
4. Valitse muille kentille oletusarvoisesti käytettävä päiväkirjamalli tai -erä.

## <a name="see-also"></a>Katso myös
[Käyttöomaisuuserien määrittäminen](fa-setup.md)  
[Käyttöomaisuuden hallinta](fa-manage.md)  
[Rahoitus](finance-setup.md)  
[Tervetuloa Dynamics NAV -ohjelmaan](across-get-started.md)

