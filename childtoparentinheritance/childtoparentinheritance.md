# Child to Parent Inheritance

Child-to-parent inheritance automatically syncs data from child containers to parent containers. This feature saves dispatchers time by eliminating manual data entry. You will achieve real-time visibility of consolidated package statuses and aggregate cargo dimensions.

#### Getting Started

Before using this feature, ensure you meet the following requirements:

* An active user account for **Nomadia Delivery** with administrative privileges.
* Pre-configured parent and child container profiles.

Set up child-to-parent inheritance using these steps:

1. Go to **Configuration**.

![](../.gitbook/assets/childtoparentinheritance-childtoparentinheritance_timestamp_0_to_00_to_0_to_06.gif)

2. Click **Container Types**.

![](../.gitbook/assets/childtoparentinheritance-childtoparentinheritance_timestamp_0_to_10.png)

3. Scroll down to find the correct identifier.

![](../.gitbook/assets/childtoparentinheritance-childtoparentinheritance_timestamp_0_to_10_to_0_to_22.gif)

4. Click the correct identifier.

![](../.gitbook/assets/childtoparentinheritance-childtoparentinheritance_timestamp_0_to_22.png)

5. Locate the **Fetch status from child missions** toggle.
6. Toggle the setting to **Yes** if it is disabled.
7. Click **Save**.

![](../.gitbook/assets/childtoparentinheritance-childtoparentinheritance_timestamp_0_to_35.png)

8. Click **Sub status**.

![](../.gitbook/assets/childtoparentinheritance-childtoparentinheritance_timestamp_0_to_52_to_1_to_03.gif)

10. Click **Delivered** if you wish to deliver the parcel.

![](../.gitbook/assets/childtoparentinheritance-childtoparentinheritance_timestamp_1_to_11.png)

11. Check if **Scan all the items in the container** is enabled.
12. Toggle the option to **Yes** if it is disabled.

![](../.gitbook/assets/childtoparentinheritance-childtoparentinheritance_timestamp_1_to_22.png)

13. Click **Save**.

![](../.gitbook/assets/childtoparentinheritance-childtoparentinheritance_timestamp_1_to_30.png)

#### Feature Overview

* **Fetch status from child missions**: This setting enables parent containers to inherit progress status from child containers. It ensures automatic updates.
* **Scan all the items in the container**: This toggle forces operators to scan every child item before executing delivery. It guarantees delivery accuracy.
* **Mission status**: This field defines the current operational status of each individual child machine. It updates inherited status values.
* **Aggregate dimensions**: This configuration defines which physical dimensions sum up from child to parent containers. It aggregates size details.
* **Aggregate quantities**: This configuration defines which quantitative measurements sum up to the parent container. It aggregates weight and volume.

#### How To: Update Child Container Delivery Status

1. Click **Missions** on the main navigation panel.

![](../.gitbook/assets/childtoparentinheritance-childtoparentinheritance_timestamp_1_to_30_to_1_to_36.gif)

2. Click on the **child container**.

![](../.gitbook/assets/childtoparentinheritance-childtoparentinheritance_timestamp_1_to_51.png)

3. Change the **Mission status** to **Delivered**.

![](../.gitbook/assets/childtoparentinheritance-childtoparentinheritance_timestamp_2_to_00.png)

4. Click **Save**.

![](../.gitbook/assets/childtoparentinheritance-childtoparentinheritance_timestamp_2_to_08.png)

#### How To: Customize the List to View Parcel Status Attainment

1. Click **Custom field** inside the parent container view.

![](../.gitbook/assets/childtoparentinheritance-childtoparentinheritance_timestamp_2_to_42.png)

2. Click **Customize the list**.

![](../.gitbook/assets/childtoparentinheritance-childtoparentinheritance_timestamp_2_to_47.png)

3. Verify **Parcel status attainment** is in the display fields list.
4. Click **Save**.

![](../.gitbook/assets/childtoparentinheritance-childtoparentinheritance_timestamp_2_to_58.png)

5. Click the **Pencil icon** to edit another child machine.

![](../.gitbook/assets/childtoparentinheritance-childtoparentinheritance_timestamp_3_to_09.png)

6. Change the status to **Delivered**.

![](../.gitbook/assets/childtoparentinheritance-childtoparentinheritance_timestamp_3_to_16.png)

7. Click **Save**.

![](../.gitbook/assets/childtoparentinheritance-childtoparentinheritance_timestamp_3_to_25.png)

#### How To: Track Damaged Items and Not-Delivered Reasons

1. Click the **Pencil icon** of the damaged child container to edit it.

![](../.gitbook/assets/childtoparentinheritance-childtoparentinheritance_timestamp_3_to_09.png)

2. Change the status to **Not Delivered**.

![](../.gitbook/assets/childtoparentinheritance-childtoparentinheritance_timestamp_3_to_43.png)

3. Enter the specific reason in the **Reason** field.

![](../.gitbook/assets/childtoparentinheritance-childtoparentinheritance_timestamp_3_to_56.png)

4. Click **Save**.

![](../.gitbook/assets/childtoparentinheritance-childtoparentinheritance_timestamp_4_to_44.png)

The status will be reflected in the parent container. Please note that only positive statuses will be updated in the parent container.

<figure><img src="../.gitbook/assets/image (105).png" alt=""><figcaption></figcaption></figure>

#### How To: Configure and View Aggregated Dimensions and Quantities

1. Click **Configuration** on the top menu.

![](../.gitbook/assets/childtoparentinheritance-childtoparentinheritance_timestamp_4_to_19.png)

2. Click **Container size pallet**.
3. Choose your desired size metrics in **Aggregate dimensions**, such as length or height.

![](../.gitbook/assets/childtoparentinheritance-childtoparentinheritance_timestamp_4_to_41.png)

4. Choose your desired quantity metrics in **Aggregate quantities**, such as kg or volume.

![](../.gitbook/assets/childtoparentinheritance-childtoparentinheritance_timestamp_4_to_48.png)

5. Click **Save**.

![](../.gitbook/assets/childtoparentinheritance-childtoparentinheritance_timestamp_4_to_54.png)

6. Click **Missions**.

![](../.gitbook/assets/childtoparentinheritance-childtoparentinheritance_timestamp_4_to_56.png)

7. Enter the **length, height, quantity, weight (kg)**, and **volume values** for the first child container.

![](../.gitbook/assets/childtoparentinheritance-childtoparentinheritance_timestamp_5_to_24.png)

8. Click **Save**.

![](../.gitbook/assets/childtoparentinheritance-childtoparentinheritance_timestamp_5_to_49.png)

9. Select the second child container and enter its metrics.

![](../.gitbook/assets/childtoparentinheritance-childtoparentinheritance_timestamp_6_to_11.png)

10. Click **Save**.

![](../.gitbook/assets/childtoparentinheritance-childtoparentinheritance_timestamp_6_to_35.png)

11. Open the parent container to view the calculated totals.

![](../.gitbook/assets/childtoparentinheritance-childtoparentinheritance_timestamp_6_to_49.png)

#### Productivity Tips

* 💡 **Mobile Synchronization**: Use the mobile application to experience the same automatic child-to-parent data inheritance on the go.
* 💡 **Detailed Tracking**: Enter specific reasons when marking containers as not delivered to ensure accurate fleet reporting.
* ⚠️ **Parent Display Only**: Remember that overall parcel status only displays in the parent container, not in individual child containers.

***

