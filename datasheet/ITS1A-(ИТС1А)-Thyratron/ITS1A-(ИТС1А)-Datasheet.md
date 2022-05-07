# Gas-discharge sign-synthesizing indicators ITS1A (ИТС1А), ITS1B (ИТС1Б)

Single-digit gas-discharge digital indicators to display information in the form of numbers from 0 to 9 in the
media                             
displaying individual and group information. Glass body, flexible leads. Maximum weight 25g.

![Pin Diagram](pin-diagram.png "Pin Diagram")

## Pin assignment

| Pin | Name of electrodes    |
|----:|-----------------------|
|   1 | Unused                |
|   2 | First anode           |
|   3 | First grid, segment C |
|   4 | Cathode               |
|   5 | First grid, segment B |
|   6 | Second grid           |
|   7 | Subcathode            |
|   8 | First grid, segment A |
|   9 | First grid, segment F |
|  11 | First grid, segment G |
|  11 | First grid, segment E |
|  12 | First grid, segment D |
|  13 | Unused                |
|  14 | Second anode          |

## Connecting pins when forming numbers

| Number | Pins                   |
|-------:|------------------------|
|      0 | 3, 5, 8, 9, 11, 12     |
|      1 | 3, 5                   |
|      2 | 5, 8, 10, 11, 12       |
|      3 | 3, 5, 8, 10, 12        |
|      4 | 3, 5, 9, 10            |
|      5 | 3, 8, 9, 10, 12        |
|      6 | 3, 8, 9, 10, 11, 12    |
|      7 | 3, 5, 8                |
|      8 | 3, 5, 8, 9, 10, 11, 12 |
|      9 | 3, б, 8, 9, 10, 12     |

## Operating conditions

<table>
<tr>
<td>Vibration loads<br>
&nbsp;&nbsp;&nbsp;&nbsp;frequency range<br>
&nbsp;&nbsp;&nbsp;&nbsp;maximum acceleration
</td>
<td>
<br>
1 - 600<br>
49 (5)
</td>
<td>
<br>
Hz<br>
m/s<sup>2</sup> (G)
</td>
</tr>        
<tr>
<td>
Multiple shock loads<br>
&nbsp;&nbsp;&nbsp;&nbsp;maximum acceleration<br>
&nbsp;&nbsp;&nbsp;&nbsp;impact duration
</td>
<td align="right">
<br>
392 (40)<br>
10
</td>
<td>
<br>
m/s<sup>2</sup> (G)<br>
ms
</td>
</tr>    
<tr>
<td>
Single shock loads  <br>
&nbsp;&nbsp;&nbsp;&nbsp;maximum acceleration<br>
&nbsp;&nbsp;&nbsp;&nbsp;impact duration
</td>
<td align="right">
<br>
1472 (150)<br>
2
</td>
<td>
<br>
m/s<sup>2</sup> (G)<br>
ms
</td>
<tr>
<td>
Acoustic noise<br>
&nbsp;&nbsp;&nbsp;&nbsp;frequency range<br>
&nbsp;&nbsp;&nbsp;&nbsp;maximum sound pressure level
</td>
<td align="right">
<br>
50 - 10,000<br>
140
</td>
<td>
<br>
Hz<br>
dB
</td>
</tr>    
<tr>
<td>Ambient temperature</td>
<td align="right">-60 - +85</td>
<td>°С</td>
</tr>    
<tr>
<td>Maximum relative air humidity</td>
<td align="right">98</td>
<td>%</td>
</tr>    
<tr>
<td>Minimal air pressure</td>
<td align="right">666 (5)</td>
<td>Pa (mmHg)</td>
</tr>    
<tr>
<td>Maximal air pressure</td>
<td align="right">294198 (3)</td>
<td>Pa (kg/cm2)</td>
</tr> 
</table>

## Basic data

