# Case_studies-Dividing_Sub_Zones
# Case-Studies

Subzone division allows you to split an overloaded territory into two balanced zones instantly. Use this feature to handle demand surges, bulk orders, or seasonal spikes without overloading drivers. You will achieve balanced mission counts and automated driver reassignments to maintain your service levels.

### Getting Started

Before dividing a territory, ensure your setup meets these requirements:
*   A primary zone must already be subsectorized through the territory manager.
*   Target subzones must have an established link to a primary zone.

1.  Open the **Configuration module**.

![Frame at 2:32](../images/Case-Studies-Dividing_Sub_Zones_timestamp_2_to_32.png "Configuration module – The main settings area for managing logistics structures.")

2.  Click on **Manage studies and zones**.

![Frame at 2:36](../images/Case-Studies-Dividing_Sub_Zones_timestamp_2_to_36.png "Manage studies and zones – The interface for editing territory studies.")

3.  Select the **Edit** icon for the study containing the overloaded zone.

### Feature Overview

*   **Assignment Mode**: This field displays "primary subzone" to confirm the territory is part of a larger hierarchy.
![Frame at 1:38](../images/Case-Studies-Dividing_Sub_Zones_timestamp_1_to_38.png "Assignment Mode – UI indicator showing the territory is a sub-unit.")

*   **Main Zone Field**: This stores the unique identifier of the parent primary zone to keep the structure intact.
![Frame at 1:49](../images/Case-Studies-Dividing_Sub_Zones_timestamp_1_to_49.png "Main Zone Field – Data field linking the subzone to its parent territory.")

*   **Actions Menu**: This provides the **Subsectorize** command to begin the division process.

*   **Sectorization Parameters**: This pop-up allows you to filter missions by agency, period, or specific days.
![Frame at 3:08](../images/Case-Studies-Dividing_Sub_Zones_timestamp_3_to_08.png "Sectorization Parameters – Filter window to define which missions to split.")

*   **Automation Button**: This launches the territory wizard to calculate new boundaries automatically.
![Frame at 3:33](../images/Case-Studies-Dividing_Sub_Zones_timestamp_3_to_33.png "Automation Button – Entry point for the automated assignment tools.")

### How To: Divide an Overloaded Subzone

1.  Identify the overloaded subzone in the **Zone tab**.

2.  Open the **Actions menu** and click **Subsectorize**.
![Frame at 3:01](../images/Case-Studies-Dividing_Sub_Zones_timestamp_3_to_01.png "Actions menu – Selecting the subsectorize option for the chosen zone.")

3.  Set your filters in **Sectorization parameters** and click **Assign territories**.

4.  Click the **Automation button** located above the map in **Territory Manager**.
![Frame at 3:33](../images/Case-Studies-Dividing_Sub_Zones_timestamp_3_to_33.png "Territory Manager – Accessing automation tools from the map view.")

5.  Select **Balance point** as the methodology in the **Territory assignment wizard**.

6.  Click **Start**.

7.  Enter the number "2" in the **Number of territories** section.

8.  Click **Let's go** to trigger the calculation.
![Flow 4:00 to 4:19](../images/Case-Studies-Dividing_Sub_Zones_timestamp_4_to_00_to_4_to_19.gif "Territory Assignment Wizard – The system calculating and rendering two new balanced territories on the map.")

9.  Review the split on the map and click **Validate territory assignment**.

10. Click **Save** on the **Modify territory assignment** page.

### How To: Verify Automated Mission Reassignment

1.  Navigate to the **Mission tab**.

2.  Click the **Sector** field to view mission assignments.

3.  Confirm missions show the names of the new subzones.
![Frame at 5:28](../images/Case-Studies-Dividing_Sub_Zones_timestamp_5_to_28.png "Mission tab – Table showing missions automatically reassigned to the new zones.")

### Productivity Tips

*   💡 **Hierarchy Preservation**: The system uses the **Main zone field** to ensure your zone hierarchy remains consistent during edits.
*   💡 **Automated Updates**: Missions reassign themselves based on geographical delivery addresses, removing the need for manual data entry.
*   💡 **Immediate Optimization**: Planners can move directly to route optimization since the system handles all retagging automatically.
*   ⚠️ **Static Bottlenecks**: Avoid manual reassignments during surges to prevent data bottlenecks and undelivered missions.

