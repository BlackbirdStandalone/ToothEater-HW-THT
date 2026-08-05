# ToothEater-HW-THT

This repository contains the hardware design of the Honda Blackbird v1.1 Tooth Eater Module - (Through hole version). This through hole version is intended for the DIY'er for easier construction. This PCB is a simple 2 layer design, measuring 44mm x 44mm for insertion into the Hammond 1551R case.<br /><br />
This hardware is designed to work with the latest firmware version (v1.x) contained in the firmware respository. I.e. <i>'ToothEater_v1.2.hex'.</i><br />
<br />
Shown below are blank boards as received by PCBWay. This is a small unit slightly larger than a matchbox, shown in the 2" x 2" case.

<table border="1">
<tr>

<td align="center" valign="center">
<img 
    style="display: block; 
           margin-left: auto;
           margin-right: auto;
           width: 100%;"
    src="images/TE_v1.0_PCB.png#center">
</img>
</td>

<td>
<img 
    style="display: block; 
           margin-left: auto;
           margin-right: auto;
           width: 100%;"
    src="images/TE_v1.0_Boxed.png#center">
</img>
</td>

</tr>
</table>

<br />

A zoomed picture of the board is shown below. The full bill of materials can be found in the 'BOM' directory, however the table below will quickly identify the components. This table reflects the BOM for PCB v1.1.

<table border="3">
<tr>
<td align="center" valign="center"><b><u>Component</u></b></td>
<td align="center" valign="center"><b><u>Value</u></b></td>
</tr>

<tr>
<td align="center" valign="center">U1</td>
<td align="center" valign="center">atTiny85 microcontroller</td>
</tr>

<tr>
<td align="center" valign="center">U2</td>
<td align="center" valign="center">VR conditioner plug-in module (speeduino compatible)</td>
</tr>

<tr>
<td align="center" valign="center">U3</td>
<td align="center" valign="center">MCP100 reset chip</td>
</tr>

<tr>
<td align="center" valign="center">Q1</td>
<td align="center" valign="center">BD681</td>
</tr>

<tr>
<td align="center" valign="center">D1</td>
<td align="center" valign="center">1N4004</td>
</tr>

<tr>
<td align="center" valign="center">D2</td>
<td align="center" valign="center">6.2v zener</td>
</tr>

<tr>
<td align="center" valign="center">C1, C2</td>
<td align="center" valign="center">100n</td>
</tr>

<tr>
<td align="center" valign="center">R1</td>
<td align="center" valign="center">1K5</td>
</tr>

<tr>
<td align="center" valign="center">R2</td>
<td align="center" valign="center">470</td>
</tr>

<tr>
<td align="center" valign="center">R3,R5</td>
<td align="center" valign="center">10K</td>
</tr>

<tr>
<td align="center" valign="center">R4,R6</td>
<td align="center" valign="center">1K</td>
</tr>

<tr>
<td align="center" valign="center">R7,R9</td>
<td align="center" valign="center">47K</td>
</tr>

<tr>
<td align="center" valign="center">R11</td>
<td align="center" valign="center">4K7</td>
</tr>

<tr>
<td align="center" valign="center">R8,R10,R12</td>
<td align="center" valign="center">330</td>
</tr>

<tr>
<td align="center" valign="center">Q2,Q3,Q4,Q5,Q6</td>
<td align="center" valign="center">BC546B</td>
</tr>

<tr>
<td align="center" valign="center">D3</td>
<td align="center" valign="center">Power Led - Red (standard 3mm spacing)</td>
</tr>

<tr>
<td align="center" valign="center">D4,D5</td>
<td align="center" valign="center">Crank and cam Leds - Yellow (standard 3mm spacing)</td>
</tr>

<tr>
<td align="center" valign="center">J1,J2</td>
<td align="center" valign="center">Molex Micro-Fit 3.0 43045 </td>
</tr>

</table>


<img 
    style="display: block; 
           margin-left: auto;
           margin-right: auto;
           width: 100%;"
    src="images/PlainBoard.jpg#center">
</img>

<br /><br />
The board is shown below with the components assembled.
<img 
    style="display: block; 
           margin-left: auto;
           margin-right: auto;
           width: 100%;"
    src="images/BoardAssembledWithoutVR.jpg#center">
</img>

<br />



<table border="1">

The following illustrates different views of the v1.1 assembled board (without the VR mini-board installed).<br />

