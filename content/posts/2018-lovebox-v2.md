+++
title = "Lovebox"
date = "2018-06-29"
menu = "main"
+++

The Lovebox project was created as a tool for our wedding. We wanted some kind of possibility to capture and keep some moments in a photo while giving it also back to our guests at the wedding. We decided to build a DIY photo box that made photos and had the capability to print them too. That is how the idea was born.

The first version of Lovebox was made with Processing on the Java VM/Linux OS running on a Raspberry Pi with camera and printer attached over USB 2.0. The GPIO of the Raspberry Pi was used as event triggers for camera capturing and printing of the photo.

The low processing power and the low I/O throughput made it very slow to operate.

 - GPIO needed to be checked
 - photos needed to be moved on filesystem level
 - photos needed to be showed on screen
 - bash scrips for printing if desired

Looking back it seems like a bad idea to use a Raspberry Pi and NOT programm it with more low level tools for improved performance. My skills in processing made it also relatively memory hungry.

![Raspberry and GIOP breadboard](https://www.pirogoff.me/images/lovebox_v1_1.jpg)

![Raspberry and GIOP breadboard](https://www.pirogoff.me/images/lovebox_v1_2.jpg)

![Raspberry and GIOP breadboard](https://www.pirogoff.me/images/lovebox_v1_3.jpg)

![Raspberry and GIOP breadboard](https://www.pirogoff.me/images/lovebox_v1_4.jpg)

Since there is an other event coming up where the Lovebox is needed again, it's time to rebuild and make a improved version 2.

Let's think about it.
