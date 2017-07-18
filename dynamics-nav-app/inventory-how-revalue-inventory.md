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


# <a name="how-to-revalue-inventory"></a>Toimintaohje: Varaston uudelleenarvostus   
Jos haluat nostaa tai laskea nimikkeen tai tietyn nimiketapahtuman varastoarvoa, sinun tulee käyttää uudelleenarvostuspäiväkirjaa.

## <a name="to-revalue-inventory"></a>Varaston uudelleenarvostus
1. Valitse oikeassa yläkulmassa oleva **Etsi sivu tai raportti** -kuvake, syötä **Uudelleenarvostus pvk** ja valitse sitten aiheeseen liittyvä linkki.
2. Valitse **Laske varaston arvo** -toiminto.
3. Täytä **Laske varaston arvo** -ikkunassa tarvittavat kentät. Lue kentän lyhyt kuvaus valitsemalla kenttä tai siirry lisätietoihin valitsemalla linkki.
4. Valitse **OK**-painike.
5. Syötä uusi yksikkökustannus **Uudelleenarvostus pvk** -ikkunan kuhunkin **Yks.kust. (uudelleenarvostet.)** -kenttään. Vaihtoehtoisesti voit syöttää uuden kokonaissumman **Var. arvo (uudell.arvostettu)** -kenttään.

    Asianmukaiset kentät päivitetään automaattisesti. Huomaa että **Summa**-kentässä on varaston arvon todellinen muutos valitun nimiketapahtuman osalta. Ohjelma laskee **Varaston arvo (laskettu)** -kentän ja **Var. arvo (uudell.arvostettu)** -kentän erotuksen.

6. Kun olet saanut kaikki uudelleenarvostuspäiväkirjan rivit valmiiksi, valitse **Kirjaa**-toiminto.

Kirjaamiasi uudelleenarvostuksia vastaavat uudet arvotapahtumat on nyt luotu. Uudet arvot näkyvät vastaavissa nimikekorteissa.

## <a name="see-also"></a>Katso myös
[Varaston hallinta](inventory-manage-inventory.md)  
[Myynnin hallinta](sales-manage-sales.md)  
[Ostojen hallinta](purchasing-manage-purchasing.md)  
[Dynamics NAV -ohjelman käyttäminen](ui-work-product.md)

