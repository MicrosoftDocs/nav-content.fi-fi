---
title: Dynamics NAV -ohjelman mukauttaminen laajennusten avulla
author: edupont04
ms.custom: na
ms.date: 09/23/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 6b60b1344a1e18ad91863046110df880f75f7c04
ms.openlocfilehash: cc832772a255c7c801a7b956c74da827caca3765
ms.contentlocale: fi-fi
ms.lasthandoff: 07/19/2017

---

# <a name="customizing-dynamics-nav-using-extensions"></a><span data-ttu-id="ed01d-102">Dynamics NAV -ohjelman mukauttaminen laajennusten avulla</span><span class="sxs-lookup"><span data-stu-id="ed01d-102">Customizing Dynamics NAV Using Extensions</span></span>
<span data-ttu-id="ed01d-103">Voit muuttaa Dynamics NAV -ohjelmaa asentamalla laajennuksia, jotka sisältävät lisätoimintoja, muuttavat toimintaa tai mahdollistavat esimerkiksi uusien verkkopalveluiden käyttämisen.</span><span class="sxs-lookup"><span data-stu-id="ed01d-103">You can change Dynamics NAV by installing extensions that add functionality, change behavior, or give you access to new online services, for example.</span></span>
<span data-ttu-id="ed01d-104">Kun käynnistät Dynamics NAV -ohjelman ensimmäisen kerran, ohjelma sisältää jo joitakin laajennuksia.</span><span class="sxs-lookup"><span data-stu-id="ed01d-104">When you first launch Dynamics NAV, some extensions are already installed for you.</span></span> <span data-ttu-id="ed01d-105">Ajan kuluessa käytettävissä voi olla yhä enemmän laajennuksia. Voit ottaa niitä käyttöön tarpeen mukaan.</span><span class="sxs-lookup"><span data-stu-id="ed01d-105">Over time, more extensions can be made available to you, and you can then choose if you want to use the extension or not.</span></span>

<span data-ttu-id="ed01d-106">Microsoft tarjoaa esimerkiksi laajennuksen, joka mahdollistaa integroinnin PayPal Payments Standard -ohjelman kanssa.</span><span class="sxs-lookup"><span data-stu-id="ed01d-106">For example, Microsoft provides an extension that provides integration with PayPal Payments Standard.</span></span> <span data-ttu-id="ed01d-107">Tämä laajennus asennetaan oletusarvoisesti.</span><span class="sxs-lookup"><span data-stu-id="ed01d-107">This extension is installed by default.</span></span>
<span data-ttu-id="ed01d-108">Mutta jos käytettävissä on toinen laajennus, joka avulla voi suorittaa integroinnin toiseen maksujärjestelmään, voit asentaa uuden laajennuksen ja valita sen jälkeen käytettävän palvelun näistä kahdesta.</span><span class="sxs-lookup"><span data-stu-id="ed01d-108">But if another extension is made available that offers integration with another payment service, you can install the new extension and then choose which of the two services to use.</span></span>  

<span data-ttu-id="ed01d-109">Laajennuksia hallitaan **Laajennusten hallinta** -ikkunassa.</span><span class="sxs-lookup"><span data-stu-id="ed01d-109">You manage the extensions in the **Extension Management** window.</span></span> <span data-ttu-id="ed01d-110">Tämä ikkuna löytyy kotisivulta.</span><span class="sxs-lookup"><span data-stu-id="ed01d-110">You can access this window from Home.</span></span> <span data-ttu-id="ed01d-111">Vaihtoehtoisesti voit valita oikeassa yläkulmassa olevan **Etsi sivu tai raportti** -kuvakkeen, syöttää **Laajennus** ja valita sitten aiheeseen liittyvän linkin.</span><span class="sxs-lookup"><span data-stu-id="ed01d-111">Alternatively, choose the **Search for Page or Report** icon in the top right corner, enter **Extension**, and then choose the related link.</span></span>   

## <a name="installing-an-extension"></a><span data-ttu-id="ed01d-112">Laajennuksen asentaminen</span><span class="sxs-lookup"><span data-stu-id="ed01d-112">Installing an Extension</span></span>
<span data-ttu-id="ed01d-113">Jos käytettävissäsi on palvelimelle julkaistuja laajennuksia, ne näkyvät **Laajennusten hallinta** -ikkunassa.</span><span class="sxs-lookup"><span data-stu-id="ed01d-113">If new extensions are made available to you because they have been published to your server, they will be shown in the **Extension Management** window.</span></span> <span data-ttu-id="ed01d-114">Siellä voit valita laajennukset, jotka haluat asentaa ja joiden asennukset haluat poistaa.</span><span class="sxs-lookup"><span data-stu-id="ed01d-114">From here, you can choose to install and uninstall extensions.</span></span>  

