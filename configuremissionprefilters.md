# Configure Mission Pre-filters

The **Configure Managed Mission Pre-Filters** feature creates custom filter rules based on mission status and type in **Nomadia Delivery**. You need this feature to control fleet visibility and focus workflows on specific operational tasks. By configuring pre-filters, you will streamline tracking and optimize mission management across your team.

## Before you begin

Prerequisites and requirements:

* Access to **Nomadia Delivery** with administrative or dispatcher access.
* Active mission records configured in the system.
* Web browser connected to the SaaS platform.

Initial setup steps:

1. Navigate to **Configuration** in the main menu.
2. Select **Mission Pre-Filters** from the settings list.

![Select Mission Pre-Filters from the settings list](.gitbook/assets/MissionPrefilters_BeforeBegin_001.gif)

3. Click **Actions** and select **Add** to open the filter configuration builder.

![Click Actions and select Add to open the filter configuration builder](.gitbook/assets/MissionPrefilters_BeforeBegin_001.gif)

## Feature overview

* **Status Field**: Selects specific mission operational statuses for the query. It filters the fleet view to show relevant mission states.
* **Mission Type Field**: Specifies mission categories included in the filter. It restricts query results to designated mission types.
* **Logic Operator (AND/OR)**: Toggles conditional logic between filter rules. It defines whether all or any conditions must match.
* **Group Condition**: Combines multiple filter statements into a logical group. It allows complex nested filtering logic.
* **Query Name Field**: Accepts a custom text label for the filter query. It helps users identify saved filter configurations easily.
* **Translation Plus Symbol**: Opens translation entry fields for additional languages. It enables multi-language support for regional dispatchers.
* **Delete Language Button**: Removes an added language translation entry. It deletes unneeded language fields from the query.
* **Manage Usage Option**: Opens user access assignment settings for pre-filters. It controls which users receive restricted mission views.

## How To: Create and Customize a Mission Pre-Filter

1. Open **Configuration** and click **Mission Pre-Filters**.

![Open Configuration and click Mission Pre-Filters](.gitbook/assets/MissionPrefilters_BeforeBegin_001.gif)

2. Click **Actions** and select **Add** to launch the editor.

![Click Actions and select Add to launch the editor](.gitbook/assets/MissionPrefilters_BeforeBegin_001.gif)

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

## How To: Add Translations to a Pre-Filter Query

1. Click the **Translation Plus Symbol** next to the translation field.

![Click the Translation Plus Symbol next to the translation field](.gitbook/assets/MissionPrefilters_AddTranslationsPreFilter_001.gif)

2. Select your target language from the dropdown list.

![Select your target language from the dropdown list](.gitbook/assets/MissionPrefilters_AddTranslationsPreFilter_002.png)

3. Enter the query name in the selected language.

![Enter the query name in the selected language](.gitbook/assets/MissionPrefilters_AddTranslationsPreFilter_003.gif)

4. Click the **Delete Language Button** if you want to remove a language.

![Click the Delete Language Button if you want to remove a language](.gitbook/assets/MissionPrefilters_AddTranslationsPreFilter_004.gif)

5. Click **Save** to update language translations.

![Click Save to update language translations](.gitbook/assets/MissionPrefilters_CreateCustomizeMissionPre_006.png)

## How To: Assign a Pre-Filter Query to a User

1. Navigate to **Configuration** and click **Manage users**.

![Navigate to Configuration and click Manage users](.gitbook/assets/MissionPrefilters_AssignPreFilterQuery_001.gif)

2. Select the target user email address.

![Select the target user email address](.gitbook/assets/MissionPrefilters_AssignPreFilterQuery_002.gif)

3. Locate the **Mission Pre-Filters** section.

![Locate the Mission Pre-Filters section](.gitbook/assets/MissionPrefilters_AssignPreFilterQuery_003.png)

4. Select the query name to assign, such as **Out for Delivery**.

![Select the query name to assign, such as Out for Delivery](.gitbook/assets/MissionPrefilters_AssignPreFilterQuery_004.gif)

5. Click **Save** to apply the assignment.

![Click Save to apply the assignment](.gitbook/assets/MissionPrefilters_AssignPreFilterQuery_005.png)

6. Navigate to **Missions** in the main menu.
7. Click **Apply** to view assigned status missions only.

![Click Apply to view assigned status missions only](.gitbook/assets/MissionPrefilters_AssignPreFilterQuery_006.gif)

## How To: Remove an Assigned Pre-Filter from a User

1. Go to **Configuration** and select **Manage users**.
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

## Related topics

* [Pre-filters](8-6-missions/understanding-the-missions-page/pre-filters/README.md)
* [Set missions display (prefilter)](8-6-missions/understanding-the-missions-page/pre-filters/set-missions-display-prefilter.md)
* [Understanding the Missions Page](8-6-missions/understanding-the-missions-page/README.md)
