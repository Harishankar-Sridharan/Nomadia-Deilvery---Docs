# Customizing Word Templates

This guide provides step-by-step instructions for customizing your Word template used in the PDF export feature, enabling you to download delivery-related documents such as routing sheets, loading sheets, eCMR, mission reports, sticker sheets, and visit reports.

Follow these steps to manage document templates:

Open the Nomadia Delivery application and go to the Configuration tab.

From the drop-down menu, select Document Templates.

![Screenshot](<../.gitbook/assets/image-1 (8).png>)

The page will display all the default templates that Nomadia Delivery uses to generate PDFs, including routing sheets, loading sheets, eCMR, mission reports, sticker sheets, and visit reports.

![Screenshot](<../.gitbook/assets/image-2 (7).png>)

Default templates in Nomadia Delivery are enabled by default and cannot be disabled,

modified, or deleted. However, if you want to customize a template, you can download the

existing one and make the necessary changes to suit your requirements.

Follow these steps to download an existing template:

Select the template(s) you want to download.

![Screenshot](<../.gitbook/assets/image-3 (8).png>)

Open the Actions menu and choose Download.

![Screenshot](<../.gitbook/assets/image-4 (8).png>)

A ZIP file will be generated, containing all the selected templates.

![Screenshot](<../.gitbook/assets/image-5 (8).png>)

Follow these steps to modify an existing template:

Open the downloaded template in Microsoft Word.

![Screenshot](<../.gitbook/assets/image-6 (8).png>)

Refer to the accompanying document FieldsMaster\_DocumentTemplate, which lists all the

available fields that can be used within the template.

Customize the template to fit your requirements by adding or removing fields from the fields

master document as needed. When adding fields, ensure they are inserted as merged fields

rather than plain text to prevent issues during PDF generation. Merged fields

(e.g., «${ (contractor.name)!}») are highlighted with a grey background when selected, whereas

plain text fields are not.

Follow these steps to convert plain text into a merge field:

Copy the plain text of the field, for example: ${(contractor.name)!}.

Go to Insert → Quick Parts → Field.

![Screenshot](<../.gitbook/assets/image-7 (9).png>)

In the Categories dropdown, select Mail Merge, then choose Merge Field under Field names

Paste the field name you copied into the Field name text box and click OK.

The plain text will now be converted into a merge field, appearing as: «${(contractor.name)!}»

![Screenshot](<../.gitbook/assets/image-8 (8).png>)

"Follow these steps to activate a new template."

Once the new template is ready, navigate to the Document Templates section to upload it.

Go to the Configuration module and select Document Templates from the menu.

Click on the Actions menu and choose Import.

![Screenshot](<../.gitbook/assets/image-9 (8).png>)

Browse your computer and select the template you just created.

![Screenshot](<../.gitbook/assets/image-10 (7).png>)

If necessary, update the identifier or file name.

![Screenshot](<../.gitbook/assets/image-11 (7).png>)

Choose the template type from the dropdown menu (e.g., Consignment Note Template).

![Screenshot](<../.gitbook/assets/image-12 (6).png>)

Select the agency or agencies where the template should be available (e.g., Louisiana).

![Screenshot](<../.gitbook/assets/image-13 (7).png>)

Click Save to upload the template.

![Screenshot](<../.gitbook/assets/image-14 (6).png>)

The newly uploaded template will now appear in the templates table.

![Screenshot](<../.gitbook/assets/image-15 (6).png>)

By default, new templates are disabled. To enable the template:

Select the uploaded template and click the Actions menu.

Choose Enable/Disable to activate the template.

![Screenshot](<../.gitbook/assets/image-16 (6).png>)

A notification will confirm that the template has been updated successfully, and the Enabled

column will display Yes.

![Screenshot](<../.gitbook/assets/image-17 (5).png>)

Follow these steps to generate a PDF using the newly enabled template:

Navigate to the Missions tab and select a route that has been published to the mobile deliverer.

