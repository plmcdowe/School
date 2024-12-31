## IU Informatics, BS.
### [ Capstone Project: "ParkIU" ](https://github.com/plmcdowe/School/tree/1228ab2c2261ae7d5b3b14264a321303cdc0361b/IU-Informatics-Capstone)
> My contributions to a project which created an iOS application to track availability of on campus parking.   
> Two Particle Photon's fitted with sonar sensors programmed to increment/decrement parking facility occupancy.   
> Changes to occupancy are published by json web-hooks to a PHP script which updates a SQL datatbase.   
>> [ ParticleA.ino ](https://github.com/plmcdowe/School/blob/1228ab2c2261ae7d5b3b14264a321303cdc0361b/IU-Informatics-Capstone/ParticleA.ino) decrements on vehicle exit and publishes the event to ParticleB.   
>> [ ParticleB.ino ](https://github.com/plmcdowe/School/blob/1228ab2c2261ae7d5b3b14264a321303cdc0361b/IU-Informatics-Capstone/ParticleB.ino) increments on vehicle entrance and publishes all events to the Particle cloud.   
>> [ count.php ](https://github.com/plmcdowe/School/blob/1228ab2c2261ae7d5b3b14264a321303cdc0361b/IU-Informatics-Capstone/count.php) recieves the json formatted web-hook from the Particle cloud and updates the SQL database.
>> 
---
## Purdue CS, MS.
### [ SQLite-ML ](https://github.com/plmcdowe/School/tree/1228ab2c2261ae7d5b3b14264a321303cdc0361b/Purdue-CS/SQLite-ML)
> Extends SQLite syntax to allow ML outlier-detection & sentiment analysis of data directly from SQLite CLI.
### [ Json PCAP parsing ](https://github.com/plmcdowe/School/tree/1228ab2c2261ae7d5b3b14264a321303cdc0361b/Purdue-CS/JsonPCAP-Parser)
> Split between two files due to the nature of the orignial assignment.   
> The structure of either/both program could be extended to examine PCAPs for additional security events.   
> [ JsonPCAP1.py ](https://github.com/plmcdowe/School/blob/68bad203da6eec271042d636ce8111531ddbe056/Purdue-CS/JsonPCAP-Parser/JsonPCAP1.py) parses for:   
>> \> *Successful* HTTP sessions   
>> \> Directory Traversal evidence   
>> \> Failed login attempts   
>> \> Clear text credentials   
>> \> Apache webserver versions   
>> \> DNS source port randomization   
>> \> TCP ISN deviation   
>> \> Traceroute evidence   
>> \> XSS evidence   
> [ JsonPCAP.py ](https://github.com/plmcdowe/School/blob/68bad203da6eec271042d636ce8111531ddbe056/Purdue-CS/JsonPCAP-Parser/JsonPCAP1.py) parses for:   
>> \> Client MAC & IP addresses   
>> \> FTP session details   
>> \> Facebook URIs & cookies   
>
---
## Personal projects
### [ Picture Robot ](https://github.com/plmcdowe/School/tree/1228ab2c2261ae7d5b3b14264a321303cdc0361b/PersonalProjects/PictureRobot)  
> An Arduino robot controlled through Python to copy physical photographs with a DSLR camera.   
>> The Arduino Uno + Adafruit Motor Shield drives:   
>> \> Six, 5v 28BYJ-48 stepper motors   
>> \> One, 12v vacuum pump   
>> \> One, HC-SR04 sonar sensor   
>> \> One, MMA8452 accelerometer   
>> \> Triggers a Nikon DLSR through a hacked-up MC-DC2 Remote Release Cord   
>>    
> [ Robot_GUI.py ](https://github.com/plmcdowe/School/blob/1228ab2c2261ae7d5b3b14264a321303cdc0361b/PersonalProjects/PictureRobot/Robot_GUI.py) provides control over serial through a Tkinter GUI.   
> [ TkinterRobot.ino ](https://github.com/plmcdowe/School/blob/1228ab2c2261ae7d5b3b14264a321303cdc0361b/PersonalProjects/PictureRobot/TkinterRobot.ino) is the Arduino program to drive the hardware.   
