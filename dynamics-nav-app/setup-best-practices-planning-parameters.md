---
title: "Asetukset - parhaat käytännöt - suunnitteluparametrit"
description: "Nimikkeen kortin **Suunnittelu**-pikavälilehti on yrityksen toimitusketjun keskus. Oikeiden suunnitteluparametrien määrittäminen on erittäin tärkeää kustannustehokkaan varastonhallinnan ja hyvän asiakaspalvelun vuoksi."
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 09/08/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 8ea9ceaffa7a82405c43783d2a22f0b81ec4600d
ms.contentlocale: fi-fi
ms.lasthandoff: 10/16/2017

---
# <a name="setup-best-practices-planning-parameters"></a>Asetukset - parhaat käytännöt: suunnitteluparametrit
**Suunnittelu**-pikavälilehti nimikkeen kortissa on yrityksen toimitusketjun keskus. Oikeiden suunnitteluparametrien määrittäminen on erittäin tärkeää kustannustehokkaan varastonhallinnan ja hyvän asiakaspalvelun vuoksi.  

 Seuraavassa taulukossa on parhaita käytäntöjä siitä, miten voit määrittää valitun suunnitteluparametrin kentät. Saat lisätietoja kentästä valitsemalla **Asetuskenttä**-sarakkeessa olevan linkin.  

