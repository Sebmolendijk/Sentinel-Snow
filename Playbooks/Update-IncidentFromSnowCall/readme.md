# Logic App Update-IncidentFromSnowCall

author: Sebastien Molendijk

This playbook allows you to update Azure Sentinel incidents, based on ServiceNow incident properties.
The supported actions are:

- Assign Azure Sentinel incident based on ServiceNow incident owner
- Set Azure Sentinel incident severity based on ServiceNow incident impact
- Set Azure Sentinel incident status based on ServiceNow incident state
- Add comments to Azure Sentinel incident, based on ServiceNow Work notes (soon)
- Add ServiceNow incident number as tag to the Azure Sentinel incident

This Logic App must be used with the provided ServiceNow application.
This application is responsible of executint Business rules contacting the Logic App Http endpoint with the relevant updates.

## ServiceNow application details (soon)

## Deployment

You can use the **Deploy.ps1** script or use the buttons below.

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FSebmolendijk%2FSentinel-Snow%2Fmaster%2FPlaybooks%2FUpdate-IncidentFromSnowCall%2FUpdate-IncidentFromSnowCall.json" target="_blank">
    <img src="https://aka.ms/deploytoazurebutton"/>
</a>
