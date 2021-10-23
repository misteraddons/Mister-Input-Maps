# Mister Input Maps
 Pre-configured input maps for MiSTer FPGA

 This is a collection of input mappings for common controllers.

 It enables use of controllers out of the box without mapping.

 If the default mapping is not to your liking, feel free to re-map the controller.
 
 All .map files must reside in ``/media/fat/config/inputs/*.map`` without sub-directories

# Methodology
```
 Menu/OSD: Home button or Down + Start for controllers without home button
 OK: Microsoft = A, Nintendo = A (in the process of changing to B), Playstation = X
	This needs testing as it may not work for 8BitDo controllers that emulate PS/Xbox controllers
 Back: Microsoft = B, Nintendo = B, Playstation = O
```
# Joystick Mapping
```
4 5 6    Y X L
1 2 3    B A R 

Coin = Select
Start = Start
Menu/OSD = Home/PS/Guide or Down + Start
```
# Arcade Game Controller Mapping (Arcade_Inputs folder)
```
Select = Coin
Start = Start
Pause = L2
Start 2P Game (this is choosing 1P or 2P game, NOT 2P start) = R2
Notes: 
1) Controllers with fewer than 8 buttons may have Pause and Start 2P Game mapped to L1 and R1
2) Start 2P Game is NOT 2P Start. It's meant for older arcade games that had 1 set of controls but allowed for alternating 2 player gameplay. Don't get it twisted.

Left analog stick is mapped to left dpad so either can be used in any game
Right analog stick is mapped for twin stick shooters

1 button games:
<=3 button        4 button        6 button
                     -            -   -   -
                  -     -
1   -   -            1            1   -   -

2/3 button games:
<=3 button        4 button        6 button
                     -            -   -   -
                  1     3
1   2   3            2            1   2   3


4 button games:
4 button        6 button (slanted diamond pattern on most 6 button pads)
   4            1   4   -
1     3
   2            2   3   -


6 button games:
4 button        6 button
   6 (R2)           
   3 (R1)           
   2            1   2   3
1     5
   4            4   5   6
```

# Limitations
 Several 8BitDo controllers share the same vendor ID and part ID (VID:PID = 045e:028e)

 These are named appropriately in the repository but may need to be renamed 
