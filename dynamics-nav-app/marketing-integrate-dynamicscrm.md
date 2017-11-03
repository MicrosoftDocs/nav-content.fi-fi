---
title: Asiakkaiden hallinta Dynamics 365 for Sales -sovelluksessa
description: "Voit tehdä Dynamics NAV -ohjelmassa tietojen yhdistämismäärityksen Dynamics 365 for Salesilla, jolloin saavutetaan liidistä tuottoon -prosessin saumaton integrointi ja synkronointi."
documentationcenter: 
author: edupont04
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: integration, synchronize, map
ms.date: 06/06/2017
ms.author: edupont
ms.translationtype: HT
ms.sourcegitcommit: a16640e014e157d4dbcaabc53d0df2d3e063f8f9
ms.openlocfilehash: 3f26a80427a2a1c38949ca94848751527383d7f9
ms.contentlocale: fi-fi
ms.lasthandoff: 10/26/2017

---
# <a name="managing-customers-and-sales-created-in-dynamics-365-for-sales"></a>Dynamics 365 for Sales -sovelluksessa luotujen asiakkaiden ja myynnin hallinta
Jos käytät Dynamics 365 for Salesia asiakassuhteissa, voit käyttää [!INCLUDE[d365fin](includes/d365fin_md.md)]ia tilausten käsittelyyn ja talousasioissa. Tällä tavoin saavutetaan saumaton integrointi liidistä tuottoon.

Kun sovellus on määritetty integroitumaan Dynamics 365 for Salesiin, voit käyttää Sales-tietoja [!INCLUDE[d365fin](includes/d365fin_md.md)]ista ja toisin päin tietyissä tilanteissa. Tämän integroinnin ansiosta voit käsitellä ja synkronoida molemmille palveluille yhteisiä tietotyyppejä, kuten asiakkaita, kontakteja ja myyntitietoja, sekä pitää tiedot ajan tasalla molemmissa palveluissa.  

Esimerkiksi myyjä voi käyttää Dynamics 365 for Salesissa [!INCLUDE[d365fin](includes/d365fin_md.md)]in hinnastoja myyntitilausta luodessaan. Kun he lisäävät nimikkeen Dynamics 365 for Sales myyntitilausriville, he näkevät myös nimikkeen varastotason (saatavuuden) [!INCLUDE[d365fin](includes/d365fin_md.md)]ista.

Ja päinvastoin, [!INCLUDE[d365fin](includes/d365fin_md.md)] -sovelluksen tilausten käsittelijät voivat käsitellä Dynamics 365 for Sales -sovelluksesta automaattisesti tai manuaalisesti siirrettyjä myyntitilausten erityisominaisuuksia. Erityisominaisuudet voivat olla esimerkiksi sallittujen myyntitilausrivien automaattinen luominen ja kirjaaminen Sales-sovellukseen käsin lisättyinä tuotteina syötetyille nimikkeille tai resursseille. Lisätietoja on Erityisten myyntitilausten tietojen käsittelminen -osassa.  

