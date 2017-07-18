---
title: "Toimintaohje: Aikaraporttien määrittäminen"
author: SorenGP
ms.custom: na
ms.date: 11/01/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 6cbacce79ce185d6ed00ea8383259d1b28f9e11b
ms.contentlocale: fi-fi
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-set-up-time-sheets"></a>Aikaraporttien määrittäminen
Dynamics NAV -ohjelman aikaraportit käsittelevät aikarekisteröintiä viikoittain seitsemän päivän välein. Voit käyttää niitä projekteissa käytettävän ajan seuraamiseen ja yksinkertaisen resurssin aikarekisteröinnin kirjaamiseen. Ennen kuin voit käyttää aikaraportteja, on määritettävä tavat niiden määrittämiseen ja asetuksiin.

Kun olet määrittänyt, miten organisaatiossa käytetään aikaraportteja, voit määrittää aikaraporttien hyväksymistä koskevat ehdot. Organisaation tarpeista riippuen voit määrittää seuraavat vaihtoehdot:

- Vähintään yhden käyttäjän aikaraportin järjestelmänvalvojaksi ja hyväksyjäksi kaikkia aikaraportteja varten.
- Kunkin resurssin aikaraportin hyväksyjän.

Kun olet määrittänyt aikaraportit, voit luoda resursseille aikaraportit, määrittää ne projektin suunnitteluriveille ja kirjata aikaraporttirivit. Lisätietoja on kohdassa [Toimintaohje: Aikaraporttien käyttäminen](projects-how-use-time-sheets.md).

## <a name="to-set-up-general-information-for-time-sheets"></a>Aikaraporttien yleistietojen määrittäminen  

1. Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Resurssienhallinnan asetukset** ja valitse sitten aiheeseen liittyvä linkki.  
2. Täytä tarvittavat kentät. Lue kentän lyhyt kuvaus valitsemalla kenttä tai siirry lisätietoihin valitsemalla linkki.
3. Valitse **Aikaraportin projektihyväksyntä** -kenttään jokin seuraavista valinnoista.

|Asetus |Kuvaus|
|---|---|
|**Ei koskaan**|Resurssikortin **Aikaraportin hyväksyjän käyttäjätunnus** -kenttä hyväksyy aikaraportin.|
|**Aina**|Projektikortin **Vastuuhenkilö**-kenttä hyväksyy aikaraportin.|
|**Vain kone**|Jos koneen aikaraportti on linkitetty projektiin, projektikortin **Vastuuhenkilö**-kentässä mainittu käyttäjä hyväksyy aikaraportin. Jos koneen aikaraportti on linkitetty resurssiin, resurssikortin **Aikaraportin hyväksyjän käyttäjätunnus** -kentässä mainittu käyttäjä hyväksyy aikaraportin.

## <a name="to-assign-a-time-sheet-administrator"></a>Aikaraportin järjestelmänvalvojan määrittäminen  

1. Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Käyttäjäasetukset** ja valitse sitten aiheeseen liittyvä linkki.  
2.  Lisää uusi käyttäjä, jos käyttäjäluettelo ei sisällä henkilöä, jonka haluat olevan aikaraportin järjestelmänvalvoja. Pyydä lisätietoja järjestelmänvalvojalta.  
3. Valitse käyttäjä, josta tulee aikaraportin järjestelmänvalvoja, ja valitse sitten **Aikaraportin valvoja** -valintaruutu.  

**Vihje**: Yrityksen aikaraportin järjestelmänvalvojaksi kannattaa nimetä vain yksi käyttäjä. Seuraavassa toimenpiteessä määritetään aikaraportin omistaja ja hyväksyjä. Aikaraportin hyväksyjä määritetään jokaiselle resurssille.  

## <a name="to-assign-a-time-sheets-owner-and-approver"></a>Aikaraportin omistajan ja hyväksyjän määrittäminen  

1. Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Resurssit** ja valitse sitten aiheeseen liittyvä linkki.
2. Valitse resurssi, jolle haluat määrittää aikaraporttien käyttömahdollisuuden. Valitse sitten **Käytä aikaraporttia** -valintaruutu.  
3. Syötä aikaraportin omistajan tunnus **Aikaraportin omistajan käyttäjätunnus** -kenttään. Omistaja voi syöttää ajankäytön aikaraporttiin ja lähettää sen hyväksyttäväksi. Jos resurssi on henkilö, tämä henkilö on yleensä myös omistaja.  
4. Syötä aikaraportin hyväksyjän tunnus **Aikaraportin hyväksyjän käyttäjätunnus** -kenttään. Hyväksyjä voi hyväksyä, hylätä tai uudelleenavata aikaraportin.  

**Huomautus**: Aikaraportin hyväksyjän tunnusta ei voi muuttaa, jos on aikaraportteja, joita ei ole vielä käsitelty ja joiden tila on **Lähetetty** tai **Avoin**.

## <a name="see-also"></a>Katso myös
[Projektinhallinnan määrittäminen](projects-setup-projects.md)  
[Projektien hallinta](projects-manage-projects.md)  
[Rahoitus](finance-setup.md)  
[Ostojen hallinta](purchasing-manage-purchasing.md)         
[Myynnin hallinta](sales-manage-sales.md)      
[Dynamics NAV -ohjelman käyttäminen](ui-work-product.md)  

