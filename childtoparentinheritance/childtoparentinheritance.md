# Child to parent inheritance

Child-to-parent inheritance automatically syncs data from child containers to parent containers. This feature saves dispatchers time by eliminating manual data entry. You will achieve real-time visibility of consolidated package statuses and aggregate cargo dimensions.

#### Getting started

Before using this feature, ensure you meet the following requirements:

* An active user account for **Nomadia Delivery** with administrative privileges.
* Pre-configured parent and child container profiles.

#### Feature overview

* **Fetch status from child missions**: This setting enables parent containers to inherit progress status from child containers. It ensures automatic updates.
* **Scan all the items in the container**: This toggle forces operators to scan every child item before executing delivery. It guarantees delivery accuracy.
* **Mission status**: This field defines the current operational status of each individual child mission. It updates inherited status values.
* **Partial status attainment**: The parent mission shows the percentage of child missions/parcels that have reached the status.
* **Aggregate dimensions**: This configuration defines which physical dimensions sum up from child to parent containers. It aggregates size details.
* **Aggregate quantities**: This configuration defines which quantitative measurements sum up to the parent container. It aggregates weight and volume.

#### Configure child to parent inheritance

Set up child-to-parent inheritance using these steps:

1. Go to **Configuration**.

![Go to Configuration](../.gitbook/assets/childtoparentinheritance-childtoparentinheritance_timestamp_0_to_00_to_0_to_06.gif)

2. Click **Container Types**.

![Click Container Types](../.gitbook/assets/childtoparentinheritance-childtoparentinheritance_timestamp_0_to_10.png)

3. Scroll down to find the correct identifier.

![Scroll down to find the correct identifier](../.gitbook/assets/childtoparentinheritance-childtoparentinheritance_timestamp_0_to_10_to_0_to_22.gif)

4. Click the correct identifier.

![Click the correct identifier](../.gitbook/assets/childtoparentinheritance-childtoparentinheritance_timestamp_0_to_22.png)

5. Locate the **Fetch status from child missions** toggle.
6. Toggle the setting to **Yes** if it is disabled.
7. Click **Save**.

![Click Save](../.gitbook/assets/childtoparentinheritance-childtoparentinheritance_timestamp_0_to_35.png)

#### Enable scanning of all items in the container for a specific sub-status

1. Click **Sub status**.

![Click Sub status](../.gitbook/assets/childtoparentinheritance-childtoparentinheritance_timestamp_0_to_52_to_1_to_03.gif)

2. Edit the sub-status for which you want to allow the mobile user to scan all the items in the container.

![Edit the sub-status for which you want to allow the mobile user to scan all](../.gitbook/assets/childtoparentinheritance-childtoparentinheritance_timestamp_1_to_11.png)

3. Check if **Scan all the items in the container** is enabled.
4. Toggle the option to **Yes** if it is disabled.

![Toggle the option to Yes if it is disabled](../.gitbook/assets/childtoparentinheritance-childtoparentinheritance_timestamp_1_to_22.png)

5. Click **Save**.

![Click Save](../.gitbook/assets/childtoparentinheritance-childtoparentinheritance_timestamp_1_to_30.png)

#### Update child container delivery status

1. Click **Missions** on the main navigation panel.

![Click Missions on the main navigation panel](../.gitbook/assets/childtoparentinheritance-childtoparentinheritance_timestamp_1_to_30_to_1_to_36.gif)

2. Click on the **child container**.

![Click on the child container](../.gitbook/assets/childtoparentinheritance-childtoparentinheritance_timestamp_1_to_51.png)

3. Change the **Mission status** to **Delivered**.

![Change the Mission status to Delivered](../.gitbook/assets/childtoparentinheritance-childtoparentinheritance_timestamp_2_to_00.png)

4. Click **Save**.

![Click Save](../.gitbook/assets/childtoparentinheritance-childtoparentinheritance_timestamp_2_to_08.png)

5. Updating the status of a child mission also updates the status of its parent mission.

#### Customize the list to view parcel status attainment

1. Click **Customize the list** from the **Actions** menu.

![Click Customize the list from the Actions menu](../.gitbook/assets/childtoparentinheritance-childtoparentinheritance_timestamp_2_to_47.png)

2. Verify **Parcel status attainment** is in the display fields list.
3. Click **Save**.

![Click Save](../.gitbook/assets/childtoparentinheritance-childtoparentinheritance_timestamp_2_to_58.png)

