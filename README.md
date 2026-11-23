# Introduction

Nomadia Delivery is a cloud-based SaaS solution designed to streamline and optimize logistics and distribution processes. The platform enables efficient management of delivery operations by organizing shipments into Missions—each representing a logistical flow of goods from a point of origin to a delivery destination. A Mission can involve a parcel, pallet, or any other transportable container. Each Mission follows a journey from a origin to destination. For example, a Mission could involve a pallet of vegetables departing from a central warehouse to be delivered to a local grocer. Missions are tracked using a series of statuses—such as Waiting, Received, Loaded, To Be Delivered, Delivered, and more—providing complete traceability throughout the delivery lifecycle. Additional information, including status history, photos, and key journey details, is also recorded to ensure comprehensive transparency.

The platform supports management of up to 500,000 Missions, with powerful filtering and sorting features available to help users focus on the Missions relevant to their operations.

## Before you begin

* Have the Missions you want to manage available, for example as an Excel spreadsheet or through an API import.
* Know the Route and the delivery resource to which Missions will be assigned.

## Feature overview

* **Mission**: A logistical flow of goods from a point of origin to a delivery destination, such as a parcel, pallet, or any other transportable container.
* **Statuses**: Track each Mission, such as Waiting, Received, Loaded, To Be Delivered, and Delivered.
* **Backoffice**: Where Missions are imported, progress through statuses, and are assigned to a Route.
* **Mobile Application**: Where delivery personnel update Mission statuses until they reach Delivered.

## In the Backoffice

* Missions (such as parcels or pallets) can be imported into the system through various methods, including Excel spreadsheets and APIs.
* Each mission progresses through defined statuses until it reaches the 'To Be Delivered' status."
* Missions are then assigned to a specific Route, along with the designated delivery resource.

## In the Mobile Application

* The delivery personnel continue updating the Mission statuses as they progress through their route, ultimately reaching the Delivered status.

## Who this guide is for

