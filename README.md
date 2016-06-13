# PowerBIDashBoard
PowerBI DashBoard with PowerBI Embedded Integration

Follow these steps to embedded the Power BI dashboard into your application.

Step 1: Download the pbix file.

Step 2: Create a powerbi embedded workspace collection in the Azure portal,follow this link 
https://azure.microsoft.com/en-us/documentation/articles/power-bi-embedded-get-started/

Step 3: Download the solution and set the "ProvisionSample" as the start up project, select option 4 to register,
while registering select the pbix file in this sample.

Step 4: After registering the pbix file then set the "Embed Sample" as the start up project, modify these following tags in the web.config:

AccessKey,WorkspaceCollection,WorkspaceId , these values can be obatained from the Azure portal Power BI Embedded Workspace.

This should help embedding the Power BI Dashboard within your application.
