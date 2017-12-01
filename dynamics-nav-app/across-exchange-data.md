---
title: Tietojen vaihto
description: "[!INCLUDE[d365fin](includes/d365fin_md.md)] on määritetty vaihtamaan tietoja ulkoisten tiedostojen tai virtojen kanssa, jotka on liitetty yleisiin liiketoimintatehtäviin, kuten sähköisten asiakirjojen lähettämiseen ja vastaanottamiseen sekä pankkitiedostojen tuontiin ja vientiin."
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 08/18/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: b9b1f062ee6009f34698ea2cf33bc25bdd5b11e4
ms.openlocfilehash: d83e68f31edf2dee9e3e5bc5b73a4861cfe919d7
ms.contentlocale: fi-fi
ms.lasthandoff: 10/23/2017

---
# <a name="exchanging-data"></a>Tietojen vaihtaminen
[!INCLUDE[d365fin](includes/d365fin_md.md)] -järjestelmä on määritetty vaihtamaan tietoja ulkoisten tiedostojen tai virtojen kanssa, jotka on liitetty yleisiin liiketoimintatehtäviin, kuten sähköisten asiakirjojen lähettämiseen ja vastaanottamiseen sekä pankkitiedostojen tuontiin ja vientiin.  

Ennen kuin voit lähettää ja vastaanottaa sähköisiä asiakirjoja tai tuoda ja viedä pankkitiedostoja, sinun on määritettävä tiedonsiirtokehys datatiedostojen tai virtojen käsittelemistä varten. Liittyvät alueet pitää määritellä. Näihin kuuluvat esimerkiksi niiden asiakkaiden perustiedot, joille lähetät sähköisiä laskuja, tai pankkitietojen muuntopalvelun, jos käytät ulkoista palveluntarjoajaa pankkitiedostojen muuntamiseen. Lisätietoja on kohdassa [Tiedonsiirron määrittäminen](across-set-up-data-exchange.md).  

 Seuraavassa taulukossa on tehtäväsarja ja linkit tehtäviä käsitteleviin aiheisiin.  

|**Tehtävä**|**Katso**|  
|------------|-------------|  
|Muunna myyntiasiakirjojen tietueet [!INCLUDE[d365fin](includes/d365fin_md.md)]:ssa vakiomuotoon, jotka voi lähettää asiakkaalle sähköisessä muodossa tuotavaksi asiakkaan omaan järjestelmään.|[Toimintaohje: Sähköisten asiakirjojen lähettäminen](sales-how-to-send-electronic-documents.md)|  
|Lähetä PDF tai kuvatiedostot OCR-palvelun tuottajalle. Saat ne takaisin sähköisinä asiakirjoina, jotka voidaan muuntaa [!INCLUDE[d365fin](includes/d365fin_md.md)]:n asiakirjatietueiksi.|[Toimintaohje: PDF- ja kuvatiedostojen muuntaminen sähköisiksi asiakirjoiksi OCR-palvelun avulla](across-how-use-ocr-pdf-images-files.md)|  
|Vastaanota sähköiset, joko asiakirjat OCR-palvelusta tai document exchange-palvelusta, standardoidussa muodossa, jonka voit muuntaa asiakirjan tietueiksi [!INCLUDE[d365fin](includes/d365fin_md.md)]:ssa.|[Toimintaohje: Sähköisten asiakirjojen vastaanottaminen ja muuntaminen](purchasing-how-to-receive-and-convert-electronic-documents.md)|  
|Tuo tiliotetiedosto **Maksujen täsmäytyskirjauskansio** -ikkunaan saatujen maksujen käsittelyn aluksi, tai **Pankkitilin täsmäytys** -ikkunaan pankkitilien tasaamisen aluksi.|[Maksujen kohdistaminen automaattisesti ja pankkitilien täsmäyttäminen](receivables-apply-payments-auto-reconcile-bank-accounts.md)|  
|Vie maksut **Maksupäiväkirja**-ikkunasta pankkitiedostoon, jonka lataat verkkopankkitilille käsiteltäväksi.|[Kuinka maksut viedään pankkitiedostoon](payables-how-export-payments-bank-file.md)|  
|Ohjaa pankkiasi siirtämään maksusummat asiakkaan pankkitileiltä yrityksesi pankkitilille SEPA-suoraveloitusasetustesi mukaisesti.|[Toimintaohjeet: Kuinka SEPA-suoraveloitusperintämerkinnät luodaan ja viedään pankkitiedostoon](finance-how-create-sepa-direct-debit-collection-entries-export-bank-file.md)|  
|Päivitä **Valuutat**-ikkunan käyttämällä vaihtokurssin päivityspalvelun palveluntarjoajaa.|[Toimintaohje: Valuutan vaihtokurssien päivittäminen](finance-how-update-currencies.md)|  
|Tarkastele, mitkä tiedostoelementit on yhdistetty [!INCLUDE[d365fin](includes/d365fin_md.md)] -järjestelmän kenttiin kun tuot SEPA CAMT -tiliotetiedostoja.|[Kenttien vastaavuuksien määrittäminen tuotaessa SEPA-CAMT-tiedostoja](across-field-mapping-when-importing-sepa-camt-files.md)|  
|Tarkastele, mitkä tiedostoelementit on yhdistetty [!INCLUDE[d365fin](includes/d365fin_md.md)] -järjestelmän kenttiin kun viet maksutiedostoja pankkipäivämäärän muuntopalvelu-ominaisuuteen.|[Kenttien vastaavuuksien määrittäminen vietäessä maksutiedostot käyttämällä pankkitietojen muuntopalvelua](across-field-mapping-when-exporting-payment-files-using-bank-data-conversion-service.md)|  

## <a name="see-also"></a>Katso myös  
[Tiedonsiirron määrittäminen](across-set-up-data-exchange.md)  
[Sähköinen tiedonsiirto](across-data-exchange.md)  
[Toimintaohje: Myynnin laskutus](sales-how-invoice-sales.md)   
[Toimintaohje: Ostojen kirjaus](purchasing-how-record-purchases.md)  
[Saapuvat asiakirjat](across-income-documents.md)  
[Yleiset liiketoimintatoiminnot](ui-across-business-areas.md)  

