---
title: Reminder (report)
description: Print or email issued reminders that show overdue customer invoices, interest, fees, and VAT so customers can settle outstanding balances.
author: kennieNP
ms.author: kepontop
ms.reviewer: bholtorf
ms.topic: concept-article
ms.search.keywords: reporting
ms.search.form: Report_117_Primary
ms.date: 2026-09-15
ms.service: dynamics-365-business-central
ms.custom:
 - ai-gen-docs-bap
 - ai-seo-date: 2026-09-15
ai.usage: ai-assisted
---

# Reminder (report)

The **Reminder** report prints or emails an issued reminder document to a customer, listing the overdue documents, remaining amounts, interest, additional fees, and VAT that make up the total amount due. It pulls data from the Issued Reminder Header and Issued Reminder Line tables, and can render either as an RDLC layout for printing or as a Word-based email body layout, including company and customer address information, bank details, and VAT specifications.

You can filter the report by reminder number using the No. filter on the Issued Reminder Header, and set options to show internal information intended only for internal use, log the reminder as a customer interaction in the Interaction Log Entry table, show amounts that are not yet due, and include multiple interest rate (MIR) detail lines in the printed output.

## Use cases

[!INCLUDE [report-117-scenario](../includes/report-117-scenario-include.md)]

Accounts receivable clerks can use the report to:

* Print or email a formal reminder to a customer for overdue invoices after the reminder has been issued.
* Include interest amounts and additional fees calculated on the overdue balance so the customer sees the full amount due.
* Enable Log Interaction to automatically record the reminder as a customer interaction for follow-up tracking.
* Turn on Show Not Due Amounts to give the customer visibility into upcoming amounts alongside the overdue ones.,Controllers and finance teams can use the report to:

* Review the VAT amount specification section to confirm VAT bases, percentages, and amounts are correctly broken out per VAT identifier.
* Use Show Internal Information to check dimension values and MIR (multiple interest rate) details before a reminder is sent externally.
* Verify the local currency VAT specification and exchange rate details when reminders are issued in a foreign currency.

## Try the report

Try the report here: [Reminder](https://businesscentral.dynamics.com?report=117)

[!INCLUDE[ctrl-right-click-to-open-in-new-tab](../includes/ctrl-right-click-to-open-in-new-tab.md)]

## Related information

[All reports](../all-reports.md)

[!INCLUDE[footer-include](../includes/footer-banner.md)]
