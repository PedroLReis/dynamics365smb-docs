---
title: "Make Payments with Bank Data Conversion Service or SEPA Credit Transfer"
ms.custom: na
ms.date: "03-03-2017"
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: "article"
ms.assetid: 25bfb18e-6263-4d7e-ac25-fead81335b27
caps.latest.revision: 4
ms.author: "sgroespe"
translation.priority.ht: 
  - "da-dk"
  - "de-at"
  - "de-ch"
  - "de-de"
  - "en-au"
  - "en-ca"
  - "en-gb"
  - "en-in"
  - "en-nz"
  - "es-es"
  - "es-mx"
  - "fi-fi"
  - "fr-be"
  - "fr-ca"
  - "fr-ch"
  - "fr-fr"
  - "is-is"
  - "it-ch"
  - "it-it"
  - "nb-no"
  - "nl-be"
  - "nl-nl"
  - "ru-ru"
  - "sv-se"
---
# Make Payments with Bank Data Conversion Service or SEPA Credit Transfer
In the **\($ N\_256 Payment Journal $\)** window, you can process payments to your vendors by exporting a file together with the payment information from the journal lines. You can then upload the file to your electronic bank where the related money transfers are processed.  
  
> [!NOTE]  
>  In the generic version of [!INCLUDE[dyn_nav](../ApplicationDesign/includes/dyn_nav_md.md)], a global provider of services to convert bank data to any file format that your bank requires is set up and connected. In addition, the generic version of [!INCLUDE[dyn_nav](../ApplicationDesign/includes/dyn_nav_md.md)] supports the SEPA Credit Transfer format. In your country\/region, other formats for electronic payments may be available.  
>   
>  To enable export of bank file formats that are not supported by the generic or local versions of [!INCLUDE[dyn_nav](../ApplicationDesign/includes/dyn_nav_md.md)], use the Date Exchange Framework. For more information, see [How to: Set Up Data Exchange Definitions](../BusinessFunctionality/DataExchange/how-to-set-up-data-exchange-definitions.md).  
  
 To enable SEPA credit transfers, you must first set up a bank account, a vendor, and the general journal batch that the payment journal is based on.  
  
 You then prepare payments to vendors by automatically filling the **\($ N\_256 Payment Journal $\)** window with due payments with specified posting dates.  
  
> [!NOTE]  
>  When you have verified that the payments are successfully processed by the bank, you can proceed to post the payment journal lines.  
  
 The following table describes a sequence of tasks, with links to the topics that describe them. These tasks are listed in the order in which they are generally performed.  
  
|**To**|**See**|  
|------------|-------------|  
|Activate the Bank Data Conversion Service feature to have any bank statement file converted to a format that you can import or to have your exported payment files converted to the format that your bank requires.|[How to: Set Up the Bank Data Conversion Service](../BusinessFunctionality/DataExchange/how-to-set-up-the-bank-data-conversion-service.md)|  
|Set up a bank account, a vendor, and a payment journal for SEPA credit transfer.|[How to: Set Up SEPA Credit Transfer](../BusinessFunctionality/DataExchange/how-to-set-up-sepa-credit-transfer.md)|  
|Fill the payment journal with lines for due payments to vendors, with the option to insert posting dates based on the due date of the related purchase documents.|[How to: Suggest Vendor Payments](../Finance/how-to-suggest-vendor-payments.md) and [How to: Insert Due Date as Posting Date on Payment Journal Lines](../Finance/how-to-insert-due-date-as-posting-date-on-payment-journal-lines.md)|  
|Export payment journal lines to a file in the SEPA Credit Transfer format.|[How to: Export Payments to a Bank File](../BusinessFunctionality/DataExchange/how-to-export-payments-to-a-bank-file.md)|  
|Review which payments have been exported and into which files.|[\($ N\_1205 Credit Transfer Registers $\)](../Finance/-$-n_1205-credit-transfer-registers-$-.md)|  
|When the electronic payment is successfully processed by the bank, post the payments.|[How to: Fill and Post General Journals](../Finance/how-to-fill-and-post-general-journals.md)|  
  
## See Also  
 [Process Outgoing Payments](../Finance/process-outgoing-payments.md)   
 [Manage Payables](../Finance/manage-payables.md)   
 [Collect Payments with SEPA Direct Debit](../Finance/collect-payments-with-sepa-direct-debit.md)