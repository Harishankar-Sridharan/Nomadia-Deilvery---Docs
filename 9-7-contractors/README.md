# 7. Contractors

## 7.1. Registration

In the Nomadia Delivery application, contractors must be registered by the transporter before they can upload mission data. To register a contractor, the transporter must add a contractor from the ‘Contractors.

To create a new Contractor, follow these steps:

Open the Nomadia Delivery application and navigate to the Contractor

Click on Missions

![Screenshot](<../.gitbook/assets/image-1 (4).png>)

Click on the ‘Actions’ menu and click on the ‘Add’ button

![Screenshot](<../.gitbook/assets/image-2 (4).png>)

When adding a contractor, the identifier and name are mandatory fields. The transporter can also

provide additional details, such as the contractor’s address, region, and status configuration

types."

Once the contractor’s address is entered, the map displays the corresponding geographical

Location.

![Screenshot](<../.gitbook/assets/image-3 (4).png>)

Click the “Save” to register the contractor in the delivery management system

![Screenshot](<../.gitbook/assets/image-4 (4).png>)

The new contractor will be successfully added

![Screenshot](<../.gitbook/assets/image-5 (4).png>)

Alternatively, contractors can be bulk imported using an Excel file, which helps save time

and effort when adding multiple contractors simultaneously

![Screenshot](<../.gitbook/assets/image-6 (4).png>)

Once the contractor is registered, the transporter can create contractor access from the configuration section/module. This allows the contractor to access the system and perform their tasks.

##

## 7.2. A Configuration User Type

Nomadia Delivery is introducing a new user type called Contractor. This user type can import missions, manage address lists, and track mission progress, providing contractors with greater control over their work and enhancing overall efficiency.

To create a new Contractor user type, follow these steps.

Open the Nomadia Delivery application and go to Configuration > Manage Users

![Screenshot](<../.gitbook/assets/image-7 (4).png>)

Click on the Action button and select Add

![Screenshot](<../.gitbook/assets/image-8 (3).png>)

Click OK to create a new user. Alternatively, you can create a user based on an existing one, which

speeds up the process by copying all settings from the existing user to the new profile.

![Screenshot](<../.gitbook/assets/image-9 (3).png>)

In the Generalities tab, enter the login and last name of the user, enable the user status, and then

proceed to the Access tab

![Screenshot](<../.gitbook/assets/image-10 (2).png>)

Enable web access for the user and select the contractor’s website from the drop-down Menu

![Screenshot](<../.gitbook/assets/image-11 (2).png>)

Select the appropriate contractor (created in the previous section of this document) to link with

the user, then proceed to the Roles & Rights tab

Note: If no contractor appears in the list, ensure that one has been created in the Contractors module.

![Screenshot](<../.gitbook/assets/image-12 (2).png>)

Assign the necessary rights to the new Contractor user, then proceed to the Agencies Tab

![Screenshot](<../.gitbook/assets/image-13 (2).png>)

Click on Save

![Screenshot](<../.gitbook/assets/image-14 (2).png>)

Contractor will receive an email with instructions to set a password and activate the account

Click on the link to verify the account

![Screenshot](<../.gitbook/assets/image-15 (2).png>)

Enter the verification code received by email and click Verify Code.

![Screenshot](<../.gitbook/assets/image-16 (2).png>)

Click Continue.

![Screenshot](<../.gitbook/assets/image-17 (2).png>)

Enter and confirm the new password, then click Continue.

![Screenshot](<../.gitbook/assets/image-18 (2).png>)

Review and accept the End User License Agreement (EULA), then click Continue.

![Screenshot](<../.gitbook/assets/image-19 (2).png>)

The new Contractor user can now access the application and begin performing tasks

![Screenshot](<../.gitbook/assets/image-20 (2).png>)

## 7.3. Manage Address List

Nomadia Delivery allows you to manage an address list that serves as a master record of customer information. This helps improve both the speed and accuracy of mission creation. To create an address list, follow these steps

Log in to the Nomadia Delivery application as a Contractor and go to the Address List section

![Screenshot](<../.gitbook/assets/image-21 (2).png>)

To create a new address list, click the ‘Action’ button and then select ‘Add’

![Screenshot](<../.gitbook/assets/image-22 (2).png>)

Enter the customer details one by one. To add a customer, you must provide at least two

mandatory fields: an address and an identifier.

![Screenshot](<../.gitbook/assets/image-23 (2).png>)

Alternatively, you can import an address list from an Excel file by clicking the ‘Import’ button and

selecting the desired file.

![Screenshot](<../.gitbook/assets/image-24 (2).png>)

When importing, ensure that you map the address fields or the X and Y coordinates.

Click ‘Validate’ to map the remaining data into the address list.

![Screenshot](<../.gitbook/assets/image-25 (2).png>)

A preview of all locations to be imported will be displayed during the import process.

