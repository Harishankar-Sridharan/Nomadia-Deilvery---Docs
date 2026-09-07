# receptionmanagement
# receptionmanagement

The **reception management** feature allows dispatchers to manage, verify, and track container deliveries from the field. Enable this feature to automatically receive complete reports and monitor scan logs in real-time. This ensures accurate inventory management and maintains clear communication with your contractors.

### Getting Started

Ensure you have the following system requirements and configurations set up:
- Access to the **Nomadia Delivery** back-office portal.
- A registered contractor email address to receive automatic reports.
- The mobile application installed on field devices.

Follow these steps for initial setup:

1. Navigate to the **Configuration** menu in the portal.

![Configuration Menu - Accessing the portal's configuration panel.](receptionmanagement-receptionmanagement_timestamp_0_to_07.png "Configuration Menu – Accessing the portal's configuration panel.")

2. Click **Configure the mobile app**.

![Configure Mobile App - Selecting the mobile application settings button.](receptionmanagement-receptionmanagement_timestamp_0_to_15.png "Configure Mobile App – Selecting the mobile application settings button.")

3. Enable the **Ask for reception ID** and **Send reception report** toggles under the **Reception** column.

![Reception Column Settings - Turning on reception ID and email report toggles.](receptionmanagement-receptionmanagement_timestamp_0_to_25.png "Reception Column Settings – Turning on reception ID and email report toggles.")

4. Click **Save** to apply the configuration.

![Save Configuration - Clicking save to store mobile app settings.](receptionmanagement-receptionmanagement_timestamp_0_to_43.png "Save Configuration – Clicking save to store mobile app settings.")

5. Go to the **Sub Status** menu and click the **pencil icon** next to the **Received** sub-status.

![Edit Received Sub-Status - Opening the editor for received sub-status.](receptionmanagement-receptionmanagement_timestamp_0_to_57.png "Edit Received Sub-Status – Opening the editor for received sub-status.")

6. Enable the **Scan all the items in the container** toggle.

![Toggle Container Scan - Activating mandatory scans for all container items.](receptionmanagement-receptionmanagement_timestamp_1_to_02.png "Toggle Container Scan – Activating mandatory scans for all container items.")

7. Click **Save** to update the sub-status rules.

![Save Sub-Status - Clicking save to update container scan rules.](receptionmanagement-receptionmanagement_timestamp_1_to_10.png "Save Sub-Status – Clicking save to update container scan rules.")

### Feature Overview

The following UI elements control your reception tracking workflow:

* **Configure the mobile app**: Opens the mobile settings panel to customize field worker workflows.

![Configure Mobile App Button - Access point for mobile workflow configurations.](receptionmanagement-receptionmanagement_timestamp_0_to_15.png "Configure Mobile App Button – Access point for mobile workflow configurations.")

* **Ask for reception ID**: Prompts drivers for a reception identifier to ensure all received shipments are uniquely tracked.

![Ask for Reception ID Toggle - Toggle setting to request reception ID on devices.](receptionmanagement-receptionmanagement_timestamp_0_to_25.png "Ask for Reception ID Toggle – Toggle setting to request reception ID on devices.")

* **Send reception report**: Automatically emails receiving summaries to contractors to replace manual delivery reports.

![Send Reception Report Toggle - Toggle setting to trigger automated contractor emails.](receptionmanagement-receptionmanagement_timestamp_0_to_30.png "Send Reception Report Toggle – Toggle setting to trigger automated contractor emails.")

* **Scan all the items in the container**: Forces drivers to scan every package to prevent missed or incorrect deliveries.

![Scan All Items Toggle - Rule to enforce complete scanning of container contents.](receptionmanagement-receptionmanagement_timestamp_1_to_00.png "Scan All Items Toggle – Rule to enforce complete scanning of container contents.")

* **Customize the list**: Adjusts columns in the back-office view to select displayed columns.

![Customize the List Button - Column selector button for the main table view.](receptionmanagement-receptionmanagement_timestamp_2_to_50.png "Customize the List Button – Column selector button for the main table view.")

* **Sub ID**: Displays the mobile-entered reception identifier to allow quick tracking directly from the list.

![Reception ID Column - Main view column displaying reception IDs.](receptionmanagement-receptionmanagement_timestamp_3_to_15.png "Reception ID Column – Main view column displaying reception IDs.")

### How To: Associate a Contractor with a Machine Container

1. Navigate to the **Machines** menu.

![Machines Menu - Accessing the machines configuration section.](receptionmanagement-receptionmanagement_timestamp_1_to_13.png "Machines Menu – Accessing the machines configuration section.")

2. Click **Create** or edit an existing machine container.

![Create Machine Screen - Form to enter new machine or container details.](receptionmanagement-receptionmanagement_timestamp_1_to_20.png "Create Machine Screen – Form to enter new machine or container details.")

3. Select the associated **Contractor** for the container.

![Select Contractor - Dropdown to link a contractor to the machine.](receptionmanagement-receptionmanagement_timestamp_1_to_27.png "Select Contractor – Dropdown to link a contractor to the machine.")

4. Click **Add** to save the container.

![Add Container - Clicking add to finalize the machine container creation.](receptionmanagement-receptionmanagement_timestamp_1_to_38.png "Add Container – Clicking add to finalize the machine container creation.")

#### Troubleshooting: Unsaved Changes Warning
If you attempt to navigate away without saving, a popup warning will appear.

![Unsaved Changes Flow - Flow showing the unsaved changes warning pop-up.](receptionmanagement-receptionmanagement_timestamp_1_to_52_to_2_to_03.gif "Unsaved Changes Flow – Flow showing the unsaved changes warning pop-up.")

- Click **No** to stay on the page and save your changes.
- Click **Yes** to leave the page and discard progress.

### How To: Scan and Receive Containers in the Mobile Application

1. Open the mobile application on your field device.

![Open App - Launching the field delivery application.](receptionmanagement-receptionmanagement_timestamp_2_to_03.png "Open App – Launching the field delivery application.")

2. Scan the **Parent container form**.

![Scan Parent Container - Using the camera to scan the parent container code.](receptionmanagement-receptionmanagement_timestamp_2_to_11.png "Scan Parent Container – Using the camera to scan the parent container code.")

3. Enter the **Reception name** and **Reception ID** when prompted.

![Enter Details - Form fields to record reception name and identifier.](receptionmanagement-receptionmanagement_timestamp_2_to_16.png "Enter Details – Form fields to record reception name and identifier.")

4. Select the appropriate **Reason** from the dropdown menu.

![Select Reason - Dropdown options to choose receiving status reason.](receptionmanagement-receptionmanagement_timestamp_2_to_20.png "Select Reason – Dropdown options to choose receiving status reason.")

5. Scan all packages to complete the receiving process.

![Scan Packages Flow - Scanning progress for individual items in the container.](receptionmanagement-receptionmanagement_timestamp_2_to_26_to_2_to_35.gif "Scan Packages Flow – Scanning progress for individual items in the container.")

### How To: Display Reception IDs in the Back-Office List

1. Navigate to the main list view in the portal.

![Main List View - Displaying the dispatcher dashboard.](receptionmanagement-receptionmanagement_timestamp_2_to_40.png "Main List View – Displaying the dispatcher dashboard.")

2. Click **Customize the list**.

![Click Customize List - Accessing the column customization menu.](receptionmanagement-receptionmanagement_timestamp_2_to_42.png "Click Customize List – Accessing the column customization menu.")

3. Locate the **Sub ID** field and ensure it is selected for display.

![Toggle Sub ID - Checking the Sub ID column option to make it visible.](receptionmanagement-receptionmanagement_timestamp_3_to_05.png "Toggle Sub ID – Checking the Sub ID column option to make it visible.")

4. Click **Save** to update the list columns.

![Save List Layout - Saving the customized column selection.](receptionmanagement-receptionmanagement_timestamp_3_to_25.png "Save List Layout – Saving the customized column selection.")

5. Verify the entered **Reception ID** is visible in the list.

![View Reception ID - Checking the newly added column in the main list.](receptionmanagement-receptionmanagement_timestamp_3_to_39.png "View Reception ID – Checking the newly added column in the main list.")

### How To: Verify Contractor Email Addresses

1. Navigate to the **Contractor** menu.

![Contractor Menu - Navigating to the contractor directory.](receptionmanagement-receptionmanagement_timestamp_3_to_57.png "Contractor Menu – Navigating to the contractor directory.")

2. Click the **pencil icon** next to the relevant contractor.

![Edit Contractor - Clicking the edit button next to the contractor.](receptionmanagement-receptionmanagement_timestamp_4_to_00.png "Edit Contractor – Clicking the edit button next to the contractor.")

3. View and verify the **Contractor email address** on the details page.

![Verify Contractor Email - Reviewing the registered email address for reports.](receptionmanagement-receptionmanagement_timestamp_4_to_09.png "Verify Contractor Email – Reviewing the registered email address for reports.")

### Productivity Tips

- 💡 **[Automated Reports]**: Enable the **Send reception report** setting to automatically email summaries to contractors, saving manual coordination effort.
- 💡 **[Forced Verification]**: Enable **Scan all the items in the container** under **Received** sub-status to prevent drivers from skipping verification.
- ⚠️ **[Unsaved Progress Warning]**: Avoid exiting the machine creation screen without clicking save, or you will lose all entered details.

***

✉️ Would you like me to create an email template that dispatchers can use to notify contractors about these new automated reception reports?

