---
title: Myyntitilauksen luominen ja tuotteiden myyminen
description: "Tässä ohjeaiheessa kerrotaan, miten luodaan myyntitilaus kirjaamaan asiakkaan kanssa tehty sopimus tuotteiden myynnistä tai kaupasta tietyin ehdoin."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: trade
ms.date: 03/29/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 1371f7a1d1e5b5c9bd0add845d37e194db86218d
ms.contentlocale: fi-fi
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-sell-products"></a>Toimintaohje: Tuotteiden myyminen
Luo myyntitilaus tai -lasku tallentaaksesi sopimuksesi asiakkaan kanssa ja myydäksesi määrätyt tuotteet määrätyillä toimitus- ja maksuehdoilla.

> [!NOTE]  
>   Myyntitilauksia käytetään, jos myyntiprosessi vaatii tilausmäärän osittaisen toimittamisen esimerkiksi silloin, kun koko määrä ei ole kerralla käytettävissä. Jos myyt nimikkeitä toimittamalla ne suoraan toimittajalta asiakkaalle (suoratoimituksena), myyntitilauksia on käytettävä. Lisätietoja on kohdassa [Toimintaohje: Suoratoimitusten tekeminen](sales-how-drop-shipment.md). Kaikilta muilta osin myyntitilaukset toimivat samalla tavalla kuin myyntilaskut. Lisätietoja on kohdassa [Toimintaohje: Myynnin laskuttaminen](sales-how-invoice-sales.md).

Voit neuvotella asiakkaan kanssa luomalla ensin myyntitarjoukseen, jonka voit muuntaa myyntitilaukseksi, kun hyväksyt myynnin. Lisätietoja on kohdassa [Toimintaohje: Tarjousten tekeminen](sales-how-make-offers.md).

Sen jälkeen, kun asiakas on vahvistanut sopimuksen, esimerkiksi tarjousprosessin jälkeen, voit lähettää tilausvahvistuksen ja tallentaa velvollisuutesi toimittaa tuotteet sovitun mukaisesti.

Kun toimitat tuotteita kokonaan tai osittain, kirjaa myyntitilaus toimitetuksi tai toimitetuksi ja laskutetuksi. Näin järjestelmään luodaan liittyvä nimike ja asiakastapahtumat. Kun kirjaat myyntitilauksen, voit myös lähettää asiakirjan PDF-liitteenä sähköpostitse. Sähköpostin perusteksti voidaan esitäyttää tilauksen ja maksun tietojen yhteenvedolla. Tietoihin voi kuulua esimerkiksi PayPal-linkki. Lisätietoja on kohdassa [Toimintaohje: Asiakirjojen lähettäminen sähköpostitse](ui-how-send-documents-email.md).

Liiketoimintaympäristöissä, joissa asiakkaan on maksettava ennen kuin tuotteet toimitetaan, kuten vähittäismyynti, sinun on odotettava maksukuittia ennen kuin toimitat tuotteet. Useimmissa tapauksissa saapuvia maksuja käsitellään joitakin viikkoja toimituksen jälkeen kohdistamalla maksut niihin liittyviin kirjattuihin ja maksamattomiin myyntilaskuihin. Lisätietoja on kohdassa [Toimintaohje: Maksujen täsmäyttäminen käyttämällä automaattista kohdistusta](receivables-how-reconcile-payments-auto-application.md).

Voit korjata tai peruuttaa myyntitilauksen muodostaman kirjatun myyntilaskun helposti ennen sen maksamista. Tästä on hyötyä, jos haluat korjata kirjoitusvirheen tai jos asiakas pyytää muutosta prosessin alkuvaiheessa. Lisätietoja on kohdassa [Toimintaohje: Maksamattomien myyntilaskujen korjaaminen tai peruuttaminen](sales-how-correct-cancel-sales-invoice.md). Jos kirjattu myyntilasku maksetaan, sinun on luotava myyntihyvityslasku kaupan peruuttamiseksi. Lisätietoja on kohdassa [Toimintaohje: Myyntipalautusten tai -peruutusten käsitteleminen](sales-how-process-sales-returns-cancellations.md).

Voit täyttää myyntitilauksen asiakkaan kentät kahdella tavalla sen mukaan, onko asiakas jo rekisteröity. Katso vaiheet 2 ja 3 seuraavassa menettelyssä.

## <a name="to-create-a-sales-order"></a>Myyntitilauksen luominen
1. Valitse aloitussivulla **Myyntitilaus**-toiminto.  
2. Syötä **Asiakas**-kenttään nykyisen asiakkaan nimi.

    Muut **Myyntitilaus**-ikkunan kentät täytetään nyt valitun asiakkaan vakiotiedoilla. Jos asiakasta ei ole rekisteröity, toimi seuraavasti:
