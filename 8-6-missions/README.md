# Missions

### 1.1. Set missions display (prefilter)

From the Missions page:

1. Click the **"Prefiltered On"** button at the top left.\
   The display of this section may vary based on screen resolution.
2. Choose your filters:
   * **Agency**: Select one or more agencies.
   * **Reference**: Filter by creation date or modification date.
   * **Period**: Choose from options like the last hour, last 24 hours, last 7 days, or set a custom date range.
   * **Display Deleted Missions**: Enable this option to include deleted missions.
3. Click **Apply**.

![](<../.gitbook/assets/image-2 (3) (1).png>)

4. The filtered missions will be displayed on your Missions page.

![](<../.gitbook/assets/image-3 (3) (1).png>)

### 1.2. Pre-filters

The Pre-filters on the Missions Page are dynamic sections that provide users with detailed and contextual information based on their current selection or interaction. These pre-filters enhance navigation and productivity by allowing quick access to relevant data without switching screens.

![](<../.gitbook/assets/image-4 (3) (1).png>)

### 1.3. Default Delivery statuses

Below are an overview of the various mission statuses and their significance:

<table data-header-hidden><thead><tr><th valign="top"></th><th valign="top"></th></tr></thead><tbody><tr><td valign="top">Status</td><td valign="top">Description</td></tr><tr><td valign="top">Waiting</td><td valign="top">The mission is expected but not yet received</td></tr><tr><td valign="top">Received</td><td valign="top">The mission has been successfully received</td></tr><tr><td valign="top">To be Delivered</td><td valign="top">The mission is prepared for delivery</td></tr><tr><td valign="top">To be Loaded</td><td valign="top">The mission is waiting to be loaded.</td></tr><tr><td valign="top">Loaded</td><td valign="top">The package is now loaded and in transit</td></tr><tr><td valign="top">To be Picked up</td><td valign="top">Mission is scheduled and awaiting pick up</td></tr><tr><td valign="top">Picked up</td><td valign="top">Item has been collected from the origin</td></tr><tr><td valign="top">Delivered</td><td valign="top">The delivery is completed successfully.</td></tr><tr><td valign="top">Not Received</td><td valign="top">Indicates a mission was expected but couldn’t be received</td></tr><tr><td valign="top">Not Loaded</td><td valign="top">The mission couldn’t be loaded as expected</td></tr><tr><td valign="top">Not Picked up</td><td valign="top">Scheduled pickup was missed or failed.</td></tr><tr><td valign="top">Not Delivered</td><td valign="top">The delivery failed</td></tr><tr><td valign="top">Visited</td><td valign="top">Destination has been successfully visited</td></tr><tr><td valign="top">To be Visited</td><td valign="top">Destination is scheduled for a visit.</td></tr><tr><td valign="top">Not Visited</td><td valign="top">The scheduled visit was missed or unsuccessful.</td></tr></tbody></table>

![](<../.gitbook/assets/image-5 (3) (1).png>)



###















####



####



### 1.11. Manage Document Library



###





###



####





### 2. Manage Missions



### 2.1. Mission Creation Configuration

Fields can be organized within their respective blocks/sections to structure the mission creation layout according to your requirements. While the arrangement of fields inside a block remains fixed, you can modify the overall layout by changing the order of the blocks or sections.

Blocks or sections can be reordered using drag-and-drop functionality. Any changes made through drag-and-drop are automatically synchronized with the visibility and order displayed in the left-hand side user interface.

1. Go to Manage Missions

<figure><img src="../.gitbook/assets/image (10) (1).png" alt=""><figcaption></figcaption></figure>

2. Click Add Mission

<figure><img src="../.gitbook/assets/image (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

3. Enter the Mission type, Agency

<figure><img src="../.gitbook/assets/image (2) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

4. Click Next

<figure><img src="../.gitbook/assets/image (3) (1) (1).png" alt=""><figcaption></figcaption></figure>

5. Click the pencil icon in the top right corner.

<figure><img src="../.gitbook/assets/image (4) (1) (1).png" alt=""><figcaption></figcaption></figure>

6.  View the available information blocks:

    * General Information
    * Pickup Information
    * Delivery Information
    * PUDO Information
    * Custom Fields

    <figure><img src="../.gitbook/assets/image (5) (1) (1).png" alt=""><figcaption></figcaption></figure>


7. Configure fields within each block: Set fields as editable, read-only, or disabled.

<figure><img src="../.gitbook/assets/image (6) (1) (1).png" alt=""><figcaption></figcaption></figure>

