---
title: "Toimintaohje: Käyttöomaisuuden vakuutuksen määrittäminen"
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
ms.openlocfilehash: 44bb5f20702a01d9fbbc025889ec2bc3191813be
ms.contentlocale: fi-fi
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-set-up-fixed-asset-insurance"></a>Toimintaohje: Käyttöomaisuuden vakuutuksen määrittäminen
Voit hallita käyttöomaisuuden vakuutuksen kattavuutta, kun määrität ensin joitakin sopimusta koskevia yleisiä vakuutustietoja sekä vakuutuskortin.

## <a name="to-set-up-general-insurance-information"></a>Yleisten vakuutustietojen määrittäminen  
Jotta vakuutusominaisuuksia voitaisiin käyttää Dynamics NAV -ohjelmassa, tulee määrittää joitain yleisiä vakuutustietoja.  
1. Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **KO-asetukset** ja valitse sitten aiheeseen liittyvä linkki.  
2. Täytä tarvittavat kentät. Lue kentän lyhyt kuvaus valitsemalla kenttä tai siirry lisätietoihin valitsemalla linkki.  

## <a name="to-set-up-insurance-types"></a>Vakuutustyyppien määrittäminen  
Voit ryhmitellä vakuutussopimukset luokkiin, esimerkiksi vakuutukset varkauksia vastaan ja vakuutukset tulipaloa vastaan. Vakuutustyyppejä käytetään vakuutuskortissa.
1. Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Vakuutuslajit** ja valitse sitten aiheeseen liittyvä linkki.  
2. Täytä tarvittavat kentät.

## <a name="to-set-up-insurance-cards"></a>Vakuutuskorttien määrittäminen  
Vakuutuskorttiin voi kerätä tietoja kustakin vakuutussopimuksesta.  
1. Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Vakuutus** ja valitse sitten aiheeseen liittyvä linkki.  
2. Luo uusi vakuutuskortti valitsemalla **Vakuutus**-ikkunassa **Uusi**-toiminto.  
3. Täytä tarvittavat kentät.

## <a name="to-set-up-insurance-journal-templates"></a>Vakuutuspäiväkirjamallien määrittäminen  
Dynamics NAV luo automaattisesti vakuutuspäiväkirjan mallin, kun avaat **Vakuutuspäiväkirja**-ikkunan ensimmäisen kerran. Voit kuitenkin määrittää lisää päiväkirjamalleja. Lisätietoja on kohdassa [Yleisten päiväkirjojen käyttäminen](ui-work-general-journals.md).  
1. Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Vakuutuspäiväkirjan mallit** ja valitse sitten aiheeseen liittyvä linkki.  
2. Täytä tarvittavat kentät.

## <a name="to-set-up-insurance-journal-batches"></a>Vakuutuspäiväkirjaerien määrittäminen  
Vakuutuspäiväkirjan mallin alla voidaan määrittää eriä. Päiväkirjaerän arvoja käytetään oletusarvoina, jos päiväkirjarivien kenttiä ei täytetä. Lisätietoja on kohdassa [Yleisten päiväkirjojen käyttäminen](ui-work-general-journals.md)  
1. Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Vakuutuspäiväkirjan mallit** ja valitse sitten aiheeseen liittyvä linkki.  
2. Valitse vakuutuspäiväkirjamalli ja valitse sitten **Erät**-toiminto.
3. Täytä **Vakuutuspäiväkirjan erät** -ikkunassa tarvittavat kentät.

**HUOMAUTUS**: Numeroilla on päiväkirjan nimissä erityistehtävä. Jos päiväkirjamallin nimessä tai päiväkirjaerän nimessä on numero, numero suurenee automaattisesti yhdellä joka kerta, kun päiväkirja kirjataan. Esimerkiksi jos **Nimi**-kenttään syötetään HH1, päiväkirjan nimi muuttuu HH2:ksi sen jälkeen, kun päiväkirja, jonka nimi on HH1, on kirjattu.

## <a name="see-also"></a>Katso myös
[Käyttöomaisuuserien määrittäminen](fa-setup.md)  
[Käyttöomaisuuden hallinta](fa-manage.md)  
[Rahoitus](finance-setup.md)  
[Tervetuloa Dynamics NAV -ohjelmaan](across-get-started.md)

