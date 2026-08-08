# ChladniPlate
Built a DIY Chladni Plate demonstrating how resonance, vibration, and sound waves generate unique sand patterns. Also created custom software that generates frequencies to produce new, original patterns using Chladni modes and Bessel functions.

## Overview

This project is a Chladni plate, which is a device that turns sound into visible patterns. When a plate vibrates at certain frequencies, sand placed on top of it moves away from the vibrating areas and collects in the still areas. This creates a visible pattern that shows how the plate is vibrating.

## How It Works

The system uses a 6.5-inch subwoofer as a mechanical driver instead of a speaker. Rather than producing sound, the subwoofer's cone movement is used to physically vibrate the plate.

The signal path is as follows:

**Signal Source → TPA3116 Amplifier → Subwoofer → Acrylic Sheet → Aluminum Plate**

1. A tone (specific frequency) is generated from a signal source.
2. The TPA3116 amplifier boosts the signal so it is strong enough to drive the subwoofer.
3. The subwoofer cone vibrates based on the signal.
4. This vibration is transferred through five screws (one in the center, four around it) into an acrylic sheet.
5. The acrylic sheet connects to the aluminum plate, which is where the sand is placed.

## Assembly Instructions

### Tools & Materials Needed

- 3D printer + PLA filament
- Soldering iron (for heat-set inserts and wire connections)
- M3 heat-set threaded inserts + M3 screws + washers
- Drill with a small bit (roughly 3.2–3.5mm for clearance holes in the acrylic)
- Wire strippers
- Audio cable (headphone jack to RCA/aux, laptop to amp)

### Steps

1. **3D print the enclosure.**
   Print in PLA, which is easiest for beginners to work with. Use a 0.2mm layer height (good balance of speed and strength), 3 perimeter walls, and 20–25% infill for most of the part. If your slicer supports it, bump infill up to 40–50% specifically around the four mounting posts where the heat-set inserts will go, since those spots need to hold screws under tension. Use a brim if your printer has adhesion issues, and add supports only if your slicer flags overhangs greater than 45 degrees.

2. **Install the heat-set threaded inserts.**
   Before the subwoofer goes in, heat up your soldering iron to around 200–220°C. Press each M3 heat-set insert straight down into its printed hole using the iron tip, letting the heat melt the plastic just enough for the insert to sink in flush with the surface. Go slow and keep the insert perfectly vertical,, an off-angle insert will make screwing into it later frustrating or impossible. Do all four mounting posts before moving on.

3. **Route the wires, then seat the subwoofer.**
   Feed the subwoofer's wire leads through the dedicated wire hole in the enclosure before the speaker itself goes in, since it's much harder to thread wires through once the subwoofer is seated. Once the wires are through, carefully lower the subwoofer into its recess in the enclosure and check that it sits flush and centered.

4. **Drill the acrylic sheet.**
   Mark and drill four M3 clearance holes in the acrylic sheet, positioned to line up exactly with the four heat-set inserts in the enclosure. Also drill one hole in the very center of the sheet, sized to fit the center screw that will eventually connect through to the aluminum plate. Go slow with acrylic, it cracks easily if you drill too fast or press too hard, so use light pressure and let the bit do the work.

5. **Mount the acrylic sheet to the enclosure.**
   Place a washer on each of the four M3 screws, then pass each screw down through one of the acrylic sheet's corner holes. Line the acrylic up over the enclosure so the holes match the four threaded inserts, then thread each screw in by hand first to avoid cross-threading, and finish tightening with a screwdriver. Don't overtighten — snug is enough since these are small plastic-embedded inserts.

6. **Install the amplifier board.**
   Place the TPA3116 amplifier board into its spot inside the enclosure. Make sure it's sitting securely and that none of its solder joints or components are touching bare metal or the enclosure walls, which could short the board.

7. **Wire the subwoofer to the amplifier.**
   Strip a few millimeters of insulation off the subwoofer's two wire leads if not already done. Solder the positive subwoofer wire to the amplifier's positive speaker output terminal, and the negative wire to the negative terminal. Double check polarity before soldering — reversed polarity won't damage anything at this power level but will affect how the plate responds.

8. **Connect the amplifier to your laptop.**

## Images

<img width="958" height="789" alt="Screenshot 2026-08-08 at 12 15 28 PM" src="https://github.com/user-attachments/assets/3a78a94c-9bf3-49aa-a2a8-1352396c6195" />
<img width="1523" height="1049" alt="Screenshot 2026-08-08 at 12 15 15 PM" src="https://github.com/user-attachments/assets/524e4fd9-659f-4bb7-8fa3-8f3ccfdaa347" />
<img width="1540" height="1148" alt="Screenshot 2026-08-08 at 12 14 39 PM" src="https://github.com/user-attachments/assets/7c50ad6d-76e5-484f-adf2-9dae49cd5f5c" />
<img width="1344" height="901" alt="Screenshot 2026-08-08 at 12 26 03 PM" src="https://github.com/user-attachments/assets/10f066dc-6ffd-410b-8c89-5bbbc1c50dc2" />

