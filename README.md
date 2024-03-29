# Project Flexo

### Create a directory for the source files
* You can name this directory however you want, just remember to replace 
* WORKSPACE with your directory for the rest of this guide.
* This can be located anywhere (as long as the fs is case-sensitive)

```bash 
mkdir Flexo 
cd Flexo
```

### Install Repo in the created directory

>> [Hint: This might take a long time]

```bash
repo init -u https://github.com/Project-Flexo/manifest -b 13.0
```

>> [Hint: Want to save some space ? Then use this]

```bash
repo init --depth=1 -u https://github.com/Project-Flexo/manifest -b 13.0
```

### Download the source
```bash 
repo sync --force-sync
```

### Build
```bash
# Set up environment
. build/envsetup.sh
# Choose a target
lunch aosp_$device-userdebug
# Build the code
mka bacon -jX
```

### Credits
 * [**AOSP**](https://android.googlesource.com) 
 * [**LineageOS**](https://github.com/LineageOS) 
 * [**PixelExperience**](https://github.com/PixelExperience) 
 * [**ProtonAOSP**](https://github.com/ProtonAOSP)
 * [**ArrowOS**](https://github.com/ArrowOS)
 * [**ProjectBlaze**](https://github.com/ProjectBlaze)
 * [**PixelExtend**](https://github.com/PixelExtended)
 * [**RadientOS**](https://github.com/ProjectRadiant)
 * [**CipherOS**](https://github.com/CipherOS)

