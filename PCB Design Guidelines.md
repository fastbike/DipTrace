# PCB Design Guidelines

## Trace Widths

Assuming 1 oz copper layer, external layer track.

Low voltage signals: JLPCB can do down to 5mil for trace width with 5mil spacing for 2 layer boards. This is 0.127mm. They say they can do smaller for 4 layer boards but this is likely to be pushing it. 5mil will give 4 tracks per mm.

Low voltage power (<250mA):

Main Voltage: 20mil per Amp assuming short traces.  Check 2 Oz copper
Measured layouts: 

- RON03: 6.2mm single sided board

- Open Energy Monitor Relay: 3.14mm on both sides of board. Using 2.4mm routed cutouts between HV/LV. 2mm spacing between HV traces.

- iLON100: 2.5mm on both sides of board
