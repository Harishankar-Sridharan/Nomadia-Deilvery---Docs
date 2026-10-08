# Group notifications for container missions

Group notifications for container missions aggregate alerts for several missions simultaneously. Dispatchers use this feature to streamline communications with contractors or other recipients during missions. This setup ensures automated, reliable status updates are delivered directly to stakeholders based on scanning milestones.

#### Getting Started

To use this feature, make sure the following requirements are met:

* Activate this setting to have the parent inherit its status from its child items.
* Make sure each mission has a contractor assigned to it.

Follow these initial steps to access the settings:

1. Navigate to the **Configuration** screen.

![](../.gitbook/assets/groupnotificationsforthecontainermissions-groupnotificationsforthecontainermissions_timestamp_0_to_35.png)

2. Select **Container Types**.

![](../.gitbook/assets/groupnotificationsforthecontainermissions-groupnotificationsforthecontainermissions_timestamp_0_to_45.png)

3. Scroll down to find the correct identifier.

![](../.gitbook/assets/groupnotificationsforthecontainermissions-groupnotificationsforthecontainermissions_timestamp_0_to_51.png)

4. Enable the **Can Aggregate Several Missions** toggle and Status inheritance from child to parent is enabled.

![](../.gitbook/assets/groupnotificationsforthecontainermissions-groupnotificationsforthecontainermissions_timestamp_0_to_51_to_1_to_03.gif)

***

#### Feature Overview

* **Can Aggregate Several Missions**: Turn a mission into a parent container that can hold several other missions.
* **Customer Messages**: Section containing recipient and message configurations. This controls your notification preferences.
* **Recipient**: Selects the recipient for notifications. This defines who receives the alerts.
* **Message Type**: Selects the notification channel. You can choose either SMS or email.
* **Message Template**: Selects a pre-created message layout. This formats your notification text.
* **Status**: Field to select the target status for triggering the message. This defines the status transition.
* **Notification Configuration Type**: Select the template that matches the mission's notification configuration type or its contractor.
* **Other Recipient Email**: Input field to add extra email addresses. This sends notifications to additional stakeholders.
* **First scan:** Triggers the message when the first mission in the container is scanned.
* **Last scan:** Triggers the message when the last mission in the container is scanned.

#### How To: Configure Group Notifications

1. Scroll down to the **Customer Messages** section.

![](../.gitbook/assets/groupnotificationsforthecontainermissions-groupnotificationsforthecontainermissions_timestamp_1_to_17.png)

2. Select a **Recipient**.

![](../.gitbook/assets/groupnotificationsforthecontainermissions-groupnotificationsforthecontainermissions_timestamp_1_to_17.png)

3. Choose SMS or email in **Message Type**.

<figure><img src="../.gitbook/assets/image (238).png" alt=""><figcaption></figcaption></figure>

4. Select your pre-created **Message Template**.
5. Choose the target status to change to in **Status**.
6. Select the **Notification Configuration Type**.
7. Enter additional emails in **Other Recipient Email**.

![](../.gitbook/assets/groupnotificationsforthecontainermissions-groupnotificationsforthecontainermissions_timestamp_2_to_01.png)

8. Click **Save** to complete setup.

![](../.gitbook/assets/groupnotificationsforthecontainermissions-groupnotificationsforthecontainermissions_timestamp_2_to_17.png)

***

#### How To: Trigger Group Notifications

1. Go to the **Configuration** and click **Container types**
2. Click the **Pencil Icon** next to your container type.

<figure><img src="../.gitbook/assets/image (237).png" alt=""><figcaption></figcaption></figure>

3. Change the status from **Created** to a different status.

<figure><img src="../.gitbook/assets/image (236).png" alt=""><figcaption></figcaption></figure>

4. Click **Save** to send the notification.

![](../.gitbook/assets/groupnotificationsforthecontainermissions-groupnotificationsforthecontainermissions_timestamp_2_to_45.png)

Contractor will receive the notification email successfully.

<figure><img src="../.gitbook/assets/image (84).png" alt=""><figcaption></figcaption></figure>

***

#### Productivity Tips

* **Child-Parent Relationships**: Pre-configuring child-parent relationships ensures grouped notifications work correctly.
* **Scan Timing Selection**: Choosing first or last scan delivery optimizes the notification timing based on customer needs.
