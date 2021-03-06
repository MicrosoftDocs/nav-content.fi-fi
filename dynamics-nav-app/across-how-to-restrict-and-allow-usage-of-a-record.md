---
title: "Tietueen käytön rajoittaminen ja salliminen"
description: "Jos haluat rajoittaa tietueen käyttöä tietyissä aktiviteeteissa, esimerkiksi ennen kuin tietue on hyväksytty, voit sisällyttää kaksi työnkulun vastausta työnkulkuun, joka määrittää tietueen käyttöä."
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
ms.sourcegitcommit: a16640e014e157d4dbcaabc53d0df2d3e063f8f9
ms.openlocfilehash: 639d6575de6b9ea29c160ecb5cb55cff5574c77d
ms.contentlocale: fi-fi
ms.lasthandoff: 10/26/2017

---
# <a name="how-to-restrict-and-allow-usage-of-a-record"></a>Toimintaohje: rajoita ja salli tietueen käyttö
Jos haluat rajoittaa tietueen käyttöä tietyissä aktiviteeteissa, esimerkiksi ennen kuin tietue on hyväksytty, voit sisällyttää kaksi työnkulun vastausta työnkulkuun, joka määrittää tietueen käyttöä. Yksi työnkulku vastaus rajoittaa tietueen käyttöä työnkulun tapahtuman ja ehtojen mukaan. Toinen työnkulku vastaus sallii tietueen käyttöä työnkulun tapahtuman ja ehtojen mukaan. Yleisessä [!INCLUDE[d365fin](includes/d365fin_md.md)] -versiossa on kaksi vastausta tähän tarkoitukseen: **Rajoita tietueen käyttöä** ja **Salli tietueen käyttö**.

> [!NOTE]  
>  Yleinen [!INCLUDE[d365fin](includes/d365fin_md.md)] -versio tarjoaa tuen tietueen rajoittamiselle kirjaamisen, viennin maksuna ja tulostamisen sekkinä osalta. Muita rajoituksia saadaan, jos Microsoft-kumppani mukauttaa sovelluksen koodin.  

> [!NOTE]  
>  Työnkulun toiminnallisuus rajoittaa ja sallia tietueita käytettäväksi työnkulun toimintoihin ei liity toiminnallisuuteen estää nimike, asiakas ja toimittajatietueiden kirjaaminen.

Seuraavassa kuvataan, miten rajoittaa ostotilausten kirjaamisen ennen kuin ne on hyväksytty. Uusi työnkulku perustuu Ostolaskun hyväksymistyönkulku -työnkulkumalliin.  

## <a name="to-create-a-workflow-step-that-restricts-posting-of-unapproved-purchase-orders"></a>Voit seuraavasti luoda työnkulun vaiheen, joka rajoittaa hyväksymättömiä ostotilausten kirjaus  
1. Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, kirjoita **Työnkulut** ja valitse sitten aiheeseen liittyvä linkki.  
2. Luo **Työnkulut** -ikkunassa uusi työnkulku nimeltä Ostotilauksen hyväksymistyönkulku. Lisätietoja on kohdassa [Työnkulkujen luominen](across-how-to-create-workflows.md).  
3. Valitse **Kopioi työnkulun mallista** -toiminto.  
4. Valita **Lähdetyönkulun koodi** -kenttä ja sitten **Työnkulkumallit**-ikkunassa valitse Ostolaskun hyväksymistyönkulku -työnkulkumalli.  

     Huomaa, että kaksi ensimmäistä työnkulun vaiheet ovat rajoittaminen ja sitten salliminen ostolaskujen käyttö. Siirry muuttamaan uuden työnkulun ensimmäisen vaiheen tapahtumaehtoa niin, että se koskee ostotilauksia.  
5. Valitse **Työnkulun vaiheet** -pikavälilehdessä **Tapahtuman ehdot** -kenttä ja valitse sitten **Asiakirjan tyyppi** -suodattimeksi **Tilaus**.  
6. Siirry muokkaamaan, poistamaan tai lisäämään muita työnkulun vaiheita sovittaaksesi liiketoiminnan prosessi, joka alkaa rajoittamalla hyväksymättömien ostotilausten kirjaaminen.  

## <a name="see-also"></a>Katso myös  
[Toimintaohje: Työnkulkujen luominen](across-how-to-create-workflows.md)   
[Työnkulku](across-workflow.md)   

