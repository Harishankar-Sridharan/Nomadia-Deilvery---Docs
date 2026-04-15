# 7. Contractors

## 7.1. Registration

In the Nomadia Delivery application, contractors must be registered by the transporter before they can upload mission data. To register a contractor, the transporter must add a contractor from the ‘Contractors.

To create a new Contractor, follow these steps:

Open the Nomadia Delivery application and navigate to the Contractor

Click on Missions

![Screenshot](./screenshots/image-1.png)

Click on the ‘Actions’ menu and click on the ‘Add’ button

![Screenshot](./screenshots/image-2.png)

When adding a contractor, the identifier and name are mandatory fields. The transporter can also

provide additional details, such as the contractor’s address, region, and status configuration

types."

Once the contractor’s address is entered, the map displays the corresponding geographical

Location.

![Screenshot](./screenshots/image-3.png)

Click the “Save” to register the contractor in the delivery management system

![Screenshot](./screenshots/image-4.png)

The new contractor will be successfully added

![Screenshot](./screenshots/image-5.png)

Alternatively, contractors can be bulk imported using an Excel file, which helps save time

and effort when adding multiple contractors simultaneously

![Screenshot](./screenshots/image-6.png)

Once the contractor is registered, the transporter can create contractor access from the configuration section/module. This allows the contractor to access the system and perform their tasks.

## 

## 7.2. A Configuration User Type

Nomadia Delivery is introducing a new user type called Contractor. This user type can import missions, manage address lists, and track mission progress, providing contractors with greater control over their work and enhancing overall efficiency.

To create a new Contractor user type, follow these steps.

Open the Nomadia Delivery application and go to Configuration > Manage Users

![Screenshot](./screenshots/image-7.png)

Click on the Action button and select Add

![Screenshot](./screenshots/image-8.png)

Click OK to create a new user. Alternatively, you can create a user based on an existing one, which

speeds up the process by copying all settings from the existing user to the new profile.

![Screenshot](./screenshots/image-9.png)

In the Generalities tab, enter the login and last name of the user, enable the user status, and then

proceed to the Access tab

![Screenshot](./screenshots/image-10.png)

Enable web access for the user and select the contractor’s website from the drop-down Menu

![Screenshot](./screenshots/image-11.png)

Select the appropriate contractor (created in the previous section of this document) to link with

the user, then proceed to the Roles & Rights tab

Note: If no contractor appears in the list, ensure that one has been created in the Contractors module.

![Screenshot](./screenshots/image-12.png)

Assign the necessary rights to the new Contractor user, then proceed to the Agencies Tab

![Screenshot](./screenshots/image-13.png)

Click on Save

![Screenshot](./screenshots/image-14.png)

Contractor will receive an email with instructions to set a password and activate the account

Click on the link to verify the account

![Screenshot](./screenshots/image-15.png)

Enter the verification code received by email and click Verify Code.

![Screenshot](./screenshots/image-16.png)

Click Continue.

![Screenshot](./screenshots/image-17.png)

Enter and confirm the new password, then click Continue.

![Screenshot](./screenshots/image-18.png)

Review and accept the End User License Agreement (EULA), then click Continue.

![Screenshot](./screenshots/image-19.png)

The new Contractor user can now access the application and begin performing tasks

![Screenshot](./screenshots/image-20.png)

## 7.3. Manage Address List

Nomadia Delivery allows you to manage an address list that serves as a master record of customer information. This helps improve both the speed and accuracy of mission creation. To create an address list, follow these steps

Log in to the Nomadia Delivery application as a Contractor and go to the Address List section

![Screenshot](./screenshots/image-21.png)

To create a new address list, click the ‘Action’ button and then select ‘Add’

![Screenshot](./screenshots/image-22.png)

Enter the customer details one by one. To add a customer, you must provide at least two

mandatory fields: an address and an identifier.

![Screenshot](./screenshots/image-23.png)

Alternatively, you can import an address list from an Excel file by clicking the ‘Import’ button and

selecting the desired file.

