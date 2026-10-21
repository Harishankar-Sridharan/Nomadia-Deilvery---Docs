# Fixed and Recurring Plans

This guide offers step-by-step instructions for transporters on creating fixed and recurring plans for Nomadia Delivery. These features are designed to support contractors with long-term delivery and pick-up commitments by simplifying the planning process, improving accuracy, and providing flexibility for managing routes over extended periods.

## Before you begin

* Sign in to **Nomadia Delivery** with a user profile that has access to the **Contractors** tab.
* Make sure the contractor you want to plan for exists and has addresses in its **Address List**.
* Know the start and end dates of the optimization period and the vehicles for which the routes need to be created.

## Feature overview

The route plan details are:

* **Name**: Assign a name for easy reference in the future.
* **Enabled**: Switch on the toggle to activate the route plan.
* **Dedicated Routes**: Enable this option if the plan should generate dedicated routes that cannot be combined with other contractors' missions.
* **Recurrent**: Turn on this option to make the plan recurring.
* **From & To**: Specify the start and end dates to define the validity period of the plan.
* **Repeat Every**: Set the recurrence frequency (weekly or monthly).
* **Days of the Week**: Choose the days the plan should repeat and set the spacing between recurrences as required.

## Create a fixed and recurring plan

1. Open the Nomadia Delivery application and go to the **Contractors** tab.

![](<../.gitbook/assets/image-1 (7).png>)

2. Select the contractor for whom you want to create a fixed and recurring plan and click the pencil icon to edit.

![](<../.gitbook/assets/image-2 (8).png>)

3. Navigate to the **Address List**.
4. Select the addresses where you want to create the fixed and recurring plan.

![](<../.gitbook/assets/image-3 (7).png>)

5. Open the **Actions** menu and choose **Add to a simulation**.

![](<../.gitbook/assets/image-4 (7).png>)

6. Click **Create simulation** or select an existing simulation from the **Select a simulation** drop-down.

![](<../.gitbook/assets/image-5 (7).png>)

7. Define the start and end dates of the optimization period.

![](<../.gitbook/assets/image-6 (7).png>)

8. Select the vehicles for which the routes need to be created.
9. Click **Optimize** to launch the optimization process.

![](<../.gitbook/assets/image-7 (7).png>)

10. Click **Stop** once optimization is running to see the results, then click **Display simulation** to view the outcome.

![](<../.gitbook/assets/image-8 (6).png>)

11. If the results are satisfactory, go to the **Routes** section, open the **Actions** menu, and select **create the route plan**.

![](<../.gitbook/assets/image-9 (6).png>)

12. Click **OK** to confirm and begin creating the route plan.

![](<../.gitbook/assets/image-10 (5).png>)

13. Fill in the route plan details described in the feature overview.
14. Click **Save** to store the recurrent route plan.

![](<../.gitbook/assets/image-11 (5).png>)

### Result

A confirmation notification appears once the plan is successfully created.

![Screenshot](<../.gitbook/assets/image-12 (5).png>)

All saved route plans can be accessed from the Address List page in the contractor module.

![](<../.gitbook/assets/image-13 (5).png>)

## Access route plans from the Mission page

1. Open the Nomadia Delivery application and go to the **Missions** tab.
2. Click the **Panel** icon to enable panel customization.

![](<../.gitbook/assets/image-14 (5).png>)

3. Drag and drop the **Route Plan** panel to your desired location.

![](<../.gitbook/assets/image-15 (5).png>)

4. Click the **Route Plan** panel again to exit the panel editing mode.

![](<../.gitbook/assets/image-16 (5).png>)

## Generate missions on the scheduled day

On the day of delivery or pickup, missions can either be:

* Created directly by the contractor through the Contractor Portal.
* Auto-created by the transporter to make the deliveries.

If missions have already been created by the contractor:

1. Open the **Actions** menu and select **Apply the route plan**.

![](<../.gitbook/assets/image-17 (6).png>)

If the transporter needs to create missions on behalf of the contractor:

1. Click **Generate the deliveries** to create delivery missions.
2. Click **Generate the pickups** to create pickup missions.

![](<../.gitbook/assets/image-18 (6).png>)

3. Click **Yes** to confirm and generate missions for all customers included in the recurrent plan.

![](<../.gitbook/assets/image-19 (6).png>)

### Result

Nomadia Delivery automatically creates the missions for all customers associated with the recurrent route plan.

![](<../.gitbook/assets/image-20 (6).png>)

## Execute the route plan on the delivery day

On the day of delivery, contractors may create missions only for selected customers, such as some orders might decline due to reasons such as stock shortages or customer unavailability.

To validate the route plan:

1. Open the **Actions** menu and select **Apply the route plan**.

![](<../.gitbook/assets/image-17 (6).png>)

2. Compare the predefined route plan with the missions created in Comparison Mode. This helps transporters assess the percentage of the route plan that will be executed in real time.

![](<../.gitbook/assets/image-22 (6).png>)

3. Click **Validate** to generate the final route plan.

![](<../.gitbook/assets/image-23 (6).png>)

By following these steps, transporters can efficiently manage fixed and recurring plans in Nomadia Delivery, ensuring smooth operations and reliable service for contractors and their customers.

## Tips

{% hint style="warning" %}
**No linked missions**: If no missions are linked to the selected route plan, the system displays an error notification.
{% endhint %}

## Related topics

* [Contractors](README.md)
* [Register a Contractor](registration.md)
* [Manage Address List](manage-address-list.md)
* [Optimize deliveries](../simulation/simulation-deliveries-optimize.md)