<tr>
<td align="center" valign="center">
<img 
    style="display: block; 
           margin-left: auto;
           margin-right: auto;
           width: 100%;"
    src="images/3dBoard_NoVr_1.jpg#center">
</img>
</td>
<td>
<img 
    style="display: block; 
           margin-left: auto;
           margin-right: auto;
           width: 100%;"
    src="images/3dBoard_NoVr_2.jpg#center">
</img>
</td>
</tr>

<tr>
<td align="center" valign="center">
<img 
    style="display: block; 
           margin-left: auto;
           margin-right: auto;
           width: 100%;"
    src="images/3dBoard_NoVr_3.jpg#center">
</img>
</td>
<td>
<img 
    style="display: block; 
           margin-left: auto;
           margin-right: auto;
           width: 100%;"
    src="images/3dBoard_NoVr_4.jpg#center">
</img>
</td>
</tr>

</table>


<table border="1">
<tr>

<br /><br />
The board is shown below with two mini wiring harnesses connected to it, along with the speeduino compatible VR plug in mini board.

<td align="center" valign="center">
<img 
    style="display: block; 
           margin-left: auto;
           margin-right: auto;
           width: 100%;"
    src="images/BoardWithWiresAndVR.jpg#center">
</img>
</td>



</tr>
</table>


<br /><br />
Once the VR board is inserted into the tooth eater module, it may sit to tall such that it will not allow the lid to close on the case. This is due to the height of the two female 4x1 headers (8.5mm height) that is sits within. To remedy this, the plastic stand-offs may be pryed off with a screwdriver or similar. This will allow the VR module to sink lower into the tooth eater board once it is inserted.

<img 
    style="display: block; 
           margin-left: auto;
           margin-right: auto;
           width: 100%;"
    src="images/RemovingPlasticStandoff.jpg#center">
</img>

<br />
Afterwards it will sit as follows. The overall height will now allow the package to fit within the case.

<img 
    style="display: block; 
           margin-left: auto;
           margin-right: auto;
           width: 100%;"
    src="images/TallFemaleHeader.jpg#center">
</img>


<br /><br />
When assembled, the BD681 transistor sits slightly proud of the case top (~2mm). This can be fixed by bending it to the left as shown.

<img 
    style="display: block; 
           margin-left: auto;
           margin-right: auto;
           width: 100%;"
    src="images/TransistorSittingProud.jpg#center">
</img>

<img 
    style="display: block; 
           margin-left: auto;
           margin-right: auto;
           width: 100%;"
    src="images/BendPowerTransistor.jpg#center">
</img>


<br /><br />
The connectors require a section to be cut out of the case.
<img 
    style="display: block; 
           margin-left: auto;
           margin-right: auto;
           width: 100%;"
    src="images/CutSection-Before.jpg#center">
</img>
<img 
    style="display: block; 
           margin-left: auto;
           margin-right: auto;
           width: 100%;"
    src="images/CutSection-After.jpg#center">
</img>

<br /><br />
The board is fitted to the case and relative size is shown.

<img 
    style="display: block; 
           margin-left: auto;
           margin-right: auto;
           width: 100%;"
    src="images/CompletedCase.jpg#center">
</img>
<img 
    style="display: block; 
           margin-left: auto;
           margin-right: auto;
           width: 100%;"
    src="images/RelativeSize.jpg#center">
</img>

<br /><br />


<table border="3">
<tr>
<td>
<p style="text-align: left;">The final connections are shown as follows:</p>
</td>
</tr>

<tr>
<td>
<img 
    style="display: block; 
           margin-left: auto;
           margin-right: auto;
           width: 100%;"
    src="images/Connectors.png#center">
</img>
</td>
</tr>

<tr>
<td>
<p>The board requires +12v and a ground connection. These can be tapped off the wires that feed your ECU.</p>
</td>
</tr>

<tr>
<td>
The inputs to this module are:
<ul>
  <li> CRANK VR+ (from the bikes wiring harness) </li>
  <li> CAM VR+ (from the bikes wiring harness) </li>
  <li> VR- (shared with both crank & cam VR- on the bikes wiring harness) </li>
</ul>
</td>
</tr>

<tr>
<td>
The outputs are:
<ul>
  <li>CAM TTL (0-4.1v level single cam pulse - fed into your downstream ECU)</li>
  <li>CRANK TTL (0-4.1v level single crank pulse - fed into your downstream ECU)</li>
  <li>TACHO (0-12v level square wave - fed to your dash via pin A19 on main wiring harness)</li>
