---
title: "Maksujen kohdistaminen automaattisesti ja pankkitilien täsmäyttäminen"
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
ms.openlocfilehash: 11df387c16e19421090531fd03c209103b9989d9
ms.contentlocale: fi-fi
ms.lasthandoff: 06/26/2017

---

# <a name="apply-payments-automatically-and-reconcile-bank-accounts"></a>Maksujen kohdistaminen automaattisesti ja pankkitilien täsmäyttäminen
Sinun on täsmäytettävä säännöllisesti pankin, myyntisaamisten ja ostovelkojen tilit Dynamics NAV -ohjelmassa kohdistamalla pankkiin tallennetut maksut niiden vastaaviin maksamattomiin laskuihin ja hyvityslaskuihin tai muihin avoimiin tapahtumiin Dynamics NAV -ohjelmassa.

Voit suorittaa tämän tehtävän **Maksujen täsmäytyskirjauskansio** -ikkunassa tuomalla pankin tiliotteen tai syötteen ja rekisteröimällä maksut nopeasti Dynamics NAV -ohjelmaan. Automaattinen kohdistustoiminto kohdistaa maksut niihin liittyviin avoimiin asiakas- tai toimittajatapahtumiin maksun tekstin ja tapahtuman tietojen välisten tietojen vastaavuuksien perusteella. Voit tarkastella ja muuttaa automaattisia kohdistuksia, ennen kuin kirjaat päiväkirjan. Voit sulkea minkä tahansa kohdistettuun tapahtumakirjaukseen liittyvän avoimen pankkitapahtuman päiväkirjan kirjaamisen yhteydessä. Tämä tarkoittaa sitä, että pankkitili täsmäytetään automaattisesti, kun kaikki maksut on kohdistettu.

Jos haluat ottaa pankin tiliotteet käyttöön pankkisyötteenä, määritä ensin Envestnet Yodlee -pankkisyötepalvelu ja linkitä sitten pankkitilit liittyviin verkkopankkitileihin. Lisätietoja on kohdassa [Toimintaohje: Envestnet Yodlee -pankkisyötepalvelun määrittäminen](bank-how-setup-bank-statement-service.md).

**Huomautus**: Envestnet Yodlee -pankkisyötepalvelu tai toisen palveluntarjoajan pankkisyötepalvelu ei ehkä ole käytettävissä järjestelmässäsi. Jos haluat käyttää pankkisyötepalvelua tiliotteiden tuomiseen, ota yhteys Microsoft-yhteistyökumppaniisi.

Vaihtoehtoisesti voit käyttää pankkitietojen muuntopalvelua muuntaessasi minkä tahansa muotoisen pankin tiliotteen tietovirraksi, jonka voit tämän jälkeen tuoda Dynamics NAV -ohjelmaan. Lisätietoja on kohdassa [Toimintaohje: Pankkitietojen muuntopalvelun määrittäminen](bank-how-setup-bank-data-conversion-service.md).

Seuraavassa taulukossa on tehtäväsarja ja linkit tehtäviä kuvaaviin aiheisiin.

|Toiminta |Katso |
|---|----|
|Kohdista maksut avoimiin asiakas- tai toimittajatapahtumiin tuomalla tiliote. Täsmäytä pankkitili sitten, kun kaikki maksut on kohdistettu. | [Toimintaohjeet: Maksujen täsmäyttäminen käyttämällä automaattista kohdistusta](receivables-how-reconcile-payments-auto-application.md) |
|Voit kohdistaa maksut manuaalisesti tarkastelemalla jokaisen kohdistetun tiedon tietoja ja ehdotuksia avoimista tapahtumista joihin maksut kohdistetaan. | [Toimintaohjeet: Maksujen tarkastelu tai käyttäminen automaattisen kohdistuksen jälkeen](receivables-how-review-apply-payments-auto-application.md)
|Ratkaise maksut, joita ei voi kohdistaa automaattisesti niiden liittyviin avoimiin tapahtumakirjauksiin. Näin voi käydä esimerkiksi silloin, kun summat ovat erilaiset tai kun liittyvää tapahtumakirjausta ei ole. | [Toimintaohje: Niiden maksujen täsmäyttäminen, joita ei voi kohdistaa automaattisesti](receivables-how-reconcile-payments-cannot-apply-auto.md)
|Linkitä maksujen teksti tiettyyn asiakkaaseen, toimittajaan tai kirjanpitotileihin, jotta toistuvat käteiskuitit tai kulut kirjataan aina näille tileille, kun kohdistettavia asiakirjoja ei ole.| [Toimintaohje: toistuvien maksujen tekstin yhdistäminen tileihin automaattisen täsmäytyksen suorittamiseksi](receivables-how-map-text-recurring-payments-accounts-auto-reconcilliation.md)|

## <a name="see-also"></a>Katso myös
[Myyntisaamisten hallinta](receivables-manage-receivables.md)  
[Myynnin hallinta](sales-manage-sales.md)

