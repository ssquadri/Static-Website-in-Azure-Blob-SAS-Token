# Static-Website-in-Azure-Blob-SAS-Token

A small static website will be hosted in Azure blob storage(Container) and then we will access it directly with URL and then generate SAS token and then acess it with SAS token

Here is the Step-By-Step Guide to the project

Step 1 -Create A Storage Account in Azure

Setp 2 -Create container (blob storage) inside Azure Storage Account

Step 3 -Upload the HTML code file inside the Container

Step 4 -Once its Uploaded then click on it and then copy its URL (make Sure the container Access tier is anonymous for container and blobs)

Step 5 -Open Incognito in chrome to test the URL

Step 6- Paste the URL and see the website # Screenshot of Landing page is included in this repository

Step 7-Now change the Access tier to Private NO anonymous Access

Step 8 -Repeat the same process of opening and psting URL in Incognito , Website is no longer visible

Step 9-Now go to the HTML file in the container and create SAS token for it (SAS token is limited time & Limited access URL link)

Step 10-Copy the SAS token URL and paste in Incognito to see the result, Also note that once the time is over it will no longer be visible to after time expires.
