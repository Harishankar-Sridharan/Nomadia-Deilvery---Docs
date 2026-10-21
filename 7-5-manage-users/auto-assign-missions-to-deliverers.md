# Auto-Assign Missions to Deliverers

The auto-assignment feature in Nomadia Delivery simplifies dispatching by automatically assigning missions to the right deliverers and vehicles based on predefined spatial or postal zones. This reduces manual effort, minimizes administrative workload, and improves efficiency, particularly in high-volume operations.

## Before you begin

* To use automatic mission assignments, you must have a postal code zone or a spatial zone configured in advance. For step-by-step guidance, refer to the Zone Creation by Automatic Sectorization guide.

## Link zones with users and vehicles

1. Open the Nomadia Delivery application and go to the **Configuration** tab.
2. Select **Manage users** from the drop-down.
3. Click the **Pencil** icon next to the desired mobile user.

<figure><img src="../.gitbook/assets/image (113).png" alt=""><figcaption></figcaption></figure>

4. Click **Agencies** and **zones** to set up zone assignments. Users with mobile access see this additional tab for configuring zone rights.
5. Move the available zones of the associated agencies to the right-hand panel to assign them to the user.

<figure><img src="../.gitbook/assets/image (114).png" alt=""><figcaption></figcaption></figure>

6. Click **Save** to confirm the changes after adjusting the zone settings.

<figure><img src="../.gitbook/assets/image (115).png" alt=""><figcaption></figcaption></figure>

### Result

If the user is linked to a vehicle, all zone settings automatically synchronize with that vehicle.

<figure><img src="../.gitbook/assets/image (116).png" alt=""><figcaption></figcaption></figure>

## Assign missions automatically

Once users and vehicles are properly synchronized with their zone settings, missions are automatically assigned based on spatial alignment. If a mission's pickup or delivery location falls within a configured zone, the corresponding user or vehicle linked to that zone is automatically assigned, and the **Scheduled Deliverer** field is updated.

<figure><img src="../.gitbook/assets/image (118).png" alt=""><figcaption></figcaption></figure>

If multiple users share the same zone, the system assigns the mission to the first user.

<figure><img src="../.gitbook/assets/image (119).png" alt=""><figcaption></figcaption></figure>

## Optimize auto-assigned missions

During optimization, the planner has three options:

* Use only the auto-assigned scheduled deliverer.
* Allow all compatible vehicles to be considered for optimization.
* Ignore the auto-assigned deliverers.

<figure><img src="../.gitbook/assets/WINWORD_vJHdxLRpDq.png" alt=""><figcaption></figcaption></figure>

## Tips

{% hint style="info" %}
**Mobile access only**: Zones can only be associated with users who have mobile access.
{% endhint %}

{% hint style="warning" %}
**Different zones for users and vehicles**: Nomadia Delivery also allows users and vehicles to be assigned to different zones in exceptional cases, such as sick leave or sudden unavailability. In such scenarios, a synchronization error appears in the vehicle's General section.
{% endhint %}

<figure><img src="../.gitbook/assets/image (117).png" alt=""><figcaption></figcaption></figure>

## Related topics

* [Manage Users](README.md)
* [Enabling Mobile Access](enabling-mobile-access.md)
* [Manage Postal Zones](../manage-studies-and-zones/manage-postal-zones.md)
* [Create Postal Zones by Territory Management (Sectorization)](../manage-studies-and-zones/create-postal-zones-by-territory-management-sectorization.md)