| Reader | What you will find | Start here |
| ------ | ------------------ | ---------- |
| **Dispatchers and planners** | How to work every day: missions, routes, simulations, contractors, subcontractors and tickets. | [Operations guide](#operations-guide) |
| **Administrators** | How to set up the back office: users, addresses, containers, documents, notifications, zones and fleets. | [Administrator guide](#administrator-guide) |
| **Integrators** | How to connect Nomadia Delivery to other systems. | [Integration](#integration) |

## Guide contents

### Getting started

| Section | What you will find |
| ------- | ------------------ |
| [Nomadbot](chatbot.md) | The virtual assistant that answers your questions. |
| [Latest updates](summer-release-topics-2026/README.md) | The new features of each release: [Summer Release 2026](summer-release-topics-2026/summer-release-topics-2026.md) and [Fall Release 2026](fall-release-2026/fall-release-2026.md). |
| [Home Page](readme-1/README.md) | The home screen, its KPIs and its mission statuses. |

### Operations guide

| Section | What you will find |
| ------- | ------------------ |
| [Missions](8-6-missions/README.md) | Create, import, find, edit and track missions, and configure their forms and custom fields. |
| [Routes](8-6-missions-1/README.md) | Create, assign, view and finish routes. |
| [Simulation](simulation/simulation.md) | Optimize deliveries, adjust the routes and validate them. |
| [Contractors](9-7-contractors/README.md) | Register contractors and manage their users, addresses, restrictions and plans. |
| [Subcontractor Management](10-8-subcontractor-management/README.md) | Register subcontractors, create their users and assign missions to them. |
| [Return to Contractor](return-to-contractor.md) | Create the return missions for undelivered parcels. |
| [Manage Tickets](manage-tickets/README.md) | Report and resolve mission queries between contractors and transporters. |
| [Custom Dashboards](14-12-custom-dashboards/README.md) | Build and customize your dashboards. |

### Administrator guide

| Section | What you will find |
| ------- | ------------------ |
| [Manage Users](7-5-manage-users/README.md) | Users, profiles, access, roles and rights, and days off. |
| [Manage Global Address List](manage-global-address-list.md) | The master record of customer addresses. |
| [Manage Articles](manage-articles/README.md) | The catalog of articles delivered with missions. |
| [Manage Container Types](manage-container-types/README.md) | Container types, child missions, inheritance and container tracking. |
| [Manage document library](manage-document-library/README.md) | Shared documents and the documents of missions. |
| [Manage Document Templates](manage-document-templates/README.md) | Word templates, eCMR and QR codes. |
| [Manage Notifications](manage-notifications/README.md) | Email and SMS notifications and their templates. |
| [Alert Management](alertmanagement.md) | Alert thresholds. |
| [Manage Studies & Zones](manage-studies-and-zones/README.md) | Postal zones and sectorization. |
| [Manage Substatus](manage-substatus/README.md) | Sub-statuses and their notifications. |
| [Manage Vehicle Fleets](manage-vehicle-fleets/README.md) | Vehicles, fleets, constraints and lunch locations. |
| [Booking Portal](11-9-appointment-booking-portal/README.md) | Booking and rescheduling of delivery slots by customers. |
| [Configuring Customized Surveys](15-13-configuring-customized-surveys/README.md) | Surveys and vehicle condition photos. |
| [Customize Navigation Tabs](customize-navigation-tabs.md) | The order of the header tabs. |
| [Keyboard Shortcuts Configuration](keyboard-shortcuts-configuration.md) | The keyboard shortcuts of the back office. |

### Integration

| Section | What you will find |
| ------- | ------------------ |
| [Secure API Key Management](secure-api-key-management.md) | The API keys of your integrations. |
| [Custom Actions](custom-actions.md) | Buttons that call external systems from the back office. |

### Scenarios

| Section | What you will find |
| ------- | ------------------ |
| [Case Studies](case-studies/README.md) | End-to-end scenarios: zones, subcontractor swaps, PUDO, multi-leg missions, reverse logistics and No Route mode. |

### Reference

| Page | What you will find |
| ---- | ------------------ |
| [Find a Topic (A–Z)](reference/find-a-topic.md) | Every topic of the guide in alphabetical order. |
| [Glossary](reference/glossary.md) | The meaning of the words used in the back office and in this guide. |

## I want to...

| I want to... | Go to |
| ------------ | ----- |
| Understand the home screen | [Understanding the Home Screen](readme-1/understanding-the-home-screen.md) |
| Create a mission | [Adding a Mission](8-6-missions/adding-a-mission-beta/README.md) |
| Import missions from Excel | [Import Missions](8-6-missions/import-missions/README.md) |
| Find a mission | [Search for a Mission](8-6-missions/understanding-the-missions-page/search-for-a-mission.md) |
| Change several missions at once | [Bulk Edit Mission Data](8-6-missions/bulk-edit-mission-data.md) |
| Optimize my deliveries into routes | [Optimize deliveries](simulation/simulation-deliveries-optimize.md) |
| Validate the routes of a simulation | [Validate routes](simulation/simulation-routes-validate.md) |
| Create a route by hand | [Manual Route Creation](8-6-missions-1/manualroutecreation.md) |
| Register a contractor | [Register a Contractor](9-7-contractors/registration.md) |
| Assign missions to a subcontractor | [Assigning missions to subcontractor](10-8-subcontractor-management/assigning-missions-to-subcontractor.md) |
| Create a user | [Creating User from a Scratch](7-5-manage-users/creating-user-from-a-scratch.md) |
| Send email or SMS notifications | [Manage Notifications](manage-notifications/README.md) |
| Customize a Word document template | [Customizing Word Templates](manage-document-templates/customizing-word-templates.md) |
| Connect an external system | [Custom Actions](custom-actions.md) and [Secure API Key Management](secure-api-key-management.md) |
| Limit the missions loaded on the Missions page | [Set missions display (prefilter)](8-6-missions/understanding-the-missions-page/pre-filters/set-missions-display-prefilter.md) |
| Select many missions at once | [Shift-Click Range Selection](8-6-missions/understanding-the-missions-page/shift-click-range-selection.md) |
| Copy a mission configuration | [Clone a Mission Configuration](8-6-missions/clone-a-mission-configuration.md) |
| Move mission configurations to another account | [Import and Export Mission Configurations as JSON](8-6-missions/import-and-export-mission-configurations-as-json.md) |
| Choose which address blocks a user profile sees | [Address List Block Visibility per User Profile](customizetheaddresslistvisibility/address-list-block-visibility-per-user-profile.md) |
| See what is new | [Fall Release 2026](fall-release-2026/fall-release-2026.md) |
| Find a topic by name | [Find a Topic (A–Z)](reference/find-a-topic.md) |
| Understand a word | [Glossary](reference/glossary.md) |

## Tips

{% hint style="info" %}
**Real-time synchronization**: Each time a Mission status is updated, the changes are immediately synchronized with the Backoffice database in real time, ensuring consistent and up-to-date information across all platforms.
{% endhint %}

## Related topics

* [Home Page](readme-1/README.md)
* [Missions](8-6-missions/README.md)
* [Routes](8-6-missions-1/README.md)
* [Find a Topic (A–Z)](reference/find-a-topic.md)
* [Glossary](reference/glossary.md)
