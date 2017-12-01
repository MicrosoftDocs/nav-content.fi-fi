---
title: "Toimittajille suoritettavien maksujen hallintatehtävien yleiskatsaus"
description: "Tässä ohjeaiheessa kerrotaan toimittajille tai luotonantajille suoritettavien maksujen hallintatehtävistä, kuten maksurivien kirjaamisesta ja erääntyvän saldon yleiskatsauksen hakemisesta."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: print check, vendor payment, creditor, debt, balance due, AP
ms.date: 06/28/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: b9b1f062ee6009f34698ea2cf33bc25bdd5b11e4
ms.openlocfilehash: 6ec19f50c70b5355c0d586b03f4d5a41733f8e3e
ms.contentlocale: fi-fi
ms.lasthandoff: 10/23/2017

---
# <a name="making-payments"></a>Maksujen suorittaminen
Kun suoritat maksut toimittajille tai hyvityksiä työntekijöille, kirjaat liittyvät maksurivit **Maksupäiväkirja**-ikkunaan. Voit etsiä toimittajien erääntyvät maksut **Ehdota toimittajamaksuja** -eräajon avulla. Voit hakea myös toimittajien erääntyvien maksujen yhteenvedon käyttämällä **Toimittaja - Eräänt.yht.veto** -raporttia.

Maksupäiväkirjassa voit tulostaa tietokonesekkejä tai kirjata käsin kirjoitettuja sekkejä. Jos valitset **Tietokonesekki**-vaihtoehdon **Pankkimaksun tyyppi** -kenttään, sekkejä edustavat rivit on tulostettava, ennen kuin maksupäiväkirja voidaan kirjata.

Kun maksut kirjataan, voit viedä ne pankkitiedostoon, jolloin ne voidaan ladata verkkopankkiisi käsittelyä varten.

Kun maksut on tehty pankkiin, kohdista ne liittyviin avoimiin toimittaja- tai työntekijätapahtumiin. Voit tehdä sen manuaalisesti tai tuomalla pankin tiliotetiedoston ja kohdistamalla maksut automaattisesti. Lisätietoja on kohdassa [Maksujen kohdistaminen automaattisesti ja pankkitilien täsmäyttäminen](receivables-apply-payments-auto-reconcile-bank-accounts.md).

Seuraavassa taulukossa on tehtäväsarja ja linkit tehtäviä kuvaaviin aiheisiin.

| Vastaanottaja | Katso |
| --- | --- |
|Kirjaa maksut toimittajille tai työntekijöille **Maksupäiväkirja**-ikkunassa, joka perustuu yleiseen päiväkirjaan.|[Yleisten päiväkirjojen käyttäminen](ui-work-general-journals.md)|
| Käytä toimintoa ehdottaaksesi toimittajan maksuja valittujen ehtojen, kuten eräpäivän, alennuskelpoisuuden ja maksuvalmiutesi, mukaan. |[Toimintaohje: Toimittajamaksujen ehdottaminen](payables-how-suggest-vendor-payments.md) |
|Hyvitä työntekijöiden liiketoimintaan liittyvät henkilökohtaiset kulut suorittamalla maksu työntekijän pankkitilille.|[Toimintaohje: Työntekijöiden kulujen kirjaaminen ja hyvittäminen](finance-how-record-reimburse-employee-expenses.md)|
| Myönnä sekkejä toimittajan maksuille joko tulosteina tai tietokonesekkeinä. Mitätöi sekit ennen kirjaamista tai sen jälkeen. |[Toimintaohje: Sekkien käsitteleminen](payables-how-work-checks.md) |
| Maksaa toimittajalle käteisellä tai sekillä ja kirjaa maksu, kun lasku kirjataan. |[Ostolaskujen selvittäminen viipymättä](finance-how-to-settle-purchase-invoices-promptly.md) |
| Varmista lähettämällä toimittaja-, sekki- ja maksutiedot sisältävä tiedosto, että pankki vahvistaa vain tarkistetut sekit ja summat. |[Toimintaohje: Positive Pay -tiedoston vieminen](finance-how-positive-pay.md) |
|Vie maksut **Maksupäiväkirja**-ikkunasta pankkitiedostoon, joka ladataan pankkiin käsiteltäväksi. Tämä tiedosto voi olla Pohjois-Amerikassa myös sähköinen rahansiirtotiedosto (EFT). |[Toimintaohje: Maksujen vieminen pankkitiedostoon](payables-how-export-payments-bank-file.md)|  

## <a name="see-also"></a>Katso myös
[Ostovelkojen hallinta](payables-manage-payables.md)  
[Osto](purchasing-manage-purchasing.md)  
[Myyntisaamisten hallinta](receivables-manage-receivables.md)  
[[!INCLUDE[d365fin](includes/d365fin_md.md)] -ohjelman käyttäminen](ui-work-product.md)  

