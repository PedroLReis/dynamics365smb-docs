---
title: "How to: Create Remittance Accounts"
ms.custom: na
ms.date: "06-05-2016"
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: "article"
helpviewer_keywords: 
  - "remittance, accounts"
ms.assetid: 2cfc3021-4518-498f-a601-5c2aac585f9e
caps.latest.revision: 2
ms.author: "edupont"
translation.priority.ht: 
  - "nb-no"
---
# How to: Create Remittance Accounts
You must create one remittance account for each bank account where payment is made. If an account is used to make payments to both domestic and foreign vendors, this account must be created two times—one time for domestic payments and one time for foreign payments.  
  
> [!NOTE]  
>  The currency used for the bank account should be the same as the currency that the bank is using for this account. Exchange rates are based on the currency of the account and calculations are based on this currency.  
  
### To create a remittance account  
  
1.  In the **Search** box, enter **Remittance Account Overview**, and then choose the related link.  
  
2.  On the **Home** tab, in the **New** group, choose **New**.  
  
3.  In the **\($ T\_15000003 Remittance Account Card $\)** window, on the **General** FastTab, fill in the fields as described in the following table.  
  
    |[!INCLUDE[bp_tablefield](../../ApplicationDesign/includes/bp_tablefield_md.md)]|[!INCLUDE[bp_tabledescription](../../ApplicationDesign/includes/bp_tabledescription_md.md)]|  
    |---------------------------------|---------------------------------------|  
    |**\($ T\_15000003\_1 Code $\)**|Specify the identification code for the account.|  
    |**\($ T\_15000003\_2 Remittance Agreement Code $\)**|Select the agreement to which the account is connected.|  
    |**\($ T\_15000003\_14 Type $\)**|Select the payment type. Payment types include **Domestic**, **Foreign**, and **Payment Instr**.<br /><br /> If remitting to Bankernes Betalingssentral \(BBS\), you can only choose **Domestic**.|  
    |**\($ T\_15000003\_5 Description $\)**|Specify the description of the account.|  
    |**\($ T\_15000003\_22 Bank Account No. $\)**|Specify the account number of the bank.|  
    |**\($ T\_15000003\_21 BBS Agreement ID $\)**|Specify the agreement identification for each account in BBS.|  
  
4.  On the **Finance** FastTab, fill in the fields as described in the following table.  
  
    |[!INCLUDE[bp_tablefield](../../ApplicationDesign/includes/bp_tablefield_md.md)]|[!INCLUDE[bp_tabledescription](../../ApplicationDesign/includes/bp_tabledescription_md.md)]|  
    |---------------------------------|---------------------------------------|  
    |**\($ T\_15000003\_27 Account Type $\)**|Select the account type. Account types include **Finance account** and **Bank account**.|  
    |**\($ T\_15000003\_25 Account No. $\)**|Specify the account number depending on your selection in the **\($ T\_15000003\_27 Account Type $\)** field.|  
    |**\($ T\_15000003\_54 Charge Account No. $\)**|Specify the account number for the charge account.|  
    |**\($ T\_15000003\_55 Round off\/Divergence Acc. No. $\)**|Specify the finance account to post the difference as a result of rounding.|  
    |**\($ T\_15000003\_56 Max. Round off\/Diverg. \(LCY\) $\)**|Specify the maximum rounding or difference, which is accepted by settlement return.|  
    |**\($ T\_15000003\_26 Document No. Series $\)**|Specify the number series to be used when you post payments by using the remittance system.|  
    |**\($ T\_15000003\_28 New Document Per. $\)**|Select how documents will be numbered when you post a payment:<br /><br /> -   **Date** \- A new document is numbered according to the date the payment is made.<br />-   **Vendor** \- A new document is numbered according to the vendor.|  
    |**\($ T\_15000003\_29 Return Journal Template Name $\)**|Specify the general journal template to which settled payments are transferred.|  
    |**\($ T\_15000003\_30 Return Journal Name $\)**|Specify the general journal batch to which settled payments are transferred.|  
  
