+++
title = "Wifi to QR App"
date = "2018-06-25"
menu = "main"
+++

iOS 11 has some fantastic image recognition features build-in right in to the camera app. One of them is recognizing QR codes and decoding them. It also supports QR code for WiFi sharing. It does not seem to be a "real standard" for sharing WiFi credentials. But the following string encoded to QR seems to work on many platforms for WiFi sharing.

```
WIFI:S:SSID;T:Type;P:Password;
```

Just replace SSID, Password and Type ( encryption can be WEP/WPA ) and encode it to QR.

Even thus iOS is capable of decoding the WiFi credentials right out of the box there was no dedicated app for it that served just this simple purpose of creating shareable QR codes for WiFi. So I made one.

No logging, no tracking, one purpose. Enjoy.


![WiFi to QR](https://github.com/eugenpirogoff/Wifi-to-QR/blob/master/AssetSource/Screenshot.png?raw=true)

[![Download on the App Store](https://linkmaker.itunes.apple.com/assets/shared/badges/en-us/appstore-lrg.svg)](https://itunes.apple.com/us/app/wifi-to-qr/id1389058201?mt=8)

[Sourcecode on GitHub](https://github.com/eugenpirogoff/Wifi-to-QR)