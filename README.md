# 3DPrinter-firmware
Trying to build a new firmware for my 3D printer since I replaced a faulty mainboard. Original mainboard was a Hictop Ramps 1.4. Have replaced it with a MKS Base v1.4 with DRV 8825 steppers.

Printer started life as Hictop 3DP-03 i3 Prusa Heated build bed (X,Y,Z 210,270.175) but no auto levelling sensors or levelling probe.
Initially tried Marlin1.1.3 but LCD display/ Controller didn't work. Ended up using 2004 LCD Marlin firmware as it worked..:)
Learned enough to fix arduino compil error in v 1.8.3. Fixed stepper direction error. Fixed Limit switch and homing errors. Vref voltage on steppers calibrated, Extrusion steps calibrated.

Current state.
1. Initial print gap (0.4mm) not same as Z axis home gap (0.2mm).
2. Under extrusion when printing despite extruder calibrated.
3. Dont like actions on print start. X axis move and what seems like big Z axis move before test extrusion. 
