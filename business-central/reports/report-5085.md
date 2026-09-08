---
title: Contact Cover Sheet (report)
description: Print a cover sheet with contact and company address details for mailing documents to a contact or segment.
author: kennieNP
ms.author: kepontop
ms.reviewer: bholtorf
ms.topic: concept-article
ms.search.keywords: reporting
ms.search.form: Report_5085_Primary
ms.date: 2026-09-08
ms.service: dynamics-365-business-central
ms.custom:
 - ai-gen-docs-bap
 - ai-seo-date: 2026-09-08
ai.usage: ai-assisted
---

# Contact Cover Sheet (report)

The **Contact Cover Sheet** report generates a printable cover sheet that shows the addresses of both the contact and the company, along with the document date, company VAT registration number, giro number, and bank details. It can be run directly for one or more contacts, or from within a segment, in which case it collects the contact information from the segment lines. The report also offers the option to log the mailing as an interaction on the contact's record.

You can filter the report by contact number when running it directly from the Contact list, or by segment number when running it from a segment, which determines which contacts' addresses are pulled into the cover sheet. You can also use the Log Interaction option on the request page to control whether the mailing is recorded as an interaction log entry for each contact.

## Use cases

[!INCLUDE [report-5085-scenario](../includes/report-5085-scenario-include.md)]

Sales and relationship managers can use the report to:

* Print a cover sheet before mailing brochures or letters to a single contact.
* Include company bank and VAT details automatically so recipients have payment information at hand.
* Enable Log Interaction to automatically record the mailing as an interaction on the contact's record.,Marketing and campaign coordinators can use the report to:

* Run the report from a segment to generate cover sheets for every contact included in a marketing segment.
* Ensure consistent company address and contact information appears on all outgoing segment mailings.
* Track which contacts in a segment received mailings by logging the interaction for each one.

## Try the report

Try the report here: [Contact Cover Sheet](https://businesscentral.dynamics.com?report=5085)

[!INCLUDE[ctrl-right-click-to-open-in-new-tab](../includes/ctrl-right-click-to-open-in-new-tab.md)]

## Related information

[Marketing reports](../marketing-reports.md)

[!INCLUDE[footer-include](../includes/footer-banner.md)]