8. Use drag and drop to:
   * Reorder fields within a block.
   * Group multiple fields into a single container using the six-dot handle.
   *   Group the duplicated parcels in one container:

       * Selecting **Yes** automatically creates a mission based on the type selected below.
       * Selecting **No** prevents automatic mission creation.
       * Optional — The user is prompted with this option during mission creation.

       <figure><img src="../.gitbook/assets/image (7) (1) (1).png" alt=""><figcaption></figcaption></figure>


9. Expand or collapse blocks as needed.

<figure><img src="../.gitbook/assets/image (8) (1) (1).png" alt=""><figcaption></figcaption></figure>

10. Save the new mission configuration.

<figure><img src="../.gitbook/assets/image (9) (1) (1).png" alt=""><figcaption></figcaption></figure>













### 2.5. Manage Urgent Missions

### 2.5.1. Prioritizing a mission

Prioritization allows users to set the urgency of a mission to ensure it is handled according to specific timelines or customer commitments. The system supports manual priority assignment, automatic assignment based on dates, and priority recalculation during route optimization.

Manual Priority Assignment

1. Select the mission(s) to be prioritized.

<figure><img src="../.gitbook/assets/image (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

2. Click the Prioritize button from the Actions menu

<figure><img src="../.gitbook/assets/image (2) (1) (1).png" alt=""><figcaption></figcaption></figure>

3. Select the priority level: Normal, High, or Highest.

**Automatic Priority via Delivery Dates**

1. Open the mission creation or edit screen.
2. Navigate to Delivery Information.
3. Populate the Delivery Asked Date and Delivery Asked End Date.

<figure><img src="../.gitbook/assets/image (3) (1).png" alt=""><figcaption></figcaption></figure>

4. Save the mission; the system automatically sets the priority to Highest based on these commitment dates.

<figure><img src="../.gitbook/assets/image (4) (1).png" alt=""><figcaption></figcaption></figure>

Recalculating Priorities during Optimization

1. Select the missions or parent route for optimization.

<figure><img src="../.gitbook/assets/image (5) (1).png" alt=""><figcaption></figcaption></figure>

2. Click Optimize from the Actions menu

<figure><img src="../.gitbook/assets/image (6) (1).png" alt=""><figcaption></figcaption></figure>

3. Switch the Recalculate Priorities toggle to ON.

<figure><img src="../.gitbook/assets/image (7) (1).png" alt=""><figcaption></figcaption></figure>

4. Run the optimization.

<figure><img src="../.gitbook/assets/image (8) (1).png" alt=""><figcaption></figcaption></figure>

### 2.5.2. Create an urgent mission

Urgent missions follow a "Chained" model where a pickup is immediately followed by a delivery for the same order, like on-demand food or healthcare delivery. This feature ensures a strict 1-to-1 sequence of operations and uses a dedicated assignment workflow for available drivers.

1. Open the mission creation screen.
2. Select the mission type Chained Pickup and Delivery.

<figure><img src="../.gitbook/assets/image (9) (1).png" alt=""><figcaption></figcaption></figure>

3. Enter the Pickup Information (Origin).
4. Enter the Delivery Information (Destination).

<figure><img src="../.gitbook/assets/image (131) (1).png" alt=""><figcaption></figcaption></figure>

5. Select the created mission from the list.
6. Click the Assign Urgent Mission button.

<figure><img src="../.gitbook/assets/image (132) (1).png" alt=""><figcaption></figcaption></figure>

7. The new pickup mission will be dynamically added to the existing route

<figure><img src="../.gitbook/assets/image (133) (1).png" alt=""><figcaption></figcaption></figure>

#### 2.5.3. Create an urgent pickup mission (Emergency Pickup)

This feature allows an unplanned pickup mission to be inserted into an existing, published route while the driver is already in the field. It is specifically designed for pickup scenarios, such as a customer requesting an immediate return of a damaged item.

1. Create a new Pickup mission&#x20;

<figure><img src="../.gitbook/assets/image (134) (1).png" alt=""><figcaption></figcaption></figure>



2. Select the mission from the list
3. Click the Actions menu.
4. Select Emergency Pickup.

<figure><img src="../.gitbook/assets/image (135).png" alt=""><figcaption></figcaption></figure>

5. Choose the insertion point of the driver:

<figure><img src="../.gitbook/assets/image (136).png" alt=""><figcaption></figcaption></figure>

6. Assign After: Adds the pickup as the very next stop.

<figure><img src="../.gitbook/assets/image (137).png" alt=""><figcaption></figcaption></figure>

