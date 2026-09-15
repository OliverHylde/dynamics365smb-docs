---
title: Inventory - Vendor Purchases (report)
description: Analyze invoiced quantities, cost amounts, and discount amounts by vendor and item to review inventory purchasing activity.
author: kennieNP
ms.author: kepontop
ms.reviewer: bholtorf
ms.topic: concept-article
ms.search.keywords: reporting
ms.search.form: Report_714_Primary
ms.date: 2026-09-15
ms.service: dynamics-365-business-central
ms.custom:
 - ai-gen-docs-bap
 - ai-seo-date: 2026-09-15
ai.usage: ai-assisted
---

# Inventory - Vendor Purchases (report)

The **Inventory - Vendor Purchases** report shows a list of the vendors that your company has purchased items from within a selected period. For each item and vendor combination, it displays invoiced quantity, cost amount, and discount amount, with subtotals per item and grand totals at the end of the report. It's used to analyze a company's item purchases and assess the relationship between purchase volume, cost, and discounts.

You can filter the report by item number, item number 2, search description, assembly BOM, and inventory posting group to narrow the report to specific items or item groups. You can also filter the underlying value entries by posting date to restrict the report to a specific period, and by source number or source posting group to limit results to particular vendors or vendor groups. Additional filters on variant code, location code, and global dimension codes let you refine the data to specific inventory dimensions.

## Use cases

[!INCLUDE [report-714-scenario](../includes/report-714-scenario-include.md)]

Purchasing managers can use the report to:

* Review which vendors supplied a given item over a selected period to evaluate sourcing decisions.
* Compare invoiced quantities and cost amounts across vendors for the same item to identify the most cost-effective supplier.
* Track discount amounts received from each vendor to verify negotiated terms are being applied correctly.,Inventory and supply chain teams can use the report to:

* Analyze purchase volume by item and vendor to plan future procurement and inventory replenishment.
* Identify items with concentrated vendor dependency to assess supply chain risk.
* Use item and posting date filters to focus the review on a specific product line or reporting period.,Controllers and finance teams can use the report to:

* Verify total cost amounts and discount amounts per vendor against purchase invoices for reconciliation.
* Review subtotals per item to spot unexpected cost or discount variances.
* Use the report totals to support period-end purchasing cost analysis.

## Try the report

Try the report here: [Inventory - Vendor Purchases](https://businesscentral.dynamics.com?report=714)

[!INCLUDE[ctrl-right-click-to-open-in-new-tab](../includes/ctrl-right-click-to-open-in-new-tab.md)]

## Related information

[Inventory reports](../inventory-reports.md)

[!INCLUDE[footer-include](../includes/footer-banner.md)]
