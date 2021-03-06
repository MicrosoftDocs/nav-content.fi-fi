---
title: "Sekkien myöntäminen, tulostaminen, peruuttaminen ja mitätöiminen"
description: "Tässä ohjeaiheessa kerrotaan, miten sekit myönnetään maksupäiväkirjan avulla, tulostetaan ja mitätöidään tai miten sekkitapahtumia tarkastellaan Dynamics NAV -ohjelmassa."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: payment journal, print check, vendor payment, creditor, debt, balance due, AP
ms.date: 06/06/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 716cb17bf65b225036576dc73f3fe43b102ccb81
ms.contentlocale: fi-fi
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-work-with-checks"></a>Toimintaohje: Sekkien käsitteleminen
Voit myöntää sähköisiä ja manuaalisia sekkejä [!INCLUDE[d365fin](includes/d365fin_md.md)]issa. Molemmissa menetelmissä sekit myönnetään toimittajille maksupäiväkirjaa käyttäen. Ohjelman avulla voit myös mitätöidä sekkejä ja tarkastella sekkitapahtumia.

Sekkien myöntämiskäsittelyyn kuuluvat maksujen ehdottaminen, tapahtumien luominen ja tietokonesekkien tulostaminen.

> [!NOTE]  
>   Voit varmistaa lähettämällä toimittaja-, sekki- ja maksutiedot sisältävän tiedoston, että pankki vahvistaa vain tarkistetut sekit ja summat. Lisätietoja on kohdassa [Toimintaohje: Positive Pay -tiedostojen vieminen](finance-how-positive-pay.md).

Tulostin on määritettävä oikein sekkimuotoja varten. Myös käytettävä sekkien asettelu on määritettävä. Lisätietoja on kohdassa [Toimintaohje: Sekkien asetteluiden määrittäminen](finance-how-define-check-layouts.md)

## <a name="to-issue-checks"></a>Sekkien myöntäminen
1. Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, kirjoita **Maksupäiväkirjat** ja valitse sitten aiheeseen liittyvä linkki.
2. Täytä asianmukaisten maksujen tiedot päiväkirjaan esimerkiksi Ehdota toimittajamaksuja -toiminnon avulla. Lisätietoja on kohdassa [Toimintaohje: Toimittajamaksujen ehdottaminen](payables-how-suggest-vendor-payments.md).
3. Valitse sekkien avulla tehtävän maksun päiväkirjan rivillä **Pankkimaksun tyyppi** -kentässä jokin seuraavista vaihtoehdoista:

   * **Tietokonesekki**: Valitse tämä vaihtoehto, jos haluat tulostaa sekin maksupäiväkirjan tällä rivillä olevalle summalle. Tulosta sekit, ennen kuin kirjaat päiväkirjan rivit. Voit valita **Tietokonesekki**-kohdan vain, jos **Vastatilin tyyppi** tai **Tilin tyyppi** on **Pankkitili**.
   * **Manuaalinen sekki**: Valitse tämä vaihtoehto, jos olet luonut sekin manuaalisesti ja haluat luoda vastaavan sekkitapahtuman tälle summalle. Tämän vaihtoehdon avulla et voi tulostaa sekkejä [!INCLUDE[d365fin](includes/d365fin_md.md)]ista. Voit valita **Manuaalinen sekki** -kohdan vain, jos **Vastatilin tyyppi** tai **Tilin tyyppi** on **Pankkitili**.

     > [!NOTE]  
>   Tulosta tietokonesekit, ennen kuin kirjaat liittyvät päiväkirjan rivit.
4. Jos kyseessä on tietokonesekki, valitse **Tulosta sekki**.
5. Täytä **Sekki**-ikkunassa tarvittavat kentät. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]
6. Valitse **Tulosta**-painike.

> [!NOTE]  
>   Jos sekkejä täytyy tulostaa monessa valuutassa eri pankkitileiltä, sinun täytyy suorittaa **Tulosta sekki** -eräajo erikseen kullekin valuutalle ja määrittää sopivat pankkitilit.

## <a name="to-cancel-printed-checks-that-are-not-posted"></a>Kirjaamattomien ja tulostettujen sekkien peruuttaminen
Voit peruuttaa kirjaamattomat sekit niiden tulostamisen jälkeen **Maksupäiväkirja**-ikkunan **Mitätöi sekki** -toiminnon avulla.

1. Valitse **Maksupäiväkirja**-ikkunassa **Mitätöi sekki** ja valitse peruutettavat sekit.

## <a name="to-void-checks"></a>Sekkien mitätöiminen
Kun sekkimaksu on kirjattu, voit peruuttaa (mitätöidä) sekit vain tuloksena syntyvistä pankkitapahtumista.

1. Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, syötä **Pankkitilit** ja valitse sitten aiheeseen liittyvä linkki.
2. Valitse oikea pankkitili, valitse **Muokkaa**-toiminto ja valitse sitten **Sekkitapahtumat**-toiminto.
3. Valitse **Sekkitapahtumat**-ikkunassa **Mitätöi sekki** -toiminto.
4. Valitse **Mitätöi vain sekki** -valintaruutu.
5. Valitse **OK**-painike.

## <a name="see-also"></a>Katso myös
[Ostovelkojen hallinta](payables-manage-payables.md)  
[Pankkitoiminnan määrittäminen](bank-setup-banking.md)  
[Toimintaohje: Positive Pay -tiedoston vieminen](finance-how-positive-pay.md)  
[[!INCLUDE[d365fin](includes/d365fin_md.md)] -ohjelman käyttäminen](ui-work-product.md)  

