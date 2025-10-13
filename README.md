PS> Set-ExecutionPolicy -ExecutionPolicy Restricted -Scope LocalMachine

Set-ExecutionPolicy : PowerShell updated your local preference successfully, but the setting is
overridden by the Group Policy applied to your system. Due to the override, your shell will retain
its current effective execution policy of "AllSigned". Contact your Group Policy administrator for
more information. At line:1 char:20 + Set-ExecutionPolicy <<<< restricted

PS> Get-ChildItem -Path HKLM:\SOFTWARE\Microsoft\PowerShell\1\ShellIds

Hive: HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\PowerShell\1\ShellIds

Name                    Property
----                    --------
Microsoft.PowerShell    Path            : C:\Windows\System32\WindowsPowerShell\v1.0\powershell.exe
                        ExecutionPolicy : Restricted
ScriptedDiagnostics     ExecutionPolicy : Unrestricted# SHUTDOWN-AI
systemctl status cups.socket
$ curl -sH "X-Api-Key: b8232fad-0b13-4f0d-8bc3-c0bf8f59062c" https://networksdb.io/api/key
data]
  [[outlier]]
    max_deviation = 2.0const userProperties = { isPaid: true };

window.CommandBar.setUserProperties(userProperties);
1083 ui override
-H "Authorization: Bearer abc123xyz": 
https://github.com/duckduckgo/tracker-radar-collector.git
https://www.ipqualityscore.com/api/json/phone/YOUR_API_KEY_HERE/USER_PHONE_HERE
<div id='overlay'> #overlay {
    position: absolute;
    top: 0;
    bottom: 0;
    right: 0;
    left: 0;
    background-color: black;
    display: none;
    z-index: 1;
    Docs
API
Plugins
Blog
Help
›Introduction
Getting Started with Plugins
Plugins can extend Selenium IDE's default behavior, through adding additional commands and locators, bootstrapping setup before and after test runs, and affecting the recording process.

Selenium IDE is using the WebExtension standard to work in modern browsers (to learn more, you can check out Mozilla's Your first extension article). Communicating between the extensions is handled via the external messaging protocol, you can view an example of that here.

This article assumes knowledge in WebExtension development, and will only discuss Selenium IDE specific capabilities.

Calling the API
Selenium IDE API can be called using browser.runtime.sendMessage.

An example signature would be browser.runtime.sendMessage(SIDE_ID, request) where SIDE_ID refers to the IDE's official extension IDs, which can be viewed here.

Request
The request is the second argument for browser.runtime.sendMessage and is similar in it's ideas to HTTP.

{
  uri: "/register",
  verb: "post",
  payload: {
    name: "Selenium IDE plugin",
    version: "1.0.0"
  }
}
uri - a resource locator to an IDE feature (e.g. record a command, resolve a locator)
verb - a modifier function (e.g. get gets you stuff, post adds new stuff, just like in http)
The IDE will reply with a valid response, or in case of an error, this can be viewed by opening the DevTools of the IDE window.

browser.runtime.sendMessage(SIDE_ID, request).then(response => {
  console.log("it worked!");
});
The Manifest
Plugins provide the IDE with a manifest that declares their changes and additions to the IDE's capabilities.

{
  name: "New Plugin",
  version: "1.0.0",
  commands: [
    {
      id: "newCommand",
      name: "new command",
      type: "locator",
      docs: {
        description: "command description",
        target: { name: "command target", value: "command target description" },
        value: { name: "command value", value: "command value description" }
      }
    },
    {
      id: "anotherCommand",
      name: "another command",
      type: "locator",
      docs: {
        description: "another command description",
        target: "locator",
        value: "pattern"
      }
    }
  ],
  locators: [
    {
      id: "locator"
    }
  ],
  dependencies: {
    "selenium-webdriver": "3.6.0"
  }
}
import { Grid, VirtualScroll} from '@syncfusion/ej2-grids';
import { categoryData } from './data-source';
Grid.Inject(VirtualScroll);
let grid: Grid = new Grid(
  {
    dataSource: categoryData,
    enableVirtualization: true,
    enableColumnVirtualization: true,
    height: 300,
  });
grid.appendTo('#Grid');
{
  "headers": {
    "schema": "st-schema",
    "version": "1.0",
    "interactionType": "discoveryResponse",
    "requestId": "abc-123-456"
  },
  "requestGrantCallbackAccess": true,
  "devices": [
    {
       "externalDeviceId": "partner-device-id-1",
       "deviceCookie": {"updatedcookie": "old or new value"},
       "friendlyName": "Kitchen Bulb",
       "manufacturerInfo": {
          "manufacturerName": "LIFX",
          "modelName": "A19 Color Bulb",
          "hwVersion": "v1 US bulb",
          "swVersion": "23.123.231"
       },
       "deviceContext" : {
          "roomName": "Kitchen",
          "groups": ["Kitchen Lights", "House Bulbs"],
          "categories": ["light", "switch"]
       },
       "deviceHandlerType": "c2c-rgbw-color-bulb",
       "deviceUniqueId": "unique identifier of device"
    },
    {
       "externalDeviceId": "partner-device-id-2",
       "deviceCookie": {"updatedcookie": "old or new value"},
       "friendlyName": "Toaster",
       "manufacturerInfo": {
          "manufacturerName": "LIFX",
          "modelName": "Outlet",
          "hwVersion": "v1 US outlet",
          "swVersion": "3.03.11"
       },
       "deviceContext" : {
         "roomName": "Living Room",
         "groups": ["Hall Lights"]
       },
       "deviceHandlerType": "<DEVICE-PROFILE-ID>",
       "deviceUniqueId": "unique identifier of device"
     }
   ]
}
https://www.hifiboehm.de/de/produkt/sonos-sub-4-weiss
Files ~ "\.pdf$">
Header set X-Robots-Tag "noindex, nofollow"
</Files>
