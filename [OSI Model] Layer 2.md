# OSI Model: Layer 2

The data-link layer (Layer 2) defines how data is formatated for the transmission over the physical medium

* Provides node-to-node connectivity 
* The layer of MAC addresses
* Encapsulates the data being sent by adding a layer 2 header and a layer 2 trailer turning it into a **frame**

<br>

# Frames

Frames are 

* Contains both source and destination MAC addresses
* Responsible for finding the next destination in the network
* The frame is then decapsulated by the destined recipient where the rest of the data is then sent to the upper network layer 

