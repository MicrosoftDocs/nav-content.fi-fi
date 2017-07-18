---
title: "Kuinka maksut viedään pankkitiedostoon"
author: SorenGP
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 09bdf56b3d5e76b12d868091e89232ce9c08e215
ms.contentlocale: fi-fi
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-export-payments-to-a-bank-file"></a>Kuinka maksut viedään pankkitiedostoon
Kun olet valmis suorittamaan maksut toimittajille **Maksupäiväkirja**-ikkunassa, voit viedä tiedoston maksutietojen kanssa päiväkirjan riveille. Voit sitten ladata tiedoston verkkopankkiin käsitelläksesi siihen liittyvät rahansiirrot.

Dynamics NAV -ohjelman yleisessä versiossa asetetaan ja yhdistetään yleiset palvelut pankkitietojen muuntamiseen mihin tahansa pankkisi vaatimaan muotoon.

**Huomautus**: Ennen kuin voit viedä maksukirjauskansion, sinun tulee asettaa vienti käyttöön liittyvässä päiväkirjan erässä. Lisäksi elektroniseen maksuun on määritettävä sinun ja toimittajan pankkitilit. Lisätietoja on kohdassa [Toimintaohje: Pankkitietojen muuntopalvelun määrittäminen](bank-how-setup-bank-data-conversion-service.md).

Voit tarkastella maksupäiväkirjasta vietyjä maksutiedostoja **Hyvityksen siirron rekisterit** -ikkunassa. Ikkunassa voit myös viedä maksutiedostot uudelleen, jos tekniset virheet tai tiedostomuutokset vaativat sitä.

## <a name="to-export-payments-to-a-bank-file"></a>Maksujen vienti pankkitiedostoon
1. Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Maksupäiväkirjat** ja valitse sitten aiheeseen liittyvä linkki.
2. Voit esimerkiksi täyttää päiväkirjan rivit **Ehdota toimittajamaksuja** -toiminnolla. Lisätietoja on kohdassa [Toimintaohje: Toimittajamaksujen ehdottaminen](payables-how-suggest-vendor-payments.md).  
3. Kun kaikki maksupäiväkirjan rivit ovat valmiit, valitse **Vie maksu tiedostoon**.

    Virheilmoituksia näkyy **maksutiedoston virheet** -tietoruudussa, jossa voit myös nähdä yksityiskohtaiset tiedot virheviestistä. Kaikki virheet on ratkaistava ennen maksutiedoston vientiä.

    **Vihje**: Pankkitietojen muuntopalvelua käytettäessä yleinen virheilmoitus kertoo, että pankkitilin numeron pituus ei ole pankin edellyttämä. Välttääksesi tai ratkaistaksesi tämän ongelman, sinun on poistettava arvo **IBAN**-kentästä **Pankkitilin kortti** -ikkunassa ja syötettävä sitten **Pankkitilin nro** -kenttään pankkitilin numero pankin vaatimassa muodossa.
4. Määritä **Tallenna nimellä** -ikkunassa paikka, johon tiedosto viedään ja valitse sitten **Tallenna**.

Pankin maksutiedosto viedään määrittämääsi sijaintiin ja voit jatkaa sen lataamista verkkopankkitilille ja suorittaa todelliset maksut.

Kun olet vastaanottanut vahvistuksen siitä, että verkkopankki on käsitellyt maksut onnistuneesti, voit kirjata viedyt maksupäiväkirjan rivit.

## <a name="to-plan-when-to-post-exported-payments"></a>Vietyjen maksujen kirjaamisajankohdan suunnitteleminen
Jos et halua kirjata viedyn maksun maksupäiväkirjan riviä, koska esimerkiksi odotat pankin vahvistusta tapahtuman käsittelystä, voit poistaa päiväkirjan rivin. Kun luot myöhemmin maksupäiväkirjan rivin, jolla maksetaan jäljellä oleva laskun summa, **Viety summa yhteensä** -kenttä näyttää, kuinka paljon maksun summasta on jo viety. Lisäksi saat lisätietoja viedystä kokonaissummasta valitsemalla **Hyvityksen siirron rekisterimerkinnät** -painikkeen, joka avaa vietyjen maksutiedostojen tiedot.

Jos noudatat prosessia, jossa maksut kirjataan vasta sen jälkeen, kun pankin suorittamasta maksujen käsittelystä on saatu vahvistus, voit hallita tätä kahdella eri tavalla.

* Maksupäiväkirjan ehdotettujen maksurivien kohdalla voit lajitella joko **Viety maksutiedostoon** -sarakkeen tai **Viety summa yhteensä**-kentän mukaan ja sitten poistaa maksuehdotukset avoimilta laskuilta, jotka on jo maksettu ja joita et halua maksaa.
* **Ehdota toimittajamaksuja** -ikkunassa, jossa määrität maksupäiväkirjaan lisättävät maksut, voit valita **Ohita viedyt maksut** -valintaruudun, jos et halua lisätä päiväkirjarivejä jo viedyille maksuille.

Saat lisätietoja viedyistä maksuista valitsemalla **Maksujen vientihistoria** -toiminnon.

## <a name="to-re-export-payments-to-a-bank-file"></a>Maksujen vieminen uudelleen pankkitiedostoon
Voit viedä maksutiedostot uudelleen **Hyvityksen siirron rekisterit** -ikkunasta. Ennen kuin poistat tai kirjaat maksupäiväkirjan rivejä, voit myös viedä maksutiedoston uudelleen **Maksupäiväkirja**-ikkunasta yksinkertaisesti viemällä uudelleen.

Jos olet poistanut tai kirjannut maksupäiväkirjan rivit viennin jälkeen, voit viedä saman maksutiedoston uudelleen **Hyvityksen siirron rekisterit** -ikkunasta. Valitse rivi tilisiirtojen erälle, jonka haluat viedä uudelleen, ja käyttämällä sitten **Vie maksut uudelleen tiedostoon** -toimintoa.

## <a name="see-also"></a>Katso myös
[Ostovelat](payables-manage-payables.md)  
[Ostojen hallinta](purchasing-manage-purchasing.md)  
[Oston määrittäminen](purchasing-setup-purchasing.md)

