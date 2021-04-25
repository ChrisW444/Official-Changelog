# Octavi-OS Changelog Official for lavender
# Version 2.3 | Kernel 4.4 (25-04-2021)

# Changes
- Light HAL now gets loaded earlier at bootup to prevent any potential issues
- Optimized shutdown time
- Removed all-caps text for buttons
- Set custom RGB values for tianma panel.( Try to avoid a screen retention during the initial setup, it worked well during the tests)
- Set fast charging indicator threshold to 10.8W
- Switched to sdfat 2.4.5 driver for exfat
- Switch to predator EAS
- Updated dex2oat configs for faster 1st boot 
- Updated vibration pattern from Pixel 2
- Update fingerprint to Redfin - RQ2A.210405.005 (cts passed without magisk)

# Blobs
- Imported AdaptLaunch and some perf blobs
- Updated blobs from LA.UM.8.2.r1-07500-sdm660.0
- update vulkan and graphics blobs from taimen (OpenGL v490 and Vulkan v1.128)

# Apps
- Add OnePlus Screen Record
- 
# Fix
- Fix all bugs

# Dirac
- Import more blobs Dirac from miui 12.5
- Revert "Dirac: Force enable to default" (That was breaking the headphone and preset selection)
- 
# XiaomiParts
- Add privapp-permissions
- Add Retention fix preset in KCAL 
- Fix SmartCharging

# Credits
- Thanks all users in my group for tests. especially @Ryuzakl026 who helped me a lot with logs and a lot of tests in a row !
- Thanks @PredatorX91 for kernel!

