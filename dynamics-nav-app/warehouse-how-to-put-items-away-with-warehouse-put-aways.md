---
title: "Nimikkeiden hyllyttäminen ja fyysisen varaston hyllytykset"
description: "Kun sijainnissa on määritetty pakolliseksi fyysisen varastoinnin hyllytyksen ja vastaanoton käsittely, voit ohjata nimikkeiden hyllytystä fyysisen varastoinnin hyllytysasiakirjojen avulla."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 08/31/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 88a9513f12adf76cae8aabe8cbf58da0ac2b4ff3
ms.contentlocale: fi-fi
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-put-items-away-with-warehouse-put-aways"></a>Nimikkeiden hyllyttäminen ja fyysisen varaston hyllytykset
Kun fyysisen varastoinnin hyllytys- ja vastaanottokäsittely on määritetty sijainnissa pakolliseksi, voit ohjata nimikkeiden hyllytystä fyysisen varastoinnin hyllytysasiakirjojen avulla.  

Kun kirjaat fyysisen varastoinnin vastaanoton, ohjelma päivittää lähdeasiakirjat (ostotilauksen, saapuvan siirron tilauksen tai myyntipalautustilauksen), kirjaa vastaanotetun määrän nimikekirjauksiin ja lähettää vastaanotettuja nimikkeitä koskevat rivit fyysisen varastoinnin hyllytystoimintoon. Jos käytät sisäistä hyllytystä ja poimintaa, myös sisäinen hyllytys voi luoda rivejä hyllytystä varten.  

Fyysisen varastoinnin määritysten mukaan ohjelma ottaa rivit käyttöön hyllytystyökirjassa tai luo hyllytysohjeet välittömästi. Lisätietoja on kohdassa [Toimintaohje: Hyllytysten suunnitteleminen työkirjoissa](warehouse-how-to-plan-put-aways-in-worksheets.md).  

Tässä ohjeaiheessa kuvattujen fyysisen varaston hyllytysten luonnin vakiotapojen lisäksi voit luoda hyllytyksen liittyvästä kirjatusta fyysisen varaston vastaanotosta. Tämä on kätevää, jos olet poistanut hyllytysrivit tai jos käytät ohjattua hyllytystä ja poimintaa ja olet päättänyt olla käyttämättä hyllytystyökirjaa, koska voit luoda tai uudelleenluoda vastaanottorivien hyllytysohjeet.  

## <a name="to-put-items-away-without-directed-put-away-and-pick"></a>Nimikkeiden hyllytys ilman ohjattua hyllytystä ja poimintaa  
1.  Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, kirjoita **Hyllytykset** ja valitse sitten aiheeseen liittyvä linkki.  
2.  Avaa varastohyllytys, joka on valmis käsiteltäväksi.  

    Voit lajitella hyllytysrivejä eri kriteerien mukaan, esimerkiksi nimikkeen, hyllynumeron tai eräpäivän mukaan ja näin optimoida hyllytysprosessin.  
3.  Syötä kullakin rivillä **Käsiteltävä määrä** -kenttään määrä, jonka haluat hyllyttää.  
4.  Kun olet saanut nimikkeiden hyllytyksen valmiiksi, tallenna toiminnon valmistuminen ja määritä nimikkeet poimittaviksi valitsemalla **Rekisteröi hyllytys** -toiminto.  

## <a name="to-put-items-away-with-directed-put-away-and-pick"></a>Nimikkeiden hyllytys ohjatun hyllytyksen ja poiminnan avulla  
1.  Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, kirjoita **Hyllytykset** ja valitse sitten aiheeseen liittyvä linkki.
    Jos hyllytysohjeet on luotu, ikkunassa näkyy fyysisen varastoinnin hyllytys.  
