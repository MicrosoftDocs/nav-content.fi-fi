---
title: Nimikkeiden varaaminen
description: "Voit varata nimikkeitä myyntitilauksiin, ostotilauksiin ja tuotantotilauksiin. Voit varata nimikkeitä varastossa tai avoimien asiakirjarivien saapuvissa kohteissa."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 08/14/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: b9b1f062ee6009f34698ea2cf33bc25bdd5b11e4
ms.openlocfilehash: 5ce50e2e83d1d4f1d0dfee238833c831a32e103e
ms.contentlocale: fi-fi
ms.lasthandoff: 10/23/2017

---
# <a name="how-to-reserve-items"></a>Toimintaohje: Nimikkeiden varaaminen
Voit varata nimikkeitä myyntitilauksiin, ostotilauksiin, huoltotilauksiin, kokoonpanotilauksiin ja tuotantotilauksiin. Voit varata nimikkeitä varastossa tai avoimien asiakirja- tai päiväkirjarivien saapuvissa kohteissa. Käsittely tapahtuu **Varaus**-ikkunassa.

Jokaisella nimikkeiden varaamista varten avatulla **Varaus**-ikkunan rivillä on tietoja yhdestä rivin (myynti, osto, päiväkirja) tai varastotapahtuman tyypistä. Riveillä kuvataan, kuinka monta nimikettä on saatavilla varattavaksi kustakin rivin tai tapahtuman tyypistä.

## <a name="to-reserve-items-for-sales"></a>Nimikkeiden varaaminen myyntiä varten
Seuraavaksi käsitellään, miten nimikkeitä varataan myyntitilauksesta. Samat ohjeet koskevat osto-, huolto- ja kokoonpanotilauksia.  
1.  Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, kirjoita **Myyntitilaukset** ja valitse sitten aiheeseen liittyvä linkki.  
2.  Valitse myyntitilauksen **Rivit**-pikavälilehdessä **Varaa**-toiminto. **Varaustapahtumat**-ikkuna aukeaa.  
3. Napsauta riviä, jolta haluat varata nimikkeet.  
4. Valitse yksi seuraavista toiminnoista.  

    |**Toiminto**|**Kuvaus**|
    |------------------|---------------------|  
    |**Automaattinen varaus**|Nimikkeiden automaattinen varaaminen **Varaus**-ikkunassa.|  
    |**Varaa nykyiseltä riviltä**|Nimikkeiden varaaminen asiakirjasta valitsemaltasi riviltä.|  
    |**Peruuta varaus nykyiseltä riviltä**|Nimikkeiden varauksen peruuttaminen asiakirjasta valitsemaltasi riviltä.|

> [!NOTE]  
>  Jos myyntitilauksella on olemassa nimikkeen seurantarivejä, varausjärjestelmä ohjaa erikoistyövaiheiden läpi. Lisätietoja on kohdassa Tietyn erä- tai sarjanumeron varaaminen.  

## <a name="to-reserve-an-item-for-a-production-order-line"></a>Nimikkeiden varaaminen tuotantotilauksen rivejä varten  
Tuotantotilauksille voi varata nimikkeitä. Tuotantotilauksen rivit eli päänimike ja tuotantotilauksen komponentit on erotettava toisistaan.

Seuraavassa toimenpiteessä käytetään sitovasti suunniteltua tuotantotilausta.   
1. Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, kirjoita **Sitovasti suun. tuotantotil.** ja valitse sitten aiheeseen liittyvä linkki.  
2. Avaa sitovasti suunniteltu tuotantotilaus, jolle haluat varata päänimikkeitä.  
3. Valitse vapautettavan tuotantotilauksen rivi.  
4. Valitse **Rivit**-pikavälilehdessä **Varaa**-toiminto.
5. Valitse **Varaus**-ikkunassa ensin **Myyntirivi, Tilaus** -rivi ja sitten **Varaa nykyiseltä riviltä** -toiminto.  

Ohjelma on nyt varannut määrän, joka oli syötetty sitovasti suunnitellun tuotantotilausriville.

## <a name="to-reserve-items-for-production-order-components"></a>Nimikkeiden varaaminen tuotantotilauksen komponentteja varten  
Tuotantotilauksille voi varata nimikkeitä. Tuotantotilauksen rivit eli päänimike ja tuotantotilauksen komponentit on erotettava toisistaan.

Seuraavassa toimenpiteessä käytetään sitovasti suunniteltua tuotantotilausta.    
1. Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, kirjoita **Sitovasti suun. tuotantotil.** ja valitse sitten aiheeseen liittyvä linkki.  
2. Avaa sitovasti suunniteltu tuotantotilaus, jolle haluat varata komponenttinimikkeitä.  
3. Valitse käsiteltävän tuotantotilauksen rivi.  
4. Valitse **Rivit**-pikavälilehdessä ensin **Rivi** ja sitten **Komponentit**.  
5. Valitse asianmukainen komponenttirivi.  
6. Valitse **Rivit**-pikavälilehdessä **Varaa**-toiminto.  
7. Valitse **Varaus**-ikkunassa ensin rivi ja sitten **Varaa nykyiseltä riviltä** -toiminto.  

