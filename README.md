# GizontShield

## Description

This is a contraption I designed as an experiment for a very specific setup in a very specific placement. An 868MHz LoRa MeshDore repeater that would be installed on a rooftop, that happened to be neighbours to another building that would have a cell tower on it.
The cell tower would deafen the repeater enough to make package reception rate errors go as high as 30%.

The fact that shielding could work was discovered by accident, when measuring the radiation of the cell tower using an RTL-SDR. Hiding behind a wall would bring the radiation of the tower down to noise floor levels.
This design embodies the same working principle, but optimized for minimum compromise: the antenna is expected to receive transmissions from any other source that is not directly behind or in front of the tower.

Design parameters are optimized for this placement's use case, and will be laid out in the design as variables for the design to nicely recompute to, if possible.



## Design parameters

- Gizont NB-iot 868MHz 20cm Antenna
- Horizontal angular size of interferer: 8,4º
- Distance from antenna axis: Roughly one base diameter: 11mm. Perhaps adjustable.
