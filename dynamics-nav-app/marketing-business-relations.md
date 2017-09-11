---
title: "Liikesuhteiden määrittäminen kontaktiyrityksissä"
author: jswymer
ms.custom: na
ms.date: 09/16/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 6b60b1344a1e18ad91863046110df880f75f7c04
ms.openlocfilehash: 6616473a00e85e52648713d7e067f4b3b72caecf
ms.contentlocale: fi-fi
ms.lasthandoff: 07/19/2017

---
# <a name="set-up-business-relations-on-contact-companies"></a><span data-ttu-id="643c3-102">Liikesuhteiden määrittäminen kontaktiyrityksissä</span><span class="sxs-lookup"><span data-stu-id="643c3-102">Set Up Business Relations on Contact Companies</span></span>
<span data-ttu-id="643c3-103">Voit käyttää liikesuhteita, kun haluat osoittaa eri kontaktien, kuten prospektin, pankin, konsultin tai palvelun toimittajan, kanssa olevan liikesuhteen.</span><span class="sxs-lookup"><span data-stu-id="643c3-103">You can use business relations to indicate the business relationship you have with your contacts, for example, a prospect, bank, consultant, service supplier, and so on.</span></span>

<span data-ttu-id="643c3-104">Kontaktien liikesuhteiden käyttäminen on kaksivaiheinen prosessi.</span><span class="sxs-lookup"><span data-stu-id="643c3-104">Using business relations on contacts is a two-step process.</span></span> <span data-ttu-id="643c3-105">Ensin määritetään liikesuhteen koodi.</span><span class="sxs-lookup"><span data-stu-id="643c3-105">First, you define the business relation code.</span></span> <span data-ttu-id="643c3-106">Tämä vaihe suoritetaan vain kerran jokaiselle liikesuhteelle.</span><span class="sxs-lookup"><span data-stu-id="643c3-106">You only have to perform this step one time for each business relation.</span></span> <span data-ttu-id="643c3-107">Kun liikesuhteen koodi on määritetty, voit aloittaa koodin liittämisen kontaktiyrityksille.</span><span class="sxs-lookup"><span data-stu-id="643c3-107">Once you have a business relation code, you can start to assign the code to contact companies.</span></span>

<span data-ttu-id="643c3-108">**Huomautus**: Jos aiot synkronisoida kontaktisi ohjelman muissa osissa olevien toimittajien, asiakkaiden tai pankkitilien kanssa, haluat ehkä määrittää niille liikesuhteen.</span><span class="sxs-lookup"><span data-stu-id="643c3-108">**Note**: If you plan to synchronize your contacts with vendors, customers, or bank accounts in other parts of the application, you may want to set up a business relation for them.</span></span>

## <a name="define-a-business-relation-code"></a><span data-ttu-id="643c3-109">Liikesuhteen koodin määrittäminen</span><span class="sxs-lookup"><span data-stu-id="643c3-109">Define a Business Relation Code</span></span>
<span data-ttu-id="643c3-110">Liikesuhteen koodi määrittää liikesuhteen luokan tai tyypin. Se voi olla esimerkiksi PANKKI tai LAKI.</span><span class="sxs-lookup"><span data-stu-id="643c3-110">The business relation code defines a category or type of the business relationship, such as BANK or LAW.</span></span> <span data-ttu-id="643c3-111">Liikesuhteen koodeja voi olla useita.</span><span class="sxs-lookup"><span data-stu-id="643c3-111">You can have several business relation codes.</span></span> <span data-ttu-id="643c3-112">Määritä liikesuhde **Liikesuhteet**-ikkunassa.</span><span class="sxs-lookup"><span data-stu-id="643c3-112">To define the business relation, you use the **Business Relations** window.</span></span>

