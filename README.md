# Chladni Plate — Turning sound into visual patterns

A Chladni Plate is a demonstration device that shows stunning visual patterns made from vibrating sand on a plate. Using a mechanical wave driver, we can convert digital audio into mechanical vibrations, which can vibrate the plate at certain frequencies to form specific standing wave patterns. These standing waves have regions of no oscillation called "nodal lines," and regions of oscillations are called "antinodes."

## System Overview:

The system uses a subwoofer to act as a DIY mechanical driver by connecting screws to its body in order to carry the vibrations. The subwoofer is connected to an amplifier which amplifies the sound to produce greater vibrations that can move the plate better. The amplifier is connected to a laptop or you can connect it to a microcontroller and upload a software to generate and control frequencies. 


Flowchart Diagram:

Signal Source (Laptop/Microcontroller) --> Amplifier (eg., TPA3116) --> Subwoofer (6.5 inches for me) --> (vibrates) metal/aluminum sheet

## How to Assemble:

### Tools Needed:
These tools are needed to assembly the Chladni plate, this does not include the BOM

- soldering iron
- audio cable/usb-a cable
- drill/screw driver
- 3d printer and filament

1) Using a 3D printer, print out the 'enclosure' step file. I recommend these settings: 25% - 30% infill, Filament: PLA or ABS
2) Heat up your soldering iron to a fairly high temperature (200-300 celsius— not very hot) and place the appropriate size heat-set inserts (the holes where the subwoofer goes are M3 heat-set inserts, while the other heat-set inserts for the cap of the amplifier board are M5) and press the tip of the soldering iron onto the heat-set inserts until they melt the plastic around and go into their respective holes.
3) Repeat for every place for which there is a hole in the enclosure, there should only be 8
4) Drill or make a hole in the center of the subwoofer and insert the threaded rod there, insert the other thread rods into each hole in the enclosure. Then for the outer threaded rods insert a M3 nut from the top and let it go down 1 cm.
5) Then carefully place the acrylic sheet through all the holes and make sure the the nuts can support the acrylic sheet.
6) Now place a nut on the center thread rod (the taller one) and spin it until it's down a centimeter as well. Then place the aluminum sheet through the hole and put another M3 nut on top with a washer attached.
7) Place the amplifier board into the dedicated region on the side of the enclosure.
8) Then connect the subwoofer wires through the holes in the enclosure and screw them onto the board. Also connect the USB-A / audio jack wire from your audio source (laptop) through the hole behind and connect that to the amplifier. You also have to connect a DC power supply (9V-24V) to the amplifier board.
9) Then place the cap on the top and screw in M3 size counter head screws until the cap is secured. And you're done!


## Wiring Diagram:

### <img width="900" height="712" alt="Screenshot 2026-08-19 at 11 29 45 PM" src="https://github.com/user-attachments/assets/1bc12865-3d66-4902-a3db-c22bf87dd119" />

## CAD Images

<img width="767" height="435" alt="Screenshot 2026-08-20 at 12 03 26 AM" src="https://github.com/user-attachments/assets/0882f45a-8854-4c54-8dbf-32a80a99b917" />

<img width="804" height="483" alt="Screenshot 2026-08-20 at 12 04 33 AM" src="https://github.com/user-attachments/assets/78d6e77a-fa91-40ef-b380-0613f3a7161c" />

