---
title: Standard Sales - Pro Forma Inv (report)
description: Print a pro forma invoice for a sales order to give customers cost and customs details before the actual invoice is issued.
author: kennieNP
ms.author: kepontop
ms.reviewer: bholtorf
ms.topic: concept-article
ms.search.keywords: reporting
ms.search.form: Report_1302_Primary
ms.date: 2026-09-15
ms.service: dynamics-365-business-central
ms.custom:
 - ai-gen-docs-bap
 - ai-seo-date: 2026-09-15
ai.usage: ai-assisted
---

# Standard Sales - Pro Forma Inv (report)

The **Standard Sales - Pro Forma Inv** report prints a pro forma invoice for a sales order, showing customer and company address details, item lines with country of manufacture and tariff numbers, quantities, prices, net weight, VAT, and totals. It is typically used for customs purposes or to give a customer a preview of charges before the actual invoice is created, and it can include the order's work description text and either a full RDLC layout or a Word-based document layout.

You can filter the report by document No., Sell-to Customer No., and No. Printed to select which sales orders to include, and use the Hide lines with zero quantity option on the request page to exclude lines that have no quantity to invoice from the printed document.

## Use cases

[!INCLUDE [report-1302-scenario](../includes/report-1302-scenario-include.md)]

Sales administrators can use the report to:

* Generate a pro forma invoice for a customer before the actual sales invoice is posted, to confirm pricing and terms in advance.
* Print pro forma invoices with the sell-to and bill-to contact details, shipment method, and currency shown on the document.
* Hide lines with zero quantity to keep the printed pro forma invoice focused on items that still need to be shipped or invoiced.,Export and customs coordinators can use the report to:

* Provide customs authorities with a document listing each item's country of manufacture, tariff number, and net weight for customs clearance.
* Use the total weight and total VAT amounts on the document to support export declarations.
* Include the order's work description text on the pro forma invoice when additional shipment notes are required.

## Try the report

Try the report here: [Standard Sales - Pro Forma Inv](https://businesscentral.dynamics.com?report=1302)

[!INCLUDE[ctrl-right-click-to-open-in-new-tab](../includes/ctrl-right-click-to-open-in-new-tab.md)]

## Related information

[Sales reports](../sales-reports.md)

[!INCLUDE[footer-include](../includes/footer-banner.md)]
