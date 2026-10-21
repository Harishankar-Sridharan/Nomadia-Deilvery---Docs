# Create an Urgent Mission

Urgent missions follow a "Chained" model where a pickup is immediately followed by a delivery for the same order, like on-demand food or healthcare delivery. This feature ensures a strict 1-to-1 sequence of operations and uses a dedicated assignment workflow for available drivers.

## Before you begin

* Sign in to **Nomadia Delivery** with a user profile that has access to missions.
* Have the pickup (origin) and delivery (destination) details for the order ready.
* Open the **mission creation screen**.

## Feature overview

* **Chained Pickup and Delivery**: The mission type in which a pickup is immediately followed by a delivery for the same order.
* **Pickup Information (Origin)**: The section where you enter the pickup details.
* **Delivery Information (Destination)**: The section where you enter the delivery details.
* **Assign Urgent Mission**: The button that assigns the created mission to an available driver.

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

## Tips

{% hint style="info" %}
**Automatic route insertion**: The system automatically adds the pickup to a driver's current route without manual planning. It checks which driver is nearby and which route can handle the pickup, then inserts it at the best position.
{% endhint %}

{% hint style="info" %}
**Strict sequence**: Urgent missions follow a strict 1-to-1 sequence of operations, where a pickup is immediately followed by a delivery for the same order.
{% endhint %}

## Related topics

* [Missions](README.md)
* [Create an Urgent Pickup Mission](create-an-urgent-pickup-mission.md)
