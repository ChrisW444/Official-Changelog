# Octavi-OS Changelog Official for lavender
# Version 2.0 (21-02-2001)

Changes
  - Update fingerprint to Redfin - RQ1A.210205.004 (cts passed without magisk)
  - Import Pixel Power Hal (switched to eas)
  - Use NexusKernel EAS V1
  - Set google AutofillService default
  - Disable foreground prefer_idle & reduce TA boost
  - import Hotword Enrollment blobs
  - Removed all apps prebuilt
  - Drop non-functional soundtrigger

Dirac
   - Dirac/Mi Sound separate to XiaomiParts (moved for Settings)
   - Add bass booster preset for MiSound (much stronger bass for those who use headphones)
   - Add Blobs Dirac (adde some libs on vendor)
   - Fix: Dirac: Enable by default (dirac didn't work well at times)

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
