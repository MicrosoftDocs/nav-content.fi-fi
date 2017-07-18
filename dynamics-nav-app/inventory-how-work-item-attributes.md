---
title: "Toimintaohje: Nimikkeen määritteiden käsitteleminen"
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
ms.openlocfilehash: eaf539f1d4d00c2cd5679f39f29a3428e33ee1fd
ms.contentlocale: fi-fi
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-work-with-item-attributes"></a>Toimintaohje: Nimikkeen määritteiden käsitteleminen
Kun asiakkaat tekevät kyselyjä nimikkeestä kirjeenvaihdon tai integroidun verkkokaupan avulla, he voivat tehdä kyselyjä ominaisuuksien, kuten korkeuden ja vuosimallin, perusteella. Voit auttaa asiakasta määrittämällä nimikkeisiin erilaisia nimikkeen määritteen arvoja, joita voidaan käyttää nimikkeiden haussa.

Voit myös määrittää nimikkeen määritteitä nimikeluokkiin, jotka kohdistetaan nimikeluokkia käyttäviin nimikkeisiin. Lisätietoja on ohjeaiheessa [Toimintaohje: Nimikkeen luokitteleminen](inventory-how-categorize-items.md).

## <a name="to-create-item-attributes"></a>Nimikkeen määritteiden luominen
1. Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Nimikkeen määritteet** ja valitse sitten aiheeseen liittyvä linkki.
2. Valitse **Nimikkeen määritteet** -ikkunassa **Uusi**-toiminto.
3. Täytä **Nimikkeen määrite** -ikkunassa tarvittavat kentät. Lue kentän lyhyt kuvaus valitsemalla kenttä tai siirry lisätietoihin valitsemalla linkki.

**Huomautus**: Jos valitset **Asetus**-kohdan **Tyyppi**-kentässä, voit valita **Nimikkeen määritteen arvot** -toiminnon ja luoda nimikkeen määritteelle arvot. Lisätietoja on "Arvojen luominen nimikkeen määritteille, joiden tyyppi on Asetus" -osassa.  

## <a name="to-create-values-for-item-attributes-of-type-option"></a>Arvojen luominen nimikkeen määritteille, joiden tyyppi on Asetus
1. Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Nimikkeen määritteet** ja valitse sitten aiheeseen liittyvä linkki.
2. Valitse **Nimikkeen määritteet** -ikkunassa nimikkeen määrite, jonka tyyppi on Asetus ja jolle haluat määrittää arvot. Valitse sitten **Nimikkeen määritteen arvot** -toiminto.
3. Täytä **Nimikkeen määritteen arvot** -ikkunassa tarvittavat kentät. Lue kentän lyhyt kuvaus valitsemalla kenttä tai siirry lisätietoihin valitsemalla linkki.

## <a name="to-assign-item-attributes-to-items"></a>Nimikkeen määritteiden määrittäminen nimikkeille
1. Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Nimikkeet** ja valitse sitten aiheeseen liittyvä linkki.
2. Valitse **Nimikkeet**-ikkunassa nimike, jolle haluat määrittää nimikkeen määritteet. Valitse sitten **Määritteet**-toiminto.
3. Valitse **Nimikkeen määritteiden arvot** -ikkunassa **Uusi**-toiminto.
4. Valitse **Määrite**-kentässä AssistEdit-painike ja valitse aiemmin määritetty nimikkeen määrite. Vaihtoehtoisesti voit valita **Uusi**-toiminnon ja luoda ensin uuden nimikkeen määritteen "Nimikkeen määritteiden luominen" -osassa esitetyllä tavalla.
5. Syötä **Arvo**-kenttään nimikkeen määritteen arvo, kuten "2010", kun kyseessä on Mallivuosi-määrite.
6. Valitse nimikkeen määritteille, joiden tyyppi on Asetus, **Arvo**-kentän AssistEdit-painike. Valitse sitten nimikkeen määritteen arvo. Vaihtoehtoisesti voit valita **Uusi**-toiminnon ja luoda ensin uuden nimikkeen määritteen arvon "Arvojen luominen nimikkeen määritteille, joiden tyyppi on Asetus" -osassa esitetyllä tavalla.
7. Toista vaiheet 4–6 kaikille niille nimikkeen määritteille, jotka haluat määrittää nimikkeeseen.

