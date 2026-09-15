---
title: Inventory - Sales Back Orders (report)
description: Identify sales order lines that are overdue for shipment because of insufficient inventory.
author: kennieNP
ms.author: kepontop
ms.reviewer: bholtorf
ms.topic: concept-article
ms.search.keywords: reporting
ms.search.form: Report_718_Primary
ms.date: 2026-09-15
ms.service: dynamics-365-business-central
ms.custom:
 - ai-gen-docs-bap
 - ai-seo-date: 2026-09-15
ai.usage: ai-assisted
---

# Inventory - Sales Back Orders (report)

The **Inventory - Sales Back Orders** report lists sales order lines for items whose shipment date has already passed, showing the outstanding quantity that still needs to be shipped. For each order line, it displays the item number and description, sales order number, customer name and phone number, shipment date, order quantity, and outstanding quantity. It also indicates whether the customer has other items on back order, and it provides subtotals of outstanding quantity per item so you can quickly gauge the size of the shortfall.

You can filter the report by item number, search description, assembly BOM, inventory posting group, statistics group, and bin filter to narrow the report to specific items or storage areas. You can also filter the sales order lines by shipment date to focus on orders overdue by a certain period, and by variant, location, or global dimension codes carried over from the item filters to scope the report to particular inventory segments.

## Use cases

[!INCLUDE [report-718-scenario](../includes/report-718-scenario-include.md)]

Warehouse and shipping teams can use the report to:

* Identify which sales order lines are overdue for shipment because stock isn't available.
* Check the outstanding quantity per item to prioritize replenishment or picking.
* See whether a customer has other back orders to consolidate follow-up communication.
* Filter by bin or location to focus on back orders affecting a specific warehouse area.,Sales and customer service representatives can use the report to:

* Contact customers proactively about orders whose shipment date has already passed.
* Use the customer name and phone number columns to reach out without looking up each order separately.
* Review all back-ordered lines for a customer to give a complete status update in one conversation.

## Try the report

Try the report here: [Inventory - Sales Back Orders](https://businesscentral.dynamics.com?report=718)

[!INCLUDE[ctrl-right-click-to-open-in-new-tab](../includes/ctrl-right-click-to-open-in-new-tab.md)]

## Related information

[Inventory reports](../inventory-reports.md)

[!INCLUDE[footer-include](../includes/footer-banner.md)]
