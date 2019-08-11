![Evolution X](https://github.com/Evolution-X/platform_manifest/raw/pie/BannerLight.png)

# Evolution X #

[![Download Evolution X](https://img.shields.io/sourceforge/dt/evolution-x.svg)](https://sourceforge.net/projects/evolution-x/files/latest/download)

### Sync ###

```bash

# Initialize local repository
repo init -u https://github.com/Evolution-X/platform_manifest -b pie-aosp-wfd

# Sync
repo sync -c -jx --force-sync --no-clone-bundle --no-tags
```

### Build ###

```bash

# Set up environment
$ . build/envsetup.sh

# Choose a target
$ lunch aosp_$device-userdebug

# Build the code
$ mka bacon -jX
```
