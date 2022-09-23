# Woomy3DS
## How Do I Install Woomy3DS
### 1.16.0
#### Step 1: *Insert your SD card into your computer and then navigate to the Nintendo 3DS folder on your SD card and copy the 32 character long name of the folder you see inside Nintendo 3DS but Do not go inside any more folders and If you see multiple 32 character long folders, [follow these instructions](https://3ds.hacks.guide/troubleshooting#multiple-long-folder-names-in-nintendo-3ds-folder) else dont You can ignore the private folder if you have it and then paste your 32 character long folder name into a document you can reference later and power on your device Note: "Your SD card does not need to be inserted at this point" and then Go to your Friend List (the [orange Face Icon](https://3ds.hacks.guide/images/friend-list-icon.png) in the top row of your HOME Menu) Note If Have Issues: "If you receive an error and are kicked out of the menu, you either must create a new Mii or your device cannot connect to Nintendo’s servers (due to a ban or connection issues)and then Find your Mii profile, then find the “Friend Code” field on the top screen and your done for step 1 now step 2*
#### Step 2: *Open [this website](https://seedminer.hacks.guide/) on your computer and then enter your device’s Friend Code (with no spaces or dashes) into the “Your friend code” field and paste your device’s 32 character long(that you should have copied) folder name into the “Your ID0” field Note: "Do not attempt to enter the ID0 by hand. Ensure the ID0 is entered correctly by copying and pasting it from where you saved it in the previous section" and then Select “Go" and then Use the “Register Friend” button on your device to add the bot’s friend code as given by the website Note: "This may take a bit pending on what time of day you picked to do this and how many ppl are also mining their seeds" and then once its done wait for the site to update and then it will go to step 2: Bruteforce and this is the long part it all depends on how many miners and how good their gpu is and how many ppl are mining at that time and when the process is completed, download your movable.sed file from the site make sure to keep this file as you will need it in the upcoming steps and step2 is done now on to step 3*
#### Step 3: Note before we start Taiwan consoles sadly cant follow the next steps but will be able to new one a Taiwan only hack guide but all righty thats out of the way *You will need Your movable.sed file from completing Step 1 and 2 and The latest release of [SafeB9SInstaller](https://github.com/d0k3/SafeB9SInstaller/releases/download/v0.0.7/SafeB9SInstaller-20170605-122940.zip) and The latest release of [boot9strap](https://github.com/SciresM/boot9strap/releases/download/1.4/boot9strap-1.4.zip) and [https://github.com/LinuxTheDS/Woomy3DS/releases/latest](Woomy3DS) and there will be one more but that gets made in this step so lets get started so first if your device is powered on, power off your device and then Open [unSAFE_MODE Bannerbomb3](https://3ds.nhnarwhal.com/3dstools/unsafemode.php) its not as scary as it sounds but after uploading your movable.sed file to the page it will have a green button that says Build And Download click it then wait 2 seconds then you will get this zip file named unSAFE_MODE.zip if not you prob did something wrong but after that extract the zip it should have a file named F00D43D5.bin and another named usm.bin then insert your SD card into your computer and copy boot.firm and boot.3dsx from the Woomy3DS .zip to the root of your SD card and then Note: "The root of the SD card refers to the initial directory on your SD card where you can see the Nintendo 3DS folder, but are not inside of it" and then create a folder named boot9strap on the root of your SD card and then copy boot9strap.firm and boot9strap.firm.sha from the boot9strap .zip to the that folder that you just made on your SD card and then copy SafeB9SInstaller.bin from the SafeB9SInstaller .zip to the root of your SD card and then copy usm.bin from unSAFE_MODE.zip to the root of your SD card and then navigate to Nintendo 3DS -> <ID0> -> <ID1> on your SD card Note: "The <ID0> will be the same one that you used in Step 2 and The <ID1> is a 32 character long folder inside of the <ID0>" and then create a folder named Nintendo DSiWare inside of the <ID1> if it dont exist yet if so then copy them to your PC and remove them from your SD card and then copy the F00D43D5.bin file from unSAFE_MODE.zip that we made from our moveable.sed to the Nintendo DSiWare folder and then reinsert your SD card into your device and then Ppower on your device and head to System Settings and then navigate to Data Management -> DSiWare and then click on the SD Card section and then Your device should show a menu with some text Note: "If this step causes your device to crash, [follow this troubleshooting guide](https://3ds.hacks.guide/troubleshooting#dsiware-management-menu-crashes-without-showing-usm-menu)" and then select “Inject haxx” and then your device will automatically power off while still powered off hold the following buttons: Left Shoulder + Right Shoulder + D-Pad Up + A, and while holding these buttons together, power on your device Note: "If you’re unable to get into Safe Mode after multiple attempts, one of your buttons may be failing or broken. If this is the case, you will need to follow [an alternate branch of Seedminer](https://3ds.hacks.guide/bannerbomb3). For assistance with this matter, [join Nintendo Homebrew on Discord](https://discord.gg/MWxPgEp) and ask, in English, for help." and then Press “OK” to accept the update but there is no update. This is part of the exploit and then press “I accept” to accept the terms and conditions and then The update will eventually fail, with the error code ```003-1099```. This is intended behaviour and then When asked “Would you like to configure Internet settings?”, select “Yes” and then On the following menu, navigate to ```Connection 1``` -> ```Change Settings``` -> ```Next Page (right arrow)``` -> ```Proxy Settings``` -> ```Detailed Setup```. If the exploit was successful, your device will have booted into SafeB9SInstaller and then When prompted, input the key combo given on the top screen to install boot9strap. Note: "If the top screen is blank, power off your device and re-do the update thing again" and then once it is complete, press A to reboot your device and then Your device should have rebooted into the Woomy3DS configuration menu Note: "If your device shuts down when you try to power it on, ensure that you have copied boot.firm from the Woomy3DS .zip to the root of your SD card" and then Press Start to save and reboot, At this point, your console will boot to Woomy3DS by default and to finish it off launch System Settings on your device and then Navigate to ```Data Management``` -> ```DSiWare``` and then Click on the SD Card section and same mneu will pop up and then dont press "Inject haxx!" Instead press Restore Slots and then it will reboot when its done rebooting power it off and then remove the sd card and put it in the computer then go back to the ```Nintendo 3DS``` folder and then the id0 and then go to the id1 and remove the Nintendo DSiWare folder and if you have ome other dsiware put it back and we are done.*

## Building Woomy3DS
```
git clone https://github.com/LinuxTheDS/Woomy3DS && cd Woomy3DS && make
```
#### and when thats done you should have a boot.firm image thats wooomy3ds firmware image built for you by you amazing
## Restoring Woomy3DS To n3ds
#### If you dont know what n3ds is its the normal boot.firm but yeah there will als be a guide on this once found out
