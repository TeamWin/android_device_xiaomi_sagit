# android_device_xiaomi_sagit
Tree for building TWRP for Xiaomi MI 6

## To compile

export ALLOW_MISSING_DEPENDENCIES=true

. build/envsetup.sh && lunch omni_sagit-eng

mka adbd recoveryimage

## Device specifications

Basic   | Spec Sheet
-------:|:-------------------------
CPU     | Octa-core (4x2.45 GHz Kryo & 4x1.9 GHz Kryo)
Chipset | Qualcomm MSM8998 Snapdragon 835
GPU     | Adreno 540
Memory  | 6 GB RAM
Shipped Android Version | 7.1.1
Storage | 64/128 GB
Battery | Li-Po 3350 mAh battery
Display | 1080 x 1920 pixels, 5.15 inches (~428 ppi pixel density)
Rear Camera  | Dual 12 MP (27mm, f/1.8, OIS 4-axis & 52mm, f/2.6), phase detection autofocus, dual-LED (dual tone) flash


## Device picture

![Xiaomi Mi 6](https://xiaomi-mi.com/uploads/CatalogueImage/xiaomi-mi-6-exclusive-edition-6gb128gb-dual-sim-ceramic-black-01_15554_1492602917.jpg "Xiaomi Mi 6 in black")
