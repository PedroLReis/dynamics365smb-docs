---
title: "How to: Process Sales Returns"
ms.custom: na
ms.date: "03-03-2017"
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: "article"
helpviewer_keywords: 
  - "returns, sales"
  - "sales returns, processing"
  - "returns management, processing sales returns"
  - "damaged items"
ms.assetid: 5c81cf7b-7019-4c59-b506-0f2f740807dd
caps.latest.revision: 11
ms.author: "sgroespe"
manager: "terryaus"
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
# How to: Process Sales Returns
Sales returns are used to compensate your customers for incorrect or damaged items that you sent to them.  
  
 There are various ways to compensate a customer who is dissatisfied with an order. The terms of a compensation agreement reached between the company and the customer will often depend on the stated reason for return and the company\-customer relationship. For instance, the parties may agree that in case of a wrongly ordered item, the customer returns the item to the company against a credit, receives a replacement item and accepts that the company charges a certain restock fee. In other situations, for example, where an item arrives at the customer slightly damaged, the customer may agree to receive a price deduction against the original sales order price. Meanwhile, where the sold item has a warranty, the company may suggest the customer take the malfunctioning or broken item in for repair. For more information, see [About Returns Management](../Purchasing/about-returns-management.md).  
  
 The sales return order is the central document that allows the user to register a compensation agreement settled with a customer. From here, the user can access other sales\-related documents, and enter and maintain the return\-related information concerning the customer, the method of compensation, and the items in question.  
  
 The following are the standard steps in processing a basic sales return order. A basic return order is created when you simply want to credit your customer for a returned item.  
  
### To process a basic sales return  
  
1.  Create a sales return order.  
  
     On the **Invoicing** FastTab, you can apply the return order to the associated sales invoice by filling in the **Applies\-to Doc. Type** and **Applies\-to Doc. No.** fields.  
  
2.  Post the sales return order.  
  
     By receiving and invoicing the return order, a posted sales credit memo is created.  
  
     If the associated invoice was not applied earlier in the process, this application can take place after posting.  
  
### Additional Return Options  
  
-   The following options can be used in conjunction with basic processing:  
  
    -   In some cases, you may decide to charge a restock fee to cover the physical handling costs of returning an item.  
  
    -   If you want to revalue the returned item using the unit cost that is connected to the original sales entry, assign Exact Cost Reversing.  
  
    -   You may agree to compensate your customer for an item that you sold them by giving them a deduction against the original sales order price by creating a sales allowance.  
  
    -   You may agree to replace an item that you have sold your customer by creating a replacement sales order. The replacement item can be the same or it can be different.  
  
    -   In some cases, your customer may want to return a specific serialized item or lot, for example, if a particular item or lot is defective or damaged during shipment. For these situations, you can to find the item using the serial or lot number, and then receive that specific item or lot return. Follow these steps:  
  
        1.  Locate the serial\/lot numbers sold to the customer.  
  
        2.  Create a sales return order.  
  
        3.  Select the line that you want to select serial\/lot numbers for.  
  
        4.  Choose **Actions**![Action Menu icon](../DesignAndEngineering/media/actionmenuicon.png "actionMenuIcon"), choose **Line,** and then choose **Item Tracking Lines**.  
  
        5.  In the **Item Tracking Lines** window, in the **Lot No.** or **Serial No.** field, select an option from the **Item Tracking Summary** window.  
  
    -   You can create all return\-related documents at the same time from the **Sales Return Order** window. Alternatively, you can create all the documents, including replacement sales orders, purchase return orders, and purchase orders, individually.  
  
-   The following options can be used for items that have been received but not yet invoiced:  
  
    -   There may be times when your customer returns several items that are covered by different sales return orders. Once the items have been received and before you invoice, you can use the **Get Return Receipt Lines** function to create one sales credit memo for all of the received items.  
  
    -   If a return order has been received but the item is subsequently rejected, you must create a corrective sales invoice to complete the return order transaction.  
  
## See Also  
 [How to: Create Sales Credit Memos](../Finance/how-to-create-sales-credit-memos.md)   
 [\($ B\_6697 Create Return\-Related Documents $\)](../Sales/-$-b_6697-create-return-related-documents-$-.md)   
 [About Returns Management](../Purchasing/about-returns-management.md)   
 [How to: Create a Restock Charge](../Sales/how-to-create-a-restock-charge.md)   
 [How to: Assign Exact Cost Reversing in Sales](../Finance/how-to-assign-exact-cost-reversing-in-sales.md)   
 [How to: Create Replacement Sales Orders](../Sales/how-to-create-replacement-sales-orders.md)   
 [How to: Create and Post Sales Allowances](../Sales/how-to-create-and-post-sales-allowances.md)   
 [How to: Create Sales Return Orders](../Sales/how-to-create-sales-return-orders.md)   
 [How to: Get Return Receipt Lines for Item Charges](../Finance/how-to-get-return-receipt-lines-for-item-charges.md)   
 [How to: Create Corrective Sales Invoices](../Finance/how-to-create-corrective-sales-invoices.md)