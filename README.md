# OpenRhynn

This is original openrhynn modifications from ~2013-2014 if i'm correct. Follow original compilation guide from Rhynn project.
Code is quite ugly and contain some bugs but still it works fine as for abandoned game.
Following license, this sources was available since project start, but now it's also available on `GitHub`.
There are new available definitions:

```java
/* BUILD CONFIGURATIONS*/
#define BUILD_J2ME
#undefine BUILD_PC
#undefine BUILD_J2ME_TOUCH
#undefine BUILD_ANDROID
#undefine BUILD_NOKIA
#undefine BUILD_OUYA
```

Also, I recommend to set `DEFAULT_PACKETPERLOOP` to some high value as stated in [OpenrhynnJavaServer](https://github.com/steel-team/OpenrhynnJavaServer) repository.

# Original readme

The sources provided include all current code for the Rhynn client and server (based on versions 1.4+).
Please refer to the wiki on github for instructions on how to build the software and further documentation: https://github.com/marlowe-fw/Rhynn/wiki

You find the official Rhynn homepage on http://www.rhynn.com
