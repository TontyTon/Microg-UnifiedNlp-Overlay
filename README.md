# Microg-UnifiedNlp-Overlay
Use this Overlay to use Microg UnifiedNlp with Gapps.

### Installation
1. Download _UnifiedNlp.apk_ from https://github.com/microg/UnifiedNlp/releases
2. Create a new folder named '_UnifiedNlp_' in /system/priv-app/ and set Permissions/Security to 0755 (rwx r-x r-x).
3. Place the _UnifiedNlp.apk_ in /system/priv-app/UnifiedNlp and set Permissions/Security to 0644 (rw- r-- r--)
4. Place the _org.microg.nlp.xml_ file in /system/etc/permissions/ and set Permissions/Security to 0644 (rw- r-- r--).
5. Place _UnifiedNlpOverlay.apk_ in /vendor/overlay and set Permissions/Security to 0644 (rw- r-- r--).
6. Reboot to system.

### Status
Android 9 - Not Tested

Android 10 - Working

Android 11 - Not Tested
