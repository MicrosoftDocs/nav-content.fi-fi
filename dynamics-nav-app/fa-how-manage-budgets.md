---
title: "Toimintaohje: Käyttöomaisuuden budjettien hallinta"
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
ms.openlocfilehash: 47b5e0abcae4fab92da5dd9c1bda350a37ec0358
ms.contentlocale: fi-fi
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-manage-budgets-for-fixed-assets"></a>Toimintaohje: Käyttöomaisuuden budjettien hallinta
Voit määrittää budjetoidun käyttöomaisuuden. Tämän ansiosta raportteihin voidaan sisällyttää mitä tahansa ennakoituja hankintoja ja myyntejä.  

 Budjetoidun tuloslaskelman, budjetoidun taseen ja rahoitusbudjetin valmistelua varten tarvitaan tietoja käyttöomaisuuden tulevista investoinneista, luovutuksista ja poistoista. Nämä tiedot saa **Käyttöomaisuus – Suunnit. arvo** -raportista. Ennen kyseisen raportin tulostamista budjetti tulee valmistella.  

## <a name="to-budget-the-acquisition-cost-of-a-fixed-asset"></a>Käyttöomaisuuden hankintamenon budjetointi
Budjetin valmistelemista varten tulee määrittää käyttöomaisuuden kortteja käyttöomaisuuserille, joita aiot ostaa tulevaisuudessa. Budjettikäyttöomaisuuserät määritetään tavallisina käyttöomaisuuserinä, mutta ne on määritettävä niin, että pääkirjanpitoon ei tehdä kirjauksia.

Kun kirjaat hankintamenon, syötä budjetoidun käyttöomaisuuserän numero **Budjetoidun KO:n nro** -kentässä. Tämä aiheuttaa sen, että ohjelma kirjaa hankintamenon, jolla on vastakkainen etumerkki, budjetoidulle käyttöomaisuudelle. Tämä tarkoittaa sitä, että budjetoidun käyttöomaisuuden kokonaishankintameno on budjetoidun ja todellisen hankintamenon välinen ero.

1. Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Käyttöomaisuus** ja valitse sitten aiheeseen liittyvä linkki.
2. Valitse **Uusi**-toiminto, kun haluat luoda uuden käyttöomaisuuskortin budjetoitua käyttöomaisuutta varten.
3. Valitse **Budjetoitu käyttöomaisuus** -valintaruutu, kun haluat estää kirjauksen pääkirjanpitoon.
4. Täytä jäljellä olevat kentät, liitä poistokirja ja kirjaa ensimmäinen hankintameno ja budjetoitu käyttöomaisuus, joka on syötetty **Budjetoidun KO:n nro** -kenttään päiväkirjarivillä. Lisätietoja on kohdassa [Toimintaohje: Käyttöomaisuuden hankinta](fa-how-acquire.md).

## <a name="to-budget-the-disposal-of-a-fixed-asset"></a>Käyttöomaisuuden luovutuksen budjetointi
Jos suunnittelet myyväsi omaisuutta budjettijaksolla, voit syöttää tietoja myyntihinnasta ja myyntipäivämäärästä.

1. Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Käyttöomaisuus** ja valitse sitten aiheeseen liittyvä linkki.
2. Valitse luovutettava käyttöomaisuus ja valitse sitten **Poistokirjat**-toiminto.
3. Lisää sisältö **KO:n poistokirja**-ikkunassa **Suunnit. luovut. saadut tulot**-kenttään ja **Suunniteltu luovutuspvm** -kentän sisältö. Lue kentän lyhyt kuvaus valitsemalla kenttä tai siirry lisätietoihin valitsemalla linkki.

## <a name="to-view-projected-disposal-values"></a>Suunniteltujen luovutusarvojen katsominen
**KO:n suunniteltu arvo** -raportissa voi tarkastella suunniteltuja luovutusarvoja ja laskea voittoja ja tappioita.

1. Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **KO:n suunniteltu arvo** ja valitse sitten aiheeseen liittyvä linkki.
2. Täytä tarvittavat kentät.
3. Valitse **Tulosta**- tai **Esikatsele**-painike.

## <a name="to-budget-depreciation"></a>Poistojen budjetointi
Laske tuleva poisto **Käyttöomaisuus - Suunnit. arvo** -raportin avulla. Raportissa näkyvät kirjanpitoarvo ja kumulatiiviset poistot valitun ajanjakson alusta, jakson aikaiset muutokset sekä kirjanpitoarvo ja kumulatiiviset poistot valitun ajanjakson lopusta.

1. Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **KO:n suunniteltu arvo** ja valitse sitten aiheeseen liittyvä linkki.
2. Täytä tarvittavat kentät.
3. Kun haluat nähdä kaikkien käyttöomaisuuserien kokonaisarvot, tyhjennä **Tulosta KO-erittäin** -valintaruutu.
4. Jätä **Käyttöomaisuus**-pikavälilehti tyhjäksi sisällyttääksesi kaikki omaisuuserät. **Budjetoitu käyttöomaisuus** -kenttään syötetään **Ei**, kun budjetoidut käyttöomaisuuserät jätetään huomioimatta, ja **Kyllä**, kun tarkastellaan vain budjetoituja käyttöomaisuuseriä.
5. Valitse **Tulosta**- tai **Esikatsele**-painike.

## <a name="see-also"></a>Katso myös
[Käyttöomaisuuden hallinta](fa-manage.md)  
[Käyttöomaisuuserien määrittäminen](fa-setup.md)  
[Rahoitus](finance-setup.md)  
[Tervetuloa Dynamics NAV -ohjelmaan](across-get-started.md)

