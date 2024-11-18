# capgemini

This project is a SharePoint Framework (SPFx) solution that includes three web parts: Home Page, Report Page, and Admin Page. The Admin Page integrates a Power App for CRUD operations.
Home Page:

Displays a welcome message and a brief description.

Report Page:

Displays dynamic reports from the TrainingReports SharePoint list.

Admin Page:

Embeds a Power App for managing training data.
Supports Create, Read, Update, and Delete (CRUD) operations.

Prerequisites
SharePoint Online (Office 365 Tenant).
Node.js (LTS version recommended).
Gulp CLI installed globally:
npm install -g gulp

SPFx Yeoman Generator installed globally:
npm install -g @microsoft/generator-sharepoint

Build the Project
To build the project, run:
gulp bundle --ship

Package the Solution
To create the deployable package:
gulp package-solution --ship
The package will be located in the sharepoint/solution folder.

Deploy the Package
Navigate to your SharePoint App Catalog:

Upload the .sppkg file to the Apps for SharePoint library.
Click Deploy when prompted.

Add to a Site
Go to the SharePoint site where you want to add the web parts.
Navigate to Site Contents > Add an App.
Add your SPFx solution.


Troubleshooting
Web Part Not Appearing: Ensure the solution is deployed and added to the site.
Power App Not Displaying: Verify the Power App ID and user permissions


SharePoint Site URL-
https://sczgh.sharepoint.com/sites/Camgemini/Lists/Training%20Data/AllItems.aspx

Local Workbench Url-
https://sczgh.sharepoint.com/sites/Camgemini/_layouts/15/workbench.aspx

Report Page Local Workbench Url-
https://sczgh.sharepoint.com/sites/Camgemini/_layouts/15/workbench.aspx

I faced challenges to link report page and still data not fatch in same tab and also face challenges in blog container to design all images horizontaly (use display flex but still not set).Some CSS error
