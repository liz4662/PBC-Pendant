# PBC-Pendant
This project involved creating a PCB pendant from scratch which includes designing a TLC555CP timer chip on KiCAD, milling our design, and soldering the part into the board.

All design files required to reproduce my PCB pendant, including the schematic, PCB layout, Gerber files, and CNC-friendly SVG files can be found under the 'design' folder.


# Software & tools required
- KiCad
- Easel (or any CNC software)
- CNC Milling Machine
- Soldering Station (and required soldering materials)

# Instructions
1. Clone the repository
2. If modifying KiCad design, open 555timerCES.kicad_pro in design folder in KiCad and follow SVG conversion in Step 2 of assignment spec found [here](https://github.com/Barnard-PL-Labs/PCB-Milling-Project-for-Creative-Embedded-Systems/blob/main/README.md)
3. If not modifying KiCad design, open SVG files in CNC software and mill on CNC machine according to assignment spec

# Components

Specific Components Used:

- TLC555CP Timer
- Coin Cell Battery Holder
- 10K resistor 1
- 100K resistor 2
- 470R resistor 3
- 2.2 nF capacitor 1
- 10 nF capacitor 2
- Red LED (2.0 - 2.2v)
- CR2032 Coin Cell Battery (3V)

With these specs, the LED flashing frequency was ~3 Hz according to this [555 Timer Astable Oscillator Circuit calculator](https://www.allaboutcircuits.com/tools/555-timer-astable-circuit/)

These components must be soldered onto the PCB board acording to the Kicad leayout


# Finished Product
![Demo](Videos/heartbeat.gif)


# Technical Details

While designing my PCB layout, I had to 
