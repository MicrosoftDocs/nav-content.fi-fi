---
title: 'Toimintaohje: Ennakoivien kassavirtaennusteiden tekeminen'
author: bholtorf
ms.custom: na
ms.date: 09/16/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: HT
ms.sourcegitcommit: b9b1f062ee6009f34698ea2cf33bc25bdd5b11e4
ms.openlocfilehash: 1fdb53b0f58ada22475fe1c1510146c156a60410
ms.contentlocale: fi-fi
ms.lasthandoff: 10/23/2017

---

# <a name="how-to-make-predictive-cash-flow-forecasts"></a>Toimintaohje: Ennakoivien kassavirtaennusteiden tekeminen
Kassavirtaennusteiden avulla voidaan varmistaa, että yrityksen kassa riittää taloudellisista velvoitteista vastaamiseen. Niiden avulla voidaan myös määrittää oikaisut. Kassavirtaennusteiden avulla esimerkiksi mahdollista käteisylijäämää voidaan käyttää velkojen maksuun. Ne myös osoittavat ajoissa, jos tiedossa on taloudellisia haasteita.

Cortana Intelligence käyttää Azuren automaattianalyysipalveluita luotettavien ja ennakoivien ennusteiden tekemisessä. Cortana Intelligencen ennusteiden avulla voit esimerkiksi ennustaa ja välttää kassavajeet. Palvelu yhdistää aiemmat tiedot osto- ja myyntireskontran nykyisiin kirjauksiin. Näihin kirjauksiin kuuluvat myös kirjaukset, joiden eräpäivät ovat tulevaisuudessa. Näitä kirjauksia ovat:
* Ostotilaukset
* Myyntitilaukset
* kirjatut myynti- ja ostolaskut
* hyvityslaskut

## <a name="before-you-start"></a>Ennen kuin aloitat  
Cortana Intelligencen käyttäminen kassavirtaennusteissa edellyttää joidenkin toimien suorittamista.
* Jos kassavirtaennusteet eivät ole vielä käytössä, seuraavat toiminnot on määritettävä:
    * Vähintään yksi **Kassavirran asetukset** -kohdan asetus.
    * Osto- ja myyntireskontran sekä myynti- ja ostotilausten tilit. Cortana Intelligence käyttää näiden tilien kirjauksia.
    * Vähintään yksi **Kassavirtaennuste**-kohdan kassavirtaennuste. Muista sisällyttää osto- ja myyntitilaukset sekä myynti- ja ostoreskontra lähteinä.  
    Saat lisätietoja hakemalla ohjejärjestelmästä _kassavirtaennusteita_.
* Ota selville käytettävän ennakoivan verkkopalvelun API:n URL-osoite ja API-avain.  
    Voit käyttää Azuren automaattianalyysipalveluita tai toista palvelua, jos sellainen on käytössä. Vaihtoehtoisesti Cortana Intelligencen valikoimassa on online-tilassa käytettävissä julkinen malli, jonka nimi on _Microsoft Dynamics NAV -ohjelman ennustemalli_. Voit käyttää mallia seuraavien vaiheiden avulla:

    1. Siirry selaimessa [Cortana Intelligencen valikoimaan](https://go.microsoft.com/fwlink/?linkid=828352)
    2. Hae _Microsoft Dynamics NAV -ohjelman ennustemalli_ ja avaa sitten malli Azure Machine Learning Studiossa.
    3. Kirjaudu työtilaan Microsoft-tilin avulla ja kopioi malli.
    4. Aja malli ja julkaise se verkkopalveluna.
    5. Kirjoita API:n URL-osoite ja API-avain muistiin. Cortana Intelligence määritetään [!INCLUDE[navnow](includes/navnow_md.md)] -ohjelmassa näiden tunnistetietojen avulla.  

* Mieti, miten usein ennuste lasketaan. Azuren automaattianalyysipalveluilla on rajoituksia käytöstä riippuen. Jos sinulla on esimerkiksi paljon nimikkeitä, laskelmia ei ehkä kannata tehdä kovin usein.
* Liity Kirjanpitäjä-roolikeskukseen.

## <a name="set-up-cortana-intelligence"></a>Cortana Intelligencen määrittäminen
Voit määrittää kassavirtaennusteet avustetun asennusoppaan avulla. Oppaan avulla voit määrittää esimerkiksi ennusteen päivitystiheyden, ennusteen perustana olevat tilit, verojen maksua koskevat tiedot ja sen, onko Cortana Intelligence käytössä.  

Jos kassavirtaennusteet ovat jo käytössä, ja haluat ottaa vain Cortana Intelligencen käyttöön, voit käyttää myös manuaalista prosessia. Kun kirjaudut sisään, työtilan yläosan siniseen palkkiin ilmestyy ilmoitus. Voit määrittää Cortana Intelligencen heti valitsemalla **Kyllä**. Sanoma näytetään vain kerran. Jos suljet sen, määritä Cortana Intelligence manuaalisen prosessin avulla.  

**Vihje:** Mieti, miten pitkiä jaksoja palvelun laskelmissa käytetään. Mitä enemmän tietoja on käytettävissä, sitä tarkempia ennusteet ovat. Varo myös suuria jaksovaihteluita. Ne vaikuttavat myös ennusteisiin. Jos Cortana Intelligence ei löydä riittävästi tietoja tai tiedot ovat kovin erilaisia, palvelu ei voi tehdä ennustetta.

Voit käyttää avustettua asennusopasta seuraavissa toiminnoissa:
1. Valitse Kirjanpitäjä-roolikeskuksen **Kassavirtaennuste**-kaavion **Avaa avustettu määritys** -toiminto.
2. Täytä oppaan eri vaiheissa tarvittavat kentät.

Voit käyttää manuaalista prosessia seuraavasti:
1. Hae **Kassavirran asetukset** ja valitse liittyvä linkki.
2. Laajenna **Cortana Intelligence** -pikavälilehti ja täytä tarvittavat kentät.

## <a name="turn-on-cortana-intelligence-for-cash-flow-forecasts"></a>Cortana Intelligencen ottaminen käyttöön kassavirtaennusteissa
1. Hae **Kassavirtaennusteet** ja valitse liittyvä linkki.
2. Valitse **Kassavirtatyökirja**-toiminto.
3. Valitse **Kassavirtatyökirja**-sivulla **Ehdota työkirjan rivejä** -toiminto.  
4. Valitse **Sisällytettävät lähdetyypit** -kohdan **Cortana Intelligence -ennuste** -valintaruutu.

## <a name="investigate-a-cash-flow-forecast"></a>Kassavirtaennusteen tutkiminen
**Cortana Intelligence** -sarakkeen avulla voit tarkastella ennusteen perustana olevat tiedot, kuten vaihtelun. Vaihtelu näytetään taulukon ensimmäisellä rivillä. Muut rivit järjestetään lähdeasiakirjan mukaan.  

Saat tietoja esimerkiksi siitä, miten ennuste    
* käsittelee vahvistetun myynnin ja ostot
* vähentää ostoreskontran ja lisää myyntireskontran
* ohittaa myynti- ja ostotilausten kaksoiskappaleet.

## <a name="see-also"></a>Katso myös  
[Dynamics NAV -ohjelman käsitteleminen](ui-work-product.md)

