# IU Informatics, BS.
## [ \* Capstone Project: "ParkIU" ](https://github.com/plmcdowe/School/tree/1228ab2c2261ae7d5b3b14264a321303cdc0361b/IU-Informatics-Capstone)
My contributions to a project which created an iOS application to track availability of on campus parking.
> 
> Two Particle Photon's fitted with sonar sensors programmed to increment/decrement parking facility occupancy:
>> <img src="https://github.com/user-attachments/assets/638bd649-03e6-41b0-be4a-783cfbbe8448" alt="Alt Text" width="400" height="263">
> Changes to occupancy are published by json web-hooks to a PHP script which updates a SQL datatbase.   
>> [ ParticleA.ino ](https://github.com/plmcdowe/School/blob/1228ab2c2261ae7d5b3b14264a321303cdc0361b/IU-Informatics-Capstone/ParticleA.ino) decrements on vehicle exit and publishes the event to ParticleB.   
>> [ ParticleB.ino ](https://github.com/plmcdowe/School/blob/1228ab2c2261ae7d5b3b14264a321303cdc0361b/IU-Informatics-Capstone/ParticleB.ino) increments on vehicle entrance and publishes all events to the Particle cloud.   
>> [ count.php ](https://github.com/plmcdowe/School/blob/1228ab2c2261ae7d5b3b14264a321303cdc0361b/IU-Informatics-Capstone/count.php) recieves the json formatted web-hook from the Particle cloud and updates the SQL database.
>>   
---
# Purdue CS, MS.
## [ \* SQLite-ML ](https://github.com/plmcdowe/School/tree/1228ab2c2261ae7d5b3b14264a321303cdc0361b/Purdue-CS/SQLite-ML)
Extends SQLite syntax to allow ML outlier-detection & sentiment analysis of data directly from SQLite CLI.
> [ 1-README-MAIN.md ](https://github.com/plmcdowe/School/blob/1228ab2c2261ae7d5b3b14264a321303cdc0361b/Purdue-CS/SQLite-ML/1-README-MAIN.md) provides detailed instructions to setup & run.
>>  <img src="https://github.com/user-attachments/assets/f2c284a1-eebf-4575-995e-c66e101b40f2" alt="Alt Text" width="517" height="200">  
> [ 2-README-IOT.md ](https://github.com/plmcdowe/School/blob/1228ab2c2261ae7d5b3b14264a321303cdc0361b/Purdue-CS/SQLite-ML/2-README-IOT.md) documents extending this project to run between Arduino Giga & Raspberry Pi5.  
>> <img src="https://github.com/user-attachments/assets/c8bcb7e7-0ebd-4a86-984d-a77521946851" alt="Alt Text" width="400" height="400">  
>
## [ \* json PCAP parsing ](https://github.com/plmcdowe/School/tree/1228ab2c2261ae7d5b3b14264a321303cdc0361b/Purdue-CS/JsonPCAP-Parser)
> Split between two files due to the nature of the orignial assignment.   
> The structure of either/both program could be extended to examine PCAPs for additional security events.
> 
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
>> 
> [ JsonPCAP2.py ](https://github.com/plmcdowe/School/blob/66482f5573c2977825d1fe7e7c897acf34860bb2/Purdue-CS/JsonPCAP-Parser/JsonPCAP2.py) parses for:   
>> \> Client MAC & IP addresses   
>> \> FTP session details   
>> \> Facebook URIs & cookies   
>
---
# Personal projects
## [ \* Picture Robot ](https://github.com/plmcdowe/School/tree/1228ab2c2261ae7d5b3b14264a321303cdc0361b/PersonalProjects/PictureRobot)  
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

Demo of the python GUI interacting over serial with the Arduino to turn on a blue LED:   

https://github.com/user-attachments/assets/d8e87a40-d99c-4695-b16d-e683b1de0d4c

