# labview-tutorial
In this tutorial we setup a LabVIEW Program to store random generated (measurement)- values in a cloud storage.

## Setup your measurement realm at SolveStrive

Open your browser and got to https://app.solvestrive.com.
Login to the application or create a account.
Add a new measurement realm by clicking the create measurement realm button at the start page.

![Logo](/images/SolveStrive_add_realm.png)

Type in the name of the realm and press create.
Now the realm should be shown at the measurement realm list.
If not reload the page.
Click at the realm.
Now the detail data of the measurement realm are shown.
Here you can find the realm id. This we will ned a bit later.

The next step is to create a API Token.
Go to the administration -> user data.
If the Field API token is empty press the button "Generate API Key"

## Run the Software

Before we start you need to verify that you got LabVIEW 2019 or newer installed on your PC.

Clone or download the Repository on your PC.
If you got Git installed on your PC you can clone the Repository using the command:

```git clone https://github.com/SolveStrive/labview-tutorial.git```

Open the project and the SolveStrive Example.vi.
Copy the Id of your Measurement Realm from the webapp and paste it in the "Realm Id" Input.
Afterwords copy your generated API token and paste it in the Input "ApiKey".
 
 ![Logo](/images/frontend.png)

After that start the program.
When the program is finished, reload the webpage.
Now you should se a new entry with the "Zuordnung" Voltage.
