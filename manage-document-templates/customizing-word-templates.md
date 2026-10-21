# Customizing Word Templates

This guide provides step-by-step instructions for customizing your Word template used in the PDF export feature, enabling you to download delivery-related documents such as routing sheets, loading sheets, eCMR, mission reports, sticker sheets, and visit reports.

## Before you begin

Open the list of document templates.

1. Open the Nomadia Delivery application and go to the **Configuration** tab.
2. From the drop-down menu, select **Document Templates**.

![](../.gitbook/assets/image-2.png)

The page displays all the default templates that Nomadia Delivery uses to generate PDFs, including routing sheets, loading sheets, eCMR, mission reports, sticker sheets, and visit reports.

![](<../.gitbook/assets/image-2 (7).png>)

Default templates in Nomadia Delivery are enabled by default and cannot be disabled, modified, or deleted. However, if you want to customize a template, you can download the existing one and make the necessary changes to suit your requirements.

## Feature overview

* **Document Templates**: The **Configuration** page that lists the default templates used to generate PDFs, such as routing sheets, loading sheets, eCMR, mission reports, sticker sheets, and visit reports.
* **FieldsMaster\_DocumentTemplate**: The accompanying document that lists all the available fields you can use within a template.
* **Merged field**: A field inserted as a merge field rather than plain text, which prevents issues during PDF generation.
* **Actions** menu: Lets you download, import, enable or disable, and delete templates.
* **Configuration types**: Rule-based auto-assignment of sub status and notification types based on mission parameters.

## Download an existing template

1. Select the **template(s)** you want to download.

![](<../.gitbook/assets/image-3 (8).png>)

2. Open the **Actions** menu and choose **Download**.

![](<../.gitbook/assets/image-4 (8).png>)

3. Open the ZIP file that is generated, which contains all the selected templates.

![](<../.gitbook/assets/image-5 (8).png>)

## Modify an existing template

1. Open the downloaded template in Microsoft Word.

![](<../.gitbook/assets/image-6 (8).png>)

2. Refer to the accompanying document FieldsMaster\_DocumentTemplate, which lists all the available fields that can be used within the template.
3. Customize the template to fit your requirements by adding or removing fields from the fields master document as needed. When adding fields, ensure they are inserted as merged fields rather than plain text to prevent issues during PDF generation. Merged fields (e.g., «${ (contractor.name)!}») are highlighted with a grey background when selected, whereas plain text fields are not.

<table data-header-hidden><thead><tr><th valign="top"></th><th valign="top"></th></tr></thead><tbody><tr><td valign="top">Plain text</td><td valign="top">Merged field</td></tr><tr><td valign="top">${(contractor.name)!}</td><td valign="top">«${(contractor.name)!}»</td></tr></tbody></table>

## Convert plain text into a merge field

1. Copy the plain text of the field, for example: ${(contractor.name)!}.
2. Go to **Insert → Quick Parts → Field**.

![](<../.gitbook/assets/image-7 (9).png>)

3. In the **Categories** dropdown, select **Mail Merge**, then choose **Merge Field** under **Field names**.
4. Paste the **field name** you copied into the **Field name** text box and click **OK**.

### Result

The plain text is converted into a merge field, appearing as: «${(contractor.name)!}»

![](<../.gitbook/assets/image-8 (8).png>)

## Activate a new template

1. Once the new template is ready, navigate to the Document Templates section to upload it.
2. Go to the Configuration module and select **Document Templates** from the menu.
3. Click the **Actions** menu and choose **Import**.

![](<../.gitbook/assets/image-9 (8).png>)

4. Browse your computer and select the **template** you just created.

![](<../.gitbook/assets/image-10 (7).png>)

5. If necessary, update the identifier or file name.

![](<../.gitbook/assets/image-11 (7).png>)

6. Choose the **template type** from the dropdown menu (for example, Consignment Note Template).

![](<../.gitbook/assets/image-12 (6).png>)

7. Select the **agency** or agencies where the template should be available (for example, Louisiana).

![](<../.gitbook/assets/image-13 (7).png>)

8. Click **Save** to upload the template.

![](<../.gitbook/assets/image-14 (6).png>)

The newly uploaded template appears in the templates table.

![](<../.gitbook/assets/image-15 (6).png>)

By default, new templates are disabled. To enable the template:

9. Select the uploaded template and click the **Actions** menu.
10. Choose **Enable/Disable** to activate the template.

![](<../.gitbook/assets/image-16 (6).png>)

### Result

A notification confirms that the template has been updated successfully, and the **Enabled** column displays Yes.

![](<../.gitbook/assets/image-17 (5).png>)

## Generate a PDF using the newly enabled template

1. Navigate to the **Missions** tab and select a route that has been published to the mobile deliverer.

![](<../.gitbook/assets/image-18 (5).png>)

2. Click the **Actions** menu and choose **Consignment Note**.

![](<../.gitbook/assets/image-19 (5).png>)

3. Click the **Download** button to download the consignment note.

![](<../.gitbook/assets/image-20 (5).png>)

### Result

The downloaded PDF is generated using the newly enabled template.

![](<../.gitbook/assets/image-21 (5).png>)

## Delete a template

1. Open the Nomadia Delivery application and go to the **Configuration** tab.
2. From the dropdown menu, select **Document Templates**.

![](../.gitbook/assets/image-2.png)

3. In the table, choose any non-default template, then click the **Actions** menu.
4. Select **Delete** to remove the template.

![](<../.gitbook/assets/image-23 (5).png>)

5. Confirm the deletion by clicking **Yes**.

