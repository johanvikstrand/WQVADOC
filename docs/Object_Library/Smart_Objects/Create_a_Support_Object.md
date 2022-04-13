Create a Support Object
===
When creating a new support object only there really aren't any limits to what you can create. **However**, there are some guidelines that you should follow to ensure that the new object will work alongside with the already existing ones. There are also functions in the [Script Libraries]() that will make the process easier and quicker.

### Connecting to the tag structure through dynTouch
For a support object to connect to the tag in the DataStore it needs the name of the tag it wants to connect to. The object that ensures all the other support objects have access to this is [dynTouch](Support_Objects/dynTouch.md). To get a hold of how this works, please read the onLoad() script on the dynTouch object and look at the already available support objects.

### A couple of useful functions
There are functions available in the script library that today is used by existing support objects here is a list of a couple of them :

- [scSuffix.getDescription()]()
- [scSuffix.getSuffix()]()
- [scSuffix.getAlarm()]()
- [scObjectAnimation.rotateBinary()]()
- [scObjectAnimation.rotate()]()
- [scObjectAnimation.alarmColor()]()

More functions that could be useful can be found in the [Script](../../Scripts/index.md) part of this documentation.