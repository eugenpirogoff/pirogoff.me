+++
title = "Ransack - twitter image search "
date = "2014-03-23"
menu = "main"
+++
A friend of mine [@jnikles](https://github.com/jnikles) and i had to make a project for a course at our university a couple of months ago. So we decided to use the Twitter-API and its geotagging as the main entry point for our search for pictures inside tweets. Sadly the API v.1 is deprecated and turned off by now (18 Feb. 2014). Before then it was possible to select a point of interest and radius for a search. The link inside the tweet a image hosting services where parsed (if we supported that image service. Instagram was our main goal) and the images where displayed on the map as an overlay on their coordinates. That worked really well and we used to MongoDB in the backend and delivered every search as an zip archive to a user.

A big thank to [@jnikles](https://github.com/jnikles)

![alt text](/images/ransack_thumb.png")
[https://github.com/eugenpirogoff/ransack](https://github.com/eugenpirogoff/ransack)
