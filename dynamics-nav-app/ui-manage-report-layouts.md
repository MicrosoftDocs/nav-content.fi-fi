---
title: "Raporttien ja asiakirjojen mukautettujen ja valmiiden asettelujen käyttäminen"
description: "Voit mukauttaa asiakirjoja raporttiasettelujen avulla. Voit muokata tällä tavoin asiakkaille lähetettävien PDF-tiedostojen fonttia, logoa tai sivuasetuksia."
documentationcenter: 
author: SusanneWindfeldPedersen
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: customized report, document layout, logo, personalize
ms.date: 03/29/2017
ms.author: solsen
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 11abe8b3375bca1515602143830d4c9963058172
ms.contentlocale: fi-fi
ms.lasthandoff: 10/16/2017

---
# <a name="managing-report-and-document-layouts"></a>Raporttien ja asiakirjojen asettelujen hallinta
Raporttiasettelu ohjaa raportin sisältöä ja muotoa, mukaan lukien, mitkä tietojen kentät näkyvät raportissa ja miten ne järjestetään, tekstityylin, kuvia ja muita ominaisuuksia. Voit luoda [!INCLUDE[d365fin](includes/d365fin_md.md)]ista uuden asettelun, muuttaa raportissa käytettävää asettelua tai muokata nykyisiä asetteluja.

> [!NOTE]  
>   Raportti tarkoittaa [!INCLUDE[d365fin](includes/d365fin_md.md)]issa myös ulkoisille käyttäjille tarkoitettuja asiakirjoja, kuten myyntilaskuja tai tilausvahvistuksia, jotka lähetetään asiakkaille PDF-tiedostoina.

Erityisesti raporttiasettelu määrittää seuraavat asetukset:

* [!INCLUDE[d365fin](includes/d365fin_md.md)]-raportin tietojoukosta sisällytettävät tunnus- ja tietokentät.
* Tekstin muoto, kuten kirjasimen tyyppi, koko ja väri.
* Yrityksen logo ja sen sijainti.
* Yleiset sivun asetukset, esimerkiksi reunukset ja taustakuvia.

[!INCLUDE[d365fin](includes/d365fin_md.md)]iin voidaan määrittää useita raportin asetteluja, joita voit vaihtaa tarpeen mukaan. Voit valita jonkin valmiin raporttiasettelun tai voit luoda mukautettuja raporttiasetteluja ja määrittää ne raportteihisi tarpeen mukaan. Lisätietoja on kohdassa [Toimintaohje: Raportin tai asiakirjan mukautetun asettelun luominen](ui-how-create-custom-report-layout.md).

Raporteissa käytettävän raporttiasettelun tyyppi voi olla Word tai RDLC.

## <a name="word-report-layout-overview"></a>Word-raporttiasettelun esittely
Word-raportin asettelu perustuu Word-asiakirjaan (.docx-tiedostotyyppi). Word-raporttiasetteluiden avulla voit suunnitella raporttiasetteluita käyttämällä Microsoft Word 2013 -versiota tai uudempaa. Word-raporttiasettelu määrittää raportin sisällön ja ohjaa sitä, miten sisältöelementit järjestetään ja miltä ne näyttävät. Raportin asettelu Word-asiakirjassa käyttää yleensä taulukoita, joiden avulla voit järjestää sisältöä, jossa solut sisältävät tietokentät, tekstiä tai kuvia.

 ![Esimerkki NAV:n Wordin raporttiasetteluasiakirjasta](media/nav_wordreportlayout_edit_in_word_example.png "NAV_WordReportLayout_Edit_In_Word_Example")  

