# Octavi-OS Changelog Official for lavender
# Version 2.1 | Kernel 4.4 (07-03-2021)

# Changes
- Switch to enforcing
- Switch Offline Charger to MIUI
- Update Nexus Kernel to V2 4.4.258
- Update fingerprint to Redfin - RQ2A.210305.006 (cts passed without magisk)
- Update wfd blobs from LA.UM.9.6.2.r1-03300-89xx.0
- Update GPS blos from LA.UM.9.6.2.r1-03600-89xx.0
- Update some blobs from LA.UM.9.6.2.r1-03600-89xx.0
- Update Telephony overlays from LA.UM.9.2.1.r1-05500-sdm660.0
- Update vendor SPL from LA.UM.8.2.r1-07400-sdm660.0
- Add wfd dependency blobs From LA.UM.9.6.2.r1-03300-89xx.0
- Add CustomDoze Octavi-OS (Ambient Display)
- Add support for 240FPS 1/8 slow-motion
- Add flipendo sepolicy rules
- Configure SQLite to operate in MEMORY mode
- Define ro.media.recorder-max-base-layer-fps
- Switch Channels for Camera Recording

# Apps
- Add Gboard default in Vanilla Build
- Add Google Go files manager in Gapps builds
- Add Vanced Manager 
- Set Solid Explorer default file manager
- Update GCamGO to v1.11

# Fix
- Fix audio recording in video mode
- Fix mic issues in apps like WhatsApp
- Fix headsup app icon offset.
- Fix Google Assistent

# Dirac
- Force enable on boot
- Update icons to preset

# XiaomiParts
- Update icons to CPU & GPU Boost
- Add Punch Saturated Colors preset on KCal by default
- Drop Spectrum (was negatively impacting performance and battery) 

# Credits
- Thanks @Golpiista, @pilot1964691, @OOSFAN, @Lavender101 fot tests!
- Thanks @NotZeetaa for kernel!


# Version 2.0 (22-02-2001)

Changes
  - Update fingerprint to Redfin - RQ1A.210205.004 (cts passed without magisk)
  - Import Pixel Power Hal (switched to eas)
  - Use NexusKernel EAS V1
  - Set google AutofillService default
  - Disable foreground prefer_idle & reduce TA boost
  - import Hotword Enrollment blobs
  - Removed all apps prebuilt
  - Drop non-functional soundtrigger
  - Fix: fix lag in the system UI
  - Fix: fix hotspost didn't work for some people

Dirac
   - Dirac/Mi Sound separate to XiaomiParts (moved for Settings)
   - Add bass booster preset for MiSound (much stronger bass for those who use headphones)
   - Add Blobs Dirac (adde some libs on vendor)
   - Fix: Dirac: Enable by default (dirac didn't work well at times)
   - Import MIUI dirac translations

XiaomiParts
   - Adding XiaomiParts into the whitelist ( Adding XiaomiParts into whitelist to avoid it being killed by
     doze. Also granting necessary permission to function properly.Required for Headphone & Mic Gain as it currently get killed)
   - Improvement Spectrum (cpu and gpu values adjusted for lavender)
   - Specrtum adapted for EAS
   - Update Icons
   - FPS Info: redesign FPS Info (now it's better than ever hehe)
   - Fix: Remove intent for BootReceiver
   - Fix: Fix icon does not appear in white theme
   - Fix: Removed all garbage that was not working

Credits:
   - Thanks @hazama25 for dt base!
   - Thanks @NotZeetaa for kernel!
   - Thanks @inferno964 for tests!
