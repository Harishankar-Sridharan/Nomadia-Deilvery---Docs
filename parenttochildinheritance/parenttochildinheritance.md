# Parent to Child Inheritance

The **Parent to Child Inheritance** feature automatically synchronizes settings from a parent container to its child containers. This eliminates the need to manually update each individual child container. Enable this to save time and ensure data consistency across your fleet.

## Before you begin

Prerequisites and system requirements:

* Active account in **Nomadia Delivery** with **Configuration** panel access.
* Parent and child containers configured with correct identifiers.

Steps:

1. Navigate to the **Configuration** menu.
2. Click on **Container Types**.

![Click on Container Types](../.gitbook/assets/ParentToChildInheritance_BeforeBegin_001.gif)

## Feature overview

* **Inherit sub status to child missions:** This toggle switch automatically passes parent container status to child containers.
* **Sub-status inheritance:** Sub-statuses can be inherited by child containers in the same way as statuses.
* **Pallet and Pencil icons:** The pallet icon opens configuration options for a specific container type, and the pencil icon opens the configuration mode for a mission.
* **Inherit attributes to child missions:** This setting automatically copies parent details to child containers.
* **Inherit documents to child missions**: This option automatically shares parent documents with child containers.

## Inherit status and sub-status

1. Navigate to the **Configuration** menu.

![Navigate to the Configuration menu](../.gitbook/assets/ParentToChildInheritance_BeforeBegin_001.gif)

2. Click on **Container Types**.
3. Scroll down to find the correct identifier.
4. Edit any container type from the list.
5. Toggle **Inherit sub status to child missions** to **Yes**.
6. Select the status that needs to be inherited, such as **Out for delivery** and **To be loaded**.

![Select the status that needs to be inherited, such as Out for delivery](../.gitbook/assets/ParentToChildInheritance_StatusSubStatus_001.png)

7. Click on the **Save** button.

![Click on the Save button](../.gitbook/assets/ParentToChildInheritance_StatusSubStatus_002.png)

8. Go to **Missions**.
9. Click the **Pencil icon** next to the parent container mission.
10. Change the **Mission status** to the status configured in container types, such as **Out for delivery**.

![Change the Mission status to the status configured in container types](../.gitbook/assets/ParentToChildInheritance_StatusSubStatus_003.png)

11. Click on **Save**.

### Result

The status has been updated for all child missions.

![The status has been updated for all child missions](../.gitbook/assets/ParentToChildInheritance_StatusSubStatus_004.png)

## Inherit attributes to child containers

1. Navigate to **Configuration**.
2. Click on **Container Types**.
3. Toggle **Inherit attributes to child missions** to enable it.
4. Click on **Save**.

![Click on Save](../.gitbook/assets/ParentToChildInheritance_InheritAttributesChildContainers_001.png)

5. Go to **Missions**.
6. Click the **Parent container**.
7. Correct the **Address** if it is wrong.
8. Click on **Save**.

![Click on Save](../.gitbook/assets/ParentToChildInheritance_InheritAttributesChildContainers_002.png)

### Result

Only the address has been updated for all child missions. The status is not updated when attributes are inherited.

<figure><img src="../.gitbook/assets/ParentToChildInheritance_InheritAttributesChildContainers_003.png" alt="Only the address has been updated for all child missions"><figcaption></figcaption></figure>

## Inherit documents to child containers

1. Navigate to **Configuration**.
2. Click on **Container Types**.
3. Toggle **Inherit documents to child missions** to enable it.

![Toggle Inherit documents to child missions to enable it](../.gitbook/assets/ParentToChildInheritance_InheritDocumentsChildContainers_001.png)

4. Click on **Save**.

![Click on Save](../.gitbook/assets/ParentToChildInheritance_InheritDocumentsChildContainers_002.png)

5. Go to **Missions**.
6. Click the **Parent container**.

![Click the Parent container](../.gitbook/assets/ParentToChildInheritance_InheritDocumentsChildContainers_003.gif)

7. Click **Browse the computer**.
8. Select the **PDF** file.

![Select the PDF file](../.gitbook/assets/ParentToChildInheritance_InheritDocumentsChildContainers_004.gif)

9. Click **Save** to complete the upload.

![Click the Save button to complete the upload](../.gitbook/assets/ParentToChildInheritance_InheritDocumentsChildContainers_005.png)

### Result

The document appears in the child container.

<figure><img src="../.gitbook/assets/ParentToChildInheritance_InheritDocumentsChildContainers_006.png" alt="The document will be reflected in the child container"><figcaption></figcaption></figure>

## Tips

{% hint style="info" %}
**Automatic Syncing**: Updating parent container status, sub-status, address, or documents automatically updates child containers.
{% endhint %}

## Related topics

* [Child to Parent Inheritance](../childtoparentinheritance/childtoparentinheritance.md)
* [Edit a Container Type](../manage-container-types/edit-a-container-type.md)
* [Group notifications for container missions](../groupnotificationsforthecontainermissions/groupnotificationsforthecontainermissions.md)
