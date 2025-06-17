<img src="https://github.com/xfmn/tip41c_5V1A/blob/main/main-dc%20(2).png">

0 .. 30V/0 .. 10A LABORATORY POWER SUPPLY
A laboratory power supply offers an indispensable set for both the professional
and the amateur.
This power supply is short-circuit protected and infinitely variable from 0 to 30V
and from 0 to 1 OA.
Both a digital voltage meter and a digital ampere-meter are supplied as
indicators.
Thanks to the in-built fan the power supply is able to cater for long-term fu ll load.
Is supplied complete with housing, buttons and transformers.
TECHNICAL DATA
- Output voltage variable from Ov to 30V.
- Fine tuning over 1 V
- Output current limiting device infinitely variable from 0 to 1 OA.
-LED (l ight emitting diode)-indication of current limitation
- Output current: 8A. continuous/1 OA. peak
- Short-cicuit protected
-Ripple maximum: 0.5mV RMS
-Digital voltage meter: 3-digit, 0.1V accurate
-Digital amperemeter: 3-digit, 0.01A accurate
-Consumption: 300W maximum
- Dimensions WxHxD: 330x90x215
We reserve the right to make alterations
INSTALLATION INSTRUCTIONS
VERY IMPORTANT
-MOUNT ALL COMPONENTS AGAINST THE P.C. BOARD
-USE A SMALL SOLDERING IRON OF 40W MAXIMUM
-USE THIN (1 mm) SOLDERING TIN
-CARELESS ASSEMBLY WILL UNDOUBTEDLY CAUSE PROBLEMS
The power supply consists of four pcb's:
A base card with potentiometers that feature behind the front panel.
Two transistor boards on to which the power transistors, situated on the
heatsinks, are connected.
Finally, a board with digital voltage and ampere-meter.
A) Construction of the transistor PCB P7200T
The two PCB's are assembled differently:

Board1:
Mount the pins for connecting T 4 to T6
Mount six Faston clamps forE B C (left and right)
Mount the 5W resistances R41 to R43 of 0.22 Ohm vertically and with the body
as on the PCB annotation. (see figure 3.2)
Board2:
Mount the pins for connecting T7 and T8 (T6 remains open)
Mount three Faston clamps forE B C next to R41 /R44.
Mount the 5W resistances R44 and R45 for 0.22 Ohm vertically and with the
body as on the PCB annotation. (R43 remains open)
IMPORTANT: PUT AN EXTRA THICK TIN COATING ON THE ALREADY
PLATED CIRCUITS
B) Construction of base PCB P7200B
ATTENTION: The additionally supplied piece of resistance wire of about 50 em
is not to be used to construct jumpwires.
Mount the jumpwires marked with J
Mount the resistances:
- R1 , 6K8 (blue, grey, red)
- R2, 8K2 (grey, red, red)
- R3 to R8, 4K7 (yellow, purple, red)
- R9 to R12, 220 Ohm (red, red, brown)
- R13 and R14, 2K2 (red, red, red)
- R 15 and R 16, 2K7 (red, purple, red)
- R17 and R18, 820 Ohm (grey, red, brown)
- R19 to R22, 22K (red, red, amber)
- R23 and R24, 1 K2 (brown, red, red)
- R25, 1 OOK (brown, black, yellow)
- R26, 15K (brown, green, amber)
- R27, 100 Ohm (brown, black, brown)
- R28, 1 K (brown, black, red)
- R29, 330 Ohm (orange, orange, brown)
- R30, 220K (red, red, yellow)
- R31 , 18 Ohm (brown, grey, black)
- R32, 270K (red, purple, yellow)
- R33, 12K (brown, red, amber)
- R34, 27K (red, purple, amber)
- R35, 39 Ohm (amber, white, black)
Mount the diodes: (pay attention to polarity!)


