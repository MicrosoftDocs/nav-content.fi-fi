---
title: "Tietojenvaihdon määrittäminen"
description: "Määritä Dynamics NAV -ohjelman tiedonsiirtokehys."
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 08/21/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: bd45b6a3d0a611154828a0c9b6a8e39fe1c14635
ms.contentlocale: fi-fi
ms.lasthandoff: 10/16/2017

---
# <a name="setting-up-data-exchange"></a>Tiedonsiirron määrittäminen
Ennen kuin voit lähettää ja vastaanottaa sähköisiä asiakirjoja tai tuoda ja viedä pankkitiedostoja, sinun on määritettävä tiedonsiirtokehys tiedostojen käsittelemistä varten. Lisäksi joudut määrittämään toimintoon liittyviä alueita (esimerkiksi niiden asiakkaiden perustiedot, joille lähetät sähköisiä laskuja, tai pankkitietojen muuntopalvelun, jos käytät ulkoista palveluntarjoajaa pankkitiedostojen muuntamiseen). Lisätietoja on kohdassa [Sähköinen tiedonsiirto](across-data-exchange.md).  

 Kun [!INCLUDE[d365fin](includes/d365fin_md.md)] on määritetty vaihtamaan tietoja ulkoisten tiedostojen kanssa, käyttäjät voivat käyttää määritystä yleisissä liiketoimintatehtävissä, kuten sähköisten asiakirjojen lähettämisessä ja vastaanottamisessa sekä pankkitiedostojen tuonnissa ja viennissä.  

 Seuraavassa taulukossa on tehtäväsarja ja linkit tehtäviä käsitteleviin aiheisiin.  

|**Tehtävä**|**Katso**|  
|------------|-------------|  
|Määritä valmiiksi määritetty document exchange -palvelu sallimaan lähettää ja vastaanottaa sähköisiä asiakirjoja [!INCLUDE[d365fin](includes/d365fin_md.md)]:n kanssa.|[Toimintaohje: Document Exchange -palvelun määrittäminen](across-how-to-set-up-a-document-exchange-service.md)|  
|Määritä valmiiksi määritetty OCR-palvelu muuntamaan PDF- tai kuvatiedostot sähköisiksi asiakirjoiksi, jotka voidaan muuntaa [!INCLUDE[d365fin](includes/d365fin_md.md)]in tiedoston tietueiksi.|[Toimintaohje: Saapuvien asiakirjojen määrittäminen](across-how-setup-income-documents.md)|  
|Määritä yksi tai kaksi esimääritettyä palvelua käyttämään päivitettyjä valuuttakursseja, jotta saat uusimmat valuutanvaihtokurssit järjestelmään **Valuutat**-ikkunaan.|[Toimintaohje: Valuutan vaihtokurssien päivittäminen](finance-how-update-currencies.md)|  
|Määritä joitakin perustietoja, kuten yrityksen tiedot, asiakkaat, toimittajat, nimikkeet ja mittayksiköt, jotka liittyvät tietojen yhdistämiseen [!INCLUDE[d365fin](includes/d365fin_md.md)]issa.|[Toimintaohje: Sähköisten asiakirjojen vastaanottamisen ja lähettämisen määrittäminen](across-how-to-set-up-electronic-document-sending-and-receiving.md)|  
|Määritä pankkitili, myyjä ja maksuloki SEPA-tilisiirrolle.|[Toimintaohje: SEPA-hyvityksen siirron määrittäminen](finance-how-to-set-up-sepa-credit-transfer.md)|  
|Valmistele pankkitilimuodot, maksutavat ja asiakkaan SEPA-suoraveloitussopimukset.|[Toimintaohje: SEPA-suoraveloituksen määrittäminen](finance-how-to-set-up-sepa-direct-debit.md)|  
|Määritä käyttäjätunnistus ja pankkitietojen muuntopalvelun tarjoajan URL, joka vaaditaan, jotta pankkitiedostot voidaan muuttaa pankkisi vaatimaan muotoon.|[Toimintaohje: Pankkitietojen muuntopalvelun määrittäminen](bank-how-setup-bank-data-conversion-service.md)|  
|Määritä ja ota käyttöön ulkoinen palvelu, jonka avulla voit tuoda pankin tiliotteet suoraan pankkisyötteinä.|[Toimintaohje: Pankkitietojen muuntopalvelun määrittäminen](bank-how-setup-bank-data-conversion-service.md)|  
|Kun pankkitietojen muuntopalvelu on otettu käyttöön, linkitä pankkitilit [!INCLUDE[d365fin](includes/d365fin_md.md)] -sovelluksessa.|[Toimintaohje: Pankkitilien määrittäminen](bank-how-setup-bank-accounts.md)|  
|Valmistele datatiedoston tai tietovirran uuden tietojenvaihtomäärityksen luonti käyttämällä tiedoston XML-rakennetta. Se esitäyttää **Sarakkeen määritykset** -pikalomakkeen **Kirjauksen tiedonsiirtomääritykset** -ikkunassa.|[Toimintaohje: XML-rakenteiden käyttäminen tiedonsiirtomääritysten valmistelussa](across-how-to-use-xml-schemas-to-prepare-data-exchange-definitions.md)|  
|Määritä tietojen vaihtokehys, jotta käyttäjät voivat vastaanottaa ja lähettää tietoja uudessa ostoasiakirjamuodossa, tuoda uuden pankkitiedoston tai vaihtaa muita tietoja.|[Toimintaohje: Tietojenvaihtomääritysten määrittäminen](across-how-to-set-up-data-exchange-definitions.md)|  

## <a name="see-also"></a>Katso myös  
[Sähköinen tiedonsiirto](across-data-exchange.md)  
[Tietojen siirto](across-exchange-data.md)   
[Saapuvat asiakirjat](across-income-documents.md)  
[Yleiset liiketoimintatoiminnot](ui-across-business-areas.md)  

