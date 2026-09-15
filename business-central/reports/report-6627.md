---
title: SN Label (report)
description: Print serial number labels for tracked items, including both a linear barcode and a QR code.
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

The **SN Label** report generates printable labels for items tracked by serial number. For each serial number information record, it prints the item number, description, and serial number, along with the serial number encoded as both a Code39 barcode and a QR code, making it easy to identify and scan individual items throughout the warehouse.

You can filter the report by item number, letting you limit label printing to serial numbers associated with a specific item or range of items.

## Use cases

[!INCLUDE [report-6627-scenario](../includes/report-6627-scenario-include.md)]

Warehouse staff can use the report to:

* Print labels for newly received serial-tracked items before put-away.
* Scan the barcode or QR code on the label during picking, put-away, or shipping to quickly identify the correct serial number.
* Reprint labels for items whose original labels are damaged or lost.,Inventory managers can use the report to:

* Generate labels in bulk for a specific item or item range using the item number filter.
* Ensure serial-tracked items are properly labeled to support accurate physical inventory counts.
* Standardize label output across the warehouse using the predefined Word layout.

## Try the report

Try the report here: [SN Label](https://businesscentral.dynamics.com?report=6627)

[!INCLUDE[ctrl-right-click-to-open-in-new-tab](../includes/ctrl-right-click-to-open-in-new-tab.md)]

## Related information

[All reports](../all-reports.md)

[!INCLUDE[footer-include](../includes/footer-banner.md)]
