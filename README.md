# V2v-V2I-auto-switch-

This code is to auto switch between services in self driving cars. The example is for a delivery company and a car is delivering packages to customers. 
The car will be using both v2v and v2i applications . 
This code shows how if the car received an error message from V2V-server it will switch connection to V2I server 

there are 3 files: 
V2V server file (it will wait for the car to connect to it)
Vehicle file (the car will connect to the V2v server and then will wait if it received an error message it will connect to V2I server) 
V2I server file (will be wait for the car to connect to it if there is an error from V2V server )

