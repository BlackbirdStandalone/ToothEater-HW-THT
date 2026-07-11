# ToothEater-HW-THT

This repository contains the hardware design of the Honda Blackbird v1.0 Tooth Eater Module - (Through hole version). This through hole version is intended for the DIY'er for easier construction. This PCB is a simple 2 layer design, measuring 44mm x 44mm for insertion into the Hammond 1551R case.<br /><br />
This hardware is designed to work with the latest firmware version (v1.1) contained in the firmware respository. I.e. <i>'ToothEater_v1.1.hex'</i><br />
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

A zoomed picture of the board is shown below. The full bill of materials can be found in the 'BOM' directory, however the table below will quickly identify most components.

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
The board is shown below with the components assembled. It is up to you whether you install a 8-pin DIP socket for the microcontroller. I pre-programmed mine and just soldered it in. Also, the 8-pin DIP socket for the VR module is also not ideal, but will work just fine. It is better to use a two 1x4 pin female headers of appropriate height.
<img 
    style="display: block; 
           margin-left: auto;
           margin-right: auto;
           width: 100%;"
    src="images/BoardAssembledWithoutVR.jpg#center">
</img>

<br />


<table border="1">
<tr>

<br /><br />
On the left: The assembled board, connectors installed as well as the VR plug-in module.<br />
On the right: The case (Hammond 1551R).

<td align="center" valign="center">
<img 
    style="display: block; 
           margin-left: auto;
           margin-right: auto;
           width: 100%;"
    src="images/Board_1.jpg#center">
</img>
</td>

<td>
<img 
    style="display: block; 
           margin-left: auto;
           margin-right: auto;
           width: 100%;"
    src="images/Case_Hammond_1551R.jpg#center">
</img>
</td>

</tr>
</table>


<br /><br />
Looking through the board, it can be seen that the pins on the VR mini-board don't bottom out. This doesn't appear ideal, but is fine in practice. With the VR board pressed down until it bottoms out, all the components on the tooth eater board are cleared of the VR board.

<img 
    style="display: block; 
           margin-left: auto;
           margin-right: auto;
           width: 100%;"
    src="images/VR_PinHeight.jpg#center">
</img>

<br /><br />
When assembled, the BD681 transistor sits slightly proud of the case top (~2mm). This can be fixed by slightly cutting into the lid in that area. 
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
    src="images/LidModification.jpg#center">
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
    src="images/BoardInCase-SideView.jpg#center">
</img>
<img 
    style="display: block; 
           margin-left: auto;
           margin-right: auto;
           width: 100%;"
    src="images/BoardInCase-TopView.jpg#center">
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
  <li>CAM TTL (0-5v level single cam pulse - fed into your downstream ECU)</li>
  <li>CRANK TTL (0-5v level single crank pulse - fed into your downstream ECU)</li>
  <li>TACHO (0-12v level square wave - fed to your dash via pin A19 on main wiring harness)</li>
</ul>
<p> Note: The crank signal is the 12 pulses per crank rotation. The cam signal is post-processed by the tooth eater, therefore 1 pulse per engine cycle (two crank revolutions).</p>
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


