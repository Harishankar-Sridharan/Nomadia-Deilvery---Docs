# Configure Mission Pre-filters

The **Configure Managed Mission Pre-Filters** feature creates custom filter rules based on mission status and type in **Nomadia Delivery**. You need this feature to control fleet visibility and focus workflows on specific operational tasks. By configuring pre-filters, you will streamline tracking and optimize mission management across your team. Pre-filters can also use your custom mission fields, so you can filter the mission list by the attributes that matter to your operations, and you choose which pre-filters each user can see.

## Before you begin

Prerequisites and requirements:

* Access to **Nomadia Delivery** with administrator or dispatcher permissions.
* Active mission records configured in the system.
* Web browser connected to the SaaS platform.
* To filter on custom fields, make sure the custom mission fields exist. See [Custom Fields](8-6-missions/custom-fields.md).

Initial setup steps:

1. Open the **Configuration** page.
2. Select **Mission Pre-Filters** from the settings list.

![Select Mission Pre-Filters from the settings list](.gitbook/assets/MissionPrefilters_BeforeBegin_001.gif)

3. Click **Actions** and select **Add** to open the filter configuration builder.

## Feature overview

* **Status Field**: Selects specific mission operational statuses for the query. It filters the fleet view to show relevant mission states.
* **Mission Type Field**: Specifies mission categories included in the filter. It restricts query results to designated mission types.
* **Logic Operator (AND/OR)**: Toggles conditional logic between filter rules. It defines whether all or any conditions must match.
* **Group Condition**: Combines multiple filter statements into a logical group. It allows complex nested filtering logic.
* **Query Name Field**: Accepts a custom text label for the filter query. It helps users identify saved filter configurations easily.
* **Translation Plus Symbol**: Opens translation entry fields for additional languages. It enables multi-language support for regional dispatchers.
* **Delete Language Button**: Removes an added language translation entry. It deletes unneeded language fields from the query.
* **Manage Usage Option**: Opens user access assignment settings for pre-filters. It controls which users receive restricted mission views.
* **Custom tag**: The **Custom** tag shown next to each custom field in the criteria field list, so that you can tell custom fields from standard fields. New custom fields appear in the list instantly, without any extra setup.
* **Field-type comparisons**: The comparisons offered for each field type, for example **is one of** and **is none of** for lists, **contains**, **equals**, **is empty** and **is not empty** for text, and **equals**, **greater than** and **less than** for numbers. Dates and yes/no fields are also supported.

## Create and customize a mission pre-filter

1. Open the **Configuration** page and click **Mission Pre-Filters**.

2. Click **Actions** and select **Add** to launch the editor.

3. Choose required status values from the **Status Field**.

![Choose required status values from the Status Field](.gitbook/assets/MissionPrefilters_CreateCustomizeMissionPre_001.png)

4. Choose required mission categories from the **Mission Type Field**.

![Choose required mission categories from the Mission Type Field](.gitbook/assets/MissionPrefilters_CreateCustomizeMissionPre_002.png)

5. Click to add additional status conditions if needed.

![Click to add additional status conditions if needed](.gitbook/assets/MissionPrefilters_CreateCustomizeMissionPre_003.png)

6. Select **AND** or **OR** logic to connect your conditions.

![Select AND or OR logic to connect your conditions](.gitbook/assets/MissionPrefilters_CreateCustomizeMissionPre_004.gif)

7. Group conditions together if combining multiple filter rules.

![Group conditions together if combining multiple filter rules](.gitbook/assets/MissionPrefilters_CreateCustomizeMissionPre_005.gif)

8. Type a clear descriptive label in the **Query Name Field**.
9. Click **Save** to create the filter query.

![Click Save to create the filter query](.gitbook/assets/MissionPrefilters_CreateCustomizeMissionPre_006.png)

## Add a custom field to a mission pre-filter

1. Check your custom mission fields and their types, for example **List of values**, **Number** or **Text**.

![The custom mission fields and their types](.gitbook/assets/PrefilterCustomFields_001.jpg)

2. Go to **Configuration** > **Mission pre-filters**, and then click the **pencil icon** next to a pre-filter, or click **Actions** > **Add** to create one.

![The Mission pre-filters page](.gitbook/assets/PrefilterCustomFields_002.jpg)

3. Under **Criteria**, open the field list of a condition. Custom fields appear with a **Custom** tag. Select a custom field.

![Custom fields with the Custom tag in the field list](.gitbook/assets/PrefilterCustomFields_003.jpg)

4. Choose the comparison. The comparisons depend on the field type:

   * For a list of values, choose **is one of** or **is none of**, and then pick the values straight from the list.

![The comparisons for a list field](.gitbook/assets/PrefilterCustomFields_004.jpg)

![Pick values from the list](.gitbook/assets/PrefilterCustomFields_005.jpg)

   * For text, choose **contains**, **equals**, **is empty** or **is not empty**, and then type the text.

![The comparisons for a text field](.gitbook/assets/PrefilterCustomFields_006.jpg)

   * For a number, choose **equals**, **greater than** or **less than**, and then enter the number.

