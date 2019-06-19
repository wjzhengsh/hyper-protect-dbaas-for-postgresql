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

# Considerações gerais de alta disponibilidade e recuperação de desastres
{: #ha-dr}

Todas as ofertas de disponibilidade geral (GA) do {{site.data.keyword.cloud_notm}} possuem um Acordo de Nível de Serviço de 99,95% de disponibilidade. O {{site.data.keyword.cloud_notm}} {{site.data.keyword.ihsdbaas_postgresql_full}} é um serviço GA que é oferecido em Dallas. Cada local possui três data centers diferentes para redundância.
{: shortdesc}

O {{site.data.keyword.IBM_notm}} hospeda seus bancos de dados em um ambiente altamente disponível e seguro. A tecnologia do {{site.data.keyword.IBM_notm}} Secure Service Container protege o sistema por meio de um
ambiente inviolável. O {{site.data.keyword.cloud_notm}} {{site.data.keyword.ihsdbaas_postgresql_full}} fornece criptografia de dados em repouso e em andamento. Como nem a {{site.data.keyword.IBM_notm}} nem um terceiro é capaz de acessar seus dados, uma política de backup e restauração para seus bancos de dados é essencial.

Consulte [Fazendo backup e restaurando seus bancos de dados usando o IBM Cloud Object Storage](/docs/services/hyper-protect-dbaas-for-postgresql?topic=hyper-protect-dbaas-for-postgresql-backup_postgresql_databases) e [Restaurando seus bancos de dados pelo Suporte IBM](/docs/services/hyper-protect-dbaas-for-postgresql?topic=hyper-protect-dbaas-for-postgresql-restore_postgresql_databases) para aprender como fazer backup e restaurar seus bancos de dados.

Consulte
[Como assegurar tempo de inatividade zero?](/docs/overview?topic=overview-zero-downtime#zero-downtime) para saber mais sobre os padrões de alta disponibilidade e de recuperação de desastre no {{site.data.keyword.cloud_notm}}. Também é possível localizar informações sobre [Acordos de Nível de Serviço](/docs/overview?topic=overview-zero-downtime#SLAs).