<span data-ttu-id="ed01d-115">Kun valitset laajennuksen, voit lukea tietoja laajennuksesta ja hakea lisätietoja käyttämällä laajennuksen Ohje-toimintoa.</span><span class="sxs-lookup"><span data-stu-id="ed01d-115">If you choose an extension, you can read about what the extension does, and you can access Help for the extension to learn more.</span></span> <span data-ttu-id="ed01d-116">Kun haluat noutaa laajennuksen, sinun on hyväksyttävä käyttöehdot.</span><span class="sxs-lookup"><span data-stu-id="ed01d-116">When you choose to get an extension, you must agree to the terms of use.</span></span>  

<span data-ttu-id="ed01d-117">Laajennus on ehkä määritettävä asennuksen yhteydessä. Se tarkoittaa esimerkiksi **PayPal Payments Standard for Dynamics NAV** -laajennuksen käyttämisessä tarvittavan tilin määrittämistä.</span><span class="sxs-lookup"><span data-stu-id="ed01d-117">When you install an extension, you might have to set it up, such as specifying an account for use with the **PayPal Payments Standard for Dynamics NAV** extension.</span></span>
<span data-ttu-id="ed01d-118">Muissa laajennuksissa esimerkiksi yksinkertaisesti lisätään kenttiä olemassa olevalle sivulle tai lisätään uusi sivu.</span><span class="sxs-lookup"><span data-stu-id="ed01d-118">Other extensions simply add fields to an existing page, or they add a new page, for example.</span></span>   

<span data-ttu-id="ed01d-119">Jos poistat laajennuksen asennuksen ja haluat ottaa sen takaisin käyttöön, voit asentaa laajennuksen uudelleen.</span><span class="sxs-lookup"><span data-stu-id="ed01d-119">If you uninstall an extension, and you then change your mind, you can install it again.</span></span> <span data-ttu-id="ed01d-120">Kun poistat käytössäsi olleen laajennuksen asennuksen, tiedot säilytetään. Jos siis asennat laajennuksen uudelleen, tiedot ovat yhä käytettävissäsi.</span><span class="sxs-lookup"><span data-stu-id="ed01d-120">When you uninstall an extension that you have been using, the data is preserved so that if you install the extension again, your data is still available.</span></span>  

<span data-ttu-id="ed01d-121">Microsoft tarjoaa seuraavat laajennukset:</span><span class="sxs-lookup"><span data-stu-id="ed01d-121">Microsoft provides the following extensions:</span></span>  
- [<span data-ttu-id="ed01d-122">PayPal Payments Standard</span><span class="sxs-lookup"><span data-stu-id="ed01d-122">PayPal Payments Standard</span></span>](ui-extensions-paypal-payments-standard.md)  
- [<span data-ttu-id="ed01d-123">Myynnin ja varaston ennuste</span><span class="sxs-lookup"><span data-stu-id="ed01d-123">Sales and Inventory Forecast</span></span>](ui-extensions-sales-forecast.md)  

<span data-ttu-id="ed01d-124">Myös muita laajennuksia on oletusarvoisesti käytettävissä maasta/alueesta riippuen.</span><span class="sxs-lookup"><span data-stu-id="ed01d-124">Other extensions are also available by default, depending on your country/region.</span></span>

## <a name="see-also"></a><span data-ttu-id="ed01d-125">Katso myös</span><span class="sxs-lookup"><span data-stu-id="ed01d-125">See Also</span></span>  
[<span data-ttu-id="ed01d-126">Toimintaohje: Asiakkaan maksujen ottaminen käyttöön PayPalin kautta</span><span class="sxs-lookup"><span data-stu-id="ed01d-126">How to: Enable Customer Payment Through PayPal</span></span>](sales-how-enable-customer-payments-paypal.md)  
[<span data-ttu-id="ed01d-127">Tervetuloa Dynamics NAV -ohjelmaan</span><span class="sxs-lookup"><span data-stu-id="ed01d-127">Welcome to Dynamics NAV</span></span>](across-get-started.md)  
