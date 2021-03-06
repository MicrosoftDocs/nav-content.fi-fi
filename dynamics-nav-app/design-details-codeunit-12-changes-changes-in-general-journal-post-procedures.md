---
title: "Rakennetiedot - koodiyksikön 12 muutokset päiväkirjakirjausten menettelytavoissa"
description: "Seuraavat muutokset on toteutettu tässä [!INCLUDE[d365fin](includes/d365fin_md.md)] -versiossa."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 07/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 19bbc6eb4939fa7f4e0180a62b03998cd2f386b6
ms.contentlocale: fi-fi
ms.lasthandoff: 10/16/2017

---
# <a name="codeunit-12-changes-changes-in-general-journal-post-procedures"></a>Koodiyksikön 12 muutokset: Päiväkirjakirjausten menettelytapojen muutokset
Seuraavat muutokset on toteutettu tässä [!INCLUDE[d365fin](includes/d365fin_md.md)] -versiossa.  

|**Microsoft Dynamics NAV 2009 R2**|**Microsoft Dynamics NAV 2013 R2**|**Kommentti**|  
|----------------------------------------|----------------------------------------|-----------------|  
|GetGLReg|GetGLReg|Päivitetty|  
|RunWithCheck|RunWithCheck|Päivitetty|  
|RunWithoutCheck|RunWithoutCheck|Päivitetty|  
|Code|Code|Päivitetty|  
||PostGenJnlLine|Lisätty|  
||InitAmounts|Lisätty|  
||InitLastDocDate|Lisätty|  
|InitVAT|InitVAT|Päivitetty|  
|PostVAT|PostVAT|Päivitetty|  
|InsertVAT|InsertVAT|Päivitetty|  
|SummarizeVAT|SummarizeVAT|Päivitetty|  
|InsertSummarizedVAT|InsertSummarizedVAT|Päivitetty|  
|PostGLAcc|PostGLAcc|Päivitetty|  
|PostCust|PostCust|Päivitetty|  
|PostVend|PostVend|Päivitetty|  
|PostBankAcc|PostBankAcc|Päivitetty|  
|PostFixedAsset|PostFixedAsset|Päivitetty|  
|PostICPartner|PostICPartner|Päivitetty|  
|InitCodeUnit|StartPosting|Päivitetty|  
||ContinuePosting|Lisätty|  
|FinishCodeunit|FinishPosting|Päivitetty|  
||PostUnrealizedVAT|Lisätty|  
||CheckPostUnrealizedVAT|Lisätty|  
||ExchangeAccounts|Lisätty|  
|InitGLEntry|InitGLEntry|Päivitetty|  
||InitGLEntryVAT|Lisätty|  
||InitGLEntryVATCopy|Lisätty|  
|InsertGLEntry|InsertGLEntry|Päivitetty|  
||CreateGLEntry|Lisätty|  
||CreateGLEntryBalAcc|Lisätty|  
||CreateGLEntryVAT|Lisätty|  
||CreateGLEntryVATCollectAdj|Lisätty|  
||CreateGLEntryFromVATEntry|Lisätty|  
||UpdateCheckAmounts|Lisätty|  
|ApplyCustLedgEntry|ApplyCustLedgEntry|Päivitetty|  
||CalcPmtDiscPossible|Lisätty|  
||CalcPmtTolerancePossible|Lisätty|  
|CalcPmtTolerance|CalcPmtTolerance|Päivitetty|  
|CalcPmtDisc|CalcPmtDisc|Päivitetty|  
|CalcPmtDiscIfAdjVAT|CalcPmtDiscIfAdjVAT|Päivitetty|  
|CalcPmtDiscTolerance|CalcPmtDiscTolerance|Päivitetty|  
||CalcPmtDiscVATBases|Lisätty|  
||CalcPmtDiscVATAmounts|Lisätty|  
||InsertPmtDiscVATForGLEntry|Lisätty|  
||InsertPmtDiscVATForGLEntry|Lisätty|  
|CalcCurrencyApplnRounding|CalcCurrencyApplnRounding|Päivitetty|  
|FindAmtForAppln|FindAmtForAppln|Päivitetty|  
|CalcCurrencyUnrealizedGainLoss|CalcCurrencyUnrealizedGainLoss|Päivitetty|  
|CalcCurrencyRealizedGainLoss|CalcCurrencyRealizedGainLoss|Päivitetty|  
|CalcApplication|CalcApplication|Päivitetty|  
|CalcRemainingPmtDisc|CalcRemainingPmtDisc|Siirretty koodiyksikön 426 maksutoleranssin hallinta|  
|CalcAmtLCYAdjustment|CalcAmtLCYAdjustment|Lisätty|  
|InitNewCVLedgEntry|InitFromGenJnlLine|Siirretty taulukkoon 383 Yks.koht. CV-tapaht. puskuri|  
|InitOldCVLedgEntry|CopyFromCVLedgEntryBuf|Siirretty taulukkoon 383 Yks.koht. CV-tapaht. puskuri|  
|InsertDtldCustLedgEntry|InsertDtldCustLedgEntry|Siirretty taulukkoon 383 Yks.koht. CV-tapaht. puskuri|  
||InitBankAccLedgEntry|Lisätty|  
||InitCheckLedgEntry|Lisätty|  
||InitCustLedgEntry|Lisätty|  
||InitVendLedgEntry|Lisätty|  
||InsertDtldCustLedgEntry|Lisätty|  
||InsertDtldVendLedgEntry|Lisätty|  
|CustUnrealizedVAT|CustUnrealizedVAT|Päivitetty|  
|CustPostApplyCustLedgEntry|CustPostApplyCustLedgEntry|Päivitetty|  
||PrepareTempCustLedgEntry|Lisätty|  
|UnapplyCustLedgEntry|UnapplyCustLedgEntry|Päivitetty|  
|TransferCustLedgEntry|CopyFromGenJnlLine|Siirretty taulukkoon 21 Asiakastapahtuma|  
|PostDtldCustLedgEntries|PostDtldCustLedgEntries|Päivitetty|  
||PostDtldCustLedgEntry|Lisätty|  
||PostDtldCustLedgEntryUnapply|Lisätty|  
||GetDtldCustLedgEntryAccNo|Lisätty|  
|ZeroTransNoDtldCustLedgEntries|SetZeroTransNo|Siirretty taulukkoon 379 Yksit.kohtainen as.tapahtuma|  
|AutoEntrForDtldCustLedgEntries||Refactored to PostDtldCustLedgEntryUnapply|  
|CustUpdateDebitCredit|UpdateDebitCredit|Siirretty taulukkoon 379 Yksit.kohtainen as.tapahtuma|  
|ApplyVendLedgEntry|ApplyVendLedgEntry|Päivitetty|  
||PrepareTempVendLedgEntry|Lisätty|  
|VendPostApplyVendLedgEntry|VendPostApplyVendLedgEntry|Päivitetty|  
|UnapplyVendLedgEntry|UnapplyVendLedgEntry|Päivitetty|  
|TransferVendLedgEntry|CopyFromGenJnlLine|Siirretty taulukkoon 25 Toimittajatapahtuma|  
|PostDtldVendLedgEntries|PostDtldVendLedgEntries|Päivitetty|  
||PostDtldVendLedgEntry|Lisätty|  
||PostDtldVendLedgEntryUnapply|Lisätty|  
||GetDtldVendLedgEntryAccNo|Lisätty|  
||PostDtldCVLedgEntry|Lisätty|  
||PostDtldCustVATAdjustment|Lisätty|  
||PostDtldVendVATAdjustment|Lisätty|  
|ZeroTransNoDtldVendLedgEntries|SetZeroTransNo|Siirretty taulukkoon 380 Yks.koht. toimit. tapahtuma|  
|AutoEntrForDtldVendLedgEntries||Refactored to PostDtldVendLedgEntryUnapply|  
|VendUpdateDebitCredit|UpdateDebitCredit|Siirretty taulukkoon 380 Yks.koht. toimit. tapahtuma|  
|VendUnrealizedVAT|VendUnrealizedVAT|Päivitetty|  
||PostUnrealVATEntry|Lisätty|  
||PostApply|Lisätty|  
|PostUnrealVATByUnapply|PostUnrealVATByUnapply|Päivitetty|  
||PostUnapply|Lisätty|  
||InsertDtldCustLedgEntry|Lisätty|  
||InsertDtldVendLedgEntryUnapply|Lisätty|  
||InsertTempVATEntry|Lisätty|  
||ProcessTempVATEntry|Lisätty|  
||UpdateCustLedgEntry|Lisätty|  
||UpdateVendLedgEntry|Lisätty|  
|UpdateCalcInterest|UpdateCalcInterest|Päivitetty|  
|UpdateCalcInterest2|UpdateCalcInterest2|Päivitetty|  
|GLCalcAddCurrency|GLCalcAddCurrency|Päivitetty|  
|HandleAddCurrResidualGLEntry|HandleAddCurrResidualGLEntry|Päivitetty|  
|CalcLCYToAddCurr|CalcLCYToAddCurr|Päivitetty|  
|CalcAddCurrFactor||Poistettu|  
|GetCurrencyExchRate|GetCurrencyExchRate|Päivitetty|  
|ExchAmount|ExchangeAmount|Siirretty taulukkoon 330 Valuutan vaihtokurssi|  
|ExchangeAmtLCYToFCY2|ExchangeAmtLCYToFCY2|Päivitetty|  
|CalcAddCurrForUnapplication|CalcAddCurrForUnapplication|Päivitetty|  
|CheckNonAddCurrCodeOccurred|CheckNonAddCurrCodeOccurred|Päivitetty|  
|CheckCalcPmtDisc||Siirretty koodiyksikön 426 maksutoleranssin hallinta|  
|CheckCalcPmtDiscCVCust||Siirretty koodiyksikön 426 maksutoleranssin hallinta|  
|CheckCalcPmtDiscCust||Siirretty koodiyksikön 426 maksutoleranssin hallinta|  
|CheckCalcPmtDiscGenJnlCust||Siirretty koodiyksikön 426 maksutoleranssin hallinta|  
|CheckCalcPmtDiscCVVend||Siirretty koodiyksikön 426 maksutoleranssin hallinta|  
|CheckCalcPmtDiscVend||Siirretty koodiyksikön 426 maksutoleranssin hallinta|  
|CheckCalcPmtDiscGenJnlVend||Siirretty koodiyksikön 426 maksutoleranssin hallinta|  
|Reverse|Reverse|Siirretty koodiyksikköön 17 yleinen päiväkirja - käänteinen kirjaus|  
|ReverseCustLedgEntry|ReverseCustLedgEntry|Siirretty koodiyksikköön 17 yleinen päiväkirja - käänteinen kirjaus|  
|ReverseCustLedgEntry|ReverseCustLedgEntry|Siirretty koodiyksikköön 17 yleinen päiväkirja - käänteinen kirjaus|  
|ReverseBankAccLedgEntry|ReverseBankAccLedgEntry|Siirretty koodiyksikköön 17 yleinen päiväkirja - käänteinen kirjaus|  
|ReverseVAT|ReverseVAT|Siirretty koodiyksikköön 17 yleinen päiväkirja - käänteinen kirjaus|  
|SetReversalDescription|SetReversalDescription|Siirretty koodiyksikköön 17 yleinen päiväkirja - käänteinen kirjaus|  
|ApplyCustLedgEntryByReversal|ApplyCustLedgEntryByReversal|Siirretty koodiyksikköön 17 yleinen päiväkirja - käänteinen kirjaus|  
|ApplyVendLedgEntryByReversal|ApplyVendLedgEntryByReversal|Siirretty koodiyksikköön 17 yleinen päiväkirja - käänteinen kirjaus|  
|PostPmtDiscountVATByUnapply|PostPmtDiscountVATByUnapply|Siirretty koodiyksikköön 17 yleinen päiväkirja - käänteinen kirjaus|  
||CheckDimComb|Lisätty koodiyksikköön 17 yleinen päiväkirja - käänteinen kirjaus|  
||CopyCustLedgEntry|Lisätty koodiyksikköön 17 yleinen päiväkirja - käänteinen kirjaus|  
||CopyVendLedgEntry|Lisätty koodiyksikköön 17 yleinen päiväkirja - käänteinen kirjaus|  
||CopyBankAccLedgEntry|Lisätty koodiyksikköön 17 yleinen päiväkirja - käänteinen kirjaus|  
|HandlDtlAddjustment|HandleDtldAdjustment|Päivitetty|  
|CollectAddjustment|CollectAdjustment|Päivitetty|  
|SetOverDimErr|SetOverDimErr|Päivitetty|  
|PostJob|PostJob|Päivitetty|  
|InsertVATEntriesFromTemp|InsertVATEntriesFromTemp|Päivitetty|  
|CaptureOrRefundCreditCardPmnt|CaptureOrRefundCreditCardPmnt|Päivitetty|  
|UpdateDOPaymentTransactEntry|UpdateDOPaymentTransactEntry|Päivitetty|  
|ABSMin|ABSMin|Päivitetty|  
|GetApplnRoundPrecision|GetApplnRoundPrecision|Päivitetty|  
|CheckDimValueForDisposal|CheckDimValueForDisposal|Päivitetty|  
|CalculateCurrentBalance|CalculateCurrentBalance|Päivitetty|  
|IncludeVATAmount||Siirretty taulukkoon 81 Yleisen päiväkirjan rivi|  
|CalcVATAmountFromVATEntry|CalcVATAmountFromVATEntry|Päivitetty|  
||TotalVATAmountOnJnlLines|Lisätty|  
||SetGLRegReverse|Lisätty|  
||GetGLSetup|Lisätty|  
||ReadGLSetup|Lisätty|  
||CheckSalesExtDocNo|Lisätty|  
||CheckPurchExtDocNo|Lisätty|  
||CheckGLAccDimError|Lisätty|  
||GetCurrency|Lisätty|  
||PostDtldAdjustment|Lisätty|  
||GetNextEntryNo|Lisätty|  
||GetNextTransactionNo|Lisätty|  
||GetNextVATEntryNo|Lisätty|  
||IncrNextVATEntryNo|Lisätty|  
||IsNotPayment|Lisätty|  
||IsTempGLEntryBufEmpty|Lisätty|  
||IsVATAdjustment|Lisätty|  
||IsVATExcluded|Lisätty|  
||UpdateDimensions|Lisätty|  
||UpdateDimensionsFromCustLedgEntry|Lisätty|  
||UpdateDimensionsFromVendLedgEntry|Lisätty|  
||UpdateTotalAmounts|Lisätty|  
||CreateGLEntriesForTotalAmounts|Lisätty|  

## <a name="see-also"></a>Katso myös  
 [Rakennetiedot: Koodiyksikön 12 muutokset: Yleisten muuttujien linkitys yleisen päiväkirjan kirjausriviin](design-details-codeunit-12-changes-mapping-global-variables-for-general-journal-post-line.md)