![](<../.gitbook/assets/image-24 (5).png>)

### Result

The selected template is permanently deleted from the application.

![](<../.gitbook/assets/image-25 (5).png>)

## Modify the template settings

Template settings include the type of document the template is associated with, such as Routing Sheet, Loading Sheet, Sticker Sheet, Consignment Note, Visit Report, or Mission Report, and the agencies for which the template is available.

1. Click the **Edit** button next to the template name.

![](<../.gitbook/assets/image-25 (5).png>)

2. Update the document type and the agencies associated with the template.

![](<../.gitbook/assets/image-27 (5).png>)

3. Click **Save** to apply and save the updated settings.

![](<../.gitbook/assets/image-28 (5).png>)

## Custom Configuration type

Nomadia Delivery offers rule-based auto-assignment for configuration types, covering both sub status and notification, based on mission parameters. This enhancement enables planners to customize the delivery lifecycle according to operational needs, automate recurring decisions and maintain consistent workflows across different types of mission.

* **Sub status Configuration Type**: Defines the intermediate steps or conditions within a mission's lifecycle. While these were previously limited to BASIC, INTERMEDIATE, and ADVANCED, planners now have the flexibility to create unlimited custom sub status types that align with specific business processes.
* **Notification Configuration Type**: Determines how and when customers are notified during the mission lifecycle. Instead of relying on a single template, planners can now set up multiple notification templates to address different scenarios.

Both configuration types can be automatically assigned based on mission attributes, such as customer type or package value.

## Configure the type

1. Open the Nomadia Delivery application and navigate to the **Configuration** tab.
2. From the drop-down, select **Configuration types**.
3. Use the three configuration types that Nomadia Delivery provides by default (BASIC, INTERMEDIATE, and ADVANCED), or create a new one from scratch.
4. To edit an existing configuration type, click the pencil icon next to it.

![](<../.gitbook/assets/image-29 (5).png>)

5. In the **General** tab, activate the toggles based on your requirements:
   * Enable both toggles if the configuration type should apply to sub status and notification.
   * Enable or disable them individually if you want separate configurations for sub status and notification.
6. Define automatic assignment rules so that configuration types are applied without manual effort. These rules are based on mission object fields:
   * If a condition is met, the configuration type is automatically applied to sub status and/or notification.
   * Multiple conditions can be set, and you can choose whether all conditions must be met or if any one condition is sufficient by activating the **Follow all the rules** toggle.
7. If multiple configuration types meet the conditions, the system assigns the one with the highest priority (with 1 being the highest).

![](<../.gitbook/assets/image-30 (4).png>)

8. Use the table below to see how different configuration types, conditions, and rules influence auto-assignment of values in the mission object.

<table data-header-hidden><thead><tr><th valign="top"></th><th valign="top"></th><th valign="top"></th><th valign="top"></th></tr></thead><tbody><tr><td valign="top"><p>Configuration</p><p>type</p></td><td valign="top"><p>Applicable</p><p>for</p></td><td valign="top">Rules</td><td valign="top"><p>Auto-assignment on</p><p>the mission object</p></td></tr><tr><td valign="top">BASIC</td><td valign="top">Substatus &#x26; Notification</td><td valign="top"><p>Package value &#x3C; 49€</p><p>Priority = 4</p><p>Follow all the rules = NO</p></td><td valign="top"><p>If Mission’s package</p><p>value = 39€</p><p>Status configuration type = BASIC</p><p>Notification configuration type =</p><p>BASIC</p></td></tr><tr><td valign="top">INTERMEDIATE</td><td valign="top">Sub status &#x26; Notification</td><td valign="top"><p>Package value &#x3C; 100€ Package value > 50€ Priority = 3</p><p>Follow all the rules = YES</p></td><td valign="top"><p>If Mission’s package</p><p>value = 99€</p><p>Status configuration type = INTERMEDIATE</p><p>Notification configuration type = INTERMEDIATE</p></td></tr><tr><td valign="top">ADVANCED</td><td valign="top">Substatus &#x26; Notification</td><td valign="top"><p>Package value &#x3C; 500€ Package value > 100€ Priority = 2</p><p>Follow all the rules = YES</p></td><td valign="top"><p>If Mission’s package</p><p>value = 499€</p><p>Status configuration type = ADVANCED</p><p>Notification configuration type = ADVANCED</p></td></tr><tr><td valign="top">LUXURY</td><td valign="top">Substatus &#x26; Notification</td><td valign="top"><p>Package value > 500€</p><p>Priority = 1</p><p>Follow all the rules = NO</p></td><td valign="top"><p>If Mission’s package</p><p>value = 500€</p><p>Status configuration type = LUXURY</p><p>Notification configuration type =</p><p>LUXURY</p></td></tr></tbody></table>

9. Once the rules are configured, any newly created or imported mission automatically inherits the corresponding configuration types, and the mission values are filled accordingly.

![](<../.gitbook/assets/image-31 (4).png>)

10. In exceptional cases, manually update the sub status or notification configuration types. If these changes conflict with rule-based assignments, a confirmation pop-up appears.
    * If you confirm, the manual changes are retained.
    * If you decline, the system reverts to auto-assigned configurations.

![](<../.gitbook/assets/image-32 (4).png>)

## Tips

{% hint style="info" %}
**Configuration type priority**: The sub status configuration type assigned to the mission object takes the highest priority, unless a zone configuration explicitly overrides it.
{% endhint %}

## Related topics

* [Manage Document Templates](README.md)
* [Accessing eCMR](accessing-ecmr.md)
