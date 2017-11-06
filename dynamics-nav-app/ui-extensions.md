---
title: Dynamics NAV -ohjelman mukauttaminen laajennusten asentamisen avulla
description: "Lis�tietoja toimintojen lis��misest� ja Dynamics NAV -ohjelman mukauttamisesta laajennusten asentamisen avulla."
documentationcenter: 
author: edupont04
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: app, add-in, manifest, customize
ms.date: 07/07/2017
ms.author: edupont
ms.translationtype: HT
ms.sourcegitcommit: a16640e014e157d4dbcaabc53d0df2d3e063f8f9
ms.openlocfilehash: 109eb8d0e2a38566739878ef513ffa3bec8dcd30
ms.contentlocale: fi-fi
ms.lasthandoff: 10/26/2017

---
# <a name="customizing-dynamics-nav-using-extensions"></a>Dynamics NAV -sovelluksen mukauttaminen laajennusten avulla
Voit muuttaa [!INCLUDE[d365fin](includes/d365fin_md.md)]ia asentamalla laajennuksia, jotka sis�lt�v�t lis�toimintoja, muuttavat toimintaa tai mahdollistavat esimerkiksi uusien verkkopalveluiden k�ytt�misen.
Kun k�ynnist�t [!INCLUDE[d365fin](includes/d365fin_md.md)]in ensimm�isen kerran, joitakin laajennuksia on asennettu valmiiksi. Ajan kuluessa k�ytett�viss� on yh� enemm�n laajennuksia. Voit ottaa niit� k�ytt��n tarpeen mukaan.

Microsoft tarjoaa esimerkiksi laajennuksen, joka mahdollistaa integroinnin PayPal Payments Standard -ohjelman kanssa. T�m� laajennus asennetaan oletusarvoisesti.
Mutta jos k�ytett�viss� on toinen laajennus, joka avulla voi suorittaa integroinnin toiseen maksuj�rjestelm��n, voit asentaa uuden laajennuksen ja valita sen j�lkeen k�ytett�v�n palvelun n�ist� kahdesta.  

Laajennuksia hallitaan **Laajennusten hallinta** -ikkunassa. T�m� ikkuna l�ytyy kotisivulta. Voit my�s valita oikeassa yl�kulmassa **Etsi sivua tai raporttia** -kuvakkeen ![Etsi sivua tai raporttia](media/ui-search/search_small.png "Etsi sivua tai raporttia -kuvake"), kirjoittaa **Laajennus** ja valita sitten liittyv�n linkin.  

> [!NOTE]  
>   Jos sinulla on mielest�si laajennuksen k�ytt�oikeus muttet l�yd� sen toimintoja, tarkista **Laajennusten hallinta** -ikkuna. Jos laajennusta ei mainita ikkunassa, voit asentaa sen seuraavassa osassa kerrotulla tavalla.  

