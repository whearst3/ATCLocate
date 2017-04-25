# ATCLocate

Source files for pythonista program to convert lat/lon to ATC reference e.g.  "xx nm NW of SGD"

Program will require Pyhtonista on an IOS device for now. 

Maybe next port to native IOS application using Swift and Xcode

This small app is to process location info for aviation, e.g. in a moving airplane.  It should capture Lat/Lon and convert this info
to "Magentic DIR" and "Distance in NM" from well established VOR locations in USA. Initial testing with California only data.

Internet access is not reliable in flight. And air traffic control (ATC) does not prefer LAT/LON,  but approx location in English. 
This voice communication is necessary only intermittently. So this app has one button, push it, and app reads geo position from iOS,
and returns a simple phrase e. g. :

< 10 nm NW of OAK VOR >

So I need a fresh location, not very often. However, even in a few minutes the airplane has moved miles.

