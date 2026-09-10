---
title: Deferral Summary - G/L (report)
description: Analyze how G/L deferral entries recognize and remain deferred across posting periods as of a chosen balance date.
author: kennieNP
ms.author: kepontop
ms.reviewer: bholtorf
ms.topic: concept-article
ms.search.keywords: reporting
ms.search.form: Report_1700_Primary
ms.date: 2026-09-10
ms.service: dynamics-365-business-central
ms.custom:
 - ai-gen-docs-bap
 - ai-seo-date: 2026-09-10
ai.usage: ai-assisted
---

# Deferral Summary - G/L (report)

The **Deferral Summary - G/L** report summarizes posted deferral activity for General Ledger accounts, showing how amounts originally scheduled for deferral are split between recognized and remaining balances as of a specified date. For each G/L account, it lists the posted deferral header lines with posting date, document type and number, deferral account, deferral start date, and number of periods, together with the amount recognized, the remaining amount deferred, and the total amount to defer. The report includes subtotals per account and grand totals, and it is intended primarily for data analysis in Excel, though a print-oriented Word layout is also available.

You can filter the report by G/L account number to limit the analysis to specific accounts, by the balance as of date to control which posting dates count as recognized versus still deferred, and by the New Page per G/L Acc. option to start each account on a new page in print layouts. You can also enable Hide Zero Remaining Amounts to suppress posted deferral headers whose remaining amount is zero, unless the deferral ends within the current accounting period based on the balance date, which requires accounting periods to be set up.

## Use cases

[!INCLUDE [report-1700-scenario](../includes/report-1700-scenario-include.md)]

Controllers and finance teams can use the report to:

* Reconcile the remaining deferred balance on G/L accounts as of month-end or period-end close.
* Verify that amounts recognized to date match expected recognition schedules for deferred revenue or expenses.
* Identify deferral headers that should have fully recognized by a given date but still show remaining amounts.
* Export the report to Excel to build supporting schedules for audit or management reporting.,Accountants performing period-end reviews can use the report to:

* Review posted deferral lines by document and posting date to trace how a specific transaction is being recognized over time.
* Use the Hide Zero Remaining Amounts option to focus only on deferrals that still have activity in the current accounting period.
* Print a per-account breakdown using the New Page per G/L Acc. option when preparing account-level reconciliation packages.

## Try the report

Try the report here: [Deferral Summary - G/L](https://businesscentral.dynamics.com?report=1700)

[!INCLUDE[ctrl-right-click-to-open-in-new-tab](../includes/ctrl-right-click-to-open-in-new-tab.md)]

## Related information

[Finance reports](../finance-reports.md)

[!INCLUDE[footer-include](../includes/footer-banner.md)]
