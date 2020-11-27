# Logic App New-SnowIncidentFromSentinel

author: Sebastien Molendijk

This playbook allows you to create ServioceNow incidents, based on Azure Sentinel incidents properties.
The playbook performs the following actions:

- Get the Sentinel incident ID, based on the alert
- Creates a ServiceNow incident with the name of the alert and uses the incident guid as \*\*Correlation ID"
- Add the ServiceNow incident number as a tag to the Azure Sentinel incident
- Add a direct link to the Azure Sentinel incident to the ServiceNow incident Work notes

This Logic App must be used with the provided ServiceNow application.
This application is responsible of executint Business rules contacting the Logic App Http endpoint with the relevant updates.

## Deployment

You can use the **Deploy.ps1** script or use the buttons below.

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FSebmolendijk%2FSentinel-Snow%2Fmaster%2FPlaybooks%2FNew-SnowIncidentFromSentinel%2FNew-SnowIncidentFromSentinel.json" target="_blank">
    <img src="https://aka.ms/deploytoazurebutton"/>
</a>
