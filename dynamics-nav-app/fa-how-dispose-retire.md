---
title: "Toimintaohje: Käyttöomaisuuden luovuttaminen tai poistaminen käytöstä"
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
ms.openlocfilehash: 795bb23e7c0b46be095b2bbdfe7705b3d7b1e4ee
ms.contentlocale: fi-fi
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-dispose-of-or-retire-fixed-assets"></a>Toimintaohje: Käyttöomaisuuden luovuttaminen tai poistaminen käytöstä
Kun myyt tai muuten luovutat käyttöomaisuuden, luovutusarvo on kirjattava voiton tai tappion laskemista ja tallentamista varten. Luovutustapahtuman tulee olla viimeinen tapahtuma, joka käyttöomaisuudelle on kirjattu. Osittain luovutetun käyttöomaisuuden osalta voidaan kirjata useampi kuin yksi luovutustapahtuma. Kaikkien kirjattujen luovutussummien kokonaissumman tulee olla kredit-summa.

 **HUOMAUTUS**: Jos käyttöomaisuuserä vaihdetaan toiseen, sekä vanhan käyttöomaisuuserän myynti (luovutus) että uuden käyttöomaisuuserän osto (hankinta) tulee tallentaa. Lisätietoja on kohdassa [Toimintaohje: Käyttöomaisuuden hankinta](fa-how-acquire.md).

## <a name="to-post-a-disposal-from-the-fixed-asset-gl-journal"></a>Luovutuksen kirjaaminen käyttöomaisuuden KP-päiväkirjasta  
1. Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **KO - KP-päiväkirjat** ja valitse sitten aiheeseen liittyvä linkki.  
2. Luo alkuperäisen päiväkirjan rivi ja täytä kentät tarpeen mukaan. Lue kentän lyhyt kuvaus valitsemalla kenttä tai siirry lisätietoihin valitsemalla linkki.
3. Valitse **KO:n kirjaustyyppi** -kentässä **Luovutus**.
4. Valitse **Syötä KO-vastatili** -toiminto. Toinen päiväkirjan rivi luodaan vastatilille, joka on määritetty luovutuksen kirjaamista varten.

    **Huomautus**: Vaihe 4 toimii vain, jos määritettynä ovat seuraavat arvot: Käyttöomaisuuden kirjausryhmän **KO:n kirjausryhmän kortti** -ikkunan **Luovutustili**-kenttä sisältää pääkirjanpidon debet-tilin ja **Luovutuksen vastatili** -kenttä sisältää sen pääkirjanpitotilin, jolle vastatilitapahtumien arvonkorotus kirjataan. Lisätietoja on "Käyttöomaisuuden kirjausryhmien määrittäminen" -osassa kohdassa [Toimintaohje: Käyttöomaisuuden yleisten tietojen määrittäminen](fa-how-setup-general.md).
5. Valitse **Kirjaa**-toiminto.

Jos myyt osan käyttöomaisuudesta tai muuten luovut osasta käyttöomaisuutta, omaisuuserä tulee jakaa ennen kuin luovutustransaktion voi tallentaa. Lisätietoja on kohdassa [Toimintaohje: Käyttöomaisuuden siirtäminen, jakaminen tai yhdistäminen](fa-how-trans-split-combine.md).

## <a name="to-view-disposal-ledger-entries"></a>Luovutustapahtumien katsominen  
Kun myyt tai luovutat käyttöomaisuutta, luovutusarvo kirjataan pääkirjanpitoon, jossa tulosta voi tarkastella.   

1. Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Käyttöomaisuus** ja valitse sitten aiheeseen liittyvä linkki.  
2. Valitse käyttöomaisuus, jonka tapahtumia haluat tarkastella. Valitse sitten **Poistokirjat**-toiminto.
3. Valitse poistokirja, jonka tapahtumia haluat tarkastella. Valitse sitten **Tapahtumakirjaukset**-toiminto.
4. Valitse **KO:n kirjausluokka** -kentässä rivi, joka sisältää **luovutuksen**. Valitse sitten **Navigoi**-toiminto.  
5. Valitse **Navigointi**-ikkunassa pääkirjanpidon tapahtuman rivi ja valitse sitten **Näytä**-toiminto.
Näyttöön tulee **Pääkirjanpidon tapahtumat** -ikkuna, jossa näkyvät tapahtumat, joiden tuloksena on luovutuksen kirjaaminen.

## <a name="see-also"></a>Katso myös
[Käyttöomaisuuden hallinta](fa-manage.md)  
[Käyttöomaisuuserien määrittäminen](fa-setup.md)  
[Rahoitus](finance-setup.md)  
[Tervetuloa Dynamics NAV -ohjelmaan](across-get-started.md)

