---
title: Raporttien tallennetut asetukset
author: jswymer
ms.custom: na
ms.date: 09/26/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 0f11d862315c8ecd160cd18afb0a72a2d684b9b2
ms.contentlocale: fi-fi
ms.lasthandoff: 06/26/2017

---
# <a name="saved-settings-on-reports"></a>Raporttien tallennetut asetukset
Ajetusta raportista riippuen näkyviin voi tulla sivu, jolla voi määrittää tietyt luodun raportin tietojen muuttamisessa tarvittavat asetukset ja suodattimet. Sivua kutsutaan raporttipyyntösivuksi. Raportti voi sisältää vähintään yhdet *tallennetut asetukset*, joita voidaan käyttää pyyntösivun raportissa. *Tallennetut asetukset* ovat periaatteessa ennalta määritettyjä asetuksia ja suodattimia. Tallennettujen asetusten käyttäminen on nopea ja helppo tapa oikeiden tietojen sisältämien raporttien luomista varten.

Voit tarkastella raportin käytettävissä olevia tallennettuja asetuksia raporttipyyntösivun **Tallennetut asetukset** -osassa.

## <a name="to-apply-saved-settings-to-a-report"></a>Tallennettujen asetusten käyttäminen raportissa
1.  Avaa raportti.

    Näkyviin tulee raporttipyyntösivu.    
2.  Määritä sivun **Tallennetut asetukset** -osan **Nimi**-kenttään ne tallennetut asetukset, joita haluat käyttää.

    **Tallennetut asetukset** -osa näkyy vain, jos raportti on suoritettu aiemmin tai jos asetukset on tallennettu aiemmin. **Viimeksi käytetyt asetukset ja suodattimet** -kirjaus on aina saatavilla. Nämä asetukset ovat valinnan ja suodattimen arvot, joita käytettiin viimeksi raportin ajon yhteydessä.

## <a name="administer-saved-report-settings-for-users"></a>Käyttäjille tallennettujen raporttiasetusten hallinta
Jos sinulla on tarvittavat oikeudet, voit tarkastella, luoda ja muokata yrityksen kaikkien käyttäjien raporttien tallennettuja asetuksia. Voit määrittää raportin tallennetut asetukset yksittäisille käyttäjille tai yrityksen kaikille käyttäjille.

Voit hallita tallennettuja asetuksia sivun 1506 **Raporttien asetukset** -kohdassa. Avaa tämä sivu valitsemalla oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syöttämällä **Raporttivalinnat** ja valitsemalla sitten aiheeseen liittyvä linkki. 

**Raporttiasetukset**-sivulla voit luoda uudet asetukset alusta alkaen tai kopioida aiemmin määritetyt asetukset ja muokata niitä. Voit muokata asetusten valintoja ja suodattimia valitsemalla **Muokkaa**-toiminnon.

**Muistiot**:
-    Raporttien tallennettujen asetusten ominaisuus on käytettävissä vain, kun pyyntösivun SaveValues-ominaisuuden arvoksi on määritetty Kyllä. SaveValues-ominaisuuden ominaisuus määritetään kehitysympäristössä.
-    Jos luot tallennetut asetukset kaikille käyttäjille, ja niillä on sama nimi kuin tietyn käyttäjän aiemmin tallennetuilla asetuksilla, käyttäjä ei voi käyttää kaikille tarkoitettua asetusjoukkoa.  Käyttäjä näkee raportin pyyntösivun Tallennetut asetukset -kentässä kaksi tallennettujen asetusten vaihtoehtoa, joilla on sama nimi. Valitusta vaihtoehdosta riippumatta järjestelmä käyttää käyttäjän omia asetuksia.

## <a name="see-also"></a>Katso myös
[Suoritettavan raportin aikatauluttaminen](ui-schedule-report.md)

