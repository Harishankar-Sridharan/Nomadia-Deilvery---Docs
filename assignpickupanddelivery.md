# assignpickupanddelivery
# assignpickupanddelivery

The **assignpickupanddelivery** feature lets dispatchers assign pickup and delivery routes to drivers and vehicles. You need it to optimize route placement and manage driver assignments in real time. By using this feature, you will achieve faster deliveries and manage driver acceptance timeouts.

### Getting Started

Prerequisites:
- Assigned driver and vehicle details.
- Driver authorizations for required skills.
- Mobile app accept timeout minutes configured.

Initial setup steps:
1. Navigate to **Configuration**.

![Frame at 2:31](assignpickupanddelivery-assignpickupanddelivery_timestamp_2_to_31.png "Configuration Screen – Navigation option to configure system settings.")

2. Click **Configure Mobile App**.

![Frame at 2:41](assignpickupanddelivery-assignpickupanddelivery_timestamp_2_to_41.png "Configure Mobile App – Menu selection for driver app settings.")

3. Enter minutes in **Accept Timeout Minutes**.

![Frame at 2:43](assignpickupanddelivery-assignpickupanddelivery_timestamp_2_to_43.png "Accept Timeout Minutes – Input field for driver response time limit.")

4. Click **Save**.

![Frame at 3:01](assignpickupanddelivery-assignpickupanddelivery_timestamp_3_to_01.png "Save Button – Action button to save configuration changes.")

### Feature Overview

- **Driver Name and Vehicle Name**: Displays driver identity and vehicle info to track active units.

![Frame at 0:29](assignpickupanddelivery-assignpickupanddelivery_timestamp_0_to_29.png "Driver Data – Displays driver name and vehicle details.")

- **Available Machines**: Lists unassigned machines ready for route assignments.

![Frame at 0:34](assignpickupanddelivery-assignpickupanddelivery_timestamp_0_to_34.png "Available Machines – Overview of unassigned machines.")

- **Authorizations**: Indicates driver skills and permissions to ensure task compatibility.

![Frame at 0:37](assignpickupanddelivery-assignpickupanddelivery_timestamp_0_to_37.png "Authorizations – Displays driver skill qualifications.")

- **Assigned Machines**: Lists machines currently linked to the selected driver.

![Frame at 0:41](assignpickupanddelivery-assignpickupanddelivery_timestamp_0_to_41.png "Assigned Machines – Shows machines currently assigned to driver.")

- **Current Route Kilometer**: Tracks total mileage on the driver active route.

![Frame at 0:43](assignpickupanddelivery-assignpickupanddelivery_timestamp_0_to_43.png "Current Route Kilometer – Shows total distance of current route.")

- **Position**: Shows driver location status relative to agency.

![Frame at 0:47](assignpickupanddelivery-assignpickupanddelivery_timestamp_0_to_47.png "Position – Displays whether driver is at agency.")

- **Assign Optimal**: Adjusts existing unstarted routes to deliver current assignments faster.

![Frame at 0:51](assignpickupanddelivery-assignpickupanddelivery_timestamp_0_to_51.png "Assign Optimal – Route placement control for faster delivery.")

- **Assign After Current State**: Inserts task directly after driver current task state.

![Frame at 1:08](assignpickupanddelivery-assignpickupanddelivery_timestamp_1_to_08.png "Assign After Current State – Placement option to add task after current state.")

- **Assign at the End**: Appends task to the end of driver scheduled route.

![Frame at 1:12](assignpickupanddelivery-assignpickupanddelivery_timestamp_1_to_12.png "Assign at the End – Placement option to append task at end of route.")

- **Acceptance Status**: Displays whether driver accepts or denies assigned route.

![Frame at 1:16](assignpickupanddelivery-assignpickupanddelivery_timestamp_1_to_16.png "Acceptance Status – Shows route acceptance or denial state.")

- **Accept Timeout Minutes**: Sets duration in minutes allowed for driver route decision.

![Frame at 2:43](assignpickupanddelivery-assignpickupanddelivery_timestamp_2_to_43.png "Accept Timeout Minutes – Input setting for driver decision window.")

