---
title: Pankkitilien hallinta
author: SorenGP
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 6b60b1344a1e18ad91863046110df880f75f7c04
ms.openlocfilehash: d97c3afba0e899768bda1b637c4f288db210d38c
ms.contentlocale: fi-fi
ms.lasthandoff: 07/19/2017

---

# <a name="manage-bank-accounts"></a><span data-ttu-id="fa0de-102">Pankkitilien hallinta</span><span class="sxs-lookup"><span data-stu-id="fa0de-102">Manage Bank Accounts</span></span>
<span data-ttu-id="fa0de-103">Täsmäytä Dynamics NAV -ohjelman pankkitilitapahtumat säännöllisin väliajoin pankin pankkitilin liittyvien pankkitapahtumien kanssa. Kirjaa sitten saldo pankkitilille.</span><span class="sxs-lookup"><span data-stu-id="fa0de-103">At regular intervals, you must reconcile your bank ledger entries in Dynamics NAV with the related bank transactions in bank accounts at your bank, and then post the balance to your bank account.</span></span> <span data-ttu-id="fa0de-104">Voit suorittaa tämän tehtävän **Maksujen täsmäytyskirjauskansio** -kohdassa pankin tiliotteessa olevien maksujen käsittelyn osana.</span><span class="sxs-lookup"><span data-stu-id="fa0de-104">You can perform this task either as part of processing the payments represented on a bank statement in the **Payment Reconciliation Journal**.</span></span> <span data-ttu-id="fa0de-105">Vaihtoehtoisesti voit suorittaa tehtävän maksujen käsittelyn ulkopuolella **Pankkitilin täsmäytys** -ikkunassa. Tämä tukee sekkitapahtumia.</span><span class="sxs-lookup"><span data-stu-id="fa0de-105">Alternatively, you can perform the task separately from payment processing, in the **Bank Acc. Reconciliation** window, which supports check ledger entries.</span></span> <span data-ttu-id="fa0de-106">Molemmissa tapauksissa ikkunat täytetään tuomalla pankin tiliote Dynamics NAV -ohjelmaan.</span><span class="sxs-lookup"><span data-stu-id="fa0de-106">In both cases, you fill the windows by importing the bank statement into Dynamics NAV.</span></span>

<span data-ttu-id="fa0de-107">Joskus on siirrettävä summia Dynamics NAV -ohjelman pankkitilien välillä pankin siirtojen mukaisesti.</span><span class="sxs-lookup"><span data-stu-id="fa0de-107">Sometimes, you need to transfer amounts between bank account in Dynamics NAV to reflect transfers at your bank.</span></span> <span data-ttu-id="fa0de-108">Tämä tehtävä suoritetaan **Yleinen päiväkirja** -ikkunassa varojen valuutan osoittamalla tavalla.</span><span class="sxs-lookup"><span data-stu-id="fa0de-108">You perform this task in the **General Journal** window, in different ways depending on the currency of the funds.</span></span>

<span data-ttu-id="fa0de-109">Jokainen pankkitili on määritettävä pankkitilin kortiksi, ennen kuin pankkitilejä voidaan hallita.</span><span class="sxs-lookup"><span data-stu-id="fa0de-109">Before you can manage bank accounts, you must set each bank account up as a bank account card.</span></span> <span data-ttu-id="fa0de-110">Lisäksi on määritettävä sähköiset palvelut, joita käytetään pankin tiliotteen tuonnissa ja maksutiedoston viennissä.</span><span class="sxs-lookup"><span data-stu-id="fa0de-110">In addition, you must set up electronic services that you may use for bank statement import and payment file export.</span></span> <span data-ttu-id="fa0de-111">Lisätietoja on kohdassa [Pankkitilien määrittäminen](bank-setup-banking.md).</span><span class="sxs-lookup"><span data-stu-id="fa0de-111">For more information, see [Set Up Bank Accounts](bank-setup-banking.md).</span></span>

