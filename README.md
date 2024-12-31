## IU Informatics, BS.
### [ Capstone Project: "ParkIU" ](https://github.com/plmcdowe/School/tree/1228ab2c2261ae7d5b3b14264a321303cdc0361b/IU-Informatics-Capstone)
> My contributions to a project which created an iOS application to track availability of on campus parking.   
> Two Particle Photon's fitted with sonar sensors programmed to increment/decrement parking facility occupancy.   
> Updates to the count were published by Json web-hooks to a PHP script which updated a SQL datatbase.   
>> [ ParticleA.ino ](https://github.com/plmcdowe/School/blob/1228ab2c2261ae7d5b3b14264a321303cdc0361b/IU-Informatics-Capstone/ParticleA.ino) decrements on vehicle exit and published the event to ParticleB.   
>> [ ParticleB.ino ](https://github.com/plmcdowe/School/blob/1228ab2c2261ae7d5b3b14264a321303cdc0361b/IU-Informatics-Capstone/ParticleB.ino) increments on vehicle entrance and published all events to the Particle cloud.   
>> [ count.php ](https://github.com/plmcdowe/School/blob/1228ab2c2261ae7d5b3b14264a321303cdc0361b/IU-Informatics-Capstone/count.php) recieves the json formatted web-hook from the Particle cloud and updated the SQL database.
>> 
---
## Purdue CS, MS.
### [ SQLite-ML ](https://github.com/plmcdowe/School/tree/1228ab2c2261ae7d5b3b14264a321303cdc0361b/Purdue-CS/SQLite-ML)
> Description
### [ Json PCAP parsing ](https://github.com/plmcdowe/School/tree/1228ab2c2261ae7d5b3b14264a321303cdc0361b/Purdue-CS/JsonPCAP-Parser)
> Description
>
---
## Personal projects
### [ Picture Robot ](https://github.com/plmcdowe/School/tree/1228ab2c2261ae7d5b3b14264a321303cdc0361b/PersonalProjects/PictureRobot)  
> An Arduino robot controlled through Python to copy physical photographs with a DSLR camera.   
>> The Arduino Uno + Adafruit Motor Shield drove:   
>> \> Six, 5v 28BYJ-48 stepper motors   
>> \> One, 12v vacuum pump   
>> \> One HC-SR04 sonar sensor   
>> \> One MMA8452 accelerometer   
>> \> Triggered a Nikon DLSR through a hacked-up Nikon MC-DC2 Remote Release Cord
>>    
> [ Robot_GUI.py ](https://github.com/plmcdowe/School/blob/1228ab2c2261ae7d5b3b14264a321303cdc0361b/PersonalProjects/PictureRobot/Robot_GUI.py) provides control through a Tkinter GUI.   
> [ TkinterRobot.ino ](https://github.com/plmcdowe/School/blob/1228ab2c2261ae7d5b3b14264a321303cdc0361b/PersonalProjects/PictureRobot/TkinterRobot.ino) is the Arduino program to drive the hardware.   