![Screenshot](./screenshots/image-24.png)

When importing, ensure that you map the address fields or the X and Y coordinates.

Click ‘Validate’ to map the remaining data into the address list.

![Screenshot](./screenshots/image-25.png)

A preview of all locations to be imported will be displayed during the import process.

![Screenshot](./screenshots/image-26.png)

Map the additional data fields in the address list, such as First Name, Last Name, Designation,

Email, etc.

![Screenshot](./screenshots/image-27.png)

After mapping all the required fields, click ‘Import’ to upload the address list to Nomadia

Delivery.

![Screenshot](./screenshots/image-28.png)

The address list shows all customers on a map according to their geographical location.

![Screenshot](./screenshots/image-29.png)

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

![Screenshot](./screenshots/image-30.png)

Click on the ‘Add a custom field’ button from the ‘My data section.

![Screenshot](./screenshots/image-31.png)

Enter the name of the field, select the type of the field, and Click on the ‘Validate’ button.

![Screenshot](./screenshots/image-32.png)

The newly created field is available now for mapping.

![Screenshot](./screenshots/image-33.png)

### 7.4.2. Inherit mission data from contractor & address list

This feature accelerates mission creation by automatically inheriting custom field data, minimizing manual input.

To enable custom field inheritance from the contractor and address list, follow the steps below:

Open the Nomadia Delivery application and go to the Configuration tab.

![Screenshot](./screenshots/image-34.png)

Select ‘Custom fields’ from the list.

![Screenshot](./screenshots/image-35.png)

Select the ‘Missions’ tab.

![Screenshot](./screenshots/image-36.png)

Click the ‘Pencil’ icon to edit an existing custom field.

![Screenshot](./screenshots/image-37.png)

From the ‘Can be initialized by’ drop-down, choose whether the field should be inherited from the contractor or the address list. Note that a custom field can be initialized from both sources at the same time. In such cases, the address list value takes priority over the contractor value.

![Screenshot](./screenshots/image-38.png)

Click the ‘Save’ button to apply the changes.

![Screenshot](./screenshots/image-39.png)

From the main header, click the ‘Contractors’ page

![Screenshot](./screenshots/image-40.png)

Click the ‘Pencil’ icon to edit the contractor.

![Screenshot](./screenshots/image-41.png)

In the Custom Fields section, all fields inherited by missions from the contractor are listed under “Custom Fields for Missions.”

![Screenshot](./screenshots/image-42.png)

Click the ‘Address List’ tab.

![Screenshot](./screenshots/image-43.png)

Click the ‘Pencil’ icon to edit an address.

![Screenshot](./screenshots/image-44.png)

In the Other Data section, all fields inherited by missions from the address are listed under “Custom Fields for Missions.”

![Screenshot](./screenshots/image-45.png)

Select a value for the custom field in the contractor or address list, then click ‘Save’ to apply the changes.

![Screenshot](./screenshots/image-46.png)

When creating a mission, the mission custom fields are automatically populated based on the selected contractor or address from the address list.

![Screenshot](./screenshots/image-47.png)

![Screenshot](./screenshots/image-48.png)

By automatically initializing fields, users don’t need to re-enter the same data during mission creation, improving consistency and efficiency.

### 7.4.3. Configuring Mission Visibility

### 7.4.3.1. Mission visibility based on a custom field

Mission visibility was previously determined mainly by the user’s agency association. To provide greater flexibility and support diverse business needs, visibility restrictions are now extended to include custom field–based rules, in addition to the existing agency-based controls.

To set up a custom field as a mission visibility restriction, follow the steps below.

Open the Nomadia Delivery application and navigate to the Configuration tab.

![Screenshot](./screenshots/image-49.png)

From the list, select Custom fields.

![Screenshot](./screenshots/image-50.png)

Click the Missions tab.

![Screenshot](./screenshots/image-51.png)

Click the Pencil icon to edit any existing custom field.

Only one custom field can be used to control mission visibility.

![Screenshot](./screenshots/image-52.png)