## <a name="to-assign-item-attributes-to-item-categories"></a>Nimikkeen määritteiden määrittäminen nimikeluokille
1. Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Nimikeluokat** ja valitse sitten aiheeseen liittyvä linkki.
2. Valitse **Nimikeluokat**-ikkunassa nimikeluokka, jolle haluat määrittää nimikkeen määritteet. Valitse sitten **Muokkaa**-toiminto.
3. Valitse **Nimikeluokkakortti**-ikkunan **Määritteet**-pikavälilehdessä **Uusi**-toiminto.
4. Valitse **Määrite**-kentässä AssistEdit-painike ja valitse aiemmin määritetty nimikkeen määrite. Vaihtoehtoisesti voit valita **Uusi**-toiminnon ja luoda ensin uuden nimikkeen määritteen "Nimikkeen määritteen luominen" -osassa esitetyllä tavalla.
5. Valitse **Oletusarvo**-kentässä AssistEdit-painike ja valitse nimikkeen määritteen arvo.
6. Toista vaiheet 4 ja 5 kaikille niille nimikkeen määritteille, jotka haluat määrittää nimikeluokkaan.

**Huomautus**: Päänimikeluokkien nimikkeen määritteet periytyvät alinimikeluokille. Tämä osoitetaan **Peritty kohteesta** -kentässä **Määritteet**-pikavälilehdessä. Lisätietoja on ohjeaiheessa [Toimintaohje: Nimikkeen luokitteleminen](inventory-how-categorize-items.md).

## <a name="to-filter-by-item-attributes"></a>Suodattaminen nimikkeen määritteiden mukaan
1. Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Nimikkeet** ja valitse sitten aiheeseen liittyvä linkki.
2. Valitse **Nimikkeet**-ikkunassa **Suodata määritteiden mukaan** -toiminto.
3. Valitse **Suodata nimikkeet määritteen mukaan** -ikkunassa **Määrite**-kentän AssistEdit-painike. Valitse sitten nimikkeen määrite.
4. Valitse **Arvo**-kentässä AssistEdit-painike ja valitse määritteen arvo, jonka mukaan nimikkeet suodatetaan.

    **Huomautus**: Voit valita arvot vain suoraan niille nimikkeen määritteille, joilla on kiinteät arvot (esimerkiksi väri). Jos nimikkeen määritteillä on muuttuvat arvot (kuten leveys), nimikkeen määritteen arvo on määritettävä valitsemalla ensin ehto. Katso vaihe 5.
5. Valitse muuttuvan nimikkeen määritteen **Arvo**-kentässä AssistEdit-painike.
6. Valitse **Määritä suodatusarvo** -ikkunassa **Ehto**-kentässä alanuolipainike ja valitse sitten ehto.
7. Syötä **Arvo**-kenttään määritteen arvo, jonka mukaan nimikkeet suodatetaan.

    **Esimerkki**: Voit suodattaa nimikkeet, joiden materiaalin kuvaus alkaa sanalla "sininen", täyttämällä kentät seuraavasti: **Määrite**-kenttä: Materiaalin kuvaus, **Ehto**-kenttä: Alkaa, **Arvo**-kenttä: sininen.
8. Valitse **OK**-painike.   

**Nimikkeet**-ikkunan nimikkeet suodatetaan määritettyjen nimikkeen määritteen arvojen mukaan.

## <a name="see-also"></a>Katso myös
[Toimintaohje: Nimikkeen luokitteleminen](inventory-how-categorize-items.md)    
[Toimintaohje: Uusien tuotteiden rekisteröiminen](inventory-how-register-new-products.md)  
[Varaston hallinta](inventory-manage-inventory.md)  
[Dynamics NAV -ohjelman käyttäminen](ui-work-product.md)

