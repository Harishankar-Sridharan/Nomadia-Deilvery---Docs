# Adding a Mission

The Add interface introduces a simplified, single-page mission creation experience in Nomadia Delivery. It is designed to minimize repetitive steps and improve clarity. It replaces the traditional multi-step wizard with a unified view that brings together all mission parameters, constraints, and dependencies in one place.

## Before you begin

* Sign in to **Nomadia Delivery** with a user profile that has access to the **Configuration** tab.
* Identify the **Mission Type** and the **Agency** for which you want to configure mission creation.
* Create the custom fields you want to display in the mission form, if you plan to arrange custom field groups.

## Feature overview

* **Custom Field Grouping**: Custom fields can now be grouped under a defined group name. During mission creation, these fields are displayed together under their respective group.
* **Group Ordering**: Custom field groups can be reordered using drag-and-drop while creating or editing a configuration.
* **Sorting Fields Within Groups**: Custom fields can be sorted based on Name or Identifier for custom ordering.
* **Custom Fields for Parcels**: Custom fields can now be associated with individual parcels when duplicating missions.
* **Group Missions in a Container**: Duplicated missions can be grouped within a parent container.
* **Immediate Document Attachment**: The Add Document page appears immediately after mission creation to attach documents.

## Arrange custom field groups in the desired order

1. Launch the Nomadia Delivery application and click the **Configuration** tab from the top navigation bar.

<figure><img src="../../.gitbook/assets/image (17) (1).png" alt=""><figcaption></figcaption></figure>

2. Inside Configuration, select the **Missions** tab. This section displays all mission-related settings.

<figure><img src="../../.gitbook/assets/image (25) (1).png" alt=""><figcaption></figcaption></figure>

3. Click the **Actions** button (top right or toolbar) and select **Add** to create a new mission configuration.

<figure><img src="../../.gitbook/assets/image (26) (1).png" alt=""><figcaption></figcaption></figure>

4. Select the appropriate **Mission Type** from the dropdown.
5. Choose the relevant **Agency** for which the mission applies.
6. Review the selected details and click **Next** to proceed to configuration settings.

<figure><img src="../../.gitbook/assets/image (27) (1).png" alt=""><figcaption></figcaption></figure>

7. Click the **Pencil (Edit) icon** in the configuration screen. This enables editing of fields and display settings.

<figure><img src="../../.gitbook/assets/image (29) (1).png" alt=""><figcaption></figcaption></figure>

8. Expand the **Custom fields** accordion. All custom field groups are displayed as separate accordions.
9. Click a group to expand it. Fields belonging to that group are listed.
10. Choose the required fields to display (for example, address, contact, delivery notes). The mission form updates automatically based on the selected fields.

<figure><img src="../../.gitbook/assets/image (29) (1).png" alt=""><figcaption></figcaption></figure>

11. Use drag and drop to reorder custom field groups and control how they appear in the mission creation form.

<figure><img src="../../.gitbook/assets/image (33) (1).png" alt=""><figcaption></figcaption></figure>

12. To change field order within a group, enable fields using identifier or name.

<figure><img src="../../.gitbook/assets/image (34) (1).png" alt=""><figcaption></figcaption></figure>

13. Toggle required fields as needed to configure mandatory fields.

<figure><img src="../../.gitbook/assets/image (35) (1).png" alt=""><figcaption></figcaption></figure>

14. Click **Save** to apply changes.

<figure><img src="../../.gitbook/assets/image (36) (1).png" alt=""><figcaption></figcaption></figure>

You can use the same procedure to activate custom fields for parcels.

## Group missions within a container

1. Open the Nomadia Delivery application and navigate to the **Configuration** tab.
2. Go to the **Missions** tab.
3. Click **Actions → Add (beta)**.
4. Choose the mission type and agency, then click **Next**.
5. Click the **Pencil icon** to edit the mission configuration.
6. From **Group your parcels**, select one of the following options:
   * **Yes**: Automatically group missions when multiple parcels are added.
   * **No**: Do not group missions.
   * **Optional**: Let the user decide during mission creation.

<figure><img src="../../.gitbook/assets/image (37) (1).png" alt=""><figcaption></figcaption></figure>

7. If you selected **Yes**, choose the default container type. Only aggregable containers are displayed.

<figure><img src="../../.gitbook/assets/image (38) (1).png" alt=""><figcaption></figcaption></figure>

8. Click **Save** to apply changes.

<figure><img src="../../.gitbook/assets/image (36) (1).png" alt=""><figcaption></figcaption></figure>

## Add documents right after mission creation

1. Open the Nomadia Delivery application and navigate to the **Configuration** tab.
2. Go to the **Missions** tab.
3. Click **Actions → Add (beta)**.
4. Select the mission type and agency, then click **Next**.
5. Click the **Pencil icon** to edit the configuration.
6. Enable the **Add documents** toggle.

<figure><img src="../../.gitbook/assets/image (40) (1).png" alt=""><figcaption></figcaption></figure>

7. Click **Save** to apply changes.

<figure><img src="../../.gitbook/assets/image (36) (1).png" alt=""><figcaption></figcaption></figure>

8. When the toggle is enabled, the system prompts you to add documents immediately after mission creation. Add documents from one of the following sources:
   * Local computer
   * Document library

<figure><img src="../../.gitbook/assets/image (42) (1).png" alt=""><figcaption></figcaption></figure>

9. Click **Save** to attach documents.

<figure><img src="../../.gitbook/assets/image (43) (1).png" alt=""><figcaption></figcaption></figure>

### Result

Documents are successfully added to the mission.

<figure><img src="../../.gitbook/assets/image (44) (1).png" alt=""><figcaption></figcaption></figure>

## Tips

{% hint style="info" %}
**Same procedure for parcels**: You can use the same procedure that arranges custom field groups to activate custom fields for parcels.
{% endhint %}

{% hint style="warning" %}
**Aggregable containers only**: When you group missions in a container, only aggregable containers are displayed as the default container type.
{% endhint %}

## Related topics

* [Missions](../README.md)
* [Customize the Validation of Mission form fields](customizethevalidationofmissionformfields.md)
* [Grouping Custom Field](../custom-fields/grouping-custom-field.md)
* [Mission Creation Configuration](../mission-creation-configuration.md)
