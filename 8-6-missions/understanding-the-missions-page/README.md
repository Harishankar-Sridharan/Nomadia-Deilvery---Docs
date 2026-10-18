# Understanding the Missions Page

A Mission refers to a task that must be executed, typically involving a pick-up location and delivery address. Each mission moves through a sequence of statuses that reflect its current stage. Understanding these statuses is essential for monitoring the progress and handling any exceptions that may occur during the process.

![](<../../.gitbook/assets/image-1 (3).png>)

<table data-header-hidden><thead><tr><th valign="top"></th><th valign="top"></th><th valign="top"></th></tr></thead><tbody><tr><td valign="top">Section ID</td><td valign="top">Section</td><td valign="top">Description</td></tr><tr><td valign="top">A</td><td valign="top">Mission Table</td><td valign="top">Displays ongoing missions in a table format. Supports up to 10,000 entries at a time. Includes sorting and filtering options for easy data access.</td></tr><tr><td valign="top">B</td><td valign="top">Map</td><td valign="top">Interactive map showing mission locations and route paths. Help visualize geographic distribution and real time spatial tracking of mission statuses.</td></tr><tr><td valign="top">C</td><td valign="top">Routes Table</td><td valign="top">Gantt-style view of routes, showing scheduling and duration. Useful for understanding workload and mission sequence. It outlines the agenda for the designated mobile user.</td></tr><tr><td valign="top">D</td><td valign="top">Details</td><td valign="top">Shows detailed information for selected missions or routes, such as deliverer name, time slots, and status. Helps in reviewing and making informed decisions.</td></tr></tbody></table>

## Selection dashboard

The Selection dashboard gives you a quick summary of the missions you have selected. Its header shows how many missions are currently selected, and each widget below it displays a count or a status for that selection.

In the screenshots below, no missions are selected, so every counter shows 0. When you select missions, the dashboard reflects your selection.

### Read the dashboard header

1. Look at the title bar of the dashboard. It is called Selection dashboard. Use the small arrow on the left to expand or collapse the panel.
2. Read the heading Information (0 missions selected). The number in brackets is the number of missions you have selected.

<figure><img src="../../.gitbook/assets/image (226).png" alt=""><figcaption></figcaption></figure>

The Selection dashboard with the Information heading

### Use the dashboard controls

In the top-right corner of the dashboard, find the three controls shown in the screenshot:

* **Add a widget**: the button used to add widgets to the dashboard.
* **Wrench icon**: the settings icon for the dashboard.
* **Enabled switch:** shows that the dashboard is turned on.

<figure><img src="../../.gitbook/assets/image (227).png" alt=""><figcaption></figcaption></figure>

The Add a widget button, the wrench icon, and the Enabled switch

### Read the summary widgets

1. Look at the first row of widgets, directly under the header. Each widget shows one number for your selection:

<table data-header-hidden><thead><tr><th valign="bottom"></th><th valign="bottom"></th></tr></thead><tbody><tr><td valign="bottom">Widget</td><td valign="bottom">What it shows</td></tr><tr><td valign="bottom">Number of missions</td><td valign="bottom">The total number of selected missions.</td></tr><tr><td valign="bottom">Number of customers</td><td valign="bottom">The number of customers concerned by the selected missions.</td></tr><tr><td valign="bottom">Total assigned routes</td><td valign="bottom">The number of routes to which the selected missions are assigned.</td></tr><tr><td valign="bottom">Pickup missions</td><td valign="bottom">The number of selected pickup missions.</td></tr><tr><td valign="bottom">Delivery missions</td><td valign="bottom">The number of selected delivery missions.</td></tr></tbody></table>

<figure><img src="../../.gitbook/assets/image (228).png" alt=""><figcaption></figcaption></figure>

The first row of summary widgets

2. If the last widget is cut off, scroll the panel to the right to see Delivery missions.

