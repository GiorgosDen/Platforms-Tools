## Exaple 

This is a Node-Red example of a Smart Irrigation System. In this system, two farmers exist. The first is George which has 3 fields, from which the one needs irrigation. The other farmer is Eleni which has 2 fields from which one needs irrigation. So in total, we have 5 fields and 2 of them need to be irrigated. The system makes irrigation decisions based on the sensors data. 

Any field has 4 controllers, two are for the air and the others for soil. Every controller has 2 sensors, one for temperature and the other for humidity. Generally, the Smart Irrigation System is based on IoT technology, which uses a WSN network and other technologies, like sensors and actuators.

In this case, we focus only on WSN and the Sensors. It's not necessary to explain what sensors are doing, but the WSN may not be clear for this example. In general, the WSN network has nodes (every node has sensors or actuators or both), where these communicate wireless (e.g. wifi). These nodes are the field's controllers, but they have only sensors, as I said previously.

In summary, the Node-Red is used to model a Smart Irrigation System based on IoT. In "Flows" folder you can find the Node-Red files, where every one of them implements a field. The other folder, named "Records", contained photos and a video from the total project.
