---
    title: How to Specify Posting Periods
    description: When you specify posting periods, you limit the period in which posting is allowed.

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
# Specify Posting Periods
When you specify posting periods, you limit the period in which posting is allowed.  

## To specify posting periods  

1.  Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **General Ledger Setup**, and then choose the related link.  
2.  In the **General Ledger Setup** window, on the **General** tab, in the **Allow Posting From** field, specify the start date of the posting period.  
3.  In the **Allow Posting To** field, specify the end date of the posting period.  

    The dates are validated against the allowed posting ranges to make sure that they belong to open fiscal years. For more information, see Allowed Posting Range.  

4.  To verify what the allowed posting range is, choose the **Get Allowed Posting Range** action.  

The dates that you define here apply to the whole company, that is, to all users.  

> [!NOTE]  
>  You can define different posting periods for different users and apply a posting period to a user in the **User Setup** window.

If you enter dates here, the dates entered on the **General** tab in the **General Ledger Setup** window will not apply to these users.  

## See Also  
 [Fiscal Periods and Fiscal Years](fiscal-periods-and-fiscal-years.md)
