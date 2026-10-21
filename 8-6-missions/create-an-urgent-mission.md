# Create an Urgent Mission

Urgent missions follow a "Chained" model where a pickup is immediately followed by a delivery for the same order, like on-demand food or healthcare delivery. This feature ensures a strict 1-to-1 sequence of operations and uses a dedicated assignment workflow for available drivers.

## Create an urgent mission

1. Open the **mission creation screen**.
2. Select the **mission type Chained Pickup** and **Delivery**.

<figure><img src="../.gitbook/assets/image (9) (1).png" alt=""><figcaption></figcaption></figure>

3. Enter the **Pickup Information (Origin)**.
4. Enter the **Delivery Information (Destination)**.

<figure><img src="../.gitbook/assets/image (131) (1).png" alt=""><figcaption></figcaption></figure>

5. Select the **created mission** from the list.
6. Click the **Assign** Urgent Mission button.

<figure><img src="../.gitbook/assets/image (132) (1).png" alt=""><figcaption></figcaption></figure>

### Result

The new pickup mission is dynamically added to the existing route.

When you create an urgent pickup mission, the system **automatically adds it to a driver’s current route** without needing manual planning.

* The system checks:
  * Which driver is nearby
  * Which route can handle the new pickup
* It then **inserts the pickup at the best position in the route**

<figure><img src="../.gitbook/assets/image (133) (1).png" alt=""><figcaption></figcaption></figure>

## Related topics

* [Missions](README.md)
* [Create an Urgent Pickup Mission](create-an-urgent-pickup-mission.md)
