---
title: KP-raporttimallit
author: edupont04
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: ba67e7e09f4375cbdbf53f401fd0f3d83450c9ec
ms.contentlocale: fi-fi
ms.lasthandoff: 06/26/2017

---

# <a name="account-schedules"></a><span data-ttu-id="3255c-102">KP-raporttimallit</span><span class="sxs-lookup"><span data-stu-id="3255c-102">Account Schedules</span></span>
<span data-ttu-id="3255c-103">KP-raporttimallien avulla voit hakea taloustietoihin yksityiskohtaisia tietoja.</span><span class="sxs-lookup"><span data-stu-id="3255c-103">With account schedules, you can get detailed insights into your financial data.</span></span> <span data-ttu-id="3255c-104">Voit määrittää eri asetteluita ja määrittää tietoja, jotka haluat poimia tilikartoista. Tilikartta sisältää taloustietoja, mutta joskus on tärkeää tarkastella myös tietoja, joita tilikartassa ei voida esittää.</span><span class="sxs-lookup"><span data-stu-id="3255c-104">You can set up various layouts to define the information that you want to extract from the chart of accounts The chart of accounts stores your financial data, but sometimes you want to get a view on your data that the chart of accounts cannot really show.</span></span> <span data-ttu-id="3255c-105">Voit käyttää KP-raporttimalleja kirjanpitotilien lukujen analysoimisessa ja pääkirjanpidon tapahtumien ja pääkirjanpidon budjettitapahtumien vertailemisessa.</span><span class="sxs-lookup"><span data-stu-id="3255c-105">So you use account schedules to analyze figures in general ledger accounts and to compare general ledger entries with general ledger budget entries.</span></span>
<span data-ttu-id="3255c-106">Saatat esimerkiksi haluta laskea tiliryhmien välisummat ja sisällyttää ne uusiin kokonaissummiin.</span><span class="sxs-lookup"><span data-stu-id="3255c-106">For example, you want to calculate subtotals for groups of accounts, and you want to include these subtotals in new totals, and so on.</span></span>
<span data-ttu-id="3255c-107">Dynamics NAV sisältää KP-raporttimalleja, joita käytetään kotisivun kaavioiden luomisessa.</span><span class="sxs-lookup"><span data-stu-id="3255c-107">Dynamics NAV includes sample account schedules that are used to generate the charts on your Home page.</span></span> <span data-ttu-id="3255c-108">Voit esimerkiksi luoda KP-raporttimalleja katteen laskemista varten erilaisille dimensioille, kuten osastoille tai asiakasryhmille.</span><span class="sxs-lookup"><span data-stu-id="3255c-108">You can also create account schedules to calculate profit margins on such dimensions as departments or customer groups.</span></span>  

<span data-ttu-id="3255c-109">KP-raporttimallien määrittäminen vaatii tilikartan taloustietojen ymmärtämistä.</span><span class="sxs-lookup"><span data-stu-id="3255c-109">Setting up account schedules requires an understanding of the financial data in the chart of accounts.</span></span>
<span data-ttu-id="3255c-110">Voit esimerkiksi tarkastella pääkirjanpidon tapahtumia budjettitapahtumien prosenttiosuuksina.</span><span class="sxs-lookup"><span data-stu-id="3255c-110">For example, you can view general ledger entries as percentages of budget entries.</span></span>
<span data-ttu-id="3255c-111">Voit käyttää KP-raporttimallissa jotakin oletusasettelua tai määrittää omat rivit ja sarakkeet, jolloin voit määrittää tarkasti vertailtavat luvut ja niiden vertailutavan.</span><span class="sxs-lookup"><span data-stu-id="3255c-111">You can use one of the default layouts for your account schedule, or you can set up your own rows and columns so that you can decide exactly which figures you wish to compare and how.</span></span>
<span data-ttu-id="3255c-112">Tämän ansioista voit luoda niin monta räätälöityä taloudellista raporttia kuin haluat.</span><span class="sxs-lookup"><span data-stu-id="3255c-112">This means that you can create as many customized financial statements as you want.</span></span> <span data-ttu-id="3255c-113">**KP-raporttimalli**-ikkunassa voit määrittää KP-raporttimalleja.</span><span class="sxs-lookup"><span data-stu-id="3255c-113">You use the **Account Schedule** window to set up account schedules.</span></span>  

## <a name="account-categories-and-account-schedules"></a><span data-ttu-id="3255c-114">Tililuokat ja KP-raporttimallit</span><span class="sxs-lookup"><span data-stu-id="3255c-114">Account Categories and Account Schedules</span></span>
<span data-ttu-id="3255c-115">Tililuokkien avulla voit muuttaa rahoituslaskelmien asettelua.</span><span class="sxs-lookup"><span data-stu-id="3255c-115">You can use account categories to change the layout of your financial statements.</span></span> <span data-ttu-id="3255c-116">Kun olet määrittänyt tililuokat **KP-tilin luokat** -ikkunassa ja valinnut **Luo KP-raporttimallit** -toiminnon, tärkeimpien talousraporttien perustana olevat KP-raporttimallit päivitetään.</span><span class="sxs-lookup"><span data-stu-id="3255c-116">When you have set up your account categories in the **G/L Account Categories** window, and you choose the **Generate Account Schedules** action, the underlying account schedules for the core financial reports are updated.</span></span> <span data-ttu-id="3255c-117">Kun seuraavan kerran suoritat jonkin näistä raporteista, uudet kokonaissummat ja korvaustapahtumat lisätään muutosten perusteella.</span><span class="sxs-lookup"><span data-stu-id="3255c-117">the next time you run one of these reports, such as the balance statement, new totals and subentries are added, based on your changes.</span></span> <span data-ttu-id="3255c-118">Lisätietoja on kohdassa [Pääkirjanpito ja tilikartta](finance-setup-general-ledger.md).</span><span class="sxs-lookup"><span data-stu-id="3255c-118">For more information, see [The General Ledger and the Chart of Accounts](finance-setup-general-ledger.md).</span></span>    
## <a name="see-also"></a><span data-ttu-id="3255c-119">Katso myös</span><span class="sxs-lookup"><span data-stu-id="3255c-119">See Also</span></span>
[<span data-ttu-id="3255c-120">Rahoitus</span><span class="sxs-lookup"><span data-stu-id="3255c-120">Finance</span></span>](finance-setup.md)  
[<span data-ttu-id="3255c-121">Rahoituksen määrittäminen</span><span class="sxs-lookup"><span data-stu-id="3255c-121">Set Up Finance</span></span>](finance-setup-setup-finance-setup.md)  
[<span data-ttu-id="3255c-122">Pääkirjanpito ja tilikartta</span><span class="sxs-lookup"><span data-stu-id="3255c-122">The General Ledger and the Chart of Accounts</span></span>](finance-setup-general-ledger.md)  
