---
title: Standard Sales - Quote (report)
description: Generate a printed or emailed sales quote that presents item lines, prices, discounts, VAT, and totals to a prospective customer.
author: kennieNP
ms.author: kepontop
ms.reviewer: bholtorf
ms.topic: concept-article
ms.search.keywords: reporting
ms.search.form: Report_1304_Primary
ms.date: 2026-09-10
ms.service: dynamics-365-business-central
ms.custom:
 - ai-gen-docs-bap
 - ai-seo-date: 2026-09-10
ai.usage: ai-assisted
---

# Standard Sales - Quote (report)

The **Standard Sales - Quote** report produces a customer-facing quote document based on a sales quote header and its lines. It includes company and customer address details, document identification such as quote number and validity date, salesperson and payment information, and a breakdown of item lines with quantities, prices, discounts, VAT percentages, and line amounts, followed by subtotal and VAT-inclusive total amounts. The report can be rendered as a Word or RDLC layout, or sent as an email body with a shorter summary layout, and it can optionally archive the quote and log a marketing interaction when printed.

You can filter the report by quote number, sell-to customer number, and whether the quote has already been printed (No. Printed), letting you reprint a specific quote, generate quotes for one customer, or limit output to quotes that haven't been printed yet. A filter is required before running the report, since printing without any filter is blocked to prevent accidentally generating every quote in the system.

## Use cases

[!INCLUDE [report-1304-scenario](../includes/report-1304-scenario-include.md)]

Sales representatives can use the report to:

* Print or email a formal quote for a prospective customer before an order is created.
* Confirm the quote validity date, payment terms, and shipment method shown to the customer.
* Send the quote as an email body using the composite email layout with a greeting and cover text.
* Reprint a previously issued quote by filtering on the quote number.,Sales managers and administrators can use the report to:

* Archive quotes automatically when they're printed, based on the Archive Quotes setup option.
* Log customer interactions for marketing and CRM tracking when a quote is sent.
* Review VAT amount specifications and invoice discount breakdowns before a quote is finalized into an order.

## Try the report

Try the report here: [Standard Sales - Quote](https://businesscentral.dynamics.com?report=1304)

[!INCLUDE[ctrl-right-click-to-open-in-new-tab](../includes/ctrl-right-click-to-open-in-new-tab.md)]

## Related information

[Sales reports](../sales-reports.md)

[!INCLUDE[footer-include](../includes/footer-banner.md)]
