---
title: "Report 340"
ms.custom: na
ms.date: "06-05-2016"
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: "article"
helpviewer_keywords: 
  - "Report 340, about"
  - "340 report, about"
ms.assetid: 3ceecf07-0c0a-45f9-932c-f4983041e99a
caps.latest.revision: 18
ms.author: "edupont"
manager: "terryaus"
translation.priority.ht: 
  - "es-es"
---
# Report 340
**Report 340** contains information about invoices and taxes that were issued or received by your company in a given period. The report is generated in a format that is approved by the tax authorities. This report should be submitted in the company’s monthly or quarterly liquidation period, depending on the size of the company. This file can be uploaded to the Spanish Tax Agency website or submitted on CD\-ROM. For more information, see the [Spanish Tax Agency](http://www.aeat.es/wps/portal/Home?channel=1af861cd949a1010VgnVCM100000d7005a80____&ver=L&site=56d8237c0bc1ff00VgnVCM100000d7005a80____&idioma=es_ES&menu=0&img=0) website. If the number of operations exceeds 1,000,000, the report can be submitted electronically.  
  
## Reporting Requirements for Entrepreneurs and Small Companies  
 The reporting requirements for entrepreneurs and small businesses are modified to support businesses that use the cash accounting criteria \(CAC\).  
  
 A company can use the cash accounting method if business sales do not exceed 2,000,000 euros per year. There is one exception to this rule for a business whose receipts in cash from any single customer exceeds the sum of 100,000 euros.  
  
 In [!INCLUDE[navnow](../../ApplicationDesign/includes/navnow_md.md)], you can set up posting groups for cash\-based VAT accounting for purchases and sales.  
  
 If you file a report under this regimen, the following label is applied to certain [!INCLUDE[navnow](../../ApplicationDesign/includes/navnow_md.md)] reports: **Régimen especial del criterio de caja**. The modified reports are:  
  
|Report|[!INCLUDE[bp_tabledescription](../../ApplicationDesign/includes/bp_tabledescription_md.md)]|  
|------------|---------------------------------------|  
|Report 117|Reminder|  
|Report 118|Finance Charge Memo|  
|Report 205|Order Confirmation|  
|Report 206|Sales \- Invoice|  
|Report 207|Sales \- Credit Memo|  
|Report 405|Purchase Order|  
|Report 406|Purchase – Invoice|  
|Report 407|Purchase \- Credit Memo|  
|Report 5900|Service Order|  
|Report 5911|Service \- Invoice|  
|Report 5912|Service \- Credit Memo|  
  
## File Format  
 The file format for **Report 340** includes one deponent record, and at least one issued invoice or one received invoice. Deponent information comes from the **\($ T\_79 Company Information $\)** table and the request form. Issued invoices come from the companies to which you have sold goods or services. Customer information comes from the **\($ T\_18 Customer $\)** table. Received invoices come from the companies from which you have purchased goods or services. Vendor information comes from the **\($ T\_23 Vendor $\)** table.  
  
> [!NOTE]  
>  If there are no file format records, the file is not created and an error message is displayed.  
  
## Entries Included in Report 340  
 The entries included in **Report 340** must have been posted in the period and fiscal year entered in the request form. The entries that are included in the report of payments in cash can be posted from the previous year.  
  
### Businesses  
 **Report 340** must include the following entries:  
  
-   Posted sales invoices and credit memos.  
  
-   Posted purchase invoices and credit memos.  
  
-   Posted service invoices and credit memos.  
  
-   Auto invoices and auto credit memos.  
  
-   Payments in cash.  
  
 Entries in the **\($ R\_10704 Sales Invoice Book $\)** report must be included in the report as issued invoices.  
  
 Entries in the **\($ R\_10705 Purchase Invoice book $\)** report must be included in the report as received invoices.  
  
### Small Businesses  
 For small businesses and entrepreneurs operating under the Cash Accounting Criteria \(CAC\), Report 340 reports invoices under the CAC. The invoice is marked with a "Z" for operation type. If the invoice is under the CAC, then the following is reported:  
  
-   Payment\/receipt method, that is, cash, check, transfer, and so forth. This field is blank in the report if no payment collection has occurred.  
  
-   Payment\/receipt amount \(full, partial\)  
  
-   Payment\/receipt dates  
  
### Invoices Including Different VAT Percentages or EC Percentages  
 If the invoice has more than one VAT percentage or equivalence charge \(EC\) percentage, the report must include all of the records with different VAT percentage and EC percentage. If the invoice includes equivalence charges \(EC\), the EC percentage and EC amount without VAT will be displayed.  
  
 All of these records will show the same invoice ID and customer VAT number.  
  
## File Format Restrictions  
 Before creating **Report 340**, you should consider the following file format restrictions:  
  
-   All amounts must be in euro.  
  
-   All amounts must be positive. In the fields where negative amounts are possible, **N** is specified.  
  
-   All text must be capitalized.  
  
-   All alphanumeric fields must be left\-aligned.  
  
-   All numeric fields must be right\-aligned.  
  
-   Special characters are converted to standard characters.  
  
-   If the field has no value, it will be empty for alphanumeric fields and populated with zeros for numeric fields.  
  
## See Also  
 [How to: Create Report 340](../../LocalFunctionalityForMicrosoftDynamicsNav2016/Spain/how-to-create-report-340.md)   
 [\($ B\_10743 Make 340 Declaration $\)](../../LocalFunctionalityForMicrosoftDynamicsNav2016/Spain/-$-b_10743-make-340-declaration-$-.md)   
 [Payments in Cash](../../LocalFunctionalityForMicrosoftDynamicsNav2016/Spain/payments-in-cash.md)   
 [Spain Local Functionality](../../LocalFunctionalityForMicrosoftDynamicsNav2016/Spain/spain-local-functionality.md)