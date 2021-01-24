# V2v-V2I-auto-switch-

This code is to auto switch between services in self driving cars.
The example is for a delivery company and a car is delivering packages to customers. 
The car will be using both v2v and v2i v2v to communicate with the surrounding cars and v2i 
to update the application server or to receive updates from the server. 
The car will mainly be using v2v. This code shows how if there was an accident that caused 
a traffic jam the car will then send updates to the server so that it can send a different road. 
It will always use v2i even if it's using v2v by opening a communication socket which will alway be opened so that the car and server can update each other. 
The link below is for the code of that function :
