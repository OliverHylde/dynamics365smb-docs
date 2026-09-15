---
title: Lot No Label (report)
description: Print lot number labels with barcodes for lot-tracked items directly from Business Central.
author: kennieNP
ms.author: kepontop
ms.reviewer: bholtorf
ms.topic: concept-article
ms.search.keywords: reporting
ms.search.form: Report_6628_Primary
ms.date: 2026-09-15
ms.service: dynamics-365-business-central
ms.custom:
 - ai-gen-docs-bap
 - ai-seo-date: 2026-09-15
ai.usage: ai-assisted
---

# Lot No Label (report)

The **Lot No Label** report generates printable labels for lot-tracked items, showing the item number, description, variant code, and lot number. It renders the lot number both as a Code 39 1D barcode and as a QR 2D barcode, so labels can be scanned with either type of barcode reader. The report uses a Word-based layout, making it easy to adapt the label design to specific printer or paper stock requirements.

You can filter the report by item number and other fields on the Lot No. Information table, which lets you narrow the label print run to a specific item, a range of items, or specific lots that need relabeling.

## Use cases

[!INCLUDE [report-6628-scenario](../includes/report-6628-scenario-include.md)]

Warehouse staff can use the report to:

* Print labels for newly received lots before putting them away in storage.
* Reprint a label for a lot whose original tag was damaged or lost.
* Scan the printed barcode or QR code during picking or put-away to confirm the correct lot.,Production and quality personnel can use the report to:

* Generate lot labels for items produced in a batch to support traceability requirements.
* Attach QR-coded labels to sample containers used for quality testing.
* Filter by item number to print labels only for the lots relevant to a specific production order.

## Try the report

Try the report here: [Lot No Label](https://businesscentral.dynamics.com?report=6628)

[!INCLUDE[ctrl-right-click-to-open-in-new-tab](../includes/ctrl-right-click-to-open-in-new-tab.md)]

## Related information

[All reports](../all-reports.md)

[!INCLUDE[footer-include](../includes/footer-banner.md)]
