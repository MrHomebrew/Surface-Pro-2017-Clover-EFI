# Surface-Pro-2017-Clover-EFI
Surface Pro 2017 i5 HD620 Clover EFI for 10.15.6 and 10.15.7

Brought to you by: MrHomebrew aka Leonidas
Surface Pro 2017 i5 HD620 Clover EFI for 10.15.6 and 10.15.7



DO NOT AND I MEAN DO NOT!!!! INSTALL TO YOUR SURFACE PRO 2017 INTERNAL DRIVE!!!!
USE A SECONDARY EXTERNAL HARD DRIVE, EXTERNAL M.2 INCLOSURE OR EXTERNAL SSD.



CREATE YOUR CATALINA USB INSTALLER USING YOUR PREFERRED METHOD.
COPY THIS EFI FOLDER TO THE EFI PARTITION OF YOU CATALINA USB INSTALLER.



TO INSTALL OR UPDATE YOU MUST, use the config-install.plist UNTIL FULLY COMPLETED.



BOOT FROM CATALINA USB INSTALLER (MAKE SURE SECURE BOOT IS OFF IN BIOS). Select config-install.plist IN CLOVER BOOT MENU UNDER CONFIG OPTION and continue to boot Catalina installer. 
Load disk Utility in installer, select view and check show all devices. 
THIS WILL DELETE EVERYTHING OFF YOUR DRIVE BE SURE TO BACKUP BEFORE PROCEEDING IF NEEDED!!!! Format/Erase YOUR external drive/disk as Catalina for the name, APFS format and also select GUID Partition Map as Scheme in DISK UTILITY, ERASE DRIVE.



GO BACK TO THE MAIN INSTALLER MENU AND CONTINUE WITH THE INSTALLATION. INSTALL TO THE CATALINA DRIVE YOU JUST CREATED!!!!



Restart and use the config-install.plist AGAIN for one more time DURING FIRST BOOT AFTER INSTALLATION COMPLETES AND DO NOT RESTART UNTIL I SAY SO (KEEP FALLOWING INSTRUCTIONS).



Connect to the internet with a compatible usb ethernet adapter OR connect a compatible bluetooth dongle and use Bluetooth tethering from your phone (NOT THE FASTEST USING BLUETOOTH TETHERING BUT WORKS AS A SECONDARY OPTION). Pair with your phone and then right click your phone in bluetooth settings. Select connect to network to tether off your phone.



Download these files:
https://github.com/headkaze/Hackintool/releases/download/3.4.4/Hackintool.zip
https://github.com/chris1111/Wireless-USB-Adapter-Clover/files/5246490/Wireless.USB.Adapter.Clover-V16.zip
https://github.com/CloverHackyColor/CloverBootloader/releases/download/5122/Clover.app_v1.24.pkg



Install both Clover.app_v1.24.pkg and Wireless USB Adapter Clover-V16.pkg along with moving Hackintool application to the Applications folder.
BUT DO NOT RESTART JUST YET AS RECOMMENDED BY Wireless USB Adapter Clover-V16.pkg INSTALLER JUST MINAMIZE IT.



WHEN INSTALLING OR FIRST STARTING THESE APPLICATIONS YOU MAY NEED TO ALLOW IT TO RUN IN Settings and then Security and Privacy. There should be an open option for the last attempted application opening. For example Hackintool app.



Using Clover app mount Clover EFI partition from your Catalina usb installer drive. Also mount the EFI partition from your SECONDARY drive that you installed Catalina on. COPY EFI FOLDER FROM Catalina usb installer drive to the EFI partition of the SECONDARY Catalina INSTALLED drive.



Open Hackintool and select Utilities tap. Then click the lego block/Install Kext(s) icon. Navigate to the EFI partition, then to the EFI/CLOVER/kexts/Other folder and install both the VoodooI2C.kext and VoodooI2CHID.kext using Hackintool to Library/Extensions folder. WAIT TILL IT COMPLETES!!!!



CLOSE HACKINTOOL AFTER IT FINISHES AND THEN CLICK THE RESTART BUTTON FROM THE Wireless USB Adapter Clover-V16.pkg INSTALLER WE MINIMIZED BEFORE.



BOOT FROM YOUR EXTERNAL DRIVE WITH THE NEWLY CREATED CLOVER EFI BOOTLOADER. NO NEED TO CHANGE THE CONFIG THIS TIME ALL SHOULD BE GOOD TO GO.



ENJOY!!!!



Brought to you by: MrHomebrew aka Leonidas
Surface Pro 2017 i5 HD620 Clover EFI for 10.15.6 and 10.15.7