<figure><img src="../../.gitbook/assets/image (229).png" alt=""><figcaption></figcaption></figure>

The Delivery missions widget visible after scrolling right

### Check missions by delivery deadline

1. Find the Missions by delivery deadline chart below the first row of widgets.
2. Use the colour legend above the chart to read it:

<table data-header-hidden><thead><tr><th valign="bottom"></th><th valign="bottom"></th></tr></thead><tbody><tr><td valign="bottom">Colour</td><td valign="bottom">Meaning</td></tr><tr><td valign="bottom">Red</td><td valign="bottom">Late (J-1 or earlier): the delivery deadline was yesterday or earlier.</td></tr><tr><td valign="bottom">Orange</td><td valign="bottom">Due today (J0): the delivery deadline is today.</td></tr><tr><td valign="bottom">Green</td><td valign="bottom">Upcoming (J+1 or later): the delivery deadline is tomorrow or later.</td></tr></tbody></table>

<figure><img src="../../.gitbook/assets/image (230).png" alt=""><figcaption></figcaption></figure>

The Missions by delivery deadline chart and its legend

### Check the mission type widgets

1. Scroll down to the next row of widgets. Each widget counts the selected missions of one type:

<table data-header-hidden><thead><tr><th valign="bottom"></th><th valign="bottom"></th></tr></thead><tbody><tr><td valign="bottom">Widget</td><td valign="bottom">What it shows</td></tr><tr><td valign="bottom">Cross-docking missions</td><td valign="bottom">The number of selected cross-docking missions.</td></tr><tr><td valign="bottom">Drop-shipping missions</td><td valign="bottom">The number of selected drop-shipping missions.</td></tr><tr><td valign="bottom">Chained pickup &#x26; delivery missions</td><td valign="bottom">The number of selected missions in which a pickup is chained to a delivery.</td></tr><tr><td valign="bottom">Visit missions</td><td valign="bottom">The number of selected visit missions.</td></tr></tbody></table>

<figure><img src="../../.gitbook/assets/image (231).png" alt=""><figcaption></figcaption></figure>

The row of mission type widgets

### Review the Problems list

1. Scroll down to the Problems list widget.
2. Read the Problems column. It lists the checks the dashboard performs on your selection: Same start address, Mission already assign (0)
3. Read the Yes / No column. Each check has a status indicator. In the screenshot, both checks show a green indicator.

<figure><img src="../../.gitbook/assets/image (232).png" alt=""><figcaption></figcaption></figure>

The Problems list widget with two checks

### Check the selection radius

1. Scroll down to the Selection radius (as the crow flies) widget.
2. Read the value. It is shown in kilometres (Km) and is measured as a straight-line distance, not by road.

<figure><img src="../../.gitbook/assets/image (233).png" alt=""><figcaption></figcaption></figure>

The Selection radius widget showing 0.0 Km

### Scroll to see all widgets

1. Use the vertical scroll bar on the right of the dashboard to move up and down through the widgets.
2. Use the horizontal scroll bar at the bottom of the dashboard to move left and right when a widget or chart is wider than the panel.

<figure><img src="../../.gitbook/assets/image (234).png" alt=""><figcaption></figcaption></figure>

The dashboard scrolled to the right

### Remove a widget

1. Point to the title of a widget. A trash can icon appears next to the title, as shown in the screenshot.
2. Select the trash can icon to remove the widget from the dashboard.

<figure><img src="../../.gitbook/assets/image (235).png" alt=""><figcaption></figcaption></figure>

The trash can icon on a widget title

## Selection dashboard widgets

The **Widgets configuration** window lets you choose which widgets appear on the Selection dashboard. The window has two lists:

* **Available widgets**: widgets that are not currently shown on the dashboard.
* **Displayed widgets**: widgets that are currently shown on the dashboard.

### Available widgets

The following widgets are available to add to the dashboard.

