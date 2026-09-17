---
title: Contract Standard Sales Inv. (report)
description: Print or export a standard sales invoice that also lists the subscription billing details behind each contract-related invoice line.
author: kennieNP
ms.author: kepontop
ms.reviewer: bholtorf
ms.topic: concept-article
ms.search.keywords: reporting
ms.search.form: Report_8008_Primary
ms.date: 2026-09-17
ms.service: dynamics-365-business-central
ms.custom:
 - ai-gen-docs-bap
 - ai-seo-date: 2026-09-17
ai.usage: ai-assisted
---

# Contract Standard Sales Inv. (report)

The **Contract Standard Sales Inv.** report extends the standard sales invoice with a subscription billing breakdown for each invoice line that originates from a subscription contract. For every contract line it adds a details section that shows the contract number, position, service description, billing start and end date, number of days billed, quantity, sales price, discount percentage and amount, and the resulting line amount, grouped by document and ledger entry so customers can see exactly what period and quantity they are being billed for.

You can filter the report by the same selections used on the standard sales invoice, such as customer, posting date, and invoice number, to control which posted sales invoices are included; the subscription billing details section itself is populated automatically from the job ledger entries linked to each invoice's subscription contract lines, so no separate filter is needed to include or exclude it.

## Use cases

[!INCLUDE [report-8008-scenario](../includes/report-8008-scenario-include.md)]

Billing and accounts receivable teams can use the report to:

* Print a posted sales invoice that shows both the standard line totals and the underlying subscription billing period for each contract line.
* Verify that the billed quantity, price, and discount on a subscription line match the contract terms before sending the invoice to the customer.
* Send customers a document that explains why an invoice line covers a specific date range and number of days.,Customers and account managers can use the report to:

* Review the exact start date, end date, and number of days covered by each subscription charge on an invoice.
* Confirm the sales price, line discount, and currency used for each subscription position without contacting billing support.
* Use the contract number and position printed on the invoice to cross-reference charges against the original subscription contract.

## Try the report

Try the report here: [Contract Standard Sales Inv.](https://businesscentral.dynamics.com?report=8008)

[!INCLUDE[ctrl-right-click-to-open-in-new-tab](../includes/ctrl-right-click-to-open-in-new-tab.md)]

## Related information

[Sales reports](../sales-reports.md)

[!INCLUDE[footer-include](../includes/footer-banner.md)]
