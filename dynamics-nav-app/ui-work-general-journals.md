---
title: "Yleisten päiväkirjojen käyttäminen"
author: edupont04
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 2dc2b22fbc0ff70addd16ca14e8c5416c49915e7
ms.contentlocale: fi-fi
ms.lasthandoff: 06/26/2017

---

# <a name="work-with-general-journals"></a>Yleisten päiväkirjojen käyttäminen
Yleisiä päiväkirjoja käytetään rahoitustapahtumien kirjaamisessa kirjanpitotileille sekä muille tileille, kuten pankki-, asiakas- ja toimittajatileille. Yleisen päiväkirjan avulla kirjaaminen luo aina tapahtumia kirjanpitotileille. Näin tapahtuu silloinkin, kun kirjataan esimerkiksi päiväkirjan rivi asiakkaan tilille, koska tapahtuma kirjataan pääkirjanpidon myyntisaamisten tilille kirjausryhmän kautta.

Päiväkirjaan lisäämäsi tiedot ovat väliaikaisia, ja niitä voi muuttaa niiden ollessa päiväkirjassa. Kun kirjaat päiväkirjan, tiedot siirretään yksittäisten tilien tapahtumiin, missä niitä ei voi muuttaa. Voit kuitenkin peruuttaa kirjattujen tapahtumien kohdistuksen tai kirjata peruuttavia tai korjaavia tapahtumia.

## <a name="journal-templates-and-batches"></a>Päiväkirjan mallit ja erät
Yleisen päiväkirjan malleja on useita. Kullakin päiväkirjan mallilla on määritetty ikkuna, jossa on erityistoimintoja sekä näitä toimintoja varten tarvittavat kentät. Ikkunoita ovat esimerkiksi **Maksujen täsmäytyskirjauskansio**, jossa käsitellään pankkimaksuja, ja **Maksupäiväkirja**, jossa maksetaan toimittajille.

Voit määrittää kullekin päiväkirjan mallille oman henkilökohtaisen päiväkirjan päiväkirjan eränä. Voit esimerkiksi määrittää maksupäiväkirjalle oman päiväkirjan erän, jolle on määritetty henkilökohtainen asettelu ja asetukset.

**Huomautus**: Esimerkki yleisen päiväkirjan erälle määritetyistä henkilökohtaisista asetuksista on se, että järjestelmä auttaa summakenttien täyttämisessä. Jos valitset **Yleisen päiväkirjan erät** -ikkunan erän rivillä olevan **Ehdota vastasummaa** -valintaruudun, esimerkiksi saman asiakirjanumeron yleisen päiväkirjan rivien **Summa**-kenttään esitäytetään automaattisesti arvo, joka vaaditaan asiakirjan täsmäyttämiseksi. Lisätietoja on kohdassa [Dynamics NAV voi ehdottaa arvoja](ui-let-system-suggest-values.md).

## <a name="main-accounts-and-balancing-accounts"></a>Päätilit ja vastatilit
Jos olet määrittänyt päiväkirjan erille oletusvastatilit, vastatili täytetään automaattisesti, kun täyttö tehdään **Tilinro**. -kentässä. Muussa tapauksessa myös **Tilinro**- ja **Vastatilin nro** -kenttä on täytettävä manuaalisesti. Positiivinen summa **Summa**-kentässä veloitetaan päätililtä ja hyvitetään vastatilille. Negatiivinen summa hyvitetään päätilille ja veloitetaan vastatililtä.

**Huomautus**: ALV lasketaan erikseen päätiliä varten ja vastatiliä varten, joten niillä voi olla eri ALV-prosentit.

## <a name="recurring-journals"></a>Toistuvat päiväkirjat
Toistuva päiväkirja on yleinen päiväkirja, jossa on erityiskenttiä sellaisten tapahtumien hallintaa varten, jotka kirjataan usein vähäisin muutoksin tai ilman muutoksia. Käyttämällä näitä kenttiä toistuviin tapahtumiin, voit kirjata sekä vakiosummia että muuttuvia summia. Voit myös määrittää automaattisen peruutuksen tapahtumat kirjauspäivämäärän jälkeisenä päivänä sekä käyttää kohdistusavaimia toistuvien tapahtumien kanssa.

## <a name="see-also"></a>Katso myös
[Toimintaohje: Kohdistustunnusten käyttäminen yleisissä päiväkirjoissa](ui-how-use-allocation-keys-general-journals.md)  
[Rahoitus](finance-setup.md)  
[Dynamics NAV -ohjelman käyttäminen](ui-work-product.md)

