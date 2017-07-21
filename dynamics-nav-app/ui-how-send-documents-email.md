---
title: "Toimintaohje: Asiakirjojen lähettäminen sähköpostitse"
author: SorenGP
ms.custom: na
ms.date: 11/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: e4476c2ab903001017dcd6c8bdaa84892ba79c9e
ms.contentlocale: fi-fi
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-send-documents-by-email"></a>Toimintaohje: Asiakirjojen lähettäminen sähköpostitse
Voit kertoa liiketoiminta-asiakirjojen sisällön, kuten esimerkiksi asiakkaiden myyntiasiakirjojen maksutiedot, liiketoimintakumppaneille nopeasti Raporttiasettelu-toiminnolla. Voit määrittää asiakirjakohtaisen sisällön, joka lisätään sähköpostien perustekstiin automaattisesti.

Ota sähköpostit käyttöön Dynamics NAV -ohjelmassa kotisivulla olevan avustetun **sähköpostien määrityksen** asetuksen avulla.

Voit lähettää käytännössä kaikkia asiakirjatyyppejä sähköpostitse sähköpostiviestien liitteinä suoraan asiakirjan ikkunasta. Liitteen lisäksi voit määrittää asiakirjakohtaisia sähköpostin perustekstejä, jotka sisältävät asiakirjan perustiedot. Niitä edeltää vakioteksti, jossa tervehditään viestin vastaanottajaa ja esitellään kyseessä oleva asiakirja. Voit tarjota asiakkaillesi mahdollisuuden maksaa sähköisesti käyttämällä maksupalvelua, kuten PayPalia. Sähköpostin perustekstiin voi siten lisätä myös PayPal-tiedot ja -hyperlinkin.

Sähköpostin luominen aloitetaan kaikissa tuetuissa asiakirjoissa valitsemalla **Lähetä**-toiminto kirjatuissa asiakirjoissa ja **Kirjaa ja lähetä** -toiminto muissa kuin kirjatuissa asiakirjoissa.

Jos **Sähköposti**-kentän arvoksi **Lähetä asiakirja kohteeseen** -ikkunassa on määritetty **Kyllä (Pyydä asetuksia)**, **Lähetä sähköposti** -ikkuna avautuu. Ikkunan **Vastaanottaja:**-kenttään on esitäytetty kontaktihenkilön tiedot ja asiakirja on liitetty PDF-tiedostona. Voit syöttää tekstin manuaalisesti **Perusteksti**-kenttään tai kenttään voidaan täyttää määrittämäsi asiakirjakohtaisen sähköpostin perusteksti.

Seuraavassa kuvataan, miten sähköpostitse lähetettävien myyntilaskujen asiakirjakohtaisissa sähköpostien perusteksteissä käytettävä **Myyntilasku**-raportti määritetään.

## <a name="to-set-up-a-document-specific-email-body-for-sales-invoices"></a>Asiakirjakohtaisen sähköpostin perustekstin määrittäminen myyntilaskuille
1. Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Raporttivalinnat - Myynti** ja valitse sitten aiheeseen liittyvä linkki.
2. Valitse **Raporttivalinta - Myynti** -ikkunan **Käyttö**-kentässä **Lasku**.
3. Valitse **Raportin tunnus** -kentän uudella rivillä esimerkiksi vakioraportti 1306.
4. Valitse **Käytä sähköpostin perustekstinä** -valintaruutu.
5. Valitse **Sähköpostin perustekstin asettelun tunnus** -kenttä ja valitse sitten jokin käytettävissä olevista asetteluista **Mukautetut raporttiasettelut** -ikkunassa.
6. Raporttiasettelut määrittävät sähköpostin perustekstin tyylin ja sisällön. Siihen kuuluu myös vakioteksti, joka edeltää asiakirjan perustietoja sähköpostin perustekstissä.
7. Voit tarkastella tai muokata asettelua, johon sähköpostin perusteksti perustuu, valitsemalla **Mukautetut raporttiasettelut** -ikkunassa **Muokkaa asettelua** -toiminnon.
8. Jos haluat tarjota asiakkaillesi mahdollisuuden maksaa sähköisesti, voit määrittää liittyvän maksupalvelun, kuten PayPalin. Tämän jälkeen sähköpostin perustekstiin voi lisätä myös PayPal-tiedot ja -hyperlinkin. Lisätietoja on kohdassa [Toimintaohje: Asiakkaan maksujen ottaminen käyttöön PayPalin kautta](sales-how-enable-customer-payments-paypal.md).
9. Valitse **OK**-painike.

