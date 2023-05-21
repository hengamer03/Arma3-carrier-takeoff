# Arma3-carrier-takeoff
This is a simple guide with code examples on how to get jets to take off from the Arma3 USS Liberty aircraft carrier using the catapult system

## Guide

to test this out simply go into the Arma3 Eden editor, place down the USS Liberty carrier somewhere on the map, then place down two fighters. These fighters needs to be aligned to the catapult launcher because they don't know how to taxi. 

Give these fighters a variable name like Fighter_1 and Fighter_2, you can name it whatever you want, I am going to refer to what i used for my variable names (Fighter_1 and Fighter_2)

Lastly put a waypont for search and destroy or whatever waypoint you want to use for your mission so that the fighters have something to do after takeoff.

save this mission and call it whatever you want. I called this mission simply assult. 
exit the Eden editor. go to you file explorerer. then go to Documents\Arma 3\missions\(missioname) your mission directory will be called .Stratis or .Altis based on the Map you chose.

in this directory create a text file called jetlaunch.sqf, Copy the file contents of the sqf file in this directory into your own sqf file, Modify it baed on your own variables etc. save this file and ReOpen the Eden editor and Load your Scenario. 

Place down a trigger with some area effect on the carrier. This trigger should be a type None, Activated by BLUFOR when Present, then in the on activation field further down you need to refer to the sqf file you just created. COpy and Paste the content from the OnActivation.txt file in this directory into this field. Lastly pu a countdown of 1 second in each timer field on the trigger. it does not work without this.

Now everythng should be set. Place down a unit on the carrier so that you can watch the planes take off without player interference, and watch the takeoff sequence. 

## Known Issues
Sometimes one or both jets explode on takeoff. I have no Idea why this happens but it shouldnt do it all the time. 