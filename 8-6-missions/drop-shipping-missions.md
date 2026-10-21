# Drop Shipping Missions

Drop-shipping missions simplify delivery operations by allowing transporters to deliver parcels directly from suppliers to end customers, without returning to the agency. This method improves efficiency and is particularly suited to logistical scenarios where direct delivery is more practical than traditional models such as cross-docking.

## Before you begin

* Sign in to **Nomadia Delivery** with a user profile that has access to the **Missions** tab.
* Identify the contractor associated with the mission.
* Identify the agency from which the deliverers begin their tour.
* Have the delivery address of the end customer ready.

## Feature overview

* **Drop-Shipping**: The mission type that delivers parcels directly from suppliers to end customers, without returning to the agency.
* **Contractor Identifier**: The drop-down where you select the contractor associated with the mission. The contractor's address is used as the default pickup address.
* **Agency**: The starting point for the deliverers' tour.
* **Optimize**: The action that creates drop-shipping routes, because these missions are managed exclusively through the optimization engine.
* **DROP prefix**: The prefix the application adds to delivery mission numbers in the **Deliveries** panel to differentiate pickup and drop events.
* **Publish to the mobile app**: The toggle that shares the validated route with the driver.
* **Force**: Proceeds with validation when the popup lists conflicts.

## Create a drop-shipping mission

Contractors, transporters, and subcontractors follow these steps to create a drop-shipping mission.

1. Open the Nomadia Delivery application and go to the **Missions** tab.
2. Click on the **Actions menu** and select **Add**.

<figure><img src="../.gitbook/assets/image (75).png" alt=""><figcaption></figcaption></figure>

3. In the Mission Type drop-down, choose **Drop-Shipping.**

<figure><img src="../.gitbook/assets/image (77).png" alt=""><figcaption></figcaption></figure>

4. From the Contractor Identifier drop-down, select the **contractor** associated with the mission.

<figure><img src="../.gitbook/assets/image (78).png" alt=""><figcaption></figcaption></figure>

For drop-shipping missions, the contractor’s address (from contractor configuration) is automatically used as the default pickup address.

<figure><img src="../.gitbook/assets/image (79).png" alt=""><figcaption></figcaption></figure>

5. Select the **Agency** from which the deliverers will begin their tour.

<figure><img src="../.gitbook/assets/image (80).png" alt=""><figcaption></figcaption></figure>

6. Click **Next**.

<figure><img src="../.gitbook/assets/image (81).png" alt=""><figcaption></figcaption></figure>

7. Review the contractor’s address, which the system displays as the pickup location by default.

<figure><img src="../.gitbook/assets/image (82).png" alt=""><figcaption></figcaption></figure>

If needed, click the **Edit** button next to the address field to set a different pickup address.

<figure><img src="../.gitbook/assets/image (83).png" alt=""><figcaption></figcaption></figure>

8. Click **Next** to continue.

<figure><img src="../.gitbook/assets/image (85).png" alt=""><figcaption></figcaption></figure>

9. Enter the **delivery address** of the end customer in the address section.

<figure><img src="../.gitbook/assets/image (86).png" alt=""><figcaption></figcaption></figure>

10. Click **Add** to create the drop-shipping mission.

<figure><img src="../.gitbook/assets/image (87).png" alt=""><figcaption></figcaption></figure>

### Result

A new mission of type Drop-Shipping is added to the delivery management system.

<figure><img src="../.gitbook/assets/image (88).png" alt=""><figcaption></figcaption></figure>

## Create a drop-shipping mission tour

Drop-shipping missions are exclusively managed through the optimization engine to ensure accuracy and strict compliance with the delivery chain. Manual route planning is restricted to preserve workflow integrity.

Deliveries are permitted only after all pickups are completed, preventing disruptions or errors.

1. Select the missions you have created, open the **Actions** menu, and choose **Optimize** to perform a batch optimization.

<figure><img src="../.gitbook/assets/image (89).png" alt=""><figcaption></figcaption></figure>

2. Define the optimization scope by selecting the date range, team, and vehicles, then click **Optimize**.

<figure><img src="../.gitbook/assets/image (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

3. Once you are satisfied, click **stop to see the result**.

<figure><img src="../.gitbook/assets/image (92).png" alt=""><figcaption></figcaption></figure>

4. Review the optimization summary and click **Display the simulation** to analyze the results.

<figure><img src="../.gitbook/assets/image (93).png" alt=""><figcaption></figcaption></figure>

5. Alternatively, click **Validate routes** to publish the results directly without reviewing them.
6. In the **Deliveries** panel, note that the application prefixes all delivery mission numbers with **DROP** to differentiate pickup and drop events.

<figure><img src="../.gitbook/assets/image (94).png" alt=""><figcaption></figcaption></figure>

7. In the **Routes** panel, select the routes you want to validate, open the **Actions** menu, and click **Validate**.

<figure><img src="../.gitbook/assets/image (95).png" alt=""><figcaption></figcaption></figure>

8. Click **OK** to confirm validation.

<figure><img src="../.gitbook/assets/image (96).png" alt=""><figcaption></figcaption></figure>

9. Check the confirmation notification displayed after validation.

<figure><img src="../.gitbook/assets/image (97).png" alt=""><figcaption></figcaption></figure>

10. At the bottom of the popup, enable the **Publish to the mobile app** toggle if you want to share the route with the driver.

<figure><img src="../.gitbook/assets/image (98).png" alt=""><figcaption></figcaption></figure>

11. If conflicts occur, the popup lists all problems detected. In such cases, click **Force** to proceed with validation.

### Result

The validated route with drop-shipping missions is published to the mobile app.

<figure><img src="../.gitbook/assets/image (100).png" alt=""><figcaption></figcaption></figure>

Transporters can create routes that start from the agency, pick up parcels directly from the contractor (supplier) location, and deliver them to end customers. Unlike cross-docking missions, these routes do not require returning to the agency after the pickups are completed.

## Tips

{% hint style="info" %}
**Contractor address**: The contractor's address from the contractor configuration is used as the default pickup address. Click **Edit** next to the address field to set a different one.
{% endhint %}

{% hint style="warning" %}
**Optimization only**: Drop-shipping missions are managed exclusively through the optimization engine, and manual route planning is restricted. Deliveries are permitted only after all pickups are completed.
{% endhint %}

## Related topics

* [Missions](README.md)
* [Cross Docking Missions](cross-docking-missions.md)
