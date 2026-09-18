---
title: Email Merge (report)
description: Generate personalized mail merge letters to contacts using segment content, salutations, and salesperson signature details.
author: kennieNP
ms.author: kepontop
ms.reviewer: bholtorf
ms.topic: concept-article
ms.search.keywords: reporting
ms.search.form: Report_5084_Primary
ms.date: 2026-09-18
ms.service: dynamics-365-business-central
ms.custom:
 - ai-gen-docs-bap
 - ai-seo-date: 2026-09-18
ai.usage: ai-assisted
---

# Email Merge (report)

The **Email Merge** report generates a personalized document for each contact in a segment, combining company information, a formal or informal salutation, free-text content supplied from the segment, and a closing signature with the salesperson's name and job title. It's typically triggered from a marketing segment to produce mail merge letters for a batch of contacts, using either an RDLC layout or a Word layout for the output.

You can filter the report by the segment line data passed in from the calling segment, such as the contact, language code, salesperson code, and document date, which determine which contact's salutation, address details, and salesperson signature appear on each generated letter.

## Use cases

[!INCLUDE [report-5084-scenario](../includes/report-5084-scenario-include.md)]

Marketing and CRM employees can use the report to:

* Produce personalized letters for all contacts in a marketing segment in a single run.
* Automatically pull the correct formal or informal salutation based on each contact's language code.
* Include free-text campaign content defined in the segment without manually editing each letter.,Salespersons can use the report to:

* Send follow-up correspondence to contacts with their own name and job title shown as the signature.
* Use the Word body-only layout to merge letters into standard company letterhead templates.
* Reference the company address and logo automatically pulled from Company Information.

## Try the report

Try the report here: [Email Merge](https://businesscentral.dynamics.com?report=5084)

[!INCLUDE[ctrl-right-click-to-open-in-new-tab](../includes/ctrl-right-click-to-open-in-new-tab.md)]

## Related information

[Sales reports](../sales-reports.md)

[!INCLUDE[footer-include](../includes/footer-banner.md)]
