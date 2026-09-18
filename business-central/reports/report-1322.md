---
title: Standard Purchase - Order (report)
description: Print or email a formatted purchase order document that shows vendor details, order lines, and VAT totals for a purchase order.
author: kennieNP
ms.author: kepontop
ms.reviewer: bholtorf
ms.topic: concept-article
ms.search.keywords: reporting
ms.search.form: Report_1322_Primary
ms.date: 2026-09-18
ms.service: dynamics-365-business-central
ms.custom:
 - ai-gen-docs-bap
 - ai-seo-date: 2026-09-18
ai.usage: ai-assisted
---

# Standard Purchase - Order (report)

The **Standard Purchase - Order** report generates a printable or emailable document for a purchase order, presenting the buy-from and pay-to vendor addresses, ship-to address, and company information alongside the order's header details such as order number, document date, payment terms, and buyer. It lists each purchase line with item number, description, quantity, unit of measure, direct unit cost, and line amount, and it calculates VAT amounts and totals, including prepayment specifications when applicable. The report can also archive the document and log the interaction with the vendor, depending on options selected on the request page.

You can filter the report by document number, buy-from vendor number, and whether the order has already been printed (No. Printed), letting you generate the document for a specific order, all orders from a given vendor, or only orders that have not yet been printed.

## Use cases

[!INCLUDE [report-1322-scenario](../includes/report-1322-scenario-include.md)]

Purchasing agents can use the report to:

* Generate a formal purchase order to send to a vendor after an order is created in Business Central.
* Confirm order details such as expected receipt date, shipment method, and vendor order/invoice number before sending to the vendor.
* Reprint a purchase order for a specific vendor by filtering on the buy-from vendor number.
* Archive the purchase order and log the interaction with the vendor for future reference.,Accounts payable and finance teams can use the report to:

* Review VAT amount specifications and totals, including VAT base and VAT amount by identifier, before the order is posted.
* Verify prepayment amounts and VAT calculated on prepayments included on the purchase order.
* Check payment terms and total amounts including and excluding VAT to confirm expected vendor payment obligations.

## Try the report

Try the report here: [Standard Purchase - Order](https://businesscentral.dynamics.com?report=1322)

[!INCLUDE[ctrl-right-click-to-open-in-new-tab](../includes/ctrl-right-click-to-open-in-new-tab.md)]

## Related information

[Purchase reports](../purchase-reports.md)

[!INCLUDE[footer-include](../includes/footer-banner.md)]
