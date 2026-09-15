---
title: Notification Email (report)
description: Generate the email body sent to users who are registered to receive Business Central notifications, such as approval requests and overdue approvals.
author: kennieNP
ms.author: kepontop
ms.reviewer: bholtorf
ms.topic: concept-article
ms.search.keywords: reporting
ms.search.form: Report_1320_Primary
ms.date: 2026-09-15
ms.service: dynamics-365-business-central
ms.custom:
 - ai-gen-docs-bap
 - ai-seo-date: 2026-09-15
ai.usage: ai-assisted
---

# Notification Email (report)

The **Notification Email** report builds the body of the email that Business Central sends to a user who is registered for notifications. It pulls data from the **Notification Entry** table that triggered the email, resolves the recipient, the related document (sales, purchase, journal, customer, vendor, item, incoming document, or approval-related record), and renders a Word layout with a greeting, an explanation of the notification, a link to the document, up to three labeled fields with values, a details section, and a link to the notification settings page.

You can filter the report by nothing on the request page, because it has no visible request page fields — it is run programmatically by the notification engine for a single **Notification Entry** record at a time. The content of each email is instead determined by the entry's type (New Record, Approval, or Overdue), the recipient user ID stored on the entry, and the record the notification was triggered by, which together control which document link, field labels, and values appear in the generated email.

## Use cases

[!INCLUDE [report-1320-scenario](../includes/report-1320-scenario-include.md)]

System administrators and IT support can use the report to:

* Verify that the notification email layout correctly reflects the document type, number, and action link for a given Notification Entry before troubleshooting delivery issues.
* Confirm that the settings link included in the email points users to the correct Notification Setup page filtered to their user ID.
* Check that sender and recipient information (Created By, Sender User ID) is populated correctly when diagnosing notification content problems.,Approvers and business users can use the report to:

* Receive an email with a direct link to the sales, purchase, or journal document that needs approval or attention.
* Read the due date and change details included in the email when a notification is for an approval request or an overdue approval.
* Use the included settings link to change how and when they receive future notifications without contacting an administrator.

## Try the report

Try the report here: [Notification Email](https://businesscentral.dynamics.com?report=1320)

[!INCLUDE[ctrl-right-click-to-open-in-new-tab](../includes/ctrl-right-click-to-open-in-new-tab.md)]

## Related information

[All reports](../all-reports.md)

[!INCLUDE[footer-include](../includes/footer-banner.md)]
