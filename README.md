# Mister Input Maps
 Pre-configured input maps for MiSTer FPGA

 This is a collection of input mappings for common controllers.

 It enables use of controllers out of the box without mapping.

 If the default mapping is not to your liking, feel free to re-map the controller.

# Methodology
```
 Menu/OSD: Home button or Down + Start for controllers without home button
 OK: Microsoft = A, Nintendo = A, Playstation = X
	This needs testing as it may not work for 8BitDo controllers that emulate PS/Xbox controllers
 Back: Microsoft = B, Nintendo = B, Playstation = O
```
# Arcade Button Mapping
```
4 5 6    Y X L
1 2 3    B A R 

Credit = Select
Start = Start
Menu/OSD = Home/PS/Guide or Down + Credit
```

# Limitations
 Several 8BitDo controllers share the same vendor ID and part ID (VID:PID = 045e:028e)

 These are named appropriately in the repository but may need to be renamed 
