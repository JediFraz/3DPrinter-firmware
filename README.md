# 3DPrinter-firmware
Trying to build a new firmware for my 3D printer since I replaced a faulty mainboard. Original mainboard was a Hictop Ramps 1.4. Have replaced it with a MKS Base v1.4 with DRV 8825 steppers.

Printer started life as Hictop 3DP-03 i3 Prusa Heated build bed (X,Y,Z 210,270.175) but no auto levelling sensors or levelling probe.
Got Marlin 1.1.3 working but unable to get satisfactory first klayer out of printer...

Fixed stepper direction error. Fixed Limit switch and homing errors. LCD heatbed not displaying fixed. Still have couple minor display issues. Vref voltage on steppers calibrated, Steps doubled to make final print to correct size. Extrusion steps calibrated twice.

Current Fault state.
1. Initial printing gap (0.4mm) not same as Z axis home gap (0.2mm).
2. Under extrusion when printing despite extruder being calibrated.