![Screenshot](<../.gitbook/assets/image-18 (5).png>)

Click on the Actions menu and choose Consignment Note.

![Screenshot](<../.gitbook/assets/image-19 (5).png>)

Click the Download button to download the consignment note.

![Screenshot](<../.gitbook/assets/image-20 (5).png>)

The downloaded PDF will be generated using the newly enabled template.

![Screenshot](<../.gitbook/assets/image-21 (5).png>)

Follow these steps to delete a template

Open the Nomadia Delivery application and go to the Configuration tab.

From the dropdown menu, select Document Templates.

![Screenshot](<../.gitbook/assets/image-22 (5).png>)

In the table, choose any non-default template, then click the Actions menu.

Select Delete to remove the template.

![Screenshot](<../.gitbook/assets/image-23 (5).png>)

Confirm the deletion by clicking Yes.

![Screenshot](<../.gitbook/assets/image-24 (5).png>)

The selected template will be permanently deleted from the application.

![Screenshot](<../.gitbook/assets/image-25 (5).png>)

Follow these steps to modify the template settings.

Template settings include the type of document the template is associated with—such as Routing Sheet, Loading Sheet, Sticker Sheet, Consignment Note, Visit Report, or Mission Report—and the agencies for which the template is available

To modify the settings, click the Edit button next to the template name.

![Screenshot](<../.gitbook/assets/image-26 (5).png>)

You can update the document type and the agencies associated with the template.

![Screenshot](<../.gitbook/assets/image-27 (5).png>)

Once the changes are made, click Save to apply and save the updated settings.

![Screenshot](<../.gitbook/assets/image-28 (5).png>)

## 10.1. Custom Configuration type

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

![Screenshot](<../.gitbook/assets/image-29 (5).png>)

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

![Screenshot](<../.gitbook/assets/image-30 (4).png>)

The table below illustrates how different configuration types, conditions, and rules influence auto-

assignment of values in the mission object.

Note: The sub status configuration type assigned to the mission object takes the highest priority, unless a zone configuration explicitly overrides it.

Once the rules are configured, any newly created or imported mission will automatically inherit the corresponding configuration types, and the mission values will be filled accordingly.

![Screenshot](<../.gitbook/assets/image-31 (4).png>)

In exceptional cases, users can manually update sub status or notification configuration types. If

these changes conflict with rule-based assignments, a confirmation pop-up will appear.

If confirmed, the manual changes will be retained.

If declined, the system will revert to auto-assigned configurations.

![Screenshot](<../.gitbook/assets/image-32 (4).png>)

##

## 10.2 Customize Email Templates

In Nomadia Delivery, custom notification templates enable planners to personalize communication with end customers according to mission parameters such as customer type or package value. This capability improves operational transparency and boosts customer satisfaction by ensuring timely and relevant messages are delivered.

Default templates

To streamline onboarding, Nomadia Delivery offers a collection of pre-configured default

templates for both email and SMS:

These templates are activated by default.

They act as a fallback when no custom configuration is in place.

While they cannot be deleted, they can be disabled if required.

![Screenshot](<../.gitbook/assets/image-33 (4).png>)

Follow the steps below to create a custom email notification template:

Open the Nomadia Delivery application and go to the Configuration tab.

From the drop-down menu, select Configure outgoing messages.

Click on the Email templates tab.

![Screenshot](<../.gitbook/assets/image-34 (4).png>)

In the table, click the Actions button and select Add.

![Screenshot](<../.gitbook/assets/image-35 (4).png>)

A list of available templates will appear. Choose one to customize (e.g., Time window to

communicate).

![Screenshot](<../.gitbook/assets/image-36 (4).png>)

In the pop-up window, personalize and configure the message as needed. Select a configuration

type to link the template with the mission.

Enable the template and save your changes.

![Screenshot](<../.gitbook/assets/image-37 (4).png>)

Repeat the process to configure other notifications and associate them with the appropriate

configuration types.
