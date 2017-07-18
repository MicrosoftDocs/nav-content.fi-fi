---
title: "Kohdistustunnusten käyttäminen yleisissä päiväkirjoissa"
author: edupont04
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: d239ab62c4be88ccc4a2ce2669dcc2c20a3c0126
ms.contentlocale: fi-fi
ms.lasthandoff: 06/26/2017

---

#  <a name="how-to-use-allocation-keys-in-general-journals"></a>Kohdistustunnusten käyttäminen yleisissä päiväkirjoissa
Voit kohdistaa yleisen päiväkirjan tapahtuman useille eri tileille päiväkirjan kirjaamisen yhteydessä. Kohdistus voidaan tehdä määrän, prosentin tai summan mukaan.

## <a name="to-set-up-allocation-keys"></a>Kohdistustunnusten määrittäminen 
1. Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Toistuva yleinen päiväkirja** ja valitse sitten aiheeseen liittyvä linkki.
2. Valitse **Erän nimi** -kenttä, kun haluat avata **Yleisen päiväkirjan erät** -ikkunan.
3. Voit muokata luettelon olemassa olevan erän kohdistuksia tai luoda uuden erän ja kohdistukset.
  * Luo uusi erä valitsemalla **Uusi**-toiminto ja siirtymällä seuraavaan vaiheeseen.
  * Voit muuttaa olemassa olevan päiväkirjan kohdistuksia valitsemalla päiväkirjan ja siirtymällä vaiheeseen 7.    
4. Syötä **Nimi**-kenttään erän nimi, esimerkiksi SIIVOUS. Syötä **Kuvaus**-kenttään kuvaus, esimerkiksi Siivouskulujen päiväkirja.
5. Kun olet valmis, sulje ikkuna. Esiin tulee uusi tyhjä toistuva kirjaus. 
6. Täytä rivin kentät.
7. Valitse **Kohdistukset**-toiminto. 
8. Lisää rivi jokaista kohdistusta varten. Sinun täytyy täyttää jokin seuraavista kentistä: **Kohdistus- %**, **Kohdistettava määrä** tai **Summa**. Sinun tulee täyttää myös **Tilinro**-kenttä ja, mikäli kohdistat tapahtuman globaaleille dimensioille, globaalin dimension kentät.
9. Jos syötät riville prosentin, ohjelma laskee **Summa**-kentän arvon automaattisesti. Näillä summilla on vastakkainen merkki kuin kokonaissummalla toistuvan kirjauksen **Summa**-kentässä.
10. Kun olet syöttänyt kohdistusrivit, valitse **OK** palataksesi takaisin **Toistuva yleinen päiväkirja** -ikkunaan. **Kohdistettu summa (USD)** -kenttä on täytetty ja vastaa **Summa** -kenttää.
11. Kirjaa päiväkirja.

## <a name="to-change-an-allocation-key-that-has-already-been-set-up"></a>Aiemmin määritetyn kohdistusavaimen muuttaminen
1. Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Toistuva yleinen päiväkirja** ja valitse sitten aiheeseen liittyvä linkki.
2. Valitse **Toistuva yleinen päiväkirja** -ikkunassa päiväkirja, jossa kohdistus on.
3. Valitse kohdistuksen rivi ja valitse sitten **Kohdistukset**-toiminto.
4. Muuta asianmukaiset kentät ja sulje ikkuna.

## <a name="see-also"></a>Katso myös
[Yleisten päiväkirjojen käyttäminen](ui-work-general-journals.md)  
[Asiakirjojen ja päiväkirjojen kirjaaminen](ui-post-documents-journals.md)




