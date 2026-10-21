# Declaring Parcel for a container mission

The parcel declaration feature allows dispatchers to define and assign parcel dimensions and container structures to container missions in Nomadia Delivery. This ensures accurate capacity planning and seamless logistics execution during container missions. Users can declare parcels when adding a new mission, editing an existing container, or directly from the action panel.

## Before you begin

Prerequisites and requirements:

* Access to the **Mission** module in Nomadia Delivery.
* An active container mission configuration.
* Parcel dimensions including length, width, height, and weight.

Setup steps:

1. Navigate to the **Mission** menu.

![Navigate to the Mission menu](.gitbook/assets/DeclareParcels_BeforeBegin_001.gif)

2. Click on **Actions** to open mission settings.

![Click on Actions to open mission settings](.gitbook/assets/DeclareParcels_BeforeBegin_002.gif)

## Feature overview

* **Actions Menu**: Displays mission configuration tools including mission creation and parcel declaration.
* **Add Button**: Launches the creation interface for adding a new container mission.
* **Agency Field**: Sets the managing organizational unit for the mission.
* **Mission Type Field**: Specifies the category and operational model of the container mission.
* **Container Type Selector**: Sets the container format for parcel generation.
* **Address Field**: Assigns the operational location for the container mission.
* **Parcel Section**: Collects length, width, height, and weight values for declared parcels.
* **Parcel Size Section**: Defines the total number of child parcels to generate.
* **Edit Button**: Opens configuration parameters for existing containers.
* **Declare Parcel Option**: Directly opens the parcel creation tool from the action panel.
* **Validate Button**: Saves configurations and generates requested containers.

## Declare a parcel while adding a mission

1. Open the **Mission** menu.

![Open the Mission menu](.gitbook/assets/DeclareParcels_BeforeBegin_002.gif)

2. Click on **Add**.

![Click on Add](.gitbook/assets/DeclareParcels_DeclareParcelWhileAdding_001.gif)

3. Select the **Agency** and **Mission Type**.

![Select the Agency and Mission Type](.gitbook/assets/DeclareParcels_DeclareParcelWhileAdding_002.gif)

4. Click on **Next**.

![Click on Next](.gitbook/assets/DeclareParcels_DeclareParcelWhileAdding_003.gif)

5. Select the **Container Type**.

![Select the Container Type](.gitbook/assets/DeclareParcels_DeclareParcelWhileAdding_004.gif)

6. Select the **Address**.

![Select the Address](.gitbook/assets/DeclareParcels_DeclareParcelWhileAdding_005.gif)

7. Select the required **Custom Fields**.

![Select the required Custom Fields](.gitbook/assets/DeclareParcels_DeclareParcelWhileAdding_006.gif)

8. Enter length, width, height, and weight in the **Parcel Section**.

![Enter length, width, height, and weight in the Parcel Section](.gitbook/assets/DeclareParcels_DeclareParcelWhileAdding_007.gif)

9. Select the total number of parcels to create in the **Parcel Size Section**.

![Select the total number of parcels to create in the Parcel Size Section](.gitbook/assets/DeclareParcels_DeclareParcelWhileAdding_008.gif)

10. Click on **Create**.

![Click on Create](.gitbook/assets/DeclareParcels_DeclareParcelWhileAdding_009.gif)

11. Click on **Add** to finish creating the parent and child containers.

![Click on Add to finish creating the parent and child containers](.gitbook/assets/DeclareParcels_DeclareParcelWhileAdding_010.gif)

## Declare a parcel while editing a container

1. Click on the **Edit Button** for the target container.

![Click on the Edit Button for the target container](.gitbook/assets/DeclareParcels_DeclareParcelWhileEditing_001.gif)

2. Click on the **Container Type Palette**.

![Click on the Container Type Palette](.gitbook/assets/DeclareParcels_DeclareParcelWhileEditing_002.gif)

3. Set the total number of parcels to create.

![Set the total number of parcels to create](.gitbook/assets/DeclareParcels_DeclareParcelWhileEditing_003.gif)

4. Click on **Create**.

![Click on Create](.gitbook/assets/DeclareParcels_DeclareParcelWhileEditing_004.gif)

5. Click on **Validate** to save the declared containers.

![Click on Validate to save the declared containers](.gitbook/assets/DeclareParcels_DeclareParcelWhileEditing_005.gif)

## Declare a parcel from the action panel

1. Select the parent container and mission, then click on **Actions**.

![Select the parent container and mission, then click on Actions](.gitbook/assets/DeclareParcels_DeclareParcelActionPanel_001.gif)

2. Click on **Declare Parcel**.

![Click on Declare Parcel](.gitbook/assets/DeclareParcels_DeclareParcelActionPanel_002.gif)

3. Choose the **Container Type**.

![Choose the Container Type](.gitbook/assets/DeclareParcels_DeclareParcelActionPanel_003.gif)

4. Click **add a parcel**.

![Click add a parcel](.gitbook/assets/DeclareParcels_DeclareParcelActionPanel_004.gif)

5. Click on **Validate** to confirm.

![Click on Validate to confirm](.gitbook/assets/DeclareParcels_DeclareParcelActionPanel_005.gif)

## Tips

{% hint style="info" %}
**Parent and Child Structure**: Generating multiple parcels automatically links child containers to one parent container for simplified mission organization.
{% endhint %}

{% hint style="info" %}
**Action Panel Convenience**: Add extra parcels directly from the action panel without re-entering the mission creation workflow.
{% endhint %}

## Related topics

* [Container child missions](manage-container-types/container-child-missions.md)
* [Child to Parent Inheritance](childtoparentinheritance/childtoparentinheritance.md)
* [Adding a Mission](8-6-missions/adding-a-mission-beta/README.md)
