---
title: Standard Sales - Invoice (report)
description: Print or email a formatted posted sales invoice that shows customer and company details, item lines, VAT breakdown, and payment amounts.
author: kennieNP
ms.author: kepontop
ms.reviewer: bholtorf
ms.topic: concept-article
ms.search.keywords: reporting
ms.search.form: Report_1306_Primary
ms.date: 2026-09-15
ms.service: dynamics-365-business-central
ms.custom:
 - ai-gen-docs-bap
 - ai-seo-date: 2026-09-15
ai.usage: ai-assisted
---

# Standard Sales - Invoice (report)

The **Standard Sales - Invoice** report produces a printable or emailable version of a posted sales invoice. It combines company and customer address information, invoice header details such as due date, payment terms, and shipping method, a list of invoice lines with quantities, prices, discounts, and VAT, and a totals section showing subtotal, VAT amount, and amount including VAT. The report supports several rendering layouts, including RDLC and multiple Word layouts, so you can choose a format that matches how the document will be printed or emailed to the customer.

You can filter the report by document **No.**, **Sell-to Customer No.**, and **No. Printed** to control which posted sales invoices are included, since the report requires at least one filter before it will run. Request page options let you also show assembly components used in linked assembly orders, show shipment information for the invoiced items, display an additional fee note, hide lines with zero quantity, and log the printing as an interaction with the customer contact.

## Use cases

[!INCLUDE [report-1306-scenario](../includes/report-1306-scenario-include.md)]

Accounts receivable and billing staff can use the report to:

* Reprint a posted sales invoice for a customer who lost the original copy.
* Email the invoice directly to the customer using one of the Word body layouts.
* Check the remaining amount due on an invoice that has been partially paid before following up with the customer.
* Include shipment or assembly component details on the invoice when the customer needs proof of what was shipped or assembled.,Controllers and finance teams can use the report to:

* Verify that VAT amounts, VAT clauses, and VAT identifiers on the printed invoice match what was posted before it goes out to the customer.
* Review invoice discount amounts and totals shown on the document during period-end reconciliation.
* Use the VAT Spec layout to produce invoices that include a VAT specification broken down by VAT identifier for jurisdictions that require it.

## Try the report

Try the report here: [Standard Sales - Invoice](https://businesscentral.dynamics.com?report=1306)

[!INCLUDE[ctrl-right-click-to-open-in-new-tab](../includes/ctrl-right-click-to-open-in-new-tab.md)]

## Related information

[Sales reports](../sales-reports.md)

[!INCLUDE[footer-include](../includes/footer-banner.md)]
