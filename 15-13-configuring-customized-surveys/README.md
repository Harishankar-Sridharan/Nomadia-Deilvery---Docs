# Configuring Customized Surveys

As a transporter, you can use customized surveys to gather valuable feedback from deliverers and contractors at different stages of their operations. Surveys centralize all data on a single platform, which removes the complexity of managing scattered information and supports data-driven decisions.

## Steps

Follow these steps to set up customizable surveys in Nomadia Delivery:

1. Open the **Configuration** page.
2. From the drop-down, select **Configure the surveys**.
3. Click the **Actions** button and choose **Create** to set up a new survey.

![Click the Actions button and choose Create to set up a new survey](../.gitbook/assets/CustomizedSurveys_Steps_001.png)

Survey Creator / Form Builder is a visual design tool that allows you to create surveys and forms. Surveys can be conducted for four specific use cases:

* Mission Creation – Filled by the contractor before creating a mission in Nomadia Delivery (only for manual creation via the wizard). This helps to capture all necessary details upfront for successful deliveries.
* Route Start – Filled by the deliverer before leaving the agency for delivery/pickup. Collects vehicle condition data to ensure readiness before beginning the route.
* Mission Fulfillment – Filled by the deliverer during delivery or pickup. Tracks delivery milestones and monitors progress in real time.
* Route End – Filled by the deliverer after returning to the agency at the end of the day. Provides insights into vehicle condition post-route, useful for maintenance and operational planning.

![The survey creator showing the four survey types](../.gitbook/assets/CustomizedSurveys_Steps_002.png)

4. Enter the Identifier and Name of the survey, select the survey type from the drop-down, set the Status to Active, and enable the Store all responses toggle to save survey results.

![Enter the Identifier and Name of the survey, select the survey type](../.gitbook/assets/CustomizedSurveys_Steps_003.png)

5. Surveys can contain one or more pages. Each page may include panels and questions. Panels group questions together and can also contain nested panels for structured organization.

![Surveys can contain one or more pages](../.gitbook/assets/CustomizedSurveys_Steps_004.png)

6. For detailed guidance on creating a survey, refer to the documentation: [Create a simple survey](https://surveyjs.io/form-library/documentation/design-survey/create-a-simple-survey)
7. Once the survey is complete, click Save to create it.

![Once the survey is complete, click Save to create it](../.gitbook/assets/CustomizedSurveys_Steps_005.png)

8. The **Configure the surveys** page displays all surveys created in the system.

![The Configure the surveys page listing all surveys](../.gitbook/assets/CustomizedSurveys_Steps_006.png)

## Additional survey configurations

### Assign a survey to contractors

1. Open the Contractors tab in Nomadia Delivery.
2. Edit a contractor by clicking the Pencil icon.

![Edit a contractor by clicking the Pencil icon](../.gitbook/assets/CustomizedSurveys_Contractors_001.png)

3. In the Mission section, assign a survey for mission creation specific to that contractor, then click Save.

![In the Mission section, assign a survey for mission creation specific](../.gitbook/assets/CustomizedSurveys_Contractors_002.png)

4. When logged in as a contractor, creating a mission via the wizard will prompt the mission creation survey, which must be completed before proceeding.

![The mission creation survey shown to a contractor](../.gitbook/assets/CustomizedSurveys_Contractors_003.png)

### Assign surveys to subcontractors

1. Open the Contractors tab.
2. Edit a subcontractor by clicking the Pencil icon.

![Edit a subcontractor by clicking the Pencil icon](../.gitbook/assets/CustomizedSurveys_Subcontractors_001.png)

3. In the Mission section, assign surveys for route start and route end specific to that subcontractor, then click Save.

<figure><img src="../.gitbook/assets/CustomizedSurveys_Subcontractors_002.png" alt="Assign the route start and route end surveys"><figcaption></figcaption></figure>

4. When logged in as a subcontractor deliverer, completing the loading process will trigger the route start survey, which must be filled before starting the missions.

<figure><img src="../.gitbook/assets/CustomizedSurveys_Subcontractors_003.png" alt="The route start survey shown to a subcontractor deliverer"><figcaption></figcaption></figure>

### Assign a survey to a sub-status

1. Open the **Configuration** page.
2. Select Sub status from the drop-down.
3. Edit a sub-status by clicking the Pencil icon.

![Edit a sub-status by clicking the Pencil icon](../.gitbook/assets/CustomizedSurveys_SubStatus_001.png)

4. Assign the appropriate Fulfillment survey from the drop-down and click Save.

![Assign the appropriate Fulfillment survey from the drop-down](../.gitbook/assets/CustomizedSurveys_SubStatus_002.png)

5. When logged in as a transporter or subcontractor deliverer, attempting to fulfill a delivery/pickup will prompt the survey, which must be completed before proceeding.

![When logged in as a transporter or subcontractor deliverer, attempting](../.gitbook/assets/CustomizedSurveys_SubStatus_003.png)

## Analyzing survey responses

1. Open the **Configuration** page.
2. Select **Configure the surveys** from the drop-down.
3. Click the Circle icon next to the survey you wish to analyze.

![Click the Circle icon next to the survey you wish to analyze](../.gitbook/assets/CustomizedSurveys_AnalysingSurveyResponses_001.png)

4. Choose the analysis period and click Apply.
5. Click Load to view results for the selected timeframe.

![Click Load to view results for the selected timeframe](../.gitbook/assets/CustomizedSurveys_AnalysingSurveyResponses_002.png)

6. Review and analyze survey responses in real time.

![Review and analyze survey responses in real time](../.gitbook/assets/CustomizedSurveys_AnalysingSurveyResponses_003.png)

## Configure vehicle photos

1. Open the **Configuration** page and select **Configure the surveys**.
2. Click the **pencil icon** to modify the required survey.
3. Enable the **Capture vehicle photos** option.
4. Specify the **number of photos** to be displayed.

<figure><img src="../.gitbook/assets/CustomizedSurveys_ConfigureVehiclePhotos_001.png" alt="Specify the number of photos to be displayed"><figcaption></figcaption></figure>

### Result

The configured photo fields are displayed on the **Survey** page of the route.

## Related topics

* [Route Editor](../routeeditor.md)
* [Manage Substatus](../manage-substatus/README.md)
* [Vehicle Condition Photos](vehicle-condition-photos.md)
