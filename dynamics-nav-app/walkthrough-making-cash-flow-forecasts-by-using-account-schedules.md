---
title: "Vaihekuvaus – Kassavirtaennusteita tekeminen KP-raporttimallien avulla"
description: "Tässä vaihekuvauksessa kuvataan, kuinka KP-raporttimallin avulla voit tehdä kassavirtaennusteita. KP-raporttimallit suorittavat laskutoimituksia, joita ei voi tehdä suoraan kassavirtakaavioihin. KP-raporttimalleissa voidaan määrittää välisummat kassavirtavastaanottoja ja suorituksia varten. Nämä välisummat voidaan sisällyttää uusiin kokonaissummiin, joita voidaan sitten käyttää kassavirtaennusteita tehtäessä."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 09/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 72e2c2ab540ce53dc747792c3d1fa93ec87282f8
ms.contentlocale: fi-fi
ms.lasthandoff: 10/16/2017

---
# <a name="walkthrough-making-cash-flow-forecasts-by-using-account-schedules"></a>Vaihekuvaus: tehdään kassavirtaennusteita käyttäen KP-raporttimalleja
Tässä vaihekuvauksessa kuvataan, kuinka KP-raporttimallin avulla voit tehdä kassavirtaennusteita. KP-raporttimallit suorittavat laskutoimituksia, joita ei voi tehdä suoraan kassavirtakaavioihin. KP-raporttimalleissa voidaan määrittää välisummat kassavirtavastaanottoja ja suorituksia varten. Nämä välisummat voidaan sisällyttää uusiin kokonaissummiin, joita voidaan sitten käyttää kassavirtaennusteita tehtäessä.  

## <a name="about-this-walkthrough"></a>Tietoja tästä vaihekuvauksesta  
Tässä vaihekuvauksessa käsitellään seuraavia tehtäviä:  

- Uuden kassavirran KP-raporttimallin nimen määrittäminen.  
- Uuden KP-raporttimallin rivien määrittäminen.  
- Uuden sarakkeen asettelun määrittäminen.  
- Sarakeasettelun määritys KP-raporttimalliin.  
- Tarkastellaan ja tulostetaan kassavirtaennustetta.  

### <a name="prerequisites"></a>Vaatimukset  
Tämän vaihekuvauksen ohjeiden noudattamisen edellytykset:  

- [!INCLUDE[d365fin](includes/d365fin_md.md)] on asennettu.  
- Kassavirran rivit on rekisteröity.  

## <a name="roles"></a>Roolit  
Tässä vaihekuvauksessa havainnollistetaan seuraavien käyttäjäroolien tehtäviä:  

- Valvoja  

## <a name="story"></a>Taustatietoja  
Ken on CRONUSIN kirjanpitäjä, joka tekee kuukausittaiset kassavirtaennusteet. Hän sisällyttää ennusteeseen rahoituksen, myynnin, oston ja käyttöomaisuuden ja esittelee ennusteen talousjohtaja Saaralle liiketoiminnan kuva selkeyttämiseksi.  

## <a name="setting-up-a-new-account-schedule-name"></a>Uuden KP-raporttimallin nimen määrittäminen  
KP-raporttimalli koostuu kassavirran KP-raporttimallin nimestä, jossa on sarja rivejä ja sarakeasettelu.  

### <a name="to-set-up-a-new-account-schedule-name"></a>Uuden KP-raporttimallin nimen määrittäminen  

1.  Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, syötä **KP-raporttimallit** ja valitse sitten aiheeseen liittyvä linkki.  
2.  Valitse **KP-raporttimallien nimet** -ikkunassa **Uusi**-toiminto ja luo uuden kassavirran KP-raporttimallin nimi.  
3.  Syötä **Nimi**-kenttään **Ennuste**.  
4.  Kirjoita **Kuvaus**-kenttään **Kassavirtaennuste**.  
5.  Älä täytä **Sarakeasettelun oletusarvo**- ja **Analyysinäkymän nimi** -kenttiä.  

## <a name="setting-up-account-schedule-lines"></a>Uuden KP-raporttimallin rivien määrittäminen  
Kun KP-raporttimallin nimi on määritetty, Ken määrittää jokaisen rivin, joka näkyy kassavirran KP-raporttimallissa. Ken määrittää rivit, jotka voidaan näyttää raporteissa niiden rivien lisäksi, jotka on tarkoitettu vain laskentaan.  

### <a name="to-set-up-account-schedule-lines"></a>Määritä KP-raporttimallin rivit  

1.  Valitse **KP-raporttimallien nimet** -ikkunassa uusi **Ennuste**-KP-raporttimallin nimi, jonka loit. Valitse **Kotisivu**-välilehden **Käsittely**-ryhmässä **Muokkaa KP-raporttimallia**.  
2.  Anna **KP-raporttimallien nimet** -ikkunassa kukin rivi täsmälleen seuraavassa taulukossa esitetyllä tavalla.  

    > [!NOTE]  
    >  Käyttämällä **Lisää kassavirtatilit** -toimintoa, voit nopeasti merkitä kassavirtatilit kassavairtatilikartallta ja kopioida ne KP-raporttimallin riveille.  

    |Rivinro|Kuvaus|Summaustyyppi|Summausväli|Rivityyppi|Summatyyppi|Näytä|  
    |-------|-----------|-------------|--------|--------|---  ------|----| |C10|Summa|Nettomuutos|Tapahtumat|Nettosumma|Aina|  
    |C20|Summa päivämäärään|Saldo pvm:ttäin|Tapahtumat|Nettosumma|Aina|  
    |C30|Koko tilikausi|Koko tilikausi|Tapahtumat|Nettosumma|Aina|  

4.  Valitse **OK**-painike.  

## <a name="assigning-the-column-layout-to-the-account-schedule-name"></a>Sarakeasettelun määritys KP-raporttimallin nimeen  
Ken on nyt valmis määrittämään sarakeasettelun KP-raporttimallin nimeen.  

### <a name="to-assign-the-column-layout-to-the-account-schedule-name"></a>Määritä sarakeasettelu KP-raporttimallin nimeen.  

1.  Valitse **KP-raporttimallien nimet** -ikkunan **Nimi**-kentässä **Ennuste**.  
2.  Valitse **Sarakeasettelun oletusarvo** -kentässä **Kassavirta**-sarakeasettelu oletussarakeasetteluksi.  

### <a name="to-view-and-print-the-cash-flow-forecast"></a>Tarkastele ja tulosta kassavirtaennuste  
1.  Valitse **KP-raporttimallien nimet** -ikkunassa **Yleiskuvaus** ja tarkastele kassavirtaennustetta.  
2.  **KP-raporttimallin yleiskuvaus** -ikkunassa voit valita summan ja näyttää sitten kassavirran tuotantoennustetapahtumat, joista summa muodostuu. Lisäksi voit tarkastella laskentakaavaa, jota käytetään summan laskemisessa. Voit myös suodattaa määrät dimension ja päivämäärän mukaan.  
3.  Tulosta kassavirtaennuste valitsemalla **Tulosta**-toiminto.  

## <a name="see-also"></a>Katso myös  
 [KP-raporttimallien käyttäminen](bi-how-work-account-schedule.md)   
 [Liiketoimintaprosessien vaihekuvaukset](walkthrough-business-process-walkthroughs.md)  
 [[!INCLUDE[d365fin](includes/d365fin_md.md)] -ohjelman käyttäminen](ui-work-product.md)

