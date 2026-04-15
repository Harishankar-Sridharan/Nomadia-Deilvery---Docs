# 10. Customizing Word Templates

This guide provides step-by-step instructions for customizing your Word template used in the PDF export feature, enabling you to download delivery-related documents such as routing sheets, loading sheets, eCMR, mission reports, sticker sheets, and visit reports.

Follow these steps to manage document templates:

Open the Nomadia Delivery application and go to the Configuration tab.

From the drop-down menu, select Document Templates.

![Screenshot](./screenshots/image-1.png)

The page will display all the default templates that Nomadia Delivery uses to generate PDFs, including routing sheets, loading sheets, eCMR, mission reports, sticker sheets, and visit reports.

![Screenshot](./screenshots/image-2.png)

Default templates in Nomadia Delivery are enabled by default and cannot be disabled,

modified, or deleted. However, if you want to customize a template, you can download the

existing one and make the necessary changes to suit your requirements.

Follow these steps to download an existing template:

Select the template(s) you want to download.

![Screenshot](./screenshots/image-3.png)

Open the Actions menu and choose Download.

![Screenshot](./screenshots/image-4.png)

A ZIP file will be generated, containing all the selected templates.

![Screenshot](./screenshots/image-5.png)

Follow these steps to modify an existing template:

Open the downloaded template in Microsoft Word.

![Screenshot](./screenshots/image-6.png)

Refer to the accompanying document FieldsMaster_DocumentTemplate, which lists all the

available fields that can be used within the template.

Customize the template to fit your requirements by adding or removing fields from the fields

master document as needed. When adding fields, ensure they are inserted as merged fields

rather than plain text to prevent issues during PDF generation. Merged fields

(e.g., «${ (contractor.name)!}») are highlighted with a grey background when selected, whereas

plain text fields are not.

Follow these steps to convert plain text into a merge field:

Copy the plain text of the field, for example: ${(contractor.name)!}.

Go to Insert → Quick Parts → Field.

![Screenshot](./screenshots/image-7.png)

In the Categories dropdown, select Mail Merge, then choose Merge Field under Field names

Paste the field name you copied into the Field name text box and click OK.

The plain text will now be converted into a merge field, appearing as:     «${(contractor.name)!}»

![Screenshot](./screenshots/image-8.png)

"Follow these steps to activate a new template."

Once the new template is ready, navigate to the Document Templates section to upload it.

Go to the Configuration module and select Document Templates from the menu.

Click on the Actions menu and choose Import.

![Screenshot](./screenshots/image-9.png)

Browse your computer and select the template you just created.

![Screenshot](./screenshots/image-10.png)

If necessary, update the identifier or file name.

![Screenshot](./screenshots/image-11.png)

Choose the template type from the dropdown menu (e.g., Consignment Note Template).

![Screenshot](./screenshots/image-12.png)

Select the agency or agencies where the template should be available (e.g., Louisiana).

![Screenshot](./screenshots/image-13.png)

Click Save to upload the template.

![Screenshot](./screenshots/image-14.png)

The newly uploaded template will now appear in the templates table.

![Screenshot](./screenshots/image-15.png)

By default, new templates are disabled. To enable the template:

Select the uploaded template and click the Actions menu.

Choose Enable/Disable to activate the template.

![Screenshot](./screenshots/image-16.png)

A notification will confirm that the template has been updated successfully, and the Enabled

column will display Yes.

![Screenshot](./screenshots/image-17.png)

Follow these steps to generate a PDF using the newly enabled template:

Navigate to the Missions tab and select a route that has been published to the mobile deliverer.

![Screenshot](./screenshots/image-18.png)

Click on the Actions menu and choose Consignment Note.

![Screenshot](./screenshots/image-19.png)

Click the Download button to download the consignment note.

![Screenshot](./screenshots/image-20.png)

The downloaded PDF will be generated using the newly enabled template.

![Screenshot](./screenshots/image-21.png)

Follow these steps to delete a template

Open the Nomadia Delivery application and go to the Configuration tab.

From the dropdown menu, select Document Templates.

![Screenshot](./screenshots/image-22.png)

In the table, choose any non-default template, then click the Actions menu.

Select Delete to remove the template.

![Screenshot](./screenshots/image-23.png)

Confirm the deletion by clicking Yes.

![Screenshot](./screenshots/image-24.png)

The selected template will be permanently deleted from the application.

