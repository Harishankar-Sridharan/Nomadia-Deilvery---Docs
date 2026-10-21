# Customize the Status Hierarchy

This feature allows dispatchers to manage how status changes on child missions affect parent containers. It ensures accurate real-time tracking across your logistics operations. Customize status priorities easily to streamline container state synchronization.

## Before you begin

Before you begin, ensure you meet the following prerequisites:

This feature is enabled exclusively for accounts configured in No Route mode.

* Create a parent container in the system.
* Create a child container.

## Feature overview

* **Container types**: Selects the container category you want to configure.
* **Identifier name**: Specifies the unique name to identify the container type.
* **Fetch status from child missions**: Enables retrieving status updates from child missions.
* **Manage status hierarchy**: Opens the status prioritize interface to arrange priorities.

Follow these initial setup steps:

1. Navigate to the **Configuration** menu.

![Navigate to the Configuration menu](../../.gitbook/assets/StatusHierarchy_FeatureOverview_001.png)

2. Select **Container types.**

![Select Container types](../../.gitbook/assets/StatusHierarchy_FeatureOverview_001.png)

3. Scroll down to select the correct **Identifier name.**

<figure><img src="../../.gitbook/assets/StatusHierarchy_FeatureOverview_002.png" alt="Scroll down to select the correct Identifier name"><figcaption></figcaption></figure>

4. Locate the **Fetch status from child missions** option in the bottom right corner.

![Locate the Fetch status from child missions option in the bottom right corner](../../.gitbook/assets/StatusHierarchy_FeatureOverview_003.png)

5. Check if the option is enabled.

![Check if the option is enabled](../../.gitbook/assets/StatusHierarchy_FeatureOverview_004.png)

6. Click on **Manage status hierarchy** once the option is enabled.

![Click on Manage status hierarchy once the option is enabled](../../.gitbook/assets/StatusHierarchy_FeatureOverview_005.png)

## Customize status hierarchy

1. Open the status hierarchy configuration window.

![Open the status hierarchy configuration window](../../.gitbook/assets/StatusHierarchy_FeatureOverview_005.png)

2. Drag the desired status to the top priority position.

* The status on top is considered as the priority status for the container if the child has several different statuses

3. Click on **Done**.

![Click on Done](../../.gitbook/assets/StatusHierarchy_CustomizeStatusHierarchy_001.gif)

4. Click **Save**.

![Click Save](../../.gitbook/assets/StatusHierarchy_CustomizeStatusHierarchy_002.png)

5. Go to **Missions**.

![Go to Missions](../../.gitbook/assets/StatusHierarchy_CustomizeStatusHierarchy_003.png)

6. Click any **Child container** (individual missions connected to the parent container).

![Click any Child container](../../.gitbook/assets/StatusHierarchy_CustomizeStatusHierarchy_004.png)

7. Change the status.

![Change the status](../../.gitbook/assets/StatusHierarchy_CustomizeStatusHierarchy_005.png)

8. Click on Save.

![Click on Save](../../.gitbook/assets/StatusHierarchy_CustomizeStatusHierarchy_006.png)

9. The container's status is determined by the status hierarchy defined on its container type.

### Result

**Example**: Only statuses that are part of the hierarchy are passed to the parent. If a status is not in the hierarchy, the mission keeps its previous status.

![Example: Only statuses that are part of the hierarchy are passed to the parent](../../.gitbook/assets/StatusHierarchy_CustomizeStatusHierarchy_007.png)

## Tips

{% hint style="info" %}
**Status Prioritization**: Drag any status to the top of the list to easily set its priority.
{% endhint %}

{% hint style="warning" %}
**Enable Fetch Status**: Enable **Fetch status from child missions** first, or the **Manage status hierarchy** option will not be visible.
{% endhint %}

## Related topics

* [Customizing Workflow](customize-work-flow.md)
* [No Route Mode](README.md)
* [Child to Parent Inheritance](../../childtoparentinheritance/childtoparentinheritance.md)
