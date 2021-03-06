﻿**************************************************************************************************************************************************************************************** 
**IMPORTANT**:  

1. If you decided to use Azure Data Factory as a host for your SSIS packages ensure that you have created a Virtual Network in Azure and configured a VPN or Express Route that connects to on your on-premises network.

2. If you are using SSIS as part of SQL Server, ensure that you have the ability to deploy, configure and schedule packages.
**************************************************************************************************************************************************************************************** 


# Lab 4:  Configuring the SSIS ETL Project

Use the following steps to complete this Lab:
1.  Open the [SSIS ETL](https://github.com/pleblanc72/Insights-in-a-Day/tree/master/4%20-%20Lab%204%20Configuring%20the%20SSIS%20ETL%20Project/SSIS/AtRisk) Visual Studio (VS) project.
2.  Once VS is open click View > Solution Explorer it is not visible.
3.  Double-click **Project.params**, which is located directly below **AtRisk.SSIS** in the Solution Explorer.
4.  Set the value for each parameter corresponding to your environment.  You may not have an Azure AS server running at time, so you can leave the TabularDatabase and TabularServer parameters blank for now.
5.  Set the value for the Initial Load Parameter for False.
6.  Click the save button and execute the MasterDWLoad.dtsx package.


[-> Next Section - Configuring and Deploying Azure Azure Analysis Services Tabular Model](https://github.com/pleblanc72/Insights-in-a-Day/tree/master/5%20-%20Lab%205%20Configuring%20and%20Deploying%20Azure%20Analysis%20Services%20Tabular%20Model)

[<- Back to Creating and Deploying the ETL Environment](https://github.com/pleblanc72/Insights-in-a-Day/tree/master/3%20-%20Lab%203%20Creating%20and%20Deploying%20the%20ETL%20Environment)

[<- Back to Creating and Deploying the Data Warehouse and Schema](https://github.com/pleblanc72/Insights-in-a-Day/tree/master/2%20-%20Lab%202%20Creating%20and%20Deploying%20the%20Data%20Warehouse%20and%20Schema)

[<- Back to Validating Views with the Data Dictionary](https://github.com/pleblanc72/Insights-in-a-Day/tree/master/1%20-%20Lab%201%20Validating%20Data%20Dictionary)

[<- Back to Main Page](https://github.com/pleblanc72/Insights-in-a-Day)