**Requirements:**
- Have **unlocked bootloader**
- Have **drivers installed** (adb and fastboot)
- Have your **phone charged**

**Advices:**
- Don't forget to backup all your important data (phone will be formatted during the installation)
- **It is Highly recommended to flash [stock rom](https://drive.google.com/file/d/1jNbrxnC9LbaQbsv2zJaP2yGd_9vKvMVU/view?usp=sharing) before flashing LucasOS to avoid any problem, especially if you are coming from an AOSP**

**Installation: (via Fastboot or via TWRP)**


**Fastboot Method (Windows)**
1. On your Computer, download [LucasOS](link) and extract the zip
2. On your Phone, hold `power button` and `volume down` simultaneously until you see the "Fastboot screen" 
3. Connect your phone with a USB cable on your Computer
4. Inside the rom folder, already extracted, **find `windows.bat`** and **click it twice**
5. The script will run and you will see a question asking for "boot type".
  - If you want your device to be pre-rooted with **Magisk Alpha**, **type `1`** and **hit `ENTER`**
  - If you want your device to be **with no root**, **type `2`** and **hit `ENTER`**
  - If you want your device to be pre-rooted with **KernelSU**, **type `3`** and **hit `ENTER`**
6. After that you will see a question asking for "Recovery type".
  - If you want your device to be with **stock xiaomi recovery**, **type `1`** and **hit `ENTER`**
  - If you want your device to be with **TWRP**, **type `2`** and **hit `ENTER`**
7. After that you will see a question about formatting your phone or not.
  - If you are just updating from a previous version of this rom and **don't want to format**, **type `1`** and **hit `ENTER`**
  - If this is your **first time flashing this rom** or if you are **coming from another rom** you **MUST format your phone**. So **type `2`** and **hit `ENTER`**
8. The flashing process of all images will start and in a few minutes your device will conclude the installation and automatically reboot. Just wait patiently! (usually this step takes between 3-7 minutes)


---


**Fastboot Method (Linux)**
1. On your Computer, download [LucasOS](link) and extract the zip
2. On your Phone, hold `power button` and `volume down` simultaneously until you see the "Fastboot screen" 
3. Connect your phone with a USB cable on your Computer
4. Inside the rom folder, already extracted, **right click on your mouse and click on open a terminal here** and inside terminal you type **`./linux.sh`**   
5. The script will run and you will see a question asking for "boot type".
  - If you want your device to be pre-rooted with **Magisk Alpha**, **type `1`** and **hit `ENTER`**
  - If you want your device to be **with no root**, **type `2`** and **hit `ENTER`**
  - If you want your device to be pre-rooted with **KernelSU**, **type `3`** and **hit `ENTER`**
6. After that you will see a question asking for "Recovery type".
  - If you want your device to be with **stock xiaomi recovery**, **type `1`** and **hit `ENTER`**
  - If you want your device to be with **TWRP**, **type `2`** and **hit `ENTER`**
7. After that you will see a question about formatting your phone or not.
  - If you are just updating from a previous version of this rom and **don't want to format**, **type `1`** and **hit `ENTER`**
  - If this is your **first time flashing this rom** or if you are **coming from another rom** you **MUST format your phone**. So **type `2`** and **hit `ENTER`**
8. The flashing process of all images will start and in a few minutes your device will conclude the installation and automatically reboot. Just wait patiently! (usually this step takes between 3-7 minutes)


---


**TWRP Method**
1. On your phone, **download LucasOS** and **do NOT extract the zip** (TWRP will read the rom in "zip")
2. Move LucasOS to where you want to flash it (can be on Internal Storage or Pen drive...)
3. **Hold `power button` and `volume up` simultaneously** until you see the logo screen (POCO, Redmi or Mi) and then immediately **release `power button` and continue holding `volume up`** until you see the "TWRP screen"
4. If this is your first time booting into TWRP, it will probably be everything in chinese. To change it, click on the **third block on the right column**, then click on the **globe icon on the right** and select the idiom you prefer
5. In the "home" page of TWRP click on `Install` block
6. **Find the "LucasOS 1.1.zip"** and swipe to **flash it**
7. Flashing process will start and you will see "xiaomi.eu updater" message and below a text saying "Flashing firmware partitions...". Just wait until flash is complete (it usually takes between 1 or 2 minutes)
8. When the flash is complete you will see the text "script succeeded: result was [0] And if you see 3 red lines of error saying "Failed to mount "/system_root" (Invalid Argument)... don't worry, everything went fined.
9. Go back to the "home" page of TWRP
10. **Click on `Reboot`** block and **select `Recovery`**
11. Your phone will reboot to TWRP again, then on the "home" page of TWRP **select the `Wipe`** block
12. **Click on `Format Data`** and **type "yes" and cofirm**
13. Check if it formatted succesfully and **click on "reboot system"** and wait until it boots!
