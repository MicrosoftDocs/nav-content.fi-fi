---
title: "Siirrä pankkivarat"
description: "Voit siirtää summia pankkitililtä toisille myös muissa valuutoissa kirjaamalla tapahtuman yleiseen päiväkirjaan."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: bank account transfer, multiple currencies
ms.date: 06/02/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 5cb652df51fc5b24088bb5cc6a41d8d3f067cfd4
ms.contentlocale: fi-fi
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-transfer-bank-funds"></a>Toimintaohje: Pankkivarojen siirtäminen
Joskus on siirrettävä varoja yhdeltä pankkitililtä toiselle. Se tehdään kirjaamalla tapahtuma yleiseen päiväkirjaan. Tehtävä vaihtelee sen mukaan, käytetäänkö pankkitileillä samaa vai eri valuuttaa.

## <a name="to-post-a-transfer-between-bank-accounts-with-the-same-currency-code"></a>Siirtojen kirjaaminen pankkitileillä, jotka käyttävät samaa valuuttakoodia
1. Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, syötä **Yleinen päiväkirja** ja valitse sitten aiheeseen liittyvä linkki.
2. Täytä päiväkirjan rivillä **Kirjauspvm**- ja **Asiakirjan nro** -kentät.
3. Valitse **Tilityyppi**-kentässä **Pankkitili**.
4. Valitse **Tilinro**-kentässä pankkitili, josta haluat siirtää varat.
5. Syötä siirrettävä summa **Summa**-kenttään.
6. Valitse **Vastatilin tyyppi** -kentässä **Pankkitili**.
7. Valitse **Vastatilin nro**-kentässä pankkitili, johon haluat siirtää varat.
8. Kirjaa päiväkirja.

## <a name="to-post-a-transfer-between-bank-accounts-with-different-currency-codes"></a>Siirtojen kirjaaminen pankkitileillä, joilla on eri valuuttakoodit
Voit siirtää varoja eri valuuttoja käyttävien pankkitilien välillä kirjaamalla kaksi yleisen päiväkirjan riviä.

1. Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, syötä **Yleinen päiväkirja** ja valitse sitten aiheeseen liittyvä linkki.
2. Luo kaksi päiväkirjan riviä ja täytä **Kirjauspvm**- ja **Asiakirjan nro.** -kentät.
3. Valitse **Tyyppi**-kentän ensimmäisellä rivillä **Pankkitili**.
4. Valitse **Tilinro**-kentässä pankkitili, josta haluat siirtää varat.
5. Syötä **Summa**-kenttään summa pankkitilin valuuttana. Anna kredit-summat miinusmerkkisinä. Anna debet-summat ilman miinusmerkkiä.
6. Valitse **Vastatilin tyyppi** -kentässä **Pankkitili**.
7. Valitse **Vastatilin nro**-kentässä pankkitili, johon haluat siirtää varat.
8. Valitse **Tyyppi**-kentän toisella rivillä **Pankkitili**.
9. Valitse **Tilinro**-kentässä pankkitili, johon haluat siirtää varat.
10. Syötä **Summa**-kenttään summa pankkitilin valuuttana. Anna kredit-summat miinusmerkkisinä. Anna debet-summat ilman miinusmerkkiä.
11. Valitse **Vastatilin tyyppi** -kentässä **Pankkitili**.  
12. Valitse **Vastatilin nro**-kentässä pankkitili, josta haluat siirtää varat.

    > [!NOTE]  
>   Jos päiväkirjassa käytetyt vaihtokurssit eroavat **Valuutan vaihtokurssit** -ikkunan kursseista, syötä kolmas rivi vaihtokurssivoittoa tai -tappiota varten. Valitse **KP-tili**-kentässä**Pankkitili**. Syötä **Tilinro**-kenttään valuuttakurssivoittojen ja -tappioiden KP-tilin numero. Syötä valuuttakurssivoitto tai -tappio **Summa**-kenttään. Syötä summa miinusmerkin kanssa, jos kyseessä on kredit, ja ilman miinusmerkkiä, jos kyseessä on debet.
13. Kirjaa päiväkirja.

## <a name="see-also"></a>Katso myös
[Pankkitilien hallinta](bank-manage-bank-accounts.md)  
[Pankkitoiminnan määrittäminen](bank-setup-banking.md)  
[Yleisten päiväkirjojen käyttäminen](ui-work-general-journals.md)  
[[!INCLUDE[d365fin](includes/d365fin_md.md)] -ohjelman käyttäminen](ui-work-product.md)

