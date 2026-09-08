---
title: Standard Sales - Order Conf. (report)
description: Print or email a formatted sales order confirmation that shows customer, shipment, and pricing details for a released sales order.
author: kennieNP
ms.author: kepontop
ms.reviewer: bholtorf
ms.topic: concept-article
ms.search.keywords: reporting
ms.search.form: Report_1305_Primary
ms.date: 2026-09-08
ms.service: dynamics-365-business-central
ms.custom:
 - ai-gen-docs-bap
 - ai-seo-date: 2026-09-08
ai.usage: ai-assisted
---

# Standard Sales - Order Conf. (report)

The **Standard Sales - Order Conf.** report generates a printable or emailable confirmation document for sales orders. It pulls together company and customer address information, order header details such as document number, external document number, salesperson, and quote number, and the full set of order lines with quantities, unit prices, discounts, VAT percentages, and line amounts. The report also calculates and displays subtotals, invoice discounts, VAT amount specifications, and the total amount including VAT, and can optionally include assembly component details, work descriptions, and a payment discount reminder.

You can filter the report by sales order number, sell-to customer number, and whether the order has already been printed, so you can target a single order, all orders for a specific customer, or only orders that haven't yet been confirmed. Request page options also let you choose whether to log the interaction with the customer, show assembly components used to supply the ordered items, and archive the document after printing.

## Use cases

[!INCLUDE [report-1305-scenario](../includes/report-1305-scenario-include.md)]

Sales administrators can use the report to:

* Print or email an order confirmation immediately after entering a sales order to give the customer written confirmation of items, quantities, and prices.
* Include assembly component details on the confirmation when items being sold are supplied by linked assembly orders.
* Archive the confirmation and log the customer interaction automatically when the document is printed or sent.
* Filter by sell-to customer number to reprint confirmations for a specific customer's outstanding orders.,Customer service representatives can use the report to:

* Verify shipment method, shipment date, and ship-to address details with the customer before the order is fulfilled.
* Confirm payment terms, payment method, and any applicable payment discount deadline shown on the document.
* Resend a confirmation for an order that hasn't yet been printed by filtering on the 'No. Printed' field.,Controllers and finance teams can use the report to:

* Review VAT amount specifications, invoice discount amounts, and totals including VAT before the order is invoiced.
* Check the exchange rate text and local currency totals for orders placed in a foreign currency.
* Use the VAT clause and VAT identifier breakdown to confirm the order complies with applicable tax reporting requirements.

## Try the report

Try the report here: [Standard Sales - Order Conf.](https://businesscentral.dynamics.com?report=1305)

[!INCLUDE[ctrl-right-click-to-open-in-new-tab](../includes/ctrl-right-click-to-open-in-new-tab.md)]

## Related information

[Sales reports](../sales-reports.md)

[!INCLUDE[footer-include](../includes/footer-banner.md)]
