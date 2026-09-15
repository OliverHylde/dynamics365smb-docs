---
title: Inventory Order Details (report)
description: Review outstanding sales order lines by item to spot overdue shipments and gauge expected sales volume.
author: kennieNP
ms.author: kepontop
ms.reviewer: bholtorf
ms.topic: concept-article
ms.search.keywords: reporting
ms.search.form: Report_708_Primary
ms.date: 2026-09-15
ms.service: dynamics-365-business-central
ms.custom:
 - ai-gen-docs-bap
 - ai-seo-date: 2026-09-15
ai.usage: ai-assisted
---

# Inventory Order Details (report)

The **Inventory Order Details** report lists outstanding sales order lines grouped by item, showing the order number, customer bill-to name, shipment date, order quantity, outstanding quantity, unit price, and any line discount or invoice discount applied. It also flags quantities that are on back order — meaning the shipment date has already passed — and totals the outstanding quantity, back order quantity, and outstanding amount for each item, plus a grand total across all items. It's built on the Excel layout for further data analysis, but a Word-based print layout is also available.

You can filter the report by item number, search description, assembly BOM, inventory posting group, statistics group, and bin to narrow the set of items included, and by shipment date on the sales order lines to focus on a specific delivery window or to isolate overdue shipments.

## Use cases

[!INCLUDE [report-708-scenario](../includes/report-708-scenario-include.md)]

Inventory planners can use the report to:

* Identify items with sales order lines that are overdue for shipment based on the back order quantity column.
* Filter by bin, location, or inventory posting group to review outstanding demand for a specific warehouse area.
* Check outstanding quantities per item to plan replenishment or prioritize picking.,Sales administrators can use the report to:

* Filter by shipment date to see which customer orders are due to ship in an upcoming period.
* Review the bill-to customer name alongside order quantity and unit price to answer customer inquiries about order status.
* Check the outstanding amount and discount columns to confirm expected order values before shipment.,Controllers and finance teams can use the report to:

* Use the total outstanding amount to estimate expected revenue from unshipped sales orders.
* Review invoice discount amounts and line discount percentages applied to outstanding order lines.
* Export the Excel layout to analyze outstanding order value trends across items.

## Try the report

Try the report here: [Inventory Order Details](https://businesscentral.dynamics.com?report=708)

[!INCLUDE[ctrl-right-click-to-open-in-new-tab](../includes/ctrl-right-click-to-open-in-new-tab.md)]

## Related information

[Inventory reports](../inventory-reports.md)

[!INCLUDE[footer-include](../includes/footer-banner.md)]
