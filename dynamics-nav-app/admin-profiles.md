---
title: Profiilien ja roolikeskusten hallinta
description: "Lisätietoja Dynamics NAV -ohjelman käyttäjien ja roolikeskusten hallinnasta."
author: jswymer
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: profiles, roles, role centers, user roles
ms.date: 09/01/2017
ms.author: jswymer
ms.prod: dynamics-nav-2018
ms.translationtype: HT
ms.sourcegitcommit: b9b1f062ee6009f34698ea2cf33bc25bdd5b11e4
ms.openlocfilehash: 0d99f95d7c90bae55ea139a958ca098ab10a0a7f
ms.contentlocale: fi-fi
ms.lasthandoff: 10/23/2017

---
# <a name="managing-profiles-and-role-centers"></a><span data-ttu-id="9d9c6-103">Profiilien ja roolikeskusten hallinta</span><span class="sxs-lookup"><span data-stu-id="9d9c6-103">Managing Profiles and Role Centers</span></span>
<span data-ttu-id="9d9c6-104">Profiilit ovat niiden [!INCLUDE[navnow_md](includes/navnow_md.md)] -käyttäjien kokoelmia, jotka jakavat saman roolikeskuksen.</span><span class="sxs-lookup"><span data-stu-id="9d9c6-104">Profiles are collections of [!INCLUDE[navnow_md](includes/navnow_md.md)] users who share the same Role Center.</span></span> <span data-ttu-id="9d9c6-105">Roolikeskus on sivu, jossa voit sijoittaa eri osia.</span><span class="sxs-lookup"><span data-stu-id="9d9c6-105">A Role Center is a type of page on which you can place different parts.</span></span> <span data-ttu-id="9d9c6-106">Jokainen osa on säilö, joka voi sisältää muita sivuja tai ennalta määritettyjä järjestelmän osia, kuten Outlook-osan tai osia tehtävien, ilmoitusten tai huomautusten lisäämiseksi.</span><span class="sxs-lookup"><span data-stu-id="9d9c6-106">Each part is a container in which you can host other pages or pre-defined system parts, such as an Outlook part or parts for adding tasks, notifications, or notes.</span></span>  

## <a name="about-profiles-and-role-centers"></a><span data-ttu-id="9d9c6-107">Tietoja profiileista ja roolikeskuksista</span><span class="sxs-lookup"><span data-stu-id="9d9c6-107">About profiles and Role Centers</span></span>
<span data-ttu-id="9d9c6-108">Profiilien avulla voit linkittää käyttäjät ennalta määritettyihin roolikeskuksiin.</span><span class="sxs-lookup"><span data-stu-id="9d9c6-108">You use profiles to link users to pre-defined Role Centers.</span></span> <span data-ttu-id="9d9c6-109">Roolikeskus on kaikkien profiilin käyttäjien kotisivu, joka on määritetty profiilin käyttäjien tehtävien ja prioriteettien perusteella.</span><span class="sxs-lookup"><span data-stu-id="9d9c6-109">A Role Center is a home page for all users of a profile, which has been configured to reflect the tasks and priorities of users of the profile.</span></span> <span data-ttu-id="9d9c6-110">Esimerkiksi tilausten käsittelijän roolikeskus on määritetty niin, että se muuttuu tilausten käsittelijän tehtävien prioriteettien mukaisesti.</span><span class="sxs-lookup"><span data-stu-id="9d9c6-110">For example, the Order Processor Role Center has been configured to reflect the tasks and priorities of an order processor.</span></span> <span data-ttu-id="9d9c6-111">Roolikeskuksen avulla käyttäjät voivat helposti käyttää päivittäisessä työssä tarvittavia tietoja.</span><span class="sxs-lookup"><span data-stu-id="9d9c6-111">A Role Center provides easy access to information users need to perform their daily work.</span></span> <span data-ttu-id="9d9c6-112">Roolikeskus voi esimerkiksi määrittää pinot tai ruudut, jotka näytetään käyttäjälle ensimmäisen sisäänkirjauksen yhteydessä, sekä siirtymissivun linkit.</span><span class="sxs-lookup"><span data-stu-id="9d9c6-112">For example, the Role Center determines the Cues, or tile, that show when isers first sign in, and the links from the navigation page.</span></span>

