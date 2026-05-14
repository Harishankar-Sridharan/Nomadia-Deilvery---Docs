# Case_studies-Subcontractor_Swap_to_Primary_Zone
# Case-Studies

Reversing a subcontractor swap allows you to quickly restore missions to their original primary zone configuration. This process is essential if a swap was made in error or if a delayed subcontractor finally arrives at the depot. You will achieve a full restoration of sectors, subcontractors, and drivers across all missions in a single action.

### Getting Started

*   Access to the **Mission** tab.
*   Missions must be currently assigned to a secondary (backup) zone.

1. Navigate to the **Mission** tab.

![Frame at 0:44](../images/Case-Studies-Subcontractor_Swap_to_Primary_Zone_timestamp_0_to_44.png "Mission Tab – The user is viewing the list of missions currently assigned to the backup zone.")

### Feature Overview

*   **Filter Panel**: Use this panel to isolate missions assigned to specific sectors or subcontractors.

![Frame at 0:54](../images/Case-Studies-Subcontractor_Swap_to_Primary_Zone_timestamp_0_to_54.png "Filter Panel – Side panel used to refine mission selection using the sector column.")

*   **Actions Menu**: Open this menu to access bulk operations for selected missions.

![Frame at 1:21](../images/Case-Studies-Subcontractor_Swap_to_Primary_Zone_timestamp_1_to_21.png "Actions Menu – Dropdown menu containing the assign to subcontractor option.")

*   **Assign to Subcontractor Pop-up**: Use this window to change zone assignments and select subcontractors.

![Frame at 1:29](../images/Case-Studies-Subcontractor_Swap_to_Primary_Zone_timestamp_1_to_29.png "Assign to Subcontractor Pop-up – Modal window for choosing zone assignment and subcontractors.")

*   **Primary Zone Toggle**: Activate this switch to restore missions to their original primary configuration.

![Frame at 1:34](../images/Case-Studies-Subcontractor_Swap_to_Primary_Zone_timestamp_1_to_34.png "Primary Zone Toggle – Switch used to reactivate the original zone settings.")

### How To: Restore Missions to the Primary Zone

1. Open the **Filter Panel**.

![Flow 0:54 to 1:01](../images/Case-Studies-Subcontractor_Swap_to_Primary_Zone_timestamp_0_to_54_to_1_to_01.gif "Filter Panel – Accessing the filter panel to refine the mission list.")

2. Filter by the **Sector** column using the **Among** operator.

![Flow 1:01 to 1:11](../images/Case-Studies-Subcontractor_Swap_to_Primary_Zone_timestamp_1_to_01_to_1_to_11.gif "Sector Filter – Selecting the backup zone to display missions needing reversal.")

3. Select all missions currently assigned to the backup zone.

![Frame at 1:21](../images/Case-Studies-Subcontractor_Swap_to_Primary_Zone_timestamp_1_to_21.png "Mission Selection – All missions currently assigned to the replacement subcontractor are highlighted.")

4. Click the **Actions Menu** and select **Assign to Subcontractor**.

![Flow 1:21 to 1:29](../images/Case-Studies-Subcontractor_Swap_to_Primary_Zone_timestamp_1_to_21_to_1_to_29.gif "Assign to Subcontractor – Opening the assignment tool for the selected missions.")

5. Activate the **Primary Zone** toggle in the pop-up.

![Frame at 1:34](../images/Case-Studies-Subcontractor_Swap_to_Primary_Zone_timestamp_1_to_34.png "Primary Zone Activation – Toggling the switch to restore primary configurations.")

6. Select the original subcontractor showing 100% coverage.

![Frame at 1:51](../images/Case-Studies-Subcontractor_Swap_to_Primary_Zone_timestamp_1_to_51.png "Subcontractor Table – The original partner is identified as the correct match.")

7. Click **Apply** to complete the restoration.

![Flow 2:02 to 2:09](../images/Case-Studies-Subcontractor_Swap_to_Primary_Zone_timestamp_2_to_02_to_2_to_09.gif "Apply Action – Finalizing the swap to move missions back to the primary zone.")

### How To: Verify the Restoration

1. Clear the backup zone filter from the mission table.

![Frame at 2:33](../images/Case-Studies-Subcontractor_Swap_to_Primary_Zone_timestamp_2_to_33.png "Clear Filter – Removing the previous filter to refresh the mission table.")

2. Apply a new filter using the **Sector** field to select the primary subzone.

![Flow 2:33 to 2:40](../images/Case-Studies-Subcontractor_Swap_to_Primary_Zone_timestamp_2_to_33_to_2_to_40.gif "Primary Filter – Filtering missions to confirm they returned to the original sector.")

3. Confirm that **Sector**, **Subcontractor**, and **Scheduled Deliverer** have been restored.

![Frame at 2:54](../images/Case-Studies-Subcontractor_Swap_to_Primary_Zone_timestamp_2_to_54.png "Verification – Confirming all three key fields match their original pre-swap states.")

### Productivity Tips

- 💡 **One-Toggle Restoration**: Reverting a swap is exactly as fast as making one by switching a single toggle.
- 💡 **Automatic Driver Relinking**: The original driver is automatically relinked to the missions when you restore the primary zone.
- 💡 **Bulk Efficiency**: Undo hundreds of mission assignments in seconds without manual editing or data re-importing.
- ⚠️ **Verification via Empty Table**: If the mission table appears empty after clicking apply, it confirms the backup filter no longer applies to those missions.

