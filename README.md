NodeRedStarter
==============

starting with Node-Red and Bluemix

see www.bluemix.net

first deploy your app via Bluemix or CF, then use the URL to see it running.

http://<yourappname>.mybluemix.net

Then you can Use Node-Red for building flows 

When you wnat to change this instance you can download the application code:

via command line (CF-tool)

$ cf login -a https://api.ng.bluemix.net -o <your org name> -s <your space name>
API endpoint: https://api.ng.bluemix.net
Warning: Insecure http API endpoint detected: secure https API endpoints are recommended

Username> <your user ID>

Password>*******
Authenticating...
OK

Targeted org <your org name>

Targeted space dev

API endpoint: https://api.ng.bluemix.net (API version: 2.0.0)
User:         <your user ID>
Org:          <your org name>
Space:        <your space name>

After you modified the code, you must deploy again in Bluemix:

$ cf push <yourappname>
