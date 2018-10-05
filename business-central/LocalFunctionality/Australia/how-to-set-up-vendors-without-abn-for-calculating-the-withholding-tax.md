---
    title: How to Set Up Vendors Without ABN for Calculating the Withholding Tax
    description: Withholding Tax (WHT) is calculated for local vendors who do not have an Australian Business Number (ABN), as required by tax law.

    services: project-madeira 
    documentationcenter: ''
    author: SorenGP

    ms.service: dynamics365-financials
    ms.topic: article
    ms.devlang: na
    ms.tgt_pltfrm: na
    ms.workload: na
    ms.search.keywords:
    ms.date: 10/01/2018
    ms.author: sgroespe

---
# Set Up Vendors Without ABN for Calculating the Withholding Tax
Withholding Tax (WHT) is calculated for local vendors who do not have an Australian Business Number (ABN), as required by tax law.  

## To set up vendors without ABN for calculating the withholding tax  

1.  Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Vendors**, and then choose the related link.  
2.  Choose the required vendor, and then choose the **Edit** action.  
3.  In the **Vendor Card** window, on the **Registration** FastTab, make sure the **ABN** field and the **Foreign Vend** field must be empty.  
4.  Choose the **OK** button.  

    > [!NOTE]  
    >  The WHT percentage is automatically withheld in accordance with what was specified in the **WHT Posting Setup** window. The WHT certificate is produced for submission to the vendor. For more information, see [Withholding Tax](withholding-tax.md).  

## See Also  
 [Withholding Tax](withholding-tax.md)   
 [Set Up Withholding Tax](how-to-set-up-withholding-tax.md)
