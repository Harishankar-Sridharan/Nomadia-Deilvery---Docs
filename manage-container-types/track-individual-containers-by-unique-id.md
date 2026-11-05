# Track Individual Containers by Unique ID

Container tracking lets you follow every container by its unique ID across its full journey. You register each container once, link it to the missions that carry it, and every scan, status change and condition change is recorded in the container's history. Supervisors get a live view of the whole fleet and can quickly find lost or damaged containers. You can also associate containers with vehicles, so that drivers see the containers on board at the start of the route and confirm them in one scan of the vehicle QR code.

## Before you begin

* Sign in to **Nomadia Delivery** with a user profile that has access to **Configuration**.
* Have the unique code of each container available. This is the code printed on the container's barcode or QR label.
* Make sure the container types you need exist. See [Manage Container Types](README.md).

## Feature overview

* **Container list**: The list under **Configuration** that shows every registered container with its code, container type, cost, purchase date, condition, status, last known position, last seen date, active state and holding vehicle.
* **Code**: The unique code of the container, as printed on its barcode or QR label.
* **Recorded in history on save**: The **Condition** (for example **Good** or **Damaged**) and **Status** (for example **Received**, **To be collected** or **Lost**) of the container. They are written to the container's history as soon as you save.
* **Stay in vehicle**: When enabled, the status can only be changed manually (**Received** or **Lost**), and status changes triggered by missions are ignored.
* **Holding vehicle** and **Last known position**: Read-only fields that are updated from the field when drivers scan the container.
* **Tracked container**: The field in the mission form that links the mission to a registered container. The **Scannable container code** field above it is free text and is not checked against the registry.
* **History**: The section of a container that lists every event in its life, with what changed, who recorded it and when.
* **Containers tab**: The tab of a vehicle, under **Configuration** > **Manage the vehicles**, where you choose the containers on board. A container can be associated with only one vehicle at a time.
* **Containers column**: The column of the vehicle import file where you list the container IDs of each vehicle, separated by commas.
* **Print QR codes**: The action that prints the QR code of the selected vehicles, which drivers scan at the start of the route.

## Register a container

1. Under **Configuration**, open the **Container list**. It shows every registered container.

![The Container list under Configuration](../.gitbook/assets/ContainerTracking_001.jpg)

2. Click **Actions**, and then click **Add**.

![Click Actions and then Add](../.gitbook/assets/ContainerTracking_002.jpg)

3. Enter the unique **Code** of the container, the one printed on its barcode or QR label, and then choose the **Container type**.

![Enter the Code and choose the Container type](../.gitbook/assets/ContainerTracking_003.jpg)

4. Enter the **Cost** and **Purchase date**, and then choose the **Condition** and **Status** under **Recorded in history on save**.

![Enter the cost, purchase date, condition and status](../.gitbook/assets/ContainerTracking_004.jpg)

5. Click **Save**.

### Result

A notification confirms that the container was added. The container appears in the **Container list**, ready to be tracked, and its condition and status are written to its history.

![The new container in the Container list](../.gitbook/assets/ContainerTracking_005.jpg)

## Assign a container to a mission

1. Open the mission form and find the **Tracked container** field.

![The Tracked container field in the mission form](../.gitbook/assets/ContainerTracking_006.jpg)

2. Scan or type the container code. Matching containers appear with their type and condition, so a damaged container is easy to spot.

![Matching containers with their type and condition](../.gitbook/assets/ContainerTracking_007.jpg)

3. Select the container, and then save the mission.

![Select the container in the Tracked container field](../.gitbook/assets/ContainerTracking_008.jpg)

### Result

The link is recorded straight away. The container's **History** shows the mission, who made the change and when.

![The container history shows the associated mission](../.gitbook/assets/ContainerTracking_009.jpg)

## Associate containers with a vehicle

1. Go to **Configuration** > **Manage the vehicles**, and then click the fleet tab, for example **DC**.

![The Manage the vehicles page](../.gitbook/assets/ContainersVehicles_001.jpg)

