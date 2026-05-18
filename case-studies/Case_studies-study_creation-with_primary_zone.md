# Study Creation with Primary Zone

Manage delivery territories effectively during peak seasons and fluctuating volumes. Organize coverage by creating seasonal plans that activate automatically at the right time. Achieve precise logistics operations that reflect real-world coverage for your field teams.

#### Getting Started

* To create and manage studies, ensure you have the correct administrative permissions:
  * Access to the Configuration module
  * Permission for Create and update zones
  * Permission for Create and update studies
* Click the Configuration module in the top banner.

![](../.gitbook/assets/01_StudyCreationWithPrimaryZone_timestamp_1_to_51.png)

* Select the **Manage Users** page.

![](../.gitbook/assets/01_StudyCreationWithPrimaryZone_timestamp_1_to_59.png)

* Edit the specific user and click the **Roles and Rights** tab.

![](../.gitbook/assets/01_StudyCreationWithPrimaryZone_timestamp_2_to_16.png)

* Enable rights for **Create and update zones** and **List of zones**.
* Click the **Save** button to apply permissions.

![](../.gitbook/assets/Case-Studies-Study-creation-with-Primary-Zone_timestamp_3_to_00.png)

#### Feature Overview

* **Study**: A structured object defining how delivery territories are organized.
* **Primary Zone**: A top-level geographical area assigned to a team and tied to postal codes.
* **Study Management Page**: Your central hub for creating and editing studies and zones.

#### How To: Create a Study

1. Navigate to the **Studies and Zones** page under the **Delivery** section in **Configuration**.

![](../.gitbook/assets/Case-Studies-Study-creation-with-Primary-Zone_timestamp_3_to_08_to_3_to_21.gif)

2. Click the **Actions** menu in the top right.

<figure><img src="../.gitbook/assets/ApplicationFrameHost_M9TUEJn4t8.png" alt=""><figcaption></figcaption></figure>

3. Select **Create Empty Study**.
4. Enter the **Identifier**, **Name**, and **Agency**.
5. Set the **Validity Start Date** and **Validity End Date**.
6. Toggle the study to **Enable**.
7. Select the active days of the week for this plan.
8. Define the specific seasonal activation period.
9. Click the **Save** button.

![](../.gitbook/assets/01_StudyCreationWithPrimaryZone_timestamp_5_to_00.png)

#### How To: Create a Primary Zone

1. Open the **Zone** tab within your new study.

![](../.gitbook/assets/01_StudyCreationWithPrimaryZone_timestamp_5_to_31.png)

2. Open the **Actions** menu.
3. Select **Add a Postal Code Zone**.

![](../.gitbook/assets/Case-Studies-Study-creation-with-Primary-Zone_timestamp_5_to_44.png)

4. Fill in the **Identifier**, **Name**, and **Agency**.
5. Select the **Country** and set the **Postal Code Normalized Length**.
6. Select **Primary Zone** in the **Assignment Mode** field.

![](../.gitbook/assets/01_StudyCreationWithPrimaryZone_timestamp_6_to_26.png)

7. Enter postal codes manually using the **Plus** button.

![](../.gitbook/assets/Case-Studies-Study-creation-with-Primary-Zone_timestamp_6_to_50.png)

8. Click the **Save** button.

![](../.gitbook/assets/01_StudyCreationWithPrimaryZone_timestamp_7_to_13.png)

#### Productivity Tips

* 💡 **Bulk Import**: Use the **Import** option in the **Actions** menu to upload large lists of postal codes.
* 💡 **Instant Visualization**: Watch the map on the right to see postal code polygons rendered automatically.
* 💡 **API Automation**: Use the **create study** endpoint to trigger study creation programmatically for large workflows.
* ⚠️ **Assignment Mode**: Always select **Primary Zone** for top-level areas to avoid creating subzones by mistake.
