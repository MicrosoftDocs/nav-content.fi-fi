---
title: "Fyysisten varastojen järjesteleminen uudelleen"
description: "Haluat ehkä järjestellä fyysisen varaston uudelleen käyttämällä uusia varastopaikan koodeja ja uusia varastopaikan ominaispiirteitä."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 08/16/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 852aa1a36b150d13d763e2c398265b9eaec5c3ea
ms.contentlocale: fi-fi
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-restructure-warehouses"></a>Fyysisten varastojen järjesteleminen uudelleen
Haluat ehkä järjestellä fyysisen varaston uudelleen käyttämällä uusia varastopaikan koodeja ja uusia varastopaikan ominaispiirteitä. Tällaista toimintoa ei suoriteta kovin usein, mutta eteen voi tulla tilanteita, jolloin uudelleenluokittelu on tarpeen, jotta saavutettaisiin tai ylläpidettäisiin tehokkaampaa toimintaa. Esimerkiksi:  

- Haluat alkaa käyttää varastopaikkakoodeja, jotka tukevat automaattisen tiedonkeruun käyttöä esimerkiksi kannettavien laitteiden kanssa.  
- Fyysiseen varastoon on voitu ostaa uusi hyllyjärjestelmä, joka antaa uusia mahdollisuuksia nimikkeiden varastointiin.  
- Yritys on voinut muuttaa nimikevalikoimaa ja on siirtänyt fyysisen varaston uuteen paikkaan muutoksen mukaisesti.  

Jos fyysinen varasto käyttää varastopaikkoja, mutta ei ohjattua hyllytystä ja poimintaa, määritä fyysisen varaston rakenne uudelleen luomalla uudet varastopaikat, joita haluat käyttää tulevaisuudessa.  

## <a name="to-restructure-a-basic-warehouse-that-uses-bins-only"></a>Järjestele uudelleen perusvarastointi, joka käyttää vain varastopaikkoja  
1.  Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, kirjoita **Sijainnit** ja valitse sitten aiheeseen liittyvä linkki.  
2.  Määritä sijaintikortissa **Varastointi**-pikavälilehden **Oletus var.paikan valinta** -kentän arvoksi **Viim. käyt. var.paikka**.  
3.  Siirrä nykyisten varastopaikkojen koko sisältö juuri luomiisi uusiin varastopaikkoihin:  

    1.  Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, kirjoita **Nimikkeen uudelleenluokituspäiväkirja** ja valitse sitten aiheeseen liittyvä linkki.  
    2.  Valitse ensin päiväkirjarivi ja sitten **Hae var.paikan sisältö** -toiminto.  
    3.  Määritä **Varastopaikan sisältö**-pikavälilehden **Sijaintikoodi**-, **Varastopaikkakoodi**- ja **Nimikenro**-kentissä sisältö, jonka haluat siirtää.  
    4.  Valitse **OK** täyttääksesi päiväkirjarivin.  
    5.  Valitse kunkin rivin **Uusi varastopaikkakoodi** -kentässä varastopaikka, johon nimikkeet tulisi siirtää.  
    6.  Toista vaiheet b-e kaikille varastopaikan sisällöille, jotka haluat siirtää.  
    7.  Valitse **Kirjaa**-toiminto.  

Olet nyt tyhjentänyt varastopaikat, joissa nimikkeet olivat. Nimikkeiden oletusvarastopaikoiksi on nyt muutettu päiväkirjan riveillä määritetyt uudet varastopaikat.  

## <a name="to-restructure-an-advanced-warehouse-that-uses-directed-put-away-and-pick"></a>Järjestele uudelleen laajennettu varastointi, jossa on käytössä ohjattu hyllytys ja poiminta  

1.  Luo uudet varastopaikat, joita haluat käyttää jatkossa. Lisätietoja on kohdassa [Toimintaohje: Varastopaikkojen luominen](warehouse-how-to-create-individual-bins.md).  
2.  Siirrä nykyisten varastopaikkojen koko sisältö juuri luomiisi uusiin varastopaikkoihin:  

    1.  Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, kirjoita **F.var. uudelleenluokit. pvk:t** ja valitse sitten aiheeseen liittyvä linkki.  
    2.  Niiden varastopaikkojen osalta, joita ei koske mikään todellinen nimikkeiden siirto, luo rivi kullekin nykyiselle varastopaikalle  **F. var. uudelleenluokituspvk** -päiväkirjaan käyttäen vanhaa varastopaikkakoodia (**Var.paikasta)** ja uutta varastopaikkakoodia ( **Varastopaikkakoodiin**).  
    3.  Jos joihinkin siirtoihin kuuluu todellisia fyysisiä siirtoja, jotka haluat työntekijöiden suorittavan, käytä  **Var.siirtotyökirjoja** valmistellaksi siirto-ohjeita sen sijaan, että käyttäisit f- varaston uudelleenluokittelupäiväkirjaa. Lisätietoja on kohdassa [Nimikkeiden siirtäminen laajennetussa varastointimäärityksissä](warehouse-how-to-move-items-in-advanced-warehousing.md).  

