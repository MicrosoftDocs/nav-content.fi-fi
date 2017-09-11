---
title: "Tietojen tuominen muista rahoitusjärjestelmistä"
author: edupont04
ms.custom: na
ms.date: 09/23/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: b5bd6092046f9a8d75498ddcf3b1ce73f674e687
ms.contentlocale: fi-fi
ms.lasthandoff: 06/26/2017

---

# <a name="import-data-from-other-finance-systems"></a><span data-ttu-id="a71c9-102">Tietojen tuominen muista rahoitusjärjestelmistä</span><span class="sxs-lookup"><span data-stu-id="a71c9-102">Import Data from Other Finance Systems</span></span>
<span data-ttu-id="a71c9-103">Dynamics NAV -ohjelmassa voi luoda tyhjän yrityksen, johon ladataan tiedot muista rahoituksen käyttöönottojärjestelmistä. Näitä tietoja voi käyttää uudessa Dynamics NAV -ohjelmassa.</span><span class="sxs-lookup"><span data-stu-id="a71c9-103">In Dynamics NAV, you can choose to create an empty company so that you can upload data from other finance-setup systems to use in your new Dynamics NAV.</span></span> <span data-ttu-id="a71c9-104">Yrityksen tällä hetkellä käytössä olevan rahoituksen käyttöönottoratkaisun mukaan voit siirtää tietoja asiakkaista, toimittajista, varastosta ja pankkitileistä.</span><span class="sxs-lookup"><span data-stu-id="a71c9-104">Depending on the finance-setup solution that your business uses today, you can transfer information about customers, vendors, inventory, and bank accounts.</span></span>
<span data-ttu-id="a71c9-105">Yrityksen omistaja -roolikeskuksen avulla voit ottaa käyttöön avustetun asennusoppaan, jonka avulla voit siirtää liiketoimintatiedot Excel-tiedostosta tai muista muodoista.</span><span class="sxs-lookup"><span data-stu-id="a71c9-105">In the Business Owner Role Center, you can access an assisted setup guide that helps you transfer the business data from an Excel file or from other formats.</span></span> <span data-ttu-id="a71c9-106">Ladattavissa olevien tiedostojen tyyppi riippuu käytettävissä olevista laajennuksista.</span><span class="sxs-lookup"><span data-stu-id="a71c9-106">The type of files you can upload depends on the extensions that are available.</span></span> <span data-ttu-id="a71c9-107">Voit esimerkiksi ladata tietoja QuickBooks-ohjelmasta, koska Dynamics NAV sisältää laajennuksen, joka käsittelee QuickBooks-tietojen muunnoksen.</span><span class="sxs-lookup"><span data-stu-id="a71c9-107">For example, you can upload data from QuickBooks because Dynamics NAV includes an extension that handles the conversion from QuickBooks.</span></span> <span data-ttu-id="a71c9-108">Jos haluat ladata tietoja muista rahoituksen käyttöönottoratkaisuista, tarkista, onko kyseiselle ratkaisulle saatavana laajennus tai tuo tiedot Excelistä.</span><span class="sxs-lookup"><span data-stu-id="a71c9-108">If you want to upload data from other finance-setup solutions, you must either check if an extension is available for that solution or import from Excel.</span></span>  
<span data-ttu-id="a71c9-109">Dynamics NAV sisältää malleja asiakkaille, toimittajille ja varastonimikkeille, joita voit kohdistaa tietojen lataamisen yhteydessä.</span><span class="sxs-lookup"><span data-stu-id="a71c9-109">Dynamics NAV includes templates for customers, vendors, and inventory items that you can choose to apply when you upload your data.</span></span>  

## <a name="transfer-from-quickbooks"></a><span data-ttu-id="a71c9-110">Siirtäminen QuickBooks-ohjelmasta</span><span class="sxs-lookup"><span data-stu-id="a71c9-110">Transfer from QuickBooks</span></span>
<span data-ttu-id="a71c9-111">Jos yrityksessä käytetään tänään QuickBooks-ohjelmaa, voit viedä tarvittavat tiedot IIF (Intuit Interchange Format) -tiedostoon.</span><span class="sxs-lookup"><span data-stu-id="a71c9-111">If your business uses QuickBooks today, you can export the relevant information to an Intuit Interchange Format (IIF) file.</span></span> <span data-ttu-id="a71c9-112">Tämän jälkeen voit avata avustetun asennusoppaan ja siirtää tiedot.</span><span class="sxs-lookup"><span data-stu-id="a71c9-112">You can then open the assisted setup guide to transfer the data.</span></span>
<span data-ttu-id="a71c9-113">Jos IIF-tiedosto sisältää esimerkiksi asiakkaita ja toimittajia, voit siirtää vain asiakkaiden tiedot.</span><span class="sxs-lookup"><span data-stu-id="a71c9-113">For example, if your IIF file includes customers and vendors, you can choose to transfer only the customer data.</span></span> <span data-ttu-id="a71c9-114">Loput tiedot voit siirtää myöhemmin.</span><span class="sxs-lookup"><span data-stu-id="a71c9-114">You can then transfer the rest of the information later.</span></span>  
<span data-ttu-id="a71c9-115">Avustetun asennuksen avulla voit muuttaa siirron oletusmäärityksiä. Näitä lisäasetuksia kannattaa muuttaa vain, jos tietokantataulukot ovat sinulle ennestään tuttuja.</span><span class="sxs-lookup"><span data-stu-id="a71c9-115">The assisted setup includes an option to change the default configuration of the transfer, but we recommend that you only enter this advanced setup if you are familiar with database tables.</span></span> <span data-ttu-id="a71c9-116">QuickBooks-ohjelmasta Dynamics NAV -ohjelmaan siirron oletusmääritykset siirtävät suurimmassa osassa yrityksiä juuri halutut tiedot.</span><span class="sxs-lookup"><span data-stu-id="a71c9-116">In the vast majority of businesses, the default mapping from QuickBooks to Dynamics NAV will transfer the information that you want.</span></span>

## <a name="see-also"></a><span data-ttu-id="a71c9-117">Katso myös</span><span class="sxs-lookup"><span data-stu-id="a71c9-117">See Also</span></span>
[<span data-ttu-id="a71c9-118">Rahoitus</span><span class="sxs-lookup"><span data-stu-id="a71c9-118">Finance</span></span>](finance-setup.md)  
<span data-ttu-id="a71c9-119">[Dynamics NAV -ohjelman mukauttaminen laajennusten avulla](ui-extensions.md) </span><span class="sxs-lookup"><span data-stu-id="a71c9-119">[Customizing Dynamics NAV Using Extensions](ui-extensions.md) </span></span>  
[<span data-ttu-id="a71c9-120">Dynamics NAV -ohjelman määrittäminen</span><span class="sxs-lookup"><span data-stu-id="a71c9-120">Set Up Your Dynamics NAV</span></span>](setup.md)

