---
title: Campaign Management
layout: default
nav_order: 3
description: Official build releases, updates, and guides for the QSms app — your solution for reliable SMS campaigns.
---

QSMS provides a robust set of tools to help you efficiently create, manage, and send your SMS campaigns. This guide covers everything from composing your messages to setting up advanced sending schedules.

### Creating Your First SMS Campaign

To begin, you'll typically start by creating a new campaign within the QSMS application.

- Navigate to Campaigns: From the main dashboard, tap on the "Add" icon at the bottom of the screen. It will take you to the "Campaigns" section.
- Here you will be presented with a screen to create a new campaign. The screen will contain 3 major components:
  - **SMS Preview:** A live preview of your SMS content as you type.
  - **SMS Content:** A text area where you can compose your SMS message. At the bottom corner there will be a character and SMS segments counter.
  - **Recipient Selection:** The group of recipients you will be sending your message to. Here you can provide a comma separated list of numbers or import them from a CSV file. At the bottom corner there will be a total number of recipients counter.
- Once you have entered your message and selected recipients, tap on the "Submit" button at the top.

{: .note }
At the bottom of the screen, you will find a "Estimated Cost" section. This displays the estimated total cost of your campaign based on the number of recipients and SMS segments.

### Automated Scheduling & Sending Options

QSMS offers powerful scheduling features to ensure your messages are delivered at the optimal time, whether it's an immediate send or a complex drip campaign.

**Immediate Sending:** If you wish to send the campaign immediately after creation, select the "Send Now" or "Immediate" option.

**Automated Scheduling:** For scheduled campaigns, QSMS provides fine grained control. You can go into the app settings and choose the sms submission frequency and chunk size. After you have set these parameters, your sms will be sent at the specified intervals. The minimum allowed time interval is 15 minutes and it can be customized as per your requirements.

{: .note }
At this moment, the customization of the time interval is not available. It will be available in the next release.

### Managing Ongoing Campaigns

After setting up and initiating your campaigns, QSMS allows you to monitor and manage them.

- **Campaign Dashboard:** Access a dashboard where you can see the status of all your active, scheduled, and completed campaigns.
- **Pause/Resume Campaigns:** Temporarily stop a running campaign or resume a paused one.
- **Edit Scheduled Campaigns:** Modify the content or schedule of campaigns that have not yet started sending.
- **View Basic Stats:** While full analytics are an [upcoming feature](/releases), you will be able to see basic delivery status for your messages.

For more detailed information on managing your recipient lists, please refer to the [Recipient Management (CSV Import)](/recipients.html) page.