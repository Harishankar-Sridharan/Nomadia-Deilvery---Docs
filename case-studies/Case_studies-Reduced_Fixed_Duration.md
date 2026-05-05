# Case_studies-Reduced_Fixed_Duration
# Case-Studies

The Reduced Fixed Duration feature optimizes bulk deliveries by adjusting time estimates for multiple packages at a single location. It eliminates "paper" time gaps that occur when the system overestimates the duration of subsequent drops. This allows you to plan more missions daily and maximize your actual fleet capacity.

### Getting Started

Prerequisites:
* Missions sharing a **Delivery Address**, **Pickup Address**, or **Group Identifier**.
* Operational data regarding realistic delivery times for first and subsequent packages.

Steps:
1. Open the **Configuration** module.

![Frame at 2:57](../images/Case-Studies-Reduced_Fixed_Duration_timestamp_2_to_57.png "Configuration Module – The main setup area for route parameters.")

2. Find the **Route** section in the left panel.

![Frame at 3:00](../images/Case-Studies-Reduced_Fixed_Duration_timestamp_3_to_00.png "Route Section – Location of route-specific settings.")

3. Click on **Settings**.

![Frame at 3:03](../images/Case-Studies-Reduced_Fixed_Duration_timestamp_3_to_03.png "Settings – Access to the processing time configurations.")

### Feature Overview

* **Processing time for parcels**: This section defines how the optimization engine calculates time for grouped stops.

![Frame at 3:08](../images/Case-Studies-Reduced_Fixed_Duration_timestamp_3_to_08.png "Processing Time for Parcels – The configuration header for duration adjustments.")

* **First mission in the group**: This field sets the full duration for the initial delivery at a location.

![Frame at 3:13](../images/Case-Studies-Reduced_Fixed_Duration_timestamp_3_to_13.png "First Mission Field – Setting the default time for the initial delivery.")

* **Following parcels in the group**: This field sets the reduced time for each additional package in the same group.

![Frame at 3:29](../images/Case-Studies-Reduced_Fixed_Duration_timestamp_3_to_29.png "Following Parcels Field – Setting the incremental time for subsequent packages.")

### How To: Set Up Reduced Fixed Duration

1. Navigate to **Configuration** > **Route** > **Settings**.

![Flow 2:57 to 3:03](../images/Case-Studies-Reduced_Fixed_Duration_timestamp_2_to_57_to_3_to_03.gif "Navigation Flow – Moving from the main menu to route settings.")

2. Locate the **Processing time for parcels** section.
3. Enter the full delivery time in the first field.
4. Enter the reduced time for additional packages in the second field.
5. Click the **Save** button to apply the changes.

![Frame at 3:56](../images/Case-Studies-Reduced_Fixed_Duration_timestamp_3_to_56.png "Save Button – Finalizing the configuration changes.")

### How To: Apply Optimized Durations

1. Open the **Mission** tab.

![Frame at 4:05](../images/Case-Studies-Reduced_Fixed_Duration_timestamp_4_to_05.png "Mission Tab – Viewing all pending delivery tasks.")

2. Select the missions you want to optimize.

![Flow 4:10 to 4:25](../images/Case-Studies-Reduced_Fixed_Duration_timestamp_4_to_10_to_4_to_25.gif "Mission Selection – Highlighting multiple tasks for the optimization engine.")

3. Click the **Actions** menu.

![Frame at 4:28](../images/Case-Studies-Reduced_Fixed_Duration_timestamp_4_to_28.png "Actions Menu – Accessing optimization tools.")

4. Select your preferred optimization algorithm.
5. Review the updated durations in the **Simulation** module.

![Frame at 4:42](../images/Case-Studies-Reduced_Fixed_Duration_timestamp_4_to_42.png "Simulation Module – Visualizing the impact of reduced duration on the route.")

### Productivity Tips

* 💡 **Capacity Gains**: Matching system data to road reality unlocks capacity for missions that otherwise remain unassigned.
* 💡 **Automatic Grouping**: The system automatically identifies stops at the same address even without a specific group identifier.
* ⚠️ **Lost Productivity**: Using default settings for bulk orders overestimates route times and reduces your daily delivery volume.