2.  Avaa varastohyllytys, jota haluat käsitellä.  
3.  Jos fyysinen varastointi edellyttää sitä, kirjoita käyttäjätunnuksesi **Yleinen**-pikavälilehteen, kun aloitat tietyn hyllytyksen käsittelyn.  
4.  Suorita riveillä osoitetut (**Toiminnon tyyppi** -kentässä olevat) Ota- ja Aseta-toiminnot.  

    Huomaa, että kustakin vastaanoton rivistä on tullut vähintään kaksi riviä fyysisen varastoinnin hyllytykseen:  

    -   Ensimmäisellä rivillä, jolla **Toiminnon tyyppi** -kentässä on **Ota**, ilmaistaan, missä vastaanottoalueella nimikkeet sijaitsevat. Tällä rivillä olevia alue- ja varastopaikkakenttiä ei voi muuttaa.  
    -   Seuraavat rivit, joiden **Toiminnon tyyppi** -kentässä lukee **Aseta**, osoittavat, minne nimikkeet tulee asettaa fyysisessä varastossa. Jos fyysinen varastointi on vastaanottanut suuren määrän nimikkeitä yhdellä vastaanottorivillä, ohjelman on hyllytettävä ne useisiin varastopaikkoihin ja jokaiselle varastopaikalle on Aseta-rivi.  

        Jos kunkin vastaanottorivin Ota- ja Aseta-rivit eivät seuraa toisiaan välittömästi ja haluat niiden seuraavan toisiaan, voit järjestellä rivit valitsemalla **Yleinen**-pikavälilehden **Järjestämistapa**-kentässä **Nimike**.  

        Jos fyysisen varaston järjestys vastaa varastopaikkojen luokittelua, voit käyttää **Varastopaikan luokittelu** -järjestämistapaa valmistellaksesi hyllytyskierroksen, joka minimoi työvaiheet fyysisessä varastossa.  

5.  Kun olet asettanut kaikki nimikkeet varastopaikkoihin ohjeiden mukaisesti, valitse **Rekisteröi hyllytys** -toiminto.  

Paikoissa, jotka on määritetty käyttämään ohjattua hyllytystä ja poimintaa, seuraavat asetukset ovat edellytykset yllä mainittua menettelyä varten:  

- Hyllytysmallien määrittäminen: Lisätietoja on kohdassa [Toimintaohje: Hyllytysmallien määrittäminen](warehouse-how-to-set-up-put-away-templates.md).  
- Nimikkeen tai varastointiyksikön paino, tilavuus ja varastoinnin erityisvaatimukset määritetään. Lisätietoja on myös kohdassa Bruttopaino.  
- Kapasiteetti, varastopaikan tyyppi ja varastopaikkojen paikkaluokittelu. Lisätietoja on kohdassa Varastopaikan luokittelu.  

Kun hyllytysmallin ehtoja vastaavia varastopaikkoja on useita, ohjelma käyttää varastopaikan luokittelua. Jos sekä hyllytysmallin ehdot että varastopaikan luokittelu ovat samat useissa varastopaikoissa, ohjelma valitsee varastopaikan, jonka numero on suurin.

## <a name="to-create-a-put-away-from-a-posted-receipt"></a>Luo hyllytys kirjatusta vastaanotosta  
 Jos sijainnissa käytetään sekä hyllytyskäsittelyä että vastaanoton käsittelyä ja olet poistanut hyllytysrivit tai jos käytät ohjattua hyllytystä ja poimintaa ja olet päättänyt olla käyttämättä hyllytystyökirjaa, voit luoda tai uudelleenluoda kirjattujen vastaanottorivien hyllytysohjeet.

1.  Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, kirjoita **Kirjatut fyysisen varastoinnin vastaanotot** ja valitse sitten aiheeseen liittyvä linkki.  
2.  Valitse kirjattu vastaanotto, joka täytyy ehkä hyllyttää.  
3.  Valitse **Kortti**-toiminto.  

    Jos **Asiakirjan tila** -kenttä on tyhjä, vastaanottoa ei ole hyllytetty ollenkaan. Muutoin kenttä ilmaisee, että vastaanotto hyllytetään osittain tai kokonaan.  

4.  Jos vastaanotto on hyllytetty osittain tai sitä ei ole hyllytetty lainkaan, valitse **Luo hyllytys** -toiminto.  
5.  Täytä eräajon pyyntöikkuna haluamasi kaltaisen hyllytyksen luomista varten ja valitse **OK**-painike.   

## <a name="see-also"></a>Katso myös  
[Varastoinninhallinta](warehouse-manage-warehouse.md)  
[Vaihto-omaisuus](inventory-manage-inventory.md)  
[Varastoinninhallinnan määrittäminen](warehouse-setup-warehouse.md)     
[Kokoonpanon hallinta](assembly-assemble-items.md)    
[Rakennetiedot: Fyysisen varaston hallinta](design-details-warehouse-management.md)  
[[!INCLUDE[d365fin](includes/d365fin_md.md)] -ohjelman käyttäminen](ui-work-product.md)

