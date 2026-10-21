# Configuring Mission Visibility

Mission visibility was previously determined mainly by the user’s agency association. To provide greater flexibility and support diverse business needs, visibility restrictions are now extended to include custom field–based rules, in addition to the existing agency-based controls.

## Feature overview

* **Mission visibility toggle**: Enables mission visibility for a mission custom field. It can be activated for only one field at a time, so only one custom field can be used to control mission visibility.
* **Mission Visibility drop-down**: Appears under the Mission section of a user's **Roles & rights** tab. It lets you select the custom field value associated with the selected user.

## Set up a custom field as a mission visibility restriction

1. Open the Nomadia Delivery application and navigate to the **Configuration** tab.

![](<../../.gitbook/assets/image-49 (2).png>)

2. From the list, select **Custom fields**.

![](<../../.gitbook/assets/image-50 (2).png>)

3. Click the **Missions** tab.

![](<../../.gitbook/assets/image-51 (2).png>)

4. Click the **Pencil** icon to edit any existing custom field.

![](<../../.gitbook/assets/image-52 (2).png>)

5. Enable the mission visibility toggle for the field.

![](<../../.gitbook/assets/image-53 (2).png>)

6. Click **Save** to apply the changes.

![](<../../.gitbook/assets/image-54 (2).png>)

## Set mission visibility based on a custom field for users

1. Select the **Manage user’s** menu.

![](<../../.gitbook/assets/image-55 (2).png>)

2. Click the **Pencil** icon to edit the required user.

![](<../../.gitbook/assets/image-56 (2).png>)

3. Open the **Roles & rights** tab.

![](<../../.gitbook/assets/image-57 (2).png>)

4. Under the Mission section, open the new Mission Visibility drop-down to select the value associated with the selected user.

![](<../../.gitbook/assets/image-58 (2).png>)

5. Select the required custom field value and click **Save**.

![](<../../.gitbook/assets/image-59 (2).png>)

6. Log in as the configured user and navigate to the **Missions** tab.

![](<../../.gitbook/assets/image-60 (2).png>)

7. Click the **Prefilter** option.

![](<../../.gitbook/assets/image-61 (2).png>)

### Result

* The prefilter is automatically applied based on the mission visibility custom field and the value configured in the user’s Roles & Rights.
* The mission visibility prefilter is read-only and cannot be modified by the user.
* The mission table displays only the missions that match the mission visibility condition, in addition to the existing agency-based prefilter.

<figure><img src="../../.gitbook/assets/image (4).png" alt=""><figcaption></figcaption></figure>

## Tips

{% hint style="info" %}
**List of Values only**: The toggle is available only for custom fields of the List of Values type.
{% endhint %}

{% hint style="warning" %}
**Administrator required**: To remove or modify the read-only mission visibility prefilter, contact the administrator.
{% endhint %}

## Related topics

* [Custom Fields](../custom-fields.md)
* [Grouping Custom Field](grouping-custom-field.md)
* [Web - Roles and Rights](../../7-5-manage-users/web-roles-and-rights.md)
