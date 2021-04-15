# dotOS Changelog OFFICIAL for lavender
# Version 5.0.1 | Kernel 4.4 (15-04-2021)

General:
- Adjusted RSSI thresholds for switching between WiFi networks
- Allocate heap values dynamicall
- Add Audio 24bits
- Add Gboard em builds Vanilla
- Add OnePlus
- Light HAL now gets loaded earlier at bootup to prevent any potential issues
- Optimized shutdown time
- Removed all-caps text for buttons
- Set custom RGB values for tianma panel.( Try to avoid a screen retention during the initial setup, it worked well during the tests)
- Set fast charging indicator threshold to 10.8W
- Switched to sdfat 2.4.5 driver for exfat
- Switch to predator EAS
- Updated dex2oat configs for faster 1st boot 
- Updated vibration pattern from Pixel 2
- Update fingerprint to Redfin - RQ2A.210405.005

# Blobs
- Imported AdaptLaunch and some perf blobs
- Updated blobs from LA.UM.8.2.r1-07500-sdm660.0
- update vulkan and graphics blobs from taimen (OpenGL v490 and Vulkan v1.128)

# Dirac
- Import more blobs Dirac from miui 12.5
- Revert "Dirac: Force enable to default" (That was breaking the headphone and preset selection)

# XiaomiParts
- Fix SmartCharging


# Notes:
- WFD e Netflix L1 Working