![The comparisons for a number field](.gitbook/assets/PrefilterCustomFields_007.jpg)

5. Add other conditions as needed, with standard fields such as **Status** and custom fields, and connect them with **AND** or **OR**.

![A pre-filter combining standard and custom fields](.gitbook/assets/PrefilterCustomFields_008.jpg)

6. Save the pre-filter.

## Add translations to a pre-filter query

1. Click the **Translation Plus Symbol** next to the translation field.

![Click the Translation Plus Symbol next to the translation field](.gitbook/assets/MissionPrefilters_AddTranslationsPreFilter_001.gif)

2. Select your target language from the dropdown list.

![Select your target language from the dropdown list](.gitbook/assets/MissionPrefilters_AddTranslationsPreFilter_002.png)

3. Enter the query name in the selected language.

![Enter the query name in the selected language](.gitbook/assets/MissionPrefilters_AddTranslationsPreFilter_003.gif)

4. Click the **Delete Language Button** if you want to remove a language.

![Click the Delete Language Button if you want to remove a language](.gitbook/assets/MissionPrefilters_AddTranslationsPreFilter_004.gif)

5. Click **Save** to update language translations.

## Assign a pre-filter query to a user

1. Open the **Configuration** page and click **Manage users**.

![Open the Configuration page and click Manage users](.gitbook/assets/MissionPrefilters_AssignPreFilterQuery_001.gif)

2. Select the target user email address.

![Select the target user email address](.gitbook/assets/MissionPrefilters_AssignPreFilterQuery_002.gif)

3. Locate the **Mission Pre-Filters** section.

![Locate the Mission Pre-Filters section](.gitbook/assets/MissionPrefilters_AssignPreFilterQuery_003.png)

4. Select the query name to assign, such as **Out for Delivery**.

![Select the query name to assign, such as Out for Delivery](.gitbook/assets/MissionPrefilters_AssignPreFilterQuery_004.gif)

5. Click **Save** to apply the assignment.

![Click Save to apply the assignment](.gitbook/assets/MissionPrefilters_AssignPreFilterQuery_005.png)

6. Navigate to **Missions** in the main menu.
7. Click **Apply** to view only the missions that match the assigned status.

![Click Apply to view assigned status missions only](.gitbook/assets/MissionPrefilters_AssignPreFilterQuery_006.gif)

You can also open the user with the **pencil icon** in **Manage users**. The **Mission pre-filters** field is on the **Access** tab, where you select every pre-filter the user can see.

![The Mission pre-filters field of the user](.gitbook/assets/PrefilterCustomFields_009.jpg)

![The pre-filters selected for the user](.gitbook/assets/PrefilterCustomFields_011.jpg)

### Result

The user sees only the pre-filters that are relevant to them. If no pre-filter is selected, the field shows **No restrictions**.

## Apply a pre-filter in the mission list

1. On the **Missions** page, click the pre-filter box at the top left of the page to open the pre-filter panel.
2. In **Mission pre-filter configuration**, choose the pre-filter. The panel shows the number of matching missions.

![The pre-filter panel with the number of matching missions](.gitbook/assets/PrefilterCustomFields_012.jpg)

3. Click **Apply**.

### Result

The mission list shows only the missions that match the pre-filter, for example 22 missions out of 364.

![The mission list filtered by the pre-filter](.gitbook/assets/PrefilterCustomFields_013.jpg)

## Remove an assigned pre-filter from a user

1. Open the **Configuration** page and select **Manage users**.
2. Click the user email address.
3. Clear the assigned query under **Mission Pre-Filters**.

![Clear the assigned query under Mission Pre-Filters](.gitbook/assets/MissionPrefilters_RemoveAssignedPreFilter_001.gif)

4. Click **Save** to update user profile settings.

![Click Save to update user profile settings](.gitbook/assets/MissionPrefilters_RemoveAssignedPreFilter_002.png)

5. Navigate to **Missions** and clear active filter selections.

![Navigate to Missions and clear active filter selections](.gitbook/assets/MissionPrefilters_RemoveAssignedPreFilter_003.gif)

6. Click **Apply** to view all fleet missions again.

![Click Apply to view all fleet missions again](.gitbook/assets/MissionPrefilters_RemoveAssignedPreFilter_004.gif)

## Tips

{% hint style="info" %}
**Multi-Language Adaptability**: Adding language translations ensures international team members view filter query titles in their preferred language.
{% endhint %}

{% hint style="warning" %}
**Hidden Fleet Visibility**: Leaving a pre-filter assigned prevents dispatchers from viewing the full fleet until the assignment is removed.
{% endhint %}

{% hint style="info" %}
**One pre-filter, all your criteria**: Combine standard fields and custom fields in a single pre-filter instead of creating several pre-filters.
{% endhint %}

## Related topics

* [Pre-filters](8-6-missions/understanding-the-missions-page/pre-filters/README.md)
* [Set missions display (prefilter)](8-6-missions/understanding-the-missions-page/pre-filters/set-missions-display-prefilter.md)
* [Understanding the Missions Page](8-6-missions/understanding-the-missions-page/README.md)
* [Custom Fields](8-6-missions/custom-fields.md)
