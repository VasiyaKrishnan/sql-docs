---
title: Overview of SQL Server on Linux
description: This article describes how SQL Server runs on Linux and provides information on how to learn more.
author: VanMSFT 
ms.author: vanto
ms.date: 03/31/2022
ms.topic: conceptual
ms.prod: sql
ms.technology: linux
ms.assetid: 9dcc6a90-0add-42c2-815b-862e4e2a21ac
---
# SQL Server on Linux

[!INCLUDE [SQL Server - Linux](../includes/applies-to-version/sql-linux.md)]

::: moniker range="= sql-server-2017 || = sql-server-linux-2017"
Starting with SQL Server 2017, SQL Server runs on Linux. It's the same SQL Server database engine, with many similar features and services regardless of your operating system.

> [!TIP]
> [SQL Server 2019](sql-server-linux-overview.md?view=sql-server-ver15&preserve-view=true) is available! To find out what's new for Linux in the latest release, see [What's new in SQL Server 2019 for Linux](sql-server-linux-whats-new-2019.md?view=sql-server-ver15&preserve-view=true).
::: moniker-end

::: moniker range=">= sql-server-ver15 || >= sql-server-linux-ver15"
SQL Server 2019 runs on Linux. It's the same SQL Server database engine, with many similar features and services regardless of your operating system. To find out more about this release, see [What's new in SQL Server 2019 for Linux](sql-server-linux-whats-new-2019.md).
::: moniker-end

## Install

To get started, install SQL Server on Linux using one of the following quickstarts:

- [Install on Red Hat Enterprise Linux](quickstart-install-connect-red-hat.md)
- [Install on SUSE Linux Enterprise Server](quickstart-install-connect-suse.md)
- [Install on Ubuntu](quickstart-install-connect-ubuntu.md)
- [Run on Docker](quickstart-install-connect-docker.md)
- [Provision a SQL VM in Azure](/azure/virtual-machines/linux/sql/provision-sql-server-linux-virtual-machine?toc=/sql/toc/toc.json)

## Connect

After installation, connect to the SQL Server instance on your Linux machine. You can connect locally or remotely and with a variety of tools and drivers. The quickstarts demonstrate how to use the [sqlcmd](sql-server-linux-setup-tools.md) command-line tool. Other tools include the following:

| Tool | Tutorial |
|-----|-----|
| Visual Studio Code (VS Code) | [Use VS Code with SQL Server on Linux](../tools/visual-studio-code/sql-server-develop-use-vscode.md) |
| SQL Server Management Studio (SSMS) | [Use SSMS on Windows to connect to SQL Server on Linux](sql-server-linux-manage-ssms.md) |
| SQL Server Data Tools (SSDT) | [Use SSDT with SQL Server on Linux](sql-server-linux-develop-use-ssdt.md) |

## Explore

SQL Server 2017 and [!INCLUDE[SQL Server 2019](../includes/sssql19-md.md)] have the same underlying database engine on all supported platforms, including Linux. Therefore, many existing features and capabilities operate the same way on Linux. This area of the documentation exposes some of these features from a Linux perspective. It also calls out areas that have unique requirements on Linux.

If you are already familiar with SQL Server on Linux, review the release notes for general guidelines and known issues for this release:

- [SQL Server 2017 release notes](sql-server-linux-release-notes.md)
- [SQL Server 2019 release notes](sql-server-linux-release-notes-2019.md)

Then look at what's new:

- [What's new for SQL Server 2017](sql-server-linux-whats-new.md)
- [What's new for SQL Server 2019 on Linux](../sql-server/what-s-new-in-sql-server-2019.md#sql-server-on-linux)

> [!TIP]
> For answers to frequently asked questions, see the [SQL Server on Linux FAQ](sql-server-linux-faq.yml).

[!INCLUDE[Get Help Options](../includes/paragraph-content/get-help-options.md)]

[!INCLUDE[contribute-to-content](../includes/paragraph-content/contribute-to-content.md)]