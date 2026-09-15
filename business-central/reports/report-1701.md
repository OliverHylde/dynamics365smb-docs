---
title: Deferral Summary - Sales (report)
description: Analyze deferred sales revenue by customer and period to reconcile recognized and remaining deferral balances.
author: kennieNP
ms.author: kepontop
ms.reviewer: bholtorf
ms.topic: concept-article
ms.search.keywords: reporting
ms.search.form: Report_1701_Primary
ms.date: 2026-09-15
ms.service: dynamics-365-business-central
ms.custom:
 - ai-gen-docs-bap
 - ai-seo-date: 2026-09-15
ai.usage: ai-assisted
---

# Deferral Summary - Sales (report)

The **Deferral Summary - Sales** report shows detailed deferral activity for posted sales documents, grouped by customer. For each deferral line, it shows the posting date, document type and number, line description, deferral account, deferral start date, and number of periods, along with the amount recognized as of a chosen balance date, the remaining amount still deferred, and the total amount originally deferred. The report includes totals for recognized, remaining, and total deferred amounts, and is available in Excel and Word layouts, with the Excel layout designed for further data analysis.

You can filter the report by customer number to limit results to specific customers, and by document number to focus on particular sales documents. The Balance as of date determines the cutoff used to split deferral amounts into recognized versus remaining amounts. You can also choose to print each customer on a new page, and hide posted deferral headers that have a zero remaining amount unless the remaining amount reaches zero within the current accounting period (this option requires accounting periods to be set up).

## Use cases

[!INCLUDE [report-1701-scenario](../includes/report-1701-scenario-include.md)]

Controllers and finance teams can use the report to:

* Reconcile deferred sales revenue balances as of a specific accounting date before closing a period.
* Review recognized versus remaining deferred amounts for each customer to verify revenue recognition accuracy.
* Identify deferral schedules that should have fully recognized by the current period but still show a remaining balance.
* Export the Excel layout to perform further analysis or build supporting schedules for audits.,Accounts receivable clerks can use the report to:

* Look up deferral details for a specific customer or document, including start date and number of periods.
* Trace deferred amounts back to the originating posted invoice, credit memo, or return receipt.
* Print a per-customer report page to include with customer account reviews or statements.

## Try the report

Try the report here: [Deferral Summary - Sales](https://businesscentral.dynamics.com?report=1701)

[!INCLUDE[ctrl-right-click-to-open-in-new-tab](../includes/ctrl-right-click-to-open-in-new-tab.md)]

## Related information

[Finance reports](../finance-reports.md)

[!INCLUDE[footer-include](../includes/footer-banner.md)]
