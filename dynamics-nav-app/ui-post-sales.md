---
title: Myynnin kirjaaminen
author: SusanneWindfeldPedersen
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 6b60b1344a1e18ad91863046110df880f75f7c04
ms.openlocfilehash: e87dd5faf7713aecfbe7209d00bb8076fcae9d25
ms.contentlocale: fi-fi
ms.lasthandoff: 07/19/2017

---

# <a name="posting-sales"></a><span data-ttu-id="fe526-102">Myynnin kirjaaminen</span><span class="sxs-lookup"><span data-stu-id="fe526-102">Posting Sales</span></span>
<span data-ttu-id="fe526-103">Kun valitset myyntiasiakirjan **Kirjausryhmä**-painikkeen, voit valita seuraavista kirjaustoiminnoista:</span><span class="sxs-lookup"><span data-stu-id="fe526-103">In the **Posting group** on a sales document, you can choose between the following posting functions:</span></span>

- <span data-ttu-id="fe526-104">**Kirjaa**</span><span class="sxs-lookup"><span data-stu-id="fe526-104">**Post**</span></span>
- <span data-ttu-id="fe526-105">**Testiraportti**</span><span class="sxs-lookup"><span data-stu-id="fe526-105">**Test Report**</span></span>
- <span data-ttu-id="fe526-106">**Kirjaa ja lähetä**</span><span class="sxs-lookup"><span data-stu-id="fe526-106">**Post and Send**</span></span>
- <span data-ttu-id="fe526-107">**Kirjaa ja tulosta**</span><span class="sxs-lookup"><span data-stu-id="fe526-107">**Post and Print**</span></span>
- <span data-ttu-id="fe526-108">**Kirjaa ja lähetä sähköpostitse**</span><span class="sxs-lookup"><span data-stu-id="fe526-108">**Post and Email**</span></span>
- <span data-ttu-id="fe526-109">**Kirjaa erä**</span><span class="sxs-lookup"><span data-stu-id="fe526-109">**Post Batch**</span></span>
- <span data-ttu-id="fe526-110">**Esikatsele kirjausta**</span><span class="sxs-lookup"><span data-stu-id="fe526-110">**Preview Posting**</span></span>

<span data-ttu-id="fe526-111">Kun olet täyttänyt kaikki rivit ja syöttänyt kaikki tiedot myyntitilaukseen, voit kirjata sen eli luoda vastaanoton ja laskun.</span><span class="sxs-lookup"><span data-stu-id="fe526-111">When you have completed all the lines and entered all the information on the sales order, you can post it.</span></span> <span data-ttu-id="fe526-112">Tämä luo toimituksen ja laskun.</span><span class="sxs-lookup"><span data-stu-id="fe526-112">This creates a shipment and an invoice.</span></span>

<span data-ttu-id="fe526-113">Kun myyntitilaus on kirjattu, asiakkaan tili, pääkirjanpito ja nimiketapahtumat päivitetään.</span><span class="sxs-lookup"><span data-stu-id="fe526-113">When a sales order is posted, the customer's account, the general ledger, and the item ledger entries are updated.</span></span>

<span data-ttu-id="fe526-114">Jokaiselle myyntitilaukselle luodaan myyntitapahtuma **KP-tapahtuma**-taulukossa.</span><span class="sxs-lookup"><span data-stu-id="fe526-114">For each sales order, a sales entry is created in the **G/L Entry** table.</span></span> <span data-ttu-id="fe526-115">Myös **Toimittajatapahtuma**-taulukon asiakkaan tilille luodaan tapahtuma. Lisäksi luodaan pääkirjanpidon tapahtuma asianmukaiselle myyntisaamistilille.</span><span class="sxs-lookup"><span data-stu-id="fe526-115">An entry is also created in the customer's account in the **Cust. Ledger Entry** table and a general ledger entry is created in the relevant receivables account.</span></span> <span data-ttu-id="fe526-116">Lisäksi tilauksen kirjauksen tuloksena saattaa olla ALV-tapahtuman ja KP-tapahtuman luonti alennussummalle.</span><span class="sxs-lookup"><span data-stu-id="fe526-116">In addition, posting the order may result in a VAT entry and a general ledger entry for the discount amount.</span></span> <span data-ttu-id="fe526-117">Se, kirjataanko alennukselle tapahtuma, määräytyy **Ostojen ja ostovelkojen asetukset** -ikkunan **Alennuksen kirjaus** -kentän sisällön perusteella.</span><span class="sxs-lookup"><span data-stu-id="fe526-117">Whether an entry for the discount is posted depends on the contents of the **Discount Posting** field in the **Sales & Receivables Setup** window.</span></span>

