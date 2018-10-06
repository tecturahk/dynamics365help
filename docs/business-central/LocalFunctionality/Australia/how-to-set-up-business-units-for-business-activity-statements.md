---
    title: How to Set Up Business Units for Business Activity Statements
    description: Describes how to consolidate the financial statements of various companies into one financial statement.
    services: project-madeira
    documentationcenter: ''
    author: bholtorf
    ms.service: dynamics365-financials
    ms.topic: article
    ms.devlang: na
    ms.tgt_pltfrm: na
    ms.workload: na
    ms.search.keywords:
    ms.date: 10/01/2018
    ms.author: bholtorf

---
# Set Up Business Units for Business Activity Statements
In [!INCLUDE[d365fin](../../includes/d365fin_md.md)], you can consolidate the financial statements of various companies into one financial statement.  

You must set up a consolidation company to perform the consolidation. In this company, the total amounts for all accounts in the group, from both the parent company and subsidiaries are added together. You must also indicate the general ledger accounts in the consolidated company to which the total should be transferred.  

You can use the **BAS Business Units** window to set up the following:  

- Parent company  
- Subsidiaries  
- Affiliates  

You must set up information in the **General Ledger Setup** window before you can set up business units.  

## To set up general ledger for a business activity statement  
1. Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **General Ledger Setup**, and then choose the related link.  
2. Fill in the required fields as described in the following table.  

    |Field|Description|  
    |---------------------------------|---------------------------------------|  
    |**BAS to be Lodged as a Group**|Select if you are logging a business activity statement for a group of companies.|  
    |**BAS Group Company**|Select if this company is the main company in the group of companies for which you are lodging a group business activity statement.|  

3.  Choose the **OK** button.  

## To set a business unit for a business activity statement  
1. Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **BAS Business Units**, and then choose the related link.  
2. Fill in the fields as described in the following table.  

    |Field|Description|  
    |---------------------------------|---------------------------------------|  
    |**Company Name**|Specify the name of the company which will be added to the group company's business activity statement.|  
    |**Document No.**|Specify the BAS document number that has to be consolidated. This field is associated with the **BAS Version** field.|  
    |**BAS Version**|Specify the BAS version number in which the transaction was included. This field is associated with the **Document No.** field.|  

3. Choose the **OK** button.  

## See Also  
[Australian Local Functionality](australia-local-functionality.md)   

