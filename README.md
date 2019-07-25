Updated home-assistant component for hass version 0.96 and the "climate-1.0" changes.

It does not read the device's state on initial connection, since for some reason the update method causes my device to turn on and be set to fan only mode. (This is a bug to be fixed in [andersonshatch/midea-ac-lib](https://github.com/andersonshatch/midea-ac-lib)... if only I knew how.)

Instead, it restores state from home-assistant's previous state.
This should work okay as long as you only alter the state of your device using home-assisant.

Original Readme:
# midea-ac-py 

This is a library to allow communicating to a Midea AC via the Midea Cloud.

This is a very early release, and comes without any guarantees. This is still an early work in progress and simply serves as a proof of concept.

This library would not have been possible if it wasn't for the amazing work done by @yitsushi and his Ruby based command line tool. 
You can find his work here: https://github.com/yitsushi/midea-air-condition
The reasons for me converting this to Python is that this library also serves as a platform component for Home Assistant.

## Wiki
Please visit the Wiki for device support and instruction on how to use this component: https://github.com/NeoAcheron/midea-ac-py/wiki 
