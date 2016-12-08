The Android Open Source Project Nougat 7.1.1_r4
===========

To initialize your local repository using the AOSP trees, use a command like this:
````bash
repo init -u git://github.com/nbehary/manifest.git -b n-mr1
```
Then to sync up:
````bash
repo sync
```
Finally to build:
````bash
. build/envsetup.sh
lunch                 -> (device number)
make -j8 otapackage
```
