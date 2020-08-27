*********************************************************CAR HMI******************************************************************

This car HMI is designed to facilitate the user experience by having an user-friendly interface and a straightforward way for 
the user to communicate with the interface.

Variables to be modified from the Activity Monitor:

*warningsActive(boolean List) --> modifications made to "BoardState"
*fuelLevel (Integer) --> modifications made to "BoardState"

It has all the key features that an Infotaiment system has: 

-Radio
-Phonebook + the ability of making phonecalls 
-Navigation system
-Vehicle status - providing the date of the last revisions made by official services
-The ability to change the Driving Mode, thus providing optimized consumption
-Settings (the ability to change HMI language - English/German and the skin - Light Theme/Dark Theme, cofigure Bluetooth)
-Board View (showing Fuel level, whether music is playing or not, whether there are phone calls in progress, 
speed, revs, speedlimit alerts, basic board alerts)

Key EB Guide technologies used:

-Dynamic State Machines
-Language Support
-Skin
-Instantiator
-Animation
-Image
-Label
-Shapes (Rectangle/Sphere)
-.psd files
-Templates
-Conditional scripts
-Touch pressed/touch released
-MoveIn, moveOut
-Events w/ and w/o parameters
-Scrollable Lists