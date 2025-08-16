# Flashing instructions For Voltage OS

# Flashing Recovery and DTBO:

* [boot & vendor_boot](https://sourceforge.net/projects/voltage-os/files/veux/recovery/).
* [dtbo](https://t.me/frosty_builds/50818) - Only for Android 15 + builds.
* [dtbo_a14](https://t.me/frosty_builds/51604) - Only for Android 14 builds.

## Use a14 dtbo for older, i.e. Android 14 builds, namely VoltageOS v3.7-EOL.

# Reboot to fastboot - Hold Volume down button + Power button until fastboot logo appears 

## Connect your phone to pc and write these commands in your pc's cmd -

```
fastboot flash boot_a voltage-5.0-veux-20250819-0557-OFFICIAL-boot.img
```

```
fastboot flash boot_b voltage-5.0-veux-20250819-0557-OFFICIAL-boot.img
```

```
fastboot flash vendor_boot voltage-5.0-veux-20250819-0557-OFFICIAL-vendor_boot.img
```

```
fastboot flash dtbo dtbo.img
```

# Reboot to recovery - Hold Volume up button + Power button until recovery appears

Flashing Firmware
------------

[Firmware](https://t.me/sweaterinsack/3/5) - Download your latest regional firmware.

```
1. Through adb sideload
2. Through SD Card / OTG
```

### 1st method

* Select Apply Update

* Select Apply Update from ADB

* Connect your phone to PC

* Type this in your pc's cmd

```
adb sideload firmware.zip
```

### 2nd method

* Select Apply Update

* Select Choose from sdcard

* Select your firmware.zip

Flashing Rom
------------

```
1. Clean Flash (Vanilla)
2. Clean Flash (Sandbox Gapps)
3. Clean Flash (Normal Gapps)
```

### 1st method - Clean Flash (Vanilla)

- Select Apply Update

- Select Apply Update from ADB

- Connect your phone to PC

- Type this in your pc's cmd

```
adb sideload rom.zip
```

- Click yes on the prompt that comes after sideloading rom.zip

- Click Factory Reset 

- Click Format Data/Factory Reset

- Click Reboot System Now

### 2nd method - Clean Flash (Sandbox Gapps)

- Select Apply Update

- Select Apply Update from ADB

- Connect your phone to PC

- Type this in your pc's cmd

```
adb sideload rom.zip
```

- Click yes on the prompt that comes after sideloading rom.zip

- Click Factory Reset 

- Click Format Data/Factory Reset

- Click Reboot System Now

- Download [THIS](https://github.com/GrapheneOS/AppStore/releases) app

- Open the app

<p align="left"> <img src="https://raw.githubusercontent.com/Karan-Frost/images/refs/heads/main/IMG_20241209_143433_631.jpg"> </p>

- Download this app

- Enjoy rom with Sandbox Gapps

- For more information on Sandbox Gapps - [HERE](https://grapheneos.org/usage#sandboxed-google-play)

- For some fixes - [HERE](https://t.me/voltageos/122664)

### 3rd method - Clean Flash (Normal Gapps)

- Select Apply Update

- Select Apply Update from ADB

- Connect your phone to PC

- Type this in your pc's cmd

```
adb sideload rom.zip
```

- Click yes on the prompt that comes after sideloading rom.zip

- Select Apply Update

- Select Apply Update from ADB

- Type this in your pc's cmd

```
adb sideload gapps.zip
```

- Click Advanced

- Click Reboot to Recovery 

- Click Factory Reset 

- Click Format Data/Factory Reset

- Click Reboot System Now

Updating ROM - 
------------

```
1. Dirty Flash
2. Through OTA
```

### 1st method - Dirty Flash

- Select Apply Update

- Select Apply Update from ADB

- Connect your phone to PC

- Type this in your pc's cmd

```
adb sideload rom.zip
```

- Click yes on the prompt that comes after sideloading rom.zip

- Click Reboot System Now

### Only if you flashed gapps in clean installation

- Don't Reboot To System

- Select Apply Update

- Select Apply Update from ADB

- Type this in your pc's cmd

```
adb sideload gapps.zip
```

- Click Reboot System Now

### 2nd method - Through OTA

- Tap on Settings -> System -> System updates and download latest build

- Click on Reboot in OTA updater

# Flashing different kernel:

## If you want to flash different kernel in VoltageOS, you can follow these steps (for Android 16):

- Download vendor_boot.img from [HERE](https://sourceforge.net/projects/voltage-os-veux-peux/files/kernel-flash/voltage-5.0-kernel-flash-vendor_boot.img/download)

- Reboot to fastboot - Hold Volume down button + Power button until fastboot logo appears

- Connect your phone to PC

- Type this in your pc's cmd

```
fastboot flash vendor_boot voltage-5.0-kernel-flash-vendor_boot.img
```

- Reboot to recovery - Hold Volume up button + Power button until recovery appears

- Flash your desired kernel

- Click Reboot System Now

# For any queries ask in [SUPPORT GROUP](https://t.me/frosty_builds)