| Widget                        | Description                                                              |
| ----------------------------- | ------------------------------------------------------------------------ |
| Delivery missions             | Shows the number of delivery missions.                                   |
| Missions by delivery deadline | Shows how missions are distributed according to their delivery deadline. |
| Number of routes              | Shows the total number of routes.                                        |
| Pickup missions               | Shows the number of pickup missions.                                     |

### Displayed widgets

The following widgets are currently shown on the dashboard.

| Widget                               | Description                                                                                                                                         |
| ------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------- |
| Chained pickup & delivery missions   | Shows the number of missions in which a pickup is chained to a delivery.                                                                            |
| Cross-docking missions               | Shows the number of cross-docking missions, where goods are transferred from inbound to outbound transport through a hub without long-term storage. |
| Drop-shipping missions               | Shows the number of drop-shipping missions, where goods are sent directly from the supplier to the customer.                                        |
| Number of customers                  | Shows the number of customers concerned.                                                                                                            |
| Number of missions                   | Shows the total number of missions.                                                                                                                 |
| Problems list                        | Lists the problems detected.                                                                                                                        |
| Selection radius (as the crow flies) | Shows the radius of the selection, measured as a straight-line distance.                                                                            |
| Total assigned routes                | Shows the number of routes to which missions are assigned.                                                                                          |
| Total volume                         | Shows the total volume of the missions.                                                                                                             |
| Total weight                         | Shows the total weight of the missions.                                                                                                             |
| Visit missions                       | Shows the number of visit missions.                                                                                                                 |

### Add or remove a widget

1. In the **Widgets configuration** window, select one or more widgets in a list.
2. Use the arrow buttons between the two lists:
   * Select the **right arrow** to move the selected widgets to **Displayed widgets**.
   * Select the **left arrow** to move the selected widgets back to **Available widgets**.
3. Select **Save** to apply your changes, or **Cancel** to close the window without saving.

<figure><img src="../../.gitbook/assets/image (225).png" alt=""><figcaption></figcaption></figure>

### Default Delivery statuses

Below are an overview of the various mission statuses and their significance:

<table data-header-hidden><thead><tr><th valign="top"></th><th valign="top"></th></tr></thead><tbody><tr><td valign="top">Status</td><td valign="top">Description</td></tr><tr><td valign="top">Waiting</td><td valign="top">The mission is expected but not yet received</td></tr><tr><td valign="top">Received</td><td valign="top">The mission has been successfully received</td></tr><tr><td valign="top">To be Delivered</td><td valign="top">The mission is prepared for delivery</td></tr><tr><td valign="top">To be Loaded</td><td valign="top">The mission is waiting to be loaded.</td></tr><tr><td valign="top">Loaded</td><td valign="top">The package is now loaded and in transit</td></tr><tr><td valign="top">To be Picked up</td><td valign="top">Mission is scheduled and awaiting pick up</td></tr><tr><td valign="top">Picked up</td><td valign="top">Item has been collected from the origin</td></tr><tr><td valign="top">Delivered</td><td valign="top">The delivery is completed successfully.</td></tr><tr><td valign="top">Not Received</td><td valign="top">Indicates a mission was expected but couldn’t be received</td></tr><tr><td valign="top">Not Loaded</td><td valign="top">The mission couldn’t be loaded as expected</td></tr><tr><td valign="top">Not Picked up</td><td valign="top">Scheduled pickup was missed or failed.</td></tr><tr><td valign="top">Not Delivered</td><td valign="top">The delivery failed</td></tr><tr><td valign="top">Visited</td><td valign="top">Destination has been successfully visited</td></tr><tr><td valign="top">To be Visited</td><td valign="top">Destination is scheduled for a visit.</td></tr><tr><td valign="top">Not Visited</td><td valign="top">The scheduled visit was missed or unsuccessful.</td></tr></tbody></table>

<figure><img src="../../.gitbook/assets/image (40).png" alt=""><figcaption></figcaption></figure>
