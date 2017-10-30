---
title: "Kirjanpitäjän portaalin käyttäminen"
description: "Sisältää tietoja Kirjanpitäjän portaali -laajennuksesta."
author: edupont04
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms. search.keywords: app, add-in, manifest, customize, accountant
ms.date: 09/05/2017
ms.author: edupont
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 1515aac025f29a5b6e36d2caae362411a280a109
ms.contentlocale: fi-fi
ms.lasthandoff: 10/16/2017

---
# <a name="accountant-portal-for-dynamics-nav"></a><span data-ttu-id="00afc-103">Dynamics NAV -ohjelman kirjanpitäjän portaali</span><span class="sxs-lookup"><span data-stu-id="00afc-103">Accountant Portal for Dynamics NAV</span></span>
<span data-ttu-id="00afc-104">Tässä sovelluksessa on koontinäyttö, jossa on kirjanpitäjän jokaisen asiakasohjelman yhteenvetotiedot.</span><span class="sxs-lookup"><span data-stu-id="00afc-104">This application provides a dashboard with summary data for each client of an accountant.</span></span> <span data-ttu-id="00afc-105">Portaalissa on esillä taloushallinnon tunnuslukujen lisäksi myös suora linkki asiakasohjelman taloushallinnon sovellukseen.</span><span class="sxs-lookup"><span data-stu-id="00afc-105">The portal displays financial KPIs as well as a direct link to the client’s financial application.</span></span>  

<span data-ttu-id="00afc-106">Koontinäyttö on erikoistunut roolikeskus, jonka kautta saa hyvän kokonaiskuvan asiakasohjelmista.</span><span class="sxs-lookup"><span data-stu-id="00afc-106">The dashboard is a highly specialized Role Center for a better overview of your clients.</span></span>  
<span data-ttu-id="00afc-107">[![Kirjanpitäjän portaali](./media/ui-extensions-accportal/accountant-portal.png)](https://go.microsoft.com/fwlink/?linkid=851257)</span><span class="sxs-lookup"><span data-stu-id="00afc-107">[![Accountant Portal](./media/ui-extensions-accportal/accountant-portal.png)](https://go.microsoft.com/fwlink/?linkid=851257)</span></span>

<span data-ttu-id="00afc-108">Kun laajennus asennetaan ensimmäisen kerran, pääset alkuun malliyrityksen avulla.</span><span class="sxs-lookup"><span data-stu-id="00afc-108">When you first install the extension, a sample company helps you get started.</span></span> <span data-ttu-id="00afc-109">Voit poistaa malliyrityksen koska tahansa.</span><span class="sxs-lookup"><span data-stu-id="00afc-109">You can delete the sample company at any time.</span></span>  

## <a name="installing-the-extension"></a><span data-ttu-id="00afc-110">Laajennuksen asentaminen</span><span class="sxs-lookup"><span data-stu-id="00afc-110">Installing the Extension</span></span>
<span data-ttu-id="00afc-111">Kun olet asentanut laajennuksen [!INCLUDE[d365fin](includes/d365fin_md.md)]iin, sinulta kysytään, haluatko käyttää sitä heti.</span><span class="sxs-lookup"><span data-stu-id="00afc-111">When you install the extension in your [!INCLUDE[d365fin](includes/d365fin_md.md)], you will be asked if you want to use it now.</span></span> <span data-ttu-id="00afc-112">Jos haluat aloittaa käytön heti, sinun on kirjauduttava ensin ulos ja sitten takaisin sisään, koska laajennus korvaa nykyisen roolikeskuksen ja lisää käyttöoikeudet käyttäjäprofiiliisi.</span><span class="sxs-lookup"><span data-stu-id="00afc-112">If you do, then you must sign out and sign in again, because the extension replaces your current Role Center and adds permissions to your user profile.</span></span>  

<span data-ttu-id="00afc-113">Lisätietoja on kohdassa [Kirjanpitäjän käyttökokemukset Dynamics NAV -ohjelmassa](finance-accounting.md).</span><span class="sxs-lookup"><span data-stu-id="00afc-113">For more information, see [Accountant Experiences in Dynamics NAV](finance-accounting.md).</span></span>  

> [!NOTE]  
>  <span data-ttu-id="00afc-114">Laajennuksen nykyinen versio edellyttää, että asiakasohjelmassa on käytössä [!INCLUDE[d365fin](includes/d365fin_md.md)].</span><span class="sxs-lookup"><span data-stu-id="00afc-114">The current version of the extension requires that your clients use [!INCLUDE[d365fin](includes/d365fin_md.md)].</span></span>  

## <a name="using-the-extension"></a><span data-ttu-id="00afc-115">Laajennuksen käyttäminen</span><span class="sxs-lookup"><span data-stu-id="00afc-115">Using the extension</span></span>
<span data-ttu-id="00afc-116">Laajennusta käytetään, kun kirjaudut [Dynamics NAV for Accountants -sovellukseen sivustossa Microsoft.com](https://www.microsoft.com/en-us/dynamics365/financial-insights-for-accountants). Jos asennat laajennuksen [!INCLUDE[d365fin](includes/d365fin_md.md)] -sovellukseen, se korvaa nykyisen roolikeskuksesi.</span><span class="sxs-lookup"><span data-stu-id="00afc-116">This extension is used when you sign up at [Dynamics NAV for Accountants on Microsoft.com](https://www.microsoft.com/en-us/dynamics365/financial-insights-for-accountants). If you install the extension in your [!INCLUDE[d365fin](includes/d365fin_md.md)], it will replace your current Role Center.</span></span> <span data-ttu-id="00afc-117">Jos haluat sitten palata toiseen roolikeskukseen, voit tehdä sen omissa asetuksissa.</span><span class="sxs-lookup"><span data-stu-id="00afc-117">If you then want to return to the other Role Center, then you can do that in My Settings.</span></span> <span data-ttu-id="00afc-118">Lisätietoja on kohdassa [Toimintaohje: Roolikeskuksen vaihtaminen](change-role.md).</span><span class="sxs-lookup"><span data-stu-id="00afc-118">For more information, see [How to: Change the Role Center](change-role.md).</span></span>  

## <a name="see-also"></a><span data-ttu-id="00afc-119">Katso myös</span><span class="sxs-lookup"><span data-stu-id="00afc-119">See Also</span></span>
[<span data-ttu-id="00afc-120">Kirjanpitäjän käyttökokemukset Dynamics NAVissa</span><span class="sxs-lookup"><span data-stu-id="00afc-120">Accountant Experiences in Dynamics NAV</span></span>](finance-accounting.md)  
[<span data-ttu-id="00afc-121">Rahoitus</span><span class="sxs-lookup"><span data-stu-id="00afc-121">Finance</span></span>](finance.md)  

