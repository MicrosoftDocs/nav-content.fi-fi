---
title: "Toimintaohje: Asiakkaan maksujen ottaminen käyttöön PayPalin kautta"
author: SorenGP
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: HT
ms.sourcegitcommit: 6b60b1344a1e18ad91863046110df880f75f7c04
ms.openlocfilehash: 15f30a03c3e7ccc865ef527a707794c2c6428b2f
ms.contentlocale: fi-fi
ms.lasthandoff: 10/16/2017

---

# <a name="how-to-enable-customer-payments-through-paypal"></a><span data-ttu-id="84065-102">Toimintaohje: Asiakkaan maksujen ottaminen käyttöön PayPalin kautta#</span><span class="sxs-lookup"><span data-stu-id="84065-102">How to: Enable Customer Payments Through PayPal#</span></span>
<span data-ttu-id="84065-103">Pankkisiirron tai luottokorttien lisäksi asiakkaille voi tarjota mahdollisuuden maksaa PayPal-tilin avulla.</span><span class="sxs-lookup"><span data-stu-id="84065-103">As an alternative to collecting payments through bank transfer or credit cards, you can offer your customers to pay you through their PayPal account.</span></span>

<span data-ttu-id="84065-104">Kun asiakas valitsee myyntilaskun tai myyntitilausasiakirjan PayPal-linkin, näyttöön avautuu asiakkaan PayPal-tilin palvelusivu, joka sisältää myyntiä koskevat maksutiedot.</span><span class="sxs-lookup"><span data-stu-id="84065-104">When a customer chooses the PayPal link on a sales invoice or sales order document, the service page for their PayPal account appears showing the payment details for the sale.</span></span> <span data-ttu-id="84065-105">Tämän jälkeen asiakas voi maksaa laskun kuten minkä tahansa PayPal-maksun.</span><span class="sxs-lookup"><span data-stu-id="84065-105">The customer can then pay the invoice as any other PayPal payment.</span></span>

<span data-ttu-id="84065-106">Voit ottaa asiakkaan maksut käyttöön PayPalin kautta seuraavasti:</span><span class="sxs-lookup"><span data-stu-id="84065-106">To enable customer payments through PayPal, you must do the following:</span></span>

1. <span data-ttu-id="84065-107">Määritä PayPal Payments Standard maksupalveluksi **Maksupalvelut**-ikkunassa.</span><span class="sxs-lookup"><span data-stu-id="84065-107">Set up PayPal Payments Standard as a payment service in the **Payments Services** window.</span></span>
2. <span data-ttu-id="84065-108">Valitse kyseisen myyntiasiakirjan **Maksupalvelu**-kentässä PayPal Payments Standard.</span><span class="sxs-lookup"><span data-stu-id="84065-108">Select PayPal Payments Standard in the **Payment Service** field on the sales document in question.</span></span>

<span data-ttu-id="84065-109">PayPal Payments Standard -palvelu asennetaan laajennuksena Dynamics NAV -ohjelmaan. Se on valmis otettavaksi käyttöön.</span><span class="sxs-lookup"><span data-stu-id="84065-109">The PayPal Payments Standard service is installed as an extension to Dynamics NAV and ready to enabled.</span></span> <span data-ttu-id="84065-110">Lisätietoja on kohdassa [Dynamics NAV -ohjelman mukauttaminen laajennusten avulla](ui-extensions.md).</span><span class="sxs-lookup"><span data-stu-id="84065-110">For more information, see [Customizing Dynamics NAV Using Extensions ](ui-extensions.md).</span></span>

