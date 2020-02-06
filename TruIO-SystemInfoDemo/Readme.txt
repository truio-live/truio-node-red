Tested with:
Node-red v1.0.3
Ubuntu 18.04

Known issue:
1. Drivers node in the node-red-contrib-os is not compatible with Windows OS and will crash node-red.

How to use:
1. Import the "TruIO-SystemInfoDemo.json" into your Node-red
2. Insert your device key to TruIO subflows node.
3. Insert your device key as the username and password for MQTT connection.
4. Deploy your Node-red

Node-red Palette pre-requisite:
1. node-red-contrib-cpu
2. node-red-contrib-os
3. node-red-dashboard