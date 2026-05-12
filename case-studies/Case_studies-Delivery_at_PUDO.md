# Case_studies-Delivery_at_PUDO
# Case-Studies

The PUDO (Pick-Up Drop-Off) delivery flow allows drivers to redirect parcels to local relay points when customers are unavailable. This feature eliminates the need for expensive re-delivery runs and keeps your depot backlog manageable. You will achieve higher first-attempt resolution rates and provide better flexibility for your customers.

### Getting Started

Before using this feature, ensure the following requirements are met:
*   PUDO network data is configured in the system.
*   The **fallback delivery in PUDO** field is enabled for the specific mission.
*   Sub-statuses for failed PUDO drops (e.g., "PUDO full") are defined in the **configuration menu**.

1. Create a route in the back-office.
2. Select the checkbox for the route you want to share in the **route table**.

![Frame at 0:38](../images/Case-Studies-Delivery_at_PUDO_timestamp_0_to_38.png "Route table – Selecting a specific route for publication.")

3. Click the **actions** button.

![Frame at 0:41](../images/Case-Studies-Delivery_at_PUDO_timestamp_0_to_41.png "Actions menu – Accessing the route management options.")

4. Select **publish on mobile app**.

![Frame at 0:45](../images/Case-Studies-Delivery_at_PUDO_timestamp_0_to_45.png "Actions menu – Selecting the option to send the route to the driver.")

5. Click **OK** to confirm the publication.

![Frame at 0:52](../images/Case-Studies-Delivery_at_PUDO_timestamp_0_to_52.png "Confirmation dialog – Finalizing the publication to the driver app.")

### Feature Overview

*   **PUDO point selection page**: Displays a list of preloaded relay locations near the customer address.

![Frame at 2:02](../images/Case-Studies-Delivery_at_PUDO_timestamp_2_to_02.png "PUDO point selection page – Viewing the list of nearby preloaded relay points.")

*   **Search radius slider**: Allows the driver to increase or decrease the distance to find more relay points.

![Frame at 2:14](../images/Case-Studies-Delivery_at_PUDO_timestamp_2_to_14.png "Search radius slider – Adjusting the distance to find more relay locations.")

*   **PUDO delivery location ID**: Automatically records the specific point where the driver deposited the parcel.

![Frame at 4:09](../images/Case-Studies-Delivery_at_PUDO_timestamp_4_to_09.png "Mission Editor – The field showing the exact location of the PUDO drop.")

*   **Mission logs tab**: Tracks every action from the first delivery attempt to the final PUDO deposit.

![Frame at 4:24](../images/Case-Studies-Delivery_at_PUDO_timestamp_4_to_24.png "Logs Tab – Reviewing the time-stamped sequence of all delivery actions.")

### How To: Manage Failed Deliveries

**Driver: Redirecting a Parcel**

1. Tap the shared route in the mobile app.
2. Load the vehicle and tap **validate my loading**.

![Flow 1:16 to 1:29](../images/Case-Studies-Delivery_at_PUDO_timestamp_1_to_16_to_1_to_29.gif "Mobile App – The sequence of opening a route and validating the vehicle load.")

3. Tap **start my route**.
4. At the customer location, select **do not deliver** if the customer is absent.

![Flow 1:35 to 1:45](../images/Case-Studies-Delivery_at_PUDO_timestamp_1_to_35_to_1_to_45.gif "Mobile App – Marking a delivery attempt as failed due to customer absence.")

5. Select the **customer not available** sub-status.
6. Swipe the slider to adjust the search radius if necessary.
7. Select a **PUDO point** from the list.
8. Confirm the status and continue other deliveries.
9. When ready to drop, tap the relay point notification in the **route details**.
10. Select the mission and use the **scanner** to deposit the parcel.

![Flow 3:08 to 3:24](../images/Case-Studies-Delivery_at_PUDO_timestamp_3_to_08_to_3_to_24.gif "Mobile App – Scanning the parcel barcode to confirm the PUDO deposit.")

11. Capture the **signature** and a **photograph** to validate the drop.

**Planner: Verifying the Drop**

1. Click the **refresh button** in the back-office to see real-time updates.

![Frame at 3:51](../images/Case-Studies-Delivery_at_PUDO_timestamp_3_to_51.png "Back-office – Refreshing the view to see the synchronized delivery status.")

2. Open the mission in the **editor** to verify the **PUDO delivery location ID**.
3. Check the **logs tab** for a full sequence of time-stamped actions.

**Troubleshooting: PUDO Issues**

If a PUDO location is full or closed:
1. Mark the mission as **not delivered at the PUDO location**.
2. Select the specific sub-status, such as **PUDO full** or **PUDO closed**.
3. The mission will appear as **unsolved** for the planner.
4. Include the mission in the next **planning cycle** for a redelivery attempt.

### Productivity Tips

- 💡 **Automatic Detection**: The system automatically identifies PUDO locations within a 5 km radius of the route.
- 💡 **Preloaded Data**: Drivers do not need to search manually as nearest options are preloaded before they open the app.
- 💡 **Real-time Sync**: Information synchronizes with the back-office immediately after the driver confirms the drop.
- ⚠️ **Accurate Sub-statuses**: Always use the correct sub-status for full or closed PUDO points to ensure the mission is tracked for redelivery.

