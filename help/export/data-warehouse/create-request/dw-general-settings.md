---
description: Steps that describe how to create a Data Warehouse request.
title: Data Warehouse request general settings
feature: Data Warehouse
---
# Data Warehouse request general settings

>[!AVAILABILITY]
>
>Some of the Data Warehouse features described in this article (and other Data Warehouse articles in this section) are available only in the Limited Testing phase of release and might not be available yet in your environment. 
>
>For information about which features are not yet available for all customers, as well as for information about the release timeline of these features, see the [release notes](/help/release-notes/latest.md).
>
>This note will be removed when the functionality is generally available. For information about the Analytics release process, see [Adobe Analytics feature releases](/help/release-notes/releases.md).

There are various configuration options available when creating a Data Warehouse request. The following information describes how to configure general settings for the request.

For information about how to begin creating a request, as well as links to other important configuration options, see [Create a Data Warehouse request](/help/export/data-warehouse/create-request/t-dw-create-request.md). 

To configure general settings for a Data Warehouse request:

1. Begin creating a Data Warehouse request in Adobe Analytics by selecting **[!UICONTROL Tools]** > **[!UICONTROL Data Warehouse]** > [!UICONTROL **Add**].

   For additional details, see [Create a Data Warehouse request](/help/export/data-warehouse/create-request/t-dw-create-request.md).

1. On the New Data Warehouse request page, select the [!UICONTROL **General settings**] tab.

   ![Report destination tab](assets/dw-general-settings.png)

1. Complete the following fields:

   |Option | Function | 
   |---------|----------|
   | Request name | This name appears on the main Data Warehouse page when managing requests. | 
   | Date ranges | Select the date range to be included in the report. <p>You can choose custom dates, or a preset date range. Preset ranges are relative to the date the report is sent.</p><p>The following preset options are available:</p><ul><li>Today</li><li>Yesterday</li><li>Last 7 days</li><li>Last 30 days</li><li>This week</li><li>Last week</li><li>Last 2 weeks</li><li>Last 3 weeks</li><li>Last 4 weeks</li><li>This month</li><li>Last month</li><li>Last hour</li></ul> | 
   | Granularity | <!--what does this setting do? It's not the schedule/frequency... --> The time granularity. Valid values are None, Hour, Day, Week, Month, Quarter, and Year.<p>Reporting granularity requires additional processing time. If you are reporting monthly granularity for an entire year, your reports process much faster if you submit a report request for each month.</p>| 

   {style="table-layout:auto"}

1. Continue configuring your Data Warehouse request on the [!UICONTROL **Build your report**] tab. For more information, see [Build a report for a Data Warehouse request](/help/export/data-warehouse/create-request/dw-request-build-report.md).