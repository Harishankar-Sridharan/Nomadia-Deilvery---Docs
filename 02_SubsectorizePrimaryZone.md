# 02_SubsectorizePrimaryZone
### **Guide to Subsectorizing and Balancing Your Territories**

Welcome! This guide will help you transform a large primary zone into smaller, fair, and logical territories. By using real mission data, you can ensure your team has balanced workloads without the manual guesswork.

---

### **1. Feature Overview & Benefits**
Subsectorization is the process of splitting a primary zone into smaller areas called "subzones". 

*   **Fairness**: Use actual delivery data (stops, coordinates, and times) to ensure every agent has a manageable workload.
*   **Logical Boundaries**: The system creates geographically sensible splits, so agents aren't crossing over each other.
*   **Automation**: No more manual drawing on maps; the system does the heavy lifting for you.

---

### **2. Pre-Check: Prepare Your Data**
⚠️ **Important**: Before you begin, your **Mission Page** must have historical missions loaded. The system uses this data—like delivery points and stop coordinates—to calculate how to split the zone intelligently. Without missions, there is nothing to balance against.

---

### **3. Step-by-Step: Creating Your Subzones**

#### **Phase 1: Selecting Your Zone and Filtering Data**
1.  Open your **Study** and navigate to the **Zone** tab.
2.  Select your **Primary Zone** from the list.

![GIF at 1:43–1:48](../../images/02_SubsectorizePrimaryZone_timestamp_1_to_43–1_to_48.gif "Click the **Actions** menu and select **Subsectorize** – Opens the parameters pop-up.")

4.  In the **Sectorization Parameters** pop-up, use the filters to choose which data to use (e.g., filtering by a specific agency, subcontractor, or a period like "Monday missions").
5.  💡 **Tip**: Toggle on the **Naming Pattern** option. This automatically names your subzones based on the primary zone (e.g., "North Paris_01"), saving you manual work later.

![GIF at 3:16–3:20](../../images/02_SubsectorizePrimaryZone_timestamp_3_to_16–3_to_20.gif "Click **Assign Territories** – Launches the Territory Manager module.")


#### **Phase 2: Automating the Split**

![GIF at 3:52–3:58](../../images/02_SubsectorizePrimaryZone_timestamp_3_to_52–3_to_58.gif "Click the **Automation** button located in the top left, just above the map – Opens the Territory Assignment Wizard.")

2.  Select **Balance Points** as your balancing method and click **Start**.
3.  Go to the **Number of Territories** tab and set your target (e.g., "3").
4.  Go to the **Balance the Territories On** tab and choose your indicator.
    *   *Example*: Select **Number of Points** to distribute missions evenly by count.
    *   💡 **Tip**: You can also balance by **Delivery Duration** or **Service Time** if those metrics are more important for your operation.

![GIF at 5:00–5:05](../../images/02_SubsectorizePrimaryZone_timestamp_5_to_00–5_to_05.gif "Click **Let's Go** – The system processes and creates the split.")


#### **Phase 3: Review and Finalize**
1.  Review the map. Each new subzone will be shown in a different color so you can easily see the new boundaries.

![GIF at 5:45–5:52](../../images/02_SubsectorizePrimaryZone_timestamp_5_to_45–5_to_52.gif "Click **Validate Territory Management** in the top right – Redirects you to the Assignment page.")

3.  On the **Assignment Page**, use the drop-down menus next to each subzone to link them to a specific agency or team.
4.  Choose your save method:
    *   **Save and Assign**: Use this if you are ready to go live immediately.
    *   **Save**: Use this to store the boundaries now and assign teams later.

---

### **4. Visual Guidance (Interface States)**

*   **[Diagram 1: Parameter Pop-up]**: A window showing filter options for Agency, Subcontractor, and Days of the week (📹 1:53).
*   **[Diagram 2: The Assignment Wizard]**: A step-by-step panel where you input the "Number of Territories" and choose "Balance Points" (📹 4:03).
*   **[Diagram 3: Balanced Map View]**: A map display showing the primary zone divided into three distinct color-coded sections (📹 5:22).
*   **[Diagram 4: Updated Zone Table]**: A list view showing the new subzones as individual rows next to the updated map (📹 6:48).

---

### **5. Productivity Tips for Success**
*   **Real-World Scenario**: If you manage "North Paris," using the **Naming Pattern** will automatically create "North Paris_01," "North Paris_02," etc., keeping your database clean and organized.
*   **Flexible Metrics**: Don't feel restricted to just counting delivery points. If some areas have high traffic, try balancing by **Delivery Duration** to keep workloads fair for your drivers.
*   **No Manual Drawing**: Trust the system! It uses actual delivery coordinates on the ground to draw the most efficient lines for your field teams.

