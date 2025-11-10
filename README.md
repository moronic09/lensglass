# lensglass
# LensGlass Privacy System

**Author:** Darshan Solbannavar  
**Date:** 10-11-2025  

## Description
LensGlass is a privacy protection system that allows only the wearer of special smart glasses to see a device's screen. It includes a full-screen privacy blackout controlled via software, with optional lens ON/OFF detection.  

## Features
- Full-screen blackout
- Lens ON/OFF simulation
- Adjustable opacity
- Safe exit (Q/Esc)
- Settings saved automatically
- Future-ready for smart lens integration

## Hardware Overview
- Privacy Lens (OLED / Polarization layer)
- Bluetooth Low Energy (BLE) module
- Microcontroller (ESP32 or Arduino Nano 33 BLE)
- Proximity sensor (detects if glasses are worn)
- Rechargeable battery

## Software Flow
1. User enables privacy mode in app
2. Screen goes black (overlay)
3. Lens ON → wearer sees the screen clearly
4. Lens OFF → full-screen blackout continues
5. User can exit using Q or Esc

## Files Included
- `privacy_app.py` — Python app prototype  
- `diagrams/` — block diagrams (optional)  
- `demo.mp4` — prototype demo video (optional)

---

This repository is a **defensive publication**. Public disclosure is intended to prevent others from patenting the same concept.

