# Case_studies-PUDO_Configuration
# Case-Studies

PUDO (Pickup and Drop-off Points) allows drivers to leave packages at secure locations when customers are unavailable. This feature eliminates expensive redelivery costs and reduces vehicle emissions. You will achieve higher first-attempt success rates and improved customer convenience.

### Getting Started

*   A prepared list of PUDO locations including names and addresses.
*   Defined categories for your network, such as lockers or retail stores.
*   Access to the **Configuration** module in Nomadia Delivery.

1.  Open the **Configuration** module.

    ![Frame at 2:32](../images/Case-Studies-PUDO_Configuration_timestamp_2_to_32.png "Configuration Module – The main entry point for managing system-wide settings.")

2.  Select the **PUDO type** page to define your categories.

    ![Frame at 2:36](../images/Case-Studies-PUDO_Configuration_timestamp_2_to_36.png "PUDO type – The interface where users define categories like lockers or supermarkets.")

3.  Navigate to the **PUDO** page to upload your physical locations.

    ![Frame at 3:29](../images/Case-Studies-PUDO_Configuration_timestamp_3_to_29.png "PUDO page – The screen used to manage the network of drop-off addresses.")

### Feature Overview

*   **PUDO Types**: Categories like stores or lockers with specific handling requirements.

    ![Frame at 1:23](../images/Case-Studies-PUDO_Configuration_timestamp_1_to_23.png "PUDO Types – The UI element used to distinguish between different types of handover points.")

*   **PUDO List**: The database of actual locations and addresses your operation uses.

    ![Frame at 1:37](../images/Case-Studies-PUDO_Configuration_timestamp_1_to_37.png "PUDO List – The registry that the system queries to find nearby driver options.")

*   **PUDO Substatus**: Custom labels for the mobile app that apply only during PUDO interactions.

    ![Frame at 1:53](../images/Case-Studies-PUDO_Configuration_timestamp_1_to_53.png "PUDO Substatus – Specialized status options that filter out standard delivery flows for drivers.")

*   **Fallback PUDO**: A mission-level field that determines if a PUDO drop is permitted.

    ![Frame at 2:11](../images/Case-Studies-PUDO_Configuration_timestamp_2_to_11.png "Fallback PUDO – The setting that controls automatic activation of PUDO flows in the field.")

### How To: Configure PUDO Types

1.  Go to the **Configuration** module.

    ![Flow 2:32 to 2:36](../images/Case-Studies-PUDO_Configuration_timestamp_2_to_32_to_2_to_36.gif "Configuration Module – Navigating from the dashboard to the PUDO type settings.")

2.  Click on **PUDO type**.
3.  Define categories such as supermarkets, partner retailers, or lockers.

    ![Frame at 3:01](../images/Case-Studies-PUDO_Configuration_timestamp_3_to_01.png "PUDO Types – Selecting automated lockers that require an OTP for access.")

### How To: Upload the PUDO List

1.  Navigate to the **PUDO** page in the **Configuration** module.

    ![Flow 3:26 to 3:29](../images/Case-Studies-PUDO_Configuration_timestamp_3_to_26_to_3_to_29.gif "PUDO Page – Accessing the location database management screen.")

2.  Open the **Actions** menu.
3.  Select the **Import** action to upload your list in bulk.

    ![Frame at 4:02](../images/Case-Studies-PUDO_Configuration_timestamp_4_to_02.png "Import Action – Using the bulk upload feature to update the PUDO network.")

### How To: Set Up PUDO Substatuses

1.  Click the **Substatus** page in the **Configuration** module.

    ![Flow 4:14 to 4:18](../images/Case-Studies-PUDO_Configuration_timestamp_4_to_14_to_4_to_18.gif "Substatus Page – Navigating to the status label configuration screen.")

2.  Toggle the **PUDO only** switch.

    ![Frame at 4:28](../images/Case-Studies-PUDO_Configuration_timestamp_4_to_28.png "PUDO Only Toggle – Restricting specific statuses to the PUDO interaction flow.")

3.  Enter operational labels like "Locker Deposited" or "PUDO Point Full".
4.  Click the **Save** button.

    ![Frame at 5:09](../images/Case-Studies-PUDO_Configuration_timestamp_5_to_09.png "Save Button – Confirming and storing the new substatus configurations.")

### How To: Enable Fallback PUDO on a Mission

1.  Find the **Fallback delivery in PUDO** field in the **Mission Table**.

    ![Frame at 5:24](../images/Case-Studies-PUDO_Configuration_timestamp_5_to_24.png "Mission Table – Locating the fallback PUDO permission column.")

2.  Click the **Edit** button to open the **Mission Editor**.

    ![Flow 5:52 to 5:56](../images/Case-Studies-PUDO_Configuration_timestamp_5_to_52_to_5_to_56.gif "Mission Editor – Opening the detailed mission settings for manual adjustment.")

3.  Select the **Delivery information** section.
4.  Set the fallback characteristic to **Allow**, **Deny**, or **After retry**.

    ![Frame at 6:08](../images/Case-Studies-PUDO_Configuration_timestamp_6_to_08.png "Fallback PUDO Settings – Choosing the drop-off permission level for a mission.")

### Productivity Tips

*   💡 **Multi-Mission Support**: Use PUDO for both pickup and delivery missions to increase operational flexibility.
*   💡 **Bulk Updates**: Manage fallback permissions at scale using the **Import template** or the API during mission creation.
*   ⚠️ **Data Maintenance**: Keep the **PUDO list** current or drivers will be unable to find nearby drop-off points.
*   ⚠️ **Type Distinctions**: Always differentiate between stores and lockers as they require different handling processes like **OTP** codes.

