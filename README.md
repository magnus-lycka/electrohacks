# electrohacks
My electronics designs for home automation etc.

## Ideas

 - Control of lights
 - Monitoring of electricity consumers, e.g. fridge and stove
 - Monitoring of electricity and water consumption
 - Burgler alarm
 - Multi room audio? (Packaged solutions might be better for this...)

## Tech stack

### Controllers / processors

 - Retired laptops w/ linux?
  - Pros: Display, Keyboard, Wifi, Ethernet, USB, UPS.
  - Cons: Size. Limited supply or costly. No GPIO ports.
 - Raspberry Pi
  - Pros: Ethernet, USB, HDMI, GPIO, decent RAM & CPU.
  - Cons: Not as small, cheap and low powered as arduino
 - Arduino
  - Pros: Very cheap, Very low power, Size, 
  - Cons: Gets costly with Ethernet shields etc. Limited 

### Communication stack, hardware level

For communication with external entities, fiber and cell phone networks are available.
For in-house communication, wired or wireless have different strengths and weaknesses:

 - Wireless communication can be jammed from the outside, unless you do frequency
   hopping etc, which is way out of scope here. (On the other hand, this kind of
   sabotage is fairly easy to notice, and to react to unless wireless is all you've got.)
 - It's possible to eavesdrop on wireless communication, and I doubt you'd have lots of
   strong encryption in arduinos. (On the other hand, sensor data is probably moderately
   interesting to monitor.)
 - With wired communication, you can provide power and comms in the same cable.
 - Cables can be cut, and they might break.
 - Wireless is quite superior for movable objects.
 - Wireless is a lot cheaper today, unless you have all the cables you need drawn already.
   (2.4GHz Wireless Transceiver Modules for Arduino cost about 1$.)
 - It seems logical to communicate with equipment controlling electrical (230V) equipment
   through the mains cables, but is there anything neater for that than bulky Ethernet
   over powerline adapters from e.g. D-Link?

