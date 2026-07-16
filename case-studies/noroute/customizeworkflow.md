# Customizing Workflow

The customized workflow feature allows you to define how mission statuses progress and who can change them. The configured **user profiles** define who can sign in and perform delivery-related actions, including updating mission statuses. This ensures a structured, secure, and geographically verified delivery process.

#### Getting Started

* Access to the **Configuration** page.
* Administrative permissions to modify system tables.
* Open the **Configuration** page.
* Click on **Customize Status Tables and Workflow**.
* To learn more about customizing labels, refer to the following link

[https://app.gitbook.com/o/oWGpSeZsFYIlc5oQ3d3d/s/OZAbiFSFd1RKuejzxr5e/8-6-missions/customizing-status-labels](../../8-6-missions/customizing-status-labels.md)

* Click the **Workflow** tab.

<figure><img src="../../.gitbook/assets/msedge_9ldIAXlwgI.png" alt=""><figcaption></figcaption></figure>

#### Feature Overview

* **Workflow Mapping**: Define which status can be changed to a specific next status.&#x20;
* **Proximity Toggle**: Check if a deliverer is at the expected location by toggling **Yes** or **No**.&#x20;
* **Profile Definition**: Restrict specific status changes to authorized roles, such as a **Dispatch User**.

#### How To: Customize a Mission Workflow

1. Select a starting status in the workflow grid, such as **Created**.
2. Assign a user role from the **Profile** dropdown to control who can change the status.
3. Select which target statuses the mission can transition to, such as **DAIS collected** or **EXP log collected**.
4. Configure the next transition, such as allowing a **Dispatch User** to scan a mission and change it to **Delivered**.
5. Click on **Save** to modify the changes.

**Note**: The **Workflow** page allows users to configure the mission status flow. they can define which statuses a mission can transition between and specify the **user profiles** that are authorized to perform each status change. This provides complete control over the delivery workflow by ensuring that only designated profiles can execute specific status transitions.

<figure><img src="../../.gitbook/assets/msedge_lDhxFtHrRp.png" alt=""><figcaption></figcaption></figure>

#### Productivity Tips

* ⚠️ **Unsaved Changes**: Always click the Save button after making adjustments to ensure the mission workflow updates.
