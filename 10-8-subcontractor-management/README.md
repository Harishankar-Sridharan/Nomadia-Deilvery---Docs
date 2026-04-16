# Subcontractor Management

The subcontractor management feature allows transporters to delegate logistics tasks to subcontractors, making collaborations smoother and increasing operational flexibility.

This feature ensures subcontractors are managed efficiently so that logistics operations remain optimized and aligned with business objectives.

In the Nomadia Delivery application, subcontractors must be registered by the transporter before they can upload mission data. To do this, the transporter needs to add the subcontractor through the Subcontractor module.

Use the following steps to register a subcontractor

1. Open the Nomadia Delivery application and go to the Subcontractors module. (Ensure the user has the necessary rights to create and modify subcontractors.)
2. Click the Actions menu and select the Add button.

![](<../.gitbook/assets/image-1 (6).png>)

3. When adding a subcontractor, the following fields are mandatory:
   * Identifier
   * Subcontractor name
   * Subcontractor address
   * Mission types they can handle
   * Allocated web users
   * Allocated mobile users
   * Profiles
   * Agency
4. The transporter may also enter additional details such as zone and authorizations. Once the subcontractor’s address is entered, the map will automatically highlight their geographical location.

![](<../.gitbook/assets/image-2 (6).png>)

5. Click Save to add the subcontractor to the delivery management system.

![](<../.gitbook/assets/image-3 (6).png>)

6. A notification will confirm that the subcontractor has been successfully added.

![](<../.gitbook/assets/image-4 (6).png>)

7. As an alternative, subcontractors can be imported in bulk via an Excel file, saving time and effort when adding multiple entries.

![](<../.gitbook/assets/image-5 (6).png>)

After registration, the transporter can create subcontractor access from the Configuration module. This enables subcontractors to log in to the system and carry out their tasks.

Use the following steps to set up a new subcontractor user.

Transporters can assign users within each subcontractor to manage planning and execution tasks more effectively. This capability enables the creation of dedicated planners and drivers for every subcontractor, ensuring smooth and efficient management of logistics operations.

1. Open the Nomadia Delivery application and go to Configuration > Manage users.

![](<../.gitbook/assets/image-6 (6).png>)

2. Click the Action button and select Add.

![](<../.gitbook/assets/image-7 (6).png>)

3. Click OK to create a new user.

![](<../.gitbook/assets/image-8 (5).png>)

Alternatively, you can create a user from an existing one. This speeds up the process by copying all settings from the existing user to the new one.

4. In the Generalities tab, enter the profile, login, and last name of the user, and enable the user status. Then proceed to the Access tab.

![](<../.gitbook/assets/image-9 (5).png>)

5. Enable web access for the user and select the subcontractor’s website from the drop-down list.

![](<../.gitbook/assets/image-10 (4).png>)

6. Select the correct subcontractor (created in the Subcontractors module) to link with this user, then continue to the Roles & rights tab.

**Note**: If no subcontractor appears in the list, ensure one has been created in the Subcontractors module.

7. The system automatically assigns rights based on the user.

![](<../.gitbook/assets/image-11 (4).png>)

8. Save the new user. The subcontractor will receive an email notification with instructions to create a password and activate the account.

![](<../.gitbook/assets/image-12 (4).png>)

9. The subcontractor must:
   * Click the verification link in the email.
   * Enter the verification code received by email and click **Verify code**.
   * Click **Continue**.
   * Enter and confirm a new password, then click **Continue**.
   * Accept the end-user license agreement, then click **Continue**.

The new subcontractor user can now access the application and perform their tasks, such as importing missions, planning, and executing missions. Use the following steps to allocate missions to subcontractors, Transporters can assign predefined geographic zones, based on postal codes, to subcontractors. This targeted mission allocation ensures that each subcontractor is responsible for specific areas, enhancing the efficiency of logistics operations. With just a few clicks, transporters can delegate specific missions to subcontractors, reducing manual coordination and streamlining the overall assignment process.

1. Open the Nomadia Delivery application and go to the Missions tab.
2. Select the missions you want to assign from the mission table, click the Actions button, and choose Assign to subcontractor.

![](<../.gitbook/assets/image-13 (4).png>)

3. From the list, select the desired subcontractor to allocate the missions and click Apply.

![](<../.gitbook/assets/image-14 (4).png>)

4. The selected missions will now be assigned to the chosen subcontractor.

![](<../.gitbook/assets/image-15 (4).png>)

Use the following steps to filter missions assigned to subcontractors

1. Open the Nomadia Delivery application and go to the Missions tab.
2. By default, transporters can see all missions created in the delivery management system. To filter missions assigned to specific subcontractors, click the Prefilter option in the mission tab.
3. In the Allotted to drop-down, select the desired subcontractor.
4. Click Apply to display the missions assigned to the selected subcontractor.

![](<../.gitbook/assets/image-16 (4).png>)

5. The mission tab will now show only the missions allocated to the chosen subcontractor.

![](<../.gitbook/assets/image-17 (4).png>)

The Subcontractor Management feature equips transporters with the tools to efficiently outsource logistics operations. By enabling subcontractor setup and management, creation and assignment of subcontractor planners and drivers, mission allocation, subcontractor route creation, zone-based auto-assignment, subcontractor self-sufficiency, and real-time progress tracking, this feature ensures a streamlined and effective logistics management process.

### 1. Optimized Route Plan for Subcontractors

As a subcontractor, you now have enhanced flexibility to plan and manage your missions or deliveries. This improvement allows subcontractors to independently optimize their routes with the help of our advanced algorithm, minimizing reliance on transporter instructions.

However, before subcontractors can create optimized routes, they must first be granted authorization by the primary transporter. The transporter must assign the necessary permissions by:

1. Navigate to the Configuration module.
2. Open the Manage User Profile section.

![](<../.gitbook/assets/image-18 (4).png>)

3. Update the subcontractor’s access by enabling Vehicles and Optimization rights.

![](<../.gitbook/assets/image-19 (4).png>)

4. Once these permissions are granted, subcontractors can log in and use the route optimization features.

![](<../.gitbook/assets/image-20 (4).png>)

Running Optimization with Subcontractor Login

1. Log in to the Nomadia Delivery application with the subcontractor account.
2. Go to the Missions tab.
3. Select the missions to optimize, click the Actions button, and choose Optimize.

![](<../.gitbook/assets/image-21 (4).png>)

4. Define the optimization scope by selecting date range, team, and vehicles, then click Optimize.

![](<../.gitbook/assets/image-22 (4).png>)

5. When satisfied with the outcome, click Stop and see the result.

![](<../.gitbook/assets/image-23 (4).png>)

6. An optimization summary is displayed. Click Display the simulation to analyze results.

![](<../.gitbook/assets/image-24 (4).png>)

Alternatively, click Validate routes to publish results directly without reviewing them.

7. In the Routes panel:
   * Select the routes to validate.
   * Open the **Actions** menu, then click **Validate**.

![](<../.gitbook/assets/image-25 (4).png>)

Confirm by clicking OK.

![](<../.gitbook/assets/image-26 (3).png>)

8. The route is validated, and a confirmation notification appears.

![](<../.gitbook/assets/image-27 (3).png>)

At the bottom of the popup, activate Publish to the mobile app if you want to share the route with the driver.

![](<../.gitbook/assets/image-28 (3).png>)

If conflicts are listed, review them. To proceed anyway, click Force to validate.

9. The validated route is published to the mobile app.

![Screenshot](<../.gitbook/assets/image-29 (3).png>)
