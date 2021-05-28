# dotOS Changelog OFFICIAL for Surya/Karna
# Version 5.1 (28-05-2021)

# User build instructions (caution)
- Because of the new dotOS Security Policy, all offical devices are now mandatory user build (an emforcing build with a higher level of security). So because of that I will make two important points:
- Do not do dirty flash or do not update via OTA in this version (the old version is userdebug, so this will cause bootloop, do clean flash only in this version)
- the Kcal Controller will only work if you switch to permissive through the selinux controller.

# General Changes
- Add real device model: Poco X3 NFC/Poco X3 (this old name is complicated and not good to see)
- Add option min/max refresh rate in display settings (Add dinamic refresh rate too)
- Audio: Import Dirac Blobs From Lavender
- Enable HWUI_COMPILE_FOR_PERF
- Enable Face Unlock
- Fix Broken AOD
- Fix Ok Google
- Introduce IORap
- Introduce PocoParts
- Overlay: Set default refresh rate to 120Hz 
- Overlay: Default to full gesture navigation
- Set blur by default (surya/karna can handle it without problems)
- Update Fingerprint to Sunfish 210505.002/7246365

# Parts
* ( all of these changes were made to suit the dotOS UI and organize all those extra features in one place)
- Add a button to turn off the thermal profile
- Move Dirac to Poco parts
- Move Doze to PocoParts
- Move Thermal Profiles to PocoParts
- Move Clear Speaker to Poco Parts
- Drop Refresh Rate

# Poco Parts
* Features:
- Display Color Calibration(KCAL)
- FPS Info
- Selinux control

* most recent changes:
- Add pt-rBR translation
- Add header animation
- Add animation for PocoDoze e Clear spekaer
- Add Poco Parts Qs Tile
- Add Dirac Launcher
- Update FPSInfo icon
- Doze: Update XiaomiDoze from arrow sdm660 tree

# Credits
- Special thanks to @badadam69 Continuous testing for the improvement of the tree.
- Thanks to all users of the Poca Rom Brazil group for testing.