![Screenshot](./screenshots/image-25.png)

Follow these steps to modify the template settings.

Template settings include the type of document the template is associated with—such as Routing Sheet, Loading Sheet, Sticker Sheet, Consignment Note, Visit Report, or Mission Report—and the agencies for which the template is available

To modify the settings, click the Edit button next to the template name.

![Screenshot](./screenshots/image-26.png)

You can update the document type and the agencies associated with the template.

![Screenshot](./screenshots/image-27.png)

Once the changes are made, click Save to apply and save the updated settings.

![Screenshot](./screenshots/image-28.png)

## 10.1.  Custom Configuration type

Nomadia Delivery now offers rule-based auto-assignment for configuration types—covering both sub status and notification—based on mission parameters. This enhancement enables planners to customize the delivery lifecycle according to operational needs, automate recurring decisions and maintain consistent workflows across different types of mission.

Sub status Configuration Type

Sub status configuration types define the intermediate steps or conditions within a mission’s lifecycle. While these were previously limited to BASIC, INTERMEDIATE, and ADVANCED, planners now have the flexibility to create unlimited custom sub status types that align with specific business processes.

Notification Configuration Type

Notification configuration types determine how and when customers are notified during the mission lifecycle. Instead of relying on a single template, planners can now set up multiple notification templates to address different scenarios.

Both configuration types can be automatically assigned based on mission attributes, such as customer type or package value.

Follow these steps to configure the type

Open the Nomadia Delivery application and navigate to the Configuration tab.

From the drop-down, select Configuration types.

By default, Nomadia Delivery provides three configuration types: BASIC, INTERMEDIATE, and

ADVANCED. You can either use these existing types or create a new one from scratch.

To edit an existing configuration type, click the Pencil icon next to it.

![Screenshot](./screenshots/image-29.png)

In the General tab, activate the toggles based on your requirements:

Enable both toggles if the configuration type should apply to sub status and notification.

Enable or disable them individually if you want separate configurations for sub status and

notification.

You can define automatic assignment rules so that configuration types are applied without

manual effort. These rules are based on mission object fields:

If a condition is met, the configuration type is automatically applied to sub status and/or

notification.

Multiple conditions can be set, and you can choose whether all conditions must be met or if

any one condition is sufficient by activating the Follow all the rules toggle.

If multiple configuration types meet the conditions, the system will assign the one with the highest

priority (with 1 being the highest).

![Screenshot](./screenshots/image-30.png)

The table below illustrates how different configuration types, conditions, and rules influence auto-

assignment of values in the mission object.

Note: The sub status configuration type assigned to the mission object takes the highest priority, unless a zone configuration explicitly overrides it.

Once the rules are configured, any newly created or imported mission will automatically inherit the corresponding configuration types, and the mission values will be filled accordingly.

![Screenshot](./screenshots/image-31.png)

In exceptional cases, users can manually update sub status or notification configuration types. If

these changes conflict with rule-based assignments, a confirmation pop-up will appear.

If confirmed, the manual changes will be retained.

If declined, the system will revert to auto-assigned configurations.

![Screenshot](./screenshots/image-32.png)

## 

## 10.2 Customize Email Templates

In Nomadia Delivery, custom notification templates enable planners to personalize communication with end customers according to mission parameters such as customer type or package value. This capability improves operational transparency and boosts customer satisfaction by ensuring timely and relevant messages are delivered.

Default templates

To streamline onboarding, Nomadia Delivery offers a collection of pre-configured default

templates for both email and SMS:

These templates are activated by default.

They act as a fallback when no custom configuration is in place.

While they cannot be deleted, they can be disabled if required.

![Screenshot](./screenshots/image-33.png)

Follow the steps below to create a custom email notification template:

Open the Nomadia Delivery application and go to the Configuration tab.

From the drop-down menu, select Configure outgoing messages.

Click on the Email templates tab.

![Screenshot](./screenshots/image-34.png)

In the table, click the Actions button and select Add.

![Screenshot](./screenshots/image-35.png)

A list of available templates will appear. Choose one to customize (e.g., Time window to

communicate).

![Screenshot](./screenshots/image-36.png)

In the pop-up window, personalize and configure the message as needed. Select a configuration

type to link the template with the mission.

Enable the template and save your changes.

![Screenshot](./screenshots/image-37.png)

Repeat the process to configure other notifications and associate them with the appropriate

configuration types.