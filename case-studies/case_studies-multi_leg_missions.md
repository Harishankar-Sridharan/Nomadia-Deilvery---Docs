# Multi Leg Missions

**Nomadia Delivery** uses multi-leg missions to track parcels across multiple hubs and agencies from first-mile pickup to last-mile delivery. This feature provides end-to-end visibility for complex supply chain operations by following a mission through every touchpoint. You will achieve a complete, trackable chain of custody for every parcel in your network.

#### Getting Started

To use this feature, ensure you have a user account with permissions for your specific agency.

* Access to the **Nomadia Delivery** back office.
* User account assigned to an **Origin Agency**.
* Configured routing infrastructure for automated zone assignment.

1. Log in to **Nomadia Delivery** as a user from the **Origin Agency**.

![](../.gitbook/assets/Case-Studies-Multi_Leg_Missions_timestamp_3_to_06.png)

#### Feature Overview

* **Agency**: Displays the current location of the mission and determines user visibility.
* **Origin Agency**: Marks the hub where the first-mile pickup begins.
* **Destination Agency**: Marks the final hub from which the customer receives the parcel.
* **Leg**: Indicates the current phase: Collection, Distribution, or Delivery.

![](../.gitbook/assets/Case-Studies-Multi_Leg_Missions_timestamp_2_to_20.png)

#### How To: Create a Multi-Leg Mission

1. Click on the **Mission** tab.

![](../.gitbook/assets/Case-Studies-Multi_Leg_Missions_timestamp_3_to_13_to_3_to_23.gif)

2. Select **Add** from the **Actions** menu.
3. Select **Cross-Docking** as the mission type, choose the required agency, and click **Next**.

![](../.gitbook/assets/Case-Studies-Multi_Leg_Missions_timestamp_3_to_30_to_3_to_38.gif)



4. Select the **Origin Agency** and the **Destination Agency**.
5. Set the **Leg** to **Collection**.
6. Enter the pickup and delivery location details.
7. Click **Add** to save the mission.

![](../.gitbook/assets/Case-Studies-Multi_Leg_Missions_timestamp_4_to_30.png)

#### How To: Update Mission Legs and Visibility (API /updateMultiLegStatusInformation)

1. Use the **Update multi-leg status information** endpoint to transition between legs.
2. Set the **Leg** to **Distribution** when the item is ready for mid-mile transit.

![](../.gitbook/assets/Case-Studies-Multi_Leg_Missions_timestamp_7_to_09_to_7_to_36.gif)

3. Navigate to the **Configuration** module to manage user visibility.
4. Select **Edit** for a specific user on the **Manage Users** page.
5. Open the **Rules and Rights** tab.

![](../.gitbook/assets/Case-Studies-Multi_Leg_Missions_timestamp_8_to_22_to_8_to_28.gif)

6. Activate the **Manage missions in transit** right.
7. Click **Save** to allow the user to see missions that have left their hub.

![](../.gitbook/assets/Case-Studies-Multi_Leg_Missions_timestamp_8_to_35.png)

8. Update the **Leg** to **Delivery** when the mission arrives at the final hub.
9. Set the **Status** to **Received** for the destination agency user.

![](../.gitbook/assets/Case-Studies-Multi_Leg_Missions_timestamp_9_to_12_to_9_to_58.gif)

#### How To: Audit Mission History

1. Open a mission in the **Editor**.
2. Select the **Logs** tab to view every status change and agency transition.

<figure><img src="../.gitbook/assets/msedge_bIBOxerQnR.png" alt=""><figcaption></figcaption></figure>

#### Productivity Tips

* 💡 **Automated Assignment**: Routing infrastructure automatically fills agents and sub-zones as soon as you create the mission.
* 💡 **Flexible Entry**: Create missions directly in distribution or delivery status if subcontractors handled the initial collection.
* ⚠️ **Visibility Loss**: Missions normally disappear from the origin view once they leave the hub unless specific rights are enabled.
