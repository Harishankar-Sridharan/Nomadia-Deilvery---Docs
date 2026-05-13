# Dividing Sub Zones

Subzone division allows you to split an overloaded territory into two balanced zones instantly. Use this feature to handle demand surges, bulk orders, or seasonal spikes without overloading drivers. You will achieve balanced mission counts and automated driver reassignments to maintain your service levels.

#### Getting Started

Before dividing a territory, ensure your setup meets these requirements:

* A primary zone must already be sub sectorized through the territory manager.
* Target subzones must have an established link to a primary zone.

1. Open the **Configuration module**.

![](../.gitbook/assets/Case-Studies-Dividing_Sub_Zones_timestamp_2_to_32.png)

2. Click on **Manage studies and zones**.

![](../.gitbook/assets/Case-Studies-Dividing_Sub_Zones_timestamp_2_to_36.png)

3. Select the **Edit** icon for the study containing the overloaded zone.

#### Feature Overview

* **Assignment Mode**: This field displays "primary subzone" to confirm the territory is part of a larger hierarchy.

![](../.gitbook/assets/Case-Studies-Dividing_Sub_Zones_timestamp_1_to_38.png)

* **Main Zone Field**: This stores the unique identifier of the parent primary zone to keep the structure intact.

![](../.gitbook/assets/Case-Studies-Dividing_Sub_Zones_timestamp_1_to_49.png)

* **Actions Menu**: This provides the **Subsectorize** command to begin the division process.
* **Sectorization Parameters**: This pop-up allows you to filter missions by agency, period, or specific days.

![](../.gitbook/assets/Case-Studies-Dividing_Sub_Zones_timestamp_3_to_08.png)

* **Automation Button**: This launches the territory wizard to calculate new boundaries automatically.

![](../.gitbook/assets/Case-Studies-Dividing_Sub_Zones_timestamp_3_to_33.png)

#### How To: Divide an Overloaded Subzone

1. Identify the overloaded subzone in the **Zone tab**.
2. Open the **Actions menu** and click **Sub sectorize**.

![](../.gitbook/assets/Case-Studies-Dividing_Sub_Zones_timestamp_3_to_01.png)

3. Set your filters in **Sectorization parameters** and click **Assign territories**.
4. Click the **Automation button** located above the map in **Territory Manager**.

![](../.gitbook/assets/Case-Studies-Dividing_Sub_Zones_timestamp_3_to_33.png)

5. Select **Balance point** as the methodology in the **Territory assignment wizard**.
6. Click **Start**.
7. Enter the number "2" in the **Number of territories** section.
8. Click **Let's go** to trigger the calculation.

![](../.gitbook/assets/Case-Studies-Dividing_Sub_Zones_timestamp_4_to_00_to_4_to_19.gif)

9. Review the split on the map and click **Validate territory assignment**.
10. Click **Save** on the **Modify territory assignment** page.

#### How To: Verify Automated Mission Reassignment

1. Navigate to the **Mission tab**.
2. Click the **Sector** field to view mission assignments.
3. Confirm missions show the names of the new subzones.

![](../.gitbook/assets/Case-Studies-Dividing_Sub_Zones_timestamp_5_to_28.png)

#### Productivity Tips

* 💡 **Hierarchy Preservation**: The system uses the **Main zone field** to ensure your zone hierarchy remains consistent during edits.
* 💡 **Automated Updates**: Missions reassign themselves based on geographical delivery addresses, removing the need for manual data entry.
* 💡 **Immediate Optimization**: Planners can move directly to route optimization since the system handles all retagging automatically.
* ⚠️ **Static Bottlenecks**: Avoid manual reassignments during surges to prevent data bottlenecks and undelivered missions.
