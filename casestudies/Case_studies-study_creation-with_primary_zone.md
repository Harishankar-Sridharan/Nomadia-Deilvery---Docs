# Study Creation with Primary Zone

## Case\_studies-study\_creation-with\_primary\_zone

## Case-Studies

Manage delivery territories effectively during peak seasons and fluctuating volumes. Organize coverage by creating seasonal plans that activate automatically at the right time. Achieve precise logistics operations that reflect real-world coverage for your field teams.

#### Getting Started

To create and manage studies, ensure you have the correct administrative permissions.

* Access to the **Configuration** module.
* Permission for **Create and update zones** and **Create and update studies**.

1. Click the **Configuration** module in the top banner. ![Frame at 1:51](../.gitbook/assets/Case-Studies-Study-creation-with-Primary-Zone_timestamp_1_to_51.png)
2. Select the **Manage Users** page. ![Frame at 1:59](../.gitbook/assets/Case-Studies-Study-creation-with-Primary-Zone_timestamp_1_to_59.png)
3. Edit the specific user and click the **Roles and Rights** tab. ![Frame at 2:16](../.gitbook/assets/Case-Studies-Study-creation-with-Primary-Zone_timestamp_2_to_16.png)
4. Enable rights for **Create and update zones** and **List of zones**.
5. Click the **Save** button to apply permissions. ![Frame at 3:00](../.gitbook/assets/Case-Studies-Study-creation-with-Primary-Zone_timestamp_3_to_00.png)

#### Feature Overview

* **Study**: A structured object defining how delivery territories are organized. ![Frame at 0:45](../.gitbook/assets/Case-Studies-Study-creation-with-Primary-Zone_timestamp_0_to_45.png)
* **Primary Zone**: A top-level geographical area assigned to a team and tied to postal codes. ![Frame at 1:06](../.gitbook/assets/Case-Studies-Study-creation-with-Primary-Zone_timestamp_1_to_06.png)
* **Study Management Page**: Your central hub for creating and editing studies and zones. ![Frame at 3:21](../.gitbook/assets/Case-Studies-Study-creation-with-Primary-Zone_timestamp_3_to_21.png)

#### How To: Create a Study

1. Navigate to the **Studies and Zones** page under the **Delivery** section in **Configuration**. ![Flow 3:08 to 3:21](../.gitbook/assets/Case-Studies-Study-creation-with-Primary-Zone_timestamp_3_to_08_to_3_to_21.gif)
2. Click the **Actions** menu in the top right. ![Frame at 3:29](../.gitbook/assets/Case-Studies-Study-creation-with-Primary-Zone_timestamp_3_to_29.png)
3. Select **Create Empty Study**.
4. Enter the **Identifier**, **Name**, and **Agency**.
5. Set the **Validity Start Date** and **Validity End Date**.
6. Toggle the study to **Enable**.
7. Select the active days of the week for this plan.
8. Define the specific seasonal activation period.
9. Click the **Save** button. ![Frame at 5:00](../.gitbook/assets/Case-Studies-Study-creation-with-Primary-Zone_timestamp_5_to_00.png)

#### How To: Create a Primary Zone

1. Open the **Zone** tab within your new study. ![Frame at 5:31](../.gitbook/assets/Case-Studies-Study-creation-with-Primary-Zone_timestamp_5_to_31.png)
2. Open the **Actions** menu.
3. Select **Add a Postal Code Zone**. ![Frame at 5:44](../.gitbook/assets/Case-Studies-Study-creation-with-Primary-Zone_timestamp_5_to_44.png)
4. Fill in the **Identifier**, **Name**, and **Agency**.
5. Select the **Country** and set the **Postal Code Normalized Length**.
6. Select **Primary Zone** in the **Assignment Mode** field. ![Frame at 6:26](../.gitbook/assets/Case-Studies-Study-creation-with-Primary-Zone_timestamp_6_to_26.png)
7. Enter postal codes manually using the **Plus** button. ![Frame at 6:50](../.gitbook/assets/Case-Studies-Study-creation-with-Primary-Zone_timestamp_6_to_50.png)
8. Click the **Save** button. ![Frame at 7:13](../.gitbook/assets/Case-Studies-Study-creation-with-Primary-Zone_timestamp_7_to_13.png)

#### Productivity Tips

* 💡 **Bulk Import**: Use the **Import** option in the **Actions** menu to upload large lists of postal codes.
* 💡 **Instant Visualization**: Watch the map on the right to see postal code polygons rendered automatically.
* 💡 **API Automation**: Use the **create study** endpoint to trigger study creation programmatically for large workflows.
* ⚠️ **Assignment Mode**: Always select **Primary Zone** for top-level areas to avoid creating subzones by mistake.
