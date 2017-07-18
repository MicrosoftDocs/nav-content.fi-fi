---
title: Numerosarjojen luominen
author: SusanneWindfeldPedersen
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 22b3bcf71c99e106527d6bfa35478045d29b9629
ms.contentlocale: fi-fi
ms.lasthandoff: 06/26/2017

---

# <a name="create-number-series"></a>Numerosarjojen luominen

Jokaiselle yritykselle on määritettävä ainutkertaiset tunnuskoodit esimerkiksi pääkirjanpidon tilejä, asiakas- ja toimittajatilejä, laskuja ja asiakirjoja varten. Numerointi ei ole tärkeää pelkästään tunnistamisen kannalta. Hyvin suunniteltu numerointijärjestelmä helpottaa myös yrityksen hallittavuutta ja analysointia ja voi vähentää tietojen syötössä tapahtuvien virheiden määrää.

Voit määrittää täydellisen numerointijärjestelmän, jossa on rajoittamaton määrä numerosarjoja. Numerosarjoja voi käyttää kaikentyyppisille asiakirjoille ja päiväkirjoille sekä perustiedoille, kuten asiakkaille, nimikkeille ja projekteille.

Voit yhdistää numerosarjojen käytön manuaaliseen numerointiin.

Numerointijärjestelmä luodaan määrittämällä koodeja kullekin perustietotyypille tai asiakirjalle. Voit määrittää koodin esimerkiksi asiakkaiden, myyntilaskujen ja yleisten päiväkirjojen numerointia varten.

Kun olet määrittänyt koodin, sinun on määritettävä vähintään yksi numerosarjarivi. Numerosarjarivit sisältävät erilaisia tietoja, kuten sarjan ensimmäisen ja viimeisen numeron sekä alkupäivämäärän. Voit määrittää yhtä numerosarjakoodia kohti useita numerosarjarivejä, joilla kullakin on eri alkupäivämäärä. Numerosarjoja käytetään peräkkäin kulloisestakin alkupäivämäärästä alkaen.

Jos haluat käyttää useita numerosarjakoodeja yhdelle perustietotyypille (esimerkiksi silloin, kun haluat eri numerosarjoja eri nimikeluokille), voit käyttää numerosarjasuhteita.

Manuaalisesti tai numerointijärjestelmän avulla määrittämiesi numeroiden lisäksi kaikille tapahtumille määritetään automaattisesti peräkkäiset numerot. Nämä luvut voidaan nähdä **Tapahtumanro.**-kentässä kaikissa tapahtumaikkunoissa. Tapahtumanumeroita ei voi muokata tai poistaa.

## <a name="to-create-relationships-between-number-series"></a>Numerosarjojen suhteiden luonti
Jos tietylle perustiedolle tai tapahtumalle on luotu useampia numerosarjoja, näiden koodien välille voidaan luoda suhteita. Tämä toiminto auttaa koodien valinnassa kun käytetään numeroa.

1. Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Nrosarja** ja valitse sitten aiheeseen liittyvä linkki.
2. Valitse numerosarjoja sisältävä rivi, jolle haluat luoda suhteita. Valitse sitten **Suhteet**.
3. Kirjoita **Sarjakoodi**-kenttään sen numerosarjan koodi, johon haluat luoda suhteen vaiheessa 2 valitusta sarjasta.
4. Lisää rivi kullekin valittuun numerosarjaan liitettävälle koodille.
5. Sulje ikkuna.

Kun tarvitset numeron voit käyttää niitä suhteita, joita on luotu numerosarjojen valitsemiseksi.

## <a name="see-also"></a>Katso myös
[Dynamics NAV -ohjelman käyttäminen](ui-work-product.md)

