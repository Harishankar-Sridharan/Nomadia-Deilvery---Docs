# Automated Contractor Tickets and Reminders

Automated contractor tickets and reminders create a ticket for the contractor as soon as a driver records a specific sub-status in the mobile app, such as **Customer Door Closed**. If the contractor does not reply, reminders are posted on a schedule and an email notification is sent. The reminders stop as soon as the contractor replies or the ticket is closed, and every step is logged in the ticket history. Each ticket also gives contractors and your team the full mission context: the mission fields you insert in the template are filled in automatically, a snapshot of the mission is kept at the time of creation, the ticket is visible on the mission, and for container missions a single ticket is created on the parent mission instead of one ticket per item.

## Before you begin

* Sign in to **Nomadia Delivery** with a user profile that has access to the **Tickets** module and to **Configuration**. See [Activating the Ticket Module](activating-the-ticket-module.md).
* Make sure the sub-status that should trigger the ticket exists. See [Manage Substatus](../manage-substatus/README.md).

## Feature overview

* **Ticketing templates**: The page under **Tickets** where you create the templates used for automatic tickets.
* **Ticket template**: A template with an **Identifier**, a **Template name**, an **Enabled** switch, the original message and up to three reminders.
* **Reminders on no response**: Reminders posted when the contractor has not replied. You can add up to three reminders, only one per day, and each new reminder must land on a later day than the one before it, up to D+10.
* **Now editing**: The selector that switches between the **Original message** and each reminder, so that each one has its own ticket title and message.
* **Insert fields in your message**: Dynamic fields, such as **Status**, **Substatus**, **Motive**, **Delivery comment**, **Pickup comment**, **Customer first name**, **Customer last name**, **Name of the contractor** and **Mission numbers**, that are replaced with the mission's values in the ticket.
* **Create ticket**: The completion action of a sub-status that automatically creates a ticket when a mobile user executes this sub-status.
* **Mission details at time of creation**: The section of the ticket that shows the mission status, sub-status, motive, comment, customer name and mission number as they were when the ticket was created.
* **Help tab**: The tab of the mission editor where the mission's tickets are also visible.
* **One ticket per container**: For a container mission, one ticket is created on the parent mission for all its items, instead of one ticket per item.

## Create a ticket template

1. Go to **Tickets** > **Ticketing templates**.

![The Ticketing templates page](../.gitbook/assets/ContractorTickets_001.jpg)

2. Click **Actions**, and then click **New template**.

![Click Actions and then New template](../.gitbook/assets/ContractorTickets_002.jpg)

3. Enter an **Identifier** and a **Template name**.

![Enter the Identifier and the Template name](../.gitbook/assets/ContractorTickets_003.jpg)

4. Make sure the **Enabled** switch is on.

![The Enabled switch of the ticket template](../.gitbook/assets/ContractorTickets_004.jpg)

5. With **Original message** selected in **Now editing**, enter the **Ticket title** and the message in **Instructions for the agent**.

![Enter the ticket title and the message](../.gitbook/assets/ContractorTickets_005.jpg)

6. To add mission data to the message, click the fields under **Insert fields in your message**. For example, `$[Name of the contractor]$` is replaced with the contractor's name in the ticket.

![The dynamic fields you can insert in the message](../.gitbook/assets/ContractorTickets_006.jpg)

7. Under **Reminders on no response**, click **+ Add reminder** and choose the day of each reminder, for example **D+1**, **D+3** and **D+5**.

![Add reminders on no response](../.gitbook/assets/ContractorTickets_007.jpg)

8. In **Now editing**, select each reminder in turn and enter its own **Ticket title** and message.

![Enter the title and message of a reminder](../.gitbook/assets/ContractorTickets_008.jpg)

9. Save the template.

### Result

The template appears in the **Ticketing templates** list, with its number of reminders and its enabled state.

## Add mission fields to a ticket template

1. Go to **Tickets** > **Ticketing templates**, and then click the **pencil icon** next to the template.

![The Ticketing templates page](../.gitbook/assets/MissionDetailsTickets_001.jpg)

2. With **Original message** selected in **Now editing**, place the cursor in **Instructions for the agent** where you want to add a mission value.

