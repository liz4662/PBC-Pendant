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

While designing my PCB layout, I had to take into consideration what design I wanted to have on order to effectively place each part of the PCB. After placing each part strategically round the timer chip and adding my design. I generated the svg files for the drill holes, edge cuts and traces. Using these files I was able to carve my PCB pendantusing a Carvey CNC.

# Soldering Components
I decided to use different component values that those used in the tutorial because I wanted a higher flashing frequency. During the soldering process, I had to be very careful considering that my traces and copper pads were very tiny. It took a lot of pacience and presision to make sure the solder was not making unnecessary connections. The most difficult part was sodlering the timer chip since for some of the pins there was very little pad to event make contact with. I got the LED to flash and everything looked perfect but since I had my pendant in my backpack I later realized the led light accidentally snapped off of the board and with it took the copper pad it was connected to and damaged the traces connected to them so I had to create a bridge of solder that could connect these diconnected parts. It was challenging but very satisfying when I was able to fix the connections and see my LED flashing again.

# Photos

![Heartbeat](images/demo.png)

