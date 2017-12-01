---
title: "Dynamics NAV -ohjelman hallintatehtävät"
description: "Joitakin [!INCLUDE[d365fin](includes/d365fin_md.md)]in tehtäviä on hallittava ja ne on määritettävä keskitetysti. Katso lisätietoja näistä tehtävistä ja niiden määrittämisestä."
author: edupont04
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 09/01/2017
ms.author: edupont
ms.translationtype: HT
ms.sourcegitcommit: 1dfba8b14019991c95f40ffd5f7fbaed5df414eb
ms.openlocfilehash: 3ddb647d28a4065be248a265316b38e8d37d28c2
ms.contentlocale: fi-fi
ms.lasthandoff: 12/01/2017

---
# <a name="setup-and-administration-in-dynamics-nav"></a><span data-ttu-id="a9a1e-104">Asetukset ja hallinto Dynamics NAV -ohjelmassa</span><span class="sxs-lookup"><span data-stu-id="a9a1e-104">Setup and Administration in Dynamics NAV</span></span>
<span data-ttu-id="a9a1e-105">Yleensä yksi rooli hoitaa yrityksen keskitetyt hallintatehtävät.</span><span class="sxs-lookup"><span data-stu-id="a9a1e-105">Central administration tasks are usually performed by one role in the company.</span></span> <span data-ttu-id="a9a1e-106">Tehtävien laajuus voi määräytyä yrityksen koon ja järjestelmänvalvojan vastuualueiden mukaan.</span><span class="sxs-lookup"><span data-stu-id="a9a1e-106">The scope of these tasks can depend on the company's size and the administrator's job responsibilities.</span></span> <span data-ttu-id="a9a1e-107">Tehtäviin voi sisältyä esimerkiksi työ- ja sähköpostijonojen tietokantasynkronoinnin hallintaa, käyttäjien määritystä, käyttöliittymän mukautusta ja salausavainten hallintaa.</span><span class="sxs-lookup"><span data-stu-id="a9a1e-107">These tasks can include managing database synchronization of job and email queues, setting up users, customizing the user interface, and managing encryption keys.</span></span>  

<span data-ttu-id="a9a1e-108">Uuden liiketoimintaohjelmiston toimivuuden vuoksi on tärkeää, että syötettävät asetusarvot ovat oikeita alusta alkaen.</span><span class="sxs-lookup"><span data-stu-id="a9a1e-108">Entering the correct setup values from the start is important to the success of any new business software.</span></span> [!INCLUDE[d365fin](includes/d365fin_md.md)]<span data-ttu-id="a9a1e-109">issa on useita asetusoppaita, jotka helpottavat perustietojen määrittämistä.</span><span class="sxs-lookup"><span data-stu-id="a9a1e-109"> includes a number of setup guides that help you set up core data.</span></span> <span data-ttu-id="a9a1e-110">Lisätietoja on ohjeaiheessa [Dynamics NAVin määrittäminen ](setup.md).</span><span class="sxs-lookup"><span data-stu-id="a9a1e-110">For more information, see [Setting Up Dynamics NAV](setup.md).</span></span>

<!--Whether you use [!INCLUDE[rim](../../includes/rim_md.md)] to implement setup values or you manually enter them in the new company, you can support your setup decisions with some general recommendations for selected setup fields that are known to potentially cause the solution to be inefficient if defined incorrectly.-->  

<span data-ttu-id="a9a1e-111">Pääkäyttäjä tai järjestelmänvalvoja voi määrittää tietojen vaihtamiskehyksen, jonka avulla käyttäjät voivat viedä ja tuoda pankki- ja palkanlaskentatiedostojen tietoja esimerkiksi erilaisia kassanhallintaprosesseja varten.</span><span class="sxs-lookup"><span data-stu-id="a9a1e-111">A super user or an administrator can set up the Data Exchange Framework to enable users to export and import data in bank and payroll files, for example for various cash management processes.</span></span>  

<span data-ttu-id="a9a1e-112">Seuraavassa taulukossa on tehtäväsarja ja linkit tehtäviä käsitteleviin aiheisiin.</span><span class="sxs-lookup"><span data-stu-id="a9a1e-112">The following table describes a sequence of tasks, with links to the topics that describe them.</span></span>   