Kun nyt valitset esimerkiksi **Kirjattu myyntilasku** -ikkunan, sähköpostin perusteksti sisältää raportin 1306 asiakirjan tiedot, joita edeltää tyylitelty vakioteksti vaiheessa 5 valitun raporttiasettelun mukaan.

Seuraavassa kerrotaan, miten kirjattu myyntilasku lähetetään sähköpostiviestinä, johon on liitetty asiakirja PDF-tiedostona ja joka sisältää asiakirjakohtaisen sähköpostin perustekstin.
## <a name="to-send-documents-by-email"></a>Asiakirjojen lähettäminen sähköpostitse
1. Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Kirjatut myyntilaskut** ja valitse sitten aiheeseen liittyvä linkki.
2. Valitse asianmukainen myyntilasku ja valitse sitten **Lähetä**-toiminto. **Lähetä asiakirja kohteeseen** -ikkuna avautuu.
3. Valitse **Sähköposti**-kentässä **Kyllä (Pyydä asetuksia)**. Lisätietoja on kohdassa [Toimintaohje: Asiakirjan lähetysprofiilien määrittäminen](sales-how-setup-document-send-profiles.md).
4. Valitse **OK**-painike. **Lähetä sähköposti** -ikkuna avautuu.
5. Syötä **Vastaanottaja:**-kenttään kelvollinen sähköpostiosoite. Oletusarvo on asiakkaan sähköpostiosoite.
6. Syötä **Kopio:**-kenttään sähköpostiosoite, johon lähetetään sähköpostiviestin kopio toiselle vastaanottajalle.
7. Määritä **Piilokopio:**-kenttään sähköpostiosoite, johon lähetetään kopio sähköpostiviestistä ilman, että vastaanottajan sähköpostiosoite näkyy muille vastaanottajille.
8. Kirjoita **Aihe**-kenttään kuvaava aiheteksti. Oletusarvo on asiakkaan nimi ja laskun numero.
9. Luotu lasku on liitetty **Liite**-kenttään oletusarvoisesti PDF-tiedostona. Valitse valintapainike, kun haluat avata tiedoston tai liittää toisen tiedoston.
10. Kirjoita **Runkoteksti**-kenttään lyhyt viesti vastaanottajalle.

    Jos asiakirjakohtainen sähköpostin perusteksti on määritetty **Raporttivalinta - Myynti** -ikkunassa, **Perusteksti**-kenttä täytetään automaattisesti. Lisätietoja on tämän ohjeaiheen “Asiakirjakohtaisen sähköpostin perustekstin määrittäminen myyntilaskuille” -osassa.
11. Valitse **Muokkaa Outlookin verkkosovelluksessa** -valintaruutu, kun haluat avata sähköpostiviestin Office 365:n sähköpostisovelluksessa.
12. Valitse **OK**-painike, kun haluat lähettää sähköpostiviestin.

**Huomautus**: Sähköpostiviestin asetuksia ei tarvitse määrittää aina, kun lähetät asiakirjan sähköpostitse, kun valitset **Kyllä (Käytä oletusasetuksia)** -vaihtoehdon **Lähetä asiakirja kohteeseen** -ikkunan Sähköposti-kentässä. Tällöin **Lähetä sähköposti** -ikkuna ei avaudu. Lisätietoja on vaiheessa 4. Lisätietoja on kohdassa [Toimintaohje: Asiakirjan lähetysprofiilien määrittäminen](sales-how-setup-document-send-profiles.md).

## <a name="see-also"></a>Katso myös  
[Dynamics NAV -ohjelman käyttäminen](ui-work-product.md)  
[Toimintaohje: Myynnin laskutus](sales-how-invoice-sales.md)

