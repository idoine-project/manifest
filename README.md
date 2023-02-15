Idoine
===========

### Sync ###

```bash

# Initialize local repository
repo init -u https://github.com/idoine-project/manifest -b tiramisu

# Sync
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```

### Build ###

```bash

# Set up environment
$ . build/envsetup.sh

# Choose a target
$ lunch idoine_$device-userdebug

# Build the code
$ mka idoine
```

# Credits:

 * [**Evolution-x**](https://github.com/Evolution-X)
 * [**LineageOS**](https://github.com/LineageOS)
 * [**ParanoidAndroid**](https://github.com/AOSPA)
 * [**PixelDust**](https://github.com/PixelDust-Twelve)
 * [**ProtonAOSP**](https://github.com/ProtonAOSP)
 * [**BlissROMs**](https://github.com/BlissRoms)
 * [**Syberia Project**](https://github.com/syberia-project)
 * [**crDroid**](https://github.com/crdroidandroid)
 * [**Octavi-OS**](https://github.com/Octavi-OS)
 * [**hentaiOS**](https://github.com/hentaiOS)
 * [**POSP**](https://github.com/PotatoProject)
 * [**StatiXOS**](https://github.com/StatiXOS)
 * [**ArrowOS**](https://github.com/ArrowOS)
 * [**PixelExperience**](https://github.com/PixelExperience)
 * [**AICP**](https://github.com/AICP)
 * [**ShapeShiftOS**](https://github.com/ShapeShiftOS)
 * [**YAAP**](https://github.com/yaap)
 * [**PixelExtended**](https://github.com/PixelExtended)
 * [**AospExtended**](https://github.com/AospExtended)
 * [**Nitrogen OS**](https://github.com/nitrogen-project)
 * [**PixysOS**](https://github.com/PixysOS)
 * [**Havoc-OS**](https://github.com/Havoc-OS)
 * [**Xtended**](https://github.com/Project-Xtended)
 * [**ColtOS**](https://github.com/Colt-Enigma)
 * [**exTHmUI**](https://github.com/exTHmUI)

* And tons of other ROMs not mentioned above
