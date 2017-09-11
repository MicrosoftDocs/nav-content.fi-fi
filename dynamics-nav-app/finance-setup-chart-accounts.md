---
title: "Tilikartan määrittäminen tai muuttaminen"
author: edupont04
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 6b60b1344a1e18ad91863046110df880f75f7c04
ms.openlocfilehash: 2a2f1f2ec3ac5bdd935ec19c11d74e16bdee7686
ms.contentlocale: fi-fi
ms.lasthandoff: 07/19/2017

---

# <a name="set-up-or-change-the-chart-of-accounts"></a><span data-ttu-id="0ab8f-102">Tilikartan määrittäminen tai muuttaminen</span><span class="sxs-lookup"><span data-stu-id="0ab8f-102">Set Up or Change the Chart of Accounts</span></span>
<span data-ttu-id="0ab8f-103">Tilikartta näyttää ne kirjanpidon tilit, joihin on tallennettu taloustietoja.</span><span class="sxs-lookup"><span data-stu-id="0ab8f-103">The chart of accounts shows the ledger accounts that store your financial data.</span></span> <span data-ttu-id="0ab8f-104">Dynamics NAV sisältää tilikartan, joka on valmis tukemaan liiketoimintaasi.</span><span class="sxs-lookup"><span data-stu-id="0ab8f-104">Dynamics NAV includes a standard chart of accounts that is ready to support your business.</span></span>
<span data-ttu-id="0ab8f-105">Voit kuitenkin muuttaa oletustilejä ja lisätä uusia tilejä.</span><span class="sxs-lookup"><span data-stu-id="0ab8f-105">However, you can change the default accounts, and you can add new accounts.</span></span>  

## <a name="adding-or-changing-accounts"></a><span data-ttu-id="0ab8f-106">Tilien lisääminen tai muuttaminen</span><span class="sxs-lookup"><span data-stu-id="0ab8f-106">Adding or Changing Accounts</span></span>
<span data-ttu-id="0ab8f-107">Voit avata kunkin tilin KP-tilin tilikartasta ja lisätä tai muuttaa asetuksia.</span><span class="sxs-lookup"><span data-stu-id="0ab8f-107">From the chart of accounts, you can open each G/L account and add or change settings.</span></span>

<span data-ttu-id="0ab8f-108">**Huomautus**: Voit poistaa pääkirjanpitotilin.</span><span class="sxs-lookup"><span data-stu-id="0ab8f-108">**Note**: You can delete a general ledger account.</span></span> <span data-ttu-id="0ab8f-109">Ennen sen poistamista seuraavien on kuitenkin toteuduttava:</span><span class="sxs-lookup"><span data-stu-id="0ab8f-109">However, before you delete it, the following must be true:</span></span>  
- <span data-ttu-id="0ab8f-110">Tilin saldon tulee olla nolla.</span><span class="sxs-lookup"><span data-stu-id="0ab8f-110">The balance on the account must be zero.</span></span>  
- <span data-ttu-id="0ab8f-111">**Salli KP-tilin poisto ennen** -kenttä on määritettävä **Pääkirjanpidon asetukset** -ikkunassa. Tilillä ei saa olla tapahtumakirjauksia kyseisenä päivänä tai sen jälkeen.</span><span class="sxs-lookup"><span data-stu-id="0ab8f-111">The **Allow G/L Acc. Deletion Before** field must be set in the **General Ledger Setup** window, and the account must not have ledger entries on or after that date.</span></span>  
- <span data-ttu-id="0ab8f-112">Jos **Tarkista KP-tilin käyttö** -kenttä on valittu **Pääkirjanpidon asetukset** -ikkunassa, tiliä ei voi käyttää kirjausryhmässä tai kirjauksen asetuksissa.</span><span class="sxs-lookup"><span data-stu-id="0ab8f-112">If the **Check G/L Account Usage** field in the **General Ledger Setup** window is selected, then the account must not be used in any posting groups or posting setup.</span></span>  

<span data-ttu-id="0ab8f-113">Dynamics NAV ei anna poistaa pääkirjanpitotiliä, joka sisältää tilikartassa tarvittavia tietoja.</span><span class="sxs-lookup"><span data-stu-id="0ab8f-113">Dynamics NAV will prevent you from deleting a general ledger account that stores data that is needed in the chart of accounts.</span></span>  

##<a name="see-also"></a><span data-ttu-id="0ab8f-114">Katso myös</span><span class="sxs-lookup"><span data-stu-id="0ab8f-114">See Also</span></span>  
[<span data-ttu-id="0ab8f-115">Pääkirjanpito ja tilikartta</span><span class="sxs-lookup"><span data-stu-id="0ab8f-115">The General Ledger and the Chart of Accounts</span></span>](finance-setup-general-ledger.md)  
[<span data-ttu-id="0ab8f-116">Pankkitilien hallinta</span><span class="sxs-lookup"><span data-stu-id="0ab8f-116">Manage Bank Accounts</span></span>](bank-manage-bank-accounts.md)  
[<span data-ttu-id="0ab8f-117">Dimensiot</span><span class="sxs-lookup"><span data-stu-id="0ab8f-117">Dimensions</span></span>](finance-setup-dimensions.md)  
[<span data-ttu-id="0ab8f-118">Toimintaohje: Kanadan GIFI-koodien käyttäminen</span><span class="sxs-lookup"><span data-stu-id="0ab8f-118">How to: Work With GIFI Codes in Canada</span></span>](ca-finance-setup-work-GiFI-codes.md)

