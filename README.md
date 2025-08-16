# Flashing instructions For Voltage OS

# Flashing VoltageOS Recovery:

# Reboot to fastboot - Hold Volume down button + Power button until fastboot logo appears 

* Download latest VoltageOS recovery from [Telegram](https://t.me/nebula_violet/2)

* Connect your phone to PC and write the following command in your PC's command prompt

```
fastboot flash recovery recovery.img
```

# Reboot to recovery - Hold Volume up button + Power button until recovery appears

Flashing Firmware
------------

[Firmware](https://xmfirmwareupdater.com/firmware/violet/) - Download your latest regional firmware.

```
1. Through adb sideload
2. Through SD Card / OTG
```

### 1st method

* Select Apply Update

* Select Apply Update from ADB

* Connect your phone to PC

* Type this in your PC's cmd

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

- Type this in your PC's cmd

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

- Type this in your PC's cmd

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

- Type this in your PC's cmd

```
adb sideload rom.zip
```

- Click yes on the prompt that comes after sideloading rom.zip

- Select Apply Update

- Select Apply Update from ADB

- Type this in your PC's cmd

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

- Type this in your PC's cmd

```
adb sideload rom.zip
```

- Click yes on the prompt that comes after sideloading rom.zip

- Click Reboot System Now

### Only if you flashed GApps in clean installation and your GApps weren’t backed up

- Don't Reboot To System

- Select Apply Update

- Select Apply Update from ADB

- Type this in your PC's cmd

```
adb sideload gapps.zip
```

- Click Reboot System Now

### 2nd method - Through OTA

- Tap on Settings -> System -> System updates and download latest build

- Click on Reboot in OTA updater

# For any queries ask in [SUPPORT GROUP](https://t.me/frosty_builds)
