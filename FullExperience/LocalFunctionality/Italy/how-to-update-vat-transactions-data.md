---
title: "How to: Update VAT Transactions Data"
ms.custom: na
ms.date: "06-05-2016"
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: "article"
helpviewer_keywords: 
  - "VAT reports, update transactions"
ms.assetid: 475cb942-ecc3-418c-a878-d1e51885f1a4
caps.latest.revision: 14
ms.author: "edupont"
manager: "terryaus"
translation.priority.ht: 
  - "it-it"
---
# How to: Update VAT Transactions Data
Before you create the first VAT transaction report, you should prepare the existing data by running the **\($ R\_12190 Update VAT Transaction Data $\)** report. You should also run this report if you have made changes to the setup based on new requirements from the tax authorities.  
  
 You can run the **\($ R\_12190 Update VAT Transaction Data $\)** report as a test before you change any data. When you have verified that the filters meet your expectations and the requirements of the tax authorities, you should run the report again to make the appropriate changes to data.  
  
> [!CAUTION]  
>  Before you run the **\($ R\_12190 Update VAT Transaction Data $\)** report, you should activate the change log in the **\($ N\_592 Change Log Setup $\)** window. Also, you should enable logging for modifications to the **\($ T\_254\_12120 Include in VAT Transac. Report $\)** field on the **\($ T\_254 VAT Entry $\)** table.  
  
### To update VAT transaction data  
  
1.  In the **Search** box, enter **\($ R\_12190 Update VAT Transaction Data $\)**, and then choose the related link.  
  
2.  Optionally, on the **VAT Entry** FastTab, set the appropriate filters.  
  
3.  On the **Options** FastTab, fill in the fields as described in the following table.  
  
    |[!INCLUDE[bp_tablefield](../../ApplicationDesign/includes/bp_tablefield_md.md)]|[!INCLUDE[bp_tabledescription](../../ApplicationDesign/includes/bp_tabledescription_md.md)]|  
    |---------------------------------|---------------------------------------|  
    |**\($ R\_12190\_N\_2\_1130008 Compare against Threshold $\)**|Select to compare VAT entries against the threshold amounts that are specified in the VAT posting setup.|  
    |**\($ R\_12190\_N\_2\_1130000 Show List Only $\)**|Select if you do not want to update data.<br /><br /> If you select this field, [!INCLUDE[navnow](../../ApplicationDesign/includes/navnow_md.md)] prints a report so that you can verify the changes before data is modified. The report contains a line for each document where the VAT base is equal to or greater than the threshold amounts. **Warning:**  Do not select both this field and the **Set Include in VAT Transaction Report** field.|  
    |**\($ R\_12190\_N\_2\_1130004 Set Include in VAT Transaction Report $\)**|Select to set the **\($ T\_254\_12120 Include in VAT Trans. Report $\)** to **Yes** on all VAT entries where the amounts meet the threshold amounts that are specified in the VAT posting setup. **Warning:**  If you select this field, your data is updated. You should run the report as a test before you run it to change data.|  
  
4.  Choose the **Print** button to update VAT transaction data, or choose the **Preview** button to view the changes.  
  
 When you run the report, [!INCLUDE[navnow](../../ApplicationDesign/includes/navnow_md.md)] processes VAT entries based on the filters that you set. The following rules are also applied:  
  
-   The **\($ T\_254\_12130 Blacklisted $\)** field for the VAT entry must be blank.  
  
-   The **\($ T\_254\_7 Type $\)** field for the VAT entry must not be **Settlement**.  
  
## See Also  
 [How to: Prepare for VAT Transactions Reports](../../LocalFunctionalityForMicrosoftDynamicsNav2016/Italy/how-to-prepare-for-vat-transactions-reports.md)   
 [Italian VAT](../../LocalFunctionalityForMicrosoftDynamicsNav2016/Italy/italian-vat.md)   
 [\($ R\_12190 Update VAT Transaction Data $\)](../../LocalFunctionalityForMicrosoftDynamicsNav2016/Italy/-$-r_12190-update-vat-transaction-data-$-.md)