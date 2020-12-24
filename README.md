# TWRP Tree for Teos [Testing]
## Note by Tenshi
```bash
Don't ask me why I made this, basically this TWRP tree is very easy to make and I want make it for someone who want make their own TWRP
````

# Getting started
```bash
# Make folder
$ mkdir teos_twrp ; cd teos_twrp

# Clone TWRP tree
$ repo init -u https://github.com/minimal-manifest-twrp/platform_manifest_twrp_omni.git -b twrp-7.1

# Clone this repo
$ git clone https://github.com/windowzytch/recovery_device_teos -b msin device/vestel/teos

# Sync
$ repo sync

# Make some stuffs and build it
$ . build/envsetup.sh
$ lunch omni_teos-eng
$ make recoveryimage
```

# Credit
2020 @Tenshi2112
