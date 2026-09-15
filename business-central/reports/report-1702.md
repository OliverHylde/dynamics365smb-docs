---
title: Deferral Summary - Purchasing (report)
description: Analyze deferred purchasing expenses by vendor and posting period to verify accrual accuracy.
author: kennieNP
ms.author: kepontop
ms.reviewer: bholtorf
ms.topic: concept-article
ms.search.keywords: reporting
ms.search.form: Report_1702_Primary
ms.date: 2026-09-15
ms.service: dynamics-365-business-central
ms.custom:
 - ai-gen-docs-bap
 - ai-seo-date: 2026-09-15
ai.usage: ai-assisted
---

# Deferral Summary - Purchasing (report)

The **Deferral Summary - Purchasing** report summarizes deferral activity for purchase transactions, grouped by vendor and showing recognized versus remaining deferred amounts. It draws on posted deferral headers and lines for posted purchase invoices, credit memos, and return receipts, calculating how much of each deferral schedule has been recognized as of a selected balance date and how much remains outstanding. The report is intended primarily for data analysis in Excel, though a Word layout is also available for printed output.

You can filter the report by vendor number to focus on one or more vendors, and by document number to narrow results to specific purchase transactions. The **Balance as of** date filter determines the cutoff date used to split deferral amounts into recognized versus remaining amounts. The **New Page per Vendor** option starts each vendor's data on a new page when printing, and **Hide Zero Remaining Amounts** suppresses deferral headers whose remaining amount is zero, unless the deferral reaches zero within the current accounting period based on the balance date.

## Use cases

[!INCLUDE [report-1702-scenario](../includes/report-1702-scenario-include.md)]

Controllers and finance teams can use the report to:

* Review deferred purchasing costs as of a chosen balance date to verify that accrual amounts are correctly recognized.
* Reconcile expense deferral balances by vendor before closing an accounting period.
* Identify purchase deferral schedules with remaining amounts still to be recognized in future periods.
* Hide fully recognized deferral headers to focus review on open deferral schedules.,Accounts payable staff can use the report to:

* Trace deferred amounts back to specific posted purchase invoices, credit memos, or return receipts.
* Confirm deferral start dates and number of periods used for a vendor's purchase transactions.
* Export the report to Excel for further analysis of vendor deferral totals.

## Try the report

Try the report here: [Deferral Summary - Purchasing](https://businesscentral.dynamics.com?report=1702)

[!INCLUDE[ctrl-right-click-to-open-in-new-tab](../includes/ctrl-right-click-to-open-in-new-tab.md)]

## Related information

[Finance reports](../finance-reports.md)

[!INCLUDE[footer-include](../includes/footer-banner.md)]