7. Assign at End: Adds the pickup to the end of the current route.
8. Click Replace

These grouped missions will be executed only once on the mobile application, significantly reducing field execution time. Additionally, even if missions are not grouped beforehand, the mobile app automatically groups missions that share the same address information.

#### 2.5.4. Create a 'perform at once' mission

'Perform at once' links multiple individual missions destined for the same customer/address. Unlike container grouping, this relies on a "Grouping Key" to tell the mobile app that these items should be fulfilled together, allowing for a single validation step (one signature or one photo) for all linked items.

1. Select multiple missions that share the exact same delivery address.

<figure><img src="../.gitbook/assets/image (138).png" alt=""><figcaption></figcaption></figure>

2. Click the Actions menu.
3. Select Perform at once.

<figure><img src="../.gitbook/assets/image (139).png" alt=""><figcaption></figcaption></figure>

4. The system generates a Grouping Key for the selected missions.

<figure><img src="../.gitbook/assets/image (140).png" alt=""><figcaption></figcaption></figure>

### 2.6. 2.8.2. Map the addresses fields from the global address list

The Global Address List now offers enhanced control over how addresses are managed and accessed in Nomadia Delivery. It is no longer restricted to contractors and is now available directly from the Configuration module. Addresses added to the Global Address List are visible and usable by all Nomadia Delivery users, regardless of contractor.

To use addresses from the Global Address List, follow the steps below:

1. Open the Nomadia Delivery application and go to the Configuration tab.

<figure><img src="../.gitbook/assets/image (157).png" alt=""><figcaption></figcaption></figure>

2. Select Address List from the menu.

<figure><img src="../.gitbook/assets/image (158).png" alt=""><figcaption></figcaption></figure>

3. Create a new address or import addresses from an Excel file.

<figure><img src="../.gitbook/assets/image (159).png" alt=""><figcaption></figcaption></figure>

Once the address list is created, navigate to the Mission page.

<figure><img src="../.gitbook/assets/image (160).png" alt=""><figcaption></figcaption></figure>

4. From the mission table, select Actions → Add (Beta).

<figure><img src="../.gitbook/assets/image (162).png" alt=""><figcaption></figcaption></figure>

5. Select an agency from the dropdown list.

<figure><img src="../.gitbook/assets/image (163).png" alt=""><figcaption></figcaption></figure>

Click Next

<figure><img src="../.gitbook/assets/image (164).png" alt=""><figcaption></figcaption></figure>

6. In the address picker (pickup/delivery), enter an address from the Address List.

<figure><img src="../.gitbook/assets/image (166).png" alt=""><figcaption></figcaption></figure>

* The autocomplete suggests addresses from the Global Address List.
* If a contractor is selected during mission creation, the autocomplete combines contractor addresses and Global Address List entries into a single dropdown.

<figure><img src="../.gitbook/assets/image (167).png" alt=""><figcaption></figcaption></figure>

* Items in the dropdown are distinguished by an icon and tooltip, indicating whether they come from the Global Address List or the contractor’s address list.

<figure><img src="../.gitbook/assets/image (168).png" alt=""><figcaption></figcaption></figure>

This ensures a seamless and unified experience when entering mission addresses.

### 2.9. Improve the Missions addresses geocoding

### 2.9.1. Correct geocoding with a new address

From the Missions page

1. Click Actions.
2. Select Import from the dropdown menu.
3. Click Browse (Excel).
4. Disable the Pickup address field
5. Select the Latitude and Longitude from the location indicators
6. Click on Validate
7. Update the New address in the new address field

<figure><img src="../.gitbook/assets/image (170).png" alt=""><figcaption></figcaption></figure>

#### 2.9.2. Select Missions from the map

From the Map view.

1. Use the Selection button to choose the selection method (e.g., Polygon, Circle).

<figure><img src="../.gitbook/assets/image (171).png" alt=""><figcaption></figcaption></figure>

2. Draw/select the region to highlight missions.

<figure><img src="../.gitbook/assets/image (172).png" alt=""><figcaption></figcaption></figure>

3. Selected missions will appear in the table view on the left panel.

<figure><img src="../.gitbook/assets/image (173).png" alt=""><figcaption></figcaption></figure>

##

### 2.10. Manage Missions Table

#### 2.10.1. Customize the Table Display

1. Click on the Table action menu
2. Click on Customize List.

<figure><img src="../.gitbook/assets/image (174).png" alt=""><figcaption></figcaption></figure>

3. Select the desired fields from the Available Fields list and click the arrow icon to move them to the Display Fields section.
4. Click on Save

