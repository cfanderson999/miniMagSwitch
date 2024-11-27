# miniMagSwitch

Microscopic magnetic switch for high power rocketry.

Designed to be assembled entirely by JLCPCB with only the connectors of your choice being soldered afterwards.

## Ordering & Assembly

The assembled switch can be ordered by uploading the files under `fabrication` to JLCPCB. The `miniMagSwitch.zip` contains the PCB files which are uploaded first, then the `miniMagSwitchBom.csv` and `miniMagSwitchCentroid.csv` files are uploaded for assembly. Use the following settings when ordering:

* Vias = Tented
* Remove order number = Remove Mark
* PCBA type = Economic
* Assembly side = Top side
* Tooling holes = Added by Customer

For soldering, there are decent labels on the bottom of the PCB for input/output and polarity. The space on top was extremely limited. For both input and output the GND connection is on the "inside" and the power connection is on the "outside"

## Operation

Operation is very similar to other available magnetic switches, take a strong neodymium magnet and move it across the switch to turn it on, then again across to turn it off. The onboard green LED will shine when the switch is on.

A basic diagram for mounting can be found in `mounting.pdf`. The holes are made for 4-40 screws and there should be enough clearance for the head of standard hex drive button head screws.

I give no guarantees with respect to the operation. There is reverse polarity protection on the input side, though testing it is probably best avoided. It (should) operate fine with 1-4s lipos, maybe higher, not sure.

Testing performed as of 11/27/2024:

* StratologgerCF ground ematch pop test using ~50% charged 1s LiPo
* Elvin beacon worked
* Featherweight tracker worked
