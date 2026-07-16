# customizeworkflow
# customizeworkflow

The customized workflow feature allows you to define how mission statuses progress and who can change them. Dispatchers use this to control the delivery process and ensure accountability. You will achieve a structured, secure, and geographically verified delivery pipeline.

### Getting Started

*   Access to the **Configuration** page.
*   Administrative permissions to modify system tables.

1.  Open the **Configuration** page.
2.  Click on **Customize Status Tables and Workflow**.

    ![Frame at 0:12](../images/customizeworkflow-customizeworkflow_timestamp_0_to_12.png "Configuration Screen – Selecting the Customize Status Tables and Workflow menu option.")

3.  Click the **Workflow** tab.

    ![Frame at 0:15](../images/customizeworkflow-customizeworkflow_timestamp_0_to_15.png "Status Tables Screen – Clicking the Workflow tab to access the editor.")


### Feature Overview

*   **Workflow Mapping**: Define which status can be changed to a specific next status.
    ![Frame at 0:25](../images/customizeworkflow-customizeworkflow_timestamp_0_to_25.png "Workflow Page – The interface where users define status transition paths.")

*   **Proximity Toggle**: Check if a deliverer is at the expected location by toggling **Yes** or **No**.
    ![Frame at 0:33](../images/customizeworkflow-customizeworkflow_timestamp_0_to_33.png "Proximity Settings – The toggle used to enable location verification for status changes.")

*   **Profile Definition**: Restrict specific status changes to authorized roles, such as a **Dispatch User**.
    ![Frame at 0:52](../images/customizeworkflow-customizeworkflow_timestamp_0_to_52.png "Profile Selection – The setting used to define which user profiles can work on specific statuses.")


### How To: Customize a Mission Workflow

1.  Select a starting status in the workflow grid, such as **Created**.

    ![Frame at 0:59](../images/customizeworkflow-customizeworkflow_timestamp_0_to_59.png "Workflow Grid – Identifying the Created status to begin configuration.")

2.  Assign a user role from the **Profile** dropdown to control who can change the status.

    ![Frame at 1:01](../images/customizeworkflow-customizeworkflow_timestamp_1_to_01.png "Profile Settings – Restricting the Created status to the Dispatch User profile.")

3.  Select which target statuses the mission can transition to, such as **DAIS collected** or **EXP log collected**.

    ![Flow 1:01 to 1:08](../images/customizeworkflow-customizeworkflow_timestamp_1_to_01_to_1_to_08.gif "Status Selection – Mapping multiple possible next steps for the mission workflow.")

4.  Configure the next transition, such as allowing a **Dispatch User** to scan a mission and change it to **Delivered**.

    ![Frame at 1:36](../images/customizeworkflow-customizeworkflow_timestamp_1_to_36.png "Workflow Chain – Setting the final transitions for a completed delivery.")

5.  Click on **Save** to modify the changes.

    ![Frame at 1:46](../images/customizeworkflow-customizeworkflow_timestamp_1_to_46.png "Footer Bar – Clicking the Save button to apply the new workflow configuration.")


### Productivity Tips

*   ⚠️ **Unsaved Changes**: Always click the Save button after making adjustments to ensure the mission workflow updates.