![Screenshot](<../.gitbook/assets/image-26 (2).png>)

Map the additional data fields in the address list, such as First Name, Last Name, Designation,

Email, etc.

![Screenshot](<../.gitbook/assets/image-27 (2).png>)

After mapping all the required fields, click ‘Import’ to upload the address list to Nomadia

Delivery.

![Screenshot](<../.gitbook/assets/image-28 (2).png>)

The address list shows all customers on a map according to their geographical location.

![Screenshot](<../.gitbook/assets/image-29 (2).png>)

##

##

##

##

## 7.4. Custom Fields

### 7.4.1. Creating Custom Fields while Importing

The Nomadia Delivery application allows users to dynamically add new fields during the import process. These custom fields can be linked to various objects, including Contractors, Missions, and Addresses, and can be created in different data types such as Number, Text, list of values, Date, URL, and Boolean.

Steps to create a custom field:

Open the Nomadia Delivery application as a transporter user and navigate to any of the import

process Missions/Contractors/Address lists.

Click on the ‘Actions’ button and click ‘Import’.

Drag & drop the desired file and map the address fields or X, Y

In the ‘Fields mapping’ step, click on any unmapped field.

![Screenshot](<../.gitbook/assets/image-30 (2).png>)

Click on the ‘Add a custom field’ button from the ‘My data section.

![Screenshot](<../.gitbook/assets/image-31 (2).png>)

Enter the name of the field, select the type of the field, and Click on the ‘Validate’ button.

![Screenshot](<../.gitbook/assets/image-32 (2).png>)

The newly created field is available now for mapping.

![Screenshot](<../.gitbook/assets/image-33 (2).png>)

### 7.4.2. Inherit mission data from contractor & address list

This feature accelerates mission creation by automatically inheriting custom field data, minimizing manual input.

To enable custom field inheritance from the contractor and address list, follow the steps below:

Open the Nomadia Delivery application and go to the Configuration tab.

![Screenshot](<../.gitbook/assets/image-34 (2).png>)

Select ‘Custom fields’ from the list.

![Screenshot](<../.gitbook/assets/image-35 (2).png>)

Select the ‘Missions’ tab.

![Screenshot](<../.gitbook/assets/image-36 (2).png>)

Click the ‘Pencil’ icon to edit an existing custom field.

![Screenshot](<../.gitbook/assets/image-37 (2).png>)

From the ‘Can be initialized by’ drop-down, choose whether the field should be inherited from the contractor or the address list. Note that a custom field can be initialized from both sources at the same time. In such cases, the address list value takes priority over the contractor value.

![Screenshot](<../.gitbook/assets/image-38 (2).png>)

Click the ‘Save’ button to apply the changes.

![Screenshot](<../.gitbook/assets/image-39 (2).png>)

From the main header, click the ‘Contractors’ page

![Screenshot](<../.gitbook/assets/image-40 (2).png>)

Click the ‘Pencil’ icon to edit the contractor.

![Screenshot](<../.gitbook/assets/image-41 (2).png>)

In the Custom Fields section, all fields inherited by missions from the contractor are listed under “Custom Fields for Missions.”

![Screenshot](<../.gitbook/assets/image-42 (2).png>)

Click the ‘Address List’ tab.

![Screenshot](<../.gitbook/assets/image-43 (2).png>)

Click the ‘Pencil’ icon to edit an address.

![Screenshot](<../.gitbook/assets/image-44 (2).png>)

In the Other Data section, all fields inherited by missions from the address are listed under “Custom Fields for Missions.”

![Screenshot](<../.gitbook/assets/image-45 (2).png>)

Select a value for the custom field in the contractor or address list, then click ‘Save’ to apply the changes.

![Screenshot](<../.gitbook/assets/image-46 (2).png>)

When creating a mission, the mission custom fields are automatically populated based on the selected contractor or address from the address list.

![Screenshot](<../.gitbook/assets/image-47 (2).png>)

![Screenshot](<../.gitbook/assets/image-48 (2).png>)

By automatically initializing fields, users don’t need to re-enter the same data during mission creation, improving consistency and efficiency.

### 7.4.3. Configuring Mission Visibility

### 7.4.3.1. Mission visibility based on a custom field

Mission visibility was previously determined mainly by the user’s agency association. To provide greater flexibility and support diverse business needs, visibility restrictions are now extended to include custom field–based rules, in addition to the existing agency-based controls.

To set up a custom field as a mission visibility restriction, follow the steps below.

Open the Nomadia Delivery application and navigate to the Configuration tab.

![Screenshot](<../.gitbook/assets/image-49 (2).png>)

From the list, select Custom fields.

![Screenshot](<../.gitbook/assets/image-50 (2).png>)

Click the Missions tab.

![Screenshot](<../.gitbook/assets/image-51 (2).png>)

