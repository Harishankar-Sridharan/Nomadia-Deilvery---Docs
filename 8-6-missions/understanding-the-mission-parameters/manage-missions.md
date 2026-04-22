# Manage Missions

The following fields are available at the mission level, allowing you to configure various mission constraints based on your business requirements.

<table data-header-hidden><thead><tr><th valign="top"></th><th valign="top"></th><th valign="top"></th></tr></thead><tbody><tr><td valign="top">Mission Section</td><td valign="top">Mission Field</td><td valign="top">Description</td></tr><tr><td valign="top">General Information</td><td valign="top">Mission Number</td><td valign="top">A unique identifier automatically or manually assigned to the mission for tracking and reference purposes.</td></tr><tr><td valign="top"> </td><td valign="top">Sender Barcode</td><td valign="top">Barcode associated with the sender or shipment, used for scanning and quick identification during processing and delivery operations</td></tr><tr><td valign="top"> </td><td valign="top">Parent Container ID</td><td valign="top">Identifies the parent container to which the mission or shipment belongs, enabling hierarchical shipment tracking</td></tr><tr><td valign="top"> </td><td valign="top">Grouping key</td><td valign="top">A value used to group multiple missions together for planning, routing, or operational purposes.</td></tr><tr><td valign="top"> </td><td valign="top">Container Type</td><td valign="top">Defines the type of container used for the shipment (e.g., box, pallet, envelope), which may influence handling or transportation constraints.</td></tr><tr><td valign="top"> </td><td valign="top">Status Configuration Type</td><td valign="top">Specifies the status workflow configuration applied to the mission, determining available mission states and transitions.</td></tr><tr><td valign="top"> </td><td valign="top">Notification Configuration Type</td><td valign="top">Defines the notification rules associated with the mission, such as alerts sent to customers, drivers, or operators during mission progress.</td></tr><tr><td valign="top"> </td><td valign="top">Scheduled Deliverer</td><td valign="top">The planned resource (driver, technician, or agent) assigned to execute the mission.</td></tr><tr><td valign="top"> </td><td valign="top">Origin</td><td valign="top">The starting location from which the mission begins or where the goods are picked up.</td></tr><tr><td valign="top"> </td><td valign="top">Priority</td><td valign="top">Indicates the importance level of the mission, which may influence planning order and execution scheduling.</td></tr><tr><td valign="top"> </td><td valign="top">Storage place</td><td valign="top">Specifies the storage or warehouse location associated with the mission before dispatch or after completion.</td></tr><tr><td valign="top"> </td><td valign="top">Fixed Visit Duration</td><td valign="top">Defines the expected duration required to complete the mission at the location.</td></tr><tr><td valign="top"> </td><td valign="top">Keys</td><td valign="top">Reference identifiers or tags used for classification, filtering, or integration purposes.</td></tr><tr><td valign="top"> </td><td valign="top">Compatibility with the resources</td><td valign="top">Defines constraints ensuring that only compatible resources (based on skills, vehicle type, or configuration) can be assigned to the mission.</td></tr><tr><td valign="top"> </td><td valign="top">Require all skills to be compatible</td><td valign="top"><p>When enabled, the assigned resource must possess all required skills defined for the mission.</p><p> </p></td></tr><tr><td valign="top"> </td><td valign="top">Delivery to be executed before any pickup</td><td valign="top">Ensures delivery operations are completed before pickup tasks within the same mission sequence.</td></tr><tr><td valign="top"> </td><td valign="top">One time password</td><td valign="top">A security verification code required to validate mission completion or delivery confirmation.</td></tr><tr><td valign="top"> </td><td valign="top">Origin agency</td><td valign="top">The agency or operational unit responsible for initiating the mission.</td></tr><tr><td valign="top"> </td><td valign="top">Destination agency</td><td valign="top">The agency or operational unit responsible for receiving or completing the mission.</td></tr><tr><td valign="top"> </td><td valign="top">Leg</td><td valign="top">Represents a segment of a multi-stage mission or transportation route.</td></tr><tr><td valign="top"> </td><td valign="top">Mission status</td><td valign="top">Displays the current state of the mission within the operational workflow (e.g., Planned, Assigned, In Progress, Completed, Cancelled).</td></tr><tr><td valign="top">Pickup Information</td><td valign="top">Pickup (Address)</td><td valign="top">Specifies the primary address where the pickup operation will take place.</td></tr><tr><td valign="top"> </td><td valign="top">Pickup (Address Complement)</td><td valign="top">Provides additional address details such as building name, apartment number, floor, or access instructions to help locate the pickup point accurately.</td></tr><tr><td valign="top"> </td><td valign="top">Pickup Designation</td><td valign="top">Identifies the pickup location or organization name associated with the shipment.</td></tr><tr><td valign="top"> </td><td valign="top">Pickup (First name)</td><td valign="top">First name of the contact person available at the pickup location.</td></tr><tr><td valign="top"> </td><td valign="top">Pickup (Last name)</td><td valign="top">Last name of the contact person responsible for coordinating the pickup.</td></tr><tr><td valign="top"> </td><td valign="top">Pickup (Cell phone)</td><td valign="top">Mobile phone number of the pickup contact person, used for communication during mission execution.</td></tr><tr><td valign="top"> </td><td valign="top">Pickup (Landline phone)</td><td valign="top">Landline telephone number of the pickup location or contact person.</td></tr><tr><td valign="top"> </td><td valign="top">Pickup (Email)</td><td valign="top">Email address of the pickup contact for sending notifications or communication related to the mission.</td></tr><tr><td valign="top"> </td><td valign="top">Pickup asked date</td><td valign="top">The requested date and time when the pickup should begin.</td></tr><tr><td valign="top"> </td><td valign="top">Pickup asked end date</td><td valign="top">The latest acceptable date and time by which the pickup must be completed.</td></tr><tr><td valign="top"> </td><td valign="top">Pickup Instructions</td><td valign="top">Special instructions or operational notes provided to the resource performing the pickup (e.g., access procedures, handling requirements, security instructions).</td></tr><tr><td valign="top"> </td><td valign="top">Scannable container code</td><td valign="top">Barcode or scannable identifier associated with the container, enabling quick verification and tracking during pickup operations.</td></tr><tr><td valign="top">Delivery Information</td><td valign="top">Address</td><td valign="top">Specifies the primary destination address where the delivery must be completed.</td></tr><tr><td valign="top"> </td><td valign="top">Delivery (Address Complement)</td><td valign="top">Provides additional location details such as apartment number, building name, floor, gate number, or access instructions to help accurately locate the delivery point.</td></tr><tr><td valign="top"> </td><td valign="top">Designation</td><td valign="top">Indicates the name of the delivery location, company, or organization receiving the shipment.</td></tr><tr><td valign="top"> </td><td valign="top">First name</td><td valign="top">First name of the recipient or contact person at the delivery location.</td></tr><tr><td valign="top"> </td><td valign="top">Last name</td><td valign="top">Last name of the recipient or responsible contact person.</td></tr><tr><td valign="top"> </td><td valign="top">Cell phone</td><td valign="top">Mobile phone number of the delivery contact, used for communication during delivery execution.</td></tr><tr><td valign="top"> </td><td valign="top">Landline phone</td><td valign="top">Landline telephone number associated with the delivery location or recipient.</td></tr><tr><td valign="top"> </td><td valign="top">Email</td><td valign="top">Email address of the recipient used for notifications, confirmations, or delivery updates.</td></tr><tr><td valign="top"> </td><td valign="top">Delivery asked date</td><td valign="top">The requested date and time when the delivery should start or be performed.</td></tr><tr><td valign="top"> </td><td valign="top">Delivery asked end date</td><td valign="top">The latest acceptable date and time by which the delivery must be completed.</td></tr><tr><td valign="top"> </td><td valign="top">Cash on delivery</td><td valign="top">Specifies the amount to be collected from the recipient at the time of delivery, if applicable.</td></tr><tr><td valign="top"> </td><td valign="top">Delivery price</td><td valign="top">Defines the delivery charge associated with the mission for billing or accounting purposes.</td></tr><tr><td valign="top"> </td><td valign="top">Delivery instructions</td><td valign="top">Special notes or operational instructions provided to the delivery resource (e.g., access procedures, preferred delivery time, handling precautions).</td></tr><tr><td valign="top"> </td><td valign="top">Fallback delivery in PUDO</td><td valign="top">Indicates whether the shipment can be redirected to a Pick-Up and Drop-Off (PUDO) point if the primary delivery attempt fails or the recipient is unavailable.</td></tr><tr><td valign="top">Custom fields</td><td valign="top"> </td><td valign="top">The Custom Fields section allows users to define and capture additional information specific to business requirements that are not covered by the standard mission fields.</td></tr><tr><td valign="top">Articles</td><td valign="top"> </td><td valign="top">The Articles section contains detailed information about the items or goods associated with a mission. It allows users to define the characteristics, quantity, and handling requirements of the products being picked up or delivered.</td></tr><tr><td valign="top">Opening hours</td><td valign="top"> </td><td valign="top">The Opening Hours section defines the time periods during which a pickup or delivery location is available for operational activities. It ensures that missions are scheduled and executed only within the authorized working hours of the location.</td></tr><tr><td valign="top">PUDO Information</td><td valign="top">PUDO Id</td><td valign="top">A unique identifier assigned to the Pick-Up and Drop-Off point used for tracking and system reference.</td></tr><tr><td valign="top"> </td><td valign="top">PUDO (Address complement)</td><td valign="top">Provides additional address details such as building information, floor number, or specific access instructions to help locate the PUDO point easily.</td></tr><tr><td valign="top"> </td><td valign="top">PUDO Address</td><td valign="top">Specifies the physical address of the Pick-Up and Drop-Off location.</td></tr><tr><td valign="top"> </td><td valign="top">PUDO first name</td><td valign="top">First name of the contact person responsible at the PUDO location.</td></tr><tr><td valign="top"> </td><td valign="top">PUDO last name</td><td valign="top">Last name of the contact person managing or coordinating operations at the PUDO point.</td></tr><tr><td valign="top"> </td><td valign="top">PUDO landline phone</td><td valign="top">Landline telephone number of the PUDO location for operational communication.</td></tr><tr><td valign="top"> </td><td valign="top">PUDO cell phone</td><td valign="top">Mobile phone number of the PUDO contact person for real-time communication during mission execution.</td></tr><tr><td valign="top"> </td><td valign="top">PUDO email</td><td valign="top">Email address associated with the PUDO location used for notifications and operational correspondence.</td></tr><tr><td valign="top"> </td><td valign="top">PUDO fixed visit duration</td><td valign="top">Defines the standard time required to complete operations (pickup or drop-off) at the PUDO location. This duration is used by the planning system for scheduling and route optimization.</td></tr><tr><td valign="top"> </td><td valign="top">Pickup PUDO</td><td valign="top">Pickup PUDO refers to the Pick-Up and Drop-Off (PUDO) location designated as the pickup point for a mission instead of the standard pickup address.</td></tr><tr><td valign="top"> </td><td valign="top">Delivery PUDO</td><td valign="top">Delivery PUDO refers to the Pick-Up and Drop-Off (PUDO) location used as an alternative or final delivery destination instead of the recipient’s primary address.</td></tr></tbody></table>