### How To: Assign Drop Shipping Route

1. Go to **Machines**.

![Flow 0:05 to 0:13](assignpickupanddelivery-assignpickupanddelivery_timestamp_0_to_05_to_0_to_13.gif "Machines List – Navigate to machines screen.")

2. Select **Drop shipping machine**.

![Frame at 0:14](assignpickupanddelivery-assignpickupanddelivery_timestamp_0_to_14.png "Drop Shipping Machine – Select drop shipping machine.")

3. Click **Actions**.

![Frame at 0:16](assignpickupanddelivery-assignpickupanddelivery_timestamp_0_to_16.png "Actions Menu – Open actions dropdown menu.")

4. Click **Assign pickup and delivery machine**.

![Flow 0:18 to 0:21](assignpickupanddelivery-assignpickupanddelivery_timestamp_0_to_18_to_0_to_21.gif "Assign Pickup and Delivery Action – Open assignment modal window.")

5. Select placement option like **Assign Optimal**.

![Frame at 0:51](assignpickupanddelivery-assignpickupanddelivery_timestamp_0_to_51.png "Placement Options – Choose route placement strategy.")

6. Click **Confirm**.

![Flow 1:31 to 1:37](assignpickupanddelivery-assignpickupanddelivery_timestamp_1_to_31_to_1_to_37.gif "Confirm Assignment – Confirm and save route assignment.")

### How To: Assign Pickup and Delivery Machine Route

1. Go to **Machines**.

![Frame at 1:40](assignpickupanddelivery-assignpickupanddelivery_timestamp_1_to_40.png "Machines List – Navigate to machines menu.")

2. Select **Assign pickup and delivery** machine.

![Frame at 1:44](assignpickupanddelivery-assignpickupanddelivery_timestamp_1_to_44.png "Pickup and Delivery Machine – Select pickup and delivery machine.")

3. Click **Actions**.

![Frame at 1:46](assignpickupanddelivery-assignpickupanddelivery_timestamp_1_to_46.png "Actions Menu – Open actions menu.")

4. Click **Assign pickup and delivery machine**.

![Frame at 1:49](assignpickupanddelivery-assignpickupanddelivery_timestamp_1_to_49.png "Assignment Details – Review assignment screen parameters.")

5. Select **Assign Optimal** to modify route.

![Flow 2:04 to 2:31](assignpickupanddelivery-assignpickupanddelivery_timestamp_2_to_04_to_2_to_31.gif "Assign Optimal Flow – Modify existing unstarted driver route.")

### How To: Configure Driver Acceptance Timeout

1. Go to **Configuration**.

![Frame at 2:31](assignpickupanddelivery-assignpickupanddelivery_timestamp_2_to_31.png "Configuration – Access system configuration menu.")

2. Click **Configure Mobile App**.

![Frame at 2:41](assignpickupanddelivery-assignpickupanddelivery_timestamp_2_to_41.png "Configure Mobile App – Open mobile app configuration.")

3. Enter value in **Accept Timeout Minutes**.

![Frame at 2:43](assignpickupanddelivery-assignpickupanddelivery_timestamp_2_to_43.png "Accept Timeout Minutes – Enter response time limit in minutes.")

4. Click **Save**.

![Flow 3:01 to 3:05](assignpickupanddelivery-assignpickupanddelivery_timestamp_3_to_01_to_3_to_05.gif "Save Settings – Save mobile app timeout settings.")

### Troubleshooting

- **Empty Acceptance Status**: Configure **Accept Timeout Minutes** in **Configure Mobile App** settings if acceptance fields appear empty.

### Productivity Tips

- 💡 **Optimal Route Sequencing**: Select **Assign Optimal** to re-sequence unstarted routes and accelerate delivery schedules.
- ⚠️ **Started Route Lock**: Avoid selecting **Assign Optimal** for active drivers who have already started their route because changes will fail.
- 💡 **Driver Response Limits**: Set **Accept Timeout Minutes** to enforce response deadlines for driver route acceptance.

