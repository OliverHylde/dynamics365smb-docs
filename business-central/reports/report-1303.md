---
title: Standard Sales - Draft Invoice (report)
description: Generate a draft invoice document from an unposted sales invoice to review or send to a customer before posting.
author: kennieNP
ms.author: kepontop
ms.reviewer: bholtorf
ms.topic: concept-article
ms.search.keywords: reporting
ms.search.form: Report_1303_Primary
ms.date: 2026-09-15
ms.service: dynamics-365-business-central
ms.custom:
 - ai-gen-docs-bap
 - ai-seo-date: 2026-09-15
ai.usage: ai-assisted
---

# Standard Sales - Draft Invoice (report)

The **Standard Sales - Draft Invoice** report produces a printable or emailable draft of a sales invoice before it is posted. It pulls the customer and company addresses, header information such as document number, external document number, your reference, salesperson, payment terms, and shipment method, and the invoice lines with quantities, unit prices, discounts, VAT percentages, and line amounts. The report also calculates and displays VAT amount specifications, VAT clauses, and totals including subtotal, invoice discount, VAT amount, and total including VAT, so the customer or internal reviewer can verify the invoice content before it becomes final.

You can filter the report by document number, sell-to customer number, and No. Printed, which lets you generate a draft invoice for a specific sales invoice, restrict the report to a particular customer's open invoices, or exclude documents that have already been printed.

## Use cases

[!INCLUDE [report-1303-scenario](../includes/report-1303-scenario-include.md)]

Accounts receivable clerks can use the report to:

* Print or email a draft invoice to a customer for review before the actual invoice is posted.
* Verify line amounts, discounts, and VAT calculations against the sales order before finalizing the invoice.
* Confirm payment terms, payment method, and shipment method details are correct before posting.
* Attach the draft invoice to an email using the email body layout to send directly to the customer.,Salespersons can use the report to:

* Share a draft invoice with a customer to confirm pricing and quantities before the deal is finalized.
* Check that the customer's reference number and shipping address are correctly reflected on the document.
* Review invoice discounts and VAT clauses applied to the sale before it is posted.,Controllers and finance teams can use the report to:

* Audit VAT amount specifications and VAT clauses on draft invoices to ensure compliance before posting.
* Reconcile subtotal, invoice discount, and total amounts including VAT prior to invoice posting.
* Use the log interaction option to track customer communication history related to draft invoices sent.

## Try the report

Try the report here: [Standard Sales - Draft Invoice](https://businesscentral.dynamics.com?report=1303)

[!INCLUDE[ctrl-right-click-to-open-in-new-tab](../includes/ctrl-right-click-to-open-in-new-tab.md)]

## Related information

[Sales reports](../sales-reports.md)

[!INCLUDE[footer-include](../includes/footer-banner.md)]
