# Assigning zones to missions

This feature automatically associates new missions with predefined delivery sectors the moment they enter the system. It eliminates the need for manual postal code lookups or dispatcher intervention. You will achieve an efficient, fully automated workflow from mission creation to sector assignment in seconds.

#### Getting Started

Before using automatic sector assignment, ensure your operational infrastructure is configured:

* Create your studies.
* Map primary zones.
* Build and balance subzones.
* Assign deliverers to their specific territories.

To begin the setup:

1. Navigate to the **Mission tab**.
2. Click the **Actions menu**.

#### Feature Overview

* **Geocoding**: This process converts address data into latitude and longitude coordinates for geographical map display.
* **Sector Field**: This column displays mission assignments using the format "Study Name | Subzone Name".
* **Zone icon**: Use this map control to toggle the visibility of subzone boundaries.

#### How To: Import Missions and Assign Sectors

Follow these steps to import missions via Excel and trigger automatic assignment.

1. Click the **Import button** in the **Actions menu**.

![](../.gitbook/assets/Case-Studies-assigning_zones_to_missions_timestamp_1_to_40_to_1_to_50.gif)

2. Select the mission file from your computer and click **Open**.
3. Select the desired tab and click the **Validate button**.
4. Review the geocoded mission locations on the map.
5. Click the **Import button** to push the data into **Nomadia Delivery**.

![](../.gitbook/assets/Case-Studies-assigning_zones_to_missions_timestamp_2_to_41_to_2_to_50.gif)

6. The **Sector** and **Scheduled Deliverer** fields are automatically populated based on the configured zone settings.

<figure><img src="../.gitbook/assets/ApplicationFrameHost_4CNHYZNXlj.png" alt=""><figcaption></figcaption></figure>

#### How To: Surface the Sector Column

If the sector information is hidden, follow these steps to display it in your table.

1. Click the **Actions menu**.
2. Select **Customize the list item**.

![](../.gitbook/assets/Case-Studies-assigning_zones_to_missions_timestamp_4_to_41_to_4_to_47.gif)

3. Locate the **Sector** field within the **Available fields** column.
4. Click the **Arrow button** to move it to the **Displayed fields** column.

![](../.gitbook/assets/Case-Studies-assigning_zones_to_missions_timestamp_5_to_01_to_5_to_04.gif)

5. Click **Save** to update the mission table.

#### Productivity Tips

* 💡 **Operational Reviews**: Activate zone boundaries on the map to spot overloaded territories or uneven mission distributions.
* ⚠️ **Static Boundaries**: Avoid using outdated boundaries when demand changes; update your configuration to keep operations dynamic.
