---
title: SN Label (report)
description: Print labels for serial number tracked items, showing the item description and serial number as both text and a 2D barcode.
author: kennieNP
ms.author: kepontop
ms.reviewer: bholtorf
ms.topic: concept-article
ms.search.keywords: reporting
ms.search.form: Report_6627_Primary
ms.date: 2026-09-15
ms.service: dynamics-365-business-central
ms.custom:
 - ai-gen-docs-bap
 - ai-seo-date: 2026-09-15
ai.usage: ai-assisted
---

# SN Label (report)

The **SN Label** report prints labels for items tracked by serial number, using data from the Serial No. Information table. Each label includes the item number, description, variant code, and the serial number rendered both as text with a 1D barcode and as a 2D QR code, so items can be quickly identified and scanned on the shop floor or in the warehouse.

You can filter the report by Item No. to limit the labels printed to serial numbers associated with a specific item, letting you generate a targeted batch of labels rather than printing for the entire Serial No. Information table.

## Use cases

[!INCLUDE [report-6627-scenario](../includes/report-6627-scenario-include.md)]

Warehouse and inventory staff can use the report to:

* Print serial number labels for newly received items before putting them into storage.
* Generate replacement labels for items whose original label is damaged or unreadable.
* Scan the 2D QR code on printed labels during picking, put-away, or cycle counting to quickly identify serial numbers.,Quality control and production teams can use the report to:

* Attach serial number labels to finished goods before they move to inventory or shipping.
* Verify that the item description and serial number printed on the label match the physical unit.
* Filter by item number to print labels only for the batch of items currently being processed.

## Try the report

Try the report here: [SN Label](https://businesscentral.dynamics.com?report=6627)

[!INCLUDE[ctrl-right-click-to-open-in-new-tab](../includes/ctrl-right-click-to-open-in-new-tab.md)]

## Related information

[Warehousemanagement reports](../warehousemanagement-reports.md)

[!INCLUDE[footer-include](../includes/footer-banner.md)]
