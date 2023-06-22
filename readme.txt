Instructions for updating the software of PSIO copies / clones:

1. Download archives MENU2628 and menu2628_hack_v4_patch;
2. Unpack the contents of the downloaded archives into a separate directory;
3. Run the patch.cmd script, wait for completion, as a result, only the MENU.SYS file will remain in the directory;
4. Place the resulting MENU.SYS file on the SD card;
5. If the device uses Menu System version 2.6 (build 3), then you should download the UPDATE2628 archive and unpack its contents to an SD card;
6. Insert the SD card into the PSIO, wait for the update to complete by following the instructions on the screen.

If the menu starts after the update, but the list is empty, then you should reset the settings by pressing and holding the SELECT and START buttons while the console is starting.

---------
Reference
---------

MENU2628

	Original MENU.SYS version 2.6 (build 28).

	DO NOT USE WITHOUT A PATCH!
	Otherwise, you can get a "brick" of the device (clearing the contents of the EEPROM SPI microcircuit), as well as losing the serial number 			recorded in the internal memory of the ARM microcontroller.

UPDATE2628

	Files required to upgrade from Menu System version 2.6 (build 3).

RECOVERY2628

	Files needed to restore the "brick" (the contents of the EEPROM of the SPI chip have been cleared). This is the same as UPDATE2628, with the only 	difference being that the "FIRMWARE.AFW" file has been renamed to "RECOVERY.BIN".

menu2628_hack_v4_patch

	A set of files for making changes to the original MENU.SYS version 2.6 (build 28), allowing it to be used on PSIO copies/clones.

menu2628_hack_v5_patch

	A set of files for making changes to the original MENU.SYS version 2.6 (build 28), allowing it to be used on PSIO copies/clones.
	In v5, added the display of the serial number with zeros in case it was erased.

serial_number_recovery

	An exploit that allows you to recover a lost device serial number. The serial number will be the most common among clones - 050715001789.

