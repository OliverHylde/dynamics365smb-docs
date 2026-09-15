---
title: Salesperson - Sales Statistics (report)
description: Analyze sales, profit, and discount performance by salesperson for a selected period in Business Central.
author: kennieNP
ms.author: kepontop
ms.reviewer: bholtorf
ms.topic: concept-article
ms.search.keywords: reporting
ms.search.form: Report_114_Primary
ms.date: 2026-09-15
ms.service: dynamics-365-business-central
ms.custom:
 - ai-gen-docs-bap
 - ai-seo-date: 2026-09-15
ai.usage: ai-assisted
---

# Salesperson - Sales Statistics (report)

The **Salesperson - Sales Statistics** report shows sales, profit, and adjusted profit amounts in LCY and as percentages for each salesperson over a selected period. It also includes invoice discount, payment discount given, and payment tolerance amounts, giving a full picture of how each salesperson's sales activity translates into net profitability. The report is calculated from customer ledger entries filtered by salesperson code and posting date, and it provides column totals across all salespeople included in the selection.

You can filter the report by salesperson code to include only specific salespeople or teams, and by posting date to restrict the analysis to a specific period, such as a month, quarter, or fiscal year. Additional customer ledger entry filters, such as document type or customer, can be applied to narrow the underlying transactions used to calculate sales, profit, and discount amounts.

## Use cases

[!INCLUDE [report-114-scenario](../includes/report-114-scenario-include.md)]

Sales managers can use the report to:

* Compare sales and profit contributions across salespeople for a given period to identify top and bottom performers.
* Review adjusted profit and adjusted profit percentage to see how cost changes after posting affect each salesperson's actual profitability.
* Use invoice discount and payment discount given figures to assess how much margin was given away by each salesperson.,Controllers and finance teams can use the report to:

* Verify sales and profit totals in LCY by salesperson as part of period-end financial reviews.
* Check payment tolerance and payment discount amounts to understand their impact on realized profit.
* Use the report totals row to reconcile aggregated sales and profit figures against other financial reports.

## Try the report

Try the report here: [Salesperson - Sales Statistics](https://businesscentral.dynamics.com?report=114)

[!INCLUDE[ctrl-right-click-to-open-in-new-tab](../includes/ctrl-right-click-to-open-in-new-tab.md)]

## Related information

[Sales reports](../sales-reports.md)

[!INCLUDE[footer-include](../includes/footer-banner.md)]
