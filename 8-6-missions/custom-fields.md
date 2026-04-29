# Custom Fields

#### Creating Custom Fields while Importing

The Nomadia Delivery application allows users to dynamically add new fields during the import process. These custom fields can be linked to various objects, including Contractors, Missions, and Addresses, and can be created in different data types such as Number, Text, list of values, Date, URL, and Boolean.

**Steps to create a custom field**:

1. Open the Nomadia Delivery application as a transporter user and navigate to any of the import process Missions/Contractors/Address lists.
2. Click on the ‘**Actions**’ button and click ‘Import’.
3. Drag & drop the desired file and map the address fields or X, Y
4. In the ‘Fields mapping’ step, click on any **unmapped** field.

![](<../.gitbook/assets/image-30 (2).png>)

5. Click on the ‘**Add a custom field**’ button from the ‘My data section.

![](<../.gitbook/assets/image-31 (2).png>)

6. Enter the **name of the field**, select the type of the field, and Click on the ‘**Validate**’ button.

![](<../.gitbook/assets/image-32 (2).png>)

7. The newly created field is available now for mapping.

![](<../.gitbook/assets/image-33 (2).png>)

#### Inherit mission data from contractor & address list

This feature accelerates mission creation by automatically inheriting custom field data, minimizing manual input.

To enable custom field inheritance from the contractor and address list, follow the steps below:

1. Open the Nomadia Delivery application and go to the **Configuration** tab.

![](<../.gitbook/assets/image-34 (2).png>)

2. Select ‘**Custom fields**’ from the list.

![](<../.gitbook/assets/image-35 (2).png>)

3. Select the ‘**Missions**’ tab.

![](<../.gitbook/assets/image-36 (2).png>)

4. Click the ‘**Pencil**’ icon to edit an existing custom field.

![](<../.gitbook/assets/image-37 (2).png>)

5. From the ‘Can be initialized by’ drop-down, choose whether the field should be inherited from the contractor or the address list. Note that a custom field can be initialized from both sources at the same time. In such cases, the address list value takes priority over the contractor value.

![](<../.gitbook/assets/image-38 (2).png>)

6. Click the ‘**Save**’ button to apply the changes.

![](<../.gitbook/assets/image-39 (2).png>)

From the main header, click the ‘**Contractors**’ page

![](<../.gitbook/assets/image-40 (2).png>)

Click the ‘**Pencil**’ icon to edit the contractor.

![](<../.gitbook/assets/image-41 (2).png>)

In the Custom Fields section, all fields inherited by missions from the contractor are listed under “**Custom Fields for Missions.**”

![](<../.gitbook/assets/image-42 (2).png>)

Click the ‘**Address List**’ tab.

![](<../.gitbook/assets/image-43 (2).png>)

Click the ‘**Pencil**’ icon to edit an address.

![](<../.gitbook/assets/image-44 (2).png>)

In the Other Data section, all fields inherited by missions from the address are listed under “**Custom Fields for Missions**.”

![](<../.gitbook/assets/image-45 (2).png>)

Select a value for the custom field in the contractor or address list, then click ‘**Save**’ to apply the changes.

![](<../.gitbook/assets/image-46 (2).png>)

When creating a mission, the mission custom fields are automatically populated based on the selected contractor or address from the address list.

![](<../.gitbook/assets/image-48 (2).png>)

By automatically initializing fields, users don’t need to re-enter the same data during mission creation, improving consistency and efficiency.

#### Configuring Mission Visibility

**Mission visibility based on a custom field**

Mission visibility was previously determined mainly by the user’s agency association. To provide greater flexibility and support diverse business needs, visibility restrictions are now extended to include custom field–based rules, in addition to the existing agency-based controls.

To set up a custom field as a mission visibility restriction, follow the steps below.

1. Open the Nomadia Delivery application and navigate to the **Configuration** tab.

![](<../.gitbook/assets/image-49 (2).png>)

2. From the list, select **Custom fields**.

![](<../.gitbook/assets/image-50 (2).png>)

3. Click the **Missions** tab.

![](<../.gitbook/assets/image-51 (2).png>)

4. Click the **Pencil** icon to edit any existing custom field.

Only one custom field can be used to control mission visibility.

![](<../.gitbook/assets/image-52 (2).png>)

A toggle option is available to enable mission visibility for each mission custom field; however, it can be activated for only one field at a time.

Note: The toggle is available only for custom fields of the List of Values type.

![](<../.gitbook/assets/image-53 (2).png>)

5. After enabling the toggle, click **Save** to apply the changes.

![](<../.gitbook/assets/image-54 (2).png>)

**Mission visibility based on a custom field for users**

1. Select the **Manage user’s** menu.

![](<../.gitbook/assets/image-55 (2).png>)

2. Click the **Pencil** icon to edit the required user.

![](<../.gitbook/assets/image-56 (2).png>)

3. Open the **Roles & rights** tab.

![](<../.gitbook/assets/image-57 (2).png>)

4. Under the Mission section, a new Mission Visibility drop-down is available, allowing you to select the value associated with the selected user.

![](<../.gitbook/assets/image-58 (2).png>)

5. Select the required custom field value and click **Save**.

![](<../.gitbook/assets/image-59 (2).png>)

6. Log in as the configured user and navigate to the **Missions** tab.

![](<../.gitbook/assets/image-60 (2).png>)

7. Click the **Prefilter** option.
8. The prefilter is automatically applied based on the mission visibility custom field and the value configured in the user’s Roles & Rights.

![](<../.gitbook/assets/image-61 (2).png>)

9. This mission visibility prefilter is set to read-only and cannot be modified by the user. To remove or modify this restriction, contact the administrator.
10. The mission table will display only the missions that match the mission visibility condition, in addition to the existing agency-based prefilter.

<figure><img src="../.gitbook/assets/image (4).png" alt=""><figcaption></figcaption></figure>

To group custom fields in the mission creation form using a group name:

* Open the Nomadia Delivery application and go to the **Configuration** tab.

<figure><img src="../.gitbook/assets/image (17) (1).png" alt=""><figcaption></figcaption></figure>

* From the list, select **Custom fields**.

<figure><img src="../.gitbook/assets/image (18) (1).png" alt=""><figcaption></figcaption></figure>

* Click on **Missions**.

<figure><img src="../.gitbook/assets/image (19) (1).png" alt=""><figcaption></figcaption></figure>

* Click the **Pencil icon** to edit an existing custom field.

<figure><img src="../.gitbook/assets/image (20) (1).png" alt=""><figcaption></figcaption></figure>

*   In the **Group name** field:

    * Enter a **group name**.
    * Choose an existing group or create a new one.

    <figure><img src="../.gitbook/assets/image (21) (1).png" alt=""><figcaption></figcaption></figure>
* Click **Save** to apply the changes.

<figure><img src="../.gitbook/assets/image (22) (1).png" alt=""><figcaption></figcaption></figure>

* The assigned group name will be displayed in the Custom Fields table.

<figure><img src="../.gitbook/assets/image (23) (1).png" alt=""><figcaption></figcaption></figure>
