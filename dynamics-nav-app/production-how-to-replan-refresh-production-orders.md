---
title: "Tuotantotilausten suora uudelleensuunnittelu tai päivittäminen"
description: "Tuotantotilauksen rivit sisältävät nimikkeet, jotka tuotetaan tuotantotilauksessa."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 09/06/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 424fddfb1f92f426badec5477267be7477c3be22
ms.contentlocale: fi-fi
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-replan-or-refresh-production-orders-directly"></a>Toimintaohje: Tuotantotilausten suora uudelleensuunnittelu tai päivittäminen
Tuotantotilausten **Uudelleensuunnittelu**-toimintoa käytetään yleensä sen jälkeen, kun alemman tason tuotantotilauksiin vaikuttavia komponentteja on lisätty tai muutettu. Toiminto laskee komponentti- ja reititysriveille tehdyt muutokset. Toiminto vaikuttaa myös tuotannon tuoterakenteen alitasoihin, joille saatetaan luoda uusia tuotantotilauksia.  

Uudelleensuunnittelutoiminto laskee ja suunnittelee tuotantotilauksen uuden kysynnän komponentti- ja reititysriveille tehtyjen muutosten perusteella.  

Tuotantotilausten **Päivitä**-toimintoa käytetään yleensä sen jälkeen, kun jokin seuraavista on tehty:

- luotu tuotantotilauksen otsikko manuaalisesti – tällöin rivien tiedot luodaan ja lasketaan ensimmäistä kertaa
- Tehty muutoksia tuotantotilauksen otsikkoon – tällöin kaikkien rivien tiedot lasketaan uudelleen.

Päivitystoiminto laskee tuotantotilauksen otsikkotietoihin tehdyt muutokset. Toiminto ei vaikuta tuotannon tuoterakennetasoihin. Toiminto laskee ja valmistelee komponenttirivien ja reititysrivien arvot määritetyn tuotannon tuoterakenteen ja reitityksen päätietojen sekä tuotantotilauksen otsikon sisältämän tilausmäärän ja eräpäivän mukaan.

Tuotantotilausrivit voidaan syöttää joko manuaalisesti tai voidaan käyttää toimintoa, joka laskee tuotantotilausrivit otsikosta.  

> [!NOTE]
 Jos päivitystoimintoa käytetään laskemaan tuotantotilausrivit uudelleen, ohjelma poistaa vanhat tuotantotilausrivit ja laskee uudet rivit.  

## <a name="to-replan-a-production-order"></a>Tuotantotilauksen uudelleensuunnittelu  
1.  Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, kirjoita **Sitovasti suunn. tuotantotil.** ja valitse sitten aiheeseen liittyvä linkki.  
2.  Avaa uudelleensuunniteltava tuotantotilausrivi.  
3.  Valitse **Rivit**-pikavälilehdessä ensin **Rivit**-toiminto ja sitten **Komponentit**-toiminto.  
4.  Lisää komponentti, joka on tuotantonimeke (osakokoonpano).  
5.  Valitse tuotantotilauksessa **Uudelleensuunnittele**-toiminto.  

    Siirry **Uudelleensuunnittele tuot.til.** -ikkunaan määrittämään, mitä uudelleensuunnitellaan ja miten se tehdään.  
6.  Valitse **Aikataulutuksen suunta** -kentässä jokin seuraavista vaihtoehdoista:  

    |Asetus|Description|  
    |----------------------------------|---------------------------------------|  
    |**Takaisin**|Taaksepäin – operaatiot lasketaan järjestyksessä taaksepäin aikaisimmasta mahdollisesta lopetuspäivämäärästä (määräytyy eräpäivän ja/tai muiden aikataulutettujen tilausten mukaan) myöhäisimpään mahdolliseen aloituspäivämäärään. **Huomautus:**  Tämä oletusvaihtoehto soveltuu useimpiin tilanteisiin.|  
    |**Eteenpäin**|Operaatiot lasketaan järjestyksessä eteenpäin myöhäisimmästä mahdollisesta aloituspäivämäärästä (määräytyy eräpäivän ja/tai muiden aikataulutettujen tilausten mukaan) aikaisimpaan mahdolliseen lopetuspäivämäärään. **Huomautus:**  Tämä vaihtoehto soveltuu vain tilauksiin, jotka halutaan tehdä niin pian kuin mahdollista.|  

