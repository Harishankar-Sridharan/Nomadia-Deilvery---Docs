# Inherit mission data from contractor & address list

This feature accelerates mission creation by automatically inheriting custom field data, minimizing manual input. By automatically initializing fields, you don’t need to re-enter the same data during mission creation, which improves consistency and efficiency.

## Before you begin

* Sign in to **Nomadia Delivery** with a user profile that has access to the **Configuration** tab.
* Make sure an existing mission custom field is available to edit.
* Make sure the contractor or address list entry that should provide the value exists.

## Feature overview

* **Can be initialized by**: The drop-down that sets whether a custom field is inherited from the contractor or the address list.
* **Custom Fields for Missions**: The section in the contractor (Custom Fields section) and in the address (Other Data section) that lists the fields missions inherit.
* **Address List tab**: The contractor tab where you edit an address and set its inherited values.

## Enable custom field inheritance

1. Open the Nomadia Delivery application and go to the **Configuration** tab.

![](<../../.gitbook/assets/image-34 (2).png>)

2. Select **Custom fields** from the list.

![](<../../.gitbook/assets/image-35 (2).png>)

3. Select the **Missions** tab.

![](<../../.gitbook/assets/image-36 (2).png>)

4. Click the **Pencil** icon to edit an existing custom field.

![](<../../.gitbook/assets/image-37 (2).png>)

5. From the **Can be initialized by** drop-down, choose whether the field is inherited from the contractor or the address list.

![](<../../.gitbook/assets/image-38 (2).png>)

6. Click the **Save** button to apply the changes.

![](<../../.gitbook/assets/image-39 (2).png>)

## Set inherited values in the contractor and address list

1. From the main header, click the **Contractors** page.

![](<../../.gitbook/assets/image-40 (2).png>)

2. Click the **Pencil** icon to edit the contractor.

![](<../../.gitbook/assets/image-41 (2).png>)

3. In the Custom Fields section, find all fields inherited by missions from the contractor under **Custom Fields for Missions**.

![](<../../.gitbook/assets/image-42 (2).png>)

4. Click the **Address List** tab.

![](<../../.gitbook/assets/image-43 (2).png>)

5. Click the **Pencil** icon to edit an address.

![](<../../.gitbook/assets/image-44 (2).png>)

6. In the Other Data section, find all fields inherited by missions from the address under **Custom Fields for Missions**.

![](<../../.gitbook/assets/image-45 (2).png>)

7. Select a value for the custom field in the contractor or address list, then click **Save** to apply the changes.

![](<../../.gitbook/assets/image-46 (2).png>)

### Result

When you create a mission, the mission custom fields are automatically populated based on the selected contractor or address from the address list.

![](<../../.gitbook/assets/image-48 (2).png>)

## Tips

{% hint style="info" %}
**Both sources**: A custom field can be initialized from both the contractor and the address list at the same time. In such cases, the address list value takes priority over the contractor value.
{% endhint %}

## Related topics

* [Custom Fields](../custom-fields.md)
* [Register a Contractor](../../9-7-contractors/registration.md)
* [Manage Address List](../../9-7-contractors/manage-address-list.md)
