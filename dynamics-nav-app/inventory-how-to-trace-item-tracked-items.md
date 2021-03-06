---
title: "Nimikeseurannan nimikkeiden jäljittäminen"
description: "Näet, missä nimikeseurannassa olevaa nimikettä on käytetty, mukaan lukien kuinka ja missö se oli vastaanotettu tai tuotettu, siirretty, myyty, kulutettu tai palautettu. Voit myös etsiä kaikki nykyiset esiintymät tietystä sarja- tai eränumerosta tietokannassa. Voit tehdä tämän käyttämällä nimikkeen jäljitystä ja Navigoi-toimintoja."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 07/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: b9b1f062ee6009f34698ea2cf33bc25bdd5b11e4
ms.openlocfilehash: 6d25a7b60f8b1b37ef9de34d5ffc098a89828ea8
ms.contentlocale: fi-fi
ms.lasthandoff: 10/23/2017

---
# <a name="how-to-trace-item-tracked-items"></a>Nimikeseurannan nimikkeiden jäljittäminen
Näet, missä nimikeseurannassa olevaa nimikettä on käytetty, mukaan lukien miten ja missä se oli vastaanotettu tai tuotettu, siirretty, myyty, kulutettu tai palautettu. Voit myös etsiä kaikki nykyiset esiintymät tietystä sarja- tai eränumerosta tietokannassa. Voit tehdä tämän käyttämällä nimikkeen jäljitystä ja Navigoi-toimintoja.  

 Nämä toiminnot ovat erityisen hyödyllisiä laaduntarkkailussa, kun haluat tietää, kuka asiakas vastaanotti tietyllä eränumerolla olevia tuotteita tai mihin erään viallinen komponentti kuuluu.  

 Voit jäljittää **Nimikkeen jäljitys** -ikkunassa sarja- tai eränumeron järjestyksessä eteenpäin ja taaksepäin kirjatuissa varastotapahtumissa.  

 **Navigoi**-ikkunassa ei näy tapahtumien järjestystä, mutta näet kuitenkin sarja- tai eränumeron kaikki tietueet – sekä kirjatut tapahtumat että avatut tietueet.  

 Kahta ominaisuutta voi käyttää yhdessä siirtämällä jäljitetty sarja- tai eränumero **Navigoi**-ikkunaan ja viimeistelemään jäljitystilanne. Lisätietoja on kohdassa [Vaihekuvaus: Sarja- ja eränumeroiden jäljitys](walkthrough-tracing-serial-lot-numbers.md).  

## <a name="to-trace-item-tracked-items"></a>Nimikeseurannan nimikkeiden jäljittäminen  

1.  Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, kirjoita **Nimikkeen jäljitys** ja valitse sitten aiheeseen liittyvä linkki.  
2.  Syötä ikkunan yläosan suodatinkenttiin tietyt nimikenumerot tai niiden nimikenumeroiden suodatin, joita haluat jäljittää.  
3.  Valitse **Näytä komponentit** -kentässä, haluatko tarkastaa myös sen, mistä nimikkeiden komponentit ovat lähtöisin. Vaihtoehtosi tässä kentässä ovat seuraavat.  

    |Kenttä|Description|  
    |----------------------------------|---------------------------------------|  
    |**Nro**|Valitse tämä vaihtoehto, jos et halua tarkastella komponentteja.|  
    |**Vain nimikeseuranta**|Valitse tämä vaihtoehto, jos haluat tarkastella vain niitä komponentteja, joilla on erä- tai sarjanumeroita.|  
    |**Kaikki**|Valitse tämä vaihtoehto, jos haluat tarkastella kaikkia komponentteja.|  

4.  Valitse **Jäljitysmenetelmä**-kentässä menetelmä, jota haluat ohjelman käyttävän nimikkeen jäljityksessä. Käytettävissä ovat seuraavat vaihtoehdot  

    |Kenttä|Description|  
    |----------------------------------|---------------------------------------|  
    |**Käyttö->alkuperä**|Tämä menetelmä jäljittää nimikettä lähtien siitä paikasta, josta sitä käytettiin, siihen paikkaan, josta se tuli. Jos esimerkiksi valmistettu nimike myytiin asiakkaalle, **Nimikkeen jäljitys** -ikkunassa näkyvät nämä tiedot niin, että lähtevän toimituksen rivi on ensimmäisenä. Voit laajentaa näkymää, jos haluat nähdä, mistä tuotantotilauksesta se tuli.|  
    |**Alkuperä-> Käyttö**|Tämä menetelmä jäljittää nimikettä lähtien siitä paikasta, josta se tuli varastoon, siihen paikkaan, jossa sitä käytettiin. Jos esimerkiksi valmistettu nimike myytiin asiakkaalle, **Nimikkeen jäljitys** -ikkunassa näkyvät nämä tiedot niin, että valmis tuotantotilaus on ensimmäisenä. Voit laajentaa näkymää, jos haluat nähdä ne lähtevän toimituksen rivit, joissa nimikettä käytettiin.|  

5.  Suorita jäljitys valitsemalla **Jäljitys**.  

> [!NOTE]  
>  Jos olet vastaanottanut saman erän useissa tapahtumissa, kaikki tapahtumat eivät ehkä näy **Nimikkeen jäljitys** -ikkunassa. Näytetään vain kohdistetut tapahtumat.  

> [!NOTE]  
>  Jos jäljitysrivin yläpuolinen rivi on jo jäljittänyt lisätapahtumahistorian, **Jo jäljitetty** -valintaruutu on valittuna. Yksinkertaisemman näkymän tarjoavia alla olevia rivejä ei näytetä.  
>   
>  Etsi kohteen jäljitysrivejä, joissa tapahtumahistoria on jo jäljitetty, ja valitse **Siirry jo jäljitetty** -painike. Nimikkeen jäljitysrivi on valittu, ja kaikki pohjana olevat rivit on laajennettu.  

## <a name="to-find-item-tracked-items-with-navigate"></a>Voit etsiä nimikeseurannassa olevia nimikkeitä Navigoi-toiminnolla  

1.  Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, kirjoita **Navigoi** ja valitse sitten aiheeseen liittyvä linkki.  
2.  Anna **Nimikeseuranta**-pikavälilehden **Sarjanumero**- ja **Eränro**-kenttiin nimikeseurantanumerot, joita haluat seurata.  
3.  Etsi kaikki sarja- tai eränumeron ilmentymät tietokannasta valitsemalla **Etsi**-toiminto.  

## <a name="see-also"></a>Katso myös  
[Vaihto-omaisuus](inventory-manage-inventory.md)  
[Rakennetiedot: Nimikkeen seuranta](design-details-item-tracking.md)
[Rakennetiedot: Nimikkeen seuranta ja varaukset](design-details-item-tracking-and-reservations.md)  
[Toimintaohje: Nimikkeiden varaaminen](inventory-how-to-reserve-items.md)  
[[!INCLUDE[d365fin](includes/d365fin_md.md)]in käyttäminen](ui-work-product.md)
[Vaihekuvaus: Sarja- ja eränumeroiden jäljitys](walkthrough-tracing-serial-lot-numbers.md)

