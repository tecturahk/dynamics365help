---
    title: How to Apply General Ledger Entries
    description: You apply general ledger entries to justify ledger balances on asset and liability accounts.

    services: project-madeira 
    documentationcenter: ''
    author: SorenGP

    ms.service: dynamics365-business-central
    ms.topic: article
    ms.devlang: na
    ms.tgt_pltfrm: na
    ms.workload: na
    ms.search.keywords:
    ms.date: 10/01/2018
    ms.author: sgroespe

---
# Apply General Ledger Entries
You apply general ledger entries to justify ledger balances on asset and liability accounts. For example, you can apply transactions on the bill of exchange accounts to get a clear picture of which bills make up the balance of the account.  

## To apply general ledger entries  

1.  Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Chart of Accounts**, and then choose the related link.  
2.  In the **Chart of Accounts** window, select the account that you want to apply entries for, and then choose the **Apply Entries** action.  
3.  In the **Apply G/L Entries** window, select the ledger entries that you want to apply.  
4.  Choose the **Set Applies-to ID** action to populate the Applies-to ID field with the user ID of the current user.  
5.  Choose the **Post Application** action.  

This effectuates the application by setting the Letter and Letter Date fields.  

> [!NOTE]  
>  Applied entries will be identified by the same three-letter combination and the same date. Balanced entries will be assigned only uppercase letters, and unbalanced entries will be assigned only lowercase letters.  

## See Also  
 [Unapply General Ledger Entries](how-to-unapply-general-ledger-entries.md)