3. Syötä **Asiakas**-kenttään uuden asiakkaan nimi.
4. Valitse uuden asiakkaan rekisteröimisen valintaikkunassa **Kyllä**-painike.
5. Valitse **Valitse uuden asiakkaan malli** -ikkunassa malli uuden asiakkaan kortin perusteella ja valitse sitten **OK**-painike.

    Uuden asiakkaan kortti avautuu esitäytettynä valitun asiakasmallin tiedoilla. **Nimi**-kenttään esitäytetään myyntitilaukseen syöttämäsi uuden asiakkaan nimi.
6. Jatka täyttämällä asiakkaan kortin jäljellä olevat kentät. Lisätietoja on kohdassa [Toimintaohje: Uusien asiakkaiden rekisteröiminen](sales-how-register-new-customers.md).  
7. Kun olet määrittänyt asiakaskortin, valitse **OK**-painike palataksesi **Myyntitilaus**-ikkunaan.

    Myyntitilauksen useat kentät täytetään nyt tiedoilla, jotka olet määrittänyt uuden asiakkaan kortissa.
8. Täytä tarvittaessa jäljellä olevat kentät **Myyntitilaus**-ikkunassa. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]

    Voit nyt täyttää myyntitilausrivit varastonimikkeillä tai palveluilla, joita haluat myydä asiakkaalle.

    Jos olet määrittänyt toistuvien myyntien rivin asiakkaalle, kuten kuukausittainen täydennystilaus, voit lisätä nämä rivit tilaukseen valitsemalla **Nouda toistuvat myyntirivit** -toiminto.
9. Syötä **Rivit**-pikavälilehden **Nimike**-kenttään varastonimikkeen tai palvelun numero.  
10. Syötä myytävien nimikkeiden lukumäärä **Määrä**-kenttään.

    **Rivisumma**-kenttä päivitetään näyttämään arvoa, joka saadaan kertomalla **Yksikköhinta**-kentän arvo **Määrä**-kentän arvolla.

    Hinta ja rivin summat näytetään ALV:n kanssa tai ilman riippuen siitä, mitä valitsit **Hinnat verojen kanssa** -kenttään asiakkaan kortissa.
11. Syötä **Rivialennus-%**-kenttään prosentti, jos haluat myöntää asiakkaalle alennuksen tuotteesta. Sama arvo päivitetään **Rivisumma**-kenttään.

    Jos olet määrittänyt asiakkaan tai nimikkeen kortin **Myyntihinnat ja myyntirivien alennukset**-pikavälilehdellä erityisiä nimikehintoja, rivialennusprosentti, hinta ja summa päivitetään automaattisesti tarjousrivillä, jos sovitut hinnan ehdot täyttyvät. Lisätietoja on kohdassa [Myyntihinnan, alennuksen ja maksusopimusten tallentaminen](sales-how-record-sales-price-discount-payment-agreements.md).
12. Voit lisätä tarjousriviä koskevan huomautuksen, jonka asiakas näkee tulostetussa myyntitarjouksessa, kirjoittamalla tekstin **Kuvaus**-kentän tyhjälle riville.  
13. Toista vaiheet 10–13 jokaiselle nimikkeelle, jonka haluat tarjota asiakkaalle.

    Rivien kokonaissummat lasketaan automaattisesti samalla, kun rivejä luodaan ja muokataan.
6. Uuden asiakkaan kortissa näkyy valitun asiakasmallin tiedot. Täytä jäljellä olevat kentät. Lisätietoja on kohdassa [Toimintaohje: Uusien asiakkaiden rekisteröiminen](sales-how-register-new-customers.md).  
7. Kun olet määrittänyt asiakaskortin, valitse **OK**-painike palataksesi **Myyntitilaus**-ikkunaan.

   Monet myyntitilauksen kentistä täytetään nyt tiedoilla, jotka olet määrittänyt uuden asiakkaan kortissa.  
8. Täytä tarvittaessa jäljellä olevat kentät **Myyntitilaus**-ikkunassa. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]  

   Voit nyt täyttää asiakkaille myytävien tuotteiden tai KP-tilille kirjattavan asiakastapahtuman myyntitilauksen rivit.   

   Jos olet määrittänyt toistuvien myyntien rivin asiakkaalle, kuten kuukausittainen täydennystilaus, voit lisätä nämä rivit tilaukseen valitsemalla **Nouda toistuvat myyntirivit** -toiminto.  