<span data-ttu-id="9d9c6-113">Käytettävä profiili näkyy roolikeskuksen pääsisältöalueen otsikossa.</span><span class="sxs-lookup"><span data-stu-id="9d9c6-113">The profile that is used appears in the header of the Role Center’s main content area.</span></span> <span data-ttu-id="9d9c6-114">Järjestelmänvalvoja voi mukauttaa tätä roolikeskusta tietyn roolia tai tietyn yrityksen tarpeisiin.</span><span class="sxs-lookup"><span data-stu-id="9d9c6-114">An administrator can customize this Role Center to meet the needs of a specific role in a specific company.</span></span> <span data-ttu-id="9d9c6-115">Tilausten käsittelijä -roolikeskusta voi mukauttaa edelleen tietokonekohtaisesti tietyn tilausten käsittelijän tarpeita varten.</span><span class="sxs-lookup"><span data-stu-id="9d9c6-115">The Order Processor Role Center can then be further personalized on a single computer to meet the needs of a person who is carrying out the job as an order processor.</span></span> <span data-ttu-id="9d9c6-116">Tämä henkilö voi mukauttaa roolikeskusta tallentamalla kyselyjä, lisäämällä suodattimia ja lisäämällä tai poistamalla kenttiä.</span><span class="sxs-lookup"><span data-stu-id="9d9c6-116">This person can personalize the Role Center by saving queries, adding filters, and adding or removing fields.</span></span>

<span data-ttu-id="9d9c6-117">Profiilit ja roolikeskukset edustavat rooleja ja vastuualueita organisaatiossa.</span><span class="sxs-lookup"><span data-stu-id="9d9c6-117">Profiles and Role Centers align with the roles and responsibilities in your organization.</span></span> [!INCLUDE[navnow_md](includes/navnow_md.md)]<span data-ttu-id="9d9c6-118"> sisältää joukon valmiita profiileja, joista kukin vastaa tiettyä Roolikeskusta ja sisältää siihen linkin.</span><span class="sxs-lookup"><span data-stu-id="9d9c6-118"> provides a set of default profiles, which each correspond to and link to a Role Center.</span></span> <span data-ttu-id="9d9c6-119">Järjestelmänvalvojat voivat muokata luotuja profiileja tai luoda uusia profiileja.</span><span class="sxs-lookup"><span data-stu-id="9d9c6-119">Administrators can modify existing profiles or create new ones.</span></span>  
  
