+++
title = "Pluto - game remote controller"
date = "2013-09-30"
menu = "main"
+++
As a part for my bachelor thesis i have written a remote controller for the game HexGL that runs platform agnostic inside a web browser. It just needs WebSockets or WebRTC for communication between the devices and a fast connection (i recommend to use chrome). The controller is designed to run on a phone or a tablet. The game itself is a WebGL implementation of WipeOut that runs completely in your browser on a desktop or mobile device and has been written by Thibaut Despoulain.

![alt text](/images/pluto_thumb_1.png")

In order that the running game sessions can run next to each other and the conntroller finds the corresponding game we need to make sure the game host and the controller use the same token or key to connect. You can type whatever session key you want in that field otherwise an abstraction of epoch time will be used ( i recommend a custom key ). After hitting the “Game : HexGL” button on the game host device we can connect with our phone or tablet as a controller to the running session and play the game. Dont forget to enter the same key on the mobile device.

![alt text](/images/pluto_thumb_2.png")
![alt text](/images/pluto_thumb_3.png")

[https://github.com/eugenpirogoff/pluto](https://github.com/eugenpirogoff/pluto)
