# Appointment Booking Portal

The appointment booking portal in Nomadia Delivery enables you to schedule optimized slots for missions, ensuring alignment with the deliverers’ existing tour plans. This guide outlines how to use the portal’s features to improve scheduling efficiency.

To configure Nomadia Delivery for the appointment booking portal, the transporter should follow these steps:

1. Open the Nomadia Delivery application and go to the Configuration tab.

![](<../.gitbook/assets/image-1 (5).png>)

2. From the drop-down menu, select Configure customer experience pages.

![](<../.gitbook/assets/image-2 (5).png>)

3. Click on the Schedule a delivery option.

![](<../.gitbook/assets/image-3 (5).png>)

4. Open the Planning tab. This tab allows the transporter to define the time slots that will be available for booking in the appointment portal.

![](<../.gitbook/assets/image-4 (5).png>)

5. Click within the grey area to set the availability of your deliverers.

![](<../.gitbook/assets/image-5 (5).png>)

6. Choose the preferred days and times according to your delivery preferences, then save the planning.

**Note**: The delivery slots defined here are the ones proposed by the real-time optimization engine. Ensure you configure them carefully to avoid unwanted slot suggestions during breaks (e.g., lunch, briefing, or debriefing times). You can either apply the same slots across all days of the week or configure different slots for each day. Once the setup is complete, the planning view will display the preferred slots, as shown in the example screenshot.

![](<../.gitbook/assets/image-6 (5).png>)

7. Finally, click Save to confirm the planning.

![](<../.gitbook/assets/image-7 (5).png>)

To update or delete an existing plan, follow these steps

1. Click on the blue area to open the planning you want to modify

![](<../.gitbook/assets/image-8 (4).png>)

2. Adjust the date and time as needed and click Update to save the changes or delete to remove the plan.

**Note**: Slot proposals are influenced by multiple factors, such as user availability, vehicle availability, and mission opening times. Make sure your slot definitions take these factors into account.

To reserve a slot through the appointment booking portal, follow these steps:

1. Launch the Nomadia Delivery application and go to the Missions tab.
2. Select any existing mission by clicking the pencil icon to edit it.

![](<../.gitbook/assets/image-9 (4).png>)

3. Then, click the ‘Appointment Booking’ button to view the available slot proposals.

![](<../.gitbook/assets/image-10 (3).png>)

Please note that the ‘Appointment Booking’ feature is available only for standard pickup or delivery missions. It will be disabled for the following mission types:

* Cross-docking
* Chained pickup & delivery

For these missions, a tooltip message, as shown in the screenshot below, will appear.

![](<../.gitbook/assets/image-11 (3).png>)

The real-time optimization engine suggests slots by considering vehicle and user availability, as well as mission schedules, based on the pre-defined slots configured during setup.

![](<../.gitbook/assets/image-12 (3).png>)

The proposed slots are categorized based on the star rating

* 1-star: The proposed slot is more than 30 minutes away from the existing tour plans in the back office.
* 2-star: The proposed slot is between 10 and 30 minutes away from the existing tour plans in the back office.
* 3-star: The proposed slot is less than 10 minutes away from the existing tour plans in the back office.

![](<../.gitbook/assets/image-13 (3).png>)

The user can choose any of the proposed slots and click the ‘Choose’ button to either create a new tour plan for the selected slot (if no existing tour is scheduled in the back office at that date and time) or add the mission to an existing tour plan.

![](<../.gitbook/assets/image-14 (3).png>)

Once the slot is successfully booked, a notification will appear in the back office.

![](<../.gitbook/assets/image-15 (3).png>)

Return to the Missions tab to confirm that the tour has been created or updated for the selected date and time.

![](<../.gitbook/assets/image-16 (3).png>)

### 1. Booking Portal Configuration

The I-Frame Booking Portal is designed to give transporters a flexible and seamless booking solution that can be directly embedded into contractor websites. Its purpose is to boost customer engagement by enabling optimized delivery slot booking and providing a hassle-free user experience.

To configure Nomadia Delivery for the appointment booking portal, transporters need to follow these steps:

1. Open the Nomadia Delivery application and go to the Configuration tab.
2. From the drop-down menu, select Configure customer experience pages.

![](<../.gitbook/assets/image-17 (3).png>)

3. Choose the Schedule a delivery menu item.
4. Open the Booking portal tab.
5. Turn on the toggle Display the booking portal.
6. Configure the fields you want to display to the end customer to capture details needed for successful delivery. By default, Name and Address are mandatory, as they are essential for locating the customer.
7. Click Add a field to include additional fields.

![](<../.gitbook/assets/image-18 (3).png>)

8. Specify the field name and select the field type (Text, Checkbox, Multiline Text, List of values, Number or date).

Example: Field name – Access Code (the code the deliverer needs to access the customer’s premises).

9. Choose the Mode for the field, such as Input Required, Hidden, Read-only, or Read/Write, to define the customer’s control when filling out the form.