5.  On the **Domestic** FastTab, fill in the fields as described in the following table.  
  
    |[!INCLUDE[bp_tablefield](../../ApplicationDesign/includes/bp_tablefield_md.md)]|[!INCLUDE[bp_tabledescription](../../ApplicationDesign/includes/bp_tabledescription_md.md)]|  
    |---------------------------------|---------------------------------------|  
    |**\($ T\_15000003\_40 Recipient ref. 1\- Invoice $\)**|Specify the text that will print on the payment invoice.|  
    |**\($ T\_15000003\_41 Recipient ref. 1\- Cr. Memo $\)**|Specify the text that will print on the payment invoice when deducting a credit memo.|  
  
6.  On the **Foreign** FastTab, fill in the fields as described in the following table.  
  
     This information is only used if the account is used for foreign payments. For remittance to BBS, do not use this tab.  
  
    |[!INCLUDE[bp_tablefield](../../ApplicationDesign/includes/bp_tablefield_md.md)]|[!INCLUDE[bp_tabledescription](../../ApplicationDesign/includes/bp_tabledescription_md.md)]|  
    |---------------------------------|---------------------------------------|  
    |**\($ T\_15000003\_52 Currency Code $\)**|Specify the currency that is used for the bank account.<br /><br /> If the account is a currency account, the currency code must be given.|  
    |**\($ T\_15000003\_51 Recipient Ref. Aboard $\)**|Specify the template text that displays on the vendor card. This field is for foreign payments only.|  
    |**\($ T\_15000003\_46 Futures Contract No. $\)**|Specify the number of the futures contract, if the transaction is linked to a futures contract.|  
    |**\($ T\_15000003\_47 Futures Contract Exch. Rate $\)**|Specify the exchange rate for the futures contract.|  
  
7.  Choose the **OK** button.  
  
## See Also  
 [Electronic Payments to Vendors in Norway](../../LocalFunctionalityForMicrosoftDynamicsNav2016/Norway/electronic-payments-to-vendors-in-norway.md)   
 [How to: Set Up Remittance Agreements](../../LocalFunctionalityForMicrosoftDynamicsNav2016/Norway/how-to-set-up-remittance-agreements.md)   
 [How to: Set Up Vendors for Remittance](../../LocalFunctionalityForMicrosoftDynamicsNav2016/Norway/how-to-set-up-vendors-for-remittance.md)   
 [Recipient Reference Codes](../../LocalFunctionalityForMicrosoftDynamicsNav2016/Norway/recipient-reference-codes.md)   
 [How to: Create Remittance Suggestions](../../LocalFunctionalityForMicrosoftDynamicsNav2016/Norway/how-to-create-remittance-suggestions.md)   
 [How to: Create Manual Remittance Payments](../../LocalFunctionalityForMicrosoftDynamicsNav2016/Norway/how-to-create-manual-remittance-payments.md)   
 [How to: Set Up Payment Line Information](../../LocalFunctionalityForMicrosoftDynamicsNav2016/Norway/how-to-set-up-payment-line-information.md)   
 [How to: Test Remittance Payments](../../LocalFunctionalityForMicrosoftDynamicsNav2016/Norway/how-to-test-remittance-payments.md)   
 [How to: Export Remittance Payments](../../LocalFunctionalityForMicrosoftDynamicsNav2016/Norway/how-to-export-remittance-payments.md)   
 [Types of Payment Returns Files](../../LocalFunctionalityForMicrosoftDynamicsNav2016/Norway/types-of-payment-returns-files.md)   
 [How to: Import Payment Return Data](../../LocalFunctionalityForMicrosoftDynamicsNav2016/Norway/how-to-import-payment-return-data.md)   
 [How to: Delete Remittance Payment Orders](../../LocalFunctionalityForMicrosoftDynamicsNav2016/Norway/how-to-delete-remittance-payment-orders.md)   
 [Remittance Errors](../../LocalFunctionalityForMicrosoftDynamicsNav2016/Norway/remittance-errors.md)   
 [How to: View Remittance Error Codes](../../LocalFunctionalityForMicrosoftDynamicsNav2016/Norway/how-to-view-remittance-error-codes.md)   
 [How to: Cancel Payments](../../LocalFunctionalityForMicrosoftDynamicsNav2016/Norway/how-to-cancel-payments.md)