> [!NOTE]
> Integrointi Dynamics 365 for Sales -sovelluksen kanssa edellyttää erilaisia teknisiä valmisteluita. Lisätietoja on MSDN-sivuston kohdissa [Toimintaohje: Dynamics CRM -yhteyden määrittäminen](https://msdn.microsoft.com/en-us/dynamics-nav/how-to-set-up-a-dynamics-crm-connection) ja [Toimintaohje: Dynamics CRM:n valmisteleminen integrointia varten](https://msdn.microsoft.com/en-us/dynamics-nav/how-to-prepare-dynamics-crm-for-integration).

## <a name="setting-up-the-connection"></a>Yhteyden määrittäminen
Voit käynnistää aloitussivulta asetusten ohjatun **Dynamics 365 for Sales -yhteyden määrittäminen** -määrittämisen, joka auttaa yhteyden määrittämisessä. Kun yhteys on muodostettu, Dynamics 365 for Salesin tietueet on yhdistetty saumattomasti [!INCLUDE[d365fin](includes/d365fin_md.md)]in tietueisiin.  

> [!NOTE]  
> Seuraavaksi käsitellään asetusten ohjattu määritys, mutta voit suorittaa samat tehtävät manuaalisesti **Dynamics 365 for Sales -yhteyden määrittäminen** -ikkunassa.

Voit valita avustetussa asennusoppaassa, mitkä tiedot synkronoidaan palvelujen välillä. Voit myös määrittää, että haluat tuoda nykyisen Dynamics 365 for Sales -ratkaisun. Siinä tapauksessa on määritettävä hallinnollinen käyttäjätili.

### <a name="setting-up-the-user-account-for-importing-the-solution"></a>Käyttäjätilin määrittäminen ratkaisun tuontia varten
Asennusopas tuo nykyisen Dynamics 365 for Sales -ratkaisun käyttämällä järjestelmänvalvojatiliä. Tämän tilin on oltava hyväksytty Dynamics 365 for Salesin käyttäjä, jolla on seuraavat käyttöoikeusroolit:

* järjestelmänvalvoja  
* ratkaisun mukauttaja.  

Lisätietoja on TechNetin artikkelissa [Käyttäjien luominen ja Microsoft Dynamics NAV (online) -käyttöoikeusroolien määrittäminen](https://technet.microsoft.com/library/jj191623.aspx) ja kohdassa [Toimintaohje: Käyttäjien ja käyttöoikeuksien hallinta](ui-how-users-permissions.md).  

Tätä tiliä käytetään vain asennuksen aikana. Kun ratkaisu on tuotu [!INCLUDE[d365fin](includes/d365fin_md.md)]iin, tiliä ei enää tarvita.

### <a name="setting-up-the-user-account-for-synchronization"></a>Synkronoinnin käyttäjätilin määrittäminen
Integraatiota varten tarvitaan jaettu käyttäjätili. Niinpä sinun on luotava Office 365 -tilauksessa erillinen käyttäjä, jota käytetään kahden palvelun välillä tapahtumaan synkronointiin. Tämän tilin on jo oltava hyväksytty Dynamics 365 for Salesin käyttäjä, mutta tilille ei tarvitse määrittää käyttöoikeusrooleja, koska asennusopas tekee sen puolestasi. Tämä käyttäjätili on määritettävä asennusoppaassa ainakin kerran sen perusteella, kuinka laajan synkronoinnin haluat ottaa käyttöön. Lisätietoja on TechNetin artikkelissa [Käyttäjien luominen ja Microsoft Dynamics NAV (online) -käyttöoikeusroolien määrittäminen](https://technet.microsoft.com/library/jj191623.aspx).

Jos otat käyttöön *tuotteen saatavuuden*, integrointiin käytettävällä käyttäjätilillä on oltava verkkopalvelun käyttöoikeusavain. Se on kaksivaiheinen toiminto kyseisen käyttäjätilin [!INCLUDE[d365fin](includes/d365fin_md.md)]-sivulla. Sinun on valittava **Muuta verkkopalvelun käyttöoikeusavainta** -painike ja määritettävä kyseinen käyttäjä OData-verkkopalvelun käyttäjäksi Dynamics 365 -yhteyden asennusoppaassa.

Jos otat käyttöön *myyntitilauksen integroinnin*, sinun on määritettävä tämän synkronoinnin käsittelevä käyttäjä. Se voi olla joko integrointikäyttäjä tai jokin muu käyttäjätili.

### <a name="coupling-records"></a>Tietueiden yhdistäminen
Voit valita avustetussa asennusoppaassa mitä kahden palvelun välillä synkronoidaan. Voit määrittää myöhemmin myös tietyn tyyppisten tietojen synkronoinnin. Tätä kutsutaan *yhdistämiseksi* ja tässä osassa kerrotaan, mitä seikkoja on kannattaa ottaa huomioon.

Jos haluat esimerkiksi Dynamics 365 for Salesin tilit [!INCLUDE[d365fin](includes/d365fin_md.md)]in asiakkaina, kaksi tietuetyyppiä on yhdistettävä. Se on aika yksinkertaista: avaa **Asiakasluettelo**-ikkuna [!INCLUDE[d365fin](includes/d365fin_md.md)]issa ja yhdistä nämä tiedot valintanauhan toiminnolla Dynamics 365 for Salesiin. Voit sitten määrittää, mitä Dynamics 365 for Salesin tilejä tietyt [!INCLUDE[d365fin](includes/d365fin_md.md)]in asiakkaat vastaavat.

Tietyillä alueilla toimintoa varten on ensin yhdistettävä tietyt tietojoukot ennen muita tietojoukkoja. Lisätietoja on seuraavassa luettelossa:

* Asiakkaat ja tilit  
  * Myyjät on yhdistettävä ensin Dynamics 365 for Salesin käyttäjien kanssa  
* Nimikkeet ja resurssit  
  * Mittayksiköt on yhdistettävä ensin Dynamics 365 for Salesin yksikköryhmien kanssa  
* Nimikkeiden ja resurssien hinnat  
  * Asiakkaan hintaryhmät on yhdistettävä ensin Dynamics 365 for Salesin hintoihin  

> [!NOTE]  
>   Jos hinnoissa käytetään ulkomaan valuuttaa, varmista, että valuutat yhdistetään Dynamics 365 for Salesin tapahtumavaluuttoihin.

Dynamics 365 for Salesin myyntitilaukset tarvitsevat lisätietoja, kuten asiakkaita, mittayksiköitä, valuuttoja, asiakkaan hintaryhmiä, nimikkeitä ja/tai resursseja. Dynamics 365 for Salesin myyntitilausten saumaton käyttö edellyttää, että asiakkaat, mittayksikkö, asiakkaan hintaryhmät, nimikkeet ja/tai resurssit yhdistetään ensin.

### <a name="synchronizing-records-fully"></a>Tietueiden täysi synkronointi
Valitse asetusten ohjatun määritysoppaan lopussa **Suorita täysi synkronointi** -toiminto. Tämä toiminto aloittaa kaikkien [!INCLUDE[d365fin](includes/d365fin_md.md)]in tietueiden synkronoinnin kaikkien liittyvien tietueiden synkronoinnin yhdistetyssä Dynamics 365 for Sales -ratkaisussa. Valitse **Täyden CRM-synkronoinnin tarkistus** -ikkunassa **Aloita**-toiminto. Synkronointi aloittaa sitten töiden suorittamisen riippuvuuksien mukaisesti. Esimerkiksi valuuttatietueet synkronoidaan ennen asiakastietueita. Täysi synkronointi voi kestää kauan, joten se tapahtuu taustalla, jotta voit jatkaa [!INCLUDE[d365fin](includes/d365fin_md.md)]in käyttöä.

Voit tarkistaa täyden synkronoinnin yksittäisten töiden etenemistä, porautua alaspäin **Työjonon tapahtuman tila**-, **Integrointitaulukkoon – projektin tila**- tai **Integrointitaulukosta – projektin tila** -kentissä **Täyden CRM-synkronoinnin tarkistus** -ikkunassa.

**Dynamics 365 -yhteyden määritys** -ikkunasta voi katsoa koska tahansa tietoja täydestä synkronoinnista. Voit avata sieltä myös **Integrointitaulukon yhdistämismääritykset** -ikkunan, jossa on tietoja synkronoitavista Dynamics NAV -ohjelman ja yhdistetyn Dynamics 365 for Sales -ratkaisun taulukoista.

## <a name="handling-special-sales-order-data"></a>Erityisen myyntitilauksen tietojen käsitteleminen
Dynamics 365 for Sales -sovelluksen myyntitilaukset siirretään automaattisesti [!INCLUDE[d365fin](includes/d365fin_md.md)] -sovellukseen, jos valitset **Luo myyntitilaukset automaattisesti** -valintaruudun **Microsoft Dynamics 365 for Sales -yhteyden määrittäminen** -ikkunassa. Näissä myyntitilauksissa alkuperäisen tilauksen **Nimi**-kenttä siirretään ja yhdisetään myyntitilauksen **Ulkoisen asiakirjan numero** -kenttään [!INCLUDE[d365fin](includes/d365fin_md.md)] -sovelluksessa.

Tämä voi toimia myös, jos alkuperäinen myyntitilaus sisältää käsin lisättyjä tuotteita eli nimikkeitä tai resursseja, joita ei ole rekisteröity kumpaankaan tuotteeseen. Tällöin tulee antaa **Käsin lisätyn tuotteen tyyppi**- ja **Käsin lisätyn tuotteen numero** -kentät **Myynnin ja myyntisaamisten asetukset** -ikkunassa. Tällöin ei-rekisteröity tuotemyynti yhdistetään talousanalyysissa tiettyyn nimike-/resurssinumeroon.

Jos alkuperäisen myyntitilauksen kuvaus on hyvin pitkä, sitä varten luodaan [!INCLUDE[d365fin](includes/d365fin_md.md)] -sovelluksen myyntitilaukseen lisämyyntitilausrivi, jonka tyyppi on Kommentti.

## <a name="see-also"></a>Katso myös
[Kontaktienhallinta](marketing-relationship-management.md)  
[[!INCLUDE[d365fin](includes/d365fin_md.md)] -ohjelman käyttäminen](ui-work-product.md)  
[[!INCLUDE[d365fin](includes/d365fin_md.md)] -sovelluksen mukauttaminen](ui-customizing-overview.md)  
[Toimintaohje: Käyttäjien ja käyttöoikeuksien hallinta](ui-how-users-permissions.md)    
[Organisaation ja käyttäjien perehdyttäminen Dynamics NAV (online) -ratkaisuun](https://www.microsoft.com/en-US/Dynamics/crm-customer-center/onboard-your-organization-and-users-to-dynamics-365-online.aspx)  

##

