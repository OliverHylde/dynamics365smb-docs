---
title: Standard Sales - Shipment (report)
description: Print or email a formatted posted sales shipment document that shows shipped items, quantities, and optional lot or serial number tracking details.
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

The **Standard Sales - Shipment** report generates a formatted document for a posted sales shipment, showing company and customer address information, shipment and order references, and the shipped item lines with quantities and units of measure. It can optionally include assembly component details for items supplied through linked assembly orders, and an appendix listing lot and serial numbers for tracked items. The report supports RDLC and Word layouts and can log the printing as a customer interaction.

You can filter the report by shipment number, sell-to customer number, and whether the document has already been printed (No. Printed), so you can reprint a specific shipment or run a batch for a customer or set of unprinted shipments. Request page options let you show assembly components used in linked assembly orders, include or exclude correction lines from undone quantity postings, hide lines with zero quantity, and add a serial/lot number appendix to the printed document.

## Use cases

[!INCLUDE [report-1308-scenario](../includes/report-1308-scenario-include.md)]

Warehouse and shipping staff can use the report to:

* Print a packing confirmation for a customer immediately after posting a sales shipment.
* Include the shipping agent code and package tracking number on the document for carrier reference.
* Add a lot/serial number appendix so item tracking details travel with the shipment paperwork.
* Hide zero-quantity lines to keep the printed document limited to items actually shipped.,Sales and customer service teams can use the report to:

* Email a posted shipment confirmation to the customer's sell-to or bill-to contact.
* Log the shipment printing as a customer interaction for CRM and segment tracking.
* Reprint a shipment document for a customer by filtering on the sell-to customer number.
* Verify project (job) number and task references on shipment lines tied to project sales.

## Try the report

Try the report here: [Standard Sales - Shipment](https://businesscentral.dynamics.com?report=1308)

[!INCLUDE[ctrl-right-click-to-open-in-new-tab](../includes/ctrl-right-click-to-open-in-new-tab.md)]

## Related information

[Sales reports](../sales-reports.md)

[!INCLUDE[footer-include](../includes/footer-banner.md)]
