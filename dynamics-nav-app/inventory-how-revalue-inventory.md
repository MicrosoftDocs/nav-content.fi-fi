<properties
                pageTitle="Toimintaohje: Varaston uudelleenarvostus| Dynamics NAV"
                description="Tässä artikkelissa kerrotaan, miten vähintään yhden varaston nimikkeen arvoa nostetaan tai lasketaan kirjaamalla nimikkeen nykyinen laskettu arvo."
                services="project-madeira"
                documentationCenter=""
                authors="SorenGP"
/>
<tags
    ms.service="project-madeira"
    ms.topic="article"
    ms.devlang="na"
    ms.tgt_pltfrm="na"
    ms.workload="na"
    ms.date="11/07/2016"
    ms.author="SorenGP" />


# <a name="how-to-revalue-inventory"></a><span data-ttu-id="4b1b2-103">Toimintaohje: Varaston uudelleenarvostus</span><span class="sxs-lookup"><span data-stu-id="4b1b2-103">How to: Revalue Inventory</span></span>   
<span data-ttu-id="4b1b2-104">Jos haluat nostaa tai laskea nimikkeen tai tietyn nimiketapahtuman varastoarvoa, sinun tulee käyttää uudelleenarvostuspäiväkirjaa.</span><span class="sxs-lookup"><span data-stu-id="4b1b2-104">If you want to appreciate or depreciate an item or a specific item ledger entry, you must use the revaluation journal.</span></span>

## <a name="to-revalue-inventory"></a><span data-ttu-id="4b1b2-105">Varaston uudelleenarvostus</span><span class="sxs-lookup"><span data-stu-id="4b1b2-105">To revalue inventory</span></span>
1. <span data-ttu-id="4b1b2-106">Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Uudelleenarvostus pvk** ja valitse sitten aiheeseen liittyvä linkki.</span><span class="sxs-lookup"><span data-stu-id="4b1b2-106">In the top right corner, choose the **Search for Page or Report** icon, enter **Revaluation Journal**, and then choose the related link.</span></span>
2. <span data-ttu-id="4b1b2-107">Valitse **Laske varaston arvo** -toiminto.</span><span class="sxs-lookup"><span data-stu-id="4b1b2-107">Choose the **Calculate Inventory Value** action.</span></span>
3. <span data-ttu-id="4b1b2-108">Täytä **Laske varaston arvo** -ikkunassa tarvittavat kentät.</span><span class="sxs-lookup"><span data-stu-id="4b1b2-108">In the **Calculate Inventory Value** window, fill in the fields as necessary.</span></span> <span data-ttu-id="4b1b2-109">Lue kentän lyhyt kuvaus valitsemalla kenttä tai siirry lisätietoihin valitsemalla linkki.</span><span class="sxs-lookup"><span data-stu-id="4b1b2-109">Choose a field to read a short description of the field or link to more information.</span></span>
4. <span data-ttu-id="4b1b2-110">Valitse **OK**-painike.</span><span class="sxs-lookup"><span data-stu-id="4b1b2-110">Choose the **OK** button.</span></span>
5. <span data-ttu-id="4b1b2-111">Syötä uusi yksikkökustannus **Uudelleenarvostus pvk** -ikkunan kuhunkin **Yks.kust. (uudelleenarvostet.)** -kenttään.</span><span class="sxs-lookup"><span data-stu-id="4b1b2-111">On each line in the **Revaluation Journal** window, in the **Unit Cost (Revalued)** field, enter the new unit cost.</span></span> <span data-ttu-id="4b1b2-112">Vaihtoehtoisesti voit syöttää uuden kokonaissumman **Var. arvo (uudell.arvostettu)** -kenttään.</span><span class="sxs-lookup"><span data-stu-id="4b1b2-112">Alternatively, enter the new total amount in the **Inventory Value (Revalued)** field.</span></span>

    <span data-ttu-id="4b1b2-113">Asianmukaiset kentät päivitetään automaattisesti.</span><span class="sxs-lookup"><span data-stu-id="4b1b2-113">The relevant fields are automatically updated.</span></span> <span data-ttu-id="4b1b2-114">Huomaa että **Summa**-kentässä on varaston arvon todellinen muutos valitun nimiketapahtuman osalta.</span><span class="sxs-lookup"><span data-stu-id="4b1b2-114">Note that the **Amount** field shows the actual change in inventory value for the selected item ledger entry.</span></span> <span data-ttu-id="4b1b2-115">Ohjelma laskee **Varaston arvo (laskettu)** -kentän ja **Var. arvo (uudell.arvostettu)** -kentän erotuksen.</span><span class="sxs-lookup"><span data-stu-id="4b1b2-115">It calculates the difference between the **Inventory Value (Calculated)** field and the **Inventory Value (Revalued)** field.</span></span>

6. <span data-ttu-id="4b1b2-116">Kun olet saanut kaikki uudelleenarvostuspäiväkirjan rivit valmiiksi, valitse **Kirjaa**-toiminto.</span><span class="sxs-lookup"><span data-stu-id="4b1b2-116">When you have completed all lines in the revaluation journal, choose the **Post** action.</span></span>

<span data-ttu-id="4b1b2-117">Kirjaamiasi uudelleenarvostuksia vastaavat uudet arvotapahtumat on nyt luotu.</span><span class="sxs-lookup"><span data-stu-id="4b1b2-117">New value entries are now created to reflect the revaluations that you have posted.</span></span> <span data-ttu-id="4b1b2-118">Uudet arvot näkyvät vastaavissa nimikekorteissa.</span><span class="sxs-lookup"><span data-stu-id="4b1b2-118">You can see the new values on the respective item cards.</span></span>

## <a name="see-also"></a><span data-ttu-id="4b1b2-119">Katso myös</span><span class="sxs-lookup"><span data-stu-id="4b1b2-119">See Also</span></span>
[<span data-ttu-id="4b1b2-120">Varaston hallinta</span><span class="sxs-lookup"><span data-stu-id="4b1b2-120">Manage Inventory</span></span>](inventory-manage-inventory.md)  
[<span data-ttu-id="4b1b2-121">Myynnin hallinta</span><span class="sxs-lookup"><span data-stu-id="4b1b2-121">Manage Sales</span></span>](sales-manage-sales.md)  
[<span data-ttu-id="4b1b2-122">Ostojen hallinta</span><span class="sxs-lookup"><span data-stu-id="4b1b2-122">Manage Purchasing</span></span>](purchasing-manage-purchasing.md)  
[<span data-ttu-id="4b1b2-123">Dynamics NAV -ohjelman käyttäminen</span><span class="sxs-lookup"><span data-stu-id="4b1b2-123">Work With Dynamics NAV</span></span>](ui-work-product.md)
