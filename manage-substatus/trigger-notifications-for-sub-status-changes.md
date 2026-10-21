# Trigger Notifications for Sub Status Changes

The Trigger Notifications for Sub-Status Changes feature enables accurate, real-time communication with all stakeholders involved in parcel movement. It improves transparency, coordination, and overall service quality across first-mile, mid-mile, and last-mile operations.

## Feature overview

Notifications can be made for the following recipients:

* **Sender**: The original sender of the mission. Notifications are sent to the contractor's email address or mobile number stored in the mission details.
* **Consignee**: The original recipient of the mission (customer). Notifications are sent to the delivery email address or mobile number stored in the mission details.
* **Other Recipients**: Internal stakeholders such as dispatch or logistics teams. This field accepts multiple email addresses or phone numbers, separated by commas. This field is enabled only when **Other Recipients** is selected in the **Recipient** column.

## Configure notifications for sub-status changes

1. Open the Nomadia Delivery application and go to the **Configuration** tab.

<figure><img src="../.gitbook/assets/image (5) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

2. Select **Sub-statuses** from the list.

<figure><img src="../.gitbook/assets/image (6) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

3. Click the **Pencil** icon next to the existing sub-status to edit it.

<figure><img src="../.gitbook/assets/image (7) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

4. Locate the Custom Messages Configuration section at the bottom of the page.

<figure><img src="../.gitbook/assets/image (8) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

5. Click the **+** button to add the notification configuration to the sub status.

<figure><img src="../.gitbook/assets/image (9) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

6. Select the recipient: **Sender**, **Consignee**, or **Other Recipients**.

<figure><img src="../.gitbook/assets/image (10) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

7. Select a **recipient**, **message type** (Email or SMS), and **message template** to create the notification configuration.

<figure><img src="../.gitbook/assets/image (11) (1) (1).png" alt=""><figcaption></figcaption></figure>

8. If you selected **Other Recipients**, enter multiple email addresses or phone numbers in the Other Recipients field, separated by commas.

<figure><img src="../.gitbook/assets/image (12) (1) (1).png" alt=""><figcaption></figcaption></figure>

9. Click **Save** to apply and store the changes.

<figure><img src="../.gitbook/assets/image (13) (1) (1).png" alt=""><figcaption></figcaption></figure>

### Result

When the mobile user triggers a sub-status, all configured recipients automatically receive the update via Email or SMS at the same time, providing real-time information on the mission's movement.

<figure><img src="../.gitbook/assets/image (14) (1) (1).png" alt=""><figcaption></figcaption></figure>

## Tips

{% hint style="info" %}
**Message templates**: Only **custom message templates** are supported for this case.
{% endhint %}

## Related topics

* [Manage Substatus](README.md)
* [Creating a Substatus](creating-a-substatus.md)
* [Manage Notifications](../manage-notifications/README.md)
* [Customize Email Templates](../manage-notifications/customize-email-templates/README.md)