3.  Kun vanhat varastopaikat on tyhjennetty, luokittele ne uudelleen **QC** -tyypin varastopaikoiksi varmistaaksesi, että ne eivät kuulu nimikevirtoihin.  

    1.  Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, kirjoita **Sijainnit** ja valitse sitten aiheeseen liittyvä linkki.  
    2.  Valitse ensin sijainnin rivi ja sitten **Varastopaikat**-toiminto.  
    3.  Anna **Varastopaikat**-ikkunan **Varastopaikkatyypin koodi** -kentässä koodi **QC** jokaiselle vanhalle varastopaikalle, jonka tyhjensit edellisen toimenpiteen vaiheessa 3.  

Olet nyt poistanut fyysisen varastoinnin virrasta varastopaikat ja luokitellut ne uudestaan QC-varastopaikoiksi. QC-varastopaikoiissa ei ole aktiviteetti-kenttiä **Varastopaikkatyypit** -ikkunassa valittuna ja näin ollen niitä ei huomioida nimikevirrassa. Lisätietoja on kohdassa [Varastopaikkojen määrittäminen](warehouse-how-to-set-up-bin-types.md).  

## <a name="to-delete-a-bin"></a>Varastopaikan poistaminen  

1.  Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, kirjoita **Sijainnit** ja valitse sitten aiheeseen liittyvä linkki.  
2.  Valitse sijainti, jossa haluat poistaa varastopaikkoja. Valitse **Varastopaikat**-toiminto.  
3.  Valitse poistettavien varastopaikkojen rivit.  
4.  Valitse **Poista**-toiminto.  

Jos napsautat **Kyllä**-painiketta, varastopaikka poistetaan käytöstä tulevaisuudessa, mutta varastopaikan koodi säilyy samana kaikissa fyysisen varastoinnin tapahtumissa.  

Jos haluat nimetä varastopaikan uudelleen, niin että myös kaikki varastopaikkaan tietueet nimetään uudelleen (tietueisiin kuuluvat varastopaikan sisältö, fyysisen varastoinnin toimintorivit, rekisteröidyt fyysisen varastoinnin toimintorivit, fyysisen varastoinnin työkirjarivit, fyysisen varastoinnin vastaanottorivit, kirjatut fyysisen varastoinnin vastaanottorivit, fyysisen varastoinnin toimitusrivit, kirjatut fyysisen varastoinnin toimitusrivit ja fyysisen varastoinnin tapahtumat), voit tehdä sen **Varastopaikat**-ikkunassa.  

## <a name="to-rename-a-bin-and-change-the-bin-code-in-all-records"></a>Varastopaikan nimeäminen uudelleen ja varastopaikkakoodin muuttaminen kaikkiin tietueisiin  

1.  Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, kirjoita **Sijainnit** ja valitse sitten aiheeseen liittyvä linkki.  
2.  Valitse sijainti, jonka varastopaikan haluat nimetä uudelleen tai jossa haluat muuttaa varastopaikkakoodia, ja valitse sitten **Varastopaikat**-toiminto.  
3.  Valitse se varastopaikka, jota haluat muuttaa. Syötä uusi varastopaikan koodi **Koodi**-kentässä.  
4.  Valitse **Kyllä**-painike.  

> [!NOTE]  
>  Jos napsautat **Kyllä** ja tätä varastopaikkaa koskevia tapahtumia on paljon (jos et ole esimerkiksi poistanut fyysisen varastoinnin asiakirjoja vähään aikaan), ohjelmalta voi kestää jonkin aikaa tietueiden uudelleennimeämisessä. Joten jos käytät tätä tapaa, harkitse **Poista rekisteröidyt f. var. asiakirjat** -eräajon ajamista ennen uudelleennimeämisprosessin aloittamista. Huomaa myös, että ainoat asiakirjat, joita tämä eräajo poistaa, ovat hyllytyksiä, poimintoja ja varastosiirtoja.  
>   
>  Jos olet nimeämässä uudelleen vastaanottavaa varastopaikkaa tai toimituksen varastopaikkaa, ohjelman täytyy nimetä uudelleen kaikki kirjatut vastaanotot tai toimitukset, jotka viittaavat kyseessä olevaan varastopaikkaan.  

## <a name="see-also"></a>Katso myös  
[Varastoinninhallinta](warehouse-manage-warehouse.md)  
[Vaihto-omaisuus](inventory-manage-inventory.md)  
[Varastoinninhallinnan määrittäminen](warehouse-setup-warehouse.md)     
[Kokoonpanon hallinta](assembly-assemble-items.md)    
[Rakennetiedot: Fyysisen varaston hallinta](design-details-warehouse-management.md)  
[[!INCLUDE[d365fin](includes/d365fin_md.md)] -ohjelman käyttäminen](ui-work-product.md)