## <a name="installing-an-extension"></a>Laajennuksen asentaminen
Saat uusia laajennuksia kaupasta osoitteessa [AppSource.microsoft.com](https://appsource.microsoft.com/en-us/marketplace/apps?product=dynamics-365%3Bdynamics-365-for-financials&page=1). N�ht�viss� on kaikki saatavilla olevat [!INCLUDE[d365fin](includes/d365fin_md.md)]in laajennukset. Saat sovelluksia, laajennuksia ja sis�lt�paketteja my�s muihin Microsoftin tuotteisiin. M��rit� soveltuvat suodattimet, tutustu kunkin laajennuksen tietoihin ja hae laajennus [!INCLUDE[d365fin](includes/d365fin_md.md)]iin.  
> [!NOTE]  
>   Kirjaudu sivustoon [AppSource.microsoft.com](https://appsource.microsoft.com/) [!INCLUDE[d365fin](includes/d365fin_md.md)]issa k�ytt�m�si s�hk�postitilin tiedoilla. Saman s�hk�postitilin k�ytt�minen my�s muissa palveluissa ja tuotteissa takaa sujuvan k�ytt�kokemuksen.  

Kauppaan p��see my�s suoraan [!INCLUDE[d365fin](includes/d365fin_md.md)]ista. T�ll� hetkell� asennettuna olevat laajennukset n�kyv�t **Laajennusten hallinta** -ikkunassa. Voit avata **Laajennuskauppa**-sivun, jolla n�kyv�t AppSource-sivustossa t�ll� hetkell� k�ytett�viss� olevat [!INCLUDE[d365fin](includes/d365fin_md.md)]in laajennukset. Jos valitset *Lis�� sovelluksia* -linkin, sinut siirret��n osoitteeseen [AppSource.microsoft.com](https://appsource.microsoft.com/en-us/marketplace/apps?product=dynamics-365%3Bdynamics-365-for-financials&page=1).  

Kun valitset laajennuksen, voit lukea tietoja laajennuksesta ja hakea lis�tietoja k�ytt�m�ll� laajennuksen Ohje-toimintoa. Kun haluat noutaa laajennuksen, sinun on hyv�ksytt�v� k�ytt�ehdot. Jos noudat laajennuksen AppSource-sivustosta, sinut kirjataan sis��n [!INCLUDE[d365fin](includes/d365fin_md.md)]iin asennuksen viimeistelemiseksi.  

Laajennus on ehk� m��ritett�v� asennuksen yhteydess�. Se tarkoittaa esimerkiksi **[!INCLUDE[d365fin](includes/d365fin_md.md)]in PayPal Payments Standard** -laajennuksen k�ytt�misess� tarvittavan tilin m��ritt�mist�.
Muissa laajennuksissa esimerkiksi yksinkertaisesti lis�t��n kentti� olemassa olevalle sivulle tai lis�t��n uusi sivu.   

Jos poistat laajennuksen asennuksen ja haluat ottaa sen takaisin k�ytt��n, voit asentaa laajennuksen uudelleen. Kun poistat k�yt�ss�si olleen laajennuksen asennuksen, tiedot s�ilytet��n. Jos siis asennat laajennuksen uudelleen, tiedot ovat yh� k�ytett�viss�si.  

Jotkin ovat Microsoftin laajennuksia, jotkin [muiden yritysten](ui-extensions-other.md). Kaikki laajennukset testataan, ennen kuin ne ovat k�ytt�jien k�ytett�viss�. Suosittelemme kuitenkin lis�tietoihin tutustumista laajennuksen mukana saatavien linkkien avulla ennen laajennuksen asentamista.  

Microsoft tarjoaa seuraavat laajennukset:  

* [Dynamics GP -tietojen siirto](ui-extensions-dynamicsgp-data-migration.md)  
* [PayPal Payments Standard](ui-extensions-paypal-payments-standard.md)  
* [QuickBooks-tietojen siirto](ui-extensions-quickbooks-data-migration.md)  
* [Myynti- ja varastoennuste](ui-extensions-sales-forecast.md)  
* [Ceridian Payroll](ui-extensions-ceridian-payroll.md)  
* [Quickbooks Payroll -tiedostojen tuonti](ui-extensions-quickbooks-payroll.md)  
* [WorldPay Payments Standard](ui-extensions-worldpay-payments-standard.md)
* [Ison-Britannian postinumeroiden GetAddress.io](ui-extensions-getaddressio.md)
* [QuickBooks Online -tietojen siirto](ui-extensions-quickbooks-online-data-migration.md)
* [Kirjanpit�j�n portaali](ui-extensions-accountant-portal.md)  
* [Kuvan analysointitoiminto](ui-extensions-image-analyzer.md)

> [!NOTE]  
>  Uudet laajennukset eiv�t ole saatavana AppSourcessa heti, kun ilmoitamme p�ivityksest�. Voit tarkkailla laajennuksia osoitteessa [AppSource.microsoft.com](https://appsource.microsoft.com/en-us/marketplace/apps?product=dynamics-365%3Bdynamics-365-for-financials&page=1).

## <a name="see-also"></a>Katso my�s
[Toimintaohje: Asiakkaan maksujen ottaminen k�ytt��n PayPalin kautta](sales-how-enable-payment-service-extensions.md)  
[Liiketoiminnan tietojen siirt�minen muista rahoitusj�rjestelmist�](upload-data.md)    
[Muiden palveluntarjoajien [!INCLUDE[d365fin](includes/d365fin_md.md)]in laajennukset](ui-extensions-other.md)  
[Tervetuloa [!INCLUDE[d365fin_long](includes/d365fin_long_md.md)]iin!](index.md)  

##


