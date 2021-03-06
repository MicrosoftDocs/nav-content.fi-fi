---
title: "Tuotantoerän mittayksikön käyttäminen"
description: "Jos nimike varastoidaan yhtä mittayksikköä ja tuotetaan toista mittayksikköä käyttäen, tuotantotilauksen on käytettävä tuotantoerän mittayksikköä komponenttien oikean määrän laskemiseen. Tuotantoerän mittayksikön laskentaa voidaan tarvita esimerkiksi, kun nimike varastoidaan kappaleina mutta tuotetaan tonneina."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 09/14/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: cf0c91b076f473c12e61ce82d870a66e352c1920
ms.contentlocale: fi-fi
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-work-with-manufacturing-batch-units-of-measure"></a>Toimintaohje: Tuotantoerän mittayksiköiden käyttäminen
Jos nimike varastoidaan yhtä mittayksikköä ja tuotetaan toista mittayksikköä käyttäen, ohjelma voi laskea komponenttien oikean määrän **Päivitä tuotantotilaus** -eräajon aikana luomalla tuotantoerän mittayksikköä käyttävän tuotantotilauksen. Tuotantoerän mittayksikön laskentaa voidaan tarvita esimerkiksi, kun nimike varastoidaan kappaleina mutta tuotetaan tonneina.  

## <a name="to-create-a-production-bom-using-a-batch-unit-of-measure"></a>Tuotannon tuoterakenteen luominen erän mittayksikköä käyttäen  
1.  Tuotantoerän mittayksikkö määritetään vaihtoehtoiseksi mittayksiköksi tuotettavan nimikkeen **Nimikkeen mittayksiköt**-ikkunassa. Erän mittayksikkö ei korvaa nimikkeen perusmittayksikköä.  
2.  Luo tuotannon tuoterakenne nimikkeelle, johon on määritetty tuotantoerän mittayksikkö. Lisätietoja on kohdassa [Tuotannon tuoterakenteiden luominen](production-how-to-create-production-boms.md).  
3.  Napsauta **Mittayksikön koodi** -kenttää ja valitse tuotantoerän mittayksikön koodi.  
4.  Lisää tuotannon tuoterakenteen jokaiselle riville **Määrä per** -kenttään tämän komponenttinimikkeen määrä, joka tarvitaan tämän erän mittayksikön luomiseen.  
5.  Avaa liittyvän nimikkeen **Nimikkeen kortti**.  

    Valitse **Täydennys**-pikavälilehden **Tuotannon tuoterakenteen nro** -kentässä edellä luotu tuotannon tuoterakenne.  
6.  Luo tuotantotilauksen otsikko käyttäen nimikettä, johon on määritetty tuotantoerän mittayksikkö. Lisätietoja on kohdassa [Toimintaohje: Tuotantotilausten luominen](production-how-to-create-production-orders.md).  
7.  Valitse ensin **Päivitä**-toiminto ja sitten **OK**.  

Voit tarkastella tuloksia valitsemalla ensin **Rivit**-pikavälilehdessä **Rivi**- ja sitten **Komponentit**-toiminnon. Ohjelma laskee tuotantoerän mittayksikön perusteella oikean komponenttimäärän, jonka tuotannon tuoterakenne tarvitsee.  

## <a name="to-calculate-a-manufacturing-batch-unit-of-measure-on-a-production-order"></a>Tuotantotilauksen tuotantoerän mittayksikön laskeminen  
1.  Luo tuotantotilauksen otsikko käyttäen nimikettä, johon on määritetty tuotantoerän mittayksikkö.  
2.  Kirjoita otsikossa käytetty nimikkeen numero tuotantotilauksen rivin **Nimikkeen nro** -kenttään.  
3.  Lisää otsikossa käytetty määrä **Määrä**-kenttään.  
4.  Napsauta **Mittayksikön koodi** -kenttää ja valitse tuotantoerän mittayksikön koodi.  
5.  Valitse **Päivitä**-toiminto.
6.  Poista **Laske**-pikavälilehden **Rivit**-valintaruudun valinta.  
7.  Valitse **OK**-painike.  
8.  Voit tarkastella tuloksia valitsemalla ensin **Rivit**-pikavälilehdessä **Rivi**- ja sitten **Komponentit**-toiminnon. Ohjelma laskee tuotantoerän mittayksikön perusteella oikean komponenttimäärän, jonka tuotannon tuoterakenne tarvitsee.  

## <a name="see-also"></a>Katso myös  
[Toimintaohje: Uusien reititysten luominen](production-how-to-create-routings.md)  
[Toimintaohje: Tuotannon tuoterakenteiden luominen](production-how-to-create-production-boms.md)     
[Tuotannon määrittäminen](production-configure-production-processes.md)  
[Tuotanto](production-manage-manufacturing.md)    
[Suunnittelu](production-planning.md)   
[Vaihto-omaisuus](inventory-manage-inventory.md)  
[Osto](purchasing-manage-purchasing.md)  
[[!INCLUDE[d365fin](includes/d365fin_md.md)] -ohjelman käyttäminen](ui-work-product.md)  

