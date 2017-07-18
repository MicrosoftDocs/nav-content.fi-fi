---
title: "Toimintaohje: Sekkien käsitteleminen"
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
ms.openlocfilehash: 421516a7580a90d6eabc8ecfcc841215839994c9
ms.contentlocale: fi-fi
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-work-with-checks"></a>Toimintaohje: Sekkien käsitteleminen
Dynamics NAV tukee sekkien sähköistä ja manuaalista myöntämistä. Molemmissa menetelmissä sekit myönnetään toimittajille maksupäiväkirjaa käyttäen. Ohjelman avulla voit myös mitätöidä sekkejä ja tarkastella sekkitapahtumia.

Sekkien myöntämiskäsittelyyn kuuluvat maksujen ehdottaminen, tapahtumien luominen ja tietokonesekkien tulostaminen.

Tulostin on määritettävä oikein sekkimuotoja varten. Myös käytettävä sekkien asettelu on määritettävä. Lisätietoja on kohdassa [Toimintaohje: Sekkien asetteluiden määrittäminen](finance-setup-how-define-check-layouts.md)

## <a name="to-issue-checks"></a>Sekkien myöntäminen
1. Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Maksupäiväkirjat** ja valitse sitten aiheeseen liittyvä linkki.
2. Täytä asianmukaisten maksujen tiedot päiväkirjaan esimerkiksi Ehdota toimittajamaksuja -toiminnon avulla. Lisätietoja on kohdassa [Toimintaohje: Toimittajamaksujen ehdottaminen](payables-how-suggest-vendor-payments.md).
3. Valitse sekkien avulla tehtävän maksun päiväkirjan rivillä **Pankkimaksun tyyppi** -kentässä jokin seuraavista vaihtoehdoista:

 - **Tietokonesekki**: Valitse tämä vaihtoehto, jos haluat tulostaa sekin maksupäiväkirjan tällä rivillä olevalle summalle. Tulosta sekit, ennen kuin kirjaat päiväkirjan rivit. Voit valita **Tietokonesekki**-kohdan vain, jos **Vastatilin tyyppi** tai **Tilin tyyppi** on **Pankkitili**.

 - **Manuaalinen sekki**: Valitse tämä vaihtoehto, jos olet luonut sekin manuaalisesti ja haluat luoda vastaavan sekkitapahtuman tälle summalle. Tämän vaihtoehdon avulla et voi tulostaa sekkejä Dynamics NAV -ohjelmasta. Voit valita **Manuaalinen sekki** -kohdan vain, jos **Vastatilin tyyppi** tai **Tilin tyyppi** on **Pankkitili**.

    **Huomautus**: Tulosta tietokonesekit, ennen kuin kirjaat liittyvät päiväkirjan rivit.
4. Jos kyseessä on tietokonesekki, valitse **Tulosta sekki**.
5. Täytä **Sekki**-ikkunassa tarvittavat kentät. Lue kentän lyhyt kuvaus valitsemalla kenttä tai siirry lisätietoihin valitsemalla linkki.
6. Valitse **Tulosta**-painike.

**Huomautus**: Jos haluat tulostaa sekkejä monessa valuutassa eri pankkitileiltä, sinun täytyy suorittaa **Tulosta sekki** -eräajo erikseen kullekin valuutalle ja määrittää sopivat pankkitilit.

## <a name="to-cancel-printed-checks-that-are-not-posted"></a>Kirjaamattomien ja tulostettujen sekkien peruuttaminen
Voit peruuttaa kirjaamattomat sekit niiden tulostamisen jälkeen **Maksupäiväkirja**-ikkunan **Mitätöi sekki** -toiminnon avulla.
1. Valitse **Maksupäiväkirja**-ikkunassa **Mitätöi sekki** ja valitse peruutettavat sekit.

## <a name="to-void-checks"></a>Sekkien mitätöiminen
Kun sekkimaksu on kirjattu, voit peruuttaa (mitätöidä) sekit vain tuloksena syntyvistä pankkitapahtumista.

1. Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Pankkitilit** ja valitse sitten aiheeseen liittyvä linkki.
2. Valitse oikea pankkitili, valitse **Muokkaa**-toiminto ja valitse sitten **Sekkitapahtumat**-toiminto.
3. Valitse **Sekkitapahtumat**-ikkunassa **Mitätöi sekki** -toiminto.
4. Valitse **Mitätöi vain sekki** -valintaruutu.
5. Valitse **OK**-painike.

## <a name="see-also"></a>Katso myös
[Ostovelkojen hallinta](payables-manage-payables.md)  
[Pankkitoiminnan määrittäminen](bank-setup-banking.md)  

