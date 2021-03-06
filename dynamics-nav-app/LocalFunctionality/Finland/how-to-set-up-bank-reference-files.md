---
title: "Pankin viitetiedostojen määrittäminen"
description: "Elektronisten maksujen käsittelyä varten on ensin määritettävä pankin viitetiedostot, joiden avulla määritetään, miten maksutiedot tuodaan tai viedään."
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
ms.sourcegitcommit: b9b1f062ee6009f34698ea2cf33bc25bdd5b11e4
ms.openlocfilehash: fbfd2d109e813b62a5c1d936be9081052fd7c43c
ms.contentlocale: fi-fi
ms.lasthandoff: 10/23/2017

---
# <a name="how-to-set-up-bank-reference-files"></a>Toimintaohje: Pankin viitetiedostojen määrittäminen
Elektronisten maksujen käsittelyä varten on ensin määritettävä pankin viitetiedostot, joiden avulla määritetään, miten maksutiedot tuodaan tai viedään.  

## <a name="to-set-up-a-bank-reference-file"></a>Pankin viitetiedoston määrittäminen  

1.  Valitse ![Etsi sivu tai raportti -kuvake](../../media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, syötä **Pankin viitetiedoston asetukset** ja valitse sitten aiheeseen liittyvä linkki.  
2.  Täytä **Yleinen**-pikavälilehden kentät seuraavassa taulukossa kuvatulla tavalla.  

    |Kenttä|Description|  
    |---------------------------------|---------------------------------------|  
    |**Nro**|Määrittää pankkitilin koodin.|  
    |**Vie viitemaksut**|Anna vietävän maksutiedoston koko polku.|  
    |**Tuo viitemaksut**|Anna tuotavan maksutiedoston koko polku.|  
    |**Valuutan vaihtokurssitiedosto**|Anna valuutan vaihtokurssitiedoston koko polku.|  
    |**Kohdistettujen hyvityslaskujen tiedot**|Kun valitset tämän, laskuihin kohdistetut hyvitykset näkyvät maksun vastaanottajan tiliotteessa.|  

3.  Täytä **Ulkomaan maksut** -pikavälilehden kentät seuraavassa taulukossa kuvatulla tavalla.  

    |Kenttä|Description|  
    |---------------------------------|---------------------------------------|  
    |**Vie ulkomaan maksut**|Anna ulkomaan pankkeihin vietävän maksutiedoston koko polku.|  
    |**Eräpäivän käsittely**|Määritä, miten eräpäivän käsittelyä käytetään ulkomaan maksuissa.<br /><br /> **Erä** – Kaikki tiedoston maksut saavat saman maksupäivämäärän.<br /><br /> -tai-<br /><br /> **Tapahtuma** – Jokainen tiedoston maksu saa tapahtumakohtaisen maksupäivämäärän. Kysy pankista lisätietoja tämän asetuksen käytöstä.|  
    |**Palvelumaksun oletuskoodi**|Valitse palvelumaksun oletuskoodi ulkomaan pankkeja varten.|  
    |**Oletusmaksutapa**|Valitse oletusmaksutapa ulkomaan pankkeja varten.|  
    |**Vaihtokurssin sopimusnro**|Anna vaihtokurssin sopimusnumero.|  
    |**Salli ulkomaan maksujen yhdistäminen**|Yhdistä kaikki yhdelle vastaanottajalle tietyn päivän aikana samalta pankkitililtä tehdyt ulkomaan maksut.|  

4.  Täytä **SEPA**-pikavälilehden kentät seuraavassa taulukossa kuvatulla tavalla.  

    |Kenttä|Description|  
    |---------------------------------|---------------------------------------|  
    |**Pankin tunnus**|Anna SEPA-pankin tunnus. **Huomautus:** Tätä kenttää käytetään vain SEPA-standardissa pain.001.001.02.|  
    |**Tiedostonimi**|Anna SEPA-maksutiedoston koko polku. **Huomautus:** Tätä kenttää käytetään vain SEPA-standardissa pain.001.001.02.|  

    > [!IMPORTANT]  
    >  Voit viedä toimittajan maksut SEPA-standardin avulla, kun täytät **Maksun vientimuoto** -kentän **Pankkitilin kortti** -ikkunassa.  

5.  Valitse **OK**-painike.  

## <a name="see-also"></a>Katso myös  
 [Verkkopankkitoiminta Suomessa](electronic-banking-in-finland.md)   
 [Toimintaohje: Maksutiedostojen luominen](how-to-generate-payment-files.md)   
 [Toimintaohje: Maksualennusten ohittaminen](how-to-disregard-payment-discounts.md)

