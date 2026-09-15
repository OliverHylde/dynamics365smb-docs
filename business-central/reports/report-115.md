---
title: Salesperson - Commission (report)
description: Calculate and review commission amounts earned by salespeople based on invoiced sales and profit for a selected period.
author: kennieNP
ms.author: kepontop
ms.reviewer: bholtorf
ms.topic: concept-article
ms.search.keywords: reporting
ms.search.form: Report_115_Primary
ms.date: 2026-09-15
ms.service: dynamics-365-business-central
ms.custom:
 - ai-gen-docs-bap
 - ai-seo-date: 2026-09-15
ai.usage: ai-assisted
---

# Salesperson - Commission (report)

The **Salesperson - Commission** report lists invoices and credit memos posted for each salesperson over a selected period, showing the sales amount, profit amount, and adjusted profit amount for each entry along with the commission calculated on each of those figures based on the salesperson's commission percentage. The report also provides subtotals per salesperson and grand totals for all salespeople, with all amounts shown in LCY.

You can filter the report by salesperson code to limit the report to specific salespeople, and by posting date on the customer ledger entries to restrict the report to a specific period. Both filters are echoed in the report header so you can confirm which salespeople and date range the figures cover.

## Use cases

[!INCLUDE [report-115-scenario](../includes/report-115-scenario-include.md)]

Sales managers can use the report to:

* Review each salesperson's invoiced sales and profit for a chosen period before approving commission payouts.
* Compare commission amounts calculated on sales versus profit to decide which basis to use for payment.
* Filter the report to a single salesperson to verify individual performance and commission calculations.,Controllers and finance teams can use the report to:

* Use the adjusted profit and adjusted profit commission columns to account for changes in the original cost of goods sold before finalizing payouts.
* Run the report for a specific posting date range to reconcile commission expense with the corresponding accounting period.
* Check subtotals per salesperson and the grand total to validate total commission liability before posting entries.

## Try the report

Try the report here: [Salesperson - Commission](https://businesscentral.dynamics.com?report=115)

[!INCLUDE[ctrl-right-click-to-open-in-new-tab](../includes/ctrl-right-click-to-open-in-new-tab.md)]

## Related information

[Sales reports](../sales-reports.md)

[!INCLUDE[footer-include](../includes/footer-banner.md)]
