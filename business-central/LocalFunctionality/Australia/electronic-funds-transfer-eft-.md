---
    title: Electronic Funds Transfer (EFT)
    description: You can pay vendors using the electronic funds transfer (EFT) system in Australia.
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
# Electronic Funds Transfer (EFT)
You can pay vendors using the electronic funds transfer (EFT) system in Australia.  

## Setting up Electronic Funds Transfer in [!INCLUDE[d365fin](../../includes/d365fin_md.md)]  
[!INCLUDE[d365fin](../../includes/d365fin_md.md)] can export EFT files that you can then upload to your bank’s website for additional processing. To submit EFT files, you must set up the following information:  

* You must add EFT information to the bank account or bank accounts that you will use to pay vendors electronically. The EFT-specific fields are on the **Transfer** FastTab in the **Bank Account** window.  
* For those vendors that you want to pay electronically, you must select the **EFT Payment** check box and specify the vendor bank account in the **EFT Vendor Bank Account Code** field in the **Vendor** window.  

When you have set up bank accounts and vendors, you can create EFT file that are based on entries in the payment journal. When you create an EFT file, an entry is made in the **EFT Register** table. On the EFT Register page you can drill down to see the vendor ledger entries for the EFT file. On the Payment Journal page, you can also import existing EFT register entries to the payment journal by using the **Transfer EFT Register** batch job.

> [!NOTE]  
> Electronic Funds Transfer (EFT) uses posted and non-posted payments as the basis to calculate withholding tax amounts for applied invoices. Payments that are not applied to an invoice can only be exported to an EFT file if the **Skip WHT** check box is selected. During export of the EFT file, the payment journal lines are not deleted and cannot be deleted as long as they have a reference to an EFT register. To remove the link between the EFT register and payment journal lines, choose the **Cancel Export** action either in the **EFT Register** window or the **Payment Journal** window.       

## See Also  
[Export Payments to a Bank File](../../payables-how-export-payments-bank-file.md)  
[Australia Local Functionality](australia-local-functionality.md)