![Place the cursor in the message](../.gitbook/assets/MissionDetailsTickets_002.jpg)

3. Under **Insert fields in your message**, click the field to add, for example **Delivery comment**. The field is added to the message as `$[Delivery comment]$`.

![The Delivery comment field added to the message](../.gitbook/assets/MissionDetailsTickets_003.jpg)

4. Save the template.

### Result

In new tickets created from this template, the inserted fields are replaced with the mission's values.

## Link the template to a sub-status

1. Go to **Configuration** > **Sub-statuses**.

![The Sub-statuses page](../.gitbook/assets/ContractorTickets_009.jpg)

2. Click the **pencil icon** next to the sub-status that should trigger the ticket, for example **Customer Door Closed**.

![Open the sub-status, for example Customer Door Closed](../.gitbook/assets/ContractorTickets_010.jpg)

3. Under the completion actions, turn on **Create ticket**, and then choose the **Ticket template**. The **Ticket title** is filled in from the template.

![Turn on Create ticket and choose the Ticket template](../.gitbook/assets/ContractorTickets_011.jpg)

![Create ticket automatically creates a ticket when a mobile user executes this sub-status](../.gitbook/assets/ContractorTickets_012.jpg)

4. Save the sub-status.

### Result

From now on, when a driver records this sub-status in the mobile app:

1. A ticket is created from your template.
2. If the contractor does not reply, the reminders are posted on schedule, for example at D+1, D+3 and D+5, and an email notification is sent.
3. The reminders stop as soon as the contractor replies or the ticket is closed.

## Follow up on an automatic ticket

1. Go to **Tickets** and open the ticket. It shows the original message, with the mission's values in place of the inserted fields.

![The automatic ticket with its original message](../.gitbook/assets/ContractorTickets_013.jpg)

![The ticket message with the values filled in automatically](../.gitbook/assets/MissionDetailsTickets_004.jpg)

2. Check **Mission details at time of creation**. It shows a snapshot of the mission when the ticket was created, such as the mission status, sub-status, motive, comment, customer name and mission number.

![The mission details at the time of creation](../.gitbook/assets/ContractorTickets_014.jpg)

3. Check **Responses**. The reminders are posted there on schedule.

![The reminders posted in the Responses section](../.gitbook/assets/ContractorTickets_015.jpg)

4. To reply, type your response in the response box and click **Reply**.

![The response box](../.gitbook/assets/ContractorTickets_016.jpg)

5. To end the follow-up, click **Close ticket**.

![Click Close ticket](../.gitbook/assets/ContractorTickets_017.jpg)

### Result

When the contractor replies or the ticket is closed, the remaining reminders stop. Every step is logged in the ticket history.

## View the ticket on the mission

1. In the ticket, click **Mission**, or open the mission in the mission editor, and then click the **Help** tab. The ticket is also visible there, with its message and mission details.

![The ticket in the Help tab of the mission](../.gitbook/assets/MissionDetailsTickets_006.jpg)

2. For a container mission, click the tab of the container type, for example **Pallet**. The ticket is created on this parent mission, which lists its child missions.

![The child missions of the parent mission](../.gitbook/assets/MissionDetailsTickets_007.jpg)

### Result

When several items of a container have the same issue, one ticket is created on the parent mission for the whole container, instead of one ticket per item.

![One ticket per container instead of one ticket per item](../.gitbook/assets/MissionDetailsTickets_008.jpg)

## Tips

{% hint style="info" %}
**Reminder schedule**: You can add up to three reminders, only one per day. Each new reminder must land on a later day than the one before it, up to D+10.
{% endhint %}

{% hint style="info" %}
**Insert a field from the keyboard**: Type `$` in the message to insert one of the available fields.
{% endhint %}

{% hint style="info" %}
**Captured at creation**: The mission details in a ticket are captured when the ticket is created. Later changes to the mission do not change them, so the ticket always shows the situation the contractor was asked about.
{% endhint %}

## Related topics

* [Manage Tickets](README.md)
* [Creating a Ticket](creating-a-ticket.md)
* [Manage Substatus](../manage-substatus/README.md)
* [Container child missions](../manage-container-types/container-child-missions.md)