</ul>
</td>
</tr>

<tr>
<td>
<p>Notes:<br />
1. The crank signal is the 12 pulses per crank rotation. The cam signal is post-processed by the tooth eater, therefore 1 cam pulse per engine cycle (I.e. Two crank revolutions, 720 deg).<br /><br />
2. The TTL output voltages are square wave outputs. The output voltage is slightly less than 5.0v and realistically closer to 4.1v. This should be fine in practice for ECUs expecting either 5.0v or 3.3v inputs (with internal built in protection on its inputs). In the future on the next board revision, I may add a jumper and a voltage divider to offer both use cases.<br />
</p>
</td>
</tr>

</table>

<br />

## Additional notes to observe

1. If you are using the speeduino compatible VR conditioner mini board by 'OpenLogic EFI', then you will need to solder both VR1 and VR2 jumpers as shown in the image below. This is so your crank and cam signals can be processed by the tooth eater.
2. There are also additional jumpers on the underside of the board. If you are using the VR board as mentioned above then leave these open circuit (o.c) as they are. These jumpers are of no practial use on the bike. <br />
The purpose of these jumpers are mainly for bench testing the board with 0-5v TTL signals when testing with ardu-stim, so they should only be soldered when bench testing or when HALL effect sensors are being used instead of the VR.
<table border="1">
<tr>

<td align="center" valign="center">
<img 
    style="display: block; 
           margin-left: auto;
           margin-right: auto;
           width: 100%;"
    src="images/VR_Soldering.png#center">
</img>
</td>

<td>
<img 
    style="display: block; 
           margin-left: auto;
           margin-right: auto;
           width: 100%;"
    src="images/UndersideJumpers.png#center">
</img>
</td>

</tr>
</table>

<br /><br />

# Hardware Design

<table border="1">

<tr> 
<td width="20%">
<strong><u>Current Revision</u></strong>
</td>
<td width="60%">
<strong><u>Date</u></strong>
</td>
<td width="20%">
<strong><u>Author</u></strong>
</td>
</tr>

<tr>
<td width="20%">
v1.1
</td>
<td width="60%">
July 2026
</td>
<td width="20%">
Alex Kiaos
</td>
</tr>

</table>

<br />
This project has been designed in Kicad 6.0.11 under linux and is licenced under the CERN Open Hardware Licence Version 2 - Strongly Reciprocal (CERN-OHL-S).<br /><br />

The directory structure of this project is as follows:

<p id=directories>
<img src="./images/.directoryStructure.png" width="302">
</p>



<table border="1">

<tr> 
<td width="20%">
<strong><u>Directory</u></strong>
</td>
<td width="80%">
<strong><u>Description</u></strong>
</td>
</tr>

<tr>
<td width="20%">
BOM
</td>
<td width="80%">
Bill of materials
</td>
</tr>

<tr>
<td width="20%">
kicad
</td>
<td width="80%">
The main project file is 'ToothEater.kicad_pro' found under</br>'/pcb/kicad/ToothEater'.</br></br>
Gerber files can be found as a group of 9 individual files under the 'gerbers' directory or as a single zipped file under the 'gerber_zipped' directory for uploading to a PCB house for manufacture.</br></br>
The 'CustomLibrary' directory contains the custom symbols and footprints used in the project.
</td>
</tr>

</table>

</br>
After cloning the repository and opening the project for the first time, you may need to set up the symbol library path.<br />

To setup the symbols library, in the menu:<br>
<pre><i>Preferences -> Manage Symbol Libraries</i><br>
  Then in the 2nd tab under 'Project specific libraries' add the following:<br>
Nickname: <b>ToothEater</b><br>
Library Path: <b>${KIPRJMOD}/../CustomLibrary/symbols/ToothEater_symbols.kicad_sym</b><br>
</pre>
<br><br>

# Relevant links

### PCBWay
To visit the PCBWay project and/or place an [order](https://www.pcbway.com/project/shareproject/Honda_CBR_Tooth_Eater_Module_Compatibility_module_for_the_CBR_1100XX_Super_Bla_bf3a4c0d.html).


### Wiring Harness & Pinouts
To see the ECU pin-out details, refer to the latest pdf file at: 
[Wiring Harness Pinout diagram](https://github.com/BlackbirdStandalone/Documentation/tree/main/wiring).



