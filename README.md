# SkyHawk Recovery Project for the Samsung Galaxy J5 2017

### How to build ###

```bash
# Create dirs
$ mkdir shrp ; cd shrp

# Init repo
$ repo init --depth=1 -u git://github.com/SKYHAWK-Recovery-Project/platform_manifest_twrp_omni.git -b android-9.0

# Clone my local repo
$ git clone https://code.binbash.rocks:8443/MVA-VoLTE/android_device_samsung_j5y17lte.git -b android-9.0_shrp device/samsung/j5y17lte

# Sync
$ repo sync --no-repo-verify -c --force-sync --no-clone-bundle --no-tags --optimized-fetch --prune -j`nproc`

# Build
$ mka recoveryimage
```
## Credits
2019-2020 Astrako

## Contact
Telegram support group: https://t.me/sfX_Android
