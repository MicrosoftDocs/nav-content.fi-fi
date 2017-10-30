---
title: "Ilmoitusten vastaanoton ajankohdan ja tavan määrittäminen"
description: "Kun määrität käyttäjiä hyväksynnän työnkulkuihin, Ilmoituksen asetukset ja Ilmoitusaikataulu-ikkunoissa on määritettävä miten ja milloin käyttäjät saavat ilmoituksia hyväksynnän työnkulun osavaiheista. Yksittäiset käyttäjät voivat muuttaa ilmoitusasetuksiaan valitsemalla Muuta ilmoitusasetuksia -painikkeen, joka näytetään kaikissa ilmoituksissa."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 07/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 7d4c09b216f64b41a1bd72507c7a09c05e19d06a
ms.contentlocale: fi-fi
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-specify-when-and-how-to-receive-notifications"></a>Toimintaohje: Määritä, milloin ja miten käyttäjät saavat ilmoituksia
Kun määrität käyttäjiä hyväksynnän työnkulkuihin, **Ilmoituksen asetukset** ja **Ilmoitusaikataulu**-ikkunoissa on määritettävä miten ja milloin käyttäjät saavat ilmoituksia hyväksynnän työnkulun osavaiheista. Yksittäiset käyttäjät voivat muuttaa ilmoitusasetuksiaan valitsemalla **Muuta ilmoitusasetuksia** -painikkeen, joka näytetään kaikissa ilmoituksissa.  

 Ennen kuin voit määrittää hyväksynnän käyttäjän ilmoitusasetukset, käyttäjä on määritettävä hyväksynnän käyttäjäksi. Lisätietoja on kohdassa [Toimintaohje: Hyväksynnän käyttäjien määrittäminen](across-how-to-set-up-approval-users.md).  

 Ilmoitusten asettelu ja sisältö määritetään ilmoitusmalleilla. Lisätietoja on kohdassa [Toimintaohje: Ilmoitusmallien hallinta](across-how-to-manage-notification-templates.md).  

 Useat hyväksyntätyönkulun osavaiheet ilmoittavat käyttäjille toimia vaativista tapahtumista. Työnkulun osavaiheen tapahtuma voi olla esimerkiksi se, että käyttäjä 1 pyytää uuden tietueen hyväksymistä. Vastauksena lähetetään ilmoitus käyttäjälle 2 (hyväksyjälle). Seuraavan työnkulun osavaiheen tapahtuma voi olla se, että käyttäjä 2 hyväksyy tietueen. Vastauksena lähetetään ilmoitus käyttäjälle 3, jotta hyväksytyn tietueen käsittely voidaan aloittaa. Hyväksyntään liittyvien työnkulun osavaiheiden ilmoitukset ovat sidoksissa hyväksyntämerkintään. Lisätietoja on kohdassa [Työnkulku](across-workflow.md).  

## <a name="specify-when-and-how-users-receive-notifications"></a>Määritä, milloin ja miten käyttäjät saavat ilmoituksia  

1.  Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "") -kuvake, kirjoita **Hyväksynnän käyttäjäasetukset** ja valitse sitten aiheeseen liittyvä linkki.  
2.  Valitse sen käyttäjän rivi, jonka ilmoitusasetukset haluat määrittää, ja valitse sitten **Ilmoitusasetukset**-toiminto.  
3.  Täytä **Ilmoituksen asetukset** -ikkunan kentät seuraavassa taulukossa kuvatulla tavalla.  

    |Kenttä|Description|  
    |---------------------------------|---------------------------------------|  
    |**Ilmoitustyyppi**|Määritä, minkälaiseen tapahtumaan ilmoitus liittyy.<br /><br /> Valitse jompikumpi seuraavista vaihtoehdoista:<br /><br /> -   **Uusi tietue** tarkoittaa, että ilmoitus koskee uutta tietuetta, kuten asiakirjaa, joka vaatii käyttäjän huomiota.<br />-   **Hyväksyntä** tarkoittaa, että ilmoitus koskee yhtä tai useampaa hyväksyntäpyyntöä.<br />-   **Myöhässä** tarkoittaa, että ilmoitus muistuttaa käyttäjiä, että tiettyä tapahtumaa ei ole huomioitu ajoissa.|  
    |**Ilmoitusmallin koodit**|Määritä ilmoitusmallin koodi, jota käytetään käyttäjän ilmoitusten luonnissa.|  
    |**Yhdistämättömät ilmoitukset**|Määritä, lähetetäänkö käyttäjälle yksi ilmoitus jokaista tapahtumaa kohti vai koostettuja ilmoituksia.<br /><br /> Jos **Yhdistämättömät ilmoitukset** -valintaruutua ei ole valittu, käyttäjä saa ilmoituksia, joihin on koottu tietoja tapahtumista, jotka tapahtuvat samalla toistumiskaavalla ilmoitusjakson aikana.|  

     Olet nyt määrittänyt, miten käyttäjä saa ilmoituksia. Määritä seuraavaksi, milloin käyttäjä saa ilmoituksia.  

4.  Valitse **Ilmoitusaikataulu**-toiminto.  
5.  Täytä **Ilmoitusaikataulu**-ikkunan kentät seuraavassa taulukossa kuvatulla tavalla.  

    |Kenttä|Description|  
    |---------------------------------|---------------------------------------|  
    |**Toistuminen**|Määritä toistumiskaava, jonka mukaan käyttäjä saa ilmoituksia.|  
    |**Aika**|Määritä, mihin kellonaikaan käyttäjä vastaanottaa ilmoitukset, kun **Toistuminen**-kentän arvo on jokin muu kuin **Heti**.|  
    |**Päivittäinen esiintymistiheys**|Määritä, minkälaisina päivinä käyttäjä saa ilmoituksia kun **Toistuminen**-kentän arvo on **Päivittäin**.<br /><br /> Valitse **Arkipäivisin**, jos haluat saada ilmoituksia jokaisena arkipäivänä. Valitse **Päivittäin**, jos haluat saada ilmoituksia jokaisena viikonpäivänä, myös viikonloppuisin.|  
    |**Maanantai** - **Sunnuntai**|Määritä, minä päivinä käyttäjä saa ilmoituksia kun **Toistuminen**-kentän arvo on **Viikoittain**.|  
    |**Kuukaudenpäivä**|Määritä, lähetetäänkö käyttäjälle ilmoituksia kuukauden ensimmäisenä, viimeisenä, tai tiettynä päivänä.|  
    |**Kuukausittaisen ilmoituksen pvm**|Määritä, minä kuun päivänä käyttäjä saa ilmoituksia kun **Kuukaudenpäivä** -kentän arvo on **Mukautettu**.|  

## <a name="change-when-and-how-you-receive-notifications"></a>Muuta, milloin ja miten saat ilmoituksia  
1.  Valitse jossain saamassasi sähköposti- tai viesti-ilmoituksessa olevaa **Muuta ilmoitusasetuksia** -painiketta.  
2.  Muuta ilmoitusasetuksiasi **Ilmoituksen asetukset** -ikkunassa edellä kuvattujen ohjeiden mukaisesti.  

## <a name="see-also"></a>Katso myös  
 [Toimintaohje: Hyväksyjäkäyttäjien määrittäminen](across-how-to-set-up-approval-users.md)   
 [Toimintaohje: Ilmoitusmallien hallinta](across-how-to-manage-notification-templates.md)   
 [Työnkulkuilmoitusten määrittäminen](across-setting-up-workflow-notifications.md)   
 [Työnkulkujen määrittäminen](across-set-up-workflows.md)   
 [Työnkulkujen käyttäminen](across-use-workflows.md)