<figure><img src="../.gitbook/assets/image (175).png" alt=""><figcaption></figcaption></figure>

The selected fields will be displayed on the table

#### 2.10.2. Sort the Table

1. Click on the column header (e.g., Last Name).
2. Select Ascending or Descending order.
3. The table reorders based on the selection.

<figure><img src="../.gitbook/assets/image (176).png" alt=""><figcaption></figcaption></figure>



#### 2.10.3. Filter Table using Mission statuses shortcuts

1. Click on the Mission Status dropdown or shortcut button.
2. Choose the desired status like Waiting, Picked Up, etc.
3. The table will refresh and show only matching entries.

<figure><img src="../.gitbook/assets/image (177).png" alt=""><figcaption></figcaption></figure>







#### Filter the Table using criteria

1.

#### 2.10.6. Create a Filter

1. Click on the Filter input field.
2. Select the appropriate condition from the suggestions.
3. Click the Load saved filter icon
4. Enter the Appropriate name in the input field
5. Click on Save

<figure><img src="../.gitbook/assets/image (182).png" alt=""><figcaption></figcaption></figure>



#### 2.10.7. Pin a Filter

1. Click Load saved filters icon.
2. Click on the pin icon of the filter to pin.

<figure><img src="../.gitbook/assets/image (183).png" alt=""><figcaption></figcaption></figure>

#### 2.10.8. Delete a Filter

1. Click on the Filter input field.
2. Select the appropriate condition from the suggestions.
3. Click the filter option.
4. Click the "Delete" icon to delete the selected status

<figure><img src="../.gitbook/assets/image (185).png" alt=""><figcaption></figcaption></figure>



####



### 2.11. View a Mission information

1. Click the Pen icon corresponding to the desired mission.
2.  A details panel will open showing information such as:

    * Pickup details
    * Delivery location
    * Parcel barcode and contents
    * Contact information, etc.

    <figure><img src="../.gitbook/assets/image (190).png" alt=""><figcaption></figcaption></figure>





### 2.14. Duplicating Missions with Quantities

This guide explains how contractors and transporters can duplicate missions with quantities in Nomadia Delivery. The feature simplifies the handling of multiple items, enhancing both efficiency and accuracy in mission management.

Steps to duplicate missions with quantities:

1. Open the Nomadia Delivery application and go to the Missions tab.

<figure><img src="../.gitbook/assets/image (38).png" alt=""><figcaption></figcaption></figure>

2. In the Mission table, click the Actions drop-down menu and select Add.

<figure><img src="../.gitbook/assets/image (39).png" alt=""><figcaption></figcaption></figure>

3. In the mission wizard, complete the mandatory fields according to the mission type (e.g., agency, pickup address, delivery address, etc.).

<figure><img src="../.gitbook/assets/image (40).png" alt=""><figcaption></figcaption></figure>

4. Under the Parcel section, enter parcel details such as length, width, height, weight, volume, and solver constraints.

<figure><img src="../.gitbook/assets/image (41).png" alt=""><figcaption></figcaption></figure>

5. To add a new parcel with different values, click the “+” symbol.

<figure><img src="../.gitbook/assets/image (42).png" alt=""><figcaption></figcaption></figure>

6. To duplicate an existing parcel with the same details, click the Copy icon.

<figure><img src="../.gitbook/assets/image (43).png" alt=""><figcaption></figcaption></figure>

7. If you mistakenly add a parcel, click the Delete icon to remove it.

<figure><img src="../.gitbook/assets/image (44).png" alt=""><figcaption></figcaption></figure>

8. After finalizing the parcels to be duplicated, click Add to generate the required number of missions.

<figure><img src="../.gitbook/assets/image (45).png" alt=""><figcaption></figcaption></figure>

9. The duplicated missions will now appear in the mission table.

<figure><img src="../.gitbook/assets/image (46).png" alt=""><figcaption></figcaption></figure>

### 2.15. Cross Docking Missions

Cross-docking missions are a newly introduced feature in Nomadia Delivery aimed at improving efficiency and ensuring full traceability across both mid-mile and last mile logistics. The same mission ID (Barcode) is maintained throughout the process, allowing transporters to seamlessly manage parcel movements from the point of pickup to final delivery.

**A cross-docking mission is divided into two main legs:**

**Leg 1 – Mid-Mile Pickup Tour**

* Plan the Pickup Tour: Organize and assign missions for the pickup route, starting from the agency.
* Collect Parcels: Deliverers pick up parcels directly from the contractor’s warehouse or designated location.
* Return to Agency: All collected parcels are brought back to the agency for sorting and processing.

