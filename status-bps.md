---

copyright:

  years: 2015, 2026
lastupdated: "2026-05-19"

keywords: IBM Cloud status, upcoming maintenance, stay up-to-date, monitor status, best practices, status monitoring

subcollection: support

---

{{site.data.keyword.attribute-definition-list}}

# Best practices for monitoring IBM Cloud status and maintenance
{: #best-practices}

Learn how to stay informed about IBM Cloud status and maintenance by using best practices for monitoring and planning.
{: shortdesc}

## Check for upcoming maintenance windows
{: #monbp-checmaintwin}

Check for upcoming maintenance windows posted on the {{site.data.keyword.cloud_notm}} console Dashboard page, at least one time every 24 hours, by using one of the following options:

* Check out the Planned maintenance widget on the [Dashboard](https://{DomainName}){: external}, and click **View events** to view all planned maintenance.
* Go directly to the [Status - Planned maintenance page](/status?selected=maintenance){: external}.

## Check for current maintenance windows or an incident in progress
{: #monbp-checcurmaninprog}

If you suspect that {{site.data.keyword.cloud_notm}} isn't functioning as expected, check the Status page for current maintenance windows or an incident in progress. To report an incident that isn't already listed on the Status page, open a support case. For more information about opening a support case, see [Creating support cases](/docs/support?topic=support-open-case).

In most cases, {{site.data.keyword.cloud_notm}} can be used normally during a maintenance window. However, minor interruptions of a service can't always be avoided. Running applications typically remain available even if the application management functions, such as starting and stopping apps, are temporarily interrupted. To maximize the availability of your running applications, run at least three instances of each application.

## Take advantage of multiple {{site.data.keyword.cloud_notm}} locations
{: #monbp-multpreg}

All users of {{site.data.keyword.cloud_notm}} automatically have access to the Dallas, London, Frankfurt, Sydney, Washington DC, and Tokyo locations. The {{site.data.keyword.cloud_notm}} Global Operations team manages all locations to avoid maintenance impacts and minimize the risk of incidents that affect all locations at the same time.

You can check the status of your locations from the dashboard on the {{site.data.keyword.cloud_notm}} status widget. To view specific events, click **View all**.

## Subscribing to email notifications
{: #monbp-subscribing}

As a Lite account owner, you can select whether to receive email notifications about {{site.data.keyword.cloud_notm}} platform unplanned events, such as outages, and planned events, such as maintenance. As a Pay-As-You-Go or Subscription account, you can choose whether to receive {{site.data.keyword.cloud_notm}} infrastructure email notifications about unplanned events, maintenance, and announcements. For more information, see [Setting email preferences](/docs/support?topic=support-email-prefs).
