Set Up and Run the MS3 Contact Management API in your local environment
Follow the steps in this procedure to create and run the API in your own instance of Anypoint Studio.

Open the MS3 Contacts project in Anypoint Studio from Anypoint Exchange.
Within the project in Anypoint Studio, click the Global Elements tab. Double-click the HTTP Listener global element to open its Global Element Properties panel. Change the contents of the port field to the required HTTP port (e.g., 8081).
In the Package Explorer pane in Studio, right-click the project name, then select Run As > Mule Application. Studio runs the application and Mule is up and kicking!
Open your Web browser.
In the address bar, type the following URL to access the API console: http://localhost:8081/console
From the API console, you can view the API resources and their associated operations. You can run each operation in real-time through the console.
Run the MS3 Contact Management API via live deployment on CloudHub
This API has been deployed to the cloud via CloudHub and AWS. To use the live version of this API, access the API console at http://ms3contactsapi.us-e2.cloudhub.io/console/
