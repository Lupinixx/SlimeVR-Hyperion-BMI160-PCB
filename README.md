# Modified Hyperion case for SlimeVR with PCB for BMI160 IMU

This is a modified version Hyperion case made to fit a custom made PCB that holds standard SlimeVR components and a BMI160 IMU. <br>
Includes a modified lid with holes to allow you to see the LEDs on the PCB inside. <br>
The original design of the case is made by Smeltie and can be found here: https://github.com/Smeltie/Hyperion
The 804040 battery variant of the case is made by Discord user 'Tamate Momochi#9595'

## Components
This Case/PCB is made for the standard DIY SlimeVR components that are recommended in the docs. you can check the docs for links to the specific componets here: https://docs.slimevr.dev/diy/components-guide.html <br>
Only difference is to the docs the switch used, which is smaller and looks nicer (standard for the hyperion case) <br>
The IMU used is the BMI160. <br>

- TP4056
- Wemos D1 Mini
- BMI160
- 40MM Straps
- SS12D00G3 (switch)
- Battery
    - 503759 (Nokia BL-5C also fits this version and is also a cheap alternative. Bit harder to solder as it does not come with battery leads.)
    - 804040
- 1N5817 Diode (2x)
- 180K Ohm resistor


## PCB
Included in this repo are the gerber files that can be uploaded at [JLCPCB](https://jlcpcb.com/) <br>
The source of this PCB can be found at:  https://oshwlab.com/lupinix/slimevr-hyperion-bmi160

## Building
The PCB is made for the above mentions components to be soldered on with the pin headers that are (almost always) included with those components.
The TP4056 however has to be directly soldered to the PCB so there is no gap between PCB and the TP4056. What I like to do is lign up the holes of the TP4056 and the PCB and then throw in a short snipped off resistor lead, and then solder it from both sides. This way you can be sure there is electrical contact between the PCB and TP4056. <br>
The Resistor and diodes can just be soldered like a regular troughhole component. <br>
For the switch I reccomend to first solder everything else, put the PCB on the 3D printed tray, then push the switch in place and solder it.
