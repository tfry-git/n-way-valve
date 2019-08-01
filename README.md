# n-way-valve
A 3d home-printable 1-to-12+ position valve for low-pressure applications, and a sample plant watering software

# Status
I know this is lacking proper documentation, so far. Hang on, I'll type up some, eventually. However it works so well that the time has come to share.

# Basic description / instructions
## What this is:
This valve has one input and 12 outputs (could be scaled to more). I designed it for the task of individualized plant watering.

The valve can be 3d printed on an inexpensive 3d printer, using inexpensive filament (I used PLA, and despite it's reputation to be sensible to moisture, this seems to work quite well). Current 3d printers / slicers are known to produce too small inner diameters. I've taken this into account for the main rotor element, but you'll probably have to drill the 6mm input/output port holes to 6mm. Be sure to sand the inner surfaces a bit to achieve a smooth surface and less leakage. Assemble the parts using small screws or nails where needed.

It can be driven using a cheap and ubiquitary 28BYJ-48 stepper motor, and comes with proper fixation and gears for that.

## Limitations:
* The valve is uni-directional. Unused valve positions are not shut.
* The valve is *not tight*. You will get some leakage across the output ports, and also a few drops through other gaps. However, the majority of water will go through the destined output.
* The value is *not* suited for high pressure. The higher the pressure, the more leakage.
* The value should only be used upright, horizontally, and ideally above the water reservoir (to catch and re-use leaking water).

To be honest I have trouble thinking of use cases other than plant watering, but it does work really well for this use case.

# Software
Think of the attached sketch as an example for getting started. The main item in this repository is the 3d model(s).

# Outlook
I have some tweaks in mind to further reduce the leakage. Also, I might try a linear (instead of rotary) version one day, as this should allow to use sealing-washers.

# Licence
This work is licensed under a Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License (https://creativecommons.org/licenses/by-nc-sa/4.0/).

If you wish to (re-)use this work under different terms, please contact me.
