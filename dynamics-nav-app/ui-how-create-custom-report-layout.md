---
title: Raporttien ja asiakirjojen mukautettujen asettelujen luominen ja muokkaaminen
description: "Voit tutustua omien mukautettujen asettelujen luomiseen ja raportin ulkoasun muokkaamiseen, kun sitä tarkastellaan, tulostetaan tai tallennetaan."
documentationcenter: 
author: jswymer
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: customized report, document layout, logo, personalize
ms.date: 03/29/2017
ms.author: jswymer
ms.translationtype: HT
ms.sourcegitcommit: b9b1f062ee6009f34698ea2cf33bc25bdd5b11e4
ms.openlocfilehash: ee614c44a17873591916bc97bd9b2a3f33fce21b
ms.contentlocale: fi-fi
ms.lasthandoff: 10/23/2017

---
# <a name="how-to-create-and-modify-a-custom-report-or-document-layout"></a>Toimintaohje: Raporttien tai asiakirjojen mukautetun asettelun luominen ja muokkaaminen
Oletusarvon mukaan raportilla on valmis raporttiasettelu, joka voi olla RDLC-raporttiasettelu, Word-raporttiasettelu tai molemmat. Et voi muuttaa valmiita asetteluita. Voit kuitenkin luoda omia mukautettuja asetteluita, joiden avulla voit muuttaa raportin ulkoasua, kun sitä tarkastellaan, tulostetaan tai tallennetaan. Voit luoda useita mukautettuja raporttiasetteluja samalle raportille ja vaihtaa sitten raportin käyttämää asettelua tarpeen mukaan.

> [!NOTE]  
>   Raportti tarkoittaa [!INCLUDE[d365fin](includes/d365fin_md.md)]issa myös ulkoisille käyttäjille tarkoitettuja asiakirjoja, kuten myyntilaskuja tai tilausvahvistuksia, jotka lähetetään asiakkaille PDF-tiedostoina.

Jos haluat luoda mukautetun asettelun, voit joko kopioida aiemmin mukautetun asettelun tai lisätä uuden mukautetun asettelun, joka useimmissa tapauksissa perustuu valmiiseen asetteluun. Kun lisäät uuden mukautetun asettelun, voit lisätä RDLC-raporttiasettelutyypin, Word-raporttiasettelutyypin tai molemmat. Uusi mukautettu asettelu perustuu automaattisesti raportin valmiiseen asetteluun, jos sellainen on käytettävissä. Jos tyypille ei ole sisäänrakennettua asettelua, järjestelmä luo uuden tyhjän asettelun ja sinun on muokattava ja luotava alusta alkaen. Lisätietoja RDLC- ja Word-raporttiasettelusta sekä valmiista ja mukautetuista asetteluista ja muista ominaisuuksista on ohjeaiheessa [Raporttiasetteluiden hallinta](ui-manage-report-layouts.md).  

## <a name="to-create-a-custom-layout"></a>Mukautetun asettelun luonti
1. Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, kirjoita **Raporttiasetteluvalinta** ja valitse sitten aiheeseen liittyvä linkki.  

    **Raporttiasetteluvalinta**-ikkunassa on luettelo kaikista raporteista, joita voi käyttää ikkunan yläosan **Yritys**-kentässä määritetyssä yrityksessä.
2. Aseta **Yritys**-kenttä yritykselle jolle haluat luoda raporttiasettelun.
3. Valitse sen raportin rivi, johon haluat luoda asettelun, ja valitse sitten **Mukautetut asettelut** -toiminto.  
   **Mukautetut raporttiasettelut** -ikkunassa näkyvät kaikki mukautetut asettelut, jotka ovat käytettävissä valitussa raportissa.
4. Jos haluat luoda kopion aiemmin luodusta mukautetusta asettelusta, valitse luettelossa ensin aiemmin luotu mukautettu asettelu ja valitse **Kopioi** -toiminto.  
   Mukautetun asettelun kopio näkyy **Mukautetut raporttiasettelut** -ikkunassa, jonka **Kuvaus**-kentässä on sana *Kopio*.
5. Jos haluat lisätä uuden mukautetun asettelun, joka perustuu valmiiseen asetteluun, toimi seuraavasti:  
   1. Valitse **Uusi**-toiminto. **Lisää raportin valmis asettelu** -ikkuna avautuu. **Tunnus**- ja **Nimi**-kentät täytetään automaattisesti.
   2. Voit lisätä mukautetun Word-raporttiasettelun tyypin valitsemalla **Lisää Word-asettelu** -valintaruutu.
   3. Voit lisätä mukautetun RDLC-raporttiasettelun tyypin valitsemalla **Lisää RDLC-asettelu** -valintaruutu.
   4. Valitse **OK**-painike.  
      Uudet mukautetut asettelut näkyvät **Mukautetut raporttiasettelut** -ikkunassa. Jos uusi asettelu perustuu valmiiseen asetteluun, sitten siinä on sanat **valmiin asettelun kopio** **Kuvaus**-kentässä. Jos valmista asettelua ei ole saatavilla, uudessa asettelussa on sanat **uusi asettelu** **Kuvaus**-kentässä. Tämä osoittaa, että mukautettu asettelu on tyhjä.
6. Oletusarvon mukaan **Yrityksen nimi** -kenttä on tyhjä, joten mukautettu asettelu ovat käytettävissä kaikissa yrityksen raporteissa. Voit asettaa mukautetun asettelun vain tietyn yrityksen käytettäväksi valitsemalla **Muokkaa** ja määrittämällä sitten **Yrityksen nimi** -kenttään haluamasi yritys.

