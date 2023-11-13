# Installing the bootloader
Installing the MicroSD compatible bootloader is as easy as downloading the [Installer.apk](https://github.com/GarlicOS/bootloader_anbernic_rg405/releases/latest), installing it and running it on your **RG405**.
### Uninstalling the bootloader
Running the installer a second time will restore the original bootloader.

# Creating bootable MicroSD cards
To create a bootable MicroSD card:
1. Format it with an **exfat** filesystem
2. Create a **boot** folder on it
3. Copy an OS **init** script of choice into the **boot** folder (ex. [GarlicOS](https://github.com/GarlicOS/init_template/raw/main/init))
4. Extract an OS **rootfs** file of choice into the **boot** folder with [7zip](https://www.7-zip.org/download.html) (ex. [GarlicOS](https://github.com/GarlicOS/buildroot/releases/latest))

# Booting bootable MicroSD cards
To boot a bootable MicroSD card:
1. Make sure your device is powered off and **not plugged in**
2. Hold down the **power button**
3. 1.5 seconds into holding the power button, hold down the **home/back button** as well (you are now holding down two buttons)
4. Let go of both buttons once the **Anbernic logo** is visible on screen
