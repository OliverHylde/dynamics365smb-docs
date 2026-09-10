---
title: Deferral Summary - G/L (report)
description: Analyze how deferral entries affect general ledger accounts over time and reconcile deferred balances as of a chosen date.
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

The **Deferral Summary - G/L** report summarizes posted deferral activity for general ledger accounts, showing how deferred amounts are recognized over time. For each G/L account, it lists the posted deferral lines with their posting date, document type and number, deferral account, deferral start date, and number of periods, along with the amount recognized, the remaining amount deferred, and the total amount deferred as of the balance date you specify. The report includes subtotals per account and a grand total, and it can be run per G/L account or across a range of accounts.

You can filter the report by G/L account number to limit the analysis to specific accounts, and by the Balance as of date to control which posted deferral lines are counted as recognized versus remaining. You can also choose to print each G/L account on a new page when multiple accounts are included, and enable the option to hide posted deferral headers with a zero remaining amount unless the deferral ends within the current accounting period, which requires accounting periods to be set up.

## Use cases

[!INCLUDE [report-1700-scenario](../includes/report-1700-scenario-include.md)]

Controllers and finance teams can use the report to:

* Reconcile the remaining deferred balance on G/L accounts as of a specific period-end date.
* Verify that recognized amounts on deferral schedules match expected G/L activity for the period.
* Identify deferral headers with zero remaining balance to clean up completed deferral schedules.
* Review deferral start dates and number of periods to confirm deferral schedules were set up correctly.,Auditors and compliance reviewers can use the report to:

* Trace posted deferral lines back to their source documents using document type and document number.
* Confirm that amounts recognized versus remaining are correctly split based on the balance date.
* Review per-account totals and the report grand total to validate overall deferral reconciliation.

## Try the report

Try the report here: [Deferral Summary - G/L](https://businesscentral.dynamics.com?report=1700)

[!INCLUDE[ctrl-right-click-to-open-in-new-tab](../includes/ctrl-right-click-to-open-in-new-tab.md)]

## Related information

[Finance reports](../finance-reports.md)

[!INCLUDE[footer-include](../includes/footer-banner.md)]
