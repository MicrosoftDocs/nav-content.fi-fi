---
title: "Työnkulun käyttäjien määrittäminen"
description: "Työnkuluissa jäseninä olevat käyttäjät on määritettävä, ennen kuin voit luoda työnkulun. On esimerkiksi pakollista määritellä ne henkilöt, jotka saavat ilmoituksen toimia työnkulun osavaiheilla."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: reject, delegate, request
ms.date: 08/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: ed7ca6e166f7100bc19a558825e3103170fc000c
ms.contentlocale: fi-fi
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-set-up-workflow-users"></a>Toimintaohje: Työnkulun käyttäjien määrittäminen
Työnkuluissa jäseninä olevat käyttäjät on määritettävä, ennen kuin voit luoda työnkulun. On esimerkiksi pakollista määritellä ne henkilöt, jotka saavat ilmoituksen toimia työnkulun osavaiheilla.  

Käyttäjät määritellään työnkulun käyttäjäryhmiin **Työnkulun käyttäjäryhmä** -ikkunassa, jonka jälkeen käyttäjän numerot määritetään osaksi prosessin järjestystä, kuten hyväksyjäketjua.  

Työnkulun käyttäjät, jotka toimivat hyväksynnän pyytäjinä ja hyväksyjinä on myös määritettävä työnkulun käyttäjiksi **Hyväksynnän käyttäjäasetukset** -ikkunassa. Lisätietoja on kohdassa [Toimintaohje: Hyväksynnän käyttäjien määrittäminen](across-how-to-set-up-approval-users.md).  

> [!NOTE]  
>  Jos haluat määrittää, että hyväksymispyyntöä ei ole hyväksytty, ennen kuin hyväksyntä-ketjussa usea hyväksyjä on hyväksynyt sen, määritä hyväksyjien hierarkia. Käyttäjätunnukselle **Hyväksyjä** on määritettävä hyväksyjä **Hyväksynnän käyttäjäasetukset** -ikkunassa. Määritä hyväksyjät hyväksyjätyypille **Työnkulun käyttäjäryhmä** **Työnkulun käyttäjäryhmät** -ikkunassa ja määritä hierarkia määrittämällä kullekin hyväksyjälle **Järjestysnro** -kentässä. Lisätietoja on tässä ohjeaiheessa sekä kohdassa [Toimintaohje: Hyväksynnän käyttäjien määrittäminen](across-how-to-set-up-approval-users.md).  
>   
>  Voit määrittää, että hyväksymispyyntöä ei ole hyväksytty, ennen kuin usea hyväksyjä on hyväksynyt sen, huolimatta hierarkiasta, määrittämällä tasainen työnkulun käyttäjäryhmän. Määritä hyväksyjät hyväksyjätyypille **Työnkulun käyttäjäryhmä** **Työnkulun käyttäjäryhmät** -ikkunassa ja määritä kullekin hyväksyjälle sama numero **Järjestysnro** -kentässä. Lisätietoja on tässä ohjeaiheessa.  

### <a name="to-set-up-a-workflow-user"></a>Työnkulun käyttäjän määrittäminen  

1. Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, kirjoita **Työnkulun käyttäjäryhmät** ja valitse sitten liittyvä linkki.  
2. Valitse **Uusi**-toiminto. **Työnkulun käyttäjäryhmä** -ikkuna aukeaa.  
3. Anna **Koodi**-kentässä enintään 20 merkkiä pitkä työnkulun tunniste.  
4. Syötä **Kuvaus**-kenttään työnkulun kuvaus.  
5. Lisää soveltuvat arvot **Työnkulun käyttäjäryhmän jäsenet**-pikalomakkeen ensimmäisen rivin kenttiin seuraavassa taulukossa kuvatulla tavalla.  

    |Kenttä|Description|  
    |---------------------------------|---------------------------------------|  
    |**Käyttäjänimi**|Määritä työnkulkuun osaa ottava käyttäjä.<br /><br /> Käyttäjän on oltava olemassa **Käyttäjien määritys** -ikkunassa. Lisätietoja on kohdassa [Toimintaohje: Käyttäjien ja käyttöoikeuksien hallinta](ui-how-users-permissions.md).|  
    |**Järjestysnro**|Määritä järjestys, jossa työnkulun käyttäjä osallistuu työnkulkuun suhteessa muihin käyttäjiin. Tätä kenttää voidaan käyttää, esimerkiksi määrittämään, milloin käyttäjä hyväksyy suhteessa muihin hyväksyjiin, kun käytät **työnkulun käyttäjäryhmä** -vaihtoehdon **Hyväksyjän tyyppi** -kenttää liittyvässä työnkulkuvastauksessa. **VINKKI:**Jos haluat määrittää, että hyväksymispyyntö ei ole hyväksytty, ennen useat samanarvoiset (hierarkiasta riippumatta) hyväksyjät ovat hyväksyneet sen, määritä tasainen työnkulkuryhmä määrittämällä sama järjestysnumero kyseisille hyväksyjille.|  
6. Toista vaihe 5, jos haluat lisätä useampia työnkulun käyttäjiä ryhmään.  
7. Toista vaiheet 2-6, jos haluat luoda uusia työnkulun käyttäjäryhmiä.  

## <a name="see-also"></a>Katso myös  
[Toimintaohje: Hyväksyjäkäyttäjien määrittäminen](across-how-to-set-up-approval-users.md)   
[Työnkulkujen määrittäminen](across-set-up-workflows.md)   
[Työnkulkujen käyttäminen](across-use-workflows.md)   
[Vaihekuvaus: Ostojen hyväksyntätyönkulun määrittäminen ja käyttäminen](walkthrough-setting-up-and-using-a-purchase-approval-workflow.md)   
[Työnkulku](across-workflow.md)   

