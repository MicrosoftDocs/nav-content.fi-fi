---
title: "KO-vakuutuksen määrittäminen"
description: "Voit hallita käyttöomaisuuden vakuutuksen kattavuutta, kun määrität ensin joitakin sopimusta koskevia yleisiä vakuutustietoja sekä vakuutuskortin."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: policy, coverage
ms.date: 06/02/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 0c0b553adee7df5979352999c60549b280501926
ms.contentlocale: fi-fi
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-set-up-fixed-asset-insurance"></a>Toimintaohje: Käyttöomaisuuden vakuutuksen määrittäminen
Voit hallita käyttöomaisuuden vakuutuksen kattavuutta, kun määrität ensin joitakin sopimusta koskevia yleisiä vakuutustietoja sekä vakuutuskortin.

## <a name="to-set-up-general-insurance-information"></a>Yleisten vakuutustietojen määrittäminen
Jotta [!INCLUDE[d365fin](includes/d365fin_md.md)]in vakuutusominaisuuksia voitaisiin käyttää, tietyt yleiset vakuutustiedot on määritettävä.  

1. Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, syötä **KO-asetukset** ja valitse sitten aiheeseen liittyvä linkki.  
2. Täytä tarvittavat kentät. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]  

## <a name="to-set-up-insurance-types"></a>Vakuutustyyppien määrittäminen
Voit ryhmitellä vakuutussopimukset luokkiin, esimerkiksi vakuutukset varkauksia vastaan ja vakuutukset tulipaloa vastaan. Vakuutustyyppejä käytetään vakuutuskortissa.

1. Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, syötä **Vakuutustyypit** ja valitse sitten aiheeseen liittyvä linkki.  
2. Täytä tarvittavat kentät.

## <a name="to-set-up-insurance-cards"></a>Vakuutuskorttien määrittäminen
Vakuutuskorttiin voi kerätä tietoja kustakin vakuutussopimuksesta.  

1. Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, syötä **Vakuutus** ja valitse sitten aiheeseen liittyvä linkki.  
2. Luo uusi vakuutuskortti valitsemalla **Vakuutus**-ikkunassa **Uusi**-toiminto.  
3. Täytä tarvittavat kentät.

## <a name="to-set-up-insurance-journal-templates"></a>Vakuutuspäiväkirjamallien määrittäminen
[!INCLUDE[d365fin](includes/d365fin_md.md)] luo automaattisesti vakuutuspäiväkirjan mallin, kun avaat **Vakuutuspäiväkirja**-ikkunan ensimmäisen kerran, mutta voit määrittää myös lisää päiväkirjamalleja. Lisätietoja on kohdassa [Yleisten päiväkirjojen käyttäminen](ui-work-general-journals.md).  

1. Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, syötä **Vakuutuspäiväkirjan mallit** ja valitse sitten aiheeseen liittyvä linkki.  
2. Täytä tarvittavat kentät.

## <a name="to-set-up-insurance-journal-batches"></a>Vakuutuspäiväkirjaerien määrittäminen
Vakuutuspäiväkirjan mallin alla voidaan määrittää eriä. Päiväkirjaerän arvoja käytetään oletusarvoina, jos päiväkirjarivien kenttiä ei täytetä. Lisätietoja on kohdassa [Yleisten päiväkirjojen käyttäminen](ui-work-general-journals.md)  

1. Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, syötä **Vakuutuspäiväkirjan mallit** ja valitse sitten aiheeseen liittyvä linkki.  
2. Valitse vakuutuspäiväkirjamalli ja valitse sitten **Erät**-toiminto.
3. Täytä **Vakuutuspäiväkirjan erät** -ikkunassa tarvittavat kentät.

> [!NOTE]  
>   Numeroilla on päiväkirjan nimissä erityistehtävä. Jos päiväkirjamallin nimessä tai päiväkirjaerän nimessä on numero, numero suurenee automaattisesti yhdellä joka kerta, kun päiväkirja kirjataan. Esimerkiksi jos **Nimi**-kenttään syötetään HH1, päiväkirjan nimi muuttuu HH2:ksi sen jälkeen, kun päiväkirja, jonka nimi on HH1, on kirjattu.

## <a name="see-also"></a>Katso myös
[Käyttöomaisuuden määrittäminen](fa-setup.md)  
[Käyttöomaisuus](fa-manage.md)  
[Rahoitus](finance.md)  
[Tervetuloa [!INCLUDE[d365fin_long](includes/d365fin_long_md.md)]iin!](index.md)  
[[!INCLUDE[d365fin](includes/d365fin_md.md)] -ohjelman käyttäminen](ui-work-product.md)

