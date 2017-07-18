---
title: Kausien sulkeminen
author: jswymer
ms.custom: na
ms.date: 09/16/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: ac1ed2d1dcf8bf780bda91fbf0a04e5c5e8d106a
ms.contentlocale: fi-fi
ms.lasthandoff: 06/26/2017

---
# <a name="close-periods"></a>Kausien sulkeminen
Sovellus ei pakota sulkemaan kausia. Sovelluksessa voidaan kuitenkin suorittaa useita kauden lopun (kuukauden lopun) toimenpiteitä. Tässä ohjeaiheessa on yrityksen käytettävissä olevien prosessien ja toimenpiteiden yleiskuvaus.

## <a name="general-ledger"></a>Pääkirjanpito
* Määritä järjestelmänlaajuinen ja käyttäjäkohtainen kirjausjakso.

    Tässä määritetään kirjausten sallittu päivämääräväli. Liiketoimintatarpeittesi mukaan haluat ehkä rajoittaa käyttäjän kirjauspäivämääräalueet kauden lopussa suoritettavan prosessin alussa tai myöhemmin jakson lopussa. Lisätietoja on kohdassa [Toimintaohje: Kirjausjaksojen määrittäminen](finance-setup-how-specify-posting-periods.md).
* Tee kaikki tarpeelliset KP-muutokset.
* Päivitä ja kirjaa toistuvat päiväkirjat.
<!--* Process Consolidations-->
* Suorita KP-raporttimallit seuraavasti:
  1. Avaa **KP-raporttimalli**-ikkuna ja valitse **Tulosta**-toiminto.
  2. Täytä **KP-raporttimalli**-pyyntöikkuna ja valitse **Tulosta**-toiminto.

## <a name="sales--receivables"></a>Myynnit ja myyntisaamiset
* Kirjaa kaikki myyntitilaukset, laskut, hyvityslaskut ja palautustilaukset.
* Kirjaa kaikki kassapäiväkirjat.
* Päivitä ja kirjaa myyntiin ja myyntisaamisiin liittyvät toistuvat päiväkirjat.
* Täsmäytä myyntisaatavat pääkirjanpitoon.
* Suorita **Poista laskutetut myyntitilaukset** -eräajo.

## <a name="purchases--payables"></a>Ostot ja ostovelat
* Kirjaa kaikki ostotilaukset, laskut, hyvityslaskut ja palautustilaukset.
* Kirjaa kaikki maksupäiväkirjat.
* Päivitä ja kirjaa ostoihin ja ostovelkoihin liittyvät toistuvat päiväkirjat.
* Suorita **Ostovelkojen tilanne** -raportti ja täsmäytä ostovelat pääkirjanpitoon.
* Suorita **Poista laskutetut ostotilaukset** -eräajo.

<!-- ### Fixed Assets
* Post all maintenance costs have been posted through the fixed asset journals or invoices.
* Post adjustments.
* Post appreciation.
* Post depreciation.
* Update and post the recurring fixed asset journal.-->

<!--### Intercompany
* Process Intercompany Postings.-->

## <a name="calculate-and-process-sales-tax"></a>Arvonlisäveron laskeminen ja käsitteleminen
*  Täytä ALV-ilmoitukset.

## <a name="see-also"></a>Katso myös
[Vuosien ja kausien sulkeminen](year-close-years-periods.md)  
[Kirjojen sulkeminen](year-close-books.md)

