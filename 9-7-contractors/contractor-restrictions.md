# Contractor Restrictions

Contractor Restrictions allow you to precisely control access to templates and mission editing permissions.

## Feature overview

In the **Missions** section of the contractor details, multiple restrictions can be applied to contractors.

* **Mission Extract Template**: Allows users to select only the mission extracted templates applicable to the contractor.
* **Sticker Template**: Allows users to select only the sticker templates applicable to the contractor.
* **Bulk Edit**: Allows users to select only the edit configurations applicable to the contractor.

## Restrict contractors to specific templates

1. Open the Nomadia Delivery application and go to the **Configuration** tab.

![](<../.gitbook/assets/image-67 (2).png>)

2. Click the **Contractors** page from the main header.

![](<../.gitbook/assets/image-68 (2).png>)

3. Click the **Pencil** icon to edit the contractor details.

![](<../.gitbook/assets/image-69 (2).png>)

4. Apply the restrictions in the **Missions** section.

![](<../.gitbook/assets/image-70 (2).png>)

5. Click **Save** to apply the restrictions to the selected contractor.

![](<../.gitbook/assets/image-71 (2).png>)

## Prevent contractors from editing missions after printing

1. Open the Nomadia Delivery application and go to the **Configuration** tab.

![](<../.gitbook/assets/image-72 (2).png>)

2. Select **Manage Users** from the list.

![](<../.gitbook/assets/image-73 (2).png>)

3. Click the **Pencil** icon to edit a contractor user.

![](<../.gitbook/assets/image-74 (2).png>)

4. Click the **Roles & Rights** tab.
5. Disable the **Modify Mission After Printing** right under the **Missions** section.

![](<../.gitbook/assets/image-75 (2).png>)

6. Click **Save** to apply the changes.

![](<../.gitbook/assets/image-76 (2).png>)

7. Go to the **Missions** tab and select any Waiting mission.

![](<../.gitbook/assets/image-77 (2).png>)

8. Click the **Actions** menu and select **Generate Sticker Labels**.

![](<../.gitbook/assets/image-78 (2).png>)

9. Click the **Print** button to generate the sticker.

![](<../.gitbook/assets/image-79 (2).png>)

10. Click the **Pencil** icon to edit the mission after printing.

![](<../.gitbook/assets/image-77 (2).png>)

### Result

A warning appears in the mission editor, and mission editing is blocked because the user does not have permission to modify it after sticker printing.

![](<../.gitbook/assets/image-81 (2).png>)

This ensures better traceability and protects mission data once documents are generated.

## Related topics

* [Contractors](README.md)
* [Register a Contractor](registration.md)
* [Create a Contractor User](a-configuration-user-type.md)
* [Customizing Word Templates](../manage-document-templates/customizing-word-templates.md)