Mukautettu asettelu on luotu. Voit nyt muokata mukautettua asettelua tarpeen mukaan.

## <a name="ModifyCustomLayout"></a>Mukautetun asettelun muokkaaminen
Voit muokata raporttiasettelua viemällä raporttiasettelun ensin tiedostona tietokone- tai verkkosijaintiin ja avaamalla sitten viedyn asiakirjan Wordissa ja tekemällä muutokset. Kun olet tehnyt haluamasi muutokset, voit tuoda raporttiasettelun.

### <a name="to-modify-a-custom-layout"></a>Mukautetun asettelun muokkaaminen
1.  Voit viedä mukautetun asettelun **Mukautetut raporttiasettelut** -ikkunassa. Jos ikkuna ei ole vielä avoinna, etsi ja avaa **Raporttiasetteluvalinta**-ikkunassa, valitse raportti, jossa muokattava asettelu on, ja valitse sitten **Mukautetut asettelut** -toiminto.  
2.  Valitse **Mukautetut raporttiasettelut** -ikkunassa ensin muokattava raportti ja sitten **Vie asettelu** -toiminto. Tallenna raporttiasetteluasiakirja sitten tietokone- tai verkkosijaintiin valitsemalla **Tallenna** tai **Tallenna nimellä**.  

3.  Avaa juuri tallentamasi raporttiasettelu ja tee muutokset.

      Jos muutat Word-asettelua, avaa asetteluasiakirja Wordissa. Lisätietoja on seuraavassa kohdassa [Muutosten tekeminen raporttiasetteluun](ui-how-create-custom-report-layout.md#MakeChangesToLayout).

      RDLC-raporttiasettelut ovat kehittyneempiä kuin Word-raporttiasettelut. Lisätietoja RDLC-raporttiasettelujen muokkaamisesta on kohdassa [RDLC-raporttiasettelujen suunnitteleminen](https://msdn.microsoft.com/en-us/dynamics-nav/designing-rdlc-report-layouts).

      Muista tallentaa muutokset, kun olet valmis.

4.  Palaa **Mukautetut raporttiasettelut** -ikkunaan, valitse viety ja muokattu raporttiasettelu ja valitse lopuksi **Tuo asettelu** -toiminto.  

5. Etsi ja valitse raporttiasetteluasiakirja valitsemalla **Tuo**-valintaruudussa ensin **Valitse** ja sitten **Avaa**.

##  <a name="MakeChangesToLayout"></a> Muutosten tekeminen Word-raporttiasetteluun  
Voit tehdä yleisiä muotoilu- ja asettelumuutoksia, kuten vaihtaa tekstin fontin sekä lisätä taulukon ja muokata sitä tai poista tietokentän, käyttämällä samoja Wordin perustoimintoja kuin muissakin Word-asiakirjoissa.

Jos olet suunnittelemassa Wordin raporttiasettelua alusta tai lisäämässä uusia tietokenttiä, aloita lisäämällä taulukko, jossa on rivejä ja sarakkeita, jotka ovat lopulta tietokenttiä.

> [!TIP]  
>  Näytä taulukon ruudukko siten, että näet taulukon solujen rajat. Muista piilottaa ruudukko, kun lopetat muokkauksen. Voit näyttää tai piilottaa ruudukot valitsemalla taulukon ja valitsemalla **Asettelu**-kohdan alta **Taulukko**-välilehdellä **Näytä ruudukko**.  

###  <a name="RemoveField"></a> Otsikko- ja tietokenttien poistaminen Word-asetteluissa  
 Raportin otsikko- ja tietokentät sisältyvät Wordin sisällön ohjausobjekteihin. Seuraavassa kuvassa on esitetty sisällön ohjausobjekti, kun se on valittuna Word-asiakirjassa.  

 ![Kentän sisällönhallinta Word-raporttiasettelussa](media/nav_wordreportlayouts_contentcontrol.png "NAV_WordReportLayouts_ContentControl")  

 Selitteen tai tietokentän nimi näkyy sisällön ohjausobjektissa. Esimerkissä kentän nimi on CompanyAddr1.  

### <a name="to-remove-a-label-or-data-field"></a>Selitteen tai tietokentän poistaminen  

1.  Napsauta poistettavaa kenttää hiiren kakkospainikkeella ja valitse **Poista sisällön hallinta**.  

     Sisällön ohjausobjekti poistetaan, mutta kentän nimi säilyy tekstinä.  

2.  Poistaa jäljellä olevan tekstin tarpeen mukaan.  

### <a name="adding-data-fields"></a>Tietokenttien lisääminen
Tietokenttien lisääminen raportin tietojoukosta on kuitenkin lisäasetus ja edellyttää tietoja raportin tietojoukosta. Lisätietoja tieto-, otsikko- ja kuvakenttien lisäämisestä on kohdassa [Toimintaohje: Kenttien lisääminen Word-raporttiasetteluun](ui-how-add-fields-word-report-layout.md).  


## <a name="see-also"></a>Katso myös
[Raporttiasetteluiden hallinta](ui-manage-report-layouts.md)  
[Miten voit: muuta tällä hetkellä raportissa käytettävää asettelua](ui-how-change-layout-currently-used-report.md)  
[Toimintaohje: Raporttien tai asiakirjojen mukautetun asettelun tuonti ja vienti](ui-how-import-and-export-report-layout.md)  
[Raporttien käsittely](ui-work-report.md)  
[[!INCLUDE[d365fin](includes/d365fin_md.md)] -ohjelman käyttäminen](ui-work-product.md)  