### Add a Mission

Adding Mission allows users to create a mission by selecting a mission type, choosing a configuration, and entering mandatory mission information. The system enforces validations based on the selected mission type.

1. Go to **Missions**

<figure><img src="../../.gitbook/assets/image (10) (1) (1).png" alt=""><figcaption></figcaption></figure>

2. Click **Add** from the Actions menu

<figure><img src="../../.gitbook/assets/image (11) (1).png" alt=""><figcaption></figcaption></figure>

3. Select **Mission Type, (Pickup information - delivery) Delivery information -pickup), Agency.**

<figure><img src="../../.gitbook/assets/image (12) (1).png" alt=""><figcaption></figcaption></figure>

4. Click **Next**.

<figure><img src="../../.gitbook/assets/image (13) (1).png" alt=""><figcaption></figcaption></figure>

5.  Select a **Mission Configuration**:

    * Default configuration
    * Any custom configuration created earlier

    <figure><img src="../../.gitbook/assets/image (14) (1).png" alt=""><figcaption></figcaption></figure>
6. Enter **mandatory mission details** based on mission type.

<figure><img src="../../.gitbook/assets/image (15) (1).png" alt=""><figcaption></figcaption></figure>

7. Click **Add** or **Add and Print.**

<figure><img src="../../.gitbook/assets/image (16) (1).png" alt=""><figcaption></figcaption></figure>

