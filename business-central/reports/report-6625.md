---
title: Item GTIN Label (report)
description: Print item labels that show the item number, description, and GTIN barcode in both 1D and 2D formats.
author: kennieNP
ms.author: kepontop
ms.reviewer: bholtorf
ms.topic: concept-article
ms.search.keywords: reporting
ms.search.form: Report_6625_Primary
ms.date: 2026-09-15
ms.service: dynamics-365-business-central
ms.custom:
 - ai-gen-docs-bap
 - ai-seo-date: 2026-09-15
ai.usage: ai-assisted
---

# Item GTIN Label (report)

The **Item GTIN Label** report generates printable labels for items, showing the item number, description, and the item's Global Trade Item Number (GTIN) encoded as both a 1D barcode and a 2D QR code. It uses a Word-based layout designed for label printing, so you can attach the labels directly to physical items or shelves for scanning at receiving, picking, or point-of-sale stations.

You can filter the report by item number to control which items are included, letting you print labels for a single item, a range of items, or your entire item list in one run.

## Use cases

[!INCLUDE [report-6625-scenario](../includes/report-6625-scenario-include.md)]

Warehouse and inventory staff can use the report to:

* Print shelf labels for a range of items so bin locations can be scanned during putaway and picking.
* Generate labels for newly received items that include a scannable GTIN for use with handheld barcode readers.
* Reprint labels for damaged or missing tags on existing inventory without regenerating other item data.,Retail and point-of-sale teams can use the report to:

* Produce item labels with GTIN barcodes for checkout scanning at the register.
* Print QR-code labels for items that need to be scanned by mobile devices or self-checkout kiosks.
* Batch-print labels for a product line before it goes on the sales floor.

## Try the report

Try the report here: [Item GTIN Label](https://businesscentral.dynamics.com?report=6625)

[!INCLUDE[ctrl-right-click-to-open-in-new-tab](../includes/ctrl-right-click-to-open-in-new-tab.md)]

## Related information

[All reports](../all-reports.md)

[!INCLUDE[footer-include](../includes/footer-banner.md)]
