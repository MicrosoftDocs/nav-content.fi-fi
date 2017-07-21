---
title: "Tulostimen valinnan määrittäminen raporteille"
author: SusanneWindfeldPedersen
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 55b48aef2bc108ced7f581f0ff6c11263ee467df
ms.contentlocale: fi-fi
ms.lasthandoff: 06/26/2017

---
    
# <a name="specify-printer-selection-for-reports"></a>Tulostimen valinnan määrittäminen raporteille
Voit määrittää raportit niin, että ne täytyy tulostaa tietyssä tulostimessa. Seuraavat ovat joitain tulostimen valinnen käyttötapauksia: 

- Voit tulostaa raportteja erityisissä julkaisuissa.
- Voit tulostaa raportteja eri paperikoissa.
- Voit tulostaa raportteja tietyn työntekijän oletustulostimen.

Määritä **Tulostimen valinnat** -ikkunassa eri arvot eri tulosteiden saamista varten. Jos määrität tulostinvalinnan, valinta ohittaa yleisemmän tulostinvalinnan. Voit esimerkiksi määrittää tulostimen valinnan, jolla on arvot **Käyttäjätunnus**-, **Raportin tunnus**- ja **Tulostimen nimi** -kentässä. Tämän tulostimen valinta ohittaa tulostimen valinnan, jossa **Käyttäjätunnus**- tai**Raportin tunnus**-kentät ovat tyhjiä. 

Seuraavassa taulukossa on kuvattu arvoyhdistelmät, jotka määritetään raportin tulostinvalinnassa.

|Tehtävä                                                 |Määritä seuraavat arvot                                             |
|---------------------------------------------------|---------------------------------------------------------------------|
|Tulosta raportti tiettyyn tulostimeen kaikkia käytäjiä varten. |Määritä arvot **Tunnus** ja **Tulostimen nimi** -kenttiin ja jätä **Käyttäjätunnus**-kenttä tyhjäksi.|
|Tulosta kaikki raportit tiettyyn tulostimeen tietylle käyttäjälle|Määritä arvot **Käyttäjätunnus** ja **Tulostimen nimi** -kenttiin ja jätä **Tunnus**-kenttä tyhjäksi.|
|Määritä oletustulostin kaikkiin raportteihin|Määritä arvo **Tulostimen nimi** -kenttään ja jätä **Käyttäjätunnus** ja **Tunnus** -kentät tyhjiksi.|
|Tulosta tietty raportti käyttäjän oletustulostimeen|Määritä arvo **Tunnus** -kenttään ja jätä **Tulostimen nimi** ja **Käyttäjätunnus** -kentät tyhjiksi.|
|Tulosta tietty raportti tiettyyn tulostimeen tietylle käyttäjälle|Määritä arvot kaikkiin kolmeen kenttään.|

## <a name="see-also"></a>Katso myös
[Dynamics NAV -ohjelman käyttäminen](ui-work-product.md)