### Mission Wizard: A Guided step by step process

The Mission Creation Wizard in Nomadia Delivery provides a user-friendly, step-by-step process for creating and adding missions effortlessly. From entering basic mission details to specifying customer opening hours, the wizard simplifies mission setup while ensuring accuracy and efficiency throughout.

Follow these steps to create a mission using the wizard

1. Open the delivery management system, then navigate to the ‘**Missions**’ tab

<figure><img src="../../.gitbook/assets/image (141).png" alt=""><figcaption></figcaption></figure>

2. Click the ‘**Actions**’ button and choose ‘**Add**’ to launch the mission creation wizard

<figure><img src="../../.gitbook/assets/image (142).png" alt=""><figcaption></figcaption></figure>

3. Select the type of **mission** and **agency**

<figure><img src="../../.gitbook/assets/image (143).png" alt=""><figcaption></figcaption></figure>

4.  Pickup Address details:

    * **For Pickup Missions**: Enter the pickup address details such as **address line, city, state/province, postal code**, and any additional instructions or landmarks to ensure accurate identification.
    * **For Delivery Missions**: The agency address is used by default.

    <figure><img src="../../.gitbook/assets/image (144).png" alt=""><figcaption></figcaption></figure>
5.  Delivery Address details:

    * **For Delivery Missions**: Enter the **delivery address details**. Providing clear and accurate information ensures successful and timely deliveries.
    * **For Pickup Missions**: The agency address is used by default.

    <figure><img src="../../.gitbook/assets/image (145).png" alt=""><figcaption></figcaption></figure>