- 01 to 03, diodes from 1 N4000 series
- ZD1 , 1 OV Zener-diode
- ZD2, 18V/1.3W Zener-diode
Mount the IC socket for IC1 to IC3
Mount the pins for VS,COM and CS
Mount the coil L 1 of 4700uH; this coil looks like a resistance but, as a rule,
possesses a somewhat thicker brown body with the colours yellow, purple, red
and gold.
Mount the capacitors:
- C1, 150pF ceramic (sometimes with annotation 151)
- C2, 33nF MKM
- C3, 68nF MKM
- C4, 100nF ceramic (sometimes with annotation 104)
- C5, 1uF MKM
- C6 and C7, 10uF elco. Pay attention to polarity!
- C8 and C9, 1 OOuF elco. Pay attention to polarity!
- C1 0, 470uF elco. Pay attention to polarity!
Mount the trimming potentiometers:
RV1 , 100 Ohm
RV2, 47K (or 50K)
Mount the screw connectors for J 1 to J5; these are telescoped two-pole
connectors.
Mount a three-pole connector for J6.
Mount the transistors:
- T1, type BC557B or equivalent.
- T2, type BC547B or equivalent.
- T3, type 80646: to be installed together with the heat sink on to the board (but
first fold its connection at right angles). Only when the transistor has been fixed
with 1 Omm bolt and nut, can it be soldered.
Depending on the supplied type, mount relay RY1a or RYe (16A/12V)
Mount for R36, 180 Ohm 1/2W (brown, grey, brown) if RY1a is used, or mount
R36, 100 Ohm 1W (brown, black, brown) if RY1c is used.
Installing the potentiometers: (see figure 1.0)
Install the potentiometers THROUGH the board, in such a way that the axes are
situated on the solder side. Only when the potentiometers have been fixed can
switch-throughs A, B and C with the board be made, by means of small pieces of
blank wire.
- RV3, 4K7 or 5K logarithmical.


- RV4, 1 OK linear.
- RV5, 1 K linear.
Assembling the current-sensor resistances:
These resistances are made by means of the additionally supplied piece of
resistance wire. Proceed as fo llows:
- Snip off four pieces of 1 Ocm each from the supplied resistance wire.
- Fold the four pieces as shown in figure 1.1
IMPORTANT: The soldering ends must first be grinded with abrasive paper and
must then be plated with tin; otherwise it might lead to inadequate contact and
consequently to an inadequate functioning of the power supply.
- Mount these resistance wires on the spots R37 up to and including R40. (see
figure 1.2)
Mount the lcs in their socket:
I C 1, type 7 41 with its notch facing C7
IC2, type 723 with its notch facing R7
IC3, type VK7200 with its notch facing C3.
- Mount the current limitation indication LED LD1 ON THE SOLDER SIDE, in
such a way that the tip of the LED rises 3cm above the PCB surface (= total
length of the LED). Pay attention to polarity; the shortest connection of the LED
coincides with the opening next to the flattened circular annotation.
IMPORTANT: PUT AN EXTRA THICK TIN COATING ON THE ALREADY
PLATED CIRCUITS
C) construction of the digital readout PCB P7201
Mount the jumpwires marked Jon the board.
Mount the resistances:
- R1 to R4, 100K (brown, black, yellow)
- R5 and R6, 22K (red, red, amber)
- R7 and R8, 47K (yellow, purple, amber)
- R9 and R10, 470 Ohm (yellow, purple, brown)
Mount the diodes. Pay attention to polarity:
D1 to 04, diodes from the 1 N4000 series.
Mount he lc socket for IC1 and IC2 together with those for the displays.
Mount the trimming potentiometers RV1 and RV2 of 1 K
Mount the capacitors:
C1 and C2, 1 OOpF ceramic (sometimes with annotation 101)
C3 to CB, 1 OOnF (sometimes with annotation 104)
C9 and C10, 100nF MKM (sometimes with annotation u1)


C11 and C12, 220nF MKM (sometimes with annotation u22)
C13 and C14, 470nF MKM (sometimes with annotation u47)
Assembling the voltage regulator:
Fold the connections of the voltage regulators at right angles and Mount them on
to the board. Fiw them by means of M3 bolt and nut; then solder the
connections.
VR1 type 7805; VR2 type 7905
Mount the elco's C15 and C16 of 1000uF on the solder side of the board and
lay them flat on to the board surface; then the connect-ions can be soldered and
snipped off on the component side. Pay attention to polarity!
Mount the ICs type 7107 in their socket with the peak facing C15 and C16.
Mount the displays DY1 and DY6 (see board annotation)
Mount the six boardpins for Va and Cs on the solder side.
CHECK ALL COMPONENTS THOROUGHLY YET AGAIN!
CONSTRUCTION
- Supply the ends of the heatsinks with thread by means of the additionally
supplied 25mm long zinc-plated bolt (see figure 2.0). This screw-thread is used
for fixing the front and back panel.
- Mount the bottom plate on the heatsinks by means of the rubber feet and
12mm bolts and nuts (first mount the four feet on the bottom plate, then slide the
nuts in the slots and fix) (figure 8.0)
- Mount the back cover of the heatsinks (with four black M4 nuts which are not
zinc-plated), in such a way that the large openings are situated in the top righthand
corner (when viewed from behind). (figure 8.0)
-On the back cover, mount by means of 35mm long bolts, lock washer and nut,
the fan with blowing direction outward (the blow direction is indicated on the fan
by means of an arrow). Supply a nut between the back cover and the fan to the
2 upper openings (see figure 2.1)
- Mount the fuse holder and the power plug by means of zinc plated M3 bolts
with lock washer and nut.
Assembling the transistors type TIP3055:
REMARK: when assembling the transistors the easiest way to tackle the
problem is to put the housing upright.
-Slide the transistor board with connections for three transistors into the slot of
the right heatsink (see figure 3.2) in such a way that the connections for the
transistors are situated on the appropriate positions (see figure 3.0).
-Slide the other transistor board into the left heatsink (see figure 3.1)
- Slide hexagonal socket bolts in the fastening slot of the heatsinks and position
them on the spot where the transistors are to come. (see figure 3.4)