> [!NOTE]  
>  <span data-ttu-id="9d9c6-120">Profiileja ei ole eksplisiittisesti linkitetty rooleihin ja käyttöoikeuksiin, jotka muodostavat suojausjärjestelmän, mutta profiilien käyttäjillä on oltava käyttöoikeudet, jotka ovat yhdenmukaiset heidän rooliensa kanssa suojausjärjestelmässä.</span><span class="sxs-lookup"><span data-stu-id="9d9c6-120">Profiles are not explicitly linked to the roles and permissions that constitute the security system, but profile users must have permissions that align with their roles in the security system.</span></span> <span data-ttu-id="9d9c6-121">Katso lisätietoja kohdasta [Security in the Role Tailored Environment](http://go.microsoft.com/fwlink?LinkId=147633) MSDN-kirjastossa (englanninkielinen).</span><span class="sxs-lookup"><span data-stu-id="9d9c6-121">For more information, see [Security in the Role Tailored Environment](http://go.microsoft.com/fwlink?LinkId=147633) in the MSDN Library.</span></span> 

## <a name="to-create-a-profile"></a><span data-ttu-id="9d9c6-122">Profiilin luominen</span><span class="sxs-lookup"><span data-stu-id="9d9c6-122">To create a profile</span></span>
1.  <span data-ttu-id="9d9c6-123">Valitse ![Etsi sivu tai raportti](media/ui-search/search_small.png "Etsi sivu tai raportti -kuvake") -kuvake, syötä **Profiilit** ja valitse sitten aiheeseen liittyvä linkki.</span><span class="sxs-lookup"><span data-stu-id="9d9c6-123">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Profiles**, and then choose the related link.</span></span>  
  
2.  <span data-ttu-id="9d9c6-124">Valitse **Uusi**-toiminto, kun haluat avata **Uusi profiilikortti** -ikkunan.</span><span class="sxs-lookup"><span data-stu-id="9d9c6-124">Choose the **New** action to open the **New Profile Card** window.</span></span>  
  
3.  <span data-ttu-id="9d9c6-125">Anna **Profiilin tunnus** -kentässä nimi, joka kuvaa käyttäjän tarkoitettua roolia.</span><span class="sxs-lookup"><span data-stu-id="9d9c6-125">In the **Profile ID** field, enter a name that describes the intended role of the user.</span></span>  
  
4.  <span data-ttu-id="9d9c6-126">Kirjoita **Kuvaus**-kenttään profiilitunnuksen kuvaus, esimerkiksi **Tilausten käsittelijä**.</span><span class="sxs-lookup"><span data-stu-id="9d9c6-126">In the **Description** field, enter a description of the Profile ID, for example, **Order Processor**.</span></span>  
  
5.  <span data-ttu-id="9d9c6-127">Määritä **Roolikeskuksen tunnus** -kenttäään profiiliin liitettävä roolikeskus.</span><span class="sxs-lookup"><span data-stu-id="9d9c6-127">Set the **Role Center ID** field to the Role Center that you want to assign to the profile.</span></span>  
  
6.  <span data-ttu-id="9d9c6-128">Jos haluat määrittää tämän roolikeskuksen profiilin oletusroolikeskukseksi, valitse **Oletusroolikeskus**-valintaruutu.</span><span class="sxs-lookup"><span data-stu-id="9d9c6-128">To make this Role Center the default for the profile, select the **Default Role Center** chack box.</span></span>  
  
7.  <span data-ttu-id="9d9c6-129">Valitse **OK**-painike.</span><span class="sxs-lookup"><span data-stu-id="9d9c6-129">Choose the **OK** button.</span></span> <span data-ttu-id="9d9c6-130">.</span><span class="sxs-lookup"><span data-stu-id="9d9c6-130">.</span></span>  
  
<span data-ttu-id="9d9c6-131">Olemassa olevan profiilin muokkaaminen tehdään samoin, paitsi valitset olemassa olevan profiilin Profiili-sivulla **Uusi**-painikkeen valitsemisen sijaan.</span><span class="sxs-lookup"><span data-stu-id="9d9c6-131">The procedure for modifying an existing profile is the same, except you select an existing profile in the Profiles page instead of chooseing **New**.</span></span>  


##<a name="copying-a-profile"></a><span data-ttu-id="9d9c6-132">Profiilin kopioiminen</span><span class="sxs-lookup"><span data-stu-id="9d9c6-132">Copying a profile</span></span> 
<span data-ttu-id="9d9c6-133">Profiilin kopioiminen voi säästää aikaa, jos haluat käyttää profiilissa samanlaisia asetuksia, ja haluat muuttaa vain joitakin asetuksia.</span><span class="sxs-lookup"><span data-stu-id="9d9c6-133">Copying a profile can save you time if you want to use similar settings on a profile and you only want to change a few settings.</span></span>

1.  <span data-ttu-id="9d9c6-134">Avaa kopioitava profiili ja valitse sitten **Kopioi profiili** -toiminto.</span><span class="sxs-lookup"><span data-stu-id="9d9c6-134">Open the profile that you want to copy, and then choose the **Copy Profile** action.</span></span>

2.  <span data-ttu-id="9d9c6-135">Syötä **Uuden profiilin tunnus** -kenttään sen profiilin nimi, jonka haluat kopioida.</span><span class="sxs-lookup"><span data-stu-id="9d9c6-135">In **New Profile ID** field, enter a name for the profile that you want to copy.</span></span> 

3.  <span data-ttu-id="9d9c6-136">Määritä **Uuden profiilin alue** -kenttään jokin seuraavista arvoista:</span><span class="sxs-lookup"><span data-stu-id="9d9c6-136">Set the **New Profile Scope** field to one of the following:</span></span>

    - <span data-ttu-id="9d9c6-137">**Järjestelmä**, kun haluat määrittää uuden profiilin kaikkien sovellusta käyttävien vuokraajatietokantojen käytettäväksi.</span><span class="sxs-lookup"><span data-stu-id="9d9c6-137">**System** to make the new profile available to all tenant databases that use the application.</span></span>
    - <span data-ttu-id="9d9c6-138">**Vuokraaja**, kun haluat määrittää profiilin vain nykyisen vuokraajatietokannan käytettäväksi.</span><span class="sxs-lookup"><span data-stu-id="9d9c6-138">**Tenant** to make the new profile available to just the current tenant database.</span></span> 
4. <span data-ttu-id="9d9c6-139">Valitse **OK**-painike, kun olet valmis.</span><span class="sxs-lookup"><span data-stu-id="9d9c6-139">Choose the **OK** buttom when done.</span></span>

## <span data-ttu-id="9d9c6-140"><a name="ExportImportProfile"></a>Profiilien vieminen ja tuominen</span><span class="sxs-lookup"><span data-stu-id="9d9c6-140"><a name="ExportImportProfile"></a>Exporting and importing profiles</span></span>

<span data-ttu-id="9d9c6-141">Voit viedä profiileja XML-tiedostoina [!INCLUDE[d365fin](includes/d365fin_md.md)] -tietokantaan ja tuoda niitä tietokannasta.</span><span class="sxs-lookup"><span data-stu-id="9d9c6-141">You can export and import profiles as XML files to and from the a [!INCLUDE[d365fin](includes/d365fin_md.md)] database.</span></span> <span data-ttu-id="9d9c6-142">Profiilin vieminen ja tuominen voi säästää aikaa, kun määrität käyttöliittymää. Voit käyttää aiemmin luotua profiilimääritystä sen sijaan, että määrittäisit profiilin alusta alkaen.</span><span class="sxs-lookup"><span data-stu-id="9d9c6-142">Exporting and importing a profile can save you time when configuring the user interface because you reuse an existing profile configuration instead of having to configure a profile from scratch.</span></span> <span data-ttu-id="9d9c6-143">Jos profiili on määritetty [!INCLUDE[d365fin](includes/d365fin_md.md)] -tietokannassa ja haluat käyttää sen tai osan samasta profiilimäärityksestä uudelleen toisessa tietokannassa, voit viedä profiilin XML-tiedostoon.</span><span class="sxs-lookup"><span data-stu-id="9d9c6-143">If you have a profile that is configured in a [!INCLUDE[d365fin](includes/d365fin_md.md)] database and you would like to reuse all or some of the same profile configurations in another database, you can export the profile to an XML file.</span></span> <span data-ttu-id="9d9c6-144">Tämän jälkeen voit tuoda profiilin XML-tiedoston toiseen tietokantaan.</span><span class="sxs-lookup"><span data-stu-id="9d9c6-144">Then, you can import the profile XML file into the other database.</span></span>

-   <span data-ttu-id="9d9c6-145">Voit viedä profiilin avaamalla hakutoiminnon ja avaamalla sitten **Vie profiilit** -sivun. Valitse profiili luettelosta ja valitse sitten **Vie**-toiminto.</span><span class="sxs-lookup"><span data-stu-id="9d9c6-145">To export a profile, open search for and open the **Export Profiles** page, select the profile from the list, and then choose the **Export** action.</span></span> <span data-ttu-id="9d9c6-146">Tallenna XML-tiedosto tietokoneelle tai verkkoon.</span><span class="sxs-lookup"><span data-stu-id="9d9c6-146">Save the XML file to a location on your computer or network.</span></span> 
  
-   <span data-ttu-id="9d9c6-147">Voit tuoda profiilin avaamalla hakutoiminnon ja avaamalla sitten **Tuo profiilit** -sivun. Valitse profiilin XML-tiedosto ja valitse sitten **OK**-toiminto.</span><span class="sxs-lookup"><span data-stu-id="9d9c6-147">To import a profile, open search for and open the **Import Profiles** page, select the profile XML file, and then choose the **OK** button.</span></span> 

    > [!NOTE]  
    >  <span data-ttu-id="9d9c6-148">Et voi tuoda profiilia, joka on jo tietokannassa, vaikka XML-tiedosto olisi eriniminen tai sillä olisi eri sisältö.</span><span class="sxs-lookup"><span data-stu-id="9d9c6-148">You cannot import a profile that already exists in the database, even though the XML file is named differently or has different content.</span></span> <span data-ttu-id="9d9c6-149">Poista olemassa oleva profiili ennen kuin tuot uuden profiilin.</span><span class="sxs-lookup"><span data-stu-id="9d9c6-149">You must delete the existing profile before you can import the new profile.</span></span> 



## <a name="see-also"></a><span data-ttu-id="9d9c6-150">Katso myös</span><span class="sxs-lookup"><span data-stu-id="9d9c6-150">See Also</span></span>  
[<span data-ttu-id="9d9c6-151">Toimintaohje: Käyttäjien ja käyttöoikeuksien hallinta</span><span class="sxs-lookup"><span data-stu-id="9d9c6-151">How to: Manage Users and Permissions</span></span>](ui-how-users-permissions.md)  
[<span data-ttu-id="9d9c6-152">Käyttöliittymän mukauttaminen</span><span class="sxs-lookup"><span data-stu-id="9d9c6-152">Customizing the User Interface</span></span>](ui-customizing-overview.md)   
<!--[Security Overview](../Security%20Overview.md)-->

