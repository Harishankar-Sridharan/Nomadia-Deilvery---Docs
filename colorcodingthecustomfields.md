# Color coding the custom fields

Color coding custom fields visually highlights key data based on the value ranges in **Nomadia Delivery**. Use this feature to quickly spot critical operational metrics and make faster decisions. Set up custom rules to automatically color-code values across your system workflows.

## Before you begin

Prerequisites:

* Active account in **Nomadia Delivery** with administrative access.
* Pre-existing custom field parameters configured in the system.

Initial Setup Steps:

1. Log into **Nomadia Delivery**, navigate to **Configuration**, and select **Custom Field**.

![Log into Nomadia Delivery, navigate to Configuration, and select Custom Field](.gitbook/assets/ColorCoding_BeforeBegin_001.gif)

## Feature overview

* **Configuration**: Accesses administrative system settings to locate custom parameters.
* **Custom Field**: Opens the management list for custom fields across the system.
* **Package Value**: Represents the specific numerical custom field attribute assigned to assets.
* **Edit Button**: Opens configuration options for the selected custom field attribute.
* **Conditional Background Color**: Defines numerical threshold ranges and their corresponding background colors.
* **Search Button**: Filters mission records by mission number to verify attribute colors.

## Configure color coding rules

1. Log into **Nomadia Delivery** and click **Configuration**.

![Log into Nomadia Delivery and click Configuration](.gitbook/assets/ColorCoding_BeforeBegin_001.gif)

2. Click **Custom Field** from the configuration menu.

![Click Custom Field from the configuration menu](.gitbook/assets/ColorCoding_ConfigureColorCodingRules_001.png)

3. Locate the target field and click the **Edit** button next to **Package Value**.

![Locate the target field and click the Edit button next to Package Value](.gitbook/assets/ColorCoding_ConfigureColorCodingRules_002.gif)

4. Scroll down to **Conditional Background Color**.

![Scroll down to Conditional Background Color](.gitbook/assets/ColorCoding_ConfigureColorCodingRules_003.gif)

5. Input numerical value ranges and assign background colors.

![Input numerical value ranges and assign background colors](.gitbook/assets/ColorCoding_ConfigureColorCodingRules_004.gif)

6. Click **Save** to apply the color rules.

![Click Save to apply the color rules](.gitbook/assets/ColorCoding_ConfigureColorCodingRules_005.png)

## Verify color coding in mission entry

1. Click **Mission** from the main navigation menu.
2. Click **Add** to create a new mission entry.

![Click Add to create a new mission entry](.gitbook/assets/ColorCoding_VerifyColorCodingMission_001.gif)

3. Select the **Mission Type** and **Agency**, then click **Next**.

![Select the Mission Type and Agency, then click Next](.gitbook/assets/ColorCoding_VerifyColorCodingMission_002.gif)

4. Enter a numerical value in **Package Value** to trigger conditional color highlighting.

![Enter a numerical value in Package Value to trigger conditional color](.gitbook/assets/ColorCoding_VerifyColorCodingMission_003.gif)

5. Click **Add** to complete saving the Mission entry.

![Click Add to complete saving the Mission entry](.gitbook/assets/ColorCoding_VerifyColorCodingMission_004.gif)

## Verify color coding in mission table

1. Navigate back to the main overview screen.
2. Locate the **Mission Table** view on the screen.

![Locate the Mission Table view on the screen](.gitbook/assets/ColorCoding_VerifyColorCodingMission_005.png)

3. Review the **Package Value** column to confirm automatic background coloring.

![Review the Package Value column to confirm automatic background coloring](.gitbook/assets/ColorCoding_VerifyColorCodingMission_006.png)

## Verify color coding via mission search

1. Click the **Search** button in the top interface.

![Click the Search button in the top interface](.gitbook/assets/ColorCoding_VerifyColorCodingVia_001.png)

2. Search for the target mission using the **Mission Number**.

![Search for the target mission using the Mission Number](.gitbook/assets/ColorCoding_VerifyColorCodingVia_002.gif)

3. Scroll right across the search table using the horizontal scroll bar.

![Scroll right across the search table using the horizontal scroll bar](.gitbook/assets/ColorCoding_VerifyColorCodingVia_003.gif)

4. Verify the visual color highlighting applied under the **Package Value** header.

![Verify the visual color highlighting applied under the Package Value header](.gitbook/assets/ColorCoding_VerifyColorCodingVia_004.png)

### Result

## Tips

{% hint style="info" %}
**Multi-Location Verification**: Verify custom field color coding across mission creation, systems tables, and search views.
{% endhint %}

{% hint style="info" %}
**Horizontal Scroll Access**: Use the horizontal scroll bar in search tables to locate hidden package value colors.
{% endhint %}

{% hint style="warning" %}
**Unsaved Configuration Rules**: Click Save after editing color ranges or your custom background rules will not apply.
{% endhint %}

## Related topics

* [Custom Fields](8-6-missions/custom-fields.md)
* [Grouping Custom Field](8-6-missions/custom-fields/grouping-custom-field.md)
* [Configuring Mission Visibility](8-6-missions/custom-fields/configuring-mission-visibility.md)
