---
title: Contact Cover Sheet (report)
description: Generate a printable cover sheet that pairs a contact's mailing address with your company's address and banking details for outgoing correspondence or segment mailings.
author: kennieNP
ms.author: kepontop
ms.reviewer: bholtorf
ms.topic: concept-article
ms.search.keywords: reporting
ms.search.form: Report_5085_Primary
ms.date: 2026-09-18
ms.service: dynamics-365-business-central
ms.custom:
 - ai-gen-docs-bap
 - ai-seo-date: 2026-09-18
ai.usage: ai-assisted
---

# Contact Cover Sheet (report)

The **Contact Cover Sheet** report prints a cover page that shows the contact's address next to the company's address, along with the company's VAT registration number, giro number, bank name, and bank account number, and closes with a regards line. It can run for a single contact or for all contacts included in a marketing segment, and it can optionally log the printing as an interaction on the contact's record.

You can filter the report by contact number to select one or more specific contacts, or by segment number when the report is run from a marketing segment to include every contact linked to that segment. You can also turn on the Log Interaction option to record the cover sheet printing as an interaction entry for each contact included in the run.

## Use cases

[!INCLUDE [report-5085-scenario](../includes/report-5085-scenario-include.md)]

Sales and marketing teams can use the report to:

* Print a cover sheet for a single contact before sending a letter or fax.
* Generate cover sheets for every contact in a marketing segment in one run.
* Attach the company's address and bank details automatically so they don't need to be typed manually.,Relationship managers can use the report to:

* Enable the Log Interaction option to automatically record that a cover sheet was sent to a contact.
* Use the printed VAT registration, giro, and bank account details to support formal correspondence with contacts.
* Track outgoing cover sheet interactions as part of a contact's interaction history for follow-up.

## Try the report

Try the report here: [Contact Cover Sheet](https://businesscentral.dynamics.com?report=5085)

[!INCLUDE[ctrl-right-click-to-open-in-new-tab](../includes/ctrl-right-click-to-open-in-new-tab.md)]

## Related information

[Sales reports](../sales-reports.md)

[!INCLUDE[footer-include](../includes/footer-banner.md)]
