---
title: 'Toimintaohje: mukautetun raporttiasettelun luonti'
author: SusanneWindfeldPedersen
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 90136439e09deb00a9aed9344fc5f89812caef3a
ms.contentlocale: fi-fi
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-create-a-custom-report-layout"></a>Toimintaohje: mukautetun raporttiasettelun luonti
Oletusarvon mukaan raportilla on valmis raporttiasettelu, joka voi olla RDLC-raporttiasettelu, Word-raporttiasettelu tai molemmat. Et voi muuttaa valmiita asetteluita. Voit kuitenkin luoda omia mukautettuja asetteluita, joiden avulla voit muuttaa raportin ulkoasua, kun sitä tarkastellaan, tulostetaan tai tallennetaan. Voit luoda useita mukautettuja raporttiasetteluja samalle raportille ja vaihtaa sitten raportin käyttämää asettelua tarpeen mukaan.

Jos haluat luoda mukautetun asettelun, voit joko kopioida aiemmin mukautetun asettelun tai lisätä uuden mukautetun asettelun, joka useimmissa tapauksissa perustuu valmiiseen asetteluun. Kun lisäät uuden mukautetun asettelun, voit lisätä RDLC-raporttiasettelutyypin, Word-raporttiasettelutyypin tai molemmat. Uusi mukautettu asettelu perustuu automaattisesti raportin valmiiseen asetteluun, jos sellainen on käytettävissä. Jos tyypille ei ole sisäänrakennettua asettelua, järjestelmä luo uuden tyhjän asettelun ja sinun on muokattava ja luotava alusta alkaen. Lisätietoja RDLC- ja Word-raporttiasettelusta sekä valmiista ja mukautetuista asetteluista ja muista ominaisuuksista on kohdassa [Raporttiasetteluiden hallinta](ui-manage-report-layouts.md).  

## <a name="to-create-a-custom-layout"></a>Mukautetun asettelun luonti
1. Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Raporttiasetteluvalinta** ja valitse sitten aiheeseen liittyvä linkki.  
**Raporttiasetteluvalinta**-ikkunassa näkyvät kaikki yrityksen käytettävissä olevat raportit. Kyseinen yritys määritetty Yritys-kentässä ikkunan yläosassa.
2. Aseta **Yritys**-kenttä yritykselle jolle haluat luoda raporttiasettelun.
3. Valitse rivi raportille, jolle haluat luoda asettelun, ja valitse sitten **Mukautetut asettelut**.  
**Mukautetut raporttiasettelut** -ikkunassa näkyvät kaikki mukautetut asettelut, jotka ovat käytettävissä valitussa raportissa.
4. Jos haluat luoda kopion aiemmin luodusta mukautetusta asettelusta, valitse luettelosta aiemmin luotu mukautettu asettelu ja valitse sitten **Kopioi**.  
Mukautetun asettelun kopio näkyy **Mukautetut raporttiasettelut** -ikkunassa, jonka Kuvaus-kentässä on sana Kopio.
5. Jos haluat lisätä uuden mukautetun asettelun, joka perustuu valmiiseen asetteluun, toimi seuraavasti:  
    1. Valitse **Uusi**. **Lisää raportin valmis asettelu** -ikkuna avautuu. **Tunnus**- ja **Nimi**-kentät täytetään automaattisesti.
    2. Voit lisätä mukautetun Word-raporttiasettelun tyypin valitsemalla **Lisää Word-asettelu** -valintaruutu.
    3. Voit lisätä mukautetun RDLC-raporttiasettelun tyypin valitsemalla **Lisää RDLC-asettelu** -valintaruutu.
    4. Valitse **OK**-painike.  
    Uudet mukautetut asettelut näkyvät **Mukautetut raporttiasettelut** -ikkunassa. Jos uusi asettelu perustuu valmiiseen asetteluun, sitten siinä on sanat **valmiin asettelun kopio** **Kuvaus**-kentässä. Jos valmista asettelua ei ole saatavilla, uudessa asettelussa on sanat **uusi asettelu** **Kuvaus**-kentässä. Tämä osoittaa, että mukautettu asettelu on tyhjä.
6. Oletusarvon mukaan **Yrityksen nimi** -kenttä on tyhjä, joten mukautettu asettelu ovat käytettävissä kaikissa yrityksen raporteissa. Voit asettaa mukautetun asettelun vain tietyn yrityksen käytettäväksi valitsemalla **Muokkaa** ja määrittämällä sitten **Yrityksen nimi** -kenttään haluamasi yritys.

## <a name="see-also"></a>Katso myös
[Raporttiasetteluiden hallinta](ui-manage-report-layouts.md)  
[Miten voit: muuta tällä hetkellä raportissa käytettävää asettelua](ui-how-change-layout-currently-used-report.md)

