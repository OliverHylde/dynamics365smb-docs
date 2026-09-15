---
title: Reference No Label (report)
description: Print item labels that show the item number, description, unit of measure, and a reference number barcode in both 1D and 2D formats.
author: kennieNP
ms.author: kepontop
ms.reviewer: bholtorf
ms.topic: concept-article
ms.search.keywords: reporting
ms.search.form: Report_6626_Primary
ms.date: 2026-09-15
ms.service: dynamics-365-business-central
ms.custom:
 - ai-gen-docs-bap
 - ai-seo-date: 2026-09-15
ai.usage: ai-assisted
---

# Reference No Label (report)

The **Reference No Label** report generates printable labels for items based on their item reference records. Each label includes the item number, description, unit of measure, and the reference number encoded as both a Code39 barcode and a QR code, letting warehouse staff scan the label with 1D or 2D scanners. The report merges data into a Word layout designed for label printing, and if no description is stored on the item reference, it retrieves the description from the related item record.

You can filter the report by Item No. to limit the labels printed to specific items, or run it without filters to print labels for all item reference records in the system.

## Use cases

[!INCLUDE [report-6626-scenario](../includes/report-6626-scenario-include.md)]

Warehouse and inventory staff can use the report to:

* Print labels for incoming items that use a vendor or customer reference number instead of the internal item number.
* Generate scannable barcode labels to attach to bins, boxes, or pallets for faster picking and put-away.
* Verify item descriptions and units of measure printed on labels match what's recorded on the item card.,Production and shop floor teams can use the report to:

* Print reference number labels for components tracked by an external catalog or cross-reference number.
* Use the QR code on the label to quickly scan and look up item information on handheld devices.
* Batch print labels for a range of items before a production run using the Item No. filter.

## Try the report

Try the report here: [Reference No Label](https://businesscentral.dynamics.com?report=6626)

[!INCLUDE[ctrl-right-click-to-open-in-new-tab](../includes/ctrl-right-click-to-open-in-new-tab.md)]

## Related information

[All reports](../all-reports.md)

[!INCLUDE[footer-include](../includes/footer-banner.md)]
