# PEEPER v1.0

**Tiny screen. Big eyes.** PEEPER is a motion-reactive keychain concept built around a round colour display, an ESP32-S3 controller, and an accelerometer.

## Project
- Custom PCB design and assembly files
- Arduino firmware and prebuilt firmware image
- Animated eye modes: Googly, Robo, Cyclops, and Sleep
- JLCPCB fabrication BOM, pick-and-place file, and Gerbers

## Website
This repository contains a static GitHub Pages website. Once Pages is enabled, it will be available at:

https://stancupatrick1.github.io/Project_Peeper/

## Publishing
1. Open **Settings → Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select branch `main` and folder `/(root)`, then save.

## Project files
The landing page links to `assets/` and `downloads/`. Upload the supplied asset and download folders from the PEEPER GitHub Pages package to the repository root so the animations, board image, and downloadable files work.

## Hardware notes
The website describes the ESP32-S3, GC9A01 240×240 round display, LIS3DH accelerometer, MCP73831 charger, USB-C, and Li-Po battery. Verify component variants, battery protection, pin mappings, and firmware compatibility against the actual design files before building.

## License
Add the license you intend to use for the hardware and firmware before presenting the project as formally open source.
