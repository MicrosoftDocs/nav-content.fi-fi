---
title: 'Toimintaohje: Projektibudjettien hallinta'
author: SorenGP
ms.custom: na
ms.date: 11/01/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: c28e23c4ae0082265357a567ea82795b77ac8f1c
ms.contentlocale: fi-fi
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-manage-job-budgets"></a>Toimintaohje: Projektibudjettien hallinta
Jokaiselle projektille voi määrittää budjetin. Budjettia käytetään projektille kohdistettavien resurssien suunnittelussa. Budjetti voi olla joko yleisluonteinen budjetti, joka sisältää vain vähän tapahtumia, tai se voi sisältää monia tapahtumia, jotka on jaettu toimintotasoille. Voit verrata budjetoituja summia projektipäiväkirjaan kirjattuun todelliseen käyttöön. Kun valvot todellisen ja budjetoidun käytön välisiä eroja, voit hallita suoritettavaa projektia ja parantaa tulevien projektien laatua pienentämällä kustannusten aliarvioinnin riskiä.

Seuraavissa ohjeissa kerrotaan, miten budjetoituja kustannuksia arvioidaan suunnittelun aikana. Lisätietoja budjetoitujen ja todellisten projektihintojen ja -kustannusten kirjaamisesta on kohdassa [Toimintaohje: Projektien käytön kirjaaminen](projects-how-record-job-usage.md).  

## <a name="JobBudgetCosts"></a> Projektin budjetoitujen kustannusten arvioiminen  
Kun asiakas haluaa tietää sellaisen projektin hinnan, joka laskutetaan käytön perusteella, on määritettävä projektin budjetoidut kustannukset. Tähän käytetään **Projektitehtävärivit**-ikkunaa.

1. Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Projektit** ja valitse sitten aiheeseen liittyvä linkki.  
2. Avaa asianmukainen projekti.
3. Valitse tehtävärivin tyypiksi Kirjaus ja valitse sitten **Projektin suunnittelurivit** -toiminto.
4. Täytä tarvittaessa uuden rivin kentät. Lue kentän lyhyt kuvaus valitsemalla kenttä tai siirry lisätietoihin valitsemalla linkki.   

Viittaa **Rivityyppi**-kentässä seuraaviin tietoihin.  

|Rivityyppi |Kuvaus |
|----------|------------|
|**Sekä budjetti että laskutettava**|Suunnitteluriville annetut kustannus- ja hintasummat ovat tämän suunnittelurivin budjetoidut kustannukset sekä laskutettava hinta. Hinnaston summa laskutetaan.|
|**Budjetti**|Asiakasta ei veloiteta käytöstä. Sitä ei voida koskaan siirtää laskuun, mutta käytetään edelleen KET-laskennassa.|
|**Laskutettava**|Asiakasta veloitetaan käytöstä. Käyttö siirretään laskuun Laskuun siirrettävä määrä -kentässä määritetyn määrän perusteella.|

**Huomautus**: Suunnittelurivin **Suunnittelupäivämäärä**-kenttä sisältää päivämäärän, jona suunnitteluriviin liittyvän käytön odotetaan olevan valmis. Se on myös päivämäärä, jona suunnittelurivi voidaan siirtää myyntilaskuun ja kirjata.  

**Huomautus**: Kun täytät **Määrä**-kentän, ohjelma laskee kaikki kokonaishinnan ja -kustannusten tiedot kyseistä suunnitteluriviä varten. Voit muokata niitä milloin tahansa.

**Projektikortti**-ikkunassa on nyt yhteenveto kunkin tehtävän budjetoiduista kokonaiskustannuksista, budjetoidusta hinnasta, laskutettavista kustannuksista ja laskutettavasta hinnasta.

Lisätietoja budjetoitujen ja todellisten projektihintojen ja -kustannusten kirjaamisesta on kohdassa [Toimintaohje: Projektien käytön kirjaaminen](projects-how-record-job-usage.md).

## <a name="see-also"></a>Katso myös
[Projektien hallinta](projects-manage-projects.md)  
[Rahoitus](finance-setup.md)  
[Ostojen hallinta](purchasing-manage-purchasing.md)         
[Myynnin hallinta](sales-manage-sales.md)      
[Dynamics NAV -ohjelman käyttäminen](ui-work-product.md)  

