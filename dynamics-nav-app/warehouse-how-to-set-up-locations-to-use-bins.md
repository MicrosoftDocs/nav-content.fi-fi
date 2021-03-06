---
title: "Sijaintien määrittäminen varastopaikkojen käyttämistä varten"
description: "Varastopaikat ovat varastoinnin perusrakenne, ja niitä niillä ehdotetaan nimikkeiden sijoittelua. Kun olet luonut varastopaikat, voit määrittää hyvin tarkkaan sisällön, jonka haluat ohjelman sijoittavan kuhunkin varastopaikkaan, tai varastopaikka voi toimia määrittelemättömänä varastopaikkana, jolla ei ole määritettyä sisältöä."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 09/23/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 95b36b6eed79da868c1e41905110788c90f24829
ms.contentlocale: fi-fi
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-set-up-locations-to-use-bins"></a>Sijaintien määrittäminen varastopaikkojen käyttämistä varten
Varastopaikat ovat varastoinnin perusrakenne, ja niitä niillä ehdotetaan nimikkeiden sijoittelua. Kun olet luonut varastopaikat, voit määrittää hyvin tarkkaan sisällön, jonka haluat ohjelman sijoittavan kuhunkin varastopaikkaan, tai varastopaikka voi toimia määrittelemättömänä varastopaikkana, jolla ei ole määritettyä sisältöä.  

A. Jotta voisit käyttää varastopaikan toimintoja sijainnissa, ne on otettava käyttöön **Sijainti**-kortissa Sitten voi suunnitella nimikevirran sijainnissa määrittämällä varastopaikkakoodit määrityskentistä, jotka edustavat eri virtoja.  

> [!NOTE]  
>  Ennen kuin voit määrittää varastopaikkakoodeja sijaintikortissa, on luotava varastopaikkakoodit. Lisätietoja on kohdassa [Toimintaohje: Varastopaikkojen luominen](warehouse-how-to-create-individual-bins.md).  

## <a name="to-set-up-a-location-to-use-bins"></a>Määritä sijainti käyttääksesi varastopaikkoja  
1.  Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, kirjoita **Sijainnit** ja valitse sitten aiheeseen liittyvä linkki.  
2.  Valitse sijainti, jossa haluat käyttää varastopaikkoja.  
3.  Valitse **Muokkaa** -toiminto.  
4.  Valitse **Fyysinen varasto** -pikavälilehdessä **Var.paikka pakollinen** -valintaruutu.  
5.  Jos et käytä ohjattua hyllytystä ja poimintaa sijainnissa, kirjoita **Oletusvar.paikan valinta** -kenttään menetelmä, jolla haluat järjestelmän määrittävän nimikkeelle oletusvarastopaikan.  
6.  Avaa sen sijainnin kortti, johon haluat määrittää varastopaikkoja.
7.  Valitse **Varastopaikat**-pikavälilehdessä varastopaikat, joita haluat käyttää oletuksena vastaanotoille, toimituksille sekä saapuville, lähteville ja avoimille tuotannon varastopaikoille.  
8.  Tähän täyttämäsi varastopaikkakoodit tulevat automaattisesti näkyviin useiden eri fyysisen varastoinnin asiakirjojen otsikoihin (ja sitä myötä myös riveille, ellet muuta niitä). Oletusarvoiset varastopaikat määrittelevät nimikkeiden kaikki alku- ja loppusijoitukset fyysisessä varastossa.  
9.  Jos käytät ohjattua hyllytystä ja poimintaa, valitse varastopaikka fyysisen varastoinnin muutoksille. Varastopaikkakoodi **Muutosvarastopaikan koodi** -kentässä määrittää virtuaalisen varastopaikan, johon tallennetaan eroavaisuudet silloin, kun kirjataan joko varaston nimikepäiväkirjassa havaittuja eroja tai varaston inventoinnin yhteydessä laskettuja eroja.  
10. Täytä **Var.paikkojen periaatteet** -pikavälilehden kentät, jotka ovat olennaisia käytetyn fyysisen varastoinnin kannalta. Tärkeimmät kentät ovat **Var.paikan kapasiteettitapa,****Salli erottelu** ja **Hyllytysmallin koodi**.  
11. Täytä **F. varastointi** -pikavälilehdessä kentät **Lähtevä f. var. käsittelyaika**, **Saapuva f. var. käsittelyaika** ja  **Peruskalenterin koodi**. Lisätietoja on kohdassa [Toimintaohje: Peruskalentereiden määrittäminen](across-how-to-assign-base-calendars.md).

## <a name="filling-the-consumption-bin"></a>Kulutuksen varastopaikan täyttäminen
Tämä työnkulkukaavio näyttää, miten tuotantotilauksen osarivien**Varastopaikkakoodi**-kenttä täytetään sijaintiasetusten mukaisesti.

![Varastopaikkojen vuokaavio](media/binflow.png "BinFlow")  

## <a name="see-also"></a>Katso myös
[Varastoinninhallinta](warehouse-manage-warehouse.md)  
[Vaihto-omaisuus](inventory-manage-inventory.md)  
[Varastoinninhallinnan määrittäminen](warehouse-setup-warehouse.md)     
[Kokoonpanon hallinta](assembly-assemble-items.md)    
[Rakennetiedot: Fyysisen varaston hallinta](design-details-warehouse-management.md)  
[[!INCLUDE[d365fin](includes/d365fin_md.md)] -ohjelman käyttäminen](ui-work-product.md)

