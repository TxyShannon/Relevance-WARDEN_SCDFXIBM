![Logo](https://github.com/TxyShannon/Relevance-WARDEN_SCDFXIBM/blob/master/docs/Logo.png)
## What is Project Warden?
Wide Area Responsive District Emergency Network.

Project Warden is an initiative to create an inter-weaving system of IoT enabled devices within a Smart Environment (Punggol Digital District in Singapore). As the Smart Environment is constructed ground up with the intention of embedding multiple IoT sensors, Project Warden requires no additional implementation cost in terms of IoT devices. We simply make use of the existing devices within the Smart Environment to help determine potential disasters. It primarily tackles **slow response times** and **shortage of manpower** .

## How does Project Warden work?
Within a Smart Environment, there are bound to be temperature sensors and IP cameras which will all be connected to a single controlling system. When any temperature sensor is triggered over a threshold, the system will search for nearby IP cameras that overseas the coverage of the sensor. The cameras will query the IBM Cloud Service for Object Detection to verify if the area around the sensor has any fire. 

## Who is notified?
In the event that the cameras fails to verify or verified a minor disaster, the system will sent out a message to the CFRs within the current Smart Environment. The CFRs will then be on-site to evaluate/salvage the situation, before making a call to inform the authorities. If no CFRs are within the area, a message will be sent to the authorities with attached information such as temperature reading, overall area temperature map, growth of temperature over the past few minutes and nearest IP Camera visuals.

In the event that the cameras verified a major disaster, the system will immediately notify the authorities with attached information as mentioned. The system will also make use of connected display devices such as touch-screen directories and digital display boards to provide immediate notification to the public. If evacuation of a building or vicinity is required, the displays will also show the safest way out.

## Why choose Project Warden?
There are many existing or developing IoT solutions out there. The use of temperature sensor for early fire detection in order to notify appropriate personnel. The use of Object Detection to search for anomalies like fire or car-crashes. 

Project Warden does not only use them in order to do early detection and reporting, we use them as a starting point to intergrate and get the CFRs involved in order to provide the quickest and safest response. It was never meant to only provide on-the-spot evaluation, but an entire effort to get more people involved as lifesavers. It is the connectivity between every IoT devices, from the mentioned temperature sensor and IP camera, to the digital display devices and smart directories. They all come together under this collaboration in order to provide a community solution, overcoming slow response times and shortage of manpower.





