# Study Creation with Primary Zone - Duplicate

Studies are structured objects that define the organization of your delivery territories. They allow you to create geographical zones tied to postal codes that reflect real-world logistics needs. By using multiple studies, you can activate specific coverage plans based on seasonality or holiday campaigns.

### Getting Started

To begin creating studies, ensure you have the appropriate administrative permissions.

**Prerequisites:**

* Access to the **Configuration module** in the **Nomadia Delivery** application banner.
* The following rights assigned in the **Roles and rights** tab: **List of zones**, **Assign zones**, **Create and update zones**, **Access to the sectorization tool**, and **Delete zones and delete studies**.

**Initial Setup Steps:**

1. Click the **Configuration module** in the application banner.

![Frame at 1:51](../.gitbook/assets/01_StudyCreationWithPrimaryZone_timestamp_1_to_51.png)

2. Select the **Manage users** page.

![Frame at 1:59](../.gitbook/assets/01_StudyCreationWithPrimaryZone_timestamp_1_to_59.png)

3. Edit the specific user and navigate to the **Roles and rights** tab.

![Frame at 2:16](../.gitbook/assets/01_StudyCreationWithPrimaryZone_timestamp_2_to_16.png)

4. Assign the necessary rights related to the zone module and click **Save**.

![GIF 3:00 to 3:08](../.gitbook/assets/01_StudyCreationWithPrimaryZone_timestamp_3_to_00-3_to_08.gif)

### Feature Overview

* **Study Management Page**: Your central hub for creating and editing all studies and zones.

![Frame at 3:21](../.gitbook/assets/01_StudyCreationWithPrimaryZone_timestamp_3_to_21.png)

* **Actions Menu**: A dropdown in the top right used to trigger creation and import tasks.

![Frame at 3:29](<../.gitbook/assets/01_StudyCreationWithPrimaryZone_timestamp_3_to_29 (1).png>)

* **Validity Start/End Date**: Fields defining the total lifespan of a study.

![Frame at 4:01](../.gitbook/assets/01_StudyCreationWithPrimaryZone_timestamp_4_to_01.png)

* **Zone Tab**: A sub-section within a study used to manage specific geographic areas.

![Frame at 5:38](../.gitbook/assets/01_StudyCreationWithPrimaryZone_timestamp_5_to_38.png)

* **Assignment Mode**: A critical setting to designate a zone as a **Primary Zone** (top level).

![Frame at 6:26](../.gitbook/assets/01_StudyCreationWithPrimaryZone_timestamp_6_to_26.png)

* **Map View**: A visual pane that automatically renders polygons for entered postal codes.

![Frame at 7:24](../.gitbook/assets/01_StudyCreationWithPrimaryZone_timestamp_7_to_24.png)

### How To: Create an Empty Study

1. Open the **Configuration module** and select **Studies and Zones** under the **Delivery** section.

![Frame at 3:15](../.gitbook/assets/01_StudyCreationWithPrimaryZone_timestamp_3_to_15.png)

2. Click the **Actions Menu** and select **Create empty study**.

![GIF 3:29 to 3:37](../.gitbook/assets/01_StudyCreationWithPrimaryZone_timestamp_3_to_29-3_to_37.gif)

3. Enter the **Identifier**, **Name**, and select the **Agency**.

![Frame at 3:44](../.gitbook/assets/01_StudyCreationWithPrimaryZone_timestamp_3_to_44.png)

4. Set the **Validity start date** and **Validity end date**.

![Frame at 4:09](../.gitbook/assets/01_StudyCreationWithPrimaryZone_timestamp_4_to_09.png)

5. Toggle the switch to **Enable** the study.

![Frame at 4:15](../.gitbook/assets/01_StudyCreationWithPrimaryZone_timestamp_4_to_15.png)

6. Select specific active days (e.g., Monday to Friday).

![Frame at 4:22](../.gitbook/assets/01_StudyCreationWithPrimaryZone_timestamp_4_to_22.png)

7. Configure the seasonal activation period within the year.

![Frame at 4:36](../.gitbook/assets/01_StudyCreationWithPrimaryZone_timestamp_4_to_36.png)

8. Click the **Save** button.

![Frame at 5:00](../.gitbook/assets/01_StudyCreationWithPrimaryZone_timestamp_5_to_00.png)

### How To: Add a Primary Zone

1. Navigate to the **Zone Tab** within your created study.

![Frame at 5:31](../.gitbook/assets/01_StudyCreationWithPrimaryZone_timestamp_5_to_31.png)

2. Open the **Actions Menu** and select **Add a postal code zone**.

![GIF 5:38 to 5:47](../.gitbook/assets/01_StudyCreationWithPrimaryZone_timestamp_5_to_38-5_to_47.gif)

3. Enter the **Identifier**, **Name**, and **Agency**.

![Frame at 5:53](../.gitbook/assets/01_StudyCreationWithPrimaryZone_timestamp_5_to_53.png)

4. Select the **Country** and ensure **Assignment mode** is set to **Primary Zone**.

![Frame at 6:19](../.gitbook/assets/01_StudyCreationWithPrimaryZone_timestamp_6_to_19.png)

5. Enter postal codes one by one using the **Plus button**.

![GIF 6:41 to 6:54](../.gitbook/assets/01_StudyCreationWithPrimaryZone_timestamp_6_to_41-6_to_54.gif)

6. Click the **Save** button to render the zone on the map.

![Frame at 7:13](../.gitbook/assets/01_StudyCreationWithPrimaryZone_timestamp_7_to_13.png)

### Productivity Tips

* 💡 **Bulk Import**: Use the **Import** option in the **Actions Menu** to upload large lists of postal codes instantly.
* 💡 **Automatic Geometry**: The platform automatically renders map polygons from postal codes, removing the need for manual drawing.
* 💡 **API Integration**: Automate seasonal study creation by using the **Create Study** API endpoint.
