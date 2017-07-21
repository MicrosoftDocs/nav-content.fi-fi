---
title: Myyntisaamisten hallinta
author: SorenGP
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 3f2be627dfda9720e9f31fd227164d1c27116d2c
ms.contentlocale: fi-fi
ms.lasthandoff: 06/26/2017

---

# <a name="manage-receivables"></a>Myyntisaamisten hallinta#
Myyntisaamisten hallinnan keskeinen tehtävä on kohdistaa saapuvat maksut niihin liittyviin asiakas- tai toimittajatapahtumiin. Tällöin liittyvät myyntilaskut tai ostohyvityslaskut suljetaan maksettuina. Kun kaikki maksut on kohdistettu, pankkitili voidaan täsmäyttää.  

Voit suorittaa tämän tehtävän **Maksujen täsmäytyskirjauskansio** -ikkunassa tuomalla pankin tiliotteen tai syötteen ja rekisteröimällä maksut nopeasti Dynamics NAV -ohjelmaan. Automaattinen kohdistustoiminto kohdistaa maksut niihin liittyviin avoimiin asiakas- tai toimittajatapahtumiin maksun tekstin ja tapahtuman tietojen välisten tietojen vastaavuuksien perusteella. Voit tarkastella ja muuttaa automaattisia kohdistuksia, ennen kuin kirjaat päiväkirjan. Voit sulkea minkä tahansa kohdistettuun tapahtumakirjaukseen liittyvän avoimen pankkitapahtuman päiväkirjan kirjaamisen yhteydessä. Tämä tarkoittaa sitä, että pankkitili täsmäytetään automaattisesti, kun kaikki maksut on kohdistettu.

**Huomautus**: Voit täsmäyttää pankkitilit erillisinä tehtävinä **Pankkitilin täsmäytys** -ikkunassa. Tämä toiminto tukee myös sekkitapahtumia. Lisätietoja on kohdassa [Toimintaohje: Pankkitilien täsmäyttäminen erikseen](bank-how-reconcile-bank-accounts-separately.md).

Vaihtoehtoisesti voit kohdistaa maksut **Maksurekisteröinti**-ikkunassa tarkistamalla käteisenä, sekkinä tai pankkitapahtumana vastaanotetut maksut manuaalisesti maksamattomia myyntiasiakirjoja vastaan. Huomaa, että tämä toiminto on käytettävissä vain myyntiasiakirjoja varten.

Toinen maksujen manuaalinen täsmäytystapa on kirjata jokainen vastaanotto asianmukaiseen pääkirjaan tai asianmukaiselle asiakkaalle tai toiselle tilille syöttämällä maksurivi **Kassapäiväkirja**-ikkunaan. Tällöin voit kohdistaa vastaanoton tai hyvityksen yhteen avoimeen tapahtumaan tai useisiin avoimiin tapahtumiin, ennen kuin kirjaat kassapäiväkirjan. Voit myös tehdä kohdistuksen luoduista asiakastapahtumista.

Toinen myyntisaamisten hallinnan tehtävä on kerätä avoimet saldot. Siihen kuuluu esimerkiksi rahoituksen käyttöönottokulujen hallinta ja muistutusten lähettäminen.

Seuraavassa taulukossa on tehtäväsarja ja linkit tehtäviä kuvaaviin aiheisiin.

|Toiminta |Katso |
|---|----|
|Kohdista maksut avoimiin asiakas- tai toimittajatapahtumiin tuodun pankin tiliotetiedoston tai syötteen perusteella. Täsmäytä pankkitili sitten, kun kaikki maksut on kohdistettu.|[Maksujen kohdistaminen automaattisesti ja pankkitilien täsmäyttäminen](receivables-apply-payments-auto-reconcile-bank-accounts.md)|
|Kohdista maksut avoimiin asiakasmaksuihin maksamattomien myyntiasiakirjojen luettelon manuaalisen tapahtuman perusteella. | [Toimintaohje: Asiakkaan maksujen täsmäyttäminen manuaalisesti maksamattomien myyntiasiakirjojen luettelosta](receivables-how-reconcile-customer-payments-list-unpaid-sales-documents.md)|
|Kirjaa asiakkaiden kassaanmaksut tai hyvitykset kassapäiväkirjaan ja kohdista asiakastapahtumat päiväkirjasta tai kirjatuista tapahtumakirjauksista. | [Toimintaohje: Asiakkaan maksujen täsmäyttäminen manuaalisesti](receivables-how-apply-sales-transactions-manually.md) |
|Asiakkaiden muistuttaminen erääntyneistä summista, koron laskeminen ja rahoituksen käyttöönottokulut sekä myyntireskontran hallinta. | [Toimintaohje: Avointen saldojen perintä](receivables-collect-outstanding-balances.md) |

## <a name="see-also"></a>Katso myös
[Myynnin hallinta](sales-manage-sales.md)  
[Ostovelkojen hallinta](payables-manage-payables.md)  
[Dynamics NAV -ohjelman käyttäminen](ui-work-product.md)  
[Liiketoiminta-alueiden välillä](ui-across-business-areas.md)

