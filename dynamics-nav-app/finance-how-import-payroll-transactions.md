---
title: 'Toimintaohje: palkkatapahtumien tuominen'
author: SorenGP
ms.custom: na
ms.date: 09/29/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: d5e70a0a1659c7facdeec3f0971eda43ff8a03cc
ms.contentlocale: fi-fi
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-import-payroll-transactions"></a><span data-ttu-id="c8269-102">Toimintaohje: palkkatapahtumien tuominen</span><span class="sxs-lookup"><span data-stu-id="c8269-102">How to: Import Payroll Transactions</span></span>
<span data-ttu-id="c8269-103">Jotta palkanmaksut ja liittyvät tapahtumat voidaan käsitellä, palkanlaskennan tarjoajan tekemät rahoitustapahtumat on tuotava ja kirjattava pääkirjanpitoon.</span><span class="sxs-lookup"><span data-stu-id="c8269-103">To account for salary payments and related transactions, you must import and post financial transactions made by your payroll provider to the general ledger.</span></span> <span data-ttu-id="c8269-104">Voit tehdä tämän tuomalla ensin</span><span class="sxs-lookup"><span data-stu-id="c8269-104">To do this, you first import a csv.</span></span> <span data-ttu-id="c8269-105">palkanlaskennan tarjoajalta saatu csv-tiedosto **Yleinen päiväkirja** -ikkunaan.</span><span class="sxs-lookup"><span data-stu-id="c8269-105">file that you receive from the payroll provider into the **General Journal** window.</span></span> <span data-ttu-id="c8269-106">Linkitä sitten ulkoiset tilit palkanlaskentatiedostoon soveltuvissa KP-tileissä.</span><span class="sxs-lookup"><span data-stu-id="c8269-106">Then you map the external accounts in the payroll file to the relevant G/L accounts.</span></span> <span data-ttu-id="c8269-107">Kirjaa lopuksi palkkatapahtumat tilin yhdistämisen perusteella.</span><span class="sxs-lookup"><span data-stu-id="c8269-107">Lastly, you post the payroll transactions according to the account mapping.</span></span>

## <a name="to-import-a-payroll-file"></a><span data-ttu-id="c8269-108">Palkanlaskentatiedoston tuominen</span><span class="sxs-lookup"><span data-stu-id="c8269-108">To import a payroll file</span></span>
1. <span data-ttu-id="c8269-109">Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Yleiset päiväkirjat** ja valitse sitten aiheeseen liittyvä linkki.</span><span class="sxs-lookup"><span data-stu-id="c8269-109">In the top right corner, choose the **Search for Page or Report** icon, enter **General Journals**, and then choose the related link.</span></span>
2. <span data-ttu-id="c8269-110">Valitse kyseessä olevan yleisen päiväkirjan erän **Tuo palkkatapahtumat** -toiminto.</span><span class="sxs-lookup"><span data-stu-id="c8269-110">In the relevant general journal batch, choose the **Import Payroll Transactions** action.</span></span>
3. <span data-ttu-id="c8269-111">Valitse **Tuo**-ikkunassa kyseessä oleva palkanlaskentatiedosto ja valitse sitten **OK**-painike.</span><span class="sxs-lookup"><span data-stu-id="c8269-111">In the **Import** window, select the relevant payroll file, and then choose the **OK** button.</span></span> <span data-ttu-id="c8269-112">Tiedoston on oltava CSV-muodossa.</span><span class="sxs-lookup"><span data-stu-id="c8269-112">The file must be in CSV format.</span></span> 
4. <span data-ttu-id="c8269-113">Seuraa **Tuo palkkatapahtumat** -ikkunan vaiheita ja tuo tapahtumat ja liitä tilit. Valitse sitten **Valmis**-painike.</span><span class="sxs-lookup"><span data-stu-id="c8269-113">Follow the steps in the **Import Payroll Transactions** window to import transactions and map accounts, and then choose the **Finish** button.</span></span>

    <span data-ttu-id="c8269-114">Yleiseen päiväkirjaan täytetään rivit, jotka edustavat palkanlaskentatiedoston sisältämiä tapahtumia, ja **KP-tili**-sarakkeen soveltuvat tilit.</span><span class="sxs-lookup"><span data-stu-id="c8269-114">The general journal is filled with lines representing the transactions that the payroll file contains and with the relevant accounts in the **G/L Account** column.</span></span>
4. <span data-ttu-id="c8269-115">Muokkaa tai kirjaa päiväkirjarivit samalla tavalla kuin muille pääkirjanpidon tapahtumille.</span><span class="sxs-lookup"><span data-stu-id="c8269-115">Edit or post the journal lines as for any other general ledger transactions.</span></span> <span data-ttu-id="c8269-116">Lisätietoja on kohdassa [Toimintaohje: Yleisten päiväkirjojen käyttäminen](ui-work-general-journals.md).</span><span class="sxs-lookup"><span data-stu-id="c8269-116">For more information, see [How to: Work With General Journals](ui-work-general-journals.md).</span></span>   

## <a name="see-also"></a><span data-ttu-id="c8269-117">Katso myös</span><span class="sxs-lookup"><span data-stu-id="c8269-117">See Also</span></span>
[<span data-ttu-id="c8269-118">Rahoitus</span><span class="sxs-lookup"><span data-stu-id="c8269-118">Finance</span></span>](finance-setup.md)  
[<span data-ttu-id="c8269-119">Toimintaohje: Yleisten päiväkirjojen käyttäminen</span><span class="sxs-lookup"><span data-stu-id="c8269-119">How to: Work With General Journals</span></span>](ui-work-general-journals.md)  

