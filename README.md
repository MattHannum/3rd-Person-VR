# 3rd-Person-VR
This repository is a compilation of research on 3rd person VR. It describes methods attempted to achieve it and analysis on them. Currently there is no system available to easily achieve 3rd person VR and minimal resources on it.

3rd person VR is when a user wearing a virtual reality headset sees themself in the VR headset. It is achieved by having a camera feed from an external camera sent to the VR headset.

#Purpose

When 3rd person VR is achieved it will allow for users to develop AR (Augmented Reality) games in the 3rd person. This will make for a unique out of body experience which combines video games with physical activity. The user of the headset becomes the player in the third person game.

##Oculus Quest 2

#Overview

The Oculus Quest 2 was utilized to attempt 3rd person VR. It is a wireless headset and can run on its own built-in hardware, which means it doesn't require a PC to operate. It has motion tracking capabilities, allowing users to move around in the virtual environment and interact with objects in a natural way. 

#Cast

The companion app for the Oculus Quest 2 has an option to cast from the app. However, this only allows the phone app to see what the headset sees from the phone. It cannot be cast from the phone to the headset.

#External Camera

Currently it is not possible to connect an external camera to the headset. 

#Quest Link

Oculus Quest can be connected to a computer using a USB C cable. The computer can then use the Oculus app to utilize the computer hardware to run software. In order to run the headset from the computer it requires certain specs to be met.

Processor
Intel i5-4590 / AMD Ryzen 5 1500X or greater
Graphics Card
See GPU tables below
Memory
8 GB+ RAM
Operating System
Windows 10, Windows 11


When working on the project, my computer did not meet the requirements to use it. This method is not accessible to most users because of the price point of these computers.

##ALVR (https://github.com/alvr-org/ALVR)

An alternative way of connecting a computer to the oculus is using 3rd party software like ALVR. Unlike Quest Link, ALVR is achieved over a wireless connection to connect a computer to the headset. This means that the headset is no longer needed to be connected to the computer but it adds a potential for a latency problem. ALVR allows for the SteamVR software to be used on an Oculus Quest.

Using this method also allows for less powerful computers to connect to the headset. My computer did not meet the requirements to use Quest Link but could use the ALVR method. The computer ran the games and streamed them to the headset. It still allowed for full capabilities of VR with the motion controls and tracking. 

#SteamVR

SteamVR is the companion program for running Steam games on VR headsets. Using ALVR I was able to run Unity Games from my computer and stream the gameplay to the headset using Steam.  This allowed me to easily run custom Unity games on the headset. After building a game in Unity, I could add it to my steam library to run from the headset.

##Unity

Multiple basic Unity games were developed to test the functionality of the headset.

#Ball Bounce

A basic Unity Game of a ball bouncing up and down in VR was used to see if this method was able to run custom VR games. After building the game and uploading it to my steam library, it could then be run on the headset and experienced in VR.

#Regular Camera Functionality

A Unity game was developed where it takes camera input from the computer camera and displays it on the screen using Unity. This program was developed without VR to see if it could run on a computer and then if it could run in theater mode on the headset. Theater mode is when the user is in a virtual theater on the headset and views the game on a screen in the virtual world. The program runs on a computer and shows the feed from the computer camera. When running on the headset when streamed from the computer the camera feed will not transmit and the user is left with a blank screen in the theater mode. 

#VR Camera Functionality

The Unity game was rebuilt using a VR camera and built for VR. When run, the user was put in an empty Unity world and the camera feed only showed on the computer screen. 

##Web Browser

Despite the technical methods attempted to achieve it, using the web browser in the Oculus world would prove to work the best.

#Discord

Discord allows for users to turn their cameras on making the voice calls video calls. Despite this working on computers, when viewing someone's camera feed from the browser on a headset, it shows up blank.

#Zoom

Joining a zoom call from the browser in the VR headset allows for them to see the other members of the call’s camera feeds. By hosting a zoom meeting from a phone and joining on a headset, it allows for users to view themselves from the phone camera and can now achieve 3rd person.

To enhance this experience, settings can be changed in the VR headset to allow the user free movement. With developer mode enabled, Guardian and motion tracking can be disabled on the headset to allow the feed to follow the user wherever they go.


##Conclusion

Currently 3rd person VR is achievable but not developer friendly. Since headsets limit users' capabilities to add external devices it severely inhibits what can be developed using them. This makes it hard for any innovation to be achieved using commercially available headsets. 

