---
title: Pankkitilien hallinta
description: "Pankkitapahtumat on täsmäytettävä säännöllisesti niihin liittyviin pankkitilitapahtumiin Dynamics NAV -ohjelmassa."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: reconcile
ms.date: 06/02/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: b9b1f062ee6009f34698ea2cf33bc25bdd5b11e4
ms.openlocfilehash: cd33af7062b5a8e75937f8750e09414f734d8c04
ms.contentlocale: fi-fi
ms.lasthandoff: 10/23/2017

---
# <a name="managing-bank-accounts"></a>Pankkitilien hallinta
Täsmäytä [!INCLUDE[d365fin](includes/d365fin_md.md)]in pankkitilitapahtumat säännöllisin väliajoin pankin pankkitilin liittyvien pankkitapahtumien kanssa. Kirjaa sitten saldo pankkitilille. Voit suorittaa tämän tehtävän **Maksujen täsmäytyskirjauskansio** -kohdassa pankin tiliotteessa olevien maksujen käsittelyn osana. Vaihtoehtoisesti voit suorittaa tehtävän maksujen käsittelyn ulkopuolella **Pankkitilin täsmäytys** -ikkunassa. Tämä tukee sekkitapahtumia. Molemmissa tapauksissa ikkunat täytetään tuomalla tiliote [!INCLUDE[d365fin](includes/d365fin_md.md)]iin.

[!INCLUDE[d365fin](includes/d365fin_md.md)]issa on joskus siirrettävä summia pankkitilien välillä pankin siirtojen mukaisesti. Tämä tehtävä suoritetaan **Yleinen päiväkirja** -ikkunassa varojen valuutan osoittamalla tavalla.

Jokainen pankkitili on määritettävä pankkitilin kortiksi, ennen kuin pankkitilejä voidaan hallita. Lisäksi on määritettävä sähköiset palvelut, joita käytetään pankin tiliotteen tuonnissa ja maksutiedoston viennissä. Lisätietoja on kohdassa [Pankkitilien määrittäminen](bank-setup-banking.md).

Seuraavassa taulukossa on tehtäväsarja ja linkit tehtäviä kuvaaviin aiheisiin.

| Toiminta | Katso |
| --- | --- |
| Täsmäytä maksukäsittelyyn liittyvät pankkitilit **Maksujen täsmäytyskirjauskansio** -ikkunassa. |[Maksujen kohdistaminen automaattisesti ja pankkitilien täsmäyttäminen](receivables-apply-payments-auto-reconcile-bank-accounts.md) |
| Täsmäytä pankkitilit, kuten sekkitapahtumat, erillisinä tehtävinä **Pankkitilin täsmäytys** -ikkunassa. |[Toimintaohje: Pankkitilien täsmäyttäminen erikseen](bank-how-reconcile-bank-accounts-separately.md) |
| Kirjaa pankkitilien väliset siirrot samassa valuutassa tai eri valuutoissa. |[Toimintaohje: Pankkivarojen siirtäminen](bank-how-transfer-bank-funds.md) |

## <a name="see-also"></a>Katso myös
[Pankkitoiminnan määrittäminen](bank-setup-banking.md)  
[Myyntisaamisten hallinta](receivables-manage-receivables.md)  
[Ostovelkojen hallinta](payables-manage-payables.md)    
[[!INCLUDE[d365fin](includes/d365fin_md.md)] -ohjelman käyttäminen](ui-work-product.md)  
[Yleiset liiketoimintatoiminnot](ui-across-business-areas.md)  

