# Audit Logs

The **auditlogs** feature in Nomadia Delivery tracks and records system activity and recent changes made across the platform. Dispatchers and planners need it to maintain operational oversight, verify modifications, and audit configuration actions. Using this tool, you can review change history, filter logs by agent or timeframe, and export records to Excel.

## Before you begin

Prerequisites and system requirements:

* Active access to a **Nomadia Delivery** dispatcher or planner account.
* Permissions to view system **Configuration** and **History of Changes**.

Initial setup steps:

1. Navigate to **Configuration** in the main navigation menu.
2. Scroll down and click **History of Changes**.

![Scroll down and click History of Changes](.gitbook/assets/AuditLogs_BeforeBegin_001.png)

## Feature overview

* **Date and Time**: Displays the exact timestamp when a change occurred.
* **Login Details**: Shows the user account responsible for the modification.
* **Object Name**: Identifies the specific item or record changed.
* **Type**: Indicates the category of the recorded change.
* **Report**: Reflects user-defined reports created or modified in the platform.
* **Profile**: Displays the user profile associated with the activity.
* **Object ID**: Shows the unique system identifier for the modified item.
* **Reload**: Refreshes the log table to display recent changes if loading fails.
* **Prefilter**: Opens options to filter log entries by agent or time period.

## How To: View and Export Audit Logs

1. Navigate to **Configuration** and scroll down to click **History of Changes**.

![Navigate to Configuration and scroll down to click History of Changes](.gitbook/assets/AuditLogs_ViewExportAuditLogs_001.gif)

2. Review the table showing **Date and Time**, **Login Details**, **Object Name**, **Type**, **Report**, **Profile**, and **Object ID**.

![Review the table showing Date and Time, Login Details, Object Name, Type](.gitbook/assets/AuditLogs_ViewExportAuditLogs_002.png)

3. Click **Action** above the recent changes table.

![Click Action above the recent changes table](.gitbook/assets/AuditLogs_ViewExportAuditLogs_003.png)

4. Select export to download the log data into an Excel spreadsheet.

![Select export to download the log data into an Excel spreadsheet](.gitbook/assets/AuditLogs_ViewExportAuditLogs_004.png)

### Result

**Troubleshooting**

* **Logs or file fail to load**: Click **Reload** to fetch the most recent system changes.

![Logs or file fail to load: Click Reload to fetch the most recent system changes](.gitbook/assets/AuditLogs_ViewExportAuditLogs_005.png)

## How To: Filter Audit Logs by Agent and Time Period

1. Click **Refilter** on the **History of Changes** screen.

![Click Refilter on the History of Changes screen](.gitbook/assets/AuditLogs_FilterAuditLogsAgent_001.png)

2. Select the target agent or agency from the **Agent** dropdown menu.

![Select the target agent or agency from the Agent dropdown menu](.gitbook/assets/AuditLogs_FilterAuditLogsAgent_002.png)

3. Choose a time range under **Period**, such as last hours, twenty-four hours, seven days, or twenty-four days.

![Choose a time range under Period, such as last hours, twenty-four hours, seven](.gitbook/assets/AuditLogs_FilterAuditLogsAgent_003.png)

4. Select **Custom** to set a specific custom date range.

![Select Custom to set a specific custom date range](.gitbook/assets/AuditLogs_FilterAuditLogsAgent_004.png)

## Tips

{% hint style="info" %}
**Reload Failed Logs**: Click reload whenever log entries fail to load to display recent system changes immediately.
{% endhint %}

{% hint style="info" %}
**Custom Date Search**: Select the custom period option to isolate specific timeframe windows during audits.
{% endhint %}

{% hint style="warning" %}
**Unloaded Data Assumption**: Avoid assuming no changes occurred if the list is blank; click reload to fetch missing logs.
{% endhint %}

## Related topics

* [Mission Logs](8-6-missions/mission-logs.md)
* [Understanding the Missions Page](8-6-missions/understanding-the-missions-page/README.md)