4. Click the **Pencil icon** to edit another child mission.

![Click the Pencil icon to edit another child mission](../.gitbook/assets/childtoparentinheritance-childtoparentinheritance_timestamp_3_to_09.png)

5. Change the status to **Delivered**.

![Change the status to Delivered](../.gitbook/assets/childtoparentinheritance-childtoparentinheritance_timestamp_3_to_16.png)

6. Click **Save**.

![Click Save](../.gitbook/assets/childtoparentinheritance-childtoparentinheritance_timestamp_3_to_25.png)

7. The percentage of parcel attainment shown on the parent mission changes to reflect the update.

#### Track damaged items and not-delivered reasons

1. Click the **Pencil icon** of the damaged child container to edit it.

![Click the Pencil icon of the damaged child container to edit it](../.gitbook/assets/childtoparentinheritance-childtoparentinheritance_timestamp_3_to_09.png)

2. Change the status to **Not Delivered**.

![Change the status to Not Delivered](../.gitbook/assets/childtoparentinheritance-childtoparentinheritance_timestamp_3_to_43.png)

3. Enter the specific reason in the **Reason** field.

![Enter the specific reason in the Reason field](../.gitbook/assets/childtoparentinheritance-childtoparentinheritance_timestamp_3_to_56.png)

4. Click **Save**.

![Click Save](../.gitbook/assets/childtoparentinheritance-childtoparentinheritance_timestamp_4_to_44.png)

The status will be reflected in the parent container. Please note that only positive statuses will be updated in the parent container.

The partial status attainment is updated based on the number of child missions that have a positive status.

<figure><img src="../.gitbook/assets/image (105).png" alt="The partial status attainment is updated based on the number of child missions"><figcaption></figcaption></figure>

#### Configure and view aggregated dimensions and quantities

1. Click **Configuration** on the top menu.

![Click Configuration on the top menu](../.gitbook/assets/childtoparentinheritance-childtoparentinheritance_timestamp_4_to_19.png)

2. Edit any container type from the list.
3. Choose your desired size metrics in **Aggregate dimensions**, such as length or height.

![Choose your desired size metrics in Aggregate dimensions, such as length](../.gitbook/assets/childtoparentinheritance-childtoparentinheritance_timestamp_4_to_41.png)

4. Choose your desired quantity metrics in **Aggregate quantities**, such as kg or volume.

![Choose your desired quantity metrics in Aggregate quantities, such as kg](../.gitbook/assets/childtoparentinheritance-childtoparentinheritance_timestamp_4_to_48.png)

5. Click **Save**.

![Click Save](../.gitbook/assets/childtoparentinheritance-childtoparentinheritance_timestamp_4_to_54.png)

6. Click **Missions**.

<figure><img src="../.gitbook/assets/image (1).png" alt="Click Missions"><figcaption></figcaption></figure>

7. Enter the **length, height, quantity, weight (kg)**, and **volume values** for the first child container.

![Enter the length, height, quantity, weight (kg), and volume values](../.gitbook/assets/childtoparentinheritance-childtoparentinheritance_timestamp_5_to_24.png)

8. Click **Save**.

![Click Save](../.gitbook/assets/childtoparentinheritance-childtoparentinheritance_timestamp_5_to_49.png)

9. Select the second child container and enter its metrics.

![Select the second child container and enter its metrics](../.gitbook/assets/childtoparentinheritance-childtoparentinheritance_timestamp_6_to_11.png)

10. Click **Save**.

![Click Save](../.gitbook/assets/childtoparentinheritance-childtoparentinheritance_timestamp_6_to_35.png)

11. Open the parent container to view the calculated totals.

<figure><img src="../.gitbook/assets/image (239).png" alt="Open the parent container to view the calculated totals"><figcaption></figcaption></figure>



#### Productivity tips

{% hint style="info" %}
**Mobile Synchronization**: Use the mobile application to experience the same automatic child-to-parent data inheritance on the go.
{% endhint %}

{% hint style="info" %}
**Detailed Tracking**: Enter specific reasons when marking containers as not delivered to ensure accurate fleet reporting.
{% endhint %}

{% hint style="warning" %}
**Parent Display Only**: The overall mission status is updated only on the parent mission. Sub-statuses are not passed from child missions to the parent, because each child mission can have a different sub-status.
{% endhint %}

***
