# Alert Management

Alert Threshold Management in **Nomadia Delivery** allows dispatchers to set operational trigger limits. This feature helps planners monitor disruptions like late departures, route delays, and overtime in real time. Configure alert rules to maintain full operational oversight and improve delivery reliability.

## Before you begin

Prerequisites:

* Active dispatcher account for **Nomadia Delivery**.

Setup Steps:

1. Open the **Configuration** page.

![Open the Configuration page](.gitbook/assets/AlertManagement_BeforeBegin_001.gif)

2. Click **Alert Threshold Management** under the route options.

![Click Alert Threshold Management under the route options](.gitbook/assets/AlertManagement_BeforeBegin_002.png)

## Feature overview

* **Red Icon**: Icon in the top-right corner that opens the pre-filter window.
* **Pre-filter**: Window to select previous search criteria and agency filters.
* **Quantitative Alert**: View that lists active numerical alert thresholds and live alerts.
* **Finished Alert**: View that archives completed and resolved alerts for historical tracking.
* **Add Alert**: Action button that opens the menu to create new alert rules.
* **Time Threshold**: Input box to specify duration limits for triggering alerts.
* **Late Departure**: Alert triggered when vehicle departure is delayed beyond the scheduled time.
* **ETA Delay**: Alert triggered when ETA (estimated time of arrival) is delayed.
* **ETA Change**: Alert triggered when the estimated arrival time for an order changes.
* **Overtime**: Alert triggered when vehicle arrival exceeds set working time limits.
* **Excessive Idle Time**: Alert triggered when a vehicle remains stationary for too long.

![The list of alert types, including Excessive Idle Time](.gitbook/assets/AlertManagement_FeatureOverview_001.png)

* **Validation Too Far From Address**: Alert triggered when the validation location is too far from the actual address.
* **Excessive Scan**: Alert triggered when package scan counts exceed expected limits.
* **Closing Soon**: Alert triggered when the destination's closing time is approaching.
* **Urgent Mission Response**: Alert triggered when a driver responds to an RZ machine (driver communication terminal) prompt.

![The list of alert types, including Urgent Mission Response](.gitbook/assets/AlertManagement_FeatureOverview_002.png)

## Pre-filter alerts

1. Click the **Red Icon** in the top right corner of the **Alert Threshold Management** page.
2. Select the previous search criteria from the **Previous** field.
3. Select the target agency from the **Agency** drop-down menu.
4. Click **Apply** to run the pre-filter.

<figure><img src=".gitbook/assets/AlertManagement_PreFilterAlerts_001.png" alt="Click Apply to run the pre-filter"><figcaption></figcaption></figure>

## View active and finished alerts

1. Review filtered alert details on the **Alert Threshold Management** page.

![Review filtered alert details on the Alert Threshold Management page](.gitbook/assets/AlertManagement_ViewActiveFinishedAlerts_001.png)

2. Select **Untreated Alert** to inspect active quantitative thresholds.

![Select Untreated Alert to inspect active quantitative thresholds](.gitbook/assets/AlertManagement_ViewActiveFinishedAlerts_002.png)

3. Select **Finished Alert** to inspect completed operational alerts.

<figure><img src=".gitbook/assets/AlertManagement_ViewActiveFinishedAlerts_003.png" alt="Select Finished Alert to inspect completed operational alerts"><figcaption></figcaption></figure>

## Configure a new alert threshold

1. Click **Add Alert** on the **Alert Threshold Management** page.

![Click Add Alert on the Alert Threshold Management page](.gitbook/assets/AlertManagement_ConfigureNewAlertThreshold_001.gif)

2. Select the desired alert type from the **Multiple Alerts** list.

![Select the desired alert type from the Multiple Alerts list](.gitbook/assets/AlertManagement_ConfigureNewAlertThreshold_002.png)

3. Enter the threshold value in the **Time Threshold** input field.

![Flow 1:43 to 1:56](.gitbook/assets/AlertManagement_ConfigureNewAlertThreshold_003.gif)

4. Click **Save** to confirm and activate the new alert threshold.

![Click Save to confirm and activate the new alert threshold](.gitbook/assets/AlertManagement_ConfigureNewAlertThreshold_004.gif)

5. Click **Cancel** to discard changes and close the setup window.

![Click Cancel to discard changes and close the setup window](.gitbook/assets/AlertManagement_ConfigureNewAlertThreshold_005.gif)

## Tips

{% hint style="info" %}
**Agency Pre-Filtering**: Select agency pre-filters to isolate specific operational units and speed up alert searches.
{% endhint %}

{% hint style="info" %}
**Historical Alert Auditing**: Check the finished alert tab to review historical alert resolutions and evaluate driver performance.
{% endhint %}

{% hint style="warning" %}
**Unsaved Configurations**: Avoid leaving the page without clicking **Save** when you configure thresholds, or your changes will be lost.
{% endhint %}

## Related topics

* [Route Editor](routeeditor.md)
* [Gantt View](ganttview.md)
* [Table view](tableview.md)