<span data-ttu-id="fa0de-112">Seuraavassa taulukossa on tehtäväsarja ja linkit tehtäviä kuvaaviin aiheisiin.</span><span class="sxs-lookup"><span data-stu-id="fa0de-112">The following table describes a sequence of tasks, with links to the topics that describe them.</span></span>

|<span data-ttu-id="fa0de-113">Toiminta</span><span class="sxs-lookup"><span data-stu-id="fa0de-113">To</span></span> |<span data-ttu-id="fa0de-114">Katso</span><span class="sxs-lookup"><span data-stu-id="fa0de-114">See</span></span> |
|---|----|
|<span data-ttu-id="fa0de-115">Täsmäytä maksukäsittelyyn liittyvät pankkitilit **Maksujen täsmäytyskirjauskansio** -ikkunassa.</span><span class="sxs-lookup"><span data-stu-id="fa0de-115">Reconcile bank accounts in connection with payment processing in the **Payment Reconciliation Journal** window.</span></span>|[<span data-ttu-id="fa0de-116">Maksujen kohdistaminen automaattisesti ja pankkitilien täsmäyttäminen</span><span class="sxs-lookup"><span data-stu-id="fa0de-116">Apply Payments Automatically and Reconcile Bank Accounts</span></span>](receivables-apply-payments-auto-reconcile-bank-accounts.md)|
|<span data-ttu-id="fa0de-117">Täsmäytä pankkitilit, kuten sekkitapahtumat, erillisinä tehtävinä **Pankkitilin täsmäytys** -ikkunassa.</span><span class="sxs-lookup"><span data-stu-id="fa0de-117">Reconcile bank accounts, including check ledger entries, as a separate task in the **Bank Acc. Reconciliation** window.</span></span>|[<span data-ttu-id="fa0de-118">Toimintaohje: Pankkitilien täsmäyttäminen erikseen</span><span class="sxs-lookup"><span data-stu-id="fa0de-118">How to: Reconcile Bank Accounts Separately</span></span>](bank-how-reconcile-bank-accounts-separately.md)|
|<span data-ttu-id="fa0de-119">Kirjaa pankkitilien väliset siirrot samassa valuutassa tai eri valuutoissa.</span><span class="sxs-lookup"><span data-stu-id="fa0de-119">Post transfers between bank accounts in the same currency or in different currencies.</span></span>|[<span data-ttu-id="fa0de-120">Toimintaohje: Pankkivarojen siirtäminen</span><span class="sxs-lookup"><span data-stu-id="fa0de-120">How to: Transfer Bank Funds</span></span>](bank-how-transfer-bank-funds.md)
## <a name="see-also"></a><span data-ttu-id="fa0de-121">Katso myös</span><span class="sxs-lookup"><span data-stu-id="fa0de-121">See Also</span></span>  
[<span data-ttu-id="fa0de-122">Pankkitoiminnan määrittäminen</span><span class="sxs-lookup"><span data-stu-id="fa0de-122">Set Up Banking</span></span>](bank-setup-banking.md)  
[<span data-ttu-id="fa0de-123">Myyntisaamisten hallinta</span><span class="sxs-lookup"><span data-stu-id="fa0de-123">Manage Receivables</span></span>](receivables-manage-receivables.md)  
<span data-ttu-id="fa0de-124">[Ostovelkojen hallinta](payables-manage-payables.md)  </span><span class="sxs-lookup"><span data-stu-id="fa0de-124">[Manage Payables](payables-manage-payables.md)  </span></span>  
[<span data-ttu-id="fa0de-125">Dynamics NAV -ohjelman käyttäminen</span><span class="sxs-lookup"><span data-stu-id="fa0de-125">Work With Dynamics NAV</span></span>](ui-work-product.md)  
[<span data-ttu-id="fa0de-126">Liiketoiminta-alueiden välillä</span><span class="sxs-lookup"><span data-stu-id="fa0de-126">Across Business Areas</span></span>](ui-across-business-areas.md)

