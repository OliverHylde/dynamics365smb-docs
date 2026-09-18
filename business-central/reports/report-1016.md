---
title: Job Quote (report)
description: Print or export a project quote that lists project tasks and planning lines with quantities, unit prices, discounts, and total value.
author: kennieNP
ms.author: kepontop
ms.reviewer: bholtorf
ms.topic: concept-article
ms.search.keywords: reporting
ms.search.form: Report_1016_Primary
ms.date: 2026-09-18
ms.service: dynamics-365-business-central
ms.custom:
 - ai-gen-docs-bap
 - ai-seo-date: 2026-09-18
ai.usage: ai-assisted
---

# Job Quote (report)

The **Job Quote** report generates a customer-facing quote document for a project, showing the company and bill-to addresses, project number and description, and a breakdown of job tasks and their associated planning lines. It excludes budget-type planning lines and totals the quote based on unit price, quantity, and line discounts, giving customers a clear view of the estimated cost before work starts.

You can filter the report by project number (No.) and planning date to control which project is quoted and which planning lines fall within the relevant period, and by job task number to limit the report to specific tasks within the project.

## Use cases

[!INCLUDE [report-1016-scenario](../includes/report-1016-scenario-include.md)]

Project managers can use the report to:

* Generate a formal quote to send to a customer before starting a project.
* Review task-level pricing, including quantities, unit prices, and discounts, before finalizing an estimate.
* Verify that budget lines are excluded from the customer-facing total so only billable planning lines are quoted.,Sales representatives can use the report to:

* Provide customers with a printed or Word-based quote that reflects current project planning data.
* Present a task-by-task cost breakdown to help customers understand what they're paying for.
* Use the company logo and address layout options to produce a professional, branded quote document.,Controllers and finance teams can use the report to:

* Confirm that the total project value shown to the customer matches internal planning line calculations.
* Check currency formatting and discount amounts applied to each line before a quote is issued.

## Try the report

Try the report here: [Job Quote](https://businesscentral.dynamics.com?report=1016)

[!INCLUDE[ctrl-right-click-to-open-in-new-tab](../includes/ctrl-right-click-to-open-in-new-tab.md)]

## Related information

[Projectmanagement reports](../projectmanagement-reports.md)

[!INCLUDE[footer-include](../includes/footer-banner.md)]
