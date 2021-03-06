---
title: Ostolaskun luominen ja ostojen kirjaaminen
description: "Tässä ohjeaiheessa kerrotaan, miten varasto- tai palvelunimikkeitä ostetaan luomalla ja kirjaamalla ostolaskuja tai -tilauksia."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: procurement
ms.date: 08/08/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: d5583290925252acee6a05be29f589d057794c28
ms.contentlocale: fi-fi
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-record-purchases"></a>Toimintaohje: Ostojen kirjaus
Voit luoda ostolaskun tai -tilauksen ostojen kustannusten tallentamiseksi ja ostoreskontran seuraamiseksi. Jos haluat hallita varastoa, myös ostolaskuja ja -tilauksia käytetään varastotasojen dynaamiseen päivittämiseen, jotta voit minimoida varaston kustannukset ja tarjota parempaa asiakaspalvelua. Ostokustannukset, kuten palvelukulut ja varastoarvot, jotka aiheutuvat tiliöinnin ostolaskuista tai -tilauksista, vaikuttavat kotisivullasi oleviin voittolukuihin ja muihin talouden avaintunnuslukuihin.

> [!NOTE]  
>   Ostotilauksia on käytettävä, jos ostoprosessi vaatii tilausmäärän osittaisten vastaanottojen tallentamisen esimerkiksi silloin, kun koko määrä ei ole kerralla toimittajan käytettävissä. Jos myyt nimikkeitä toimittamalla ne suoraan toimittajalta asiakkaalle (suoratoimituksena), ostotilauksia on käytettävä. Lisätietoja on kohdassa [Toimintaohje: Suoratoimitusten tekeminen](sales-how-drop-shipment.md). Kaikilta muilta osin ostotilaukset toimivat samalla tavalla kuin ostolaskut. Seuraava toimenpide perustuu ostolaskuun. Vaiheet ovat samankaltaisia ostotilaukselle.

Kun varastonimikkeitä vastaanotetaan tai ostettu palvelu on valmis, ostolasku tai -tilaus kirjataan varasto- ja taloustietueiden päivittämiseksi ja laskun aktivoimiseksi toimittajalle maksuehtojen mukaan. Lisätietoja on kohdassa [Maksujen suorittaminen](payables-make-payments.md).

> [!CAUTION]  
>   Älä kirjaa ostolaskua, ennen kuin vastaanotat nimikkeet ja tiedät oston lopullisen kustannuksen, mahdolliset lisäkustannukset mukaan lukien. Muussa tapauksessa varaston arvo ja voittoluvut voivat olla virheelliset.

Voit helposti korjata tai peruuttaa kirjatun ostolaskun ennen kuin maksua toimittajalle. Tästä on hyötyä, jos haluat korjata kirjoitusvirheen tai muuttaa ostoa tilausprosessin alkuvaiheessa. Lisätietoja on kohdassa [Toimintaohje: Maksamattomien ostolaskujen korjaaminen tai peruuttaminen](purchasing-how-correct-cancel-unpaid-purchase-invoices.md). Jos olet jo maksanut kirjatun ostolaskun nimikkeet, sinun on luotava ostohyvityslasku oston peruuttamiseksi. Lisätietoja on kohdassa [Toimintaohje: Ostopalautusten tai -peruutusten käsitteleminen](purchasing-how-process-purchase-returns-cancellations.md).

Nimikkeiden tyyppi voi olla **Varasto** tai **Palvelu**. Lisätietoja on kohdassa [Toimintaohje: Uusien nimikkeiden rekisteröiminen](inventory-how-register-new-items.md). Ostolaskuprosessi on sama molemmille nimiketyypeille.

Voit täyttää ostolaskun toimittajan kentät kahdella tavalla sen mukaan, onko toimittaja jo rekisteröity.

## <a name="to-create-a-purchase-invoice"></a>Ostolaskun kirjaamiseksi
1. Valitse kotisivulla **Ostolasku**-toiminto.  
2. Syötä **Toimittaja**-kenttään nykyisen toimittajan nimi.

    Muut **Ostolasku**-ikkunan kentät täytetään nyt valitun toimittajan vakiotiedoilla. Jos toimittajaa ei ole rekisteröity, toimi seuraavasti:
