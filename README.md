CyanogenMod/LineageOS 13 device configuration for Nokia X2(Ara).

How to build:
-------------

Initialize repo:

    repo init -u git://github.com/LineageOS/android.git -b cm-13.0
    curl --create-dirs -L -o .repo/local_manifests/manifest_nokia_ara.xml -O -L https://raw.githubusercontent.com/legaCyMod/android_local_manifest/cm-13.0/manifest_nokia_ara.xml
    repo sync

Compile:

    . build/envsetup.sh
    brunch ara
