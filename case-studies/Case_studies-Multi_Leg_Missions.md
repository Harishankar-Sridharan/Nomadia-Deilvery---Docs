# Case_studies-Multi_Leg_Missions
# Case-Studies

**Nomadia Delivery** uses multi-leg missions to track parcels across multiple hubs and agencies from first-mile pickup to last-mile delivery. This feature provides end-to-end visibility for complex supply chain operations by following a mission through every touchpoint. You will achieve a complete, trackable chain of custody for every parcel in your network.

### Getting Started

To use this feature, ensure you have a user account with permissions for your specific agency.

*   Access to the **Nomadia Delivery** back office.
*   User account assigned to an **Origin Agency**.
*   Configured routing infrastructure for automated zone assignment.

1. Log in to **Nomadia Delivery** as a user from the **Origin Agency**.

![Frame at 3:06](../images/Case-Studies-Multi_Leg_Missions_timestamp_3_to_06.png "Login Screen – User enters the system from the starting agency location.")

### Feature Overview

*   **Agency**: Displays the current location of the mission and determines user visibility.
![Frame at 1:43](../images/Case-Studies-Multi_Leg_Missions_timestamp_1_to_43.png "Agency Field – Shows the mission's current hub.")

*   **Origin Agency**: Marks the hub where the first-mile pickup begins.

*   **Destination Agency**: Marks the final hub from which the customer receives the parcel.

*   **Leg**: Indicates the current phase: Collection, Distribution, or Delivery.
![Frame at 2:20](../images/Case-Studies-Multi_Leg_Missions_timestamp_2_to_20.png "Leg Field – Displays the current stage of the mission journey.")

### How To: Create a Multi-Leg Mission

1. Click on the **Mission** tab.

![Flow 3:13 to 3:23](../images/Case-Studies-Multi_Leg_Missions_timestamp_3_to_13_to_3_to_23.gif "Mission Tab – Navigating to the mission management section.")

2. Select **Add** from the **Actions** menu.

3. Choose the **Agency** and click **Next**.

![Flow 3:30 to 3:38](../images/Case-Studies-Multi_Leg_Missions_timestamp_3_to_30_to_3_to_38.gif "Add Mission – Starting the mission creation process for a cross-docking workflow.")

4. Switch the **Configuration** from **Default** to **Multi-leg**.

![Frame at 3:38](../images/Case-Studies-Multi_Leg_Missions_timestamp_3_to_38.png "Configuration Switch – Selecting the multi-leg setup to enter extra details.")

5. Select the **Origin Agency** and the **Destination Agency**.

6. Set the **Leg** to **Collection**.

7. Enter the pickup and delivery location details.

8. Click **Add** to save the mission.

![Frame at 4:30](../images/Case-Studies-Multi_Leg_Missions_timestamp_4_to_30.png "Add Mission – Finalizing the new multi-leg mission.")

### How To: Update Mission Legs and Visibility

1. Use the **Update multi-leg status information** endpoint to transition between legs.

2. Set the **Leg** to **Distribution** when the item is ready for mid-mile transit.

![Flow 7:09 to 7:36](../images/Case-Studies-Multi_Leg_Missions_timestamp_7_to_09_to_7_to_36.gif "Update Leg – Moving the mission into the distribution phase.")

3. Navigate to the **Configuration** module to manage user visibility.

4. Select **Edit** for a specific user on the **Manage Users** page.

5. Open the **Rules and Rights** tab.

![Flow 8:22 to 8:28](../images/Case-Studies-Multi_Leg_Missions_timestamp_8_to_22_to_8_to_28.gif "Rules and Rights – Accessing permission settings to adjust visibility.")

6. Activate the **Manage missions in transit** right.

7. Click **Save** to allow the user to see missions that have left their hub.

![Frame at 8:35](../images/Case-Studies-Multi_Leg_Missions_timestamp_8_to_35.png "Save Button – Confirming the new user rights.")

8. Update the **Leg** to **Delivery** when the mission arrives at the final hub.

9. Set the **Status** to **Received** for the destination agency user.

![Flow 9:12 to 9:58](../images/Case-Studies-Multi_Leg_Missions_timestamp_9_to_12_to_9_to_58.gif "Receive Mission – Updating the status and agency for the final delivery phase.")

### How To: Audit Mission History

1. Open a mission in the **Editor**.

2. Select the **Logs** tab to view every status change and agency transition.

![Frame at 10:53](../images/Case-Studies-Multi_Leg_Missions_timestamp_10_to_53.png "Mission Logs – Reviewing the full movement history of the parcel.")

### Productivity Tips

- 💡 **Automated Assignment**: Routing infrastructure automatically fills agents and sub-zones as soon as you create the mission.
- 💡 **Flexible Entry**: Create missions directly in distribution or delivery status if subcontractors handled the initial collection.
- ⚠️ **Visibility Loss**: Missions normally disappear from the origin view once they leave the hub unless specific rights are enabled.