6. **Parcel Information (Optional)**: In this step, provide details about the parcels, such as **dimensions, weight, contents**, and any special handling requirements. Supplying accurate parcel information helps ensure proper handling and maintains delivery integrity.

<figure><img src="../../.gitbook/assets/image (146).png" alt=""><figcaption></figcaption></figure>

7. **Customer Opening Hours Definition (Optional)**: Specify the customer’s opening hours to schedule deliveries within appropriate time slots. This ensures delivery timings aligned with customer availability, reducing the chances of missed deliveries or rejections.

<figure><img src="../../.gitbook/assets/image (147).png" alt=""><figcaption></figcaption></figure>

8. **Add Mission to Delivery Management System**: After entering all required information, click the ‘**Add**’ button to save the mission in the delivery management system. The mission has been successfully created. This wizard streamlines the process by guiding users’ step by step, ensuring that all required information is entered accurately.

<figure><img src="../../.gitbook/assets/image (148).png" alt=""><figcaption></figcaption></figure>

9. The mission has been successfully created. This wizard streamlines the process by guiding users’ step by step, ensuring that all required information is entered accurately.

<figure><img src="../../.gitbook/assets/image (149).png" alt=""><figcaption></figcaption></figure>

### Map the import mission file fields

#### Map the address fields

From the **Missions page**

1. Click **Actions**.
2. Select **Import** from the dropdown menu.
3. Click **Browse (Excel).**
4. Select the **Address** from the location indicators

<figure><img src="../../.gitbook/assets/image (154).png" alt=""><figcaption></figcaption></figure>

5. Click on **Validate**

<figure><img src="../../.gitbook/assets/image (155).png" alt=""><figcaption></figcaption></figure>

6. The address fields will be mapped successfully

<figure><img src="../../.gitbook/assets/image (156).png" alt=""><figcaption></figcaption></figure>

### Color the Missions

From the **Missions page**

1. Click **Actions**.
2. Select **Coloring** from the dropdown menu.

<figure><img src="../../.gitbook/assets/image (186).png" alt=""><figcaption></figcaption></figure>

3. Select the appropriate condition from the suggestions.
4. Choose the **Color**
5. Click on **Save**

<figure><img src="../../.gitbook/assets/image (187).png" alt=""><figcaption></figcaption></figure>

6. The selected color will be applied successfully.
