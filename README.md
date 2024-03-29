# SQL Server / Azure SQL Database Toolkit

## Notes from the field

Sometimes I receive questions about the difference between Azure Data Studio (ADS) and SQL Server Management Studio (SSMS). The purpose of this topic is to enlist some key points to think about some use cases for each tool.

Talking about the tools:
- no replacement tool, but complementary tools
- no reason to ignore a tool

### SQL Server Management Studio

![SQL Server Management Studio](Images/SSMS.JPG)

  * Windows-only tool
  * For people who: 
    *   spend most of their time on database administration tasks, 
    *   need high availability, 
    *   use SQL Agent jobs and query store consumer, 
    *   are doing import/export of DACPACs, 
    *   need access to Registered Servers and want to control SQL Server services on Windows
  * Integrated with Azure Data Studio (right-click on a db in the Object Explorer or from Tools menu)
  * Data Classification to assist in support for compliance to GDPR, SOX, etc.
  * Enhanced Azure Data Factory support under Integration Services Catalogs
  * Enhancements and additions to properties dialogs for instance and database objects
  * You can work with: 
    *   Databases, Security Server Objects, Replication, PolyBase, Always On High Availability, Management, Integration services Catalogs, SQL Server Agent, XEvent Profiler
  * Top Features: 
    *   Live Query Stats, 
    *   Spatial Viewer, 
    *   Query Store, 
    *   XEvent Management, 
    *   Always On

### Azure Data Studio 

![Azure Data Studio](Images/ADS.JPG)

(formerly known as SQL Operations Studio)
  * First difference: cross platform, for Windows/MacOS/Linux
  * Built on the modern foundation of Microsoft's VS Code (most of the extensibility APIs are available)
  * Can be used to connect to on-prem and cloud-based data servers, including but not limited to:
    * SQL Server 2008-2019
    * Azure SQL
    * SQL Server Big Data Clusters
  * Engineered with the data platform user in mind
  * Its code is open and hosted in a GitHub project
  * Primarily development tool
  * Like SSMS, but for developers, less about management, more about code authorship
  * For people who: 
    *   use Mac / Linux as daily workstation, 
    *   need to source-control queries, 
    *   are connected to a SQL Server 2019 big data cluster, 
    *   can execute most administrative tasks via the integrated terminal using sqlcmd or Powershell
  * To create a unified experience across heterogenous data sources regardless of their form or location
  * Great to use with postgres/oracle/mysql
  * SQL Notebooks (based on Jupyter notebooks) which offer an experience of "interactive documentation"
  * Ability to work in other languages, such as PowerShell
  * You can work with: 
    *   Databases, Security, Server Objects, SQL Server Agent, XEvent Profiler
  * Top Features: 
    *   Marketplace Extensions to get new custom features, 
    *   Source control integration, 
    *   Task Pane, 
    *   Customizable dashboards, 
    *   Multiple color themes, including dark mode

### Visual Studio Code

  * SQL Object Explorer
  * SQLCMD
  * IntelliCode

## Download tools
[Download SQL Server Management Studio](https://docs.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms)

[Download Azure Data Studio](https://docs.microsoft.com/en-us/sql/azure-data-studio/download)