3. Syötä **Toimittaja**-kenttään uuden toimittajan nimi.
4. Valitse uuden toimittajan rekisteröimisen valintaikkunassa **Kyllä**-painike.
5. Valitse **Valitse uuden toimittajan malli** -ikkunassa malli uuden toimittajakortin perusteella ja valitse sitten **OK**-painike.
6. Uuden toimittajan kortti avautuu esitäytettynä valitun toimittajamallin tiedoilla. **Nimi**-kenttään esitäytetään uuden toimittajan nimi, jonka syötit ostolaskulle.
7. Jatka täyttämällä toimittajan kortin jäljellä olevat kentät. Lisätietoja on kohdassa [Toimintaohje: Uusien toimittajien rekisteröiminen](purchasing-how-register-new-vendors.md).  
8. Kun olet määrittänyt toimittajakortin, valitse **OK**-painike palataksesi **Ostolasku**-ikkunaan.

    Useat kentät **Ostolasku** -ikkunassa täytetään tiedoilla, jotka olet määrittänyt uuden toimittajan kortissa.
9. Täytä tarvittaessa jäljellä olevat kentät **Ostolasku**-ikkunassa. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]

    Voit nyt täyttää ostolaskurivit varastonimikkeillä tai palveluilla, joita olet ostanut toimittajalta.

    > [!NOTE]  
>   Jos olet määrittänyt toimittajalle toistuvien ostojen rivin, kuten kuukausittaisen täydennystilauksen, voit lisätä nämä rivit laskuun valitsemalla **Hae toistuvat ostorivit** -toiminnon.
10. Syötä **Rivit**-pikavälilehden **Nimikenro**-kenttään varastonimikkeen tai palvelun numero.
11. Syötä **Määrä**-kenttään ostettavien nimikkeiden lukumäärä.

    > [!NOTE]  
>   Kun nimikkeen tyyppi on **Huolto**, sen määrä on aikayksikkö, kuten tunnit, rivin **Mittayksikkökoodi**-kentän mukaan.

    **Rivisumma**-kenttä päivitetään näyttämään arvoa, joka saadaan kertomalla **Välitön yksikkökustannus** -kentän arvo **Määrä**-kentän arvolla.

    Hinta ja rivin summa näytetään ALV:n kanssa tai ilman riippuen siitä, mitä valitsit **Hinnat verojen kanssa** -kenttään toimittajan kortissa.
12. Syötä **Laskun alennussumma** -kenttään summa, joka vähennetään laskun alaosan **Yhteensä sis. ALV:n** -kentässä olevasta arvosta.

    > [!NOTE]  
>   Jos toimittajalle on määritetty laskualennukset, määritetty prosenttiluvun arvo lisätään automaattisesti **Toimittajan laskun alennus-%** -kenttään, jos ehdot täyttyvät. Liittyvä summa lisätään **Laskun alennussumma** -kenttään.
13. Kun vastaanotat ostettuja nimikkeitä tai palveluita, valitse **Kirjaa**.

Osto vaikuttaa nyt varastoon ja taloustietueisiin, ja myyjän maksu on aktivoitu. Ostolasku poistetaan ostolaskujen luettelosta ja korvataan uudella asiakirjalla kirjattujen ostolaskujen luettelosta.

## <a name="see-also"></a>Katso myös
[Osto](purchasing-manage-purchasing.md)  
[Ostojen määrittäminen](purchasing-setup-purchasing.md)  
[Toimintaohje: Tarjousten pyytäminen](purchasing-how-request-quotes.md)  
[Toimintaohje: Nimikkeiden ostaminen myyntiin](purchasing-how-purchase-products-sale.md)  
[Toimintaohje: Uusien toimittajien rekisteröiminen](purchasing-how-register-new-vendors.md)  
[Toimintaohje: Suoratoimitusten valmisteleminen](sales-how-drop-shipment.md)  
[[!INCLUDE[d365fin](includes/d365fin_md.md)] -ohjelman käyttäminen](ui-work-product.md)

