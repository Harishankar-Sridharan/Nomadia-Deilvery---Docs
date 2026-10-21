# Subcontractor Swap to Primary Zone

Reversing a subcontractor swap allows you to quickly restore missions to their original primary zone configuration. This process is essential if a swap was made in error or if a delayed subcontractor finally arrives at the depot. You will achieve a full restoration of sectors, subcontractors, and drivers across all missions in a single action.

## Before you begin

* Access to the **Mission** tab.
* Missions must be currently assigned to a secondary (backup) zone.

1. Navigate to the **Mission** tab.

![](../.gitbook/assets/Case-Studies-Subcontractor_Swap_to_Primary_Zone_timestamp_0_to_44.png)

## Feature overview

* **Filter Panel**: Use this panel to isolate missions assigned to specific sectors or subcontractors.

![](../.gitbook/assets/Case-Studies-Subcontractor_Swap_to_Primary_Zone_timestamp_0_to_54.png)

* **Actions Menu**: Open this menu to access bulk operations for selected missions.

![](../.gitbook/assets/Case-Studies-Subcontractor_Swap_to_Primary_Zone_timestamp_1_to_21.png)

* **Assign to Subcontractor Pop-up**: Use this window to change zone assignments and select subcontractors.

![](../.gitbook/assets/Case-Studies-Subcontractor_Swap_to_Primary_Zone_timestamp_1_to_29.png)

* **Primary Zone Toggle**: Activate this switch to restore missions to their original primary configuration.

![](../.gitbook/assets/Case-Studies-Subcontractor_Swap_to_Primary_Zone_timestamp_1_to_34.png)

## Restore missions to the primary zone

1. Navigate to the **Filter Panel**.

![](../.gitbook/assets/Case-Studies-Subcontractor_Swap_to_Primary_Zone_timestamp_0_to_54_to_1_to_01.gif)

2. Filter by the **Sector** column using the **Among** operator.

![](../.gitbook/assets/Case-Studies-Subcontractor_Swap_to_Primary_Zone_timestamp_1_to_01_to_1_to_11.gif)

3. Select all missions currently assigned to the backup zone.

![](../.gitbook/assets/Case-Studies-Subcontractor_Swap_to_Primary_Zone_timestamp_1_to_21.png)

4. Click the **Actions Menu** and select **Assign to Subcontractor**.

![](../.gitbook/assets/Case-Studies-Subcontractor_Swap_to_Primary_Zone_timestamp_1_to_21_to_1_to_29.gif)

5. Activate the **Primary Zone** toggle in the pop-up.

![](../.gitbook/assets/Case-Studies-Subcontractor_Swap_to_Primary_Zone_timestamp_1_to_34.png)

6. Select the original subcontractor showing 100% coverage.

![](../.gitbook/assets/Case-Studies-Subcontractor_Swap_to_Primary_Zone_timestamp_1_to_51.png)

7. Click **Apply** to complete the restoration.

![](../.gitbook/assets/Case-Studies-Subcontractor_Swap_to_Primary_Zone_timestamp_2_to_02_to_2_to_09.gif)

## Verify the restoration

1. Clear the backup zone filter from the mission table.

![](../.gitbook/assets/Case-Studies-Subcontractor_Swap_to_Primary_Zone_timestamp_2_to_33.png)

2. Apply a new filter using the **Sector** field to select the primary subzone.

![](../.gitbook/assets/Case-Studies-Subcontractor_Swap_to_Primary_Zone_timestamp_2_to_33_to_2_to_40.gif)

3. Confirm that **Sector**, **Subcontractor**, and **Scheduled Deliverer** have been restored.

![](../.gitbook/assets/Case-Studies-Subcontractor_Swap_to_Primary_Zone_timestamp_2_to_54.png)

## Tips

{% hint style="info" %}
**One-Toggle Restoration**: Reverting a swap is exactly as fast as making one by switching a single toggle.
{% endhint %}

{% hint style="info" %}
**Automatic Driver Relinking**: The original driver is automatically relinked to the missions when you restore the primary zone.
{% endhint %}

{% hint style="info" %}
**Bulk Efficiency**: Undo hundreds of mission assignments in seconds without manual editing or data re-importing.
{% endhint %}

{% hint style="warning" %}
**Verification via Empty Table**: If the mission table appears empty after clicking apply, it confirms the backup filter no longer applies to those missions.
{% endhint %}

## Related topics

* [Case Studies](README.md)
* [Subcontractor Swap to Backup Zone](subcontractor-swap-to-backup-zone.md)
* [Creating Backup Zone](creating-backup-zone.md)
