---
title: "Yleiskatsaus huoltonimikkeiden ja huoltonimikkeen komponenttien määrityksistä"
description: "Lisätietoja määrityksistä, jotka on tehtävä ennen huoltonimikkeiden käyttöä. Esimerkiksi oletusarvot, kuten vastausaika, sopimusalennusprosentti ja huoltohintaryhmä, on määritettävä."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 07/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 0632bdc3b12e60c9b49893df748e8ca165c5b9d4
ms.contentlocale: fi-fi
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-set-up-service-items-and-service-item-components"></a>Toimintaohje: Huoltonimikkeiden ja huoltonimikkeen komponenttien määrittäminen
Huoltonimikkeiden käyttöä varten on määritettävä seuraavat asetukset

* Huoltonimikeryhmät. 
* Valinnainen

## <a name="to-set-up-service-item-groups"></a>Huoltonimikeryhmien määrittäminen
Voit määrittää korjaus- ja ylläpitoehtoihin liittyvät nimikeryhmät. Huoltonimikeryhmässä oleville huoltonimikkeille voi määritellä oletusarvoja, kuten vastausajan, sopimusalennus-%:n ja huoltohintaryhmän. Huoltonimikeryhmässä olevien nimikkeiden osalta voi valita, halutaanko, että ne rekisteröidään automaattisesti huoltonimikkeiksi silloin, kun ne myydään.  
  
Huoltonimikeryhmiä määritetään **Nimike**-kortin nimikkeille ja **Huoltonimike**-kortin huoltonimikkeille.  
  
1. Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, kirjoita **Huoltonimikeryhmät** ja valitse sitten aiheeseen liittyvä linkki.  
2. Luo uusi huoltonimikeryhmä.  
3. Täytä **Koodi**- ja **Kuvaus**-kentät.  
4. Anna **Oletus sopimusalennus-%** -kenttään oletussopimusalennusprosentti, jonka haluat ryhmässä olevilla huoltonimikkeillä olevan.  
5. Anna **Oletus huoltohintaryhmän koodi** -kenttään oletushuoltohintaryhmän koodi, jonka haluat ryhmässä olevilla huoltonimikkeillä olevan.  
6. Anna **Oletusvastausaika (tuntia)** -kenttään oletusvastausaika tunneissa, jonka haluat ryhmässä olevilla huoltonimikkeillä olevan.  
7. Jos haluat rekisteröidä ryhmän nimikkeen huoltonimikkeiksi silloin, kun ne myydään, valitse **Luo huoltonimike** -kenttä.  

## <a name="to-set-up-service-item-components"></a>Huoltonimikkeen komponenttien määrittäminen
Huoltonimike voi koostua useista komponenteista, jotka voidaan korvata varaosilla nimikettä huollettaessa. Nämä komponentit määritetään **Huoltonimikk. komponenttiluet.** -sivulla. Jos lisäksi haluat määrittää komponentteja huoltonimikkeille, jotka ovat tuoterakenteita, tuoterakennenimikkeet voidaan kopioida ja luoda huoltonimikkeen komponentteina. 
  
1. Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, kirjoita **Huoltonimikkeet** ja valitse sitten aiheeseen liittyvä linkki. 
2. Avaa huoltonimike, jolle haluat määrittää komponentteja.  
3. Valitse **Komponentit**-toiminto. Näyttöön tulee **Huoltonimikk. komponenttiluet.** -ikkuna.  
4. Uuden ryhmän lisääminen  
5. Valitse **Tyyppi** -kentässä **Huoltonimike**, jos itse komponentti on rekisteröity huoltonimike. Muutoin valitse **Nimike**.  
6. Valitse **Nro**-kenttään nimike tai huoltonimike, joka on huoltonimikkeen komponentti.  

## <a name="to-set-up-service-item-components-from-a-bom"></a>Huoltonimikkeen komponenttien määrittäminen tuoterakenteista
1.  Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, kirjoita **Huoltonimikkeet** ja valitse sitten aiheeseen liittyvä linkki.  
2. Avaa huoltonimike, jolle haluat määrittää komponentteja huoltorakenteesta.  
3. Valitse **Komponentit**-toiminto. **Huoltonimikk. komponenttiluet.** -ikkuna avautuu.  
4. Valitse **Kopioi tuoterakenteesta** -toiminto.  
  
    Jos nimike, johon huoltonimike on linkitetty, on tuoterakenne, ohjelma luo automaattisesti komponentteja kaikille tuoterakenteessa oleville nimikkeille.  

## <a name="to-set-up-a-service-shelf"></a>Huoltohyllyn määrittäminen
Voit määrittää huoltohyllyjä, jotka ilmaisevat, mihin huoltonimikkeet varastoidaan. Huoltohyllyt määritetään huoltonimikkeille **Huoltotilaus**- ja **Huoltonimikkeen työkirja** -sivuilla.  
  
1. Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, kirjoita **Huoltohyllyt** ja valitse sitten aiheeseen liittyvä linkki.
2. Täytä tarvittavat kentät.

## <a name="see-also"></a>Katso myös
[Toimintaohje: Vakiohuoltokoodien määrittäminen](service-how-setup-service-coding.md)   
[Toimintaohje: Vianetsinnän määrittäminen:](service-how-setup-troubleshooting.md)
