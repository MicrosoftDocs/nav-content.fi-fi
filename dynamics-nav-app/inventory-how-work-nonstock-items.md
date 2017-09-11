---
title: "Toimintaohje: Ei-varastoitavien nimikkeiden käsitteleminen"
author: SorenGP
ms.custom: na
ms.date: 09/29/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 6b60b1344a1e18ad91863046110df880f75f7c04
ms.openlocfilehash: 6d99e06c167d3b86db97883c02c8bf5cd746ae10
ms.contentlocale: fi-fi
ms.lasthandoff: 07/19/2017

---

# Toimintaohje: Ei-varastoitavien nimikkeiden käsitteleminen
Voit tarjota asiakkaille tiettyjä nimikkeitä, joita et halua varastoida ennen kuin niitä myydään. Kun haluat alkaa varastoida tällaisia nimikkeitä, voit muuntaa ne normaaleiden nimikkeiden korteiksi kahdella eri tavalla.

- Luo ei-varastoitavan nimikkeen kortille uusi nimikekortti mallin mukaan.
- Valitse ei-varastoitava nimike myyntitilausriviltä, jolla on tyhjä **Nimike**-kenttä. Kun kirjaat myynnin, ei-varastoitavalle nimikkeelle luodaan automaattisesti nimikekortti.

**Huomautus**: Ei-varastoitavaa nimikettä ei voi valita **Myyntilasku** -ikkunassa. Voit valita ei-varastoitavan nimikkeen **Myyntitarjous**-ikkunassa, mutta ei-varastoitavaa nimikettä ei muunneta normaaliksi nimikkeeksi, jos käytössä on **Tee tilaus** -toiminto.

Ei-varastoitavalla nimikkeellä on yleensä sen toimittavan toimittajan nimikenumero. Voit ottaa ei-varastoitavan nimikkeen kortin muuntamisen käyttöön normaalin nimikkeen kortille määrittämällä ensin, miten toimittajan nimikenumerointi muunnetaan omaksi nimikenumeroinniksesi.   

## Ei-varastoitavan nimikkeen luominen
Ei-varastoitavien nimikkeiden korteissa on paljon vähemmän tietoja kuin normaalien nimikkeiden korteissa, koska niitä käytetään tarjouksissa ja tehtäessä muita tilauksia. Tämän vuoksi ne on muunnettava normaaleiden nimikkeiden korteiksi, ennen kuin niille voidaan kirjata myyntitapahtumat.

1. Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Ei-varastoitavat nimikkeet** ja valitse sitten aiheeseen liittyvä linkki.
2. Valitse **Uusi**-toiminto.
2. Täytä tarvittavat kentät. Lue kentän lyhyt kuvaus valitsemalla kenttä tai siirry lisätietoihin valitsemalla linkki.

## Määritetään, miten ei-varastoitavat nimikenumerot muunnetaan omaksi numeroinniksi  
Voit ottaa ei-varastoitavan nimikkeen kortin muuntamisen käyttöön normaalin nimikkeen kortille määrittämällä ensin, miten toimittajan nimikenumerointi muunnetaan omaksi numeromuodoksi.

1. Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Ei-varastoitavan nimikkeen määritys** ja valitse sitten aiheeseen liittyvä linkki.
2. Täytä tarvittavat kentät.

## Ei-varastoitavan nimikkeen muuntaminen normaaliksi nimikkeeksi
1. Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Ei-varastoitavat nimikkeet** ja valitse sitten aiheeseen liittyvä linkki.
2. Avaa sen ei-varastoitavan nimikkeen kortti, jonka haluat muuntaa normaaliksi nimikkeeksi.
3. Valitse **Ei-varastoitavan nimikkeen kortti**-ikkunassa **Luo nimike** -toiminto.

Luodaan uusi nimikekortti, johon on täytetty ei-varastoitavan nimikkeen tiedot, ja asiaankuuluva nimikemalli. Tämän jälkeen voit täyttää uuden nimikekortin kentät tai muokata niitä tarvittaessa. Lisätietoja on kohdassa [Toimintaohje: Uusien tuotteiden rekisteröiminen](inventory-how-register-new-products.md).

## Ei-varastoitavan nimikkeen myyminen ja muuntaminen normaaliksi nimikkeeksi
1. Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Myyntitilaukset** ja valitse sitten aiheeseen liittyvä linkki.
2. Valitse **Uusi**-toiminto. Täytä **Yleinen**-pikavälilehden kentät samalla tavalla kuin myyntitilauksen kentät.
3. Jätä uuden myyntirivin **Nimike**-kenttä tyhjäksi ja valitse **Rivi** ja **Toiminnot** ja **Ei-varastoitavat nimikkeet**.

    Ei-varastoitava nimike muunnetaan normaaliksi nimikkeeksi. Luodaan uusi nimikekortti, johon on täytetty ei-varastoitavan nimikkeen tiedot, ja asiaankuuluva nimikemalli.
4. Valitse **Ei-varastoitavat nimikkeet** -ikkunassa ei-varastoitava nimike, jonka haluat myydä, ja valitse sitten **OK**-painike.
5. Kun myyntitilaus on valmis, valitse **Kirjaa**-toiminto.

Tämän jälkeen voit täyttää uuden nimikekortin kentät tai muokata niitä tarvittaessa. Lisätietoja on kohdassa [Toimintaohje: Uusien tuotteiden rekisteröiminen](inventory-how-register-new-products.md).

**Huomautus**: Toimittajalle luodaan automaattisesti nimikkeen viittaustietue nimikkeelle, jonka numero on toimittajan nimikenumeron ja uuden nimikenumeron välissä.

## Katso myös
[Toimintaohje: Uusien tuotteiden rekisteröiminen](inventory-how-register-new-products.md)  
[Varaston hallinta](inventory-manage-inventory.md)  
[Dynamics NAV -ohjelman käyttäminen](ui-work-product.md)

