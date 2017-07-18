---
title: 'Toimintaohje: Projektin edistymisen ja suorituskyvyn valvonta'
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
ms.openlocfilehash: 05b990dd93ddff12581efdc2918ada69681482a1
ms.contentlocale: fi-fi
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-monitor-job-progress-and-performance"></a>Toimintaohje: Projektin edistymisen ja suorituskyvyn valvonta
Projektin edetessä kulutetaan materiaaleja, resursseja ja muita kuluja, ja nämä on kirjattava projektiin. Keskeneräinen työ (KET) on ominaisuus, jonka avulla voit arvioida kirjanpidossa olevien projektien taloudellisen arvon projektin ollessa meneillään. Monissa tapauksissa saatat kirjata projektille kuluja ennen projektin laskuttamista. Kun projektista on kirjattu vain kuluja, rahoituslaskelma on epätarkka. Lisätietoja on kohdassa [Tietoja KET-menetelmistä](projects-understanding-wip.md).

Voit seurata arvoa kirjanpidossa laskemalla KET:n ja kirjaamalla arvon kirjanpitoon.

Voit laskea KET:n seuraavien arvojen perusteella:

- kustannusarvo
- myyntiarvo
- tuloutettavat kustannukset
- valmistumisen prosenttiosuus
- valmis sopimus.

Jos haluat tarkastella tulosta jollakin muulla menetelmällä, voit vaihtaa menetelmää ja laskea KET:n uudelleen. KET:n laskentakertojen määrää ei ole rajoitettu. Ohjelma laskee KET:n mutta ei kirjaa sitä kirjanpitoon. Kun olet laskenut KET:n, voit kirjata sen kirjanpitoon.

## <a name="to-create-a-job-wip-method"></a>Projektin KET-menetelmän luominen  
Voit luoda projektin KET-menetelmän, joka kuvastaa organisaatiosi tarpeita. Luonnin jälkeen voit määrittää sen projektin oletusarvoiseksi KET-laskentamenetelmäksi, jota käytetään organisaatiossa.  

**Huomautus**. Kun olet käyttänyt uutta tapaasi luodaksesi KET-tapahtumat, et voi enää poistaa tai muokata tapaa.  

1. Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Projektin KET-menetelmät** ja valitse sitten aiheeseen liittyvä linkki.  
2. Valitse **Uusi**-toiminto ja täytä tarvittavat kentät. Lue kentän lyhyt kuvaus valitsemalla kenttä tai siirry lisätietoihin valitsemalla linkki.  
3. Sulje ikkuna.   
4. Määritä tämä uusi menetelmä oletusarvoksi valitsemalla oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syöttämällä **Projektienhallinnan asetukset** ja valitsemalla sitten aiheeseen liittyvä linkki.  
5. Valitse **Oletus KET-menetelmä** -kentässä menetelmä luettelosta.

## <a name="to-define-a-wip-method-for-a-job"></a>Määritä projektin KET-menetelmä  
Kun luot uuden projektin, määritä, mihin projektin KET-menetelmään se kohdistetaan. Joissakin tapauksissa käytettävissä oleva projektin KET-menetelmä on määritetty oletusasetukseksi.

1. Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Projektit** ja valitse sitten aiheeseen liittyvä linkki.
2. Valitse **Uusi**-toiminto. Lisätietoja on kohdassa [Toimintaohje: Projektien luominen](projects-how-create-jobs.md).  
3. Valitse **Projektikortti**-ikkunan **KET-menetelmä**-kentässä KET-menetelmä luettelosta. Vaikka oletusmenetelmä olisi määritetty, voit valita tarvittaessa toisen vaihtoehdon.  

## <a name="to-calculate-wip"></a>Keskeneräisen työn laskeminen  
Voit määrittää tasetileille kirjattavan KET-summan kauden lopussa suoritettavaa raportointia varten. Tähän käytetään **Laske projektin KET** -erätyötä.  

1. Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Laske projektin KET** ja valitse sitten aiheeseen liittyvä linkki.  
2. Valitse **Laske KET** -toiminto.
3. Täytä **Laske projektin KET** -ikkunassa tarvittavat kentät.
4. Valitse **OK**-painike.  

**Huomautus**: Eräajo laskee ainoastaan keskeneräisen työn. Sitä ei kirjata pääkirjanpitoon. Nämä toimet edellyttävät, että suoritat **Kirjaa KET kirjanpitoon** -eräajon, kun olet laskenut keskeneräisen työn. Katso lisätietoja seuraavasta menettelystä.

## <a name="to-post-wip"></a>Keskeneräisen työn kirjaaminen  
Kun keskeneräinen työ on laskettu, voit kirjata sen tasetileille jakson lopun raportointia varten. Tähän käytetään **Kirjaa projektin KET kirjanpitoon** -erätyötä.

1. Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Kirjaa projektin KET kirjanpitoon** ja valitse sitten aiheeseen liittyvä linkki.  
2. Täytä **Kirjaa projektin KET kirjanpitoon** -ikkunassa tarvittavat kentät.  
3. Valitse **OK**-painike.

## <a name="to-view-job-usage-estimates-and-post-updates"></a>Projektin käytön arvioiden tarkasteleminen ja päivitysten kirjaaminen  
Voit katsella projektin käyttöä projektin valmistumiseen asti yhden vaiheen avulla. Tämä tapahtuu käyttämällä **Laske projektin jäljellä oleva käyttö** -eräajoa kaikissa tehtävissä projektin alusta loppuun.  

Näin voit seurata ja vertailla alkuperäisiä arvioita todellisiin tuloksiin. Voit myös tehdä tarvittaessa muutoksia tai uusia tapahtumia. Olet esimerkiksi saattanut arvioida projektin kestoksi 10 tuntia, mutta aikaa on kulunut jo 15 tuntia. Voit lisätä viisi tuntia aiemmin luotuun päiväkirjariviin tai luoda uuden rivin, jolla nämä viisi tuntia raportoidaan ylityönä, joka on toinen työtyyppi. Sitten lasketaan oikeat kustannukset ja hinta, jotka voidaan kirjata päiväkirjaan.  

**Huomautus**: Nimiketapahtumat luovat nimiketapahtumia ja vähentävät varastomäärää. **Kirjaa varaston kustannus KP:oon** -eräajo siirtää kustannuksen varastosta pääkirjanpitoon. Resurssitapahtumat luovat resurssitapahtumia.  

1. Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Projektipäiväkirjat** ja valitse sitten aiheeseen liittyvä linkki.  
2. Valitse asianmukaisen projektin päiväkirja ja valitse sitten **Laske jäljellä oleva käyttö** -toiminto.  
3. Syötä **Laske projektin jäljellä oleva käyttö** -ikkunassa päiväkirjaan lisättävä asiakirjan numero ja kirjauspäivämäärä. Valitse sitten **OK**-painike.  
4. Päivitä tarvittavat muutokset päiväkirjaan.  
5. Valitse **Kirjaa**.

## <a name="to-view-job-ledger-entries"></a>Projektitapahtumien katsominen
Kaikki projekteihin liittyvät tapahtumat on tallennettu projektirekistereihin ja numeroitu järjestyksessä numerosta 1 alkaen. Projektirekisterissä voi saada yleiskuvan kaikista projektitapahtumista.    

1. Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Projektirekisterit** ja valitse sitten aiheeseen liittyvä linkki.
2. Valitse asianmukainen rekisteri ja valitse sitten **Projektikirjaukset**-toiminto.

**Projektitapahtumat**-ikkunassa voit tarkastella mihin tahansa projektiin liittyviä tapahtumia.  

## <a name="see-also"></a>Katso myös
[Projektien hallinta](projects-manage-projects.md)  
[Rahoitus](finance-setup.md)  
[Ostojen hallinta](purchasing-manage-purchasing.md)         
[Myynnin hallinta](sales-manage-sales.md)      
[Dynamics NAV -ohjelman käyttäminen](ui-work-product.md)  

