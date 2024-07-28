# Android device tree for samsung SM-S7110 (r11q)

# Clone
    git clone https://github.com/MrFluffyOven/android_device_samsung_r11q.git -b twrp-12.1 device/samsung/r11q

# Build
    ALLOW_MISSING_DEPENDENCIES=true; . build/envsetup.sh; lunch twrp_r11q-eng; mka recoveryimage