7.  Valitse **Suunnittele**-kentästä, lasketaanko tuotantotarpeet tuotannon tuoterakenteen tuotantonimikkeille seuraavasti:  

    |Asetus|Description|  
    |----------------------------------|---------------------------------------|  
    |**Ei tasoja**|Alempien tasojen tuotantoa ei oteta huomioon. Vain nimikkeen aikataulu päivitetään (kuten päivitystoiminnossa).|  
    |**Yksi taso**|Suunnittele ensimmäisen tason tuotantokysyntä. Ensimmäisen tason tuotantotilauksia voidaan luoda kaikille tasoille.|  
    |**Kaikki tasot.**|Suunnittele kaikkien tasojen tuotantokysyntä. Tuotantotilauksia voidaan luoda kaikille tasoille.|  

8.  Valitse **Yksi taso** ja valitse **OK**, niin tuotantotilaus suunnitellaan uudelleen ja ohjelma laskee ja luo uuden alemman tason tuotantotilauksen uudelle osakokoonpanolle, jos osakokoonpano ei ole kokonaisuudessaan saatavilla  

> [!NOTE]  
>  **Uudelleensuunnittelutoiminnolla** tehdyt muutokset muuttavat hyvin todennäköisesti myös tuotantotilauksen kapasiteettitarvetta, joten operaatioiden aikatauluja saatetaan joutua muuttamaan päivityksen jälkeen  

## <a name="to-refresh-a-production-order"></a>Tuotantotilauksen päivittäminen  
Jos olet muuttanut tuotantotilausrivejä, komponentteja tai reititysrivejä, myös tuotantotilauksen tiedot on päivitettävä. Seuraavassa toimenpiteessä komponentit lasketaan sitovasti suunnitellulle tuotantotilaukselle. Reititysrivejä koskevat vaiheet ovat samanlaisia.

1.  Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, kirjoita **Sitovasti suun. tuotantotil.** ja valitse sitten aiheeseen liittyvä linkki.  
2.  Valitse **Uusi**-toiminto. Lisätietoja on kohdassa [Toimintaohje: Tuotantotilausten luominen](production-how-to-create-production-orders.md).  
3.  Valitse **Päivitä**-toiminto.
4. Valitse **Päivitä tuotantotilaus** -ikkunassa jokin seuraavista vaihtoehdoista:

    |Asetus|Description|  
    |----------------------------------|---------------|---------------------------------------|  
    |**Aikataulutuksen suunta**|**Eteenpäin**|Aikataulutus alkaa aloituspäivämäärästä ja jatkuu eteenpäin (lopetuspäivämäärään saakka). Tämän valinnan käyttäminen edellyttää, että määrität aloituspäivämäärän.|  
    ||**Taaksepäin**|Aikataulutus alkaa lopetuspäivämäärästä ja jatkuu taaksepäin (aloituspäivämäärään asti).|  
    |**Laske**|**Rivit**|Valitsemalla tämän kentän voit laskea tuotantotilauksen rivit.|  
    ||**Reititykset**|Tällä kentällä ei ole vaikutusta tuotantorivien laskemiseen.|  
    ||**Komponenttitarve**|Tällä kentällä ei ole vaikutusta tuotantorivien laskemiseen.|  
    |**F. varastointi**|**Luo saapuva pyyntö**|Tällä kentällä ei ole vaikutusta tuotantorivien laskemiseen.|  

5. Valitse **OK**-painike vahvistaaksesi valintasi. Tuotantotilausrivit on nyt laskettu.

> [!NOTE]  
>  Tuotantotilauksen komponenttien laskeminen poistaa aiemmat komponenttien muutokset.

## <a name="see-also"></a>Katso myös  
[Suunnittelu](production-planning.md)  
[Tuotannon määrittäminen](production-configure-production-processes.md)  
[Tuotanto](production-manage-manufacturing.md)    
[Vaihto-omaisuus](inventory-manage-inventory.md)  
[Osto](purchasing-manage-purchasing.md)  
[Rakennetiedot: Toimitusten suunnittelu](design-details-supply-planning.md)   
[Parhaiden käytäntöjen määrittäminen: Toimitusten suunnittelu](setup-best-practices-supply-planning.md)  
[[!INCLUDE[d365fin](includes/d365fin_md.md)] -ohjelman käyttäminen](ui-work-product.md)