Ohjelma on nyt varannut määrän, joka oli syötetty sitovasti suunnitellun tuotantokomponentin riville.

## <a name="to-change-a-reservation"></a>Varausten muuttaminen  
Joskus voit haluta muuttaa nimikevarausta.   
1. Valitse sen asiakirjarivin, jossa olet tehnyt varauksen, **Rivit** -pikavälilehdessä **Varaa**-toiminto.  
2. Valitse **Varaus**-ikkunassa **Varaustapahtumat**-toiminto.
3. Päivitä **Varaustapahtumat**-ikkunassa muutettavan rivin **Määrä**-kenttä.
4. Vahvista avautuva sanoma valitsemalla **OK**.

## <a name="to-cancel-a-reservation"></a>Varausten peruuttaminen  
Joskus voit haluta peruuttaa nimikevarauksen.   
1. Valitse sen asiakirjarivin, jossa tehdyn varauksen haluat peruuttaa, **Rivit** -pikavälilehdessä **Varaa**-toiminto.  
2. Valitse **Varaus**-ikkunassa **Varaustapahtumat**-toiminto.  
3.  Valitse **Varaustapahtumat**-ikkunassa **Peruuta varaus**-toiminto.  
4.  Vahvista avautuva sanoma valitsemalla **OK**.  

## <a name="to-reserve-a-specific-serial-or-lot-number"></a>Varaa tietty sarja- tai eränumero  
Nimikeseurannassa olevien nimikkeiden lähtevien asiakirjojen, kuten myyntitilausten tai tuotannon komponenttiluetteloiden, tiettyjä sarja- tai eränumeroita voi varata. Tämä voi olla tarpeen, jos esimerkiksi tarvitaan tietyn erän tuotanto-osia, jotta varmistetaan yhdenmukaisuus aiempien tuotantoerien kanssa, tai koska asiakas on pyytänyt tiettyä sarjanumeroa. Lisätietoja on kohdassa [Toimintaohje: Sarja- ja eränumeroiden käsitteleminen](inventory-how-work-item-tracking.md).

Tätä kutsutaan määritetyksi varaukseksi, koska varataan erään X kuuluvan nimikkeen X määrästä. Jos varataan vain nimikkeen X määristä, kyseessä on normaali, määrittämätön varaus. Lisätietoja on kohdassa [Rakennetiedot: Nimikkeen seuranta ja varaukset](design-details-item-tracking-and-reservations.md).

Seuraava toimenpide perustuu myyntitilaukseen.    
1. Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, kirjoita **Myyntitilaukset** ja valitse sitten aiheeseen liittyvä linkki.  
2. Luo myyntitilausrivi nimikeseurannassa olevalle nimikkeelle.  
3. Määritä sarja- ja eränumerot myyntitilausriville. Lisätietoja on kohdassa [Toimintaohje: Sarja- ja eränumeroiden käsitteleminen](inventory-how-work-item-tracking.md).
4. Valitse myyntitilausrivillä **Varaa**-toiminto.  
5. Valitse **Kyllä** varataksesi tietyt sarja- tai eränumerot.  
6. Valitse **Nimikeseurantaluettelo**-ikkunassa sarja- ja eränumeron yhdistelmä, jonka olet juuri määrittänyt.  
7. Valitse **OK**, jos haluat avata vain määritettyjen nimikkeen seurantanumeroiden tarjonnan näyttävän **Varaus**-ikkunan. Jos jollakin tälle riville määritetyllä nimikkeen seurantanumerolla on määrittämättömiä varauksia, saat ilmoituksen varatusta määrästä.  
8. Luo tiettyjen nimikkeen seurantanumeroiden varaus valitsemalla joko **Automaattinen varaus**- tai **Varaa nykyiseltä riviltä** -toiminto.

## <a name="see-also"></a>Katso myös
[Vaihto-omaisuus](inventory-manage-inventory.md)  
[Rakennetiedot: varaus, tilauksen seuranta ja toimenpiteiden viestitys](design-details-reservation-order-tracking-and-action-messaging.md)  
[Rakennetiedot – nimikkeen seuranta ja varaukset](design-details-item-tracking-and-reservations.md)  
[Toimintaohje: Sarja- ja eränumeroiden käsitteleminen](inventory-how-work-item-tracking.md)  
[[!INCLUDE[d365fin](includes/d365fin_md.md)] -ohjelman käyttäminen](ui-work-product.md)

