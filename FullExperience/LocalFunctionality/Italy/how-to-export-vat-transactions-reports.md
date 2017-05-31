---
title: "How to: Export VAT Transactions Reports"
ms.custom: na
ms.date: "06-05-2016"
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: "article"
ms.assetid: 0c5707ba-ceb4-4620-b7ab-a1a7a0970296
caps.latest.revision: 7
ms.author: "edupont"
translation.priority.ht: 
  - "it-it"
---
# How to: Export VAT Transactions Reports
After you create a report, you can release it, and then export it for the authorities. To change the report, make sure that the Modify Submitted Reports check box is enabled in the VAT Report Setup window. If it is not, to change the report when you want to correct an error, you will have to create a new report, add the report with the error in the original report number, and then create a corrective report. For more information, see [How to: Correct VAT Transactions Reports](../../LocalFunctionalityForMicrosoftDynamicsNav2016/Italy/how-to-correct-vat-transactions-reports.md).  
  
 It is only possible to change the lines and fields when the document has the status Open. In the Released status, only the receipt no. is available for change. In the Submitted status, all fields are locked.  
  
### To export and submit a VAT transaction report  
  
1.  In the **Search** box, enter **VAT Reports**, and then choose the related link.  
  
2.  Select an existing report or create a new report:  
  
    -   Select the relevant VAT report from the list, and on the **Home** tab, choose **Edit**.  
  
    -   On the **Home** tab, choose **New**, and create a new report. For more information, see [How to: Create Electronic VAT Transactions Reports](../../LocalFunctionalityForMicrosoftDynamicsNav2016/Italy/how-to-create-electronic-vat-transactions-reports.md).  
  
3.  Review the transaction details. To exclude a line from being reported to the tax authority, on the line, clear the **Incl. in Report** check box. To see the VAT entries that the line is based on, right\-click the **\($ T\_741\_9 Amount $\)** field, and choose the AssistButton.  
  
    > [!NOTE]  
    >  You can create an empty report, that is, a report that has no lines, in the case in which there are no transactions to report.  
  
4.  On the **Home** tab, in the **Process** group, choose **Release**. The **\($ T\_740\_6 Status $\)** field is updated to Released.  
  
     [!INCLUDE[navnow](../../ApplicationDesign/includes/navnow_md.md)] validates that the VAT report is valid and ready for submission. If the validation fails, the errors are shown in the **\($ N\_745 VAT Report Error Log $\)** window so that you can make the appropriate changes.  
  
     After you release a VAT report, you cannot edit it. If you have to change the report after it is released, you have to first reopen it. On the **Home** tab, in the **Process** group, choose **Reopen**.  
  
5.  On the **Home** tab, in the **Process** group, choose **Export**. The **\($ B\_12193 Export VAT Transactions $\)** batch job opens.  
  
6.  Select the **\($ B\_12193\_N\_2\_1130000 Detailed Export $\)** check box, depending on your needs. The field controls whether to export the data in detailed format or in aggregate. If aggregate, lines are further grouped by VAT registration number or fiscal code.  
  
7.  Choose the **OK** button. The VAT report is exported as a .ccf file. You can now submit the report to the tax authorities by using the tool from the Italian Revenue Agency. Use the guidelines provided by the authority. For more information, see the [Italian Revenue Agency](http://go.microsoft.com/fwlink/?LinkID=206524).  
  
     After you receive a response from the tax authorities, you must update the VAT report.  
  
8.  On the **General** FastTab, in the **\($ T\_740\_12100 Tax Auth. Receipt No. $\)** field, specify the receipt number that you received from the tax authorities. In the **\($ T\_740\_12101 Tax Auth. Doc. No. $\)** field, specify the document number that you receive.  
  
9. On the **Home** tab, in the **Process** group, choose **Mark as Submitted** to finalize the report. The **\($ T\_740\_6 Status $\)** field is updated to Submitted.  
  
    > [!NOTE]  
    >  You can modify a report that has the status of Submitted only if you have enabled the **Modify Submitted Reports** check box in the **\($ N\_743 VAT Report Setup $\)** window.  
  
## See Also  
 [\($ B\_12193 Export VAT Transactions $\)](../../LocalFunctionalityForMicrosoftDynamicsNav2016/Italy/-$-b_12193-export-vat-transactions-$-.md)   
 [\($ N\_745 VAT Report Error Log $\)](assetId:///c35e6992-b833-484f-9026-d9ba5e4d528b)   
 [How to: Correct VAT Transactions Reports](../../LocalFunctionalityForMicrosoftDynamicsNav2016/Italy/how-to-correct-vat-transactions-reports.md)