## <a name="rdlc-layout-overview"></a>RDLC-asettelun yleiskuvaus
RDLC-asettelut perustuvat asiakkaan määrittelemiin raportinasetteluihin (.rdlc- tai .rdl-tiedostotyypit). Näitä asetteluja luodaan ja muokataan käyttämällä SQL Server Report Builderia. RDLC-asetteluiden rakenne muistuttaa Word-asetteluja, joissa asettelu määrittää raportin yleisen muodon ja määrää sisällytettävät tietojoukon kentät. RDLC-asetteluiden suunnitteleminen on monimutkaisempaa kuin Word-asetteluiden. Lisätietoja on kohdassa [RDLC-raporttiasetteluiden suunnitteleminen](https://msdn.microsoft.com/en-us/dynamics-nav/designing-rdlc-report-layouts).

## <a name="built-in-and-custom-report-layouts"></a>Valmiit ja mukautetut raporttiasettelut
[!INCLUDE[d365fin](includes/d365fin_md.md)] sisältää useita valmiita asetteluita. Valmiit asettelut ovat etukäteen määritettyjä asetteluita, jotka on suunniteltu määrätyille raporteille. [!INCLUDE[d365fin](includes/d365fin_md.md)]in raporteissa on valmis asettelu joko RDLC-raporttiasetteluna, Wordin raporttiasetteluna tai joissakin tapauksissa molempina. Et voi muokata valmista raporttiasettelua [!INCLUDE[d365fin](includes/d365fin_md.md)]ista, mutta voit käyttää niitä lähtökohtana oman mukautetun raporttiasettelun luomisessa.

Mukautetut asettelut ovat raporttiasetteluita, jotka olet suunnitellut raportin ulkoasun muuttamiseksi. Luot tavallisesti mukautetun asettelun valmiin asettelun perusteella, mutta voit luoda niitä alusta alkaen tai kopioimalla aiemmin luodun mukautetun asettelun. Mukautetut asettelut mahdollistavat useat asettelut samalle raportille, joita voit vaihtaa tarpeen mukaan. Kullakin [!INCLUDE[d365fin](includes/d365fin_md.md)]-yritykselle voi olla esimerkiksi erilaisia asetteluja tai samalle yritykselle voi olla eri asetteluja tietyissä tapauksissa tai tapahtumissa, kuten erityiskampanjoissa tai lomakaudella.

## <a name="deciding-whether-to-use-a-word-or-rdlc-report-layout"></a>Wordin raporttiasettelun ja RDLC-raporttiasettelun välillä valitseminen
Raporttiasettelu voi perustua Word-asiakirjaan tai RDLC-tiedostoon. Word- tai RDLC-raporttiasettelun käytöstä päätettäessä asettelutyyppi riippuu siitä, miltä luodun raportin halutaan näyttävän ja tietämyksestäsi Wordista ja SQL Server Report Builderista.

Word- ja RDLC-asetteluiden yleiset rakenteet ovat hyvin samanlaisia. Kuitenkin jokaisessa tyypissä on tiettyjä piirteitä, jotka vaikuttavat siihen, miten luotu raportti näkyy [!INCLUDE[d365fin](includes/d365fin_md.md)]issa. Tämä tarkoittaa sitä, että sama raportti saattaa näyttää erilaiselta RDLC-raporttiasetteluun verrattuna Word-raporttiasettelua käytettäessä.

Word- ja RDLC-raporttiasetteluiden asettaminen toimii samalla tavalla. Tärkein ero on asetteluiden muokkaustavassa. Word-raporttiasettelut ovat yleensä helpompia luoda ja muokata kuin RDLC-raporttiasettelut, koska voit käyttää Wordia. RDLC-raporttiasetteluja muokataan SQL Server Report Builderilla, joka on tarkoitettu kokeneille käyttäjille.

Lisätietoja näytettävän asettelun vaihtamisesta on kohdassa [Toimintaohje: Raportissa tällä hetkellä käytettävän asettelun muuttaminen](ui-how-change-layout-currently-used-report.md)

## <a name="see-also"></a>Katso myös
[Raporttien tai asiakirjojen asettelujen päivittäminen](ui-update-report-layouts.md)  
[[!INCLUDE[d365fin](includes/d365fin_md.md)] -ohjelman käyttäminen](ui-work-product.md)  
[Toimintaohje: Raporttien tai asiakirjojen mukautetun asettelun luominen ja muokkaaminen](ui-how-create-custom-report-layout.md)  
[Toimintaohje: Raporttien tai asiakirjojen mukautetun asettelun tuonti ja vienti](ui-how-import-and-export-report-layout.md)  
[Toimintaohje: Asiakirjojen lähettäminen sähköpostitse](ui-how-send-documents-email.md)  
[Raporttien käsittely](ui-work-report.md)  

