# Flashing instructions For Voltage OS

# Flashing Recovery:

* vendor_boot.img - From ROM's post.

# Reboot to fastboot - Hold Volume down button + Power button until fastboot logo appears 

## Connect your phone to pc and write these commands in your pc's cmd -

```
fastboot flash vendor_boot_ab vendor_boot.img
```

# Reboot to recovery - Hold Volume up button + Power button until recovery appears

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

# For any queries ask in [SUPPORT GROUP](https://t.me/frosty_builds)