<table>
<tr>
<td>Glow color</td>
<td>Green</td>
<td></td>
</tr>         
<tr>
<td>Minimum brightness of the indicator segment</td>
<td align="right">80</td>
<td>cd/m<sup>2</sup></td>
</tr>             
<tr>
<td>Minimum background brightness</td>
<td align="right">5</td>
<td>cd/m<sup>2</sup></td>
</tr>                 
<tr>
<td>
Maximum irregularity of luminescence brightness<br>
&nbsp;&nbsp;&nbsp;&nbsp;segments<br>
&nbsp;&nbsp;&nbsp;&nbsp;along the segment
</td>
<td align="right">
<br>
50<br>
80
</td>
<td>
<br>
%<br>
%
</td>
</tr>             
<tr>
<td>Viewing angle</td>
<td align="right">120</td>
<td>degrees</td>
</tr>             
<tr>
<td>Maximum readiness time in the dark</td>
<td align="right">90</td>
<td>s</td>
</tr>                 
<tr>
<td>Maximum electric strength recovery time</td>
<td align="right">500</td>
<td>μs</td>
</tr>               
<tr>
<td>
Unlocking static and impulse voltages 1st and 2nd mesh (segment)<br>
&nbsp;&nbsp;&nbsp;&nbsp;ITS1A<br>
&nbsp;&nbsp;&nbsp;&nbsp;ITS1B
</td>
<td align="right">
<br>
0.4 - 4.0<br>
0.4 - 5.0
</td>
<td>
<br>
s<br>
s
</td>
</tr>               
<tr>
<td>
The discharge initiation voltage at the 2nd anode (segment)<br>
&nbsp;&nbsp;&nbsp;&nbsp;in the presence of a control signal maximum<br>
&nbsp;&nbsp;&nbsp;&nbsp;in the absence of a control signal minimal
</td>
<td align="right">
<br>
86<br>
120
</td>
<td>
<br>
V<br>
V
</td>
</tr>               
<tr>
<td>Maximum total preparatory discharge current</td>
<td align="right">700</td>
<td>μA</td>
</tr>               
<tr>
<td>
Average current of electrodes<br>
&nbsp;&nbsp;&nbsp;&nbsp;first grid<br>
&nbsp;&nbsp;&nbsp;&nbsp;second grid<br>
&nbsp;&nbsp;&nbsp;&nbsp;first anode<br>
&nbsp;&nbsp;&nbsp;&nbsp;second anode<br>
&nbsp;&nbsp;&nbsp;&nbsp;subcathode
</td>
<td align="right">   
<br>
40<br>
30<br>
100<br>
200<br>
100
</td>
<td> 
<br>
μA<br>
μA<br>
μA<br>
μA<br>
μA
</td>
</tr>               
<tr>
<td>Minimum operating time</td>
<td align="right">5000</td>
<td>h</td>
</tr>              
<tr>
<td>
Parameter that changes during the minimum operating time, unlocking voltage of the first and second grids (segment)<br>   
&nbsp;&nbsp;&nbsp;&nbsp;ITS1A<br>
&nbsp;&nbsp;&nbsp;&nbsp;ITS1B
</td>
<td align="right">  
<br>
0.4 - 4.2<br>
0.4 - 5.2
</td>
<td>
<br>
V<br>
V
</td>
</tr>              
<tr>
<td>Minimal shelf life</td>
<td align="right">12</td>
<td>years</td>
</tr> 
</table>

## Maximum permissible electrical mode

<table>
<tr>
<td>Negative voltage at the sub-cathode (constant)</td>
<td align="right">235 - 265</td>
<td>V</td>
</tr>    
<tr>
<td>Voltage at the 1st anode (constant or amplitude pulsating)</td>
<td align="right">36 - 44</td>
<td>V</td>
</tr>    
<tr>
<td>Voltage at the 2nd anode (constant or amplitude pulsating)</td>
<td align="right">90 - 110</td>
<td>V</td>
</tr>    
<tr>
<td>The voltage on the first and second grids necessary to emergence discharge</td>
<td align="right">-0.3 - +0.4</td>
<td>V</td>
</tr>    
<tr>
<td>The shortest voltage pulse duration at the first and second grids</td>
<td align="right">100</td>
<td>μs</td>
</tr>     
<tr>
<td>The shortest voltage pulse duration discharge at residual voltages at first anode no more than 4 V, on the second anode no more than 10 V</td>
<td align="right">500</td>
<td>μs</td>
</tr>     
<tr>
<td>
The smallest average power reduced to one segment<br>
&nbsp;&nbsp;&nbsp;&nbsp;on power circuits<br>
&nbsp;&nbsp;&nbsp;&nbsp;on control circuits
</td>
<td align="right">
<br>
50<br>
0.2
</td>
<td>
<br>
mW<br>
mW
</td>
</tr>    
</table>

## Recommendations for use

The current of the grids and the first anode in the non-conducting state has a positive direction, in the conducting
state, the direction of the current voltage on the grids should not exceed +10V in the mode memory on the first anode
and +30V in the memory mode on the second anode do. Otherwise, the grid can extinguish the discharge. Increase by
voltage at the second anode to a value greater than 120 V, can lead to failure of the indicator and circuit elements due
to a sharp increasing the anode current.

The indicator does not require the inclusion of external limiting resistances tension in the chain of electrodes.

After storage or break in work for more than 1 month. recommends preliminarily apply operating voltage to the electrodes
of the indicator for a period of at least 10 minutes.

Soldering of flexible leads should be carried out at a distance not less than 10 mm from the glass of the cylinder to
avoid chips and cracking glass. Bend the leads at a distance of at least 3 mm from the glass of the cylinder. 
