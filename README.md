# Keychron C1 White Info

## PCB version
Keychron C1 White Ver.1.2/20200720

## MCU 
HFD48KC900

This seem to be a rebranded SN32F268

## Pinout
| Pin          | Function   
|--------------|------------
| P0.0 - P0.15 | C1 - C16  
| P1.0 - P1.2  | Unused  
| P1.3 	       | Caps LED
| P1.4 	       | Mac LED
| P1.5 	       | Windows LED
| P2.0 - P2.2  | A1 - A3 
| P2.3 - P2.8  | D1 - D6   
| P2.9 - P2.10 | A8 - A9	
| P3.0         | C17
| P3.1 - P3.3  | Unused
| P3.4         | A4	 
| P3.5         | BOOT
| P3.6         | SWCLK
| P3.7         | SWDIO / Windows-Mac switch 

The Caps, Mac and Windows LEDs are on when GPIO is driven high.

The Windows-Mac switch requires the interal pull-up, and is connected to ground in the Mac position.

SWD debugging should be possible if the switch is in the Windows position.

## Matrix
![matrix](/matrix.png)*Partial switch & LED matrix schematic*

