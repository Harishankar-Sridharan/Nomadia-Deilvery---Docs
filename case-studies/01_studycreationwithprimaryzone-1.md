# Study Creation with Primary Zone - Duplicate

Studies are structured objects that define the organization of your delivery territories. They allow you to create geographical zones tied to postal codes that reflect real-world logistics needs. By using multiple studies, you can activate specific coverage plans based on seasonality or holiday campaigns.

### Getting Started

To begin creating studies, ensure you have the appropriate administrative permissions.

**Prerequisites:**

* Access to the **Configuration module** in the **Nomadia Delivery** application banner.
* The following rights assigned in the **Roles and rights** tab: **List of zones**, **Assign zones**, **Create and update zones**, **Access to the sectorization tool**, and **Delete zones and delete studies**.

**Initial Setup Steps:**

1. Click the **Configuration module** in the application banner.&#x20;
2. Select the **Manage users** page.&#x20;
3. Edit the specific user and navigate to the **Roles and rights** tab.&#x20;
4. Assign the necessary rights related to the zone module and click **Save**.&#x20;

### Feature Overview

* **Study Management Page**: Your central hub for creating and editing all studies and zones.&#x20;
* **Actions Menu**: A dropdown in the top right used to trigger creation and import tasks.&#x20;



![Frame at 3:29](<../.gitbook/assets/01_StudyCreationWithPrimaryZone_timestamp_3_to_29 (1).png>)

* **Validity Start/End Date**: Fields defining the total lifespan of a study.&#x20;
* **Zone Tab**: A sub-section within a study used to manage specific geographic areas.&#x20;
* **Assignment Mode**: A critical setting to designate a zone as a **Primary Zone** (top level).&#x20;
* **Map View**: A visual pane that automatically renders polygons for entered postal codes.&#x20;

### How To: Create an Empty Study

1. Open the **Configuration module** and select **Studies and Zones** under the **Delivery** section.&#x20;
2. Click the **Actions Menu** and select **Create empty study**.&#x20;
3. Enter the **Identifier**, **Name**, and select the **Agency**.&#x20;
4. Set the **Validity start date** and **Validity end date**.&#x20;
5. Toggle the switch to **Enable** the study.&#x20;
6. Select specific active days (e.g., Monday to Friday).&#x20;
7. Configure the seasonal activation period within the year.&#x20;
8. Click the **Save** button.&#x20;

### How To: Add a Primary Zone

1. Navigate to the **Zone Tab** within your created study.&#x20;
2. Open the **Actions Menu** and select **Add a postal code zone**.&#x20;
3. Enter the **Identifier**, **Name**, and **Agency**.&#x20;
4. Select the **Country** and ensure **Assignment mode** is set to **Primary Zone**.&#x20;
5. Enter postal codes one by one using the **Plus button**.&#x20;
6. Click the **Save** button to render the zone on the map.&#x20;

### Productivity Tips

* 💡 **Bulk Import**: Use the **Import** option in the **Actions Menu** to upload large lists of postal codes instantly.
* 💡 **Automatic Geometry**: The platform automatically renders map polygons from postal codes, removing the need for manual drawing.
* 💡 **API Integration**: Automate seasonal study creation by using the **Create Study** API endpoint.
