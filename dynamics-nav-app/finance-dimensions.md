---
title: Dimensiot
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
ms.openlocfilehash: a1b38e74717e87bea6efb46f8f4e5236b6ec4e64
ms.contentlocale: fi-fi
ms.lasthandoff: 06/26/2017

---

#<a name="dimensions"></a>Dimensiot
Dimensiot ovat tapahtumiin lisättäviä tietoja, joiden avulla tapahtumat luokitellaan analysointia varten. Dimensioiden avulla voit esimerkiksi ilmaista, mistä projektista tai osastosta tapahtuma on lähtöisin.
Tämän jälkeen voit käyttää dimensioita, jolloin sinun ei tarvitse määrittää erillisiä kirjanpitotilejä kullekin osastolle ja projektille. Näin saat monipuolisia analyysitietoja ilman monimutkaista tilikarttaa.
Voit määrittää rajoittamattoman määrän dimensioita ja dimension arvoja.  

Voit esimerkiksi määrittää dimension nimeltä *Osasto* ja käyttää tätä dimensiota ja sen arvoa myyntiasiakirjojen kirjaamisen yhteydessä. Myöhemmin voit hakea esimerkiksi liiketoimintatietoja myydyistä nimikkeistä osastoittain.
Mitä useampia dimensioita määrität ja käytät, sitä yksityiskohtaisempia raportteja voit käyttää liiketoimintapäätösten apuna. Yhdessä myyntitapahtumassa voi esimerkiksi olla monipuolisesti dimensiotietoja siitä, mille tilille nimikkeen myynti on kirjattu, missä nimike myytiin, kuka sen möi, ja minkälainen asiakas teki oston.  

## <a name="using-dimensions"></a>Dimensioiden käyttäminen
Voit lisätä asiakirjaan, kuten esimerkiksi myyntitilaukseen, dimension tiedot sekä yksittäiseen asiakirjariviin että itse asiakirjaan. Esimerkiksi **Myyntitilaus**-ikkunassa voit syöttää dimension arvot kahdelle ensimmäiselle pikadimensiolle suoraan asiakirjassa. Voit lisätä lisää dimension tietoja valitsemalla **Dimensiot**-painikkeen.  
Jos käsittelyssä sen sijaan on päiväkirja, voit lisätä dimension tietoja tapahtumaan samalla tavalla, jos olet määrittänyt pikadimensiot kentiksi suoraan päiväkirjan riveille.  
Voit määrittää tileille tai tilityypeille oletusdimensioita, jolloin dimensiot tai dimensioiden arvot täytetään automaattisesti.  

## <a name="dimension-sets"></a>Dimensioyhdistelmät
Dimensioyhdistelmä on dimensioarvojen yksilöllinen yhdistelmä. Se tallennetaan dimensioyhdistelmän tapahtumiksi tietokantaan. Kukin dimensioyhdistelmän tapahtuma edustaa yksittäistä dimensioarvoa. Dimensioyhdistelmä tunnistetaan yhteisellä dimensioyhdistelmän tunnuksella, joka määritetään jokaiselle yhdistelmään kuuluvalle tapahtumalle.  

Kun luot uuden päiväkirjarivin, asiakirjaotsikon tai asiakirjarivin, voit määrittää dimensioarvojen yhdistelmän. Sen sijaan, että tallentaisit jokaisen dimensioarvon erikseen tietokantaan, dimensioyhdistelmä määritetään päiväkirjan rivillä, asiakirjaotsikossa tai asiakirjan rivillä dimensioyhdistelmän tunnuksen avulla.  

## <a name="see-also"></a>Katso myös
[Rahoitus](finance-setup.md)  
[Dimensioiden määrittäminen](finance-setup-setup-dimensions.md)  