Click the Pencil icon to edit any existing custom field.

Only one custom field can be used to control mission visibility.

![Screenshot](<../.gitbook/assets/image-52 (2).png>)

A toggle option is available to enable mission visibility for each mission custom field; however, it can be activated for only one field at a time.

Note: The toggle is available only for custom fields of the List of Values type.

![Screenshot](<../.gitbook/assets/image-53 (2).png>)

After enabling the toggle, click Save to apply the changes.

![Screenshot](<../.gitbook/assets/image-54 (2).png>)

### 7.4.3.2. Mission visibility based on a custom field for users

Select the Manage user’s menu.

![Screenshot](<../.gitbook/assets/image-55 (2).png>)

Click the Pencil icon to edit the required user.

![Screenshot](<../.gitbook/assets/image-56 (2).png>)

Open the Roles & rights tab.

![Screenshot](<../.gitbook/assets/image-57 (2).png>)

Under the Mission section, a new Mission Visibility drop-down is available, allowing you to select the value associated with the selected user.

![Screenshot](<../.gitbook/assets/image-58 (2).png>)

Select the required custom field value and click Save.

![Screenshot](<../.gitbook/assets/image-59 (2).png>)

Log in as the configured user and navigate to the Missions tab.

![Screenshot](<../.gitbook/assets/image-60 (2).png>)

Click the Prefilter option.

The prefilter is automatically applied based on the mission visibility custom field and the value configured in the user’s Roles & Rights.

![Screenshot](<../.gitbook/assets/image-61 (2).png>)

This mission visibility prefilter is set to read-only and cannot be modified by the user. To remove or modify this restriction, contact the administrator.

The mission table will display only the missions that match the mission visibility condition, in addition to the existing agency-based prefilter.

![Screenshot](<../.gitbook/assets/image-62 (2).png>)

## 7.5. Coloring and Filter

1. Use the ‘Coloring’ and ‘Filter’ options to organize and display data according to specific

conditions.

![Screenshot](<../.gitbook/assets/image-63 (2).png>)

![Screenshot](<../.gitbook/assets/image-64 (2).png>)

In the ‘Coloring’ popup, apply conditions based on your preference

![Screenshot](<../.gitbook/assets/image-65 (2).png>)

3. The list then displays the addresses with custom colors based on the conditions you set

![Screenshot](<../.gitbook/assets/image-66 (2).png>)

## 7.6. Contractor Restrictions

Contractor Restrictions allow you to precisely control access to templates and mission editing permissions.

To restrict contractors to specific documents and mission configuration templates, follow the steps below.

Open the Nomadia Delivery application and go to the Configuration tab.

![Screenshot](<../.gitbook/assets/image-67 (2).png>)

Click the Contractors page from the main header.

![Screenshot](<../.gitbook/assets/image-68 (2).png>)

Click the Pencil icon to edit the contractor details.

![Screenshot](<../.gitbook/assets/image-69 (2).png>)

In the Missions section, multiple restrictions can be applied to contractors.

![Screenshot](<../.gitbook/assets/image-70 (2).png>)

The Mission Extract Template drop-down allows users to select only the mission extracted templates applicable to the contractor.

The Sticker Template drop-down allows users to select only the sticker templates applicable to the contractor.

The Bulk Edit drop-down allows users to select only the edit configurations applicable to the contractor.

After making the selections, click Save to apply the restrictions to the selected contractor.

![Screenshot](<../.gitbook/assets/image-71 (2).png>)

To prevent contractors from editing missions after printing, follow the steps below.

Open the Nomadia Delivery application and go to the Configuration tab.

![Screenshot](<../.gitbook/assets/image-72 (2).png>)

Select Manage Users from the list.

![Screenshot](<../.gitbook/assets/image-73 (2).png>)

Click the Pencil icon to edit a contractor user.

![Screenshot](<../.gitbook/assets/image-74 (2).png>)

Click the Roles & Rights tab.

Under the Missions section, disable the Modify Mission After Printing right.

![Screenshot](<../.gitbook/assets/image-75 (2).png>)

Click Save to apply the changes

![Screenshot](<../.gitbook/assets/image-76 (2).png>)

Go to the Missions tab and select any Waiting mission.

![Screenshot](<../.gitbook/assets/image-77 (2).png>)

Click the Actions menu and select Generate Sticker Labels.

![Screenshot](<../.gitbook/assets/image-78 (2).png>)

Click the Print button to generate the sticker

![Screenshot](<../.gitbook/assets/image-79 (2).png>)

After printing, click the Pencil icon to edit the mission.

![Screenshot](<../.gitbook/assets/image-80 (2).png>)

A warning appears in the mission editor, and mission editing is blocked because the user does not have permission to modify it after sticker printing.

![Screenshot](<../.gitbook/assets/image-81 (2).png>)

This ensures better traceability and protects mission data once documents are generated.