**Leg 2 – Last-Mile Delivery Tour**

* Plan the Delivery Tour: After parcels are sorted at the agency, prepare and assign the final delivery route.
* Load for Delivery: Deliverers collect the sorted parcels from the agency.
* Deliver to Customers: Parcels are delivered to end recipients, with the same mission ID (Barcode) ensuring consistent tracking and traceability.

To set up a cross-docking mission, proceed with the following steps.

1. Open the Nomadia Delivery application and go to the Missions tab.

<figure><img src="../.gitbook/assets/image (47).png" alt=""><figcaption></figcaption></figure>

2. Click the Actions menu and select Add.

<figure><img src="../.gitbook/assets/image (48).png" alt=""><figcaption></figcaption></figure>

3. In the Mission type drop-down, select Cross-docking to create a cross-docking mission.

<figure><img src="../.gitbook/assets/image (49).png" alt=""><figcaption></figcaption></figure>

4. From the Contractor identifier drop-down, choose the contractor linked to the cross-docking mission.

Note: For cross-docking missions, if the contractor is mapped, their registered address will automatically be used as the default pickup address for Leg 1 | Mid-Mile Pickup Tour. This address is retrieved from the contractor configuration.

<figure><img src="../.gitbook/assets/image (50).png" alt=""><figcaption></figcaption></figure>

5. Select the Agency from which deliverers will start for the Leg 1 | Mid-Mile Pickup Tour.

<figure><img src="../.gitbook/assets/image (51).png" alt=""><figcaption></figcaption></figure>

6. Click Next to continue.

<figure><img src="../.gitbook/assets/image (52).png" alt=""><figcaption></figcaption></figure>

7. By default, the contractor’s address will be used as the pickup address. If required, you can select a different pickup address for Leg 1 | Mid-Mile Pickup Tour by clicking the Edit button next to the address field.

<figure><img src="../.gitbook/assets/image (53).png" alt=""><figcaption></figcaption></figure>

8. Enter the delivery address of the end customer in the address section to complete the cross- docking mission setup.

<figure><img src="../.gitbook/assets/image (54).png" alt=""><figcaption></figcaption></figure>

9. Click Add to create the cross-docking mission.

<figure><img src="../.gitbook/assets/image (55).png" alt=""><figcaption></figcaption></figure>

A new mission of type Cross-docking will now be added to the delivery management system.

<figure><img src="../.gitbook/assets/image (56).png" alt=""><figcaption></figcaption></figure>

**To create a cross-docking mission Leg1 | Mid-Mile Pickup Tour, follow these steps**

1. Select the created mission, open the Actions menu, and choose Assign. Assign the mission to a deliverer.

<figure><img src="../.gitbook/assets/image (57).png" alt=""><figcaption></figcaption></figure>

2. Provide a name for the route, select the deliverer, and specify the date and time for the pickup mission – Leg 1 | Mid-Mile Pickup Tour. Click OK to create the tour.

<figure><img src="../.gitbook/assets/image (58).png" alt=""><figcaption></figcaption></figure>

3. The Leg 1 | Mid-Mile Pickup Tour route will now be created in the delivery management system and will be ready for publishing to the deliverer’s mobile app.

<figure><img src="../.gitbook/assets/image (59).png" alt=""><figcaption></figcaption></figure>

4. Open the Actions menu again and select Publish on mobile app.

<figure><img src="../.gitbook/assets/image (60).png" alt=""><figcaption></figcaption></figure>

5. Click OK to confirm and push the tour details to the mobile app.

<figure><img src="../.gitbook/assets/image (61).png" alt=""><figcaption></figcaption></figure>

6. The Leg 1 | Mid-Mile Pickup Tour will now be available on the deliverer’s mobile app.

<figure><img src="../.gitbook/assets/image (62).png" alt=""><figcaption></figcaption></figure>

7. The deliverer must perform the pickup in real time to complete the Leg 1 | Mid-Mile Pickup Tour.

<figure><img src="../.gitbook/assets/WINWORD_B8sTrdeEm8.png" alt=""><figcaption></figcaption></figure>

8. Once completed, the confirmation of the tour will be displayed in the Gantt chart with a green tick mark.

<figure><img src="../.gitbook/assets/image (65).png" alt=""><figcaption></figcaption></figure>

9. Missions for Leg 2 | Last-Mile Delivery Tour can only be planned once the goods are returned to the depot.

<figure><img src="../.gitbook/assets/image (66).png" alt=""><figcaption></figcaption></figure>

