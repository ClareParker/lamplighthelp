# 12.6.0    {{Comm}}s - linking with Campaign Monitor

> CampaignMonitor is mass mailing software that provides advanced reporting on your email communications. {{Lamplight}} can automatically link to and use CampaignMonitor to send out email campaigns. 

CampaignMonitor ([www.campaignmonitor.com](www.campaignmonitor.com)) is a powerful email marketing tool that lets you send mass email campaigns and report on the number that get successfully delivered, read, or forwarded. It can also manage subscriptions and unsubscriptions. This is a paid-for service: you will need to open an account with CampaignMonitor and ensure that you have sufficient credits to send the emails you want to. You'll then need to tell {{Lamplight}} your CampaignMonitor API details.

As an overview, the link between the two systems works like this:

  1. You set up a {{group}} in {{Lamplight}} that you want to use as a mailing list in CampaignMonitor, and then ask {{Lamplight}} to tell CampaignMonitor the email addresses it will need to send to.
  2. You compose your email in {{Lamplight}}, and when you're ready you can ask {{Lamplight}} to tell CampaignMonitor to send it for you.
  3. You can view basic campaign statistics in {{Lamplight}}, or log in to CampaignMonitor to access full reports
  4. If anyone clicks on an 'unsubscribe' link in your email, CampaignMonitor receives this notification and passes it on to {{Lamplight}}. {{Lamplight}} updates the 'send email' option on the profile of the person.

Please check the terms and conditions of CampaignMonitor carefully, and in particular their guidance about [permission to send emails](http://www.campaignmonitor.com/resources/entry/558 /about-permission/). Please be certain that you have the permission (as described in the page linked to) for the email addresses you will be sending to. If you don't you may well get in trouble, and may get us in trouble too. We don't want that! 

###### comms module

