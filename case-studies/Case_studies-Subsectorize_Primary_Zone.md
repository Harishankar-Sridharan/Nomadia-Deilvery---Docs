# Case_studies-Subsectorize_Primary_Zone
# Case-Studies

This feature allows you to split a primary zone into smaller, balanced territories automatically using the territory management module. Dispatchers need this to create fair and logical areas for specific delivery agents or teams. By following this guide, you will achieve three geographically split sub-zones ready for immediate assignment.

### Getting Started

Before you begin sub-sectoring, ensure your system meets these requirements:

*   A primary zone must be built with mapped postal codes and defined geography.
*   Historical mission data, including delivery points and coordinates, must be loaded into the mission page.

Follow these initial steps:

1.  Open your **study** and navigate to the **zone tab**.

![Frame at 1:35](../images/Case-Studies-subsectorize_primary_zone_timestamp_1_to_35.png "Zone tab – The main interface where primary zones are managed.")

2.  Select your **primary zone** from the list.

![Frame at 1:42](../images/Case-Studies-subsectorize_primary_zone_timestamp_1_to_42.png "Primary zone selection – Selecting the specific geographic area to be split.")

### Feature Overview

*   **Actions menu**: Provides access to the sub-sectorization tool for the selected zone.

![Frame at 1:43](../images/Case-Studies-subsectorize_primary_zone_timestamp_1_to_43.png "Actions menu – The dropdown menu containing the subsectorize option.")

*   **Sectorization parameters pop-up**: Allows you to filter which missions the system uses for balancing.

![Frame at 1:49](../images/Case-Studies-subsectorize_primary_zone_timestamp_1_to_49.png "Sectorization parameters – The configuration window for mission data filters.")

*   **Naming pattern toggle**: Automatically names new sub-zones based on the primary zone's name to maintain consistency.

![Frame at 2:38](../images/Case-Studies-subsectorize_primary_zone_timestamp_2_to_38.png "Naming pattern toggle – The switch used to enable automatic territory naming.")

*   **Assign territories button**: Launches the territory manager module with your filtered mission data.

![Frame at 3:16](../images/Case-Studies-subsectorize_primary_zone_timestamp_3_to_16.png "Assign territories button – The action that triggers the territory manager module.")

*   **Automation button**: Opens the territory assignment wizard to start the automated balancing process.

![Frame at 3:52](../images/Case-Studies-subsectorize_primary_zone_timestamp_3_to_52.png "Automation button – The tool used to access balancing methods.")

*   **Balance points**: A balancing method that distributes missions evenly based on the number of delivery points.

![Frame at 4:03](../images/Case-Studies-subsectorize_primary_zone_timestamp_4_to_03.png "Balance points selection – Choosing the point-based distribution method.")

*   **Validate territory management button**: Finalizes the automated split and moves you to the assignment stage.

![Frame at 5:52](../images/Case-Studies-subsectorize_primary_zone_timestamp_5_to_52.png "Validate button – The confirmation step to save the generated sub-zones.")

### How To: Create Balanced Sub-zones

1.  Open the **Actions menu** and select **subsectorize**.

![Flow 1:43 to 1:48](../images/Case-Studies-subsectorize_primary_zone_timestamp_1_to_43_to_1_to_48.gif "Subsectorize action – Clicking the subsectorize option in the menu.")

2.  Use the filters to narrow mission data by **agency**, **subcontractor**, **period**, or **day of the week**.

![Frame at 2:07](../images/Case-Studies-subsectorize_primary_zone_timestamp_2_to_07.png "Data filters – Narrowing down missions for more accurate balancing.")

3.  Toggle on the **naming pattern** to automate sub-zone naming.

![Frame at 2:41](../images/Case-Studies-subsectorize_primary_zone_timestamp_2_to_41.png "Enable naming pattern – Activating the automatic naming feature.")

4.  Click **assign territories** to load the filtered missions onto the map.

![Frame at 3:16](../images/Case-Studies-subsectorize_primary_zone_timestamp_3_to_16.png "Assign territories – Loading mission points into the territory manager.")

5.  Select the **automation button** located at the top left of the map.

![Frame at 3:52](../images/Case-Studies-subsectorize_primary_zone_timestamp_3_to_52.png "Automation trigger – Opening the territory assignment wizard.")

6.  Select **balance points** as the balancing method and click **start**.

![Frame at 4:03](../images/Case-Studies-subsectorize_primary_zone_timestamp_4_to_03.png "Select method – Choosing balance points and proceeding.")

7.  Navigate to the **number of territories tab** and enter your target count (e.g., 3).

![Frame at 4:23](../images/Case-Studies-subsectorize_primary_zone_timestamp_4_to_23.png "Set territory count – Defining how many sub-zones to create.")

8.  Move to the **balance the territories on tab** and select your indicator, such as **number of points**.

![Frame at 4:32](../images/Case-Studies-subsectorize_primary_zone_timestamp_4_to_32.png "Select indicator – Setting the metric used to balance the zones.")

9.  Click **let's go** to start the automated balancing.

![Flow 5:00 to 5:12](../images/Case-Studies-subsectorize_primary_zone_timestamp_5_to_00_to_5_to_12.gif "Processing – The system automatically calculating and rendering the new sub-zones.")

10. Review the map split and click **validate territory management**.

![Frame at 5:52](../images/Case-Studies-subsectorize_primary_zone_timestamp_5_to_52.png "Validate split – Confirming the visual territory distribution.")

11. Link each sub-zone to an **agency** or **subagency** using the drop-down menu.

![Frame at 6:10](../images/Case-Studies-subsectorize_primary_zone_timestamp_6_to_10.png "Agency assignment – Mapping sub-zones to specific teams.")

12. Click **save and assign** to go live immediately, or click **save** to finalize later.

![Frame at 6:39](../images/Case-Studies-subsectorize_primary_zone_timestamp_6_to_39.png "Final save – Storing the completed sub-zones in the system.")

### Productivity Tips

- 💡 **Intelligent Balancing**: Use historical mission data like stop counts and coordinates to ensure your zones are split accurately based on real-world activity.
- 💡 **Flexible Indicators**: You can balance territories using any numerical data, such as delivery duration or service time, to match your specific operational needs.
- 💡 **Visual Verification**: Use the distinct colors on the map to immediately identify and verify the geographic logic of your new sub-zones.
- ⚠️ **Missing Data Warning**: You cannot perform sub-sectorization if missions are not loaded, as the system will have no data to balance against.

