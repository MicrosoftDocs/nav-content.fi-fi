---
title: "Tilikartan määrittäminen"
description: "Voit muuttaa tilikartan oletustilejä ja lisätä uusia tilejä."
documentationcenter: 
author: edupont04
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: COA, cha of acc
ms.date: 06/02/2017
ms.author: edupont
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: b9ed31ae8e7478f57457ad68fd69d7809f706e2a
ms.contentlocale: fi-fi
ms.lasthandoff: 10/16/2017

---
# <a name="setting-up-or-changing-the-chart-of-accounts"></a><span data-ttu-id="11a55-103">Tilikartan määrittäminen tai muuttaminen</span><span class="sxs-lookup"><span data-stu-id="11a55-103">Setting Up or Changing the Chart of Accounts</span></span>
<span data-ttu-id="11a55-104">Tilikartta näyttää ne kirjanpidon tilit, joihin on tallennettu taloustietoja.</span><span class="sxs-lookup"><span data-stu-id="11a55-104">The chart of accounts shows the ledger accounts that store your financial data.</span></span> [!INCLUDE[d365fin_long](includes/d365fin_long_md.md)]<span data-ttu-id="11a55-105"> sisältää tilikartan, joka on valmis tukemaan liiketoimintaasi.</span><span class="sxs-lookup"><span data-stu-id="11a55-105"> includes a standard chart of accounts that is ready to support your business.</span></span>
<span data-ttu-id="11a55-106">Voit kuitenkin muuttaa oletustilejä ja lisätä uusia tilejä.</span><span class="sxs-lookup"><span data-stu-id="11a55-106">However, you can change the default accounts, and you can add new accounts.</span></span>  

## <a name="adding-or-changing-accounts"></a><span data-ttu-id="11a55-107">Tilien lisääminen tai muuttaminen</span><span class="sxs-lookup"><span data-stu-id="11a55-107">Adding or Changing Accounts</span></span>
<span data-ttu-id="11a55-108">Voit avata kunkin tilin KP-tilin tilikartasta ja lisätä tai muuttaa asetuksia.</span><span class="sxs-lookup"><span data-stu-id="11a55-108">From the chart of accounts, you can open each G/L account and add or change settings.</span></span>

> [!NOTE]  
>   <span data-ttu-id="11a55-109">Voit poistaa pääkirjanpitotilin.</span><span class="sxs-lookup"><span data-stu-id="11a55-109">You can delete a general ledger account.</span></span> <span data-ttu-id="11a55-110">Ennen sen poistamista seuraavien on kuitenkin toteuduttava:</span><span class="sxs-lookup"><span data-stu-id="11a55-110">However, before you delete it, the following must be true:</span></span>  

* <span data-ttu-id="11a55-111">Tilin saldon tulee olla nolla.</span><span class="sxs-lookup"><span data-stu-id="11a55-111">The balance on the account must be zero.</span></span>  
* <span data-ttu-id="11a55-112">**Salli KP-tilin poisto ennen** -kenttä on määritettävä **Pääkirjanpidon asetukset** -ikkunassa. Tilillä ei saa olla tapahtumakirjauksia kyseisenä päivänä tai sen jälkeen.</span><span class="sxs-lookup"><span data-stu-id="11a55-112">The **Allow G/L Acc. Deletion Before** field must be set in the **General Ledger Setup** window, and the account must not have ledger entries on or after that date.</span></span>  
* <span data-ttu-id="11a55-113">Jos **Tarkista KP-tilin käyttö** -kenttä on valittu **Pääkirjanpidon asetukset** -ikkunassa, tiliä ei voi käyttää kirjausryhmässä tai kirjauksen asetuksissa.</span><span class="sxs-lookup"><span data-stu-id="11a55-113">If the **Check G/L Account Usage** field in the **General Ledger Setup** window is selected, then the account must not be used in any posting groups or posting setup.</span></span>  

[!INCLUDE[d365fin](includes/d365fin_md.md)]<span data-ttu-id="11a55-114"> estää tilikartassa tarvittavia tietoja sisältävän pääkirjanpitotilin poistamisen.</span><span class="sxs-lookup"><span data-stu-id="11a55-114"> will prevent you from deleting a general ledger account that stores data that is needed in the chart of accounts.</span></span>  

## <a name="see-also"></a><span data-ttu-id="11a55-115">Katso myös</span><span class="sxs-lookup"><span data-stu-id="11a55-115">See Also</span></span>
[<span data-ttu-id="11a55-116">Pääkirjanpito ja tilikartta</span><span class="sxs-lookup"><span data-stu-id="11a55-116">The General Ledger and the Chart of Accounts</span></span>](finance-general-ledger.md)  
[<span data-ttu-id="11a55-117">Pankkitilien hallinta</span><span class="sxs-lookup"><span data-stu-id="11a55-117">Managing Bank Accounts</span></span>](bank-manage-bank-accounts.md)  
[<span data-ttu-id="11a55-118">Dimensioiden käyttäminen</span><span class="sxs-lookup"><span data-stu-id="11a55-118">Working with Dimensions</span></span>](finance-dimensions.md)  
[<span data-ttu-id="11a55-119">Tuominen muista rahoitusjärjestelmistä</span><span class="sxs-lookup"><span data-stu-id="11a55-119">Importing from Other Finance Systems</span></span>](upload-data.md)  
<span data-ttu-id="11a55-120">[[!INCLUDE[d365fin](includes/d365fin_md.md)] -ohjelman käyttäminen](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="11a55-120">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>  

## 

