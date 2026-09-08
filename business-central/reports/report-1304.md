---
title: Standard Sales - Quote (report)
description: Generate and send a formatted sales quote document that presents proposed items, prices, and terms to a customer.
author: kennieNP
ms.author: kepontop
ms.reviewer: bholtorf
ms.topic: concept-article
ms.search.keywords: reporting
ms.search.form: Report_1304_Primary
ms.date: 2026-09-08
ms.service: dynamics-365-business-central
ms.custom:
 - ai-gen-docs-bap
 - ai-seo-date: 2026-09-08
ai.usage: ai-assisted
---

# Standard Sales - Quote (report)

The **Standard Sales - Quote** report produces a customer-facing document for a sales quote, showing company and customer address information, quote details such as document number, your reference, valid-to date, and salesperson, along with item lines that include quantity, unit price, discount percentage, VAT percentage, and line amount. It also calculates and displays VAT amount specifications and total amounts including VAT, and can optionally include a work description and archive the quote after printing or previewing.

You can filter the report by quote number, sell-to customer number, and whether the quote has already been printed (No. Printed), which lets you generate quotes for a specific customer, reprint quotes that were already issued, or restrict output to a single quote or a range of quotes.

## Use cases

[!INCLUDE [report-1304-scenario](../includes/report-1304-scenario-include.md)]

Sales representatives can use the report to:

* Print or email a formatted quote to send to a prospective customer after building the sales quote lines.
* Include a valid-to date and salesperson name on the quote so the customer knows the offer's terms and who to contact.
* Add a work description to the quote when extra explanation of the proposed items or services is needed.
* Reprint an existing quote for a customer without changing its content by filtering on the quote number.,Sales administrators and managers can use the report to:

* Archive quotes automatically after they are printed or previewed to keep a historical record of what was offered.
* Log interactions with the contact when a quote is sent, to track customer communication in the CRM.
* Review VAT amount specifications and discount breakdowns on the quote before it goes out to make sure pricing is correct.

## Try the report

Try the report here: [Standard Sales - Quote](https://businesscentral.dynamics.com?report=1304)

[!INCLUDE[ctrl-right-click-to-open-in-new-tab](../includes/ctrl-right-click-to-open-in-new-tab.md)]

## Related information

[Sales reports](../sales-reports.md)

[!INCLUDE[footer-include](../includes/footer-banner.md)]
