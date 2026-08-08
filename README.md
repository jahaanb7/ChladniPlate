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

## Wiring

1. Signal source connects to the amplifier's audio input.
2. Power supply connects to the amplifier.
3. Amplifier output connects to the subwoofer terminals (positive to positive, negative to negative).

## Notes

- Only the center screw should be rigidly driving the plate. The four corner screws are meant to support the frame, not clamp the plate itself. If all five points are rigidly attached to the plate, it may not vibrate freely, which would limit the patterns that can form.
- This device runs a continuous single tone rather than music, so the amplifier should not be run at maximum volume for extended periods.
- The power supply should match the voltage and current requirements of the TPA3116 board.

## Images

<img width="958" height="789" alt="Screenshot 2026-08-08 at 12 15 28 PM" src="https://github.com/user-attachments/assets/3a78a94c-9bf3-49aa-a2a8-1352396c6195" />
<img width="1523" height="1049" alt="Screenshot 2026-08-08 at 12 15 15 PM" src="https://github.com/user-attachments/assets/524e4fd9-659f-4bb7-8fa3-8f3ccfdaa347" />
<img width="1540" height="1148" alt="Screenshot 2026-08-08 at 12 14 39 PM" src="https://github.com/user-attachments/assets/7c50ad6d-76e5-484f-adf2-9dae49cd5f5c" />
<img width="1344" height="901" alt="Screenshot 2026-08-08 at 12 26 03 PM" src="https://github.com/user-attachments/assets/10f066dc-6ffd-410b-8c89-5bbbc1c50dc2" />