To create a cross-docking mission, follow these steps:

1. Select the Returned to Depot mission, open the Actions menu, and choose Assign. Assign the mission to a deliverer.

<figure><img src="../.gitbook/assets/image (67).png" alt=""><figcaption></figcaption></figure>

2. Enter a name for the route, select the deliverer, and set the date and time for the delivery mission – Leg 2 | Last-Mile Delivery Tour. Click OK to create the tour.

<figure><img src="../.gitbook/assets/image (68).png" alt=""><figcaption></figcaption></figure>

3. The Leg 2 | Last-Mile Delivery Tour route will now be created in the delivery management system and will be ready for publishing to the deliverer’s mobile app.

<figure><img src="../.gitbook/assets/image (69).png" alt=""><figcaption></figcaption></figure>

4. From the Actions menu, select Publish on mobile app.

<figure><img src="../.gitbook/assets/image (70).png" alt=""><figcaption></figcaption></figure>

5. Click OK to confirm and push the tour details to the mobile app.

<figure><img src="../.gitbook/assets/image (71).png" alt=""><figcaption></figcaption></figure>

6. The Leg 2 | Last-Mile Delivery Tour will now be published to the deliverer’s mobile app.&#x20;

<figure><img src="../.gitbook/assets/image (72).png" alt=""><figcaption></figcaption></figure>

7. The deliverer must carry out the deliveries in real time to complete the Leg 2 | Last-Mile Delivery Tour.

<figure><img src="../.gitbook/assets/image (73).png" alt=""><figcaption></figcaption></figure>

8. Once completed, the tour confirmation will be displayed in the Gantt chart with a green tick mark.

<figure><img src="../.gitbook/assets/image (74).png" alt=""><figcaption></figcaption></figure>

### 2.16. Drop Shipping Missions

Drop-shipping missions simplify delivery operations by allowing transporters to deliver parcels directly from suppliers to end customers, without returning to the agency. This method improves efficiency and is particularly suited to logistical scenarios where direct delivery is more practical than traditional models such as cross-docking.

To create a drop-shipping mission, users (contractors, transporters, or subcontractors) should follow these steps

1. Open the Nomadia Delivery application and go to the Missions tab.
2. Click on the Actions menu and select Add.

<figure><img src="../.gitbook/assets/image (76).png" alt=""><figcaption></figcaption></figure>

3. In the Mission Type drop-down, choose Drop-Shipping.

<figure><img src="../.gitbook/assets/image (77).png" alt=""><figcaption></figcaption></figure>

4. From the Contractor Identifier drop-down, select the contractor associated with the mission



<figure><img src="../.gitbook/assets/image (78).png" alt=""><figcaption></figcaption></figure>

* For drop-shipping missions, the contractor’s address (from contractor configuration) will be automatically used as the default pickup address.

<figure><img src="../.gitbook/assets/image (79).png" alt=""><figcaption></figcaption></figure>

5. Select the Agency from which the deliverers will begin their tour.

<figure><img src="../.gitbook/assets/image (80).png" alt=""><figcaption></figcaption></figure>

6. Click Next.

<figure><img src="../.gitbook/assets/image (81).png" alt=""><figcaption></figcaption></figure>

7. The system will display the contractor’s address as the pickup location by default

<figure><img src="../.gitbook/assets/image (82).png" alt=""><figcaption></figcaption></figure>

* If needed, click the **Edit** button next to the address field to set a different pickup address.

<figure><img src="../.gitbook/assets/image (84).png" alt=""><figcaption></figcaption></figure>

8. Click Next to continue.

<figure><img src="../.gitbook/assets/image (85).png" alt=""><figcaption></figcaption></figure>

9. Enter the delivery address of the end customer in the address section.

<figure><img src="../.gitbook/assets/image (86).png" alt=""><figcaption></figcaption></figure>

10. Click Add to create the drop-shipping mission.

<figure><img src="../.gitbook/assets/image (87).png" alt=""><figcaption></figcaption></figure>

Once completed, a new mission of type Drop-Shipping will be added to the delivery management system.

<figure><img src="../.gitbook/assets/image (88).png" alt=""><figcaption></figcaption></figure>

Follow these steps to create a drop-shipping mission tour Drop-shipping missions are exclusively managed through the optimization engine to ensure accuracy and strict compliance with the delivery chain. Manual route planning is restricted to preserve workflow integrity.

Deliveries are permitted only after all pickups are completed, preventing disruptions or errors

1. Select the missions you have created, open the ‘Actions’ menu, and choose ‘Optimize’ to perform a batch optimization.