1. <span data-ttu-id="643c3-113">Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Liikesuhteet** ja valitse sitten aiheeseen liittyvä linkki.</span><span class="sxs-lookup"><span data-stu-id="643c3-113">In the top right corner, choose the **Search for Page or Report** icon, enter **Business Relations**, and then choose the related link.</span></span>
2. <span data-ttu-id="643c3-114">Valitse **Uusi**-toiminto. Täytä sitten koodi ja kuvaus.</span><span class="sxs-lookup"><span data-stu-id="643c3-114">Choose the **New** action, and fill in a code and description.</span></span> <span data-ttu-id="643c3-115">Koodi voi olla enintään 11 merkkiä pitkä. Se voi sisältää numeroita ja kirjaimia.</span><span class="sxs-lookup"><span data-stu-id="643c3-115">The code can be a maximum of 11 characters, and can be any combination of numbers and letters.</span></span>

## <a name="assign-business-relations-to-a-contact"></a><span data-ttu-id="643c3-116">Liikesuhteiden liittäminen kontaktiin</span><span class="sxs-lookup"><span data-stu-id="643c3-116">Assign Business Relations to a Contact</span></span>
<span data-ttu-id="643c3-117">Liikesuhteita ei voi liittää kontaktihenkilöön, vaan ainoastaan yrityksiin.</span><span class="sxs-lookup"><span data-stu-id="643c3-117">You cannot assign business relations to a contact person - only companies.</span></span>

1. <span data-ttu-id="643c3-118">Avaa kontakti.</span><span class="sxs-lookup"><span data-stu-id="643c3-118">Open the contact.</span></span>
2. <span data-ttu-id="643c3-119">Valitse **Yritys**-toiminto ja sitten **Liikesuhteet**-toiminto.</span><span class="sxs-lookup"><span data-stu-id="643c3-119">Choose the **Company** action, and then the **Business Relations** action.</span></span>

    <span data-ttu-id="643c3-120">**Kontaktin liikesuhteet** -ikkuna avautuu.</span><span class="sxs-lookup"><span data-stu-id="643c3-120">The **Contact Business Relations** window opens.</span></span>
3. <span data-ttu-id="643c3-121">Valitse **Liikesuhteen koodi** -kentässä liikesuhde, jonka haluat määrittää.</span><span class="sxs-lookup"><span data-stu-id="643c3-121">In the **Business Relation Code** field, select the business relation you want to assign.</span></span>

<span data-ttu-id="643c3-122">Toista nämä vaiheet ja luo niin monta liikesuhdetta kuin haluat.</span><span class="sxs-lookup"><span data-stu-id="643c3-122">Repeat these steps to assign as many business relations as you want.</span></span> <span data-ttu-id="643c3-123">Voit myös liittää liikesuhteita kontaktiluettelosta saman menettelytavan avulla.</span><span class="sxs-lookup"><span data-stu-id="643c3-123">You can also assign business relations from the contact list by following the same procedure.</span></span>

<span data-ttu-id="643c3-124">Kontaktille liitettyjen liikesuhteiden lukumäärä näkyy **Kontakti**-ikkunan **Segmentointi**-osan **Liikesuhteiden lkm** -kentässä.</span><span class="sxs-lookup"><span data-stu-id="643c3-124">The number of business relations you have assigned to the contact is displayed in the **No. of Business Relations** field in the **Segmentation** section in the **Contact** window.</span></span>

<span data-ttu-id="643c3-125">Kun olet liittänyt liikesuhteita kontakteihisi, voit käyttää näitä tietoja valitessasi kontakteja segmentteihisi.</span><span class="sxs-lookup"><span data-stu-id="643c3-125">After you have assigned business relations to your contacts, you can use this information to select contacts for your segments.</span></span> <span data-ttu-id="643c3-126">Lisätietoja on kohdassa [Toimintaohje: Kontaktien lisääminen segmentteihin](marketing-add-contact-segment.md).</span><span class="sxs-lookup"><span data-stu-id="643c3-126">For more information, see [How to: Add Contacts to Segments](marketing-add-contact-segment.md).</span></span>

##<a name="see-also"></a><span data-ttu-id="643c3-127">Katso myös</span><span class="sxs-lookup"><span data-stu-id="643c3-127">See Also</span></span>
[<span data-ttu-id="643c3-128">Kontaktiyritysten luominen</span><span class="sxs-lookup"><span data-stu-id="643c3-128">Create Contact Companies</span></span>](marketing-create-contact-companies.md)

