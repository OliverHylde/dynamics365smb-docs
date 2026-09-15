---
title: Deferral Summary - G/L (report)
description: Analyze deferred G/L amounts by account and period, showing recognized and remaining balances as of a chosen date.
author: kennieNP
ms.author: kepontop
ms.reviewer: bholtorf
ms.topic: concept-article
ms.search.keywords: reporting
ms.search.form: Report_1700_Primary
ms.date: 2026-09-15
ms.service: dynamics-365-business-central
ms.custom:
 - ai-gen-docs-bap
 - ai-seo-date: 2026-09-15
ai.usage: ai-assisted
---

# Deferral Summary - G/L (report)

The **Deferral Summary - G/L** report summarizes posted deferral activity for general ledger accounts, showing how deferred amounts are recognized over time. For each G/L account, it lists the posted deferral lines, including posting date, document type and number, deferral account, deferral start date, and number of periods, together with the amount recognized as of a chosen balance date, the remaining amount still deferred, and the total amount originally deferred. The report includes subtotals per account and grand totals, and it can be run to open a new page per account for easier review.

You can filter the report by G/L account number to limit the analysis to specific accounts, and by the balance as of date to control which posting dates count as recognized versus remaining. You can also choose to print each G/L account on a new page when multiple accounts are included, and you can hide posted deferral headers whose remaining amount is zero unless the deferral ends within the current accounting period, which requires accounting periods to be set up.

## Use cases

[!INCLUDE [report-1700-scenario](../includes/report-1700-scenario-include.md)]

Controllers and finance teams can use the report to:

* Reconcile deferred revenue or expense balances on specific G/L accounts as of period end.
* Verify that recognized amounts match expected recognition schedules before closing the books.
* Identify deferral lines with remaining balances that still need to be recognized in future periods.
* Review deferral activity account by account using the new-page-per-account print option.,Auditors and accounting reviewers can use the report to:

* Trace posted deferral entries back to their source documents and posting dates for audit evidence.
* Confirm that total deferred amounts, recognized amounts, and remaining amounts tie out for each account.
* Filter out fully recognized deferral headers to focus review on active or ending deferrals.

## Try the report

Try the report here: [Deferral Summary - G/L](https://businesscentral.dynamics.com?report=1700)

[!INCLUDE[ctrl-right-click-to-open-in-new-tab](../includes/ctrl-right-click-to-open-in-new-tab.md)]

## Related information

[Finance reports](../finance-reports.md)

[!INCLUDE[footer-include](../includes/footer-banner.md)]