- Fold the connections of the transistors in an angle of about 45 degrees.
- Apply a thermal conduction paste on one side of the mica insulators and place
them over the bolts in such a way that they stick on to the heatsink.
- Apply a little thermal conduction paste on the transistors and place them in turn
over the fastening bolts.
- Fix the transistors first via an insulating ring, a washer and a lock washer and
finally a M3 nut. (see figure 3.3)
-Solder the transistor connections on to the boardpins for T4, T5 and T6 of one
board and T7 and T8 of the other board.
Assembling the rectifying bridge: (for positioning see figure 3.1)
- Slide a hexagonal bolt in the fastening slot of the left heatsink. (see figure 3.4)
-Apply a little silicon or thermal conduction paste (obtainable at specialist shops)
on to the back plate of the rectifying bridge and fix the latter on to the heatsink by
means of lock washer and M3 nut (see figure 3.5). Make sure that the clamp
marked + is situated on top. (see figure 3.1)
Assembling small power supply transformer for digital readout:
- Mount the 2X6V transformer on the bottom plate by means of 1 Omm M3 bolts,
lock washer and nut. (see figure 4.0)
Assembling and connecting the smoothing elcos C11 and C12 of 4700uF:
(figure 4.0)
- Mount the elcos in their bows with the connections facing upwards and fix
these on to the bottom plate by means of a 1 Omm M3 bolt, lock washer and nut
(see figure 4.0)
- Connect with a piece of additionally supplied red wire, by means of a cable
shoe (that which is soldered the best), the + clamp of the rectifier with clamp
1 (+)of a capacitor and interconnect this with clamp 1 ( +) of the other capacitor.
(figure 4.1)
-Connect in a similar fashion clamp 5(-) of the elcos with the negative clamp of
the rectifier by means of a piece of blue wire (i.e. the clamp diagonally over the +
clamp).
Assembling the front panel:
- Mount on the front plate the four zinc-plated M3 bolts of 45mm together with
the 1 Omm threaded bush. Fix these firmly, because you will not be able to reach
them after the front foil has been adhered.
Adhering the foil on to the front panel:
- Check beforehand whether the front panel is free of dust or burrs (it is safe to
degrease with alcohol first).
- Position the foil on the front panel in such a way that the openings coincide.
- For the time being adhere the foil on one side by means of adhesive tape.
- Remove on the other side the protective film and adhere this side on to the

front panel.
- Now the adhesive tape and the protective film on the other side and adhere this
side also on to the front panel.
- Mount the +(red) and -(black) connection terminals.
-Mount the power switch.
- Mount the base board and the digital readout on the front panel as shown in
figure 5.0.
Assemble the buttons on the potentiometers:
(for small buttons the potentiometer axes may have to be shortened)
-Small button with red cap for current limitation (CURRENT
LIMIT)
-Large button with blue cap for coarse (COARSE) voltage regulation.
-Small button with blue cap for fine (FINE) voltage regulation.
WIRING
-Connect the points VS, COM and CS (see board annotation in manual) of the
readout by means of wire (thin additionally supplied pieces of wire of 0.5mm) of
about 1 Ocm with the corresponding point on the power supply board. (figure 6.0)
- Connect the two free clamps of the rectifier with the clamps AC of the base
board (use two pieces of white wire). (figure 4.2)
-Connect the+ clamp of one of the smoothing elcos (clamp 1) with the+ clamp
(next to the AC clamps) of the base board (use a piece of red wire). (figure 4.2)
- Connect the- clamp of one of the smoothing elcos (clamp 5) with the- clamp
(next to the AC clamps) of the base board (use a piece of blue wire). (figure 4.2)
- Connect the red output terminal with the OUT + screw clamp (red wire) and the
black output terminal with the OUT- screw clamp (blue wire) (figure 6.2)
- The connection with the transistor boards should remain open for the time
being.
- Connect with the thin wires the points VA, Gm and GB of the readout with the
2X6V transformer, Gm reaches the middle contact (0) of the transformer, VA and
VB reach the two 6V clamps (figure 6.1 ).
Assembling the toroidal transformer (2X15V 300VA) see figure 4.0:
-Put a rubber mat on the bottom plate and position the transformer on it. Put a
rubber mat on the transformer and then the metal fixing plate; then fix all parts
with bolt and nut.
- Connect the power plug, the fuse holder and the power switch (use cable
shoes for connecting the power switch!) as shown in figure 6.2.Connect the
small 2X6V transformer (between 0 and 125V or between 0 and 220V
depending on the mains voltage) see figure 6.2.


