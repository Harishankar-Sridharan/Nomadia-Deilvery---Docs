# Reduced fixed duration

The Reduced Fixed Duration feature optimizes bulk deliveries by adjusting time estimates for multiple packages at a single location. It eliminates "paper" time gaps that occur when the system overestimates the duration of subsequent drops. This allows you to plan more missions daily and maximize your actual fleet capacity.

#### Getting Started

**Prerequisites**:

* Missions sharing a **Delivery Address**, **Pickup Address**, or **Group Identifier**.
* Operational data regarding realistic delivery times for first and subsequent packages.

**Steps**:

1. Open the **Configuration** module.

![](../.gitbook/assets/Case-Studies-Reduced_Fixed_Duration_timestamp_2_to_57.png)

2. Find the **Route** section in the left panel.

![](../.gitbook/assets/Case-Studies-Reduced_Fixed_Duration_timestamp_3_to_00.png)

3. Click on **Settings**.

![](../.gitbook/assets/Case-Studies-Reduced_Fixed_Duration_timestamp_3_to_03.png)

#### Feature Overview

* **Processing time for parcels**: This section defines how the optimization engine calculates time for grouped stops.

![](../.gitbook/assets/Case-Studies-Reduced_Fixed_Duration_timestamp_3_to_08.png)

* **First mission in the group**: This field sets the full duration for the initial delivery at a location.

![](../.gitbook/assets/Case-Studies-Reduced_Fixed_Duration_timestamp_3_to_13.png)

* **Following parcels in the group**: This field sets the reduced time for each additional package in the same group.

![](../.gitbook/assets/Case-Studies-Reduced_Fixed_Duration_timestamp_3_to_29.png)

#### How To: Set Up Reduced Fixed Duration

1. Navigate to **Configuration** > **Route** > **Settings**.

![](../.gitbook/assets/Case-Studies-Reduced_Fixed_Duration_timestamp_2_to_57_to_3_to_03.gif)

2. Locate the **Processing time for parcels** section.
3. Enter the full delivery time in the first field.
4. Enter the reduced time for additional packages in the second field.
5. Click the **Save** button to apply the changes.

![](../.gitbook/assets/Case-Studies-Reduced_Fixed_Duration_timestamp_3_to_56.png)

#### How To: Apply Optimized Durations

1. Open the **Mission** tab.

![](../.gitbook/assets/Case-Studies-Reduced_Fixed_Duration_timestamp_4_to_05.png)

2. Select the missions you want to optimize.

![](../.gitbook/assets/Case-Studies-Reduced_Fixed_Duration_timestamp_4_to_10_to_4_to_25.gif)

3. Click the **Actions** menu.

![](../.gitbook/assets/Case-Studies-Reduced_Fixed_Duration_timestamp_4_to_28.png)

4. Select your preferred optimization algorithm.
5. Review the updated durations in the **Simulation** module.

![](../.gitbook/assets/Case-Studies-Reduced_Fixed_Duration_timestamp_4_to_42.png)

#### Productivity Tips

* 💡 **Capacity Gains**: Matching system data to road reality unlocks capacity for missions that otherwise remain unassigned.
* 💡 **Automatic Grouping**: The system automatically identifies stops at the same address even without a specific group identifier.
* ⚠️ **Lost Productivity**: Using default settings for bulk orders overestimates route times and reduces your daily delivery volume.
