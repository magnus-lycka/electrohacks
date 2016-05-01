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

### Communication stack

For communication with external entities, IP and cell phone networks are available.
For in-house communication, wired communication is preferred for essential communication,
while wifi might be useful for communication with e.g. android devices or laptops as
clients/terminals.

 - Ethernet?
 - Wifi?
 - Serial/USB
 - ...
