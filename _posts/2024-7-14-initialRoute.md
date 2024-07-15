---
layout: post
title: Parameter 'initialRoute' for more flexible flight routes
---
Up to now flight routes were limited to an airport (EDDK) roundtrip and an orbit tour. With parameter
'initialRoute' an arbitray flight route can be set during scene start. The example below uses the route

```
wp:50.768,7.1672000->takeoff:50.7692,7.1617000->wp:50.7704,7.1557->wp:50.8176,7.0999->wp:50.8519,7.0921->touchdown:50.8625,7.1317000->wp:50.8662999,7.1443999";
```

from EDKB (Hangelar) runway 29 to EDDK (Cologne) runway 06. As always, the flight is started by 's' or the 'default trip' menu item on the VR control panel.
Initially the aircraft 'bluebird' is located at EDKB. The flight to EDDK only takes a few minutes.

![]({{ site.baseurl }}/images/BluebirdTravel-Preview-EDKB.png)



[Launch it](https://yard.de/tcp-flightgear/webgl.html?scene=TravelSceneBluebird&vr-controlpanel-posrot=0,0,0,200,90,0&offsetVR=0.0,%200.0,%200.0&devmode=false&teamSize=1&enableHud=false&enableNearView=false&initialVehicle=bluebird&initialRoute=wp:50.768,7.1672000-%3Etakeoff:50.7692,7.1617000-%3Ewp:50.7704,7.1557-%3Ewp:50.8176,7.0999-%3Ewp:50.8519,7.0921-%3Etouchdown:50.8625,7.1317000-%3Ewp:50.8662999,7.1443999)

This example was taken from [tcp-flightgear](https://thomass171.github.io/tcp-flightgear/tcp-flightgear.html).