<figure><img src="../.gitbook/assets/image (89).png" alt=""><figcaption></figcaption></figure>

2. Define the optimization scope by selecting the date range, team, and vehicles, then click ‘Optimize’.

<figure><img src="../.gitbook/assets/image (91).png" alt=""><figcaption></figcaption></figure>

3. Once you are satisfied with the results, click ‘Stop and see the result’.

<figure><img src="../.gitbook/assets/image (92).png" alt=""><figcaption></figcaption></figure>

4. The optimization summary is displayed. Click ‘Display the simulation’ to analyze the results.

<figure><img src="../.gitbook/assets/image (93).png" alt=""><figcaption></figcaption></figure>

5. Alternatively, click ‘Validate routes’ to publish the results directly without reviewing them.
6. In the ‘Deliveries’ panel, the application prefixes all delivery mission numbers with ‘DROP’ to differentiate pickup and drop events.

<figure><img src="../.gitbook/assets/image (94).png" alt=""><figcaption></figcaption></figure>

7. In the ‘Routes’ panel, select the routes you want to validate, open the ‘Actions’ menu, and click Validate.&#x20;

<figure><img src="../.gitbook/assets/image (95).png" alt=""><figcaption></figcaption></figure>

8. Click ‘OK’ to confirm validation.

<figure><img src="../.gitbook/assets/image (96).png" alt=""><figcaption></figcaption></figure>

9. After validation, confirmation notification is displayed.

<figure><img src="../.gitbook/assets/image (97).png" alt=""><figcaption></figcaption></figure>

10. At the bottom of the popup, enable the ‘Publish to the mobile app’ toggle if you want to share the route with the driver.

<figure><img src="../.gitbook/assets/image (98).png" alt=""><figcaption></figcaption></figure>

11. If conflicts occur, the popup will list all problems detected. In such cases, click ‘Force’ to proceed with validation.

<figure><img src="../.gitbook/assets/image (99).png" alt=""><figcaption></figcaption></figure>

12. The validated route with drop-shipping missions is then published to the mobile app.

<figure><img src="../.gitbook/assets/image (100).png" alt=""><figcaption></figcaption></figure>

Transporters can create routes that start from the agency, pick up parcels directly from the contractor (supplier) location, and deliver them to end customers. Unlike cross-docking missions, these routes do not require returning to the agency after the pickups are completed.

### 2.17. Visit – A New Mission Type

The Visit missions are a new category of operational tasks that enable transporters to schedule visits to customer locations without handling parcel pickups or deliveries. They offer greater flexibility for non-transactional activities and enhance planning efficiency across various logistical scenarios.

Transporters can monitor and manage visit missions through customized statuses.

To Be Visited: The visit is planned but has not yet taken place.

Visited: The visit was completed successfully.

Not Visited: The visit was not carried out, with the option of providing a reason if required.

To set up a visit mission, users (contractors, transporters, or subcontractors) should follow these steps:

1. Open the Nomadia Delivery application and go to the Missions tab.
2. Click the ‘Actions’ menu and select ‘Add’.

<figure><img src="../.gitbook/assets/image (101).png" alt=""><figcaption></figcaption></figure>

3. In the Mission Type drop-down, choose the new mission type ‘Visit’ to create a visit mission.

<figure><img src="../.gitbook/assets/image (102).png" alt=""><figcaption></figcaption></figure>

4. Since a visit mission does not involve pickups or deliveries, the wizard includes only the Visit address and opening hours.

<figure><img src="../.gitbook/assets/image (103).png" alt=""><figcaption></figcaption></figure>

5. Select the agency that will serve as the starting point for the deliverers.

<figure><img src="../.gitbook/assets/image (104).png" alt=""><figcaption></figcaption></figure>

6. Click ‘Next’ to proceed to the following step.

<figure><img src="../.gitbook/assets/image (105).png" alt=""><figcaption></figcaption></figure>

7. Enter the visit address of the end customer in the address field.

<figure><img src="../.gitbook/assets/image (106).png" alt=""><figcaption></figcaption></figure>

8. Click ‘Add’ to create the visit mission.

<figure><img src="../.gitbook/assets/image (107).png" alt=""><figcaption></figcaption></figure>

9. A new visit-type mission will now appear in the delivery management system.

<figure><img src="../.gitbook/assets/image (108).png" alt=""><figcaption></figcaption></figure>

To set up a tour including visit missions, follow these steps:

1. Select the created mission, click the ‘Actions’ menu, select the ‘Assign’ menu item and assign the created mission for a deliverer.

