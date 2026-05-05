# Case_studies-assigning_zones_to_missions
# Case-Studies

This feature automatically associates new missions with predefined delivery sectors the moment they enter the system. It eliminates the need for manual postal code lookups or dispatcher intervention. You will achieve an efficient, fully automated workflow from mission creation to sector assignment in seconds.

### Getting Started

Before using automatic sector assignment, ensure your operational infrastructure is configured:

*   Create your studies.
*   Map primary zones.
*   Build and balance subzones.
*   Assign deliverers to their specific territories.

To begin the setup:

1. Navigate to the **Mission tab**.

![Mission Screen – Accessing the mission management area.](../images/Case-Studies-assigning_zones_to_missions_timestamp_1_to_40.png "Mission Screen – Accessing the mission management area.")

2. Click the **Actions menu**.

![Action Menu – Opening the available actions for missions.](../images/Case-Studies-assigning_zones_to_missions_timestamp_1_to_44.png "Action Menu – Opening the available actions for missions.")

### Feature Overview

*   **Geocoding**: This process converts address data into latitude and longitude coordinates for geographical map display.

![Geocoding Map – Address information converted into map coordinates.]({IMAGE_BASE_PATH}Case-Studies-assigning_zones_to_missions_timestamp_2_to_34.png "Geocoding Map – Address information converted into map coordinates.")

*   **Sector Field**: This column displays mission assignments using the format "Study Name | Subzone Name".

![Sector Field – Clean display of automated mission-to-sector assignments.]({IMAGE_BASE_PATH}Case-Studies-assigning_zones_to_missions_timestamp_4_to_03.png "Sector Field – Clean display of automated mission-to-sector assignments.")

*   **Zone icon**: Use this map control to toggle the visibility of subzone boundaries.

![Zone Toggle – Activating subzone boundary lines on the mission map.]({IMAGE_BASE_PATH}Case-Studies-assigning_zones_to_missions_timestamp_5_to_24.png "Zone Toggle – Activating subzone boundary lines on the mission map.")

### How To: Import Missions and Assign Sectors

Follow these steps to import missions via Excel and trigger automatic assignment.

1. Click the **Import button** in the **Actions menu**.

![Flow 1:40 to 1:50](../images/Case-Studies-assigning_zones_to_missions_timestamp_1_to_40_to_1_to_50.gif "Import Button – Initiating the file import process.")

2. Select the mission file from your computer and click **Open**.

![File Browser – Choosing the Excel mission data file for import.](../images/Case-Studies-assigning_zones_to_missions_timestamp_1_to_58.png "File Browser – Choosing the Excel mission data file for import.")

3. Select the desired tab and click the **Validate button**.

![Validation Step – Confirming the data structure before processing.](../images/Case-Studies-assigning_zones_to_missions_timestamp_2_to_02.png "Validation Step – Confirming the data structure before processing.")

4. Review the geocoded mission locations on the map.

![Geocoding Review – Visualizing mission points on the map geographically.](../images/Case-Studies-assigning_zones_to_missions_timestamp_2_to_37.png "Geocoding Review – Visualizing mission points on the map geographically.")

5. Click the **Import button** to push the data into **Nomadia Delivery**.

![Flow 2:41 to 2:50](../images/Case-Studies-assigning_zones_to_missions_timestamp_2_to_41_to_2_to_50.gif "Data Push – Finalizing mission creation and triggering automatic sector links.")

### How To: Surface the Sector Column

If the sector information is hidden, follow these steps to display it in your table.

1. Click the **Actions menu**.

![Action Menu – Accessing list configuration settings.](../images/Case-Studies-assigning_zones_to_missions_timestamp_4_to_41.png "Action Menu – Accessing list configuration settings.")

2. Select **Customize the list item**.

![Flow 4:41 to 4:47](../images/Case-Studies-assigning_zones_to_missions_timestamp_4_to_41_to_4_to_47.gif "Customize List – Opening the panel to manage table columns.")

3. Locate the **Sector** field within the **Available fields** column.

![Field Selection – Finding the sector column to add to the view.](../images/Case-Studies-assigning_zones_to_missions_timestamp_4_to_57.png "Field Selection – Finding the sector column to add to the view.")

4. Click the **Arrow button** to move it to the **Displayed fields** column.

![Flow 5:01 to 5:04](../images/Case-Studies-assigning_zones_to_missions_timestamp_5_to_01_to_5_to_04.gif "Move Column – Shifting the sector field into the active display list.")

5. Click **Save** to update the mission table.

![Save Button – Applying changes to see sector data in the table.](../images/Case-Studies-assigning_zones_to_missions_timestamp_5_to_11.png "Save Button – Applying changes to see sector data in the table.")

### Productivity Tips

- 💡 **Operational Reviews**: Activate zone boundaries on the map to spot overloaded territories or uneven mission distributions.
- ⚠️ **Static Boundaries**: Avoid using outdated boundaries when demand changes; update your configuration to keep operations dynamic.

