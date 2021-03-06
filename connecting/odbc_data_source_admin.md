---

copyright:
  years: 2014, 2019
lastupdated: "2018-09-25"

keywords:

subcollection: Db2whc

---

<!-- Attribute definitions --> 
{:external: target="_blank" .external}
{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
{:tip: .tip}
{:important: .important}
{:note: .note}
{:deprecated: .deprecated}
{:pre: .pre}

# Connecting with the ODBC Data Source Administrator
{: #con_prog_odbc_dsa}

Use the Microsoft ODBC Data Source Administrator tool to define a connection between an ODBC or CLI application and a {{site.data.keyword.dashdbshort_notm}} database.
{: shortdesc}

## Prerequisites
{: #prereq91}

Before attempting to connect to your {{site.data.keyword.dashdbshort_notm}} database, verify that you have the [prerequisites](/docs/Db2whc/connecting?topic=Db2whc-connect_ov#prereqs).

<!-- Before you can connect to your database, you must perform the following steps:

- [Verify prerequisites](prereqs.html), including installing driver packages, configuring your local environment, and downloading SSL certificates (if needed)
- Collect [connection information](credentials.html), including database details such as host name and port numbers, and connection credentials such as user ID and password -->

## Procedure
{: #proc91}

1. Install the [Db2 driver package](/docs/Db2whc?topic=Db2whc-dr_pkg#dr_pkg).

2. Open ODBC Data Source Administrator and create either a User DSN or System DSN for the Db2 driver package.
    
3. Click **Advanced** Settings. Enter following CLI parameters with their values for the {{site.data.keyword.dashdbshort_notm}} server: **Hostname**, **Port**, and **Database**.
    
4. For an SSL connection, enter CLI parameter **Security** with value `SSL`.
    
5. Click **Apply**.
    
6. To test the connection, return to main page of ODBC Data Source Administrator. Click **Configure** for the DSN that you created. Enter the user ID and password for the server and click **Connect**.

