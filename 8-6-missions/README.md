# 6. Missions

## 6.1. Understanding the Missions Page

A Mission refers to a task that must be executed, typically involving a pick-up location and delivery address. Each mission moves through a sequence of statuses that reflect its current stage. Understanding these statuses is essential for monitoring the progress and handling any exceptions that may occur during the process.

![Screenshot](./screenshots/image-1.png)

### 

### 

### 

### 

### 

### 6.1.1. Set missions display (prefilter)

From the Missions page:

Click the "Prefiltered On" button at the top left, The display of this section may vary based on

screen resolution.

Choose Your Filters

Agency: Select one or more agencies.

Reference: Filter by Creation date or Modification date.

Period: Choose from options like the last hour, last 24 hours, last 7 days, or set a

custom date range.

Display Deleted Missions: Turn on if you want to include deleted missions.

Click on Apply

![Screenshot](./screenshots/image-2.png)

The filtered missions will be displayed on your Missions page.

![Screenshot](./screenshots/image-3.png)

### 6.1.2. Pre-filters

The Pre-filters on the Missions Page are dynamic sections that provide users with detailed and contextual information based on their current selection or interaction. These pre-filters enhance navigation and productivity by allowing quick access to relevant data without switching screens.

`

![Screenshot](./screenshots/image-4.png)

### 6.1.3. Default Delivery statuses

Below are an overview of the various mission statuses and their significance:

![Screenshot](./screenshots/image-5.png)

## 

## 6.2. Understanding the mission parameters

Mission Parameters are the core data elements that define the characteristics, objectives, and execution details of each mission. Understanding these parameters is essential for ensuring that missions are properly configured, assigned, and executed in the field.

These parameters provide both operational and logistical information used by

coordinators, dispatchers, and deliverers.

### 6.2.1. Access Mission Parameters

From the Mission page

Click the pencil icon next to the mission you want to edit

![Screenshot](./screenshots/image-6.png)

### 6.2.2. Mission parameters description

## 6.3. Manage Mission Parameters

The Manage Mission Parameters section allows administrators to define and configure key parameters that govern how delivery missions are planned, executed, and optimized within the system. These parameters play a crucial role in tailoring the delivery operations to match business needs and logistical constraints.

## 6.3.1. Manage Postal Zones

The Manage Postal Zones feature allows administrators and logistics managers to define and manage geographical delivery zones based on postal codes. These zones are

essential for organizing deliveries, assigning resources, and optimizing routes within specific areas

### 

### 6.3.1.1. Import Postal Zones

### 

Click on Configuration Tab

![Screenshot](./screenshots/image-7.png)

Click on Configuration Menu

Under My data section, click on Manage Zones

![Screenshot](./screenshots/image-8.png)

Click the Actions dropdown menu.

Click on Import

![Screenshot](./screenshots/image-9.png)

Click on Browse File to upload the file that contains the zone data.

![Screenshot](./screenshots/image-10.png)

Select a valid Zone file from your local system.

![Screenshot](./screenshots/image-11.png)

Postal Zones will be imported successfully.

![Screenshot](./screenshots/image-12.png)

### 6.3.1.2. Add a Postal Zone

Click on Configuration Tab

Click on Configuration Menu

Under My data section, click on Manage Zones

Click the Actions dropdown menu.

Click on Add a Postal Zone.

![Screenshot](./screenshots/image-13.png)

Fill in the required fields: Code, Name, and Prefix.

Note: The Prefix is used to standardize postal codes to a fixed length of 6 digits. In regions where postal codes are shorter (e.g., 5 digits in some areas of France), the system automatically adds the defined prefix to reach the required length.

![Screenshot](./screenshots/image-14.png)

Click on Save

![Screenshot](./screenshots/image-15.png)

Postal Zones will be added successfully

![Screenshot](./screenshots/image-16.png)

### 6.3.1.3. Create Postal Zones by Territory Management (Sectorization)

Click on Configuration Tab

Click on Configuration Menu

Under My data section, click on Manage Zones

Select a Mission

Click the Actions dropdown menu.

Click on New Sectorization.

For detailed information, refer to the Territory Manager Manual available at the following link:

https://mynomadia.com/doc/tm/docs/en/tm-book/_districting.html

![Screenshot](./screenshots/image-17.png)

Select the appropriate Indicators and define the Time Period

Click on Assign Territories

![Screenshot](./screenshots/image-18.png)

Click on Automation

![Screenshot](./screenshots/image-19.png)

In the Balancing Points section, click Start to prepare the system for

automatic balancing.

![Screenshot](./screenshots/image-20.png)

Click “Let’s go!” to launch the automated balancing of territories.

![Screenshot](./screenshots/image-21.png)

Sectors are generated according to the balancing rules set by the user.

To ensure the sectorization respects postal code boundaries, click on Administrative Borders and select Postal Code from the dropdown menu.

![Screenshot](./screenshots/image-22.png)

Sectors are aligned based on postal boundaries

Disclaimer: Postal code boundary data is unavailable for certain countries.

### 6.3.1.4. Delete a Postal Zone

Click on Configuration Tab

Click on Configuration Menu

Under My data section, click on Manage Zones

Select a Zone

![Screenshot](./screenshots/image-23.png)

Click the Actions dropdown menu.

Click on Delete

![Screenshot](./screenshots/image-24.png)

You will see a confirmation pop-up message stating: "Are you sure you want to

delete this zone?"

Click on Yes

![Screenshot](./screenshots/image-25.png)

Postal Zone will be deleted successfully

![Screenshot](./screenshots/image-26.png)

### 6.3.1.5. Export a Postal Zone

Click on Configuration Tab

Click on Configuration Menu

Under My data section, click on Manage Zones

Select a Zone

Click the Actions dropdown menu.

Click on Export

![Screenshot](./screenshots/image-27.png)

Postal Zone will be exported successfully

![Screenshot](./screenshots/image-28.png)

### 6.3.1.6. Color a Postal Zone

Apply conditions based on zone attributes such as type of mission (Delivery, Pickup), Zone priority, Assigned deliverer, Postal code prefix, etc.

Click on Configuration Tab

Click on Configuration Menu

Under My data section, click on Manage Zones

Select a Zone

Click the Actions dropdown menu.

Click on Coloring

![Screenshot](./screenshots/image-29.png)

Choose a Color

Click on Save

![Screenshot](./screenshots/image-30.png)

The selected color has been applied successfully.

![Screenshot](./screenshots/image-31.png)

### 6.3.1.7. Customize Zones Table

Refer to 4.3.1.1. Import a Postal Zones to have the complete list of available fields.

Click on Configuration Tab

Click on Configuration Menu

Under My data section, click on Manage Zones

Select a Zone

Click the Actions dropdown menu.

Click on Customize Limit

![Screenshot](./screenshots/image-32.png)

Choose which fields you want to display on the table.

Note: Avoid selecting too many fields at once, as it may become difficult to read or

navigate.

Click on Save

![Screenshot](./screenshots/image-33.png)

The selected fields have been displayed on the table.

![Screenshot](./screenshots/image-34.png)

### 6.3.2. Manage Vehicle Fleets

The Manage Vehicle Fleets in Nomadia Delivery allows administrators and planners to maintain an up-to-date registry of the vehicles used for delivery operations. This includes adding, editing, or deactivating vehicles, assigning specific characteristics, and ensuring that each vehicle is properly configured to meet logistical needs.

### 6.3.2.1. Import Vehicles fleets

Go to Configuration.

![Screenshot](./screenshots/image-35.png)

Click on Configuration menu

Under My Data, click on Manage the Vehicles.

![Screenshot](./screenshots/image-36.png)

Under My Fleets, click the Actions dropdown menu.

Click on Import

![Screenshot](./screenshots/image-37.png)

Click on Browse File to upload the file

![Screenshot](./screenshots/image-38.png)

Select a Valid file from your local system.

![Screenshot](./screenshots/image-39.png)

The vehicle fleets have been imported successfully.

![Screenshot](./screenshots/image-40.png)

### 6.3.2.2. Add a Vehicles fleets

Go to Configuration.

Click on Configuration Menu

Under My Data, click on Manage the Vehicles.

Under My Fleets, click the Actions dropdown menu.

Click on Add

![Screenshot](./screenshots/image-41.png)

Enter the Name and Agency name

Click on Add

![Screenshot](./screenshots/image-42.png)

The vehicle fleets have been added successfully.

![Screenshot](./screenshots/image-43.png)

### 

### 

### 

### 6.3.2.3. Delete a Vehicles fleets

Go to Configuration.

Click on Configuration Menu

Under My Data, click on Manage the Vehicles.

Select a Team

Under My Fleets, click the Actions dropdown menu.

Click on Delete

![Screenshot](./screenshots/image-44.png)

You will see a confirmation pop-up message stating: "Do you want to delete the Vehicle?"

Click on Delete

![Screenshot](./screenshots/image-45.png)

The Vehicle fleets have been deleted successfully.

![Screenshot](./screenshots/image-46.png)

### 

### 6.3.2.4. Manage Vehicles in a fleet

### 6.3.2.4.1. Add a Vehicle

Go to Configuration.

Click on Configuration Menu

Under My Data, click on Manage the Vehicles.

Click the Desired Name

Click on Actions

Click on Add from the dropdown menu

![Screenshot](./screenshots/image-47.png)

Enter the Name

![Screenshot](./screenshots/image-48.png)

Click on Add

![Screenshot](./screenshots/image-49.png)

### 

### 6.3.2.5. Customize the constraints

Go to Configuration.

Click on Configuration Menu

Under My Data, click on Manage the Vehicles.

Click on the Desired name

Click on Actions

Click on Add

Click on Constraints

![Screenshot](./screenshots/image-50.png)

Choose which fields you want to display on the table.

Note: Avoid selecting too many fields at once, as it may become difficult to read or navigate.

Click on Save

![Screenshot](./screenshots/image-51.png)

The Fields have been displayed successfully.

![Screenshot](./screenshots/image-52.png)

### 

### 6.3.2.5.1. Delete a Vehicle

Go to Configuration.

Click on Configuration Menu

Under My Data, click on Manage the Vehicles.

Click the Desired Name

Click on Actions

Click on Delete from the dropdown menu

![Screenshot](./screenshots/image-53.png)

You will see a confirmation pop-up message stating: "Do you want to delete the Vehicle?"

Click on Delete.

![Screenshot](./screenshots/image-54.png)

Vehicles have been deleted successfully

![Screenshot](./screenshots/image-55.png)

### 

### 

### 

### 6.3.2.5.2. Export a Vehicle

Go to Configuration.

Click on Configuration Menu

Under My Data, click on Manage the Vehicles.

Click the Desired Name

Click on Actions

Click on Export from the dropdown menu

![Screenshot](./screenshots/image-56.png)

The vehicles have been exported successfully.

![Screenshot](./screenshots/image-57.png)

### 6.3.2.5.3. Color a Vehicle

Go to Configuration.

Click on Configuration Menu

Under My Data, click on Manage the Vehicles.

Click the Desired Name

Click on Actions

Click on Coloring from the dropdown menu

![Screenshot](./screenshots/image-58.png)

Choose a Color

Click on Save

![Screenshot](./screenshots/image-59.png)

The color has been applied successfully.

![Screenshot](./screenshots/image-60.png)

### 

### 

### 

### 6.3.2.5.4. Customize Vehicles table

Go to Configuration.

Click on Configuration Menu

Under My Data, click on Manage the Vehicles.

Click the Desired Name

Click on Actions

Click on Customize the list from the dropdown menu

![Screenshot](./screenshots/image-61.png)

Choose which fields you want to display on the table.

Note: Avoid selecting too many fields at once, as it may become difficult to read or

navigate.

Click on Save

![Screenshot](./screenshots/image-62.png)

19. The selected fields will be displayed on the table successfully

![Screenshot](./screenshots/image-63.png)

### 

### 

### 

### 

### 6.3.2.6. Export a Vehicles fleets

Go to Configuration.

Click on Configuration Menu

Under My Data, click on Manage the Vehicles.

Select a Team

Under My Fleets, click the Actions dropdown menu.

Click on Export

![Screenshot](./screenshots/image-64.png)

7. The vehicles fleets will be exported successfully.

![Screenshot](./screenshots/image-65.png)

### 6.3.2.7. Color a Vehicles fleets

Apply conditions based on zone attributes such as type of mission (Delivery, Pickup),

Zone priority, Assigned deliverer, Postal code prefix, etc.

Go to Configuration.

Click on Configuration Menu

Under My Data, click on Manage the Vehicles.

Select a Team

Under My Fleets, click the Actions dropdown menu.

Click on Coloring

![Screenshot](./screenshots/image-66.png)

Choose a Color

Click on Save

![Screenshot](./screenshots/image-67.png)

The selected color has been applied successfully

![Screenshot](./screenshots/image-68.png)

### 6.3.2.8. Customize Vehicles fleets table

Go to Configuration.

Click on Configuration Menu

Under My Data, click on Manage the Vehicles.

Select a Team

Under My Fleets, click the Actions dropdown menu.

Click on Customize the list

![Screenshot](./screenshots/image-69.png)

Choose which fields you want to display on the table.

Note: Avoid selecting too many fields at once, as it may become difficult to read or navigate.

Click on Save

![Screenshot](./screenshots/image-70.png)

The selected fields have been displayed on the table successfully

![Screenshot](./screenshots/image-71.png)

### 

### 6.3.2.9. Customizing Status Labels.

Previously, statuses in Nomadia Delivery were static and could not be customized to adapt to customer workflows. Customizable status labels now enhance mission tracking by giving users full control to configure status labels and colors to align with their business workflows.

Status Labels – Description

Waiting - Initial status. The Parcel is expected to arrive at the agency.

Received - Optional Status: Indicates the parcel has been received by the deliverer. The exact location depends on context.

Not received - Optional Status: Indicates the parcel was expected but not received by the deliverer. Location is dependent on context.

To be delivered - Parcel is scheduled for delivery by the transporter or subcontractor.

To be loaded - Optional Status: Parcel is ready at the docking area, awaiting loading onto the vehicle.

Loaded - Optional Status: Parcel has been successfully loaded onto the truck by the deliverer.

Not loaded - Optional Status: Parcel was expected but not loaded onto the truck

Not delivered - Delivery attempt failed; parcel was not handed over to the customer.

Delivered - Parcel has been delivered to the final recipient.

To be picked up - Parcel is scheduled for pickup by the transporter or subcontractor.

Picked up - Parcel has been collected from the contractor or end-customer.

Not Picked up - Pickup attempt failed; parcel was not collected.

To be Visited - Visit is scheduled by the transporter or subcontractor.

Visited - Visit was completed by the deliverer.

Not Visited - Visit was scheduled but not completed.

To customize status labels in Nomadia Delivery, follow the steps below.

Open the Nomadia Delivery application and navigate to the Configuration tab.

![Screenshot](./screenshots/image-72.png)

Select Customize Status Labels from the list.

![Screenshot](./screenshots/image-73.png)

This page displays all statuses in Nomadia Delivery.

![Screenshot](./screenshots/image-74.png)

Click the text box next to the status and update the label to match your business workflow.

![Screenshot](./screenshots/image-75.png)

Click the Other Languages accordion to update labels for users in different languages or countries.

![Screenshot](./screenshots/image-76.png)

Click the Color Picker to change the background color of a status label. Ensure you choose a contrasting color that maintains text readability in the UI.

![Screenshot](./screenshots/image-77.png)

After making the changes, click Save to apply the label and color updates across both the web and mobile applications.

![Screenshot](./screenshots/image-78.png)

After saving the changes, return to the mission page to view the updated labels and colors in the pre-filter area

![Screenshot](./screenshots/image-79.png)

This provides a smooth, business-aligned experience for both planners and deliverers.

### 

### 

### 

### 6.3.3. Manage Sub Statuses

The Manage Sub Statuses feature allows administrators to create, edit, and assign detailed status labels that reflect the real-time progress or condition of a delivery task. These sub statuses provide a more granular tracking mechanism within the broader status categories such as "Pickup", "Waiting", or "Delivered"

### 6.3.3.1. Create a Sub status

Go to Configuration.

Click on Configuration Menu

Under My Data, click on Sub statuses.

![Screenshot](./screenshots/image-80.png)

Click the Actions dropdown menu

Click on Add

![Screenshot](./screenshots/image-81.png)

Enter the Sub status code

Select the Status configuration type

![Screenshot](./screenshots/image-82.png)

Click on Save

![Screenshot](./screenshots/image-83.png)

Sub status has been created successfully

![Screenshot](./screenshots/image-84.png)

### 

### 6.3.3.2. Delete a Sub status

Go to Configuration.

Click on Configuration Menu

Under My Data, click on Sub statuses.

Select a Sub statuses

Click the Actions dropdown menu

Click on Delete

![Screenshot](./screenshots/image-85.png)

You will see a confirmation pop-up message stating: "Do you want to delete the sub-status?"

Click on Yes

![Screenshot](./screenshots/image-86.png)

Sub status has been deleted successfully

![Screenshot](./screenshots/image-87.png)

### 

### 6.3.3.3. Coloring a Sub status

Apply conditions based on zone attributes such as type of mission (Delivery, Pickup), Zone priority, Assigned deliverer, Postal code prefix, etc.

Go to Configuration.

Click on Configuration Menu

Under My Data, click on Sub statuses.

Select a Sub statuses

Click the Actions dropdown menu

Click on Coloring

![Screenshot](./screenshots/image-88.png)

Choose a Color

Click on Save

![Screenshot](./screenshots/image-89.png)

The selected color has been applied successfully.

![Screenshot](./screenshots/image-90.png)

### 

### 6.3.3.4. Customize Sub statuses table

Go to Configuration.

Click on Configuration Menu

Under My Data, click on Sub statuses.

Select a Sub statuses

Click the Actions dropdown menu

Click on Customize the Limit

![Screenshot](./screenshots/image-91.png)

Choose which fields you want to display on the table.

Note: Avoid selecting too many fields at once, as it may become difficult to read or navigate.

Click on Save

![Screenshot](./screenshots/image-92.png)

The selected fields have been displayed on the table successfully

![Screenshot](./screenshots/image-93.png)

### 

### 6.3.3.5. MANAGING SUB-STATUS CONFIGURATION TYPES

Nomadia Delivery provides three types of sub-status templates that enable users to personalize the delivery workflow according to the customer type or category. These templates are Basic, Intermediate, and Advanced.

Basic Configuration types: Designed for customers who require only a single verification step,

such as capturing a photo or collecting a signature. It simplifies the delivery process by including

only the essential checks.

Intermediate Configuration types: Suitable for customers who need multiple verification steps but do not require the full range of options available on the advanced template.

Advanced Configuration types: Intended for customers who demand comprehensive verification, such as taking photos at every stage of the delivery. It provides maximum flexibility to configure detailed workflows.

Note: The Configuration types options are provided solely to help differentiate delivery workflows based on customer categories. However, the complexity of the workflow is entirely at the user’s discretion. For example, a Basic template can still be configured to support a complex delivery process if needed.

To configure and manage sub-status configuration types in Nomadia Delivery, follow these steps:

Open the Nomadia Delivery application and go to the Configuration module.

![Screenshot](./screenshots/image-94.png)

Click on the Actions button, then choose Add to create a new sub-status.

![Screenshot](./screenshots/image-95.png)

Assign the created sub-status to one or more templates.

![Screenshot](./screenshots/image-96.png)

Define the required actions for each sub-status, such as making signature mandatory, requiring a

photo, etc.

![Screenshot](./screenshots/image-97.png)

Repeat the process to create additional sub-statuses and link them to the desired templates.

![Screenshot](./screenshots/image-98.png)

Once all templates are configured, navigate to the Missions tab.

Click on the Mission Editor button to attach a sub-status template to a mission.

![Screenshot](./screenshots/image-99.png)

Select the appropriate sub-status configuration template for the chosen mission

![Screenshot](./screenshots/image-100.png)

Alternatively, configure templates in bulk during mission import by mapping the Excel field to the

Status configuration type with values like BASIC, INTERMEDIATE, or ADVANCED.

![Screenshot](./screenshots/image-101.png)

### 6.3.3.6. Trigger Notifications for Sub Status Changes

The Trigger Notifications for Sub-Status Changes feature enables accurate, real-time communication with all stakeholders involved in parcel movement. It improves transparency, coordination, and overall service quality across first-mile, mid-mile, and last-mile operations.

To configure notifications for sub-status changes, follow the steps below:

Open the Nomadia Delivery application and go to the Configuration tab.

![Screenshot](./screenshots/image-102.png)

Select Sub-statuses from the list.

![Screenshot](./screenshots/image-103.png)

Click the Pencil icon next to the existing sub-status to edit it.

![Screenshot](./screenshots/image-104.png)

The Custom Messages Configuration section is displayed at the bottom of the page.

![Screenshot](./screenshots/image-105.png)

Click the + button to add the notification configuration to the sub status.

![Screenshot](./screenshots/image-106.png)

Notifications can be made for the following recipients:

Sender – The original sender of the mission. Notifications are sent to the contractor’s email address or mobile number stored in the mission details.

Consignee – The original recipient of the mission (customer). Notifications are sent to the delivery email address or mobile number stored in the mission details.

Other Recipients – Any internal stakeholders who need to be informed about the mission’s transit, such as the dispatch or logistics teams. This field accepts multiple email addresses or phone numbers, separated by commas.

![Screenshot](./screenshots/image-107.png)

Notifications can be sent via Email or SMS.

To create a notification configuration, select a recipient, message type, and message template. Please note that only custom message templates are supported for this case.

![Screenshot](./screenshots/image-108.png)

The Other Recipients field allows you to enter multiple email addresses or phone numbers, separated by commas.

Please note that the Other Recipients field is enabled only when Other Recipients is selected in the Recipient column.

![Screenshot](./screenshots/image-109.png)

After completing the configuration, click Save to apply and store the changes.

![Screenshot](./screenshots/image-110.png)

When the mobile user triggers a sub-status, all configured recipients automatically receive the update via Email or SMS at the same time, providing real-time information on the mission’s movement.

![Screenshot](./screenshots/image-111.png)

### 

### 

### 

### 6.3.4. Manage Articles

The Manage Articles feature in Nomadia Delivery allows users to maintain and organize a centralized catalog of products (articles) that are part of the delivery workflow. This feature supports the complete lifecycle of articles — including creation, editing, activation/deactivation, and deletion — enabling seamless tracking and accurate planning of deliveries.

### 6.3.4.1. Manage Article types

The Manage Article Types feature allows administrators to define and categorize the various kinds of articles handled within the delivery process. This classification ensures better organization, filtering, and reporting of items during route planning, loading, and delivery execution.

### 6.3.4.1.1. Import Article types.

Go to Configuration.

Click on Configuration Menu

Under Customization, click on Types of Articles.

![Screenshot](./screenshots/image-112.png)

Click the Actions dropdown menu

Click on Import

![Screenshot](./screenshots/image-113.png)

Click on Browse File to upload the file that contains the zone data.

![Screenshot](./screenshots/image-114.png)

Select a valid file from your local system.

![Screenshot](./screenshots/image-115.png)

The articles have been imported successfully.

![Screenshot](./screenshots/image-116.png)

### 6.3.4.1.2. Create an Article type

Go to Configuration.

Click on Configuration Menu

Under Customization, click on Types of Articles.

Click the Actions dropdown menu

Click on Add

![Screenshot](./screenshots/image-117.png)

Enter the Name and Translation

![Screenshot](./screenshots/image-118.png)

Click on Save

![Screenshot](./screenshots/image-119.png)

The article type has been created successfully

![Screenshot](./screenshots/image-120.png)

### 6.3.4.1.3. Edit an Article type

Go to Configuration.

Click on Configuration Menu

Under Customization, click on Types of Articles.

Select an Article

Click the Pencil icon

![Screenshot](./screenshots/image-121.png)

Edit the information as needed

![Screenshot](./screenshots/image-122.png)

Click on Save

![Screenshot](./screenshots/image-123.png)

### 

### 

### 

### 6.3.4.1.4. Export Article types

Go to Configuration.

Click on Configuration Menu

Under Customization, click on Types of Articles.

Select an Article

Click the Actions dropdown menu

Click on Export

![Screenshot](./screenshots/image-124.png)

The article types have been exported successfully

![Screenshot](./screenshots/image-125.png)

### 6.3.4.1.5. Delete an article type

Go to Configuration.

Click on Configuration Menu

Under Customization, click on Types of Articles.

Select an Article

Click the Actions dropdown menu

Click on Delete

![Screenshot](./screenshots/image-126.png)

You will see a confirmation pop-up message stating: "Do you want to delete the article?"

Click on Delete

![Screenshot](./screenshots/image-127.png)

The article types have been deleted successfully

![Screenshot](./screenshots/image-128.png)

### 

### 

### 

### 6.3.4.2. Add Articles to a Mission

From the Mission page

Click on Actions

Select Add from the dropdown menu.

![Screenshot](./screenshots/image-129.png)

Click on Articles

Click on Add Articles

![Screenshot](./screenshots/image-130.png)

Enter the required information, including the Article name and Planned quantity

![Screenshot](./screenshots/image-131.png)

Click on Add

![Screenshot](./screenshots/image-132.png)

The Articles will be added successfully.

![Screenshot](./screenshots/image-133.png)

### 6.3.4.3. Edit a Mission Article

From the Mission page

Click the pencil icon of the chosen mission

![Screenshot](./screenshots/image-134.png)

In the left-hand menu, click the Articles tab

![Screenshot](./screenshots/image-135.png)

Edit the Article

![Screenshot](./screenshots/image-136.png)

Update the necessary details such as Planned, Done, and Returned quantities

Click on Save

![Screenshot](./screenshots/image-137.png)

### 6.3.4.4. Delete a Mission Article

From the Mission page

Click the pencil icon next to the desired mission

In the left-hand menu, select the Articles tab

Click on the Bin icon of the Article to delete

![Screenshot](./screenshots/image-138.png)

Mission articles will be deleted successfully.

![Screenshot](./screenshots/image-139.png)

### 6.3.5. Manage Documents

The "Manage Documents" feature allows users to upload, view, organize, and associate various documents with delivery operations to streamline communication and ensure all necessary information is easily accessible in the field and at the back office.

### 6.3.5.1. Manage Templates for Mission documents

The Manage Document Templates feature allows administrators and back-office users to create, configure, and maintain reusable templates for documents such as delivery slips, invoices, proof of delivery, and task reports. These templates standardize documentation across operations and ensure consistency in branding, structure, and required information.

You can design your own templates to replace the default one.

### 6.3.5.1.1. Download a Document Template

Go to Configuration.

Click on Configuration Menu

Under Customization, click on Document Templates

Select the Desired document from the list

![Screenshot](./screenshots/image-140.png)

Click the Actions dropdown menu

Click on Download

![Screenshot](./screenshots/image-141.png)

The document templates will be downloaded successfully.

![Screenshot](./screenshots/image-142.png)

### 

### 

### 

### 6.3.5.1.2. Edit a Document Template

Go to Configuration.

Click on Configuration Menu

Under Customization, click on Document Templates

Select the Desired document from the list

Click the Actions dropdown menu

Click on Edit

![Screenshot](./screenshots/image-143.png)

Edit the information as needed

![Screenshot](./screenshots/image-144.png)

Click on Save

![Screenshot](./screenshots/image-145.png)

### 

### 

### 

### 

### 6.3.5.1.3. Import a Document Template

Go to Configuration.

![Screenshot](./screenshots/image-146.png)

Click on Configuration Menu

Under Customization, click on Document Templates

![Screenshot](./screenshots/image-147.png)

Click the Actions dropdown menu

Click on Import

![Screenshot](./screenshots/image-148.png)

Click on Browse Computer to upload the file.

![Screenshot](./screenshots/image-149.png)

Select a Valid file from a local system

![Screenshot](./screenshots/image-150.png)

The document templates will be imported successfully.

![Screenshot](./screenshots/image-151.png)

### 

### 6.3.5.1.4. Enable/Disable a Document Template

Go to Configuration.

Click on Configuration Menu

Under Customization, click on Document Templates

Select the Desired document from the list

Click the Actions dropdown menu

Click on Enable/Disable

![Screenshot](./screenshots/image-152.png)

7. The document templates will be enabled / disabled successfully.

### 6.3.5.1.5. Delete a document Template

Go to Configuration.

Click on Configuration Menu

Under Customization, click on Document Templates

Select the Desired document from the list

Click the Actions dropdown menu

Click on Delete

![Screenshot](./screenshots/image-153.png)

7. The document templates will be deleted successfully.

![Screenshot](./screenshots/image-154.png)

### 

### 

### 

### 

### 6.3.5.1.6. Show/Hide default templates

Go to Configuration.

Click on Configuration Menu

Under Customization, click on Document Templates

Select the Desired document from the list

Click the Actions dropdown menu

Click on Show/Hide Default Template

![Screenshot](./screenshots/image-155.png)

### 6.3.5.2. Manage Document Library

The Manage Document Library feature provides a centralized repository to store, organize, and distribute commonly used documents across the delivery organization. It ensures quick access to reference materials such as safety instructions, compliance guidelines, operating procedures, and training manuals for both back-office staff and field agents.

Ensure your file is in one of these supported formats before proceeding: XLSX, DOCX, PDF, JPG, or PNG

Go to Configuration.

Click on Configuration Menu

Under My data, click on Document Library

![Screenshot](./screenshots/image-156.png)

Click on Browse Computer to upload the file

![Screenshot](./screenshots/image-157.png)

Select a Valid file from a local system.

![Screenshot](./screenshots/image-158.png)

6. The documents will be imported successfully.

![Screenshot](./screenshots/image-159.png)

### 6.3.5.3. Document recommendations

The Document Recommendations feature ensures that all required paperwork is available for each international shipment. It helps maintain compliance, prevents missing documents, and improves overall process reliability.

### 6.3.5.3.1. Recommendations While Adding the Document

Open the Nomadia Delivery application and navigate to the Missions tab

![Screenshot](./screenshots/image-160.png)

Click Actions and select Add (Beta).

![Screenshot](./screenshots/image-161.png)

Enter the Agency name.

![Screenshot](./screenshots/image-162.png)

Click the Pencil icon in the top-right corner.

![Screenshot](./screenshots/image-163.png)

Enable the Add documents toggle and click Save.

![Screenshot](./screenshots/image-164.png)

Enter the delivery address.

![Screenshot](./screenshots/image-165.png)

Click Add.

![Screenshot](./screenshots/image-166.png)

Once the delivery address is added, the Document Recommendation list is automatically displayed based on the consignee’s country (delivery country). This helps users identify the mandatory documents that must be uploaded to meet legal requirements when transporting missions across countries.

![Screenshot](./screenshots/image-167.png)

### 6.3.5.3.2. Recommendations While Editing the Document

To set up recommendations for Nomadia Delivery, follow the steps below.

Open the Nomadia Delivery application and go to the Configuration tab.

![Screenshot](./screenshots/image-168.png)

Select Document Library from the list.

![Screenshot](./screenshots/image-169.png)

Select the Document Recommendations tab.

![Screenshot](./screenshots/image-170.png)

Click the Actions menu, then select Add to create a new document recommendation.

Alternatively, users can import the document recommendation list using an Excel file from the same Actions menu.

![Screenshot](./screenshots/image-171.png)

Enter the Name of the recommendation list, the applicable Country, and the message to be displayed.

![Screenshot](./screenshots/image-172.png)

A recommendation list can be applied to multiple countries simultaneously.

Alternatively, a country can have both a general recommendation list and a country-specific recommendation list. In such cases, both lists are merged and displayed as the recommended document list during the mission creation or editing process.

Links can be added to the recommendation list, allowing users to directly access online or cloud-hosted documents, such as SharePoint documents.

Enable the toggle to activate the recommendation list.

![Screenshot](./screenshots/image-173.png)

Click Add to create the document recommendation list.

![Screenshot](./screenshots/image-174.png)

The document recommendation lists are displayed on the table.

![Screenshot](./screenshots/image-175.png)

When creating or editing a mission, the document recommendation list is displayed based on the consignee’s country (delivery country). This helps users identify the documents that must be uploaded to comply with legal requirements when transporting missions from one country to another.

![Screenshot](./screenshots/image-176.png)

If a country has multiple recommendation lists, they are seamlessly merged and displayed with a separator.

![Screenshot](./screenshots/image-177.png)

### 

### 6.3.6. Manage Container Types

The Manage Container Types feature enables logistics managers and dispatchers to define, configure, and manage the various types of containers or packaging units used in delivery operations. This helps optimize space planning, improve tracking, and ensure accurate handling of goods during transport.

The system supports three default container types: Cardboard, Pallet, and Parcel.

You can group multiple containers together and track the quantity of each container type at client locations for better inventory and logistics management.

### 6.3.6.1. Create a Container type

Go to Configuration.

![Screenshot](./screenshots/image-178.png)

Click on Configuration Menu

Under Customization, click on Container Types

![Screenshot](./screenshots/image-179.png)

Click the Actions dropdown menu

Click on Add

![Screenshot](./screenshots/image-180.png)

Enter the Code and Translation

![Screenshot](./screenshots/image-181.png)

Click on Save

![Screenshot](./screenshots/image-182.png)

Container type will be created successfully.

![Screenshot](./screenshots/image-183.png)

### 6.3.6.2. Edit a Container Type

Go to Configuration.

Click on Configuration Menu

Under Customization, click on Container Types

Click the Pencil icon of the chosen container type

![Screenshot](./screenshots/image-184.png)

Edit the information as needed

Click on Save

![Screenshot](./screenshots/image-185.png)

### 6.3.6.3. Delete a Container Type

Go to Configuration.

Click on Configuration Menu

Under Customization, click on Container Types

Select the Container Types

Click on Actions

Click on Delete

![Screenshot](./screenshots/image-186.png)

7. The container type will be deleted successfully

![Screenshot](./screenshots/image-187.png)

### 6.3.7. Manage Mission’s Notifications

The Manage Mission’s Notifications enable administrators and dispatchers to configure and automate notifications related to delivery missions. These notifications ensure real-time communication with customers, field agents, and internal stakeholders, improving operational visibility and customer satisfaction.

### 6.3.7.1. Enable Email Notification

Go to Configuration.

![Screenshot](./screenshots/image-188.png)

Click on Configuration Menu

Under Fulfillment and Client Experience, click on Configure Outgoing Messages

![Screenshot](./screenshots/image-189.png)

Select the General Configuration

Under Configure Outgoing Emails to the Customers, enable the Customers Outgoing Email

Service

![Screenshot](./screenshots/image-190.png)

Click on Save

![Screenshot](./screenshots/image-191.png)

### 6.3.7.2. Enable SMS Notifications

Go to Configuration.

Click on Configuration Menu

Under Fulfillment and Client Experience, click on Configure Outgoing Messages

Select the General Configuration

Under Configure Outgoing SMS to the Customers, enable the Customers Outgoing SMS

Service

Click on Save

Note: SMS notifications are provided as an additional service.

![Screenshot](./screenshots/image-192.png)

### 6.3.8. Manage Missions Documents

The "Manage Missions" documents specifically refer to guides and documentation that help users oversee and operate delivery-related missions within the logistics and field execution workflows.

### 6.3.8.1. Import a Document from the Document Library

Go to Configuration.

Click on Configuration Menu

Click on Document Library

Click on Actions

Click on Import

Click on Browse Computer

![Screenshot](./screenshots/image-193.png)

Select a Valid file to import a document

![Screenshot](./screenshots/image-194.png)

The mission documents will be imported successfully

![Screenshot](./screenshots/image-195.png)

### 6.3.8.2. Upload a Document

Navigate to the Missions Tab.

Locate the desired mission and click the pencil icon to open it in edit mode.

![Screenshot](./screenshots/image-196.png)

In the left-hand menu, select Documents.

Click Browse Computer to open your file explorer.

![Screenshot](./screenshots/image-197.png)

Select a valid document from your local system to upload.

![Screenshot](./screenshots/image-198.png)

The mission documents will be uploaded successfully.

![Screenshot](./screenshots/image-199.png)

### 6.3.8.3. Download a Document

Navigate to the Missions section.

Locate the desired mission and click the pencil icon to open it in edit mode.

In the left-hand menu, select Documents.

Click on Download

![Screenshot](./screenshots/image-200.png)

5. The mission documents will be downloaded successfully.

![Screenshot](./screenshots/image-201.png)

### 6.3.8.4. Delete a Document

Navigate to the Missions section.

Locate the desired mission and click the pencil icon to open it in edit mode.

In the left-hand menu, select Documents.

Click on the Bin icon of the chosen document

![Screenshot](./screenshots/image-202.png)

The mission documents will be deleted successfully.

![Screenshot](./screenshots/image-203.png)

### 6.3.8.5. ACCESSING ECMR

An eCMR (Electronic Consignment Note) is the digital equivalent of the traditional paper-

based CMR used in road transport. It acts as proof of the carriage contract, acknowledgment of goods received, and a document of title.

Download the eCMR PDF directly through the delivery management system.

Log in to the delivery management system and go to the Missions tab.

![Screenshot](./screenshots/image-204.png)

Before generating the eCMR, ensure that the company name, address, and SIRET number are

configured in Configuration → General.

These details are required by law and will be displayed on the eCMR.

![Screenshot](./screenshots/image-205.png)

Select the routes for which you want to generate the eCMR.

Click Actions → Consignment notes.

![Screenshot](./screenshots/image-206.png)

Click the Download button.

![Screenshot](./screenshots/image-207.png)

The system will generate the eCMR PDF, which you can download and share with deliverers.

![Screenshot](./screenshots/image-208.png)

## 

## 

## 

## 6.4. Manage Missions

The following fields are available at the mission level, allowing you to configure various mission constraints based on your business requirements.

### 6.4.1. Mission Creation Configuration

Fields can be organized within their respective blocks/sections to structure the mission creation layout according to your requirements. While the arrangement of fields inside a block remains fixed, you can modify the overall layout by changing the order of the blocks or sections.

Blocks or sections can be reordered using drag-and-drop functionality. Any changes made through drag-and-drop are automatically synchronized with the visibility and order displayed in the left-hand side user interface.

Go to Manage Missions

![Screenshot](./screenshots/image-209.png)

Click Add Mission

![Screenshot](./screenshots/image-210.png)

Enter the Mission type, Agency

![Screenshot](./screenshots/image-211.png)

Click Next

![Screenshot](./screenshots/image-212.png)

Click the pencil icon in the top right corner.

![Screenshot](./screenshots/image-213.png)

View the available information blocks:

General Information

Pickup Information

Delivery Information

PUDO Information

Custom Fields

![Screenshot](./screenshots/image-214.png)

Configure fields within each block:

Set fields as editable, read-only, or disabled.

![Screenshot](./screenshots/image-215.png)

Use drag and drop to:

Reorder fields within a block.

Group multiple fields into a single container using the six-dot handle.

Group the duplicated parcels in one container

Selecting Yes automatically creates a mission based on the type selected below.

Selecting No prevents automatic mission creation.

Optional — The user is prompted with this option during mission creation.

![Screenshot](./screenshots/image-216.png)

Expand or collapse blocks as needed.

![Screenshot](./screenshots/image-217.png)

Save the new mission configuration.

![Screenshot](./screenshots/image-218.png)

### 6.4.2. Add a Mission

Adding Mission allows users to create a mission by selecting a mission type, choosing a configuration, and entering mandatory mission information. The system enforces validations based on the selected mission type.

Go to Missions

![Screenshot](./screenshots/image-219.png)

Click Add from the Actions menu

![Screenshot](./screenshots/image-220.png)

Select Mission Type, (Pickup information - delivery) Delivery information -pickup), Agency.

![Screenshot](./screenshots/image-221.png)

Click Next.

![Screenshot](./screenshots/image-222.png)

Select a Mission Configuration:

Default configuration, or

Any Custom configuration was created earlier.

![Screenshot](./screenshots/image-223.png)

Enter mandatory mission details based on mission type.

![Screenshot](./screenshots/image-224.png)

Click Add or Add and Print.

![Screenshot](./screenshots/image-225.png)

### 6.4.3 Add Mission Beta

The Add (Beta) interface introduces a simplified, single-page mission creation experience in Nomadia Delivery. Designed to minimize repetitive steps and improve clarity, this interface replaces the traditional multi-step wizard with a unified view that brings together all mission parameters, constraints, and dependencies in one place.

Custom Field Grouping: Custom fields can now be grouped under a defined group name. During mission creation, these fields are displayed together under their respective group, making it easier to identify sections and enter information efficiently.

Group Ordering: Custom field groups can be reordered using drag-and-drop while creating or editing a configuration. The mission creation form reflects this order, allowing users to follow a workflow that best suits their process.

Sorting Fields Within Groups: Custom fields within a group can be sorted based on Name (default) or Identifier (for custom ordering), giving users precise control over how fields are displayed within each group.

Custom Fields for Parcels: Previously limited to the mission level, custom fields can now be associated with individual parcels when duplicating missions. Custom fields used for parcels cannot be enabled at the mission level, providing greater flexibility when duplicating missions for the same customer or address.

Group Missions in a Container: When duplicating missions, users can now group them by default within a parent container.

Immediate Document Attachment: Earlier, documents could only be added after mission creation through the mission editor. With this enhancement, the Add Document page is displayed immediately after mission creation, allowing documents to be attached right away.

To group custom fields in the mission creation form using a group name, follow the steps below:

Open the Nomadia Delivery application and go to the Configuration tab.

![Screenshot](./screenshots/image-226.png)

From the list, select Custom fields,

![Screenshot](./screenshots/image-227.png)

Click on Missions

![Screenshot](./screenshots/image-228.png)

Click the Pencil icon to edit an existing custom field.

![Screenshot](./screenshots/image-229.png)

In the Group name autocomplete field, enter a group name. You can choose an existing group or create a new one on the fly.

![Screenshot](./screenshots/image-230.png)

Once the group name is selected, click Save to apply the changes.

![Screenshot](./screenshots/image-231.png)

The assigned group name will be displayed in the Custom Fields table.

![Screenshot](./screenshots/image-232.png)

To arrange custom field groups in the desired order during mission creation, follow the steps below:

Open the Nomadia Delivery application and navigate to the Configuration tab.

![Screenshot](./screenshots/image-233.png)

Go to the Missions tab.

![Screenshot](./screenshots/image-234.png)

Click the Actions menu and select Add (beta).

![Screenshot](./screenshots/image-235.png)

Choose the mission type and agency, then click Next.

![Screenshot](./screenshots/image-236.png)

![Screenshot](./screenshots/image-237.png)

Click the Pencil icon to edit the mission configuration.

![Screenshot](./screenshots/image-238.png)

Expand the Custom fields accordion.

![Screenshot](./screenshots/image-239.png)

All custom field groups are displayed as separate accordions.

Click a Custom field group accordion to expand it.

The custom fields belonging to the selected group are listed.

Select the fields you want to display in the mission creation form.

![Screenshot](./screenshots/image-240.png)

The mission creation form dynamically updates the field visibility based on your selections.

![Screenshot](./screenshots/image-241.png)

Drag and drop the custom field groups to reorder them and control how they appear in the mission creation form.

![Screenshot](./screenshots/image-242.png)

To change the order of fields within a group, enable field display by toggling them using the identifier or name.

![Screenshot](./screenshots/image-243.png)

In addition to the default mandatory fields, you can mark custom fields as mandatory directly in the mission configuration by enabling the corresponding toggle.

![Screenshot](./screenshots/image-244.png)

Once all changes are complete, click Save to apply them.

![Screenshot](./screenshots/image-245.png)

You can use the same procedure to activate custom fields for parcels.

To group missions within a container, follow the steps below:

Open the Nomadia Delivery application and navigate to the Configuration tab.

Go to the Missions tab.

Click the Actions menu and select Add (beta).

Choose the mission type and agency, then click Next.

Click the Pencil icon to edit the mission configuration.

From the Group your parcels drop-down list, select one of the available options.

Yes: Group missions in a container automatically if multiple parcels are added to the mission.

No: Do not group missions even if multiple parcels are added to the mission.

![Screenshot](./screenshots/image-246.png)

Optional: Let the user decide the choice during the mission creation process.

If set to ‘Yes’, select the default type of container to be created in the container type for grouping drop-down.

![Screenshot](./screenshots/image-247.png)

Please note that only aggregable containers that can contain other missions will be displayed in this drop-down.

After making the changes to the mission configuration, click the ‘Save’ button to save the changes.

![Screenshot](./screenshots/image-248.png)

To add documents to missions immediately after the mission creation, follow the steps below:

Open the Nomadia Delivery application and navigate to the Configuration tab.

Go to the mission tab.

Click the ‘Actions’ menu and click the ‘Add(beta)’ menu item

Select the mission type and the agency and click the ‘Next’ button

Edit the mission configuration by clicking the ‘Pencil’ icon.

Activate the toggle ‘Add documents’ in the mission creation.

![Screenshot](./screenshots/image-249.png)

After making the changes to the mission configuration, click the ‘Save’ button to save the changes.

![Screenshot](./screenshots/image-250.png)

If set to yes, the question to add documents to the mission is asked immediately after the mission is created.

![Screenshot](./screenshots/image-251.png)

The user can opt to add documents from the local computer or from the document library and click ‘Save’ to attach documents to the mission.

![Screenshot](./screenshots/image-252.png)

The documents will be added successfully to the newly created mission.

![Screenshot](./screenshots/image-253.png)

### 6.4.4. Group missions in one container

This feature allows multiple missions to be grouped into a single parent container, such as a pallet, box, or cardboard container. Grouping facilitates the management of bulk orders for a single customer or location, allowing the system to treat several child missions as part of one parent entity.

Grouping via Mission Duplication

Navigate to the Mission tab.

![Screenshot](./screenshots/image-254.png)

Create a new mission from the Actions menu

![Screenshot](./screenshots/image-255.png)

Select the mission and use the Duplicate feature. Duplication can be completed within the Parcel section. If the Parcel details are not visible, please enable the Parcel section in the mission configuration.

![Screenshot](./screenshots/image-256.png)

Select the desired Container Type (e.g., Pallet, Box) from the dropdown menu.

![Screenshot](./screenshots/image-257.png)

When the system prompts "Group in container?", select Yes.

![Screenshot](./screenshots/image-258.png)

Parent containers and Child missions have been created.

![Screenshot](./screenshots/image-259.png)

This option is available in the Sub-status configuration.

Grouping Existing Missions via Actions

Select the mission(s) intended for grouping.

![Screenshot](./screenshots/image-260.png)

Click the Actions menu.

Select Group in one container.

![Screenshot](./screenshots/image-261.png)

Choose either new container to create a new parent or select an existing container by its ID.

Click Apply to update the Parent ID for the selected missions.

![Screenshot](./screenshots/image-262.png)

The missions have been grouped in the parent mission

![Screenshot](./screenshots/image-263.png)

### 6.4.5. Manage Urgent Missions

### 6.4.5.1. Prioritizing a mission

Prioritization allows users to set the urgency of a mission to ensure it is handled according to specific timelines or customer commitments. The system supports manual priority assignment, automatic assignment based on dates, and priority recalculation during route optimization.

Manual Priority Assignment

Select the mission(s) to be prioritized.

![Screenshot](./screenshots/image-264.png)

Click the Prioritize button from the Actions menu

![Screenshot](./screenshots/image-265.png)

Select the priority level: Normal, High, or Highest.

Automatic Priority via Delivery Dates

Open the mission creation or edit screen.

Navigate to Delivery Information.

Populate the Delivery Asked Date and Delivery Asked End Date.

![Screenshot](./screenshots/image-266.png)

Save the mission; the system automatically sets the priority to Highest based on these commitment dates.

![Screenshot](./screenshots/image-267.png)

Recalculating Priorities during Optimization

Select the missions or parent route for optimization.

![Screenshot](./screenshots/image-268.png)

Click Optimize from the Actions menu

![Screenshot](./screenshots/image-269.png)

Switch the Recalculate Priorities toggle to ON.

![Screenshot](./screenshots/image-270.png)

Run the optimization.

![Screenshot](./screenshots/image-271.png)

### 6.4.5.2. Create an urgent mission

Urgent missions follow a "Chained" model where a pickup is immediately followed by a delivery for the same order, like on-demand food or healthcare delivery. This feature ensures a strict 1-to-1 sequence of operations and uses a dedicated assignment workflow for available drivers.

Open the mission creation screen.

Select the mission type Chained Pickup and Delivery.

![Screenshot](./screenshots/image-272.png)

Enter the Pickup Information (Origin).

Enter the Delivery Information (Destination).

![Screenshot](./screenshots/image-273.png)

Select the created mission from the list.

Click the Assign Urgent Mission button.

![Screenshot](./screenshots/image-274.png)

The new pickup mission will be dynamically added to the existing route

![Screenshot](./screenshots/image-275.png)

### 6.4.5.3. Create an urgent pickup mission (Emergency Pickup)

This feature allows an unplanned pickup mission to be inserted into an existing, published route while the driver is already in the field. It is specifically designed for pickup scenarios, such as a customer requesting an immediate return of a damaged item.

Create a new Pickup mission.

![Screenshot](./screenshots/image-276.png)

Select the mission from the list.

Click the Actions menu.

Select Emergency Pickup.

![Screenshot](./screenshots/image-277.png)

Choose the insertion point of the driver:

Assign After: Adds the pickup as the very next stop.

Assign at End: Adds the pickup to the end of the current route.

![Screenshot](./screenshots/image-278.png)

Click Replace

![Screenshot](./screenshots/image-279.png)

These grouped missions will be executed only once on the mobile application, significantly reducing field execution time. Additionally, even if missions are not grouped beforehand, the mobile app automatically groups missions that share the same address information.

### 6.4.5.4. Create a 'perform at once' mission

'Perform at once' links multiple individual missions destined for the same customer/address. Unlike container grouping, this relies on a "Grouping Key" to tell the mobile app that these items should be fulfilled together, allowing for a single validation step (one signature or one photo) for all linked items.

Select multiple missions that share the exact same delivery address.

![Screenshot](./screenshots/image-280.png)

Click the Actions menu.

Select Perform at once.

![Screenshot](./screenshots/image-281.png)

The system generates a Grouping Key for the selected missions.

![Screenshot](./screenshots/image-282.png)

### 6.4.6. Mission Wizard: A Guided step by step process

The Mission Creation Wizard in Nomadia Delivery provides a user-friendly, step-by-step

process for creating and adding missions effortlessly. From entering basic mission details to

specifying customer opening hours, the wizard simplifies mission setup while ensuring

accuracy and efficiency throughout.

Follow these steps to create a mission using the wizard

Open the delivery management system, then navigate to the ‘Missions’ tab

![Screenshot](./screenshots/image-283.png)

Click the ‘Actions’ button and choose ‘Add’ to launch the mission creation wizard

![Screenshot](./screenshots/image-284.png)

Select the type of mission and agency

![Screenshot](./screenshots/image-285.png)

Pickup Address details

For Pickup Missions: Enter the pickup address details, such as the address line, city,

state/province, postal code, and any additional instructions or landmarks. This helps ensure the

pickup point is accurately identified and located.

For Delivery Missions: The agency address is used by default.

![Screenshot](./screenshots/image-286.png)

Delivery Address details

For Delivery Missions: Enter the delivery address details. Providing clear and accurate

information is essential to ensure successful and timely deliveries.

For Pickup Missions: The agency address is used by default.

![Screenshot](./screenshots/image-287.png)

Parcel Information (Optional): In this step, provide details about the parcels, such as

dimensions, weight, contents, and any special handling requirements. Supplying accurate parcel

information helps ensure proper handling and maintains delivery integrity.

![Screenshot](./screenshots/image-288.png)

Customer Opening Hours Definition (Optional): Specify the customer’s opening hours to schedule deliveries within appropriate time slots. This ensures delivery timings aligned with customer availability, reducing the chances of missed deliveries or rejections.

![Screenshot](./screenshots/image-289.png)

Add Mission to Delivery Management System: After entering all required information, click

the ‘Add’ button to save the mission in the delivery management system.

![Screenshot](./screenshots/image-290.png)

The mission has been successfully created. This wizard streamlines the process by guiding

users’ step by step, ensuring that all required information is entered accurately.

![Screenshot](./screenshots/image-291.png)

### 6.4.7. Import Missions

From the Missions page

Click Actions.

Select Import from the dropdown menu.

![Screenshot](./screenshots/image-292.png)

Click Browse (Excel).

![Screenshot](./screenshots/image-293.png)

Choose the desired Excel file from your local system to upload and import it.

![Screenshot](./screenshots/image-294.png)

Missions will be imported successfully.

![Screenshot](./screenshots/image-295.png)

### 6.4.8. Map the import mission file fields

### 6.4.8.1. Map the address fields

From the Missions page

Click Actions.

Select Import from the dropdown menu.

Click Browse (Excel).

Select the Address from the location indicators

![Screenshot](./screenshots/image-296.png)

Click on Validate

![Screenshot](./screenshots/image-297.png)

The address fields will be mapped successfully

![Screenshot](./screenshots/image-298.png)

![Screenshot](./screenshots/image-299.png)

### 6.4.8.2. Map the addresses fields from the global address list

The Global Address List now offers enhanced control over how addresses are managed and accessed in Nomadia Delivery. It is no longer restricted to contractors and is now available directly from the Configuration module. Addresses added to the Global Address List are visible and usable by all Nomadia Delivery users, regardless of contractor.

To use addresses from the Global Address List, follow the steps below:

1. Open the Nomadia Delivery application and go to the Configuration tab.

![Screenshot](./screenshots/image-300.png)

Select Address List from the menu.

![Screenshot](./screenshots/image-301.png)

Create a new address or import addresses from an Excel file.

![Screenshot](./screenshots/image-302.png)

Once the address list is created, navigate to the Mission page.

![Screenshot](./screenshots/image-303.png)

From the mission table, select Actions → Add (Beta).

![Screenshot](./screenshots/image-304.png)

Select an agency from the dropdown list and click Next.

![Screenshot](./screenshots/image-305.png)

![Screenshot](./screenshots/image-306.png)

In the address picker (pickup/delivery), enter an address from the Address List.

![Screenshot](./screenshots/image-307.png)

The autocomplete suggests addresses from the Global Address List.

If a contractor is selected during mission creation, the autocomplete combines contractor addresses and Global Address List entries into a single dropdown.

![Screenshot](./screenshots/image-308.png)

Items in the dropdown are distinguished by an icon and tooltip, indicating whether they come from the Global Address List or the contractor’s address list.

![Screenshot](./screenshots/image-309.png)

This ensures a seamless and unified experience when entering mission addresses.

### 6.4.9. Improve the Missions addresses geocoding

### 6.4.9.1. Correct geocoding with a new address

From the Missions page

Click Actions.

Select Import from the dropdown menu.

Click Browse (Excel).

Disable the Pickup address field

Select the Latitude and Longitude from the location indicators

Click on Validate

Update the New address in the new address field

![Screenshot](./screenshots/image-310.png)

### 6.4.10. Select Missions from the map

From the Map view.

Use the Selection button to choose the selection method (e.g., Polygon, Circle).

![Screenshot](./screenshots/image-311.png)

Draw/select the region to highlight missions.

![Screenshot](./screenshots/image-312.png)

Selected missions will appear in the table view on the left panel.

![Screenshot](./screenshots/image-313.png)

## 

### 6.4.11. Manage Missions Table

### 6.4.11.1. Customize the Table Display

Click on the Table action menu

Click on Customize List.

![Screenshot](./screenshots/image-314.png)

Select the desired fields from the Available Fields list and click the arrow icon to move them to

the Display Fields section.

Click on Save

![Screenshot](./screenshots/image-315.png)

The selected fields will be displayed on the table

![Screenshot](./screenshots/image-316.png)

### 6.4.11.2. Sort the Table

Click on the column header (e.g., Last Name).

Select Ascending or Descending order.

The table reorders based on the selection.

![Screenshot](./screenshots/image-317.png)

### 6.4.11.3. Filter the Table

### 6.4.11.3.1. Filter Table using Mission statuses shortcuts

Click on the Mission Status dropdown or shortcut button.

Choose the desired status like Waiting, Picked Up, etc.

The table will refresh and show only matching entries.

![Screenshot](./screenshots/image-318.png)

### 

### 

### 

### 6.4.11.3.2. Change the order of Mission statuses shortcuts

Click on the Filter configuration icon (grey panel).

Drag mission statuses into the preferred sequence.

![Screenshot](./screenshots/image-319.png)

Save or apply changes (For new filter creation Only)

![Screenshot](./screenshots/image-320.png)

### 

### 

### Filter the Table using criteria

Click on the Filter input field.

Select the appropriate condition from the suggestions.

Choose the relevant operator from the dropdown.

Enter the required value for the condition.

Press the Enter key to apply the filter.

![Screenshot](./screenshots/image-321.png)

### 6.4.11.3.4. Create a Filter

Click on the Filter input field.

Select the appropriate condition from the suggestions.

Click the Load saved filter icon

Enter the Appropriate name in the input field

Click on Save

![Screenshot](./screenshots/image-322.png)

### 6.4.11.3.5. Pin a Filter

Click Load saved filters icon.

Click on the pin icon of the filter to pin.

![Screenshot](./screenshots/image-323.png)

### 6.4.11.3.6. Delete a Filter

Click on the Filter input field.

Select the appropriate condition from the suggestions.

Click the filter option.

Click the "Delete" icon to delete the selected status

![Screenshot](./screenshots/image-324.png)

### 6.4.11.4. Color the Missions

From the Missions page

Click Actions.

Select Coloring from the dropdown menu.

![Screenshot](./screenshots/image-325.png)

Select the appropriate condition from the suggestions.

Choose the Color

Click on Save

![Screenshot](./screenshots/image-326.png)

The selected color will be applied successfully.

![Screenshot](./screenshots/image-327.png)

### 6.4.11.5. Search for a Mission

Click the Search icon.

You can search using any of the following fields

Mission Number

Sender Barcode

Phone Number

Customer Name

Postal Code

City

![Screenshot](./screenshots/image-328.png)

Enter the Desired Criterion in the input field.

The corresponding mission details will appear below.

![Screenshot](./screenshots/image-329.png)

### 6.4.11.6. View a Mission information

Click the Pen icon corresponding to the desired mission.

![Screenshot](./screenshots/image-330.png)

A details panel will open showing information such as:

Pickup details

Delivery location

Parcel barcode and contents

Contact information, etc.

![Screenshot](./screenshots/image-331.png)

### 6.4.12. Mission Ticketing System

The mission ticketing system in Nomadia Delivery simplifies the process of managing mission- or parcel-related queries. It allows contractors to raise tickets directly from the mission editor via the

Help tab. This ensures that any issues or concerns arise during a mission is reported quickly and resolved efficiently.

To access the ticket module, users must have the appropriate rights granted by administrators. To enable the ticket module for contractors or transporters,

follow these steps:

Open the Nomadia Delivery application and navigate to the Configuration tab.

![Screenshot](./screenshots/image-332.png)

Select manage users from the drop-down.

![Screenshot](./screenshots/image-333.png)

Click the pencil icon next to the user to edit a user.

![Screenshot](./screenshots/image-334.png)

Go to the ‘Roles & Rights’ tab.

Activate the necessary rights under the Tickets section.

![Screenshot](./screenshots/image-335.png)

Click ‘Save’ to save the configuration.

![Screenshot](./screenshots/image-336.png)

To create a ticket a contractor user should follow these steps:

Open the Nomadia Delivery application and go to the Missions tab.

Apply the Not delivered / Not picked pre-filter to display missions that are in distress.

Click the pencil icon next to the relevant mission to switch to edit mode.

![Screenshot](./screenshots/image-337.png)

Open the Help tab and select Create a ticket to initiate a support ticket for the mission.

![Screenshot](./screenshots/image-338.png)

Enter your query in the provided field and click Send to submit the ticket to the transporter.

![Screenshot](./screenshots/image-339.png)

The ticket is created, and the transporter will receive an email notification about the reported

issue.

![Screenshot](./screenshots/image-340.png)

To reply to a ticket, the transporter should follow these steps:

Once a contractor creates a ticket, the transporter receives an email containing the query and a

direct link to the related mission.

![Screenshot](./screenshots/image-341.png)

Click the link to open the Mission Editor and view the ticket details.

![Screenshot](./screenshots/image-342.png)

Alternatively, transporters can locate missions with active tickets by applying the Open ticket filter

= Yes in the Missions tab and saving it as a pre-filter for ongoing monitoring

![Screenshot](./screenshots/image-343.png)

To respond, open the Help tab, enter your reply in the message box, and click Reply to send the

response.

![Screenshot](./screenshots/image-344.png)

To reply to a ticket, the contractor should follow these steps

When the transporter replies to a ticket, the contractor receives an email with the response and a

direct link to the related mission.

![Screenshot](./screenshots/image-345.png)

To reply, open the Mission Editor, go to the Help tab, type your message in the response box,

and click Reply.

![Screenshot](./screenshots/image-346.png)

To close a ticket, the transporter should follow these steps:

After sharing the required information with the contractor, the transporter can close the ticket by

selecting the Close Ticket button in the Mission Editor.

![Screenshot](./screenshots/image-347.png)

To reopen a ticket, the contractor should follow these steps:

As soon as the ticket is closed by the transporter an email will be sent to the contractor about the

ticket closure.

![Screenshot](./screenshots/image-348.png)

The contractor can click on the link and reopen the ticket if the resolution provided by the

transporter is not satisfactory.

In the help tab of the mission editor, click on the reopen button to reopen the ticket if the response

is not satisfactory.

![Screenshot](./screenshots/image-349.png)

To perform a bulk edit of tickets, contractors or transporters should follow these steps:

Go to the Tickets module to fetch the list of the tickets created in the system

![Screenshot](./screenshots/image-350.png)

Select one or many tickets and click -> Actions

![Screenshot](./screenshots/image-351.png)

Click ‘Reopen’ to reopen all the selected closed tickets OR click ‘Close ticket’ to Close all the

replied tickets.

A warning message is displayed to validate the action.

![Screenshot](./screenshots/image-352.png)

Click ‘Yes’ to confirm the actions

A notification message is displayed confirming the action.

![Screenshot](./screenshots/image-353.png)

### 

### 6.4.13. Attaching Documents to the Mission

Nomadia Delivery now includes a feature that enables transporters and contractors to upload and link essential documents directly to missions. This ensures better compliance and safety throughout the transportation process.

To build and manage a document library within Nomadia Delivery, follow these steps:

Open the Nomadia Delivery application and go to the Configuration tab.

From the drop-down menu, select Document Library.

![Screenshot](./screenshots/image-354.png)

Click the Actions button and choose Import to upload a document from your computer.

![Screenshot](./screenshots/image-355.png)

Enter a clear and relevant identifier to help you recognize the document later.

![Screenshot](./screenshots/image-356.png)

Click Save to store the document in the Document Library.

![Screenshot](./screenshots/image-357.png)

The uploaded document will now be available in the Document Library section.

![Screenshot](./screenshots/image-358.png)

Steps to attach a document to a mission:

Open the Nomadia Delivery application and go to the Missions tab

Select the mission you want to update and click the pencil icon to edit it.

![Screenshot](./screenshots/image-359.png)

Navigate to the Documents tab.

![Screenshot](./screenshots/image-360.png)

Choose the source of the document you want to upload:

The default Document Library within Nomadia Delivery

Your local computer

Cloud storage services

Select the source and follow the on-screen instructions to complete the upload.

If uploading from the Document Library, click Browse the Library, then choose the

document(s) you want to attach.

Click Import.

![Screenshot](./screenshots/image-361.png)

Click Save.

![Screenshot](./screenshots/image-362.png)

The document is now successfully attached to the mission

![Screenshot](./screenshots/image-363.png)

### 6.4.14. Duplicating Missions with Quantities

This guide explains how contractors and transporters can duplicate missions with quantities in Nomadia Delivery. The feature simplifies the handling of multiple items, enhancing both efficiency and accuracy in mission management.

Steps to duplicate missions with quantities:

Open the Nomadia Delivery application and go to the Missions tab.

![Screenshot](./screenshots/image-364.png)

In the Mission table, click the Actions drop-down menu and select Add.

![Screenshot](./screenshots/image-365.png)

In the mission wizard, complete the mandatory fields according to the mission type (e.g., agency,

pickup address, delivery address, etc.).

![Screenshot](./screenshots/image-366.png)

![Screenshot](./screenshots/image-367.png)

Under the Parcel section, enter parcel details such as length, width, height, weight, volume,

and solver constraints.

![Screenshot](./screenshots/image-368.png)

To add a new parcel with different values, click the “+” symbol.

![Screenshot](./screenshots/image-369.png)

To duplicate an existing parcel with the same details, click the Copy icon.

![Screenshot](./screenshots/image-370.png)

If you mistakenly add a parcel, click the Delete icon to remove it.

![Screenshot](./screenshots/image-371.png)

After finalizing the parcels to be duplicated, click Add to generate the required number of

missions.

![Screenshot](./screenshots/image-372.png)

The duplicated missions will now appear in the mission table.

![Screenshot](./screenshots/image-373.png)

### 6.4.15. Cross Docking Missions

Cross-docking missions are a newly introduced feature in Nomadia Delivery aimed at improving efficiency and ensuring full traceability across both mid-mile and last mile logistics. The same mission ID (Barcode) is maintained throughout the process, allowing transporters to seamlessly manage parcel movements from the point of pickup to final delivery.

A cross-docking mission is divided into two main legs:

Leg 1 – Mid-Mile Pickup Tour

Plan the Pickup Tour: Organize and assign missions for the pickup route, starting from the

agency.

Collect Parcels: Deliverers pick up parcels directly from the contractor’s warehouse or

designated location.

Return to Agency: All collected parcels are brought back to the agency for sorting and

processing.

Leg 2 – Last-Mile Delivery Tour

Plan the Delivery Tour: After parcels are sorted at the agency, prepare and assign the final

delivery route.

Load for Delivery: Deliverers collect the sorted parcels from the agency.

Deliver to Customers: Parcels are delivered to end recipients, with the same mission ID

(Barcode) ensuring consistent tracking and traceability.

To set up a cross-docking mission, proceed with the following steps.

Open the Nomadia Delivery application and go to the Missions tab.

![Screenshot](./screenshots/image-374.png)

Click the Actions menu and select Add.

![Screenshot](./screenshots/image-375.png)

In the Mission type drop-down, select Cross-docking to create a cross-docking mission.

![Screenshot](./screenshots/image-376.png)

From the Contractor identifier drop-down, choose the contractor linked to the cross-docking

mission.

Note: For cross-docking missions, if the contractor is mapped, their registered address will automatically be used as the default pickup address for Leg 1 | Mid-Mile Pickup Tour. This address is retrieved from the contractor configuration.

![Screenshot](./screenshots/image-377.png)

Select the Agency from which deliverers will start for the Leg 1 | Mid-Mile Pickup Tour.

![Screenshot](./screenshots/image-378.png)

Click Next to continue.

![Screenshot](./screenshots/image-379.png)

By default, the contractor’s address will be used as the pickup address. If required, you can select

a different pickup address for Leg 1 | Mid-Mile Pickup Tour by clicking the Edit button next to the

address field.

![Screenshot](./screenshots/image-380.png)

Enter the delivery address of the end customer in the address section to complete the cross-

docking mission setup.

![Screenshot](./screenshots/image-381.png)

Click Add to create the cross-docking mission.

![Screenshot](./screenshots/image-382.png)

A new mission of type Cross-docking will now be added to the delivery management system.

![Screenshot](./screenshots/image-383.png)

To create a cross-docking mission Leg1 | Mid-Mile Pickup Tour, follow these steps

Select the created mission, open the Actions menu, and choose Assign. Assign the mission to a

deliverer.

![Screenshot](./screenshots/image-384.png)

Provide a name for the route, select the deliverer, and specify the date and time for the pickup

mission – Leg 1 | Mid-Mile Pickup Tour. Click OK to create the tour.

![Screenshot](./screenshots/image-385.png)

The Leg 1 | Mid-Mile Pickup Tour route will now be created in the delivery management system

and will be ready for publishing to the deliverer’s mobile app.

![Screenshot](./screenshots/image-386.png)

Open the Actions menu again and select Publish on mobile app.

![Screenshot](./screenshots/image-387.png)

Click OK to confirm and push the tour details to the mobile app.

![Screenshot](./screenshots/image-388.png)

The Leg 1 | Mid-Mile Pickup Tour will now be available on the deliverer’s mobile app.

![Screenshot](./screenshots/image-389.png)

The deliverer must perform the pickup in real time to complete the Leg 1 | Mid-Mile Pickup Tour.

![Screenshot](./screenshots/image-390.png)

![Screenshot](./screenshots/image-391.png)

![Screenshot](./screenshots/image-392.png)

Once completed, the confirmation of the tour will be displayed in the Gantt chart with a green

tick mark.

![Screenshot](./screenshots/image-393.png)

Missions for Leg 2 | Last-Mile Delivery Tour can only be planned once the goods are returned to

the depot.

![Screenshot](./screenshots/image-394.png)

To create a cross-docking mission, follow these steps:

Select the Returned to Depot mission, open the Actions menu, and choose Assign. Assign

the mission to a deliverer.

![Screenshot](./screenshots/image-395.png)

Enter a name for the route, select the deliverer, and set the date and time for the delivery

mission – Leg 2 | Last-Mile Delivery Tour. Click OK to create the tour.

![Screenshot](./screenshots/image-396.png)

The Leg 2 | Last-Mile Delivery Tour route will now be created in the delivery management

system and will be ready for publishing to the deliverer’s mobile app.

![Screenshot](./screenshots/image-397.png)

From the Actions menu, select Publish on mobile app.

![Screenshot](./screenshots/image-398.png)

Click OK to confirm and push the tour details to the mobile app.

![Screenshot](./screenshots/image-399.png)

The Leg 2 | Last-Mile Delivery Tour will now be published to the deliverer’s mobile app.

![Screenshot](./screenshots/image-400.png)

The deliverer must carry out the deliveries in real time to complete the Leg 2 | Last-Mile

Delivery Tour.

![Screenshot](./screenshots/image-401.png)

![Screenshot](./screenshots/image-402.png)

![Screenshot](./screenshots/image-403.png)

Once completed, the tour confirmation will be displayed in the Gantt chart with a green

tick mark.

![Screenshot](./screenshots/image-404.png)

### 6.4.16. Drop Shipping Missions

Drop-shipping missions simplify delivery operations by allowing transporters to deliver parcels

directly from suppliers to end customers, without returning to the agency. This method improves

efficiency and is particularly suited to logistical scenarios where direct delivery is more practical than

traditional models such as cross-docking.

To create a drop-shipping mission, users (contractors, transporters, or subcontractors) should

follow these steps

Open the Nomadia Delivery application and go to the Missions tab.

Click on the Actions menu and select Add.

![Screenshot](./screenshots/image-405.png)

In the Mission Type drop-down, choose Drop-Shipping.

![Screenshot](./screenshots/image-406.png)

From the Contractor Identifier drop-down, select the contractor associated with the mission.

![Screenshot](./screenshots/image-407.png)

For drop-shipping missions, the contractor’s address (from contractor configuration) will be

automatically used as the default pickup address.

![Screenshot](./screenshots/image-408.png)

Select the Agency from which the deliverers will begin their tour.

![Screenshot](./screenshots/image-409.png)

Click Next.

![Screenshot](./screenshots/image-410.png)

The system will display the contractor’s address as the pickup location by default.

![Screenshot](./screenshots/image-411.png)

If needed, click the Edit button next to the address field to set a different pickup address.

![Screenshot](./screenshots/image-412.png)

Click Next to continue.

![Screenshot](./screenshots/image-413.png)

Enter the delivery address of the end customer in the address section.

![Screenshot](./screenshots/image-414.png)

Click Add to create the drop-shipping mission.

![Screenshot](./screenshots/image-415.png)

Once completed, a new mission of type Drop-Shipping will be added to the delivery management system.

![Screenshot](./screenshots/image-416.png)

Follow these steps to create a drop-shipping mission tour Drop-shipping missions are exclusively managed through the optimization engine to ensure accuracy and strict compliance with the delivery chain. Manual route planning is restricted to preserve workflow integrity.

Deliveries are permitted only after all pickups are completed, preventing disruptions or errors

Select the missions you have created, open the ‘Actions’ menu, and choose ‘Optimize’ to

perform a batch optimization.

![Screenshot](./screenshots/image-417.png)

Define the optimization scope by selecting the date range, team, and vehicles, then click ‘Optimize’.

![Screenshot](./screenshots/image-418.png)

Once you are satisfied with the results, click ‘Stop and see the result’.

![Screenshot](./screenshots/image-419.png)

The optimization summary is displayed. Click ‘Display the simulation’ to analyze the results.

![Screenshot](./screenshots/image-420.png)

Alternatively, click ‘Validate routes’ to publish the results directly without reviewing them.

In the ‘Deliveries’ panel, the application prefixes all delivery mission numbers with ‘DROP’ to

differentiate pickup and drop events.

![Screenshot](./screenshots/image-421.png)

In the ‘Routes’ panel, select the routes you want to validate, open the ‘Actions’ menu, and click

‘Validate’.

![Screenshot](./screenshots/image-422.png)

Click ‘OK’ to confirm validation.

![Screenshot](./screenshots/image-423.png)

After validation, confirmation notification is displayed.

![Screenshot](./screenshots/image-424.png)

At the bottom of the popup, enable the ‘Publish to the mobile app’ toggle if you want to share

the route with the driver.

![Screenshot](./screenshots/image-425.png)

If conflicts occur, the popup will list all problems detected. In such cases, click ‘Force’ to proceed

with validation.

![Screenshot](./screenshots/image-426.png)

The validated route with drop-shipping missions is then published to the mobile app.

![Screenshot](./screenshots/image-427.png)

Transporters can create routes that start from the agency, pick up parcels directly from the contractor (supplier) location, and deliver them to end customers. Unlike cross-docking missions, these routes do not require returning to the agency after the pickups are completed.

### 6.4.17. Visit – A New Mission Type

The Visit missions are a new category of operational tasks that enable transporters to schedule visits to customer locations without handling parcel pickups or deliveries. They offer greater flexibility for non-transactional activities and enhance planning efficiency across various logistical scenarios.

Transporters can monitor and manage visit missions through customized statuses.

To Be Visited: The visit is planned but has not yet taken place.

Visited: The visit was completed successfully.

Not Visited: The visit was not carried out, with the option of providing a reason if required.

To set up a visit mission, users (contractors, transporters, or subcontractors) should follow

these steps:

Open the Nomadia Delivery application and go to the Missions tab.

Click the ‘Actions’ menu and select ‘Add’.

![Screenshot](./screenshots/image-428.png)

In the Mission Type drop-down, choose the new mission type ‘Visit’ to create a visit mission.

’

![Screenshot](./screenshots/image-429.png)

Since a visit mission does not involve pickups or deliveries, the wizard includes only the Visit

address and opening hours.

![Screenshot](./screenshots/image-430.png)

Select the agency that will serve as the starting point for the deliverers.

![Screenshot](./screenshots/image-431.png)

Click ‘Next’ to proceed to the following step.

![Screenshot](./screenshots/image-432.png)

Enter the visit address of the end customer in the address field.

![Screenshot](./screenshots/image-433.png)

Click ‘Add’ to create the visit mission.

![Screenshot](./screenshots/image-434.png)

A new visit-type mission will now appear in the delivery management system.

![Screenshot](./screenshots/image-435.png)

To set up a tour including visit missions, follow these steps:

Select the created mission, click the ‘Actions’ menu, select the ‘Assign’ menu item and assign the

created mission for a deliverer.

![Screenshot](./screenshots/image-436.png)

Give a name to the route, select the deliverer, date, and time for the visit mission, and click the

‘OK/Force assignment’ button to create the tour.

![Screenshot](./screenshots/image-437.png)

The visit route will be created in the delivery management system, and it is ready to be published

to the mobile app of the deliverer.

Click the ‘Actions’ menu and select the ‘Publish on mobile app’ menu item.

Click the ‘OK’ button to confirm and push the data to the mobile app

The visit route will be published on the mobile app. The status of the mission is now changed to

‘To be visited”.

![Screenshot](./screenshots/image-438.png)

The deliverer, upon logging in to the mobile app, will be able to fulfill the visit with a new status

like Visited & Not Visited.

### 6.4.18. Auto-Assign Missions to Deliverers

The auto-assignment feature in Nomadia Delivery simplifies dispatching by automatically assigning missions to the right deliverers and vehicles based on predefined spatial or postal zones. This reduces manual effort, minimizes administrative workload, and improves efficiency, particularly in high-volume operations.

Prerequisite: To use automatic mission assignments, you must have a postal code zone or a spatial zone configured in advance. For step-by-step guidance, refer to the Zone Creation by Automatic Sectorization guide.

Follow the steps below to link zones with users and vehicles:

Open the Nomadia Delivery application and go to the Configuration tab.

From the drop-down, select Manage users.

Note: Zones can only be associated with users who have mobile access.

Click the Pencil icon next to the desired mobile user.

![Screenshot](./screenshots/image-439.png)

Users with mobile access will see an additional tab for configuring zone rights. Click Agencies

and zones to set up zone assignments.

Move the available zones of the associated agencies to the right-hand panel to assign them to the

user.

![Screenshot](./screenshots/image-440.png)

After adjusting the zone settings, click Save to confirm the changes.

![Screenshot](./screenshots/image-441.png)

If the user is linked to a vehicle, all zone settings will automatically synchronize with that vehicle.

![Screenshot](./screenshots/image-442.png)

Nomadia Delivery also allows users and vehicles to be assigned to different zones in exceptional cases, such as sick leave or sudden unavailability. In such scenarios, a synchronization error will appear in the vehicle’s General section.

![Screenshot](./screenshots/image-443.png)

Once users and vehicles are properly synchronized with their zone settings, missions are automatically assigned based on spatial alignment. If a mission’s pickup or delivery location falls within a configured zone, the corresponding user or vehicle linked to that zone is automatically assigned, and the Scheduled Deliverer field is updated.

![Screenshot](./screenshots/image-444.png)

If multiple users share the same zone, the system assigns the mission to the first user.

![Screenshot](./screenshots/image-445.png)

During optimization, the planner has three options:

Use only the auto-assigned scheduled deliverer.

Allow all compatible vehicles to be considered for optimization.

Ignore the auto-assigned deliverers.

### 6.4.19. Container Child Missions

Container-Child Missions enable planners to group several related deliveries—such as parcels going to the same address—into a single container mission. This approach streamlines planning, strengthens traceability, and boosts operational efficiency by managing the grouped deliveries as one unit while still retaining detailed parcel-level information.

Here are the steps to create a container mission:

Open the Nomadia Delivery application and go to the Mission tab.

Click Actions and select Add to create a new mission.

![Screenshot](./screenshots/image-446.png)

Create a delivery or pickup mission and use the parcel duplication feature to generate multiple

missions for the same address.

![Screenshot](./screenshots/image-447.png)

Click Add to confirm and create the missions.

![Screenshot](./screenshots/image-448.png)

Select the missions you created, then click Actions and choose Group in one container.

![Screenshot](./screenshots/image-449.png)

A new container mission will be generated, automatically inheriting the address and other details

from the selected missions.

![Screenshot](./screenshots/image-450.png)

Open the new container mission and go to the Child Missions tab to view the list of missions

grouped inside.

To modify details of the child missions, click the Pencil icon next to them.

![Screenshot](./screenshots/image-451.png)

Users can assign or optimize missions by selecting only the parent container mission. To filter

container missions specifically, use the parent container is empty condition.

![Screenshot](./screenshots/image-452.png)

Here are the steps to plan or optimize container missions:

Click the Actions button to assign or optimize the selected container missions.

![Screenshot](./screenshots/image-453.png)

To require scanning of all child missions during delivery in the Nomadia Delivery mobile app,

enable the Scan all the items in the container toggle in the Delivered/Not Delivered sub-statuses.

![Screenshot](./screenshots/image-454.png)

Once enabled, the app will enforce scanning of each child mission inside the container. The

deliverer can then manage the sub-status of individual child missions, allowing for either a full or

partial delivery/pickup.

![Screenshot](./screenshots/image-455.png)

![Screenshot](./screenshots/image-456.png)

Any partially delivered missions remain linked to the route for improved traceability.

![Screenshot](./screenshots/image-457.png)

To review child mission logs, click the Pencil icon on the container mission, then open the Child

Missions tab.

![Screenshot](./screenshots/image-458.png)

Use the Log tab to view child mission logs. Activate the Also display logs of parent container

toggle to see both container and child mission logs simultaneously.

![Screenshot](./screenshots/image-459.png)

The Fulfillment tab shows only the container mission’s status for completed deliveries/pickups

and displays the Not Delivered status of child missions in the case of partial deliveries.

![Screenshot](./screenshots/image-460.png)

## 6.5. Bulk Edit Mission Data

### 6.5.1. Create Bulk Edit Configuration

Bulk editing mission data enables large-scale updates to mission information, reducing manual effort and saving time by avoiding repetitive tasks.

To edit mission data in bulk, follow the steps below.

Open the Nomadia Delivery application and go to the Configuration tab.

![Screenshot](./screenshots/image-461.png)

From the main header, click the Missions page.

![Screenshot](./screenshots/image-462.png)

Choose the missions you’re interested in from the mission table.

![Screenshot](./screenshots/image-463.png)

Enter a name for the bulk edit configuration in the Bulk Edit pop-up.

![Screenshot](./screenshots/image-464.png)

Select the fields to be enabled for bulk editing and use the arrow button to move them to the right-hand side.

![Screenshot](./screenshots/image-465.png)

Repeat the same steps for the custom fields in the Bulk Edit pop-up.

![Screenshot](./screenshots/image-466.png)

Click the ‘Save’ button to save the bulk edit configuration.

![Screenshot](./screenshots/image-467.png)

After the configuration is saved, a notification message is displayed.

![Screenshot](./screenshots/image-468.png)

### 6.5.2. Bulk Edit Mission Data

The Bulk Edit pop-up displays the number of selected missions.

The Bulk Edit pop-up displays the list of fields selected during configuration.

Choose the required values for the listed mission fields and click ‘Save’.

![Screenshot](./screenshots/image-469.png)

4. Click on Save

![Screenshot](./screenshots/image-470.png)

All selected missions are updated simultaneously with the values chosen in the Bulk Edit pop-up.

![Screenshot](./screenshots/image-471.png)

This feature improves efficiency while maintaining control and data integrity across teams.