---
title: Raporttiasetteluiden hallinta
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
ms.openlocfilehash: 57cd575c1f72841dae162b077d1f676720ee24e7
ms.contentlocale: fi-fi
ms.lasthandoff: 06/26/2017

---
    
# <a name="manage-report-layouts"></a>Raporttiasetteluiden hallinta
Raporttiasettelu ohjaa raportin sisältöä ja muotoa, mukaan lukien, mitkä tietojen kentät näkyvät raportissa ja miten ne järjestetään, tekstityylin, kuvia ja muita ominaisuuksia. Dynamics NAV -asiakasohjelmista voit luoda uuden asettelun, muuttaa raportissa käytettävää asettelua tai muokata nykyisiä asetteluja. 

Erityisesti raporttiasettelu määrittää seuraavat asetukset:

- Dynamics NAV -raportin tietojoukosta sisällytettävät tunnus- ja tietokentät.
- Tekstin muoto, kuten kirjasimen tyyppi, koko ja väri.
- Yrityksen logo ja sen sijainti.
- Yleiset sivun asetukset, esimerkiksi reunukset ja taustakuvia. 

Dynamics NAV -raportti voidaan määrittää useille raportin asetteluille, joita voit vaihtaa tarpeen mukaan. Voit valita jonkin valmiin raporttiasettelun tai voit luoda mukautettuja raporttiasetteluja ja määrittää ne raportteihisi tarpeen mukaan.

Raporteissa käytettävän raporttiasettelun tyyppi voi olla Word tai RDLC.

## <a name="word-report-layout-overview"></a>Word-raporttiasettelun esittely
Word-raportin asettelu perustuu Word-asiakirjaan (.docx-tiedostotyyppi). Word-raporttiasetteluiden avulla voit suunnitella raporttiasetteluita käyttämällä Microsoft Word 2013 -versiota tai uudempaa. Word-raporttiasettelu määrittää raportin sisällön ja ohjaa sitä, miten sisältöelementit järjestetään ja miltä ne näyttävät. Raportin asettelu Word-asiakirjassa käyttää yleensä taulukoita, joiden avulla voit järjestää sisältöä, jossa solut sisältävät tietokentät, tekstiä tai kuvia.

## <a name="rdlc-layout-overview"></a>RDLC-asettelun yleiskuvaus
RDLC-asettelut perustuvat asiakkaan määrittelemiin raportinasetteluihin (.rdlc- tai .rdl-tiedostotyypit). Näitä asetteluja luodaan ja muokataan käyttämällä SQL Server Report Builderia. RDLC-asetteluiden rakenne muistuttaa Word-asetteluja, joissa asettelu määrittää raportin yleisen muodon ja määrää sisällytettävät tietojoukon kentät. RDLC-asetteluiden suunnitteleminen on monimutkaisempaa kuin Word-asetteluiden.

## <a name="built-in-and-custom-report-layouts"></a>Valmiit ja mukautetut raporttiasettelut
Dynamics NAV sisältää useita valmiita asetteluita. Valmiit asettelut ovat etukäteen määritettyjä asetteluita, jotka on suunniteltu määrätyille raporteille. Dynamics NAV -raporteissa on valmis asettelu joko RDLC-raporttiasetteluna, Wordin raporttiasetteluna tai joissakin tapauksissa molempina. Et voi muokata valmista raporttiasettelua Dynamics NAV -ohjelmasta, mutta voit käyttää niitä lähtökohtana oman mukautetun raporttiasettelun luomisessa. 

Mukautetut asettelut ovat raporttiasetteluita, jotka olet suunnitellut raportin ulkoasun muuttamiseksi. Luot tavallisesti mukautetun asettelun valmiin asettelun perusteella, mutta voit luoda niitä alusta alkaen tai kopioimalla aiemmin luodun mukautetun asettelun. Mukautetut asettelut mahdollistavat useat asettelut samalle raportille, joita voit vaihtaa tarpeen mukaan. Kullekin Dynamics NAV -yritykselle voi olla erilaisia asetteluja tai samalle yritykselle voi olla eri asetteluja tietyissä tapauksissa tai tapahtumissa, kuten erityiskampanjoissa tai lomakaudella.

## <a name="deciding-whether-to-use-a-word-or-rdlc-report-layout"></a>Wordin raporttiasettelun ja RDLC-raporttiasettelun välillä valitseminen 
Raporttiasettelu voi perustua Word-asiakirjaan tai RDLC-tiedostoon. Word- tai RDLC-raporttiasettelun käytöstä päätettäessä asettelutyyppi riippuu siitä, miltä luodun raportin halutaan näyttävän ja tietämyksestäsi Wordista ja SQL Server Report Builderista. 

Word- ja RDLC-asetteluiden yleiset rakenteet ovat hyvin samanlaisia. Kuitenkin jokaisessa tyypissä on tiettyjä piirteitä, jotka vaikuttavat siihen, miten luotu raportti näkyy Dynamics NAV -ohjelmassa. Tämä tarkoittaa sitä, että sama raportti saattaa näyttää erilaiselta RDLC-raporttiasetteluun verrattuna Word-raporttiasettelua käytettäessä.

Word- ja RDLC-raporttiasetteluiden asettaminen toimii samalla tavalla. Tärkein ero on asetteluiden muokkaustavassa. Word-raporttiasettelut ovat yleensä helpompia luoda ja muokata kuin RDLC-raporttiasettelut, koska voit käyttää Wordia. RDLC-raporttiasetteluja muokataan SQL Server Report Builderilla, joka on tarkoitettu kokeneille käyttäjille.

Lisätietoja näytettävän asettelun vaihtamisesta on kohdassa [Toimintaohje: Raportissa tällä hetkellä käytettävän asettelun muuttaminen](ui-how-change-layout-currently-used-report.md)

## <a name="see-also"></a>Katso myös
[Dynamics NAV -ohjelman käyttäminen](ui-work-product.md)  
[Toimintaohje: mukautetun raporttiasettelun luonti](ui-how-create-custom-report-layout.md)  
[Toimintaohje: Asiakirjojen lähettäminen sähköpostitse](ui-how-send-documents-email.md)

