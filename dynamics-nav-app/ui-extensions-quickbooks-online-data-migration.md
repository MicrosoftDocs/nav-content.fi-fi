---
title: "QuickBooks-tietojen siirtolaajennuksen käyttäminen"
description: "Tässä ohjeaiheessa käsitellään, miten laajennuksella siirretään asiakkaita, toimittajia, nimikkeitä ja tilejä QuickBooks Onlinesta Dynamics NAViin."
documentationcenter: 
author: bholtorf
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms. search.keywords: extension, migrate, data, QuickBooks, import
ms.date: 05/24/2017
ms.author: bholtorf
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: ff8f8f0c529966fc108d2d4c86e2d0681b1fc005
ms.contentlocale: fi-fi
ms.lasthandoff: 10/16/2017

---

# <a name="the-quickbooks-online-data-migration-extension-for-dynamics-nav"></a>Dynamics NAVin QuickBooks Online -tietojen siirtolaajennus
Tämä laajennus sisältää **tietojen siirron** asetusten ohjattuun määritykseen, joka auttaa siirtämään tärkeitä liiketoimintatietoja QuickBooks Onlinesta [!INCLUDE[d365fin](includes/d365fin_md.md)]iin. Tämä on kätevää esimerkiksi tilanteessa, jossa liiketoiminta kasvaa ja olet päättänyt päivittää liiketoiminnan hallintasovelluksen aloittamalla [!INCLUDE[d365fin](includes/d365fin_md.md)]in käytön.

## <a name="what-data-can-i-import-from-quickbooks-online"></a>QuickBooks Onlinesta siirrettävät tiedot
QuickBooks Onlinesta voi tuoda seuraavat tiedot [!INCLUDE[d365fin](includes/d365fin_md.md)]iin:  

* Asiakkaat
* Toimittajat
* Nimikkeet
* Tilikartta 
* Pääkirjanpidon alkusaldotapahtuma
* Varastonimikkeiden varastomäärä
* Asiakkaiden ja toimittajien avoimet asiakirjat, kuten laskut, hyvityslaskut ja maksut

Myynti- ja ostoasiakirjoissa vain täydet summat siirretään. Osittain maksettuja summia ei päivitetä. Jos asiakas on esimerkiksi maksanut myyntilaskun 500 dollarista 300, siirrettävä summa on kuitenkin 500. Jos olet vastaanottanut osittaisia maksuja, ne on päivitettävä manuaalisesti ennen tietojen siirtoa tai sen jälkeen. Avoimet tapahtumat on syytä kohdistaa ennen siirtoa, sillä se helpottaa toimintaa siirron jälkeen.

> [!NOTE]  
>   Osto- tai myyntitilauksia ei siirretä.

## <a name="before-you-start"></a>Ennen kuin aloitat
Siirtoprosessiin olennaisesti kuuluva osa on määrittää tilit, joihin tapahtumat siirretään. Nämä yhdistämismääritykset on hyvä suunnitella ennen tietojen siirtoa. Kyse on esimerkiksi tileistä, joille seuraavat tapahtumat kirjataan:  
  
* Nimikkeiden tai palvelujen myynti asiakkaille.
* Nimikkeiden tai palvelujen osto toimittajilta.  
* Pääkirjanpidon oikaisut.  

[!INCLUDE[d365fin](includes/d365fin_md.md)] edellyttää, että KP-tileille on määritetty tilinumerot. Varmista, että QuickBooks Online -tileille on määritetty tilinumerot.

QuickBooks Onlinen tapahtumissa on verosummia, [!INCLUDE[d365fin](includes/d365fin_md.md)]issa on määritettävä veroalueen verotili ennen tapahtumien kirjaamista.

## <a name="how-do-i-start-using-the-extension"></a>Laajennuksen käytön aloittaminen
Aloittaminen on helppoa. Sinun tarvitsee vain suorittaa **tietojen siirron** asetusten ohjattu määritys. Ohjeet:

1. Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, kirjoita **Asetusten ohjattu määritys** ja valitse **Siirrä liiketoimintatiedot**.
2. Noudata asetusten ohjatun määrityksen ohjeita.

## <a name="what-do-i-do-after-i-migrate-data"></a>Toimenpiteet tietojen siirtämisen jälkeen
Tietojen siirron jälkeen tapahtumien tila on **Kirjaamaton**, joten voit tarkastella niitä ja tehdä muutoksia. Voit tarkastella tapahtumia siirtymällä sivulle, jossa ne yleensä ovat. Voit tarkastella kirjaamattomia myyntilaskuja esimerkiksi siirtymällä **Myyntilaskut**-sivulle. Voit tarkastella maksupäiväkirjoja siirtymällä **Maksupäiväkirjat**-sivulle.   

Tietyt toimenpiteet kannattaa tehdä:

* Jos QuickBooks Onlinen tapahtumissa oli korotettuja ja alennettuja summia, nämä summat on lisättävä manuaalisesti liittyviin tapahtumiin [!INCLUDE[d365fin](includes/d365fin_md.md)]issa ennen niiden kirjaamista.
* Jos käytät arvolisäveroa (ALV:tä), liiketoiminnan kirjausryhmä ja tuotteen kirjausryhmä on ehkä lisättävä kirjausasetuksiin ALV-summien kirjaamista varten.
* Tarkista pääkirjanpidon tilien alkusaldot. QuickBooks Online ei tallenna kaikkien tilien ajankohtaisia saldoja, joten alkusaldoja on ehkä korjattava.

## <a name="see-also"></a>Katso myös
[Liiketoimintatietojen tuominen muista rahoitusjärjestelmistä](upload-data.md)  
[[!INCLUDE[d365fin](includes/d365fin_md.md)] -ohjelman mukauttaminen laajennusten avulla](ui-extensions.md)  

