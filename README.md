pyramidOS
===========

### Getting started ###
---------------

To get started with pyramidOS, you'll need to get familiar with [Source Control Tools](https://source.android.com/setup/develop).

To initialize your local repository using trees which have been adapted to pyramidOS, use a command like this:
```
repo init -u https://github.com/pyramidOS/manifest -b 12.1
```
Then to sync up:
```
repo sync
```

### Build ###
---------------

```bash
# Set up environment
$ . build/envsetup.sh
# Choose a target
$ lunch pyramid_<codename>-buildtype
# Build the code
$ make pyramid -jX
```

### Credits ###
---------------

Big thanks to:
#### [• Pixel Experience](https://github.com/PixelExperience)
#### [• ArrowOS](https://github.com/ArrowOS)
#### [• LineageOS](https://github.com/LineageOS)
#### [• The Android Open Source Project (ofc)](https://source.android.com/)
#### [• FusionOS](https://github.com/FusionOS)
#### [• crDroid](https://github.com/crdroidandroid)
#### [• riceDroid](https://github.com/ricedroid)
#### [• ElytraOS](https://github.com/elytraos)
