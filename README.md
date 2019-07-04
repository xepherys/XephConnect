# XephConnect
Daughter Board / Breakout Board for moving Duet connections to the tool.

This PCB design is being created for the RailCore II to move carriage-based connections (extruder steppers, thermistor, heater, Y-stop) to the tool using a single wire harness.

The idea for this started with my desire to create a tool carriage for the M3D QuadFusion, which has four (4) extruder steppers, but being able to run a single connector up to the tool that can swap between the QuadFusion and the E3D standard hotends.

In current iterations, the design calls for a TE 32-pin connector.  See PARTLIST.txt in the individual version folder for information on the components required.  See VERNOTES.txt for information and notes on each version.

v0.1 was the original design.  I hadn't designed a PCB in quite some time, and used auto-router. Not the greatest plan.  It's functional (it's on my RailCore II 300ZL currently, as of 7/4/19), but it has some issues with noise from the steppers interfering with the z-probe, and a few issues with hole spacing (one of the screws doesn't play nicely with one of the Molex headers).

v0.6, as of this update (7/4/19) is being manufactured as a prototype.  I should be testing it as soon as it arrives.  It requires different wiring of the main wire harness, but also includes wiring for the heater cartridge.
