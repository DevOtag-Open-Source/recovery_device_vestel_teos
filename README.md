# TWPR Tree for Teos [Testing]
```bash
Don't ask me why I made this, basically this TWRP tree is very easy to make and I want make it for someone who want make their own TWRP
````

# Getting started
```bash
# Make folder
$ mkdir teos_twrp ; cd teos_twrp

# Clone TWRP tree
$ repo init -u git://github.com/minimal-manifest-twrp/platform_manifest_twrp_omni.git -b twrp-7.1

# Clone my repo
$ git clone https://github.com/TeGaX/android_device_teos device/vestel/teos

# Sync
$ repo sync

# Make some stuffs and build it
$ . build/envsetup.sh
$ lunch omni_teos-eng
$ make recoveryimage
```

# Credit
2020 @Tenshi2112
