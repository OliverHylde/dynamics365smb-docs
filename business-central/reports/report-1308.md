---
title: Standard Sales - Shipment (report)
description: Print or email a formatted posted sales shipment document showing shipped items, quantities, and optional lot or serial number tracking details.
author: kennieNP
ms.author: kepontop
ms.reviewer: bholtorf
ms.topic: concept-article
ms.search.keywords: reporting
ms.search.form: Report_1308_Primary
ms.date: 2026-09-10
ms.service: dynamics-365-business-central
ms.custom:
 - ai-gen-docs-bap
 - ai-seo-date: 2026-09-10
ai.usage: ai-assisted
---

# Standard Sales - Shipment (report)

The **Standard Sales - Shipment** report generates a printable or emailable document for a posted sales shipment. It includes company and customer address information, shipment and order details, and a list of shipped items with quantities and units of measure. Optionally, it can include assembly component details for items supplied through linked assembly orders, and an appendix showing lot and serial number tracking information for shipped items.

You can filter the report by posted sales shipment number, sell-to customer number, and whether the shipment has already been printed (No. Printed), so you can target a specific shipment, a specific customer's shipments, or only shipments that have not yet been printed. In the request page options, you can also choose to log the interaction with the customer contact, show assembly components used in linked assembly orders, show correction lines from undone quantity postings, print a serial/lot number appendix, and hide lines with zero quantity.

## Use cases

[!INCLUDE [report-1308-scenario](../includes/report-1308-scenario-include.md)]

Warehouse and shipping staff can use the report to:

* Print a shipment confirmation to include in the package or hand to the driver, showing exactly what items and quantities were shipped.
* Include the serial/lot number appendix so the customer can verify tracked items received against specific lot or serial numbers.
* Show assembly component details for items that were shipped from linked assembly orders, to document what parts went into an assembled item.,Customer service representatives can use the report to:

* Email the posted shipment document to a customer as confirmation that their order has been shipped, using the built-in greeting and closing text.
* Filter by a specific customer number to reprint or resend a shipment confirmation for that customer.
* Enable interaction logging so the email or print action is recorded against the customer's contact for follow-up and history tracking.
* Reference the shipping agent code and package tracking number on the document when a customer calls asking where their shipment is.,Project managers can use the report to:

* Review shipment lines tied to a project number and project task number to confirm which materials were delivered against a specific project task.
* Cross-check the project task description printed on the shipment against project records to validate billing or consumption.

## Try the report

Try the report here: [Standard Sales - Shipment](https://businesscentral.dynamics.com?report=1308)

[!INCLUDE[ctrl-right-click-to-open-in-new-tab](../includes/ctrl-right-click-to-open-in-new-tab.md)]

## Related information

[Sales reports](../sales-reports.md)

[!INCLUDE[footer-include](../includes/footer-banner.md)]
