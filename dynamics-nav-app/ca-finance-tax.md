---
title: "Kanadan arvonlisävero"
author: edupont04
ms.custom: na
ms.date: 09/21/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: c032a02b545441b927ef5c4facc9f77731f37ab7
ms.contentlocale: fi-fi
ms.lasthandoff: 06/26/2017

---

# <a name="sales-tax-and-goods-and-services-tax-in-canada"></a><span data-ttu-id="8b719-102">Kanadan arvonlisävero</span><span class="sxs-lookup"><span data-stu-id="8b719-102">Sales Tax and Goods and Services Tax in Canada</span></span>
<span data-ttu-id="8b719-103">Jos Kanadassa toimittajalla ei ole liiketilaa provinssissa, jossa ostoja tehdään, toimittaja veloittaa vain arvonlisäveroa (GST) tai harmonisoitua arvonlisäveroa (HST).</span><span class="sxs-lookup"><span data-stu-id="8b719-103">In Canada, when a vendor does not have a business presence in the province in which purchases are made, the vendor will charge the Goods and Services Tax (GST) or Harmonized Sales Tax (HST) only.</span></span> <span data-ttu-id="8b719-104">Jos provinssissa on käytössä provinssin arvonlisävero (PST), ostajan on laskettava myös PST ja maksettava se suoraan provinssiin.</span><span class="sxs-lookup"><span data-stu-id="8b719-104">However, if the province has a Provincial Sales Tax (PST), then the purchaser must still calculate the PST and pay it directly to the province.</span></span> <span data-ttu-id="8b719-105">Kun provinssin veroaluekoodi on valittuna, Dynamics NAV käyttää sitä PST:n laskemisessa ja kirjaa sen. Tällöin verovelkaa on sekä pääkirjanpidossa että arvonlisäverotietueissa.</span><span class="sxs-lookup"><span data-stu-id="8b719-105">When a Provincial Tax Area Code is selected, Dynamics NAV uses it to calculate the PST and post it so that there is a tax liability in both the general ledger and the tax entry records.</span></span> <span data-ttu-id="8b719-106">Tämän vuoksi valitun veroaluekoodin tulee olla se, jossa on valittuna PST, ei GST.</span><span class="sxs-lookup"><span data-stu-id="8b719-106">Therefore, the tax area code selected here should be one where only the PST is included, not the GST.</span></span>  
<span data-ttu-id="8b719-107">Lisätietoja on kohdassa [Kanadan arvonlisävero ja veroryhmät](us-finance-setup-sales-tax.md).</span><span class="sxs-lookup"><span data-stu-id="8b719-107">For more information about sales tax, see [Sales Tax and Tax Groups in the US and Canada](us-finance-setup-sales-tax.md).</span></span>  

## <a name="submitting-the-gsthst-file"></a><span data-ttu-id="8b719-108">GST-/HST-tiedoston lähettäminen</span><span class="sxs-lookup"><span data-stu-id="8b719-108">Submitting the GST/HST File</span></span>
<span data-ttu-id="8b719-109">Ostoasiakirjojen verotietoja käytetään veroviranomaisille annettavan GST-/HST-internet-tiedoston siirron luomisessa.</span><span class="sxs-lookup"><span data-stu-id="8b719-109">The tax information in purchase documents is used to generate a GST/HST internet file transfer that you must  provided to the tax authorities.</span></span> <span data-ttu-id="8b719-110">Tämä tiedosto sisältää arvonlisäveron (GST) ja harmonisoidun arvonlisäveron (HST).</span><span class="sxs-lookup"><span data-stu-id="8b719-110">This file includes goods and services tax (GST) and harmonized sales tax (HST).</span></span> <span data-ttu-id="8b719-111">Tiedosto on luotu .tax-muodossa, joka voidaan siirtää internetin kautta.</span><span class="sxs-lookup"><span data-stu-id="8b719-111">The file is created in a .tax file format, which can be transferred via the internet.</span></span>  

## <a name="see-also"></a><span data-ttu-id="8b719-112">Katso myös</span><span class="sxs-lookup"><span data-stu-id="8b719-112">See Also</span></span>
[<span data-ttu-id="8b719-113">Rahoitus</span><span class="sxs-lookup"><span data-stu-id="8b719-113">Finance</span></span>](finance-setup.md)  
[<span data-ttu-id="8b719-114">Rahoituksen määrittäminen</span><span class="sxs-lookup"><span data-stu-id="8b719-114">Set Up Finance</span></span>](finance-setup-setup-finance-setup.md)  
[<span data-ttu-id="8b719-115">Yhdysvaltojen ja Kanadan arvonlisävero ja veroryhmät</span><span class="sxs-lookup"><span data-stu-id="8b719-115">Sales Tax and Tax Groups in the US and Canada</span></span>](us-finance-setup-sales-tax.md)