|Kentän asetukset|Parhaat käytännöt|Kommentti|  
|-----------------|-------------------|-------------|  
|Uusintatilaustapa||Lisätietoja on ohjeaiheessa [Asetukset - parhaat käytännöt: uusintatilaustavat](setup-best-practices-reordering-policies.md).|  
|Varaa|Valitse **ei koskaan**, kun nimike suunnitellaan käyttämällä uusintatilauspistettä.<br /><br /> Valitse tuotannon **Ei koskaan** -kohta, kun haluat sallia suunnittelujärjestelmän kaikille kysynnöille.<br /><br /> Valitse **valinnainen** kohteille, jotka haluat ehkä varata ylimmän prioriteetin asiakkaille.<br /><br /> Valitse **Aina** muille kuin yksilöllisille nimikkeille, kuten sekalainen, jotka ovat tulevia, erityisvaatimuksia sisältäviä nimikkeitä.|Varaukset neutraloivat suunnittelun tarkoitusta, joka tasapainottaa kysyntää ja tarjontaa. Tämän vuoksi nimikkeitä, jotka on määritetty suunnittelussa, ei yleensä pidä varata.<br /><br /> Jos käyttäjä varaa varastomäärää tulevaa kysyntää varten, suunnittelun perusta häiriintyy ja uusintatilauspiste ei ehkä toimi oikein. Vaikka oletettu varastotaso on hyväksyttävä suhteessa uusintatilauspisteeseen, määrät eivät ehkä ole käytettävissä varauksen vuoksi.|  
|Puskuriaika|Määritä ottaen huomioon toimittajan joustavuuden.|Jos toimittaja hyväksyy tilauksiin tehtävät viime hetken muutokset, käytä pidempää jaksoa. Jos toimittaja vaatii sitovan suunnittelun, lyhennä jaksoa mahdollisimman paljon.<br /><br /> Lisätietoja yleisistä asetuksista on kohdassa [Rakennetiedot: Suunnittelun parametrit](design-details-planning-parameters.md).|  
|Puskurimäärä||Lisätietoja yleisistä asetuksista on kohdassa [Rakennetiedot: Suunnittelun parametrit](design-details-planning-parameters.md).|  
|Sisällytä varasto|Valitse aina, kun käytät uusintatilaustapaa Erä-erästä.|Älä valitse vain erityistilanteissa, esimerkiksi, kun varastonimikkeet eivät ole myytäviä.|  
|Toimitusajan varmistus|Valitse 1D tai 6D.<br /><br /> Määritä vähintään yhden päivän toimitusajan varmistus varmistaaksesi, että toimitukset ovat käytettävissä päivää ennen kuin niitä tarvitaan.<br /><br /> Jos kyseessä on uusi toimittaja, määritä aika normaalia pidemmäksi niin pitkäksi aikaa, kunnes toimittajan toimitussuorituskyky tunnetaan.<br /><br /> Määritä tuotannon kriittisille komponenteille pidemmät toimitusajan varmistukset.|Järjestelmän suunnittelema tarjonta, jolla vältetään varaston loppuminen, saapuu sinä päivänä, jona varasto loppuisi. Tämä voi olla useita tunteja myöhässä, jos esimerkiksi kysyntä tarvitaan aamulla ja tarjonta saapuu iltapäivällä. **Huomautus:**  **Toimitusajan varmistus** -kenttä käyttää peruskalenteria. 14 D ei välttämättä ole kahta viikkoa.|  
|Varmuusvaraston määrä|Käyttää nimikkeisiin, joissa on suuria vaihteluita.<br /><br /> Käytä tuotannon kriittisissä komponenteissa.<br /><br /> Käytä nimkikeisiin, joissa on huoltosopimukset.|Jos **Uusintatilauspiste**-kenttään ei ole määritetty arvoa, varmuusvaraston määrä toimii myös uusintatilauspisteenä.|  
|Erän koontijakso|Jos haluat vain muutamia suuria tilauksia ja hyväksyt varastoinnin, määritä pitkä erän koontijakso.<br /><br /> Jos haluat useita pieniä tilauksia ja mahdollisimman pienen varaston, määritä lyhyt erän koontijakso.|Erän koontijakso on yleensä pisin varastointiaika.|  
|Uusintatilauspiste|Perusta uusintatilauspiste nimikkeen kysynnän profiiliin.|Jos historiatiedot osoittavat, että nimikkeen keskimääräinen kysyntä seitsemän päivän toimitusajan aikana on 100 yksikköä, uudelleentilauspisteen vähimmäisarvoksi voidaan määrittää 100.<br /><br /> Tämä tarkoittaa, että kun varastotaso laskee "Vaiheet ongelman toistamiseen" -osassa alle 100 yksikköön, suunnittelujärjestelmä ehdottaa täydennystä, koska täydennys vie seitsemän päivää, ja varastotason on oltava riittävä, jotta se kattaa noiden seitsemän päivän aikana ilmenevän nimikkeiden kysynnän.|  
|Aikaväli|Jätä tyhjäksi, mikä tarkoittaa, että varastotaso tarkistetaan joka päivä.|Varastotason päivittäinen tarkistus varmistaa optimaalisen uudelleentilauksen suunnittelun. **Huomautus:**  Aikaväli 1V tarkoittaa sitä, että varastotaso saattaa olla alle uusintatilauspisteen yksi viikko ennen kuin toimitustilausta ehdotetaan.|  
|Pyöristystarkkuus|Jos kyseessä on kallis tuotanto, määritä arvoksi 0,00001.|Jätteen tai materiaalikulutuksen suuret pyöristysmäärät voivat aiheuttaa erittäin suuria varastokustannuksia. Siksi saattaa olla tarpeen määrittää pienin pyöristystarkkuus tämän mahdollisen kustannuksen minimoimiseksi.|  

> [!NOTE]  
>  Nimikekorttien suunnitteluparametrien parhaita käytäntöjä sovelletaan myös SKU-korttien samoihin kenttiin.  
>   
>  Jos yritykset suunnittelevat kysyntää eri sijainneissa, on suositeltavaa määrittää jokaiselle sijainnille varastointiyksiköt ja luoda kaikki kysyntä **Sijainnin koodi** -kentän arvon avulla. Katso lisätiedot kohdasta [Rakennetiedot: kysyntä tyhjä-sijainnissa](design-details-demand-at-blank-location.md).  

## <a name="see-also"></a>Katso myös  
 [Asetusten parhaat käytännöt: toimitusten suunnittelu](setup-best-practices-supply-planning.md)   
 [Rakennetiedot: Toimitusten suunnittelu](design-details-supply-planning.md)   
 [Monimutkaisten sovellusalueiden määrittäminen parhaiden käytäntöjen avulla](set-up-complex-application-areas-using-best-practices.md)  
 [[!INCLUDE[d365fin](includes/d365fin_md.md)] -ohjelman käyttäminen](ui-work-product.md)

