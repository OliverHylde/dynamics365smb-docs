---
title: Deferral Summary - Purchasing (report)
description: Analyze deferred purchasing expenses by vendor and posting period to verify recognition amounts and remaining balances.
author: kennieNP
ms.author: kepontop
ms.reviewer: bholtorf
ms.topic: concept-article
ms.search.keywords: reporting
ms.search.form: Report_1702_Primary
ms.date: 2026-09-10
ms.service: dynamics-365-business-central
ms.custom:
 - ai-gen-docs-bap
 - ai-seo-date: 2026-09-10
ai.usage: ai-assisted
---

# Deferral Summary - Purchasing (report)

The **Deferral Summary - Purchasing** report lists posted purchase deferral schedules grouped by vendor, showing the recognized and remaining amounts as of a chosen balance date. It draws on posted deferral headers and lines linked to posted invoices, credit memos, and return receipts, and calculates how much of each deferred amount has been recognized versus how much remains outstanding. The report is available in Excel and Word layouts, with the Excel version intended for data analysis and the Word version for printed output, and each vendor's totals are summarized at the end of the report.

You can filter the report by vendor number to limit results to specific vendors, by document number to focus on particular purchase documents, and by the Balance as of date, which determines the cutoff used to split amounts into recognized versus remaining deferred. You can also choose to print each vendor on a new page when multiple vendors are included, and hide posted deferral headers with a zero remaining amount unless the balance reaches zero within the current accounting period, which requires accounting periods to be configured.

## Use cases

[!INCLUDE [report-1702-scenario](../includes/report-1702-scenario-include.md)]

Controllers and finance teams can use the report to:

* Verify that deferred purchasing expenses are being recognized on schedule as of a specific accounting date.
* Reconcile remaining deferral balances across vendors before closing an accounting period.
* Identify posted invoices, credit memos, or return receipts with outstanding deferred amounts that still need recognition.,Accounts payable clerks can use the report to:

* Review deferral schedules by vendor to confirm start dates, number of periods, and deferral accounts are set up correctly.
* Filter by document number to trace a specific purchase transaction's deferral activity.
* Use the hide zero remaining amounts option to focus only on deferrals still requiring recognition.

## Try the report

Try the report here: [Deferral Summary - Purchasing](https://businesscentral.dynamics.com?report=1702)

[!INCLUDE[ctrl-right-click-to-open-in-new-tab](../includes/ctrl-right-click-to-open-in-new-tab.md)]

## Related information

[Finance reports](../finance-reports.md)

[!INCLUDE[footer-include](../includes/footer-banner.md)]