## <a name="to-enable-the-paypal-payments-standard-service"></a><span data-ttu-id="84065-111">PayPal Payments Standard -palvelun ottaminen käyttöön</span><span class="sxs-lookup"><span data-stu-id="84065-111">To enable the PayPal Payments Standard service</span></span>
1. <span data-ttu-id="84065-112">Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Maksupalvelut** ja valitse sitten aiheeseen liittyvä linkki.</span><span class="sxs-lookup"><span data-stu-id="84065-112">In the top right corner, choose the **Search for Page or Report** icon, **Payment Services**, and then choose the related link.</span></span>  
2. <span data-ttu-id="84065-113">Valitse **Maksupalvelut**-ikkunassa **Uusi**-toiminto.</span><span class="sxs-lookup"><span data-stu-id="84065-113">In the **Payment Services** window, choose the **New** action.</span></span>
3. <span data-ttu-id="84065-114">Valitse **PayPal Standard** ja sulje ikkuna.</span><span class="sxs-lookup"><span data-stu-id="84065-114">Select **PayPal Standard**, and then close the window.</span></span>
4. <span data-ttu-id="84065-115">Valitse **Maksupalvelut**-ikkunassa **Asetus**-toiminto.</span><span class="sxs-lookup"><span data-stu-id="84065-115">In the **Payment Services** window, choose the **Setup** action.</span></span>
5. <span data-ttu-id="84065-116">Täytä tarvittavat kentät.</span><span class="sxs-lookup"><span data-stu-id="84065-116">Fill in the fields as necessary.</span></span> <span data-ttu-id="84065-117">Lue kentän lyhyt kuvaus valitsemalla kenttä tai siirry lisätietoihin valitsemalla linkki.</span><span class="sxs-lookup"><span data-stu-id="84065-117">Choose a field to read a short description of the field or link to more information.</span></span>

    <span data-ttu-id="84065-118">**Huomautus**: Valitse **Sisällytä aina asiakirjoihin** -valintaruutu, jos haluat, että PayPal-maksupalvelun hyperlinkki on näkyvissä myyntiasiakirjoissa aina silloin, kun maksaminen PayPalin kautta on käytössä.</span><span class="sxs-lookup"><span data-stu-id="84065-118">**Note**: Select the **Always Include on Documents** check box if the hyperlink for the PayPal payment service should always be visible on sales documents where payment through PayPal is enabled.</span></span>

6. <span data-ttu-id="84065-119">Sulje ikkuna.</span><span class="sxs-lookup"><span data-stu-id="84065-119">Close the window.</span></span>

## <a name="to-select-paypal-payments-standard-on-a-sales-invoice"></a><span data-ttu-id="84065-120">PayPal Payments Standardin valitseminen myyntilaskussa</span><span class="sxs-lookup"><span data-stu-id="84065-120">To select PayPal Payments Standard on a sales invoice</span></span>
1. <span data-ttu-id="84065-121">Valitse kotisivun **Myyntilaskut**-kohta.</span><span class="sxs-lookup"><span data-stu-id="84065-121">On the Home page, choose **Sales Invoices**.</span></span>
2. <span data-ttu-id="84065-122">Avaa myyntilasku, jossa haluat ottaa PayPal-maksut käyttöön.</span><span class="sxs-lookup"><span data-stu-id="84065-122">Open the sales invoice that you want to enable PayPal payments for.</span></span>
3. <span data-ttu-id="84065-123">Valitse **Maksupalvelu**-kentässä PayPal Payments Standard.</span><span class="sxs-lookup"><span data-stu-id="84065-123">In the **Payment Service** field, choose PayPal Payments Standard.</span></span>

<span data-ttu-id="84065-124">**Huomautus**: **Maksupalvelu**-kenttä on näkyvissä vain, jos PayPal Payments Standard -palvelu on käytössä.</span><span class="sxs-lookup"><span data-stu-id="84065-124">**Note**: The **Payment Service** field is only visible if the PayPal Payments Standard service is enabled.</span></span>   

## <a name="see-also"></a><span data-ttu-id="84065-125">Katso myös</span><span class="sxs-lookup"><span data-stu-id="84065-125">See Also</span></span>  
[<span data-ttu-id="84065-126">Myynnin määrittäminen</span><span class="sxs-lookup"><span data-stu-id="84065-126">Set Up Sales</span></span>](sales-setup-sales.md)  
[<span data-ttu-id="84065-127">Myynnin hallinta</span><span class="sxs-lookup"><span data-stu-id="84065-127">Manage Sales</span></span>](sales-manage-sales.md)  
[<span data-ttu-id="84065-128">Dynamics NAV -ohjelman mukauttaminen laajennusten avulla</span><span class="sxs-lookup"><span data-stu-id="84065-128">Customizing Dynamics NAV Using Extensions</span></span>](ui-extensions.md)

