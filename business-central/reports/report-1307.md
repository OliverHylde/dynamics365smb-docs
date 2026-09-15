---
title: Standard Sales - Credit Memo (report)
description: Print or email a formatted posted sales credit memo that shows customer, item, and VAT details.
author: kennieNP
ms.author: kepontop
ms.reviewer: bholtorf
ms.topic: concept-article
ms.search.keywords: reporting
ms.search.form: Report_1307_Primary
ms.date: 2026-09-15
ms.service: dynamics-365-business-central
ms.custom:
 - ai-gen-docs-bap
 - ai-seo-date: 2026-09-15
ai.usage: ai-assisted
---

# Standard Sales - Credit Memo (report)

The **Standard Sales - Credit Memo** report generates a printable or emailable document for one or more posted sales credit memos. It shows the company and customer addresses, document details such as credit memo number, your reference, salesperson, applies-to document, and due date, and a line list with item number, description, shipment date, quantity, unit of measure, unit price, discount percentage, VAT percentage, and line amount. The report also includes VAT amount specification, VAT clauses, and totals including and excluding VAT, and can optionally show shipment and assembly component information for the credited items.

You can filter the report by credit memo number, sell-to customer number, and number printed to control which posted credit memos are included, since the report requires at least one filter before it runs. Request page options let you show or hide the sell-to customer's shipments, show assembly components used in linked assembly orders, hide lines with zero quantity, and log the printing as an interaction with the customer or contact.

## Use cases

[!INCLUDE [report-1307-scenario](../includes/report-1307-scenario-include.md)]

Accounts receivable and finance teams can use the report to:

* Print or email a posted credit memo to a customer as proof of the credited amount and VAT breakdown.
* Verify VAT amounts, VAT clauses, and totals before sending the document to the customer.
* Reissue a copy of a previously printed credit memo by filtering on the credit memo number.
* Log the document send as a customer interaction for CRM tracking purposes.,Sales and customer service representatives can use the report to:

* Confirm the applied invoice or return order reference shown on the credit memo before contacting the customer.
* Include shipment quantities on the credit memo when the credit relates to a returned shipment.
* Show assembly component details on credited lines that originated from an assembly order.
* Check the ship-to address and shipment method printed on the document to resolve customer questions.

## Try the report

Try the report here: [Standard Sales - Credit Memo](https://businesscentral.dynamics.com?report=1307)

[!INCLUDE[ctrl-right-click-to-open-in-new-tab](../includes/ctrl-right-click-to-open-in-new-tab.md)]

## Related information

[Sales reports](../sales-reports.md)

[!INCLUDE[footer-include](../includes/footer-banner.md)]
