---
title: "Miten voit: muuta tällä hetkellä raportissa käytettävää asettelua"
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
ms.openlocfilehash: f1411704a7b2a0565d4b23d91e04e271af07659e
ms.contentlocale: fi-fi
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-change-which-layout-is-currently-used-on-a-report"></a>Miten voit: muuta tällä hetkellä raportissa käytettävää asettelua
Raportti voidaan määrittää useille raportin asetteluille, joita voidaan vaihtaa tarpeen mukaan.

Raporttiin käytettävissä olevien asettelujen mukaan voit valita valmiin RDLC-raporttiasettelun, sisäänrakennetun Word-raportin asettelun tai mukautetun asettelun käytön välillä. Lisätietoja RDLC- ja Word-raporttiasettelusta sekä valmiista ja mukautetuista asetteluista ja muista ominaisuuksista on kohdassa [Raporttiasetteluiden hallinta](ui-manage-report-layouts.md).

## <a name="to-change-the-layout-that-is-used-on-a-report"></a>Raportissa käytetyn asettelun muuttaminen
1. Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Raporttiasetteluvalinta** ja valitse sitten aiheeseen liittyvä linkki.  
**Raporttiasetteluvalinta**-ikkunassa näkyvät kaikki raportit, jotka ovat käytettävissä yritykselle, joka on määritetty Yritys-kentässä ikkunan yläosassa. Valittu asettelu -kenttä määrittää tällä hetkellä raportissa käytetyn asettelun.
2. Aseta **Yritys**-kenttä ikkunan yläosassa yritykseksi, joka sisältää raportin.
3. Voit muuttaa raportin käyttämää asettelua valitsemalla raportin rivin luettelosta ja asettamalla **Valittu asettelu** -kentän arvoksi yhden seuraavista vaihtoehdoista:
    - RDLC (valmis), käyttää raportissa valmista RDLC-raporttiasettelua.
    - Word (valmis), käyttää raportissa valmista Word-raporttiasettelua.
    - Mukautettu, käyttää raportissa mukautettua asettelua.  
    Raportissa käytettävissä olevat mukautetut asettelut näkyvät Raporttiasettelujen osat -tietoruudussa. Jos raportille ei ole mukautettuja asetteluja, sinun on ensin luotava yksi. Jos valitset tämän vaihtoehdon, siirry seuraavaan toimenpiteeseen ja määritä mukautettu asettelu, jota haluat käyttää.
**Huomautus**: Jos valitset **RDLC (valmis)** tai **Word (valmis)**, ja näyttöön tulee virhesanoma siitä, että raportin asettelu ei määritetyn tyyppinen, sinun on valittava toinen asetteluvaihtoehto tai luotava mukautettu raportin asettelu, jolla on haluamasi tyyppi.

Lisätoimia ei vaadita, jos valitsit valmiin RDLC- tai Word-raporttiasettelun ja asettelua käytetään, kun raportti suoritetaan seuraavan kerran.

## <a name="to-specify-a-custom-layout-on-a-report"></a>Mukautetun asettelun määrittäminen raportille
1. Voit määrittää **Mukautetut raporttiasettelut** -ikkunassa raportille käytettävän mukautetun asettelun. Jos **Mukautetut raporttiasettelut** -ikkuna ei ole avoinna, valitse hakupainike **Raporttiasettelun kuvaus** -kentässä.
2. Valitse **Mukautetut raporttiasettelut** -ikkunassa rivi mukautetulle asettelulle, jota haluat käyttää. Valitse sitten **OK**-painike.

Palaa **Raporttiasetteluvalinta**-ikkunaan. Valitun mukautetun asettelun nimi näkyy **Mukautetun asettelun kuvaus** -kentässä. Mukautettua asettelua käytetään seuraavan kerran, kun suoritat raportin.

## <a name="see-also"></a>Katso myös
[Raporttiasetteluiden hallinta](ui-manage-report-layouts.md)