<figure><img src="../.gitbook/assets/image (109).png" alt=""><figcaption></figcaption></figure>

2. Give a name to the route, select the deliverer, date, and time for the visit mission, and click the OK/Force assignment’ button to create the tour.

<figure><img src="../.gitbook/assets/image (110).png" alt=""><figcaption></figcaption></figure>

3. The visit route will be created in the delivery management system, and it is ready to be published to the mobile app of the deliverer.
4. Click the ‘Actions’ menu and select the ‘Publish on mobile app’ menu item.
5. Click the ‘OK’ button to confirm and push the data to the mobile app
6. The visit route will be published on the mobile app. The status of the mission is now changed to "To be visited”.

<figure><img src="../.gitbook/assets/image (112).png" alt=""><figcaption></figcaption></figure>

7. The deliverer, upon logging in to the mobile app, will be able to fulfill the visit with a new status xlike Visited & Not Visited.

### 2.18. Auto-Assign Missions to Deliverers

The auto-assignment feature in Nomadia Delivery simplifies dispatching by automatically assigning missions to the right deliverers and vehicles based on predefined spatial or postal zones. This reduces manual effort, minimizes administrative workload, and improves efficiency, particularly in high-volume operations.

Prerequisite: To use automatic mission assignments, you must have a postal code zone or a spatial zone configured in advance. For step-by-step guidance, refer to the Zone Creation by Automatic Sectorization guide.

Follow the steps below to link zones with users and vehicles:

1. Open the Nomadia Delivery application and go to the Configuration tab.
2. From the drop-down, select Manage users.

Note: Zones can only be associated with users who have mobile access.

3. Click the Pencil icon next to the desired mobile user.

<figure><img src="../.gitbook/assets/image (113).png" alt=""><figcaption></figcaption></figure>

4. Users with mobile access will see an additional tab for configuring zone rights. Click Agencies and zones to set up zone assignments.
5. Move the available zones of the associated agencies to the right-hand panel to assign them to the user.

<figure><img src="../.gitbook/assets/image (114).png" alt=""><figcaption></figcaption></figure>

6. After adjusting the zone settings, click Save to confirm the changes.

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

### 2.20. Bulk Edit Mission Data

#### 2.20.1. Create Bulk Edit Configuration

Bulk editing mission data enables large-scale updates to mission information, reducing manual effort and saving time by avoiding repetitive tasks.

To edit mission data in bulk, follow the steps below.

1. Open the Nomadia Delivery application and go to the Configuration tab.

<figure><img src="../.gitbook/assets/image (191).png" alt=""><figcaption></figcaption></figure>

2. From the main header, click the Missions page.

<figure><img src="../.gitbook/assets/image (192).png" alt=""><figcaption></figcaption></figure>

3. Choose the missions you’re interested in from the mission table.

<figure><img src="../.gitbook/assets/image (193).png" alt=""><figcaption></figcaption></figure>

4. Enter a name for the bulk edit configuration in the Bulk Edit pop-up.

<figure><img src="../.gitbook/assets/image (194).png" alt=""><figcaption></figcaption></figure>

5. Select the fields to be enabled for bulk editing and use the arrow button to move them to the right-hand side.

<figure><img src="../.gitbook/assets/image (195).png" alt=""><figcaption></figcaption></figure>

6. Repeat the same steps for the custom fields in the Bulk Edit pop-up.

<figure><img src="../.gitbook/assets/image (196).png" alt=""><figcaption></figcaption></figure>

7. Click the ‘Save’ button to save the bulk edit configuration.

<figure><img src="../.gitbook/assets/image (197).png" alt=""><figcaption></figcaption></figure>

After the configuration is saved, a notification message is displayed.

<figure><img src="../.gitbook/assets/image (198).png" alt=""><figcaption></figcaption></figure>

#### 2.20.2. Bulk Edit Mission Data

1. The Bulk Edit pop-up displays the number of selected missions.
2. The Bulk Edit pop-up displays the list of fields selected during configuration.
3. Choose the required values for the listed mission fields.&#x20;

<figure><img src="../.gitbook/assets/image (199).png" alt=""><figcaption></figcaption></figure>

4. Click on Save

<figure><img src="../.gitbook/assets/image (200).png" alt=""><figcaption></figcaption></figure>

All selected missions are updated simultaneously with the values chosen in the Bulk Edit pop-up.

<figure><img src="../.gitbook/assets/image (201).png" alt=""><figcaption></figcaption></figure>

This feature improves efficiency while maintaining control and data integrity across teams.

