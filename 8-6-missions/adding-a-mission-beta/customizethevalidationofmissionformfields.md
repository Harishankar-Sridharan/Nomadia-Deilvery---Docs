# Customize the Validation of Mission form fields

Customizing mandatory validation enforces required data entries on mission form fields in **Nomadia Delivery**. Dispatchers require mandatory fields to prevent incomplete mission form submissions during daily operations. Configure mandatory fields to ensure accurate field reporting and complete data compliance.

## Before you begin

Administrative requirements and setup steps:

* Administrative access to **Nomadia Delivery** configuration settings.
* Active mission form profile with field identifiers.

Initial setup steps:

1. Select **Configuration** from the main menu.

![Select Configuration from the main menu](../../.gitbook/assets/FormFieldValidation_BeforeBegin_001.gif)

2. Click **Custom fields** to manage form fields.

![Click Custom fields to manage form fields](../../.gitbook/assets/FormFieldValidation_BeforeBegin_002.gif)

## Feature overview

Key user interface elements:

* **Configuration**: Opens global system preferences and customization options.
* **Custom fields**: Displays customizable form fields for missions profiles.
* **Identifier**: Represents a specific mission field selected for validation settings.
* **Mandatory**: Toggles required validation status to force data input before saving.
* **Assign Help**: Defines mandatory field assistance guidelines for field operators.
* **Missions**: Displays the mission database to test updated field validations.

## How To: Configure Mandatory Validation Rules

Configure mandatory validation for mission form fields:

1. Click **Configuration**.

![Click Configuration](../../.gitbook/assets/FormFieldValidation_BeforeBegin_001.gif)

2. Click **Custom fields**.

![Click Custom fields](../../.gitbook/assets/FormFieldValidation_BeforeBegin_002.gif)

3. Select any **Identifier**.

![Select any Identifier](../../.gitbook/assets/FormFieldValidation_ConfigureMandatoryValidationRules_001.gif)

4. Toggle **Mandatory** to enable mandatory field validation.

![Toggle Mandatory to enable mandatory field validation](../../.gitbook/assets/FormFieldValidation_ConfigureMandatoryValidationRules_002.gif)

5. Click **Save**.

![Click Save](../../.gitbook/assets/FormFieldValidation_ConfigureMandatoryValidationRules_003.png)

6. Select **Assign Hub** and make it mandatory.

![Select Assign Hub and make it mandatory](../../.gitbook/assets/FormFieldValidation_ConfigureMandatoryValidationRules_004.gif)

7. Click **Save**.

![Click Save](../../.gitbook/assets/FormFieldValidation_ConfigureMandatoryValidationRules_005.png)

## How To: Apply Validation to Mission Records

Apply mandatory validation rules when editing mission profiles:

1. Navigate to **Missions**.

![Navigate to Missions](../../.gitbook/assets/FormFieldValidation_ApplyValidationMissionRecords_001.gif)

2. Click **Actions**.

![Click Actions](../../.gitbook/assets/FormFieldValidation_ApplyValidationMissionRecords_002.gif)

3. Click **Add**.
4. Click **Agency**.

![Click Agency](../../.gitbook/assets/FormFieldValidation_ApplyValidationMissionRecords_003.gif)

5. Click **Next**.

![Click Next](../../.gitbook/assets/FormFieldValidation_ApplyValidationMissionRecords_004.gif)

6. Select **Edit**.

![Select Edit](../../.gitbook/assets/FormFieldValidation_ApplyValidationMissionRecords_005.gif)

7. Click **Custom fields** and check if the Hub A is Mandatory.

![Click Custom fields and check if the Hub A is Mandatory](../../.gitbook/assets/FormFieldValidation_ApplyValidationMissionRecords_006.gif)

### Result

**Troubleshooting**

Troubleshoot form submission errors:

* **Cannot Save Mission Entry**: Unselected mandatory fields block submission. Select **Assign Hub** before saving.

![Cannot Save Mission Entry: Unselected mandatory fields block submission](../../.gitbook/assets/FormFieldValidation_ApplyValidationMissionRecords_007.png)

## Tips

Best practices and operational warnings:

{% hint style="info" %}
**Automatic Mandatory Updates**: Toggle mandatory field validation to update mandatory rules across mission forms instantly.
{% endhint %}

{% hint style="warning" %}
**Unselected Mandatory Fields**: Do not leave mandatory fields unselected, or the system prevents saving the mission entry.
{% endhint %}

## Related topics

* [Adding a Mission](README.md)
* [Adhoc Address Creation](../../adhocaddresscreation.md)
* [Declaring Parcel for a container mission](../../declaringaparcelforacontainermission.md)