<span data-ttu-id="fe526-118">Jokaiselle myyntitilausriville luodaan nimiketapahtuma **Nimiketapahtuma**-taulukkoon (jos myyntiriveillä on nimikenumeroita) tai pääkirjanpidon tapahtuma **KP-tapahtuma**-taulukkoon (jos myyntiriveillä on pääkirjanpitotili).</span><span class="sxs-lookup"><span data-stu-id="fe526-118">For each sales order line, an item ledger entry will be created in the **Item Ledger Entry** table (if the sales lines contain item numbers) or a general ledger entry will be created in the **G/L Entry** table (if the sales lines contain a general ledger account).</span></span> <span data-ttu-id="fe526-119">Tämän lisäksi myyntitilaukset tallennetaan aina **Lähtevän toimituksen otsikko**- ja **Myyntilaskun otsikko** -taulukoihin.</span><span class="sxs-lookup"><span data-stu-id="fe526-119">In addition to this, sales orders are always recorded in the **Sales Shipment Header** and **Sales Invoice Header** tables.</span></span>

<span data-ttu-id="fe526-120">**Tärkeää**: Kun kirjaat tilauksen, voit luoda sekä toimituksen että laskun.</span><span class="sxs-lookup"><span data-stu-id="fe526-120">**Important**: When you post an order, you can create both a shipment and an invoice.</span></span> <span data-ttu-id="fe526-121">Tämä voidaan tehdä samaan aikaan tai erikseen.</span><span class="sxs-lookup"><span data-stu-id="fe526-121">These can be done at the same time or independently.</span></span> <span data-ttu-id="fe526-122">Voit luoda myös osittaisen toimituksen tai osittaisen laskun täyttämällä **Toimitettava määrä**- ja **Laskutettava määrä** -kentät yksittäisillä myyntitilausriveillä ennen kirjausta.</span><span class="sxs-lookup"><span data-stu-id="fe526-122">You can also create a partial shipment and a partial invoice by completing the **Qty. to Ship** and **Qty. to Invoice** fields on the individual sales order lines before you post.</span></span> <span data-ttu-id="fe526-123">Huomaa, että laskua ei voi luoda jollekin, jota ei ole toimitettu.</span><span class="sxs-lookup"><span data-stu-id="fe526-123">Note that you cannot create an invoice for something that is not shipped.</span></span> <span data-ttu-id="fe526-124">Tämä tarkoittaa sitä, että ennen laskutusta on täytynyt tallentaa toimitus, tai täytyy valita yhtäaikainen toimitus ja laskutus.</span><span class="sxs-lookup"><span data-stu-id="fe526-124">That is, before you can invoice, you must have recorded a shipment, or you must choose to ship and invoice at the same time.</span></span> 

<span data-ttu-id="fe526-125">Kun kirjaus on päättynyt, kirjatut myyntirivit poistuvat tilauksesta.</span><span class="sxs-lookup"><span data-stu-id="fe526-125">When the posting is completed, the posted sales lines are removed from the order.</span></span> <span data-ttu-id="fe526-126">Viesti kertoo, milloin kirjaus on valmis.</span><span class="sxs-lookup"><span data-stu-id="fe526-126">A message tells you when the posting is completed.</span></span> <span data-ttu-id="fe526-127">Tämän jälkeen voit nähdä kirjatut tapahtumat kirjattuja tapahtumia sisältävissä ikkunoissa, kuten **Asiakastapahtumat**-, **KP-tapahtumat**-, **Nimiketapahtumat**-, **Kirjatut myyntitoimitukset**- ja**Kirjatut myyntilaskut** -ikkunassa.</span><span class="sxs-lookup"><span data-stu-id="fe526-127">After this, you will be able to see the posted entries in the various windows that contain posted entries, such as the **Cust. Ledger Entries**, **G/L Entries**, **Item Ledger Entries**, **Posted Sales Shipments**, and **Posted Sales Invoices** windows.</span></span>

## <a name="see-also"></a><span data-ttu-id="fe526-128">Katso myös</span><span class="sxs-lookup"><span data-stu-id="fe526-128">See Also</span></span>
[<span data-ttu-id="fe526-129">Toimintaohje: Asiakirjojen lähettäminen sähköpostitse</span><span class="sxs-lookup"><span data-stu-id="fe526-129">How to: Send Documents by Email</span></span>](ui-how-send-documents-email.md)

