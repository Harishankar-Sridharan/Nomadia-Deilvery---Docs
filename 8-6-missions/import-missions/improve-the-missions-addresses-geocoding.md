# Improve the Missions addresses geocoding

Use this process to improve the geocoding of mission addresses during import. It is applicable only when the pickup address or delivery address is selected for importing the location indicators instead of mapping the latitude and longitude fields.

## Before you begin

* Start an import from the Missions page, as described in Import Missions, and reach the location indicator mapping section.
* Select the **Pickup Address** or **Delivery Address** for the location indicators instead of mapping the latitude and longitude fields. This process does not apply otherwise.

## Feature overview

* **Pickup Address / Delivery Address**: The address fields you select in the location indicator mapping section.
* **Validate**: Processes the selected address fields and geocodes them automatically.
* **Geocoding Status bar**: Displays the missions that have been geocoded at different geocoding levels.
* **Adjust Address**: Opens the correction options at the bottom of the map for addresses that are not geocoded correctly.
* **city-level Geocoded Missions / Non-geocoded Missions**: The mission groups you can select to correct.
* **New Address**: The field where you enter the updated address.
* **Import**: Imports the missions once the address validation is completed.

## Improve the geocoding of mission addresses

1. Select the **Pickup Address** or **Delivery Address** in the location indicator mapping section.
2. Click **Validate** to process the selected address fields.

<figure><img src="../../.gitbook/assets/msedge_7rbNCaTtlu.png" alt=""><figcaption></figcaption></figure>

3. Check that Nomadia Delivery automatically geocodes the selected addresses during the validation process. The generated latitude and longitude values are used as the mission location coordinates.
4. Review the **Geocoding Status** bar, which displays the missions that have been geocoded at different geocoding levels.

<figure><img src="../../.gitbook/assets/msedge_yWRBwQML3t.png" alt=""><figcaption></figcaption></figure>

5. If some mission addresses are not geocoded correctly, click **Adjust Address** at the bottom of the map.
6. Select either the **city-level Geocoded Missions** or **Non-geocoded Missions**.
7. Enter the updated address in the **New Address** field. The updated location is displayed on the map, and a confirmation popup stating **New location validated** is displayed.
8. Once the address validation is completed, click **Import** to import the missions.

<figure><img src="../../.gitbook/assets/msedge_ZFqV7jVaxM.png" alt=""><figcaption></figcaption></figure>

## Tips

{% hint style="info" %}
**Review the Geocoding Status bar**: After you click **Validate**, check the bar to see which missions are geocoded and at which level, then correct the others with **Adjust Address**.
{% endhint %}

{% hint style="warning" %}
**Applies to addresses only**: This process is applicable only when the pickup address or delivery address is selected for the location indicators instead of the latitude and longitude fields.
{% endhint %}

## Related topics

* [Import Missions](README.md)
* [Map the addresses fields from the global address list](../map-the-addresses-fields-from-the-global-address-list.md)
