<div align="center">

  [![](https://dlcdnimgs.asus.com/websites/global/products/yxnnaa6rkdb25veg/v6/features/images/large/1x/animation/s1/phone_right_theme.png)](#)
  [![ASUS ROG PHONE II](https://dlcdnimgs.asus.com/websites/global/products/yxnnaa6rkdb25veg/v6/features/images/large/1x/icon/s1/kv_logo.png)](#)

  <p align="center">
    ROG Phone II is the next step in the evolution of mobile gaming. It gives you the power to win, with the world’s fastest Qualcomm® Snapdragon™ 855 Plus, 12GB RAM, a monster 6000mAh battery and the unrivaled GameCool II vapor-chamber cooling system for non-stop, full-speed performance. The ultrafast 120Hz/1ms AMOLED 10-bit HDR screen has world-beating Delta-E &lt; 1 color accuracy and unrivaled touch latency for the gaming edge, while the iconic side-charging design gives you total control with uprated AirTrigger II technology, Dual Surrounding Vibration technology, dual front-facing speakers, a 3.5mm audio jack and the new quad mics with noise-cancellation. Brand-new optional accessories include the TwinView Dock II and ROG Kunai Gamepad. Mobile gaming has never been so epic!
  </p>

</div>

### Device Specifications

Feature     	      | Specification
:------------------:|:-------------------------
Manufacturer        | ASUS
Model               | ROG Phone II
Codename            | I001D
CPU                 | 2.96GHz Qualcomm® Snapdragon™ 855 Plus Mobile Platform with 7nm, 64-bit Octa-core Processor
GPU                 | Qualcomm® Adreno™ 640
Memory              | Up to LPDDR4X 12GB RAM
Operating System    | Android™ Pie™ with new ROG UI
Battery             | 6000mAh high capacity battery, supports Quick Charge 4.0 and PD Charging
Power Adapter       | Output: +5.0-10.0V 3.0A, supports up to 30.0W QC4.0 / PD3.0 / Direct Charge adapter
Finish / Color      | Matte Black (Ultimate Edition), Black Glare (Elite Edition), Black Glare (Strix Edition)
Display             | 6.59-inch 19.5:9 (2340 by 1080) 120Hz/1ms AMOLED 10-bit HDR display
.                   | 600nits outdoor readable brightness
.                   | Delta E < 1
.                   | 111.8% DCI-P3, 107.4% NTSC, 151.7% sRGB color gamut display
.                   | 500,000:1 contrast ratio AMOLED display with Corning® Gorilla® 6 Glass
.                   | Bluelight filter for eye care
.                   | Supports Always On
.                   | Capacitive touch panel with 10 points multi-touch (supports glove touch)
Capacity            | Internal storage
.                   | Up to UFS 3.0 1TB
Main Rear Camera    | Sony flagship IMX586 48MP image sensor - 1/2.0” large sensor size, 0.8 µm pixel size
.                   | Quad Bayer technology - 12MP, 1.6 µm large effective pixel size
.                   | F1.79 aperture, 26mm equivalent focal length in 35mm film camera
.                   | 6p lens, 79° field of view
.                   | 2x1 On-chip-lens phase detection autofocus
.                   | LED flash
Rear camera modes   | Auto, Portrait, Panorama, Night, Pro (RAW file support / up to 32 seconds long exposure)
.                   | AI Scene Detection in 16 types: food, sky, green field, plant, ocean, sunset, snow, flower, stage, dog, cat, people, text, tripod, QR code, night view
.                   | 8 various filters
Second Rear Camera  | 13MP, 125° ultrawide camera
.                   | 200% wider view for more friends and scenery in the frame
.                   | Real-time distortion correction
.                   | 11mm equivalent focal length in 35mm film camera
Front Camera        | 24MP, F2.0 aperture, 27mm equivalent focal length in 35mm film camera, 77.9° field of view
Front camera modes  | Auto, Portrait, 8 various filters
Video Recording     | 4K UHD (3840 by 2160) video at 30 / 60 fps for main rear camera, at 30 fps for second rear camera
.                   | 1080p FHD video recording at 30 / 60 fps
.                   | 720p HD video recording at 30 fps
.                   | 3-axis electronic image stabilization for rear cameras
.                   | Time Lapse (4K UHD video)
.                   | Slow Motion video (1080p at 240 / 120 fps; 720p at 480 fps)
.                   | Take still photo while recording video
Audio Output        | Hi-Res audio 192kHz/24-bit standard that is 4 times better than CD quality
.                   | DTS:X Ultra 7.1 virtual surround sound for headphone support
.                   | AudioWizard with listening profile
Speaker             | Dual front-facing speakers with DTS:X Ultra
.                   | Stereo speaker with dual NXP TFA9874 smart amplifier for louder, deeper and less distorted sound effect
Microphone          | Quad microphones with ASUS Noise Reduction Technology
FM Receiver         | FM radio
Wireless Technology | Integrated 802.11a/b/g/n/ac (2x2 MIMO)
.                   | WLAN 802.11ad 60GHz
.                   | Bluetooth V 5.0 (BR/EDR+LE), supports Qualcomm® aptX Adaptive
.                   | Wi-Fi direct
.                   | NFC
Navigation          | GPS (L1+L5), GLO, BDS, GAL (E1+E5a), QZSS (L1+L5)
SIM Cards           | Dual slots: Dual 4G SIM standby
Network Standard    | GSM/GPRS/EDGE; WCDMA/HSPA+/DC-HSPA+; FDD-LTE; TD-LTE
Data rate           | LTE Cat18 UL up to 211Mbps / Cat20 DL up to 2Gbps
.                   | DC-HSPA+: UL 5.76Mbps / DL 42Mbps
.                   | LTE 6CA UL up to 211Mbps / DL up to 2Gbps
.                   | 4x4 MIMO and CA w/ 4x4 MIMO support (Ultimate and Elite Edition only)
Sensors             | In-display fingerprint, Face recognition, Accelerator, E-Compass, Gyroscope, Proximity sensor, Hall sensor, Ambient light sensor, Ultrasonic sensors for AirTrigger II and grip press, Dual vibrators.
Interface           | Customized connector (48 Pin) attached to ROG Phone
I/O port            | USB 3.1 Gen1 Type-C
.                   | 3.5mm audio jack
LED                 | Aura RGB lighting support

## Compilation Guide

To build PitchBlackRecoveryProject, Use this command:
```bash
repo init -q -u https://github.com/PitchBlackRecoveryProject/manifest_pb.git -b android-9.0 --depth 1
repo sync -c -q --force-sync --no-clone-bundle --no-tags -j$(nproc --all)
```
Then clone this Device Tree into place
```bash
git clone https://github.com/PitchBlackRecoveryProject/android_device_asus_I001D.git -b android-9.0 device/asus/I001D
```

Or before `repo sync`, you can add this project to .repo/local_manifests/roomservice.xml (If you don't have it, you can add them to .repo/manifest.xml): 
```xml
<project name="PitchBlackRecoveryProject/android_device_asus_I001D" path="device/asus/I001D" remote="github" revision="android-9.0" />
```
Then give the upper `repo sync` command which will now clone your device tree automatically.

Finally execute these:

```bash
. build/envsetup.sh
export ALLOW_MISSING_DEPENDENCIES=true
# If first build fails and shows GCC errors, run this command before lunch
# export LC_ALL=C
lunch omni_I001D-eng
make -j$(nproc --all) recoveryimage
```
It will make PitchBlack*.zip as-we-as recovery.img inside out/target/product/I001D/

If flashed only _recovery.img_ using `fastboot`, make sure to flash the upper Zip file again to get full features of it.