9. Valitse **Rivit**-pikavälilehden **Tyyppi**-kentässä sen tuotteen, kulun tai tapahtuman tyyppi, jonka kirjaat myyntirivin asiakkaalle.
10. Valitse **Nro**-kenttään kirjattava tietue **Tyyppi**-kentän arvon mukaan.

    Jätä **Nro**-kenttä tyhjäksi seuraavissa tapauksissa: -Jos rivi on tarkoitettu kommentille. Kirjoita kommentti **Kuvaus**-kenttään.
    -Jos rivi on tarkoitettu ei-varastoitavalle nimikkeelle. Valitse **Valitse ei-varastoitavat nimikkeet** -toiminto. Lisätietoja on kohdassa [Toimintaohje: Ei-varastoitavien nimikkeiden käsitteleminen](inventory-how-work-nonstock-items.md).

11. Ilmoita **Määrä**-kentässä, kuinka monta tuote-, kulu- tai tapahtumayksikköä rivi kirjaa asiakkaalle.  

    > [!NOTE]  
>   Jos nimikkeen tyyppi on **Nimike - Palvelu** tai **Resurssi**, määrä on aikayksikkö, esimerkiksi tunnit, kuten rivin **Mittayksikkökoodi**-kenttä osoittaa.  

    **Rivisumma**-kentän arvo lasketaan *Yksikköhinta* x *Määrä*.  

    Hinta ja rivin summat ilmaistaan ALV:n kanssa tai ilman sitä sen mukaan, mitä valitsit **Hinnat sisältävät verot** -kenttään asiakkaan kortissa.  
12. Jos haluat antaa alennuksen, anna prosentti **Rivialennus-%**-kentässä. **Rivisumma**-kentän arvo päivittyy vastaavasti.  

    Jos nimikkeiden erikoishinnat on määritetty asiakkaan tai nimikkeen kortin **Myyntihinnat ja myyntirivien alennukset**-pikavälilehdellä, myyntiriviin hinta ja summa päivittyvät automaattisesti, jos sovitut hinnan ehdot täyttyvät. Lisätietoja on kohdassa [Myyntihinnan, alennuksen ja maksusopimusten tallentaminen](sales-how-record-sales-price-discount-payment-agreements.md).  
13. Toista vaiheet 9–12 jokaiselle tuotteelle tai kululle, jonka haluat myydä asiakkaalle.  

    Rivien kokonaissummat lasketaan automaattisesti samalla, kun rivejä luodaan ja muokataan.  
14. Syötä **Laskun alennussumma** -kenttään summa, joka vähennetään **Yhteensä sis. ALV:n** -kentässä olevasta arvosta.

    Jos asiakkaalle on määritetty laskualennukset, määritetty prosenttiluvun arvo lisätään automaattisesti **Asiakkaan laskun alennus-%** -kenttään, jos ehdot täyttyvät. Liittyvä summa lisätään **Laskun alennussumma ilman ALV:a** -kenttään. Lisätietoja on kohdassa [Myyntihinnan, alennuksen ja maksusopimusten tallentaminen](sales-how-record-sales-price-discount-payment-agreements.md).
15. Jos haluat toimittaa osan tilausmäärästä, syötä määrä **Toimitettava määrä** -kenttään. Arvo kopioidaan **Laskutettava määrä** -kenttään.
16. Jos haluat laskuttaa osan toimitettavasta määrästä, syötä kyseinen määrä **Laskutettava määrä** -kenttään. Määrän on oltava pienempi kuin **Toimitettava määrä** -kentän arvo.   
17. Kun myyntitilausrivit ovat valmiit, valitse **Kirjaa ja lähetä** -toiminto.

Asiakkaan ensisijainen asiakirjojen vastaanottomenetelmä näkyy **Kirjaa ja lähetä vahvistus** -valintaikkunassa. Voit muuttaa lähetysmenetelmän valitsemalla **Lähetä asiakirja kohteeseen** -kentän valintapainikkeen. Lisätietoja on kohdassa [Toimintaohje: Asiakirjan lähetysprofiilien määrittäminen](sales-how-setup-document-send-profiles.md).

Nyt järjestelmässä luodaan liittyvä nimike ja asiakastapahtumat. Myyntitilaus tulostetaan PDF-asiakirjana. Kun myyntitilaus on kirjattu kokonaan, se poistetaan myyntitilausluettelosta ja korvataan uusilla kirjattujen myyntilaskujen luettelon ja kirjattujen myyntitoimitusten luettelon asiakirjoilla.

## <a name="see-also"></a>Katso myös
[Myynti](sales-manage-sales.md)  
[Myynnin määrittäminen](sales-setup-sales.md)  
[Varasto](inventory-manage-inventory.md)  
[Toimintaohje: Asiakirjojen lähettäminen sähköpostitse](ui-how-send-documents-email.md)  
[[!INCLUDE[d365fin](includes/d365fin_md.md)] -ohjelman käyttäminen](ui-work-product.md)