2. Click the **pencil icon** next to the vehicle, and then click the **Containers** tab.

![The Containers tab of a vehicle](../.gitbook/assets/ContainersVehicles_002.jpg)

3. In the **Containers** field, choose the containers on board the vehicle.

![The containers on board the vehicle](../.gitbook/assets/ContainersVehicles_003.jpg)

The list shows the **Holding vehicle** of containers that are already associated with another vehicle, because a container can be on board only one vehicle.

![A container already held by another vehicle](../.gitbook/assets/ContainersVehicles_004.jpg)

4. Click **Save**.

## Associate containers with vehicles in bulk

1. On the **Manage the vehicles** page, click **Actions**, and then click **Import**.

![The vehicle import page](../.gitbook/assets/ContainersVehicles_005.jpg)

2. In your vehicle import file, add a **Containers** column. For each vehicle, enter the container IDs separated by commas. Each container can be listed for only one vehicle. To start from an example, click **See a file template**.

![A vehicle import file with a Containers column](../.gitbook/assets/ContainersVehicles_006.jpg)

3. Drop the file on the import page, or click **Browse (Excel...)** to select it, and then complete the import.

### Result

The containers are associated with the vehicles listed in the file.

## Print the vehicle QR codes

1. On the **Manage the vehicles** page, select the check boxes of the vehicles.
2. Click **Actions**, and then click **Print QR codes**.

![Click Actions and then Print QR codes](../.gitbook/assets/ContainersVehicles_007.jpg)

3. Place each QR code in its vehicle.

### Result

At the start of the route, the driver scans the vehicle QR code in the mobile app. The app lists the containers on board the vehicle, and the driver confirms them in one scan.

![The driver scans the vehicle QR code and confirms the containers on board](../.gitbook/assets/ContainersVehicles_008.jpg)

## View the history of a container

1. In the **Container list**, click the **pencil icon** next to a container to open it.

![The details of a container](../.gitbook/assets/ContainerTracking_010.jpg)

2. Check the **Holding vehicle** and **Last known position** fields to see where the container is right now. They are updated from the field.
3. Scroll down to the **History** section. It lists every event in the container's life. Each driver scan, at reception, at delivery and at pickup, is added automatically.

![The History section of a container](../.gitbook/assets/ContainerTracking_011.jpg)

4. Click **Learn more** on an event to see exactly what changed, the user who recorded it and the timestamp.

![An expanded event in the History section](../.gitbook/assets/ContainerTracking_012.jpg)

## Monitor the container fleet

1. In the **Container list**, review the **Status**, **Last known position**, **Last seen** and **Holding vehicle** columns. They give you a live view of the whole fleet.

![The fleet columns in the Container list](../.gitbook/assets/ContainerTracking_013.jpg)

2. To find a missing container, open the filter of the **Status** column and choose **Lost**.

![Filter the Status column](../.gitbook/assets/ContainerTracking_014.jpg)

The list shows only the lost containers, with their full history one click away.

![The list filtered on lost containers](../.gitbook/assets/ContainerTracking_015.jpg)

3. To list every damaged container that needs attention, filter the **Condition** column on **Damaged**.

![The list filtered on damaged containers](../.gitbook/assets/ContainerTracking_016.jpg)

## Tips

{% hint style="info" %}
**Use the Tracked container field**: Only the **Tracked container** field links a mission to a registered container. The **Scannable container code** field is free text and is not checked against the registry.
{% endhint %}

{% hint style="info" %}
**One vehicle per container**: A container can be on board only one vehicle at a time. Check the **Holding vehicle** shown in the list before you choose a container.
{% endhint %}

## Related topics

* [Manage Container Types](README.md)
* [Adding a Mission](../8-6-missions/adding-a-mission-beta/README.md)
* [Container child missions](container-child-missions.md)
* [Manage Vehicles in a fleet](../manage-vehicle-fleets/manage-vehicles-in-a-fleet.md)
