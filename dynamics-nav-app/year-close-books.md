---
title: "Kirjojen sulkemistehtävien yleiskatsaus"
description: "Tutustu prosesseihin, jolla tilikauden tai -jakson kirjat suljetaan, ja mitä tapahtuu, kun kirjat suljetaan vuoden lopussa."
documentationcenter: 
author: jswymer
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: year closing, close accounting period, close fiscal year, bank account detailed trial balance
ms.date: 03/29/2017
ms.author: jswymer
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: d709f8bfb5da3a0ebf5b44f3246fa3ccaa69c77f
ms.contentlocale: fi-fi
ms.lasthandoff: 10/16/2017

---
# <a name="closing-the-books"></a>Kirjojen sulkeminen
Kun olet varmistanut, että kaikki tilit ovat ajan tasalla, ja kohdistanut kustannukset ja tulot, voit sulkea tilikauden tai kirjanpitojakson kirjat.

Tilikautta ei ole pakko sulkea, mutta se helpottaa järjestelmän käyttöä, sillä silloin voit hyödyntää käteviä suodatusvaihtoehtoja. Tapahtumatietojen menettämisestä ei myöskään tarvitse huolehtia, sillä suljetun tilikauden kaikki tiedot säilyvät myös sulkemisen jälkeen.

## <a name="closing-book-process"></a>Kirjan sulkemisprosessi
Kirjan sulkemisprosessi sisältää seuraavat päätehtävät:

1. Kirjanpitojakson sulkeminen.

    Tilikausi koostuu **Kirjanpitojaksot**-ikkunassa määritetyistä avoimista jaksoista. Tyypillisesti tilikausi koostuu 12:sta kuukauden mittaisesta kaudesta, mutta tilikauden voi määrittää myös toisin.

    Lisätietoja on kohdassa [Toimintaohje: Kirjanpitojakson päättäminen](year-close-account-periods.md).
2. Edellisen vuoden tapahtumien rekisteröinti.

    Tilikautta suljettaessa on määritettävä erinäisiä hallinnallisia tapahtumia (kuten ennakkoon maksetut ja jaksotetut nimikkeet). Näitä tapahtumia kutsutaan oikaiseviksi tapahtumiksi. Näiden tapahtumien kirjaamista varten ei ole erityissääntöjä, ja niillä (kuten muillakin tapahtumilla) on valintamerkki **Edellisen vuoden tapahtuma** -kentässä, jos ne on kirjattu suljetun tilikauden päivämääränä. Vaikka tilikausi on suljettu, voit silti kirjata tilikaudelle KP-tapahtumia.
3. Saldojen siirtäminen tuloslaskelmatileiltä taseeseen.

    Kun tilikausi on suljettu ja kaikki edellisen vuoden tapahtumat on kirjattu, tuloslaskelmatilit on suljettava ja vuoden nettotuotto on siirrettävä taseeseen oman pääoman tilille. Käytä tätä tarkoitusta varten Sulje tuloslaskelma -eräajoa. Eräajo käsittelee kaikki Tuloslaskelma-tyyppiset kirjanpitotilit ja luo niiden saldojen vastatapahtumat. Nämä tapahtumat sijoitetaan päiväkirjaan, josta ne voi kirjata. Eräajo ei kirjaa niitä automaattisesti, ellei käytetä lisäraportointivaluuttaa. Käytettäessä lisäraportointivaluuttaa eräajo tekee kirjaukset suoraan pääkirjanpitoon.

    Lisätietoja on kohdassa [Tuloslaskelman sulkeminen](year-close-income-statement.md).
4. vuositilinpäätöstapahtuman kirjaaminen yhdessä kompensoivien pääomatilin tapahtumien kanssa.

    Kun Sulje tuloslaskelma -eräajo on valmis, voit kirjata ajon luomat tapahtumat. Jos et ole määrittänyt eräajon aikana jakamattoman voiton tiliä, lisää rivi, jolla on oikaiseva tapahtuma. Tapahtuma kirjaa nettotuoton oikealle kirjanpitotilille taseen omaan pääomaan. Kirjaa lopulta päiväkirja.

    Lisätietoja on kohdassa [Toimintaohje: Vuoden lopun tilinpäätöstapahtuman kirjaaminen](year-how-post-year-end-close-entry.md).

## <a name="what-happens-when-you-close"></a>Sulkemisen yhteydessä tapahtuvat asiat
Kun suljet tilikauden vuoden lopussa, järjestelmä siirtää voiton laskennallisesta voitosta jakamattoman voiton tilille. Järjestelmä myös merkitsee tilikauden suljetuksi ja kaikki myöhemmät suljetun vuoden tapahtumat edellisen vuoden tapahtumiksi.

Järjestelmä luo sitten tilinpäätöstapahtuman, mutta tapahtumaa ei merkitä automaattisesti. Saat mahdollisuuden tehdä kompensoivia pääomatilin tapahtumia, minkä ansiosta voit päättää, kuinka tilinpäätöstapahtuma kohdistetaan. Esimerkiksi jos yrityksessä on useita osastoja, voit antaa järjestelmän luoda yksittäisen tilinpäätöstapahtuman kaikille osastoille ja tehdä sitten kompensoivan tapahtuman kunkin osaston pääomatilille.

Voit tehdä kirjauksia edelliselle tilikaudelle myös tuloslaskelmatilien sulkemisen jälkeen suorittamalla Sulje tuloslaskelma -eräajon myöhemmin uudelleen.

## <a name="see-also"></a>Katso myös
[Toimintaohje: Uuden tilikauden avaaminen](finance-how-open-new-fiscal-year.md)  
[[!INCLUDE[d365fin](includes/d365fin_md.md)] -ohjelman käyttäminen](ui-work-product.md)

