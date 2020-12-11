# Logic App Get-IncidentDetails

author: Sebastien Molendijk

This playbook allows you to get Sentinel incident comments, status, severity, oowner to sync them to ServiceNow.
The playbook performs the following actions:

-

This Logic App must be used with the provided ServiceNow application.
This application is responsible of executint Business rules contacting the Logic App Http endpoint with the relevant updates.

## Deployment

You can use the **Deploy.ps1** script or use the buttons below.

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FSebmolendijk%2FSentinel-Snow%2Fmaster%2FPlaybooks%2FGet-IncidentDetails%2FGet-IncidentDetails.json" target="_blank">
    <img src="https://aka.ms/deploytoazurebutton"/>
</a>
