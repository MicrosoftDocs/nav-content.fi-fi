---
title: "Vian raportoinnin määrittäminen huoltohallinnossa"
description: "Lisätietoja vian raportointiprosessien määrittämisestä."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 08/22/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: fac280fc2dac2206b1e037656c522bcfef9bc9c7
ms.contentlocale: fi-fi
ms.lasthandoff: 10/16/2017

---

# <a name="how-to-set-up-fault-reporting"></a>Toimintaohje: Vian raportoinnin määrittäminen
Voit muodostaa vikaraportoinnin avulla huoltonimikkeiden vikatietojen kirjaamisstandardit. Voit määrittää esimerkiksi, mikä ongelma on, havaitut oireet, ongelman syyn ja ratkaisukeinon.  

Vikakoodit kuvaavat tavallisia huoltonimikevikoja tai huoltonimikkeille tehtyjä toimenpiteitä. Yrityksesi vikaraportoinnin tasosta riippuen ennen vikakoodien määrittämistä voi täytyä määrittää vika-aluekoodeja ja oirekoodeja. Vika-alueet kuvaavat huoltonimikevikojen alueet. Vian syykoodit kuvaavat huoltonimikkeiden vikojen syitä ja tarvittaessa myös, poistetaanko takuu- ja sopimusalennukset. Voit poistaa takuu- ja sopimusalennukset esimerkiksi silloin, jos asiakas on jollain tavalla vastuussa huoltonimikkeen viasta. Vian syykoodit määritetään huoltotilauksiin. Lisätietoja on kohdassa [Toimintaohje: Huoltotehtävien käsitteleminen](service-how-to-work-on-service-tasks.md).  

## <a name="to-specify-the-overall-level-of-fault-reporting-to-use"></a>Käytettävän vian yleisen raportointitason määrittäminen
1. Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, kirjoita **Huollon asetukset** ja valitse sitten aiheeseen liittyvä linkki. 
2. Valitse **Vian raportointitaso** -kentässä jokin seuraavassa taulukossa käsiteltävistä vaihtoehdoista.  
  
    |**Vian taso**|**Kuvaus**|  
    |------------|-------------|  
    |Ei yhtään | Raportointikoodeja ei käytetä.|  
    |Fault | Vikojen luettelo on **Vikakoodit**-taulukossa. Näillä koodeilla tunnistetaan huoltonimikkeen viat tai huoltonimikkeiden edellyttämät toimet. Voit koota toisiinsa liittyvät koodit **Vika-alueen koodi** -ryhmiksi.|  
    |Vika+Oire | Koodien yhdistelmät määritetään **Vikakoodit**- ja **Oirekoodit**-taulukoihin. Asiakkaat voivat käyttää oirekoodeja ongelman (esimerkiksi ääni tai laatu) kuvaamiseen.|  
    |Vika+Oire+Alue | Vika-, oire- ja aluekoodeja käytetään IRIS (International Repair Coding System) -järjestelmän käyttöönottona.|  
  
Vian raportointia määritettäessä voidaan myös liittää korjauksia ja ratkaisuja vikoihin ja virheisiin. Se määritetään **Vika-/ratkaisukoodien suhteet** -sivulla. Tällä sivulla määritetään sen huoltonimikkeen huoltonimikeryhmän koodiyhdistelmät, josta avasit ikkunan, ja kunkin yhdistelmän esiintymiskerrat.

## <a name="to-create-fault-and-resolution-code-relationships"></a>Vika- ja ratkaisukoodien suhteiden luominen
<!--this needs to go in a working with topic-->
Nähdäksesi tavallisimmat korjaustavat tiettyjen nimikevikojen osalta silloin, kun olet huoltamassa nimikkeitä, sinun täytyy syöttää tietoja vika-/ratkaisukoodien suhteista. Etsi **Syötä virhe-/ratkaisuk. suht.** -eräajon avulla kaikki kirjattujen huoltotilausten vika- ja ratkaisukoodiyhdistelmät ja kirjaa **Vika-/ratkaisukoodien suhteet** -sivulle. 
  
1. Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, kirjoita **Syötä virhe-/ratkaisuk. suht.** ja valitse sitten aiheeseen liittyvä linkki.  
2. Määritä eräajoon sisällytettävä ajanjakso antamalla päivämäärät.  
3. Ryhmittele suhteen huoltonimikeryhmän mukaan valitsemalla **Suhde perustuen huoltonimikeryhmään** -valintaruutu.  
4. Säilytä **Vika-/ratkaisukoodien suhteet** -sivulle manuaalisesti lisätyt tietueet valitsemalla **Säilytä manuaal. syöt. tietueet** -valintaruutu.  

## <a name="see-also"></a>Katso myös
[Huoltohallinnon määrittäminen](service-setup-service.md)  
[Service Management](service-service.md)  

