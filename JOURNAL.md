# Pancake Flipper
An upside-down toolchanger printer with belted Z axis

**Made by:** @tmshader ([GitHub](https://github.com/tmshader)) <br>
**Repository:** [https://github.com/tmshader/pancake-flipper](https://github.com/tmshader/pancake-flipper) <br>
**Total hours so far:** 24

- [x] I have a 3D printer or will be getting one before March 21st

## Log

### Day 0 -  Big research day
*(2025. 03. 06.)* <br>
*Hours: 10*

Started planning out the printer (a bit late for Infill tbh 😅). Done a lot of
research today and some CAD work.

The current plan is the following:
- Upside-down design
- Fits into filament box (200 x 200 x 70)
- 2 extruders with toolchanger
  - mechanical or electrical toolchanger <- to be decided, but mechanical is
    preferred
- 2020 and 1020 aluminium extrusions for structural rigidity and stability
- 3 linear rails for precise motion on all axes
- 1 belt for X and Y axes and 1 belt for Z axis
- Positron-style XY kinematics
- Positron hotend
- Eddy current bed leveling
- BTT SKR Pico v1.0 controller
- Rasberry Pi Zero 2 W main board
- Integrated power supply
- Enclosure
  - Fitting into the same filament box is preferred, but might not be possible
  - Not 100% planned out yet
  - Might not be included in final design

### Day 1 - First mockup of mechanical components
*(2025. 03. 07.)* <br>
*Hours: 5*

Found models for the linear rails, steppers and extrusions. After putting
together a quick model I realised that the 1020 extrusion option is not viable
for this printer, so I'm going to be using all 2020 extrusions.

Working on the placement of the Z stepper and the two extruder steppers. Tough
problem. I need to make it fit into the filament box, but also have 5 steppers,
2 control boards and a power supply in the foot of the printer. I'll continue
working on it tomorrow, it's gonna be a fun problem to solve.

### Day 2 - Iterate, iterate, iterate
*(2025. 03. 08.)* <br>
*Hours: 9*

Switched to two 1030 extrusions for the Y and Z axis as they are flatter but
also fit my original idea, which the 1020 extrusion did not.

Changed out the linear rails for 3 different types instead of using the same
type for all axes. This makes the printer stronger and more precise.

I'm having a hard time designing the Z axis belt stepper and the two extruder
steppers. It is hard to fit them all into the base, so I'm trying to put the
extruder steppers on the Z axis but that also introduces problems.
