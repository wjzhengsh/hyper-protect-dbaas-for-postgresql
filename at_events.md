---

copyright:
  years: 2019
lastupdated: "2019-08-28"

keywords: Activity tracker events

subcollection: hyper-protect-dbaas-for-postgresql

---

{:shortdesc: .shortdesc}
{:external: target="_blank" .external}
{:codeblock: .codeblock}
{:pre: .pre}
{:screen: .screen}
{:tip: .tip}
{:note: .note}
{:important: .important}

# {{site.data.keyword.cloudaccesstrailshort}} events
{: #activity-tracker-events}

Use the {{site.data.keyword.cloudaccesstrailfull}} service to track how users and applications interact with {{site.data.keyword.cloud_notm}} {{site.data.keyword.ihsdbaas_postgresql_full}}.
{: shortdesc}

{{site.data.keyword.at_full_notm}} records user-initiated activities that change the state of a service in {{site.data.keyword.cloud_notm}}. You can use this service to investigate abnormal activity and critical actions and to comply with regulatory audit requirements. In addition, you can be alerted about actions as they happen. The events that are collected comply with the Cloud Auditing Data Federation (CADF) standard. For more information, see the [getting started tutorial for {{site.data.keyword.at_full_notm}}](/docs/services/Activity-Tracker-with-LogDNA?topic=logdnaat-getting-started#getting-started).

## Viewing the events
{: #view-activity-tracker-events}

{{site.data.keyword.cloudaccesstrailshort}} events are only available in the {{site.data.keyword.cloudaccesstrailshort}} with LogDNA instance in your account that is located in **Dallas** region.

<!--
{{site.data.keyword.cloudaccesstrailshort}} events are available in the {{site.data.keyword.cloudaccesstrailshort}} **account domain** that is available in the {{site.data.keyword.cloud_notm}} region where the events are generated.
-->

## List of events
{: #list-activity-tracker-events}

The following table lists the actions that generate an event:

| Action                 | Description                               |
| ---------------------- | ----------------------------------------- |
| `cluster.create` | Create a database cluster                 |
| `cluster.delete` | Delete a database cluster                 |
| `database.create` | Create a database                  |
| `database.delete` | Delete a database                  |
| `user.create`     | Create a database user                    |
| `user.delete`     | Delete a database user                    |
| `instance.start` | Start a database service instance         |
| `instance.stop`  | Stop a database service instance          |
| `instance.restart`  | Restart a database service instance          |
| `log.get`       | Download a log file |
{: caption="Table 1. Actions that generate {{site.data.keyword.cloudaccesstrailfull_notm}} events"}

For the event of `cluster.create` and `cluster.delete`, the {{site.data.keyword.cloudaccesstrailfull_notm}} service does not record the account name and IP address of the user who performs the action. The value of `initiator.name` and `host.address` in the log indicates the service ID of Cloud Broker and the IP address of Cloud Broker respectively.
{: note}
