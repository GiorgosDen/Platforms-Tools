## Node-Red

### General:
Node-RED is an open-source platform (developed with JavaScript), that provides a browser-based editor that makes it easy to wire together flows using a wide range of nodes. It has compelling documentation and community, that makes it simple to start the road map in Node-RED. From the official site (https://nodered.org/) you can find the appropriate guidance to install Node-RED, locally, on a device (ex. Raspberry), or in the cloud. I choose to use Node-RED locally and a simple way for this is, by following the README file from the GitHub repository (https://github.com/node-red/node-red/tree/master).

### MQTT Broken (Mosquitto):
The MQTT broker is the backend system that coordinates messages between clients. The MQTT broker receives and filters customers' messages, identifies clients subscribed to each message, and sends the messages to these subscribed clients.The most common MQTT broker in node-red is "Mosquitto broker", an open-source MQTT project. You can find more about "Mosquitto broker" at this address: https://mosquitto.org/

### Dashboard:
You can also graphically represent the results of node-red flows, at the dashboard tool. The dashboard is an external node-red library, that can be downloaded easily in node-red (user settings -> palette ->install). You can see the dashboard's panel at the address  http://localhost:1880/ui if you are using the local version.

### MySQL: 
In node-red, you can download an extra palet/library, the node-red-node-mysql, which can connect a MySQL server with node-red. More specifically, with "mysql"  node (from node-red-node-mysql), you can add a new connection with MySQL DB. More information about that can be found in this video: https://www.youtube.com/watch?v=w1SRebmR_NY
