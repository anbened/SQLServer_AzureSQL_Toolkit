# SQL Server / Azure SQL Database | Notes from the field

- no replacement tool, but complementary tools
- no reason to ignore a tool

## SQL Server Management Studio
  * Windows tool
  * For people who 
    *   spend most of your time on database administration tasks, 
    *   high availability, 
    *   SQL Agent jobs and query store consumer, 
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

## Azure Data Studio 
(formerly known as SQL Operations Studio)
  * It's the database, not the instance
  * Built on the modern foundation of Microsoft's VS Code (most of the extensibility APIs are available)
  * Engineered with the data platform user in mind
  * Open source (GitHub project)/ cross-platform tool (platform independent)
  * Primarily development tool
  * Like SSMS, but for developers, less about management, more about code authorship
  * For people who 
    *   use Mac / Linux as daily workstation, 
    *   don't need to tune queries, 
    *   need to source-control queries, 
    *   are connected to a SQL Server 2019 big data cluster, 
    *   can execute most administrative tasks via the integrated terminal using sqlcmd or Powershell
  * To create a unified experience across heterogenous data sources regardless of their form or location
  * Great to use with postgres/oracle/mysql
  * SQL Notebooks (based on Jupyter notebooks) which offer an experience of "interactive documentation"
  * Ability to work in other languages, such as PowerShell
  * You can work with: 
    *   Databases, Security, Server Objects
  * Top Features: 
    *   Marketplace Extensions to get new custom features, 
    *   Source control integration, 
    *   Task Pane, 
    *   Customizable dashboards, 
    *   Dark Mode

## Visual Studio Code
  * SQL Object Explorer
  * SQLCMD
  * IntelliCode