|<span data-ttu-id="a9a1e-113">**Tehtävä**</span><span class="sxs-lookup"><span data-stu-id="a9a1e-113">**To**</span></span>|<span data-ttu-id="a9a1e-114">**Katso**</span><span class="sxs-lookup"><span data-stu-id="a9a1e-114">**See**</span></span>|  
|------------|-------------|  
|<span data-ttu-id="a9a1e-115">Lisää käyttäjiä, hallitse tietojen käyttöoikeuksia ja määritä rooleja.</span><span class="sxs-lookup"><span data-stu-id="a9a1e-115">Add users, manage permissions and access to data, assign roles.</span></span>|[<span data-ttu-id="a9a1e-116">Käyttäjät, profiilit ja roolikeskukset Dynamics NAV -ohjelmassa</span><span class="sxs-lookup"><span data-stu-id="a9a1e-116">Users, Profiles, and Role Centers in Dynamics NAV</span></span>](admin-users-profiles-roles.md)|  
|<span data-ttu-id="a9a1e-117">Seuraa kaikkia suoria muutoksia, joita käyttäjät tekevät tietokannan tietoihin. Muutoksia seuraamalla voidaan tunnistaa virheiden alkuperä ja tietojen muutokset.</span><span class="sxs-lookup"><span data-stu-id="a9a1e-117">Track all direct modifications that users make to data in the database to identify the origin of errors and data changes.</span></span>|[<span data-ttu-id="a9a1e-118">Dynamics NAV -ohjelman muutosten kirjaaminen lokiin</span><span class="sxs-lookup"><span data-stu-id="a9a1e-118">Logging Changes in Dynamics NAV</span></span>](across-log-changes.md)|  
|<span data-ttu-id="a9a1e-119">Tue määritysten suhteen tekemiäsi päätöksiä valittujen kenttien suosituksilla, joiden tiedetään mahdollisesti aiheuttavan sen, että ratkaisu on tehoton, jos se määritetään virheellisesti.</span><span class="sxs-lookup"><span data-stu-id="a9a1e-119">Support your setup decisions with recommendations for selected fields that are known to potentially cause the solution to be inefficient if set up incorrectly</span></span>|[<span data-ttu-id="a9a1e-120">Määritä monimutkaiset sovellusalueet käyttäen parhaita käytäntöjä</span><span class="sxs-lookup"><span data-stu-id="a9a1e-120">Set Up Complex Application Areas Using Best Practices</span></span>](set-up-complex-application-areas-using-best-practices.md)|  
|<span data-ttu-id="a9a1e-121">Näytä sivuja, koodiyksiköitä ja kyselyitä verkkopalveluina.</span><span class="sxs-lookup"><span data-stu-id="a9a1e-121">Expose pages, codeunits, and queries as web services.</span></span>|[<span data-ttu-id="a9a1e-122">Toimintaohje: verkkopalvelun julkaiseminen</span><span class="sxs-lookup"><span data-stu-id="a9a1e-122">How to: Publish a Web Service</span></span>](across-how-publish-web-service.md)|  
|<span data-ttu-id="a9a1e-123">Dynamics NAV -ohjelman sisäisen ja ulkoisen sähköpostiviestinnän mahdollistavan SMTP-palvelimen määrittäminen</span><span class="sxs-lookup"><span data-stu-id="a9a1e-123">Set up an SMTP server to enable e-mail communication in and out of Dynamics NAV</span></span>| [<span data-ttu-id="a9a1e-124">Toimintaohje: Sähköpostin määrittäminen manuaalisesti tai asetusten ohjatun määrityksen käyttäminen</span><span class="sxs-lookup"><span data-stu-id="a9a1e-124">How to: Set Up Email Manually or Using the Assisted Setup</span></span>](madeira-how-setup-email.md)|  
|<span data-ttu-id="a9a1e-125">Määritä yksittäisiä tai toistuvia pyyntöjä raporttien tai koodiyksiköiden suorittamista varten.</span><span class="sxs-lookup"><span data-stu-id="a9a1e-125">Enter single or recurring requests to run reports or codeunits.</span></span>|[<span data-ttu-id="a9a1e-126">Käytä työjonoja ajoitustehtäviin</span><span class="sxs-lookup"><span data-stu-id="a9a1e-126">Use Job Queues to Schedule Tasks</span></span>](admin-job-queues-schedule-tasks.md)|  
|<span data-ttu-id="a9a1e-127">Asiakirjojen hallinta, poistaminen ja pakkaaminen</span><span class="sxs-lookup"><span data-stu-id="a9a1e-127">Manage, delete, or compress documents</span></span>|[<span data-ttu-id="a9a1e-128">Asiakirjojen hallinta</span><span class="sxs-lookup"><span data-stu-id="a9a1e-128">Manage Documents</span></span>](admin-manage-documents.md)|  

## <a name="see-also"></a><span data-ttu-id="a9a1e-129">Katso myös</span><span class="sxs-lookup"><span data-stu-id="a9a1e-129">See Also</span></span>
[<span data-ttu-id="a9a1e-130">Liiketoimintatoimintojen yleiskatsaus</span><span class="sxs-lookup"><span data-stu-id="a9a1e-130">Overview of Business Functionality</span></span>](madeira-business-functionality.md)  
[<span data-ttu-id="a9a1e-131">Yleiset liiketoimintatoiminnot</span><span class="sxs-lookup"><span data-stu-id="a9a1e-131">General Business Functionality</span></span>](ui-across-business-areas.md)  
<span data-ttu-id="a9a1e-132">[[!INCLUDE[d365fin](includes/d365fin_md.md)] -ohjelman käyttäminen](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="a9a1e-132">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>  
<span data-ttu-id="a9a1e-133">[Tervetuloa [!INCLUDE[d365fin](includes/d365fin_md.md)]iin!](index.md)</span><span class="sxs-lookup"><span data-stu-id="a9a1e-133">[Welcome to [!INCLUDE[d365fin](includes/d365fin_md.md)]](index.md)</span></span>  

