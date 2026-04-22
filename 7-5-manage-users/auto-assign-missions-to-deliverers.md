# Auto-Assign Missions to Deliverers

The auto-assignment feature in Nomadia Delivery simplifies dispatching by automatically assigning missions to the right deliverers and vehicles based on predefined spatial or postal zones. This reduces manual effort, minimizes administrative workload, and improves efficiency, particularly in high-volume operations.

Prerequisite: To use automatic mission assignments, you must have a postal code zone or a spatial zone configured in advance. For step-by-step guidance, refer to the Zone Creation by Automatic Sectorization guide.

Follow the steps below to link zones with users and vehicles:

1. Open the Nomadia Delivery application and go to the **Configuration tab.**
2. From the drop-down, select **Manage users**.

**Note**: Zones can only be associated with users who have mobile access.

3. Click the **Pencil** icon next to the desired mobile user.

<figure><img src="../.gitbook/assets/image (113).png" alt=""><figcaption></figcaption></figure>

4. Users with mobile access will see an additional tab for configuring zone rights. Click **Agencies** and **zones** to set up zone assignments.
5. Move the available zones of the associated agencies to the right-hand panel to assign them to the user.

<figure><img src="../.gitbook/assets/image (114).png" alt=""><figcaption></figcaption></figure>

6. After adjusting the zone settings, click **Save** to confirm the changes.

<figure><img src="../.gitbook/assets/image (115).png" alt=""><figcaption></figcaption></figure>

If the user is linked to a vehicle, all zone settings will automatically synchronize with that vehicle.

<figure><img src="../.gitbook/assets/image (116).png" alt=""><figcaption></figcaption></figure>

Nomadia Delivery also allows users and vehicles to be assigned to different zones in exceptional cases, such as sick leave or sudden unavailability. In such scenarios, a synchronization error will appear in the vehicle’s General section.

<figure><img src="../.gitbook/assets/image (117).png" alt=""><figcaption></figcaption></figure>

Once users and vehicles are properly synchronized with their zone settings, missions are automatically assigned based on spatial alignment. If a mission’s pickup or delivery location falls within a configured zone, the corresponding user or vehicle linked to that zone is automatically assigned, and the Scheduled Deliverer field is updated.

<figure><img src="../.gitbook/assets/image (118).png" alt=""><figcaption></figcaption></figure>

If multiple users share the same zone, the system assigns the mission to the first user.

<figure><img src="../.gitbook/assets/image (119).png" alt=""><figcaption></figcaption></figure>

During optimization, the planner has three options:

* Use only the auto-assigned scheduled deliverer.
* Allow all compatible vehicles to be considered for optimization.
* Ignore the auto-assigned deliverers.

<figure><img src="../.gitbook/assets/WINWORD_vJHdxLRpDq.png" alt=""><figcaption></figcaption></figure>