A toggle option is available to enable mission visibility for each mission custom field; however, it can be activated for only one field at a time.

Note: The toggle is available only for custom fields of the List of Values type.

![Screenshot](./screenshots/image-53.png)

After enabling the toggle, click Save to apply the changes.

![Screenshot](./screenshots/image-54.png)

### 7.4.3.2. Mission visibility based on a custom field for users

Select the Manage user’s menu.

![Screenshot](./screenshots/image-55.png)

Click the Pencil icon to edit the required user.

![Screenshot](./screenshots/image-56.png)

Open the Roles & rights tab.

![Screenshot](./screenshots/image-57.png)

Under the Mission section, a new Mission Visibility drop-down is available, allowing you to select the value associated with the selected user.

![Screenshot](./screenshots/image-58.png)

Select the required custom field value and click Save.

![Screenshot](./screenshots/image-59.png)

Log in as the configured user and navigate to the Missions tab.

![Screenshot](./screenshots/image-60.png)

Click the Prefilter option.

The prefilter is automatically applied based on the mission visibility custom field and the value configured in the user’s Roles & Rights.

![Screenshot](./screenshots/image-61.png)

This mission visibility prefilter is set to read-only and cannot be modified by the user. To remove or modify this restriction, contact the administrator.

The mission table will display only the missions that match the mission visibility condition, in addition to the existing agency-based prefilter.

![Screenshot](./screenshots/image-62.png)

## 7.5. Coloring and Filter

1. Use the ‘Coloring’ and ‘Filter’ options to organize and display data according to specific

conditions.

![Screenshot](./screenshots/image-63.png)

![Screenshot](./screenshots/image-64.png)

In the ‘Coloring’ popup, apply conditions based on your preference

![Screenshot](./screenshots/image-65.png)

3. The list then displays the addresses with custom colors based on the conditions you set

![Screenshot](./screenshots/image-66.png)

## 7.6. Contractor Restrictions

Contractor Restrictions allow you to precisely control access to templates and mission editing permissions.

To restrict contractors to specific documents and mission configuration templates, follow the steps below.

Open the Nomadia Delivery application and go to the Configuration tab.

![Screenshot](./screenshots/image-67.png)

Click the Contractors page from the main header.

![Screenshot](./screenshots/image-68.png)

Click the Pencil icon to edit the contractor details.

![Screenshot](./screenshots/image-69.png)

In the Missions section, multiple restrictions can be applied to contractors.

![Screenshot](./screenshots/image-70.png)

The Mission Extract Template drop-down allows users to select only the mission extracted templates applicable to the contractor.

The Sticker Template drop-down allows users to select only the sticker templates applicable to the contractor.

The Bulk Edit drop-down allows users to select only the edit configurations applicable to the contractor.

After making the selections, click Save to apply the restrictions to the selected contractor.

![Screenshot](./screenshots/image-71.png)

To prevent contractors from editing missions after printing, follow the steps below.

Open the Nomadia Delivery application and go to the Configuration tab.

![Screenshot](./screenshots/image-72.png)

Select Manage Users from the list.

![Screenshot](./screenshots/image-73.png)

Click the Pencil icon to edit a contractor user.

![Screenshot](./screenshots/image-74.png)

Click the Roles & Rights tab.

Under the Missions section, disable the Modify Mission After Printing right.

![Screenshot](./screenshots/image-75.png)

Click Save to apply the changes

![Screenshot](./screenshots/image-76.png)

Go to the Missions tab and select any Waiting mission.

![Screenshot](./screenshots/image-77.png)

Click the Actions menu and select Generate Sticker Labels.

![Screenshot](./screenshots/image-78.png)

Click the Print button to generate the sticker

![Screenshot](./screenshots/image-79.png)

After printing, click the Pencil icon to edit the mission.

![Screenshot](./screenshots/image-80.png)

A warning appears in the mission editor, and mission editing is blocked because the user does not have permission to modify it after sticker printing.

![Screenshot](./screenshots/image-81.png)

This ensures better traceability and protects mission data once documents are generated.