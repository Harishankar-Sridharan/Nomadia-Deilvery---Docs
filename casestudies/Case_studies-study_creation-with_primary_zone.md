# Case_studies-study_creation-with_primary_zone
# Case-Studies

Manage delivery territories effectively during peak seasons and fluctuating volumes. Organize coverage by creating seasonal plans that activate automatically at the right time. Achieve precise logistics operations that reflect real-world coverage for your field teams.

### Getting Started

To create and manage studies, ensure you have the correct administrative permissions.

*   Access to the **Configuration** module.
*   Permission for **Create and update zones** and **Create and update studies**.

1.  Click the **Configuration** module in the top banner.
    ![Frame at 1:51](../images/Case-Studies-Study-creation-with-Primary-Zone_timestamp_1_to_51.png "Banner – The Configuration module is located in the top banner.")
2.  Select the **Manage Users** page.
    ![Frame at 1:59](../images/Case-Studies-Study-creation-with-Primary-Zone_timestamp_1_to_59.png "Manage Users – List of application users.")
3.  Edit the specific user and click the **Roles and Rights** tab.
    ![Frame at 2:16](../images/Case-Studies-Study-creation-with-Primary-Zone_timestamp_2_to_16.png "Roles and Rights – Access settings for the study module.")
4.  Enable rights for **Create and update zones** and **List of zones**.
5.  Click the **Save** button to apply permissions.
    ![Frame at 3:00](../images/Case-Studies-Study-creation-with-Primary-Zone_timestamp_3_to_00.png "Save Button – Applying user permissions.")

### Feature Overview

*   **Study**: A structured object defining how delivery territories are organized.
    ![Frame at 0:45](../images/Case-Studies-Study-creation-with-Primary-Zone_timestamp_0_to_45.png "Study Structure – Top level organization of territories.")
*   **Primary Zone**: A top-level geographical area assigned to a team and tied to postal codes.
    ![Frame at 1:06](../images/Case-Studies-Study-creation-with-Primary-Zone_timestamp_1_to_06.png "Zone Map – Visualization of geographical coverage.")
*   **Study Management Page**: Your central hub for creating and editing studies and zones.
    ![Frame at 3:21](../images/Case-Studies-Study-creation-with-Primary-Zone_timestamp_3_to_21.png "Study Management – Central dashboard for logistics planning.")

### How To: Create a Study

1.  Navigate to the **Studies and Zones** page under the **Delivery** section in **Configuration**.
    ![Flow 3:08 to 3:21](../images/Case-Studies-Study-creation-with-Primary-Zone_timestamp_3_to_08_to_3_to_21.gif "Navigation – Accessing the study management page.")
2.  Click the **Actions** menu in the top right.
    ![Frame at 3:29](../images/Case-Studies-Study-creation-with-Primary-Zone_timestamp_3_to_29.png "Actions Menu – Options for study creation.")
3.  Select **Create Empty Study**.
4.  Enter the **Identifier**, **Name**, and **Agency**.
5.  Set the **Validity Start Date** and **Validity End Date**.
6.  Toggle the study to **Enable**.
7.  Select the active days of the week for this plan.
8.  Define the specific seasonal activation period.
9.  Click the **Save** button.
    ![Frame at 5:00](../images/Case-Studies-Study-creation-with-Primary-Zone_timestamp_5_to_00.png "Save Study – Confirming new study configuration.")

### How To: Create a Primary Zone

1.  Open the **Zone** tab within your new study.
    ![Frame at 5:31](../images/Case-Studies-Study-creation-with-Primary-Zone_timestamp_5_to_31.png "Zone Tab – Viewing zones within a specific study.")
2.  Open the **Actions** menu.
3.  Select **Add a Postal Code Zone**.
    ![Frame at 5:44](../images/Case-Studies-Study-creation-with-Primary-Zone_timestamp_5_to_44.png "Add Zone – Adding a new postal code area.")
4.  Fill in the **Identifier**, **Name**, and **Agency**.
5.  Select the **Country** and set the **Postal Code Normalized Length**.
6.  Select **Primary Zone** in the **Assignment Mode** field.
    ![Frame at 6:26](../images/Case-Studies-Study-creation-with-Primary-Zone_timestamp_6_to_26.png "Assignment Mode – Designating the zone as a top-level area.")
7.  Enter postal codes manually using the **Plus** button.
    ![Frame at 6:50](../images/Case-Studies-Study-creation-with-Primary-Zone_timestamp_6_to_50.png "Add Postal Codes – Manually entering territory data.")
8.  Click the **Save** button.
    ![Frame at 7:13](../images/Case-Studies-Study-creation-with-Primary-Zone_timestamp_7_to_13.png "Save Zone – Finalizing the primary zone.")

### Productivity Tips

*   💡 **Bulk Import**: Use the **Import** option in the **Actions** menu to upload large lists of postal codes.
*   💡 **Instant Visualization**: Watch the map on the right to see postal code polygons rendered automatically.
*   💡 **API Automation**: Use the **create study** endpoint to trigger study creation programmatically for large workflows.
*   ⚠️ **Assignment Mode**: Always select **Primary Zone** for top-level areas to avoid creating subzones by mistake.