![](<../.gitbook/assets/image-19 (3).png>)

10. Click Add to include the custom field in the form.

![](<../.gitbook/assets/image-20 (3).png>)

The field will now appear in the list of data to be collected from the customer.

![](<../.gitbook/assets/image-21 (3).png>)

To integrate the booking portal into the contractor’s website, transporters should follow these steps: Copy the code sample from the booking portal.

![](<../.gitbook/assets/image-22 (3).png>)

Share it with the contractor for integration.

The URL in the code sample automatically redirects to the booking portal and can be embedded into an I-frame on the contractor’s website.

![](<../.gitbook/assets/image-23 (3).png>)

The I-frame allows customers to directly schedule deliveries.

The customer can click Schedule to view real-time optimized time slots and then select their preferred slot by clicking Choose.

![](<../.gitbook/assets/image-24 (3).png>)

The booking portal is directly linked with the drivers’ tour plans in Nomadia Delivery application. Once the booking is confirmed:

* A mission is automatically created.
* The mission is optimally scheduled and added to the driver’s real-time tour.

![](<../.gitbook/assets/image-25 (3).png>)

The I-Frame Booking Portal helps transporters boost their digital presence and customer

* Engagement by offering:
* Seamless integration
* Customizable booking forms
* Easy administration
* Optimized delivery slots
* Slot confirmation notifications

### 2. Rescheduling a Mission

This guide offers step-by-step instructions for transporters using Nomadia Delivery, enabling end customers to conveniently reschedule their delivery or pickup missions. These new features enhance customer convenience and communication by allowing them to select a time slot that suits their schedule.

To set up the rescheduling button in email communications, follow these steps:

1. Launch the Nomadia Delivery application and go to the Configuration tab.

![](<../.gitbook/assets/image-26 (4).png>)

2. From the drop-down menu, select Configure Customer Experience Pages.

![](<../.gitbook/assets/image-27 (4).png>)

3. Click on the Before the Delivery menu item.
4. Enable the Reschedule a Delivery toggle to activate the reschedule button in customer email communications

![](<../.gitbook/assets/image-28 (4).png>)

5. Set the rescheduling link validity using the Disable Before Delivery option. You can configure the link to be active from a maximum of 12 hours before delivery to a minimum of 3 hours before delivery, based on your operational requirements.

![](<../.gitbook/assets/image-29 (4).png>)

6. Click Save to apply and save the rescheduling configuration.

![](<../.gitbook/assets/image-30 (3).png>)

To set up the rescheduling link in customer email communications, follow these steps:

1. Launch the Nomadia Delivery application and go to the Configuration tab.

![](<../.gitbook/assets/image-31 (3).png>)

2. From the drop-down menu, select Configure Outgoing Messages.

![](<../.gitbook/assets/image-32 (3).png>)

3. Click on the Email Templates menu item.

![](<../.gitbook/assets/image-33 (3).png>)

4. Click on Actions dropdown menu and select Add

![](<../.gitbook/assets/image-34 (3).png>)

5. Click the “Time window to communicate”

![](<../.gitbook/assets/image-35 (3).png>)

6. Enable Outgoing Emails to allow communication with the end customer.
7. When composing the message, use the $ keyword to insert mission-specific links and values.
8. Click on Save

.

![](<../.gitbook/assets/image-36 (3).png>)

To send email notifications to the end customer, follow these steps:

1. Navigate to the Missions tab and assign a mission to a deliverer.
2. Click the Actions menu and select Publish on Mobile App.

![](<../.gitbook/assets/image-37 (3).png>)

3. Enable the Send Delivery Notes toggle to send email notifications to end customers, then click OK.

![](<../.gitbook/assets/image-38 (3).png>)

4. A popup will appear confirming that emails have been sent, showing the number of emails delivered.

![](<../.gitbook/assets/image-39 (3).png>)

Please note that the mission has been set up with the delivery/pickup email address, allowing Nomadia Delivery to send email notifications to your end customer.

![](<../.gitbook/assets/image-40 (3).png>)

To reschedule a mission, the end customer should follow these steps

1. On the day of delivery, the customer will receive an email.

![](<../.gitbook/assets/image-41 (3).png>)

2. The customer should click the link in the email to reschedule the mission.

![](<../.gitbook/assets/image-42 (3).png>)

3. If the proposed date and time are not convenient, the customer can click the Reschedule button.

![](<../.gitbook/assets/image-43 (3).png>)

4. The customer can then choose any of the available slots suggested by the real-time optimization engine.

![](<../.gitbook/assets/image-44 (3).png>)

5. Time slots marked with a green leaf indicate eco-friendly options, showing that a deliverer will be nearby at that time, making it the most optimal choice.
6. After selecting a preferred slot, the customer should click the Choose button.

![](<../.gitbook/assets/image-45 (3).png>)

7. A confirmation of the selected slot is sent to the end customer.

![](<../.gitbook/assets/image-46 (3).png>)

8. The route plan is automatically updated based on the customer’s chosen slot.
