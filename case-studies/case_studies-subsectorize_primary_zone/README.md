# Sub sectorize primary zone

This feature allows you to split a primary zone into smaller, balanced territories automatically using the territory management module. Dispatchers need this to create fair and logical areas for specific delivery agents or teams. By following this guide, you will achieve three geographically split sub-zones ready for immediate assignment.

#### Getting Started

Before you begin sub-sectoring, ensure your system meets these requirements:

* A primary zone must be built with mapped postal codes and defined geography.
* Historical mission data, including delivery points and coordinates, must be loaded into the mission page.

Follow these initial steps:

1. Open your **study** and navigate to the **zone tab**.

![](../../.gitbook/assets/Case-Studies-subsectorize_primary_zone_timestamp_1_to_35.png)

2. Select your **primary zone** from the list.

![](../../.gitbook/assets/Case-Studies-subsectorize_primary_zone_timestamp_1_to_42.png)

#### Feature Overview

* **Actions menu**: Provides access to the sub-sectorization tool for the selected zone.

<figure><img src="../../.gitbook/assets/ApplicationFrameHost_fZka2nACfC.png" alt=""><figcaption></figcaption></figure>

* **Sectorization parameters pop-up**: Allows you to filter which missions the system uses for balancing.

![](../../.gitbook/assets/Case-Studies-subsectorize_primary_zone_timestamp_1_to_49.png)

* **Naming pattern toggle**: Automatically names new sub-zones based on the primary zone's name to maintain consistency.

![](../../.gitbook/assets/Case-Studies-subsectorize_primary_zone_timestamp_2_to_38.png)

* **Assign territories button**: Launches the territory manager module with your filtered mission data.

![](../../.gitbook/assets/Case-Studies-subsectorize_primary_zone_timestamp_3_to_16.png)

* **Automation button**: Opens the territory assignment wizard to start the automated balancing process.

![](../../.gitbook/assets/Case-Studies-subsectorize_primary_zone_timestamp_3_to_52.png)

* **Balance points**: A balancing method that distributes missions evenly based on the number of delivery points.

![](../../.gitbook/assets/Case-Studies-subsectorize_primary_zone_timestamp_4_to_03.png)

* **Validate territory management button**: Finalizes the automated split and moves you to the assignment stage.

![](../../.gitbook/assets/Case-Studies-subsectorize_primary_zone_timestamp_5_to_52.png)

#### How To: Create Balanced Sub-zones

1. Open the **Actions menu** and select **subsectorize**.

![](../../.gitbook/assets/Case-Studies-subsectorize_primary_zone_timestamp_1_to_43_to_1_to_48.gif)

2. Use the filters to narrow mission data by **agency**, **subcontractor**, **period**, or **day of the week**.

![](../../.gitbook/assets/Case-Studies-subsectorize_primary_zone_timestamp_2_to_07.png)

3. Toggle on the **naming pattern** to automate sub-zone naming.

![](../../.gitbook/assets/Case-Studies-subsectorize_primary_zone_timestamp_2_to_41.png)

4. Click **assign territories** to load the filtered missions onto the map.

![](../../.gitbook/assets/Case-Studies-subsectorize_primary_zone_timestamp_3_to_16.png)

5. Select the **automation button** located at the top left of the map.

![](../../.gitbook/assets/Case-Studies-subsectorize_primary_zone_timestamp_3_to_52.png)

6. Select **balance points** as the balancing method and click **start**.

![](../../.gitbook/assets/Case-Studies-subsectorize_primary_zone_timestamp_4_to_03.png)

7. Navigate to the **number of territories tab** and enter your target count (e.g., 3).

![](../../.gitbook/assets/Case-Studies-subsectorize_primary_zone_timestamp_4_to_23.png)

8. Move to the **balance the territories on tab** and select your indicator, such as **number of points**.

![](../../.gitbook/assets/Case-Studies-subsectorize_primary_zone_timestamp_4_to_32.png)

9. Click **let's go** to start the automated balancing.

![](../../.gitbook/assets/Case-Studies-subsectorize_primary_zone_timestamp_5_to_00_to_5_to_12.gif)

10. Review the map split and click **validate territory management**.

![](../../.gitbook/assets/Case-Studies-subsectorize_primary_zone_timestamp_5_to_52.png)

11. Link each sub-zone to an **agency** or **subagency** using the drop-down menu.

![](../../.gitbook/assets/Case-Studies-subsectorize_primary_zone_timestamp_6_to_10.png)

12. Click **save and assign** to go live immediately, or click **save** to finalize later.

![](../../.gitbook/assets/Case-Studies-subsectorize_primary_zone_timestamp_6_to_39.png)

#### Productivity Tips

* 💡 **Intelligent Balancing**: Use historical mission data like stop counts and coordinates to ensure your zones are split accurately based on real-world activity.
* 💡 **Flexible Indicators**: You can balance territories using any numerical data, such as delivery duration or service time, to match your specific operational needs.
* 💡 **Visual Verification**: Use the distinct colors on the map to immediately identify and verify the geographic logic of your new sub-zones.
* ⚠️ **Missing Data Warning**: You cannot perform sub-sectorization if missions are not loaded, as the system will have no data to balance against.
