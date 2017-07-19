---
title: Myynnin ja varaston ennuste
author: edupont04
ms.custom: na
ms.date: 09/23/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 765527ed4f4800acec20f0abbd4374e95c9c36dc
ms.contentlocale: fi-fi
ms.lasthandoff: 06/26/2017

---

# <a name="sales-and-inventory-forecast-for-dynamics-nav"></a>Myynti- ja varastoennuste Dynamics NAV -ohjelmalle
Varaston hallintaan kuuluvat sekä asiakaspalvelu että kustannusten hallinta. Pieni varasto vaatii vähemmän liikepääomaa, mutta toisaalta varaston loppumiset voivat aiheuttaa myyntimenetyksiä. Myynti- ja varastoennuste -laajennus ennustaa mahdollisen myynnin aiempien tietojen avulla. Se tarjoaa selvän yleiskuvan odotetuista varaston loppumisista. Ennusteen perusteella laajennus auttaa luomaan täydennyspyyntöjä toimittajille, ja säästää näin aikaasi.  

## <a name="setting-up-forecasting"></a>Ennusteiden määrittäminen
Dynamics NAV -ohjelmassa on määritettävä yhteys Azuren automaattianalyysipalveluden kanssa. Lisätietoja on kohdassa [Toimintaohje: Dynamics NAV -ohjelman rekisteröiminen Azure Management Portal -portaalissa](ui-how-register-dynamics-nav-azure.md). Kun olet muodostanut yhteyden, voit määrittää ennusteen niin, että se käyttää raportoinnissa erityyppistä kautta. Ennuste voidaan laatia esimerkiksi kuukauden sijaan neljännesvuosittain. Voit myös valita ennustelaskelmassa käytettävien kausien määrän sen mukaan, miten hajautetun ennusteen haluat. Ennusteen voi tehdä esimerkiksi kuukautta kohti 12 kuukauden ajalle.  

## <a name="using-the-forecasts"></a>Ennusteiden käyttäminen
Laajennus ennustaa tulevan myynnin Azuren automaattianalyysipalveluiden toiminnoilla myyntihistorian perusteella. Näin voidaan välttää puutteet varastossa. Jos esimerkiksi valitset nimikkeen **Nimikkeet**-ikkunassa, kaavion **Nimikkeen ennuste** -ruudussa näkyy tämän nimikkeen arvioitu myynti tulevan kauden aikana. Näin näet, onko nimike loppumassa varastosta lähiaikoina.  

Voit käyttää laajennusta myös varaston täydennysajankohdan ehdottamisessa. Jos esimerkiksi luot ostotilauksen Fabrikamille, koska haluat ostaa heiltä uuden työtuolin, Myynti- ja varastoennuste -laajennus ehdottaa, että samalla kannattaa ostaa LONDON-toimistotuoleja, joita yleensä ostat kyseiseltä toimittajalta. Laajennus ehdottaa tätä sen vuoksi, koska se ennustaa LONDON-toimistotuolien loppuvan varastosta kahden seuraavan kuukauden aikana. Tuoleja siis kannattaa ostaa lisää jo nyt.  

## <a name="see-also"></a>Katso myös
[Myynnin hallinta](sales-manage-sales.md)  
[Varaston hallinta](inventory-manage-inventory.md)  
[Dynamics NAV -ohjelman mukauttaminen laajennusten avulla](ui-extensions.md)  
[Toimintaohje: Dynamics NAV -ohjelman rekisteröiminen Azure Management Portal -portaalissa](ui-how-register-dynamics-nav-azure.md)  

