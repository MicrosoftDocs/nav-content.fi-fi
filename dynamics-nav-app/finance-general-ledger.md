---
title: "Pääkirjanpito ja tilikartta"
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
ms.openlocfilehash: 9965ddcad214e97c5e4858824395d6f651b3c003
ms.contentlocale: fi-fi
ms.lasthandoff: 06/26/2017

---

# <a name="the-general-ledger-and-the-chart-of-accounts"></a>Pääkirjanpito ja tilikartta
Pääkirjanpito sisältää taloustiedot ja tilikartta näyttää tilit, joihin kaikki pääkirjanpidon tapahtumat kirjataan. Dynamics NAV sisältää tilikartan, joka on valmis tukemaan liiketoimintaasi.

## <a name="general-ledger-setup-and-general-posting-setup"></a>Pääkirjanpidon asetukset ja yleiset kirjausasetukset
Pääkirjanpito ja siihen kirjattavien tietojen määritys muodostavat liiketoimintaprosessien ytimen.
**Pääkirjanpidon asetukset** -ikkunassa määritetään, miten yrityksen tietyt kirjanpitoasiat hoidetaan. Tiedot sisältävät esimerkiksi laskujen pyöristystiedot, osoitemuodot ja mahdollisen lisäraportointivaluutan käyttämisen.
Samaan tapaan määritetään **Yleiset kirjausasetukset** -ikkunassa, miten liiketoiminnan ja tuotteen yleisten kirjausryhmien yhdistelmät määritetään. Jokaiselle liiketoiminnan kirjausryhmän ja tuotteen kirjausryhmän yhdistelmälle täytetään rivi.  

## <a name="the-chart-of-accounts"></a>Tilikartta
Tilikartassa näkyvät kaikki tilit. Tilikartan avulla voit avata erilaisia raportteja, jotka sisältävät pääkirjanpidon tapahtumia ja saldoja. Voit myös sulkea tuloslaskelmia. Voit avata kunkin tilin KP-tilin kortin ja lisätä tai muuttaa asetuksia. Näkyvillä on myös luettelo kirjausryhmistä, jotka tekevät kirjauksia kyseiselle tilille.  

Dynamics NAV ei anna poistaa pääkirjanpitotiliä, joka sisältää tilikartassa tarvittavia tietoja.  

## <a name="account-categories"></a>Tililuokat
Tililuokkien avulla voi yhdistää pääkirjanpitotilit luokkiin talouslaskelmien rakenteen mukautuksena.  

**KP-tilin luokat**-ikkuna sisältää aiemmin luodut pää- ja alaluokat sekä kuhunkin luokkaan liitetyt KP-tilit. Voit luoda uusia alaluokkia ja liittää luokat aiemmin luotuihin tileihin.  

Voit ryhmitellä tililuokat sisentämällä yksittäiset alaluokat. Tällöin yleiskuvauksen saaminen on helppoa, koska kunkin ryhmittelyn yhteydessä näytetään kokonaissaldo. Voit luoda esimerkiksi alaluokkia eri käyttöomaisuustyypeille ja luoda sitten luokkaryhmiä esimerkiksi käyttöomaisuudelle ja nykyisille vastaaville. Voit luoda luokkaryhmän sisentämällä **KP-tilin luokat** -ikkunan rivin alla olevia muita alaluokkia.  

Määritä, tuleeko alaluokan tilit sisällyttää tiettyyn talousraporttityyppiin. Tililuokat auttavat rahoituslaskelmien asettelun määrittämisessä. Esimerkiksi oletussaldon tiliote sisältää yhden tapahtuman käteiselle kohdassa Vastaavaa. Jos haluat saldon tiliotteen sisältävän käteiskassan ja sekkitilin korvaustapahtumia, voit lisätä kaksi uutta alaluokkaa, määrittää niille raportin lisämääritykseksi Käteistilit ja sisentää ne Käteinen-alaluokan alle. Kun olet luonut KP-raporttimallit muutosten perusteella, seuraavassa saldon tiliotteessa näkyvät käteisen kokonaissaldo sekä käteiskassan ja sekkitilin saldojen kaksi riviä.     

##<a name="see-also"></a>Katso myös
[Rahoitus](finance-setup.md)  
[Tilikartan määrittäminen tai muuttaminen](finance-setup-setup-chart-accounts.md)  
[KP-raporttimallit](finance-setup-account-schedule.md)  

