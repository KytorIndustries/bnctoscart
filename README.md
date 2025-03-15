# BNCtoSCART
Connect an RGBs (Red, Green, Blue, CSync) signal over BNC and Stereo Audio signal over RCA to your RetroTINK-5X Pro through the side SCART connection. 

Typical use case would be with a Extron Crosspoint or daisy-chain from the output of a PVM, TTL CSYNC only (jumper included for 75 ohm CSYNC). Connections are turned 90° so they are facing backwards, creating a simple and clean cable management path in your entertainment system.

- Input: 4x [BNC] and 2x [RCA]
- Outputs: 1x [SCART]

![BNCtoSCART](photos/DSC_8581.jpg)

## Files Included
- **PCB Design Files** (DipTrace, Gerber)
- **3D Print Files** (STEP, STL, 3MF for Bambu Studio)
- **Bill of Materials** (XLSX)
- **Photos**

## Additional Parts Required
- [2x M3x6 Screws](https://amzn.to/43MXFzS)
- [2x M3x10 Screws](https://amzn.to/43MXFzS)
- [RetroTINK-5X Pro](https://www.retrotink.com/product-page/5x-pro)

## Assembly
1. Solder BNC, RCA and resistor components in place.
2. The flat end SCART connector should be aligned with the board edge, ensure it is properly square and aligned and solder in place.
3. The jumper must only be closed for 75 ohm CSYNC only, otherwise damage to the RetroTINK-5X Pro may result. Do not close this jumper unless you are absolutely certain of 75 ohm CSYNC.
4. Clean the board with isopropyl alchohol, then ultrasonic cleaning is recommended.
5. Apply hot glue to fill the void between the bottom of the RCA connector and the top of the PCB.
6. Secure the PCB assembly to the shell with (2) of M3x6 screws.
7. Screw the shell halves together with (2) of M3x10 screws.

## PCB Revision History
- Ver 1.1 - First production version
- Ver 1.2 - Added sync jumper and screw indication
- Ver 1.3 - Fixed SCART bottom pads alignment (Initial Open Source Release)

## Shell Revision History
- Rev 1 - First production version
- Rev 2 - Modified bottom shell for low profile BNC jacks
- Rev 3 - New internal geometry to print with minimal supports (Initial Open Source Release)

## License
This project is open-source under the [CC BY 4.0 (Attribution 4.0 International)](https://creativecommons.org/licenses/by/4.0/).

## Disclaimer
This project is provided "as-is" without any warranty, express or implied, including but not limited to warranties of merchantability or fitness for a particular purpose. No support is provided.

Amazon links are affiliates.