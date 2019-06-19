---

copyright:
  years: 2019
lastupdated: "2019-06-12"

keywords: high availability disaster recovery

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

# 一般高可用性及災難回復考量
{: #ha-dr}

所有 {{site.data.keyword.cloud_notm}} 通用版 (GA) 供應項目都有 99.95% 可用性的服務水準合約。{{site.data.keyword.cloud_notm}} {{site.data.keyword.ihsdbaas_postgresql_full}} 是在達拉斯提供的 GA 服務。每個位置有三個不同的資料中心以便備援。
{: shortdesc}

{{site.data.keyword.IBM_notm}} 在高可用性的安全環境中，管理您的資料庫。{{site.data.keyword.IBM_notm}} Secure Service Container 技術透過防篡改環境來保護系統。{{site.data.keyword.cloud_notm}} {{site.data.keyword.ihsdbaas_postgresql_full}} 提供靜止和使用中資料的加密。由於 {{site.data.keyword.IBM_notm}} 和協力廠商都無法存取您的資料，因此資料庫的備份及還原原則很重要。

請參閱[使用 IBM Cloud Object Storage 備份及還原資料庫](/docs/services/hyper-protect-dbaas-for-postgresql?topic=hyper-protect-dbaas-for-postgresql-backup_postgresql_databases)及[由 IBM 支援中心還原資料庫](/docs/services/hyper-protect-dbaas-for-postgresql?topic=hyper-protect-dbaas-for-postgresql-restore_postgresql_databases)，以瞭解如何備份及還原資料庫。

請參閱[如何確保運作零中斷？](/docs/overview?topic=overview-zero-downtime#zero-downtime)以進一步瞭解 {{site.data.keyword.cloud_notm}} 的高可用性及災難回復標準。您也可以尋找[服務水準合約](/docs/overview?topic=overview-zero-downtime#SLAs)的相關資訊。
