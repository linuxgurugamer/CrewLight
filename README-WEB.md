Forum user @li0n is moving on, and asked that I take this over.  Original thread is here: https://forum.kerbalspaceprogram.com/index.php?/topic/154901-*

The goal of this mod is to automatize, as much as possible, the lights of your vessels (and of kerbal's helmet).

Every part that currently hold crew gets its lights turning on
https://web.archive.org/web/20200918144310if_/https://camo.githubusercontent.com/0bf8945f7a6453161e4214f2f24b06eb9f5f13fb/687474703a2f2f692e696d6775722e636f6d2f515571796c69702e676966

 

Lights react to the sunshine

 https://web.archive.org/web/20200908211022if_/https://camo.githubusercontent.com/debf7b2c2b6eadd9fcb8f7cbca5e6a0ec2b64754/687474703a2f2f692e696d6775722e636f6d2f687739774564382e676966

 

And to depth

GIF incoming...

 

When approaching a distant vessel its lights will blink, sending you a welcoming message in Morse code
https://web.archive.org/web/20200918144310if_/https://camo.githubusercontent.com/1f849e71e64e26e5c2fa531568d17cbbc579d0fb/687474703a2f2f692e696d6775722e636f6d2f596c77574b4d722e676966

Kerbal on EVA can toggle lights
https://web.archive.org/web/20200918144310if_/https://camo.githubusercontent.com/839c8d9bf1eda7451d485ac3e8dd30a159c75776/687474703a2f2f692e696d6775722e636f6d2f444f394777624f2e676966

 

Lights can have a motion detector set up

https://i.imgur.com/M0n02ZM.gif

https://i.imgur.com/MmYwl2Y.gif

 

Youtube review by @Kottabos :

https://youtu.be/AE1pvzh2q1Y

 

How does it works ?
Vessel's lights are divided into 3 groups :

Lights of crew-able part :
They will remain off until a kerbal gets on-board
Lights NOT in the light action group : (and kerbal's helmet light)
They'll go on when the sun's fall, off when it rises
Other Lights :
They will work as usual, toggling by the light action group
This mod rely on the light action group to determine which light belongs to which group, in stock KSP you can change action group only in the editor, so no lights on all crafts already launched will react to the sun rising/falling. To change action group in flight you will need the mod Action Groups Extended, by @Diazo.

And an enhanced support of the mod Aviation Lights by @BigNose, maintained by @MOARdV :

By default its navigation and strobe light will get turned on at night using the custom blinking light provided by AviationLights, flash, double flash, interval. This is configurable, per light, in the setting file.
The beacon light will stay off until you push the throttle, acting as a real warning light

And it now support Kerbal Electric (a set of tweak-able and very cool lights) :


How to modify how it works ?
Most of the function can be disabled, or tweaked, directly from the in-game settings screen :
 
https://i.imgur.com/1OoqY7n.png
 
There's also some extra option for the Morse Code message.
 
https://i.imgur.com/z8QINGo.png
 
Due to limitation of the stock settings menu (or limitation to my modding skill :p ) it's a bit tricky to access it : in the settings screen enable the "More Morse Settings", hit accept, twice, and you got it.
 
https://i.imgur.com/N8tFWe0.png

Here you can change the morse message send by distant vessel as you approach them. And the timing for the different symbol (they are sync to the dit duration unless you check manual timing).

 

What is needed ?
ModuleManager is the only dependency, all credits go to @ialdabaoth and @sarbian

 

Know issues :
Lights on kerbal's helmet don't turn on/off as the sun rises/falls. Lights will be turned on if the kerbal disembark in the dark but status of the sunlight won't be checked after that.

The range sphere of the Motion Detector is offset from the light position only for the stock light, for others the sphere center is at the light position.

 

What to do if it doesn't work ?
Report it to Github or on this thread.

Dependencies

ModuleManager
ClickThroughBlocker
Availability

Download: https://spacedock.info/mod/2236/Crew Light Relit
Source: https://github.com/linuxgurugamer/CrewLight
License: MIT
