# 01_StudyCreationWithPrimaryZone
# Case Studies

Studies allow you to organize delivery territories and manage seasonal volume changes effectively. You can create multiple studies with specific activation windows to ensure your logistics operations always reflect accurate coverage. By the end of this guide, you will be able to configure a study and map a primary zone for your field teams.

### Getting Started

*   Access to the Nomadia Delivery SaaS application.
*   User permissions for **List of zones**, **Create and update zones**, and **Delete studies**.

1.  Open the **Configuration** module in the application banner.
    ![Frame at 1:51](../images/01_StudyCreationWithPrimaryZone_timestamp_1_to_51.png "Configuration Module – The entry point for managing application settings and users.")
2.  Navigate to the **Manage Users** page.
    ![Frame at 1:59](../images/01_StudyCreationWithPrimaryZone_timestamp_1_to_59.png "Manage Users – The screen displaying all users configured in the application.")
3.  Select and edit a specific user.
4.  Open the **Roles and rights** tab.
    ![Frame at 2:16](../images/01_StudyCreationWithPrimaryZone_timestamp_2_to_16.png "Roles and Rights Tab – Where zone and study management permissions are assigned.")
5.  Enable the rights associated with the **Zone module**.
6.  Click the **Save** button.

### Feature Overview

*   **Study**: A structured object defining the organization of your delivery territories.
    ![Frame at 0:45](../images/01_StudyCreationWithPrimaryZone_timestamp_0_to_45.png "Study Definition – A visual hierarchy of how territories are structured.")
*   **Primary Zone**: A top-level geographical area tied to postal codes and assigned to a team.
    ![Frame at 1:00](../images/01_StudyCreationWithPrimaryZone_timestamp_1_to_00.png "Primary Zone – A mapped area representing a specific delivery territory.")
*   **Validity Start/End Date**: The fields defining the overall calendar duration for a study.
*   **Actions Menu**: The dropdown used to create, import, or manage studies and zones.
    ![Frame at 3:29](../images/01_StudyCreationWithPrimaryZone_timestamp_3_to_29.png "Actions Menu – The interface element used to initiate creation tasks.")

### How To: Create a Study

1.  Navigate to the **Configuration** module.
2.  Click **Studies and zones** in the **Delivery** section.
    ![Frame at 3:15](../images/01_StudyCreationWithPrimaryZone_timestamp_3_to_15.png "Studies and Zones Page – The management hub for logistics territories.")
3.  Open the **Actions** menu and select **Create empty study**.
    ![Flow 3:29 to 3:44](../images/01_StudyCreationWithPrimaryZone_timestamp_3_to_29_to_3_to_44.gif "Create Empty Study – The workflow to open the study creation form.")
4.  Enter the **Identifier**, **Name**, and select the **Agency**.
5.  Set the **Validity start date** and **Validity end date**.
6.  Toggle the switch to enable the study.
7.  Select the active **Days in a week**.
8.  Configure specific seasonal **Activation** dates if required.
9.  Click the **Save** button.

### How To: Create a Primary Zone

1.  Open your new study and select the **Zone** tab.
2.  Open the **Actions** menu and select **Add a postal code zone**.
    ![Flow 5:31 to 5:47](../images/01_StudyCreationWithPrimaryZone_timestamp_5_to_31_to_5_to_47.gif "Add Postal Code Zone – The transition to the zone configuration form.")
3.  Fill in the **Identifier**, **Name**, and **Agency**.
4.  Select the **Country** for the zone.
5.  Set the **Assignment mode** field to **Primary zone**.
    ![Frame at 6:26](../images/01_StudyCreationWithPrimaryZone_timestamp_6_to_26.png "Assignment Mode – Choosing Primary Zone to define the area as a top-level territory.")
6.  Enter postal codes manually or use the **Plus** button.
7.  Select the **Import** option for bulk uploads of large postal code lists.
    ![Flow 6:41 to 7:07](../images/01_StudyCreationWithPrimaryZone_timestamp_6_to_41_to_7_to_07.gif "Postal Code Entry – Adding codes to define the geographical area.")
8.  Click the **Save** button.
9.  View the rendered polygon on the map on the right.
    ![Frame at 7:30](../images/01_StudyCreationWithPrimaryZone_timestamp_7_to_30.png "Map Visualization – The automatically generated geometry of the zone.")

### Productivity Tips

- 💡 **Bulk Upload**: Use the import option to save time when setting up zones across an entire region.
- 💡 **Automatic Mapping**: The platform automatically renders polygons from postal codes, so no manual drawing is required.
- ⚠️ **Assignment Mode**: Always select Primary Zone for top-level areas to ensure they are not categorized as subzones.