Also connect the mains voltage wires of the ring core transformer (for the colours
please check the box of the transformer) see figure 6.2.
The connections for the fan should remain open for the time being.
Mount the front panel on the cooling profiles for the time being by means of the
black zinc-plated M4 bolts.
Make the following connections with the toroidal transformer: (figure 6.2):
- Connect the 15V clamp (marked GREY) with the 15V connection or grey wire
of the transformer.
- Connect the OV clamp (marked BLUE) with the OV connection or blue wire of
the transformer.
- Connect the OV clamp (marked YELLOW) with the OV connection or yellow
wire of the transformer.
- Connect the 15V clamp (marked RED) with the 15V connection or red wire of
the transformer.
TESTING
Place a 220V/25W or 40W lamp over the fuse holder of the power supply. The
fuse must NOT be mounted yet.
- Turn the trimming potentiometers RV1 and RV2 (on the base board) in the
intermediate position.
- Turn the trimming potentiometers of the digital readouts (METER ADJUST)
completely to the right.
-Turn the current (current potentiometer) on maximum.
- Connect the mains with the mains plug and switch the power supply on. If
everything functions properly, the lamp should light for only a second or not at
all ; if the lamp keeps lighting however, then the power supply should be switched
off and the wiring checked.
-The digital readout should now light up.
- Connect a voltmeter to the output terminals and check whether the output
voltage is adjustable between 0 and 30V. Around approximately 12V one
should hear the relay excitation.
-Switch off the power supply (remove mains plug as well).
- Connect the right transistor board connections E, B and C with the
corresponding connections of the base board by means of pieces of white, blue
and red wire. (do not forget the cable shoes) (see figure 7.0).
- Make an interconnection from one transistor board to the other.
(see figure 7.0).
-Switch the power supply back on (the lamp can now light up as well) and check
whether the output voltage is adjustable between 0 and 30V.
- Remove the mains voltage and also remove the lamp connections of the fuse
holder. Mount a 4A inert fuse in the fuse holder.
-The line voltage of the fan can now be connected. (see figure 6.2).


ADJUSTMENT OF THE POWER SUPPLY SECTION
- Connect an ampere-meter (minimum 1 OA range) over the output clamps.
-Turn current limitation potentiometer to maximum (completely to the right).
-Turn voltage regulator potentiometer (COARSE) to the intermediate position.
- Turn trimming potentiometer RV1 completely to the left (maximum current
adjustment).
- Turn trimming potentiometer RV2 completely to the right (minimum current
adjustment).
- Connect the power supply to the mains (the current limitation LED will light up
strongly).
- Carefully adjust RV1 until ampere-meter reads 1 OA.
-Adjust current limitation to 1A (center position).
- Carefully adjust RV2 until ampere-meter reads 1 A.
ADJUSTMENT OF DIGITAL READOUT
- Connect a voltage meter (30V range or more) to the power supply output.
-Put the current potentiometer (CURRENT LIMIT) to 1A.
- Switch on the power supply, if everything functions properly the readouts
should read 000.
-Adjust the power supply to a voltage of about 30V (see measuring appliance).
-Adjust the METER ADJUST of the voltage meter until the readout is the same
as that of the connected measuring appliance.
- Replace the voltagemeter by an ampere-meter (minimum 1 OA).
- Adjust the current until the ampere-meter reads about 8A.
-Adjust the METER ADJUST of the ampere-meter until the readout is the same
as that of the connected measuring appliance.
Finally mount the top cover (by sl iding) by first removing the front panel, the
power supply is now ready for use.
