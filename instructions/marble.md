# Keep in mind...
- DO NOT USE any other recovery but only recommended ones availabe at xda and telegram.
- YOU MUST CLEAN FLASH IF:
    - You are coming from any other ROM or MIUI
    - You are coming from previous Android Version
- Magisk should only be flashed after booting once into the ROM. Do not flash Magisk along with the ROM package
- Use the latest hyperos firmware for your region
- Use recommended recoveries i-e TWRP 3.8 or awakenOS recovery
- If you face issues like poor RAM management or storage issues, you have not followed the instructions and/or have changed kernel/recovery. STRICTLY follow the instructions provided again before reporting any issues.

# Clean Flash (coming from a different ROM)
Clean flash involves formatting data which means you will be loosing data stored in the internal storage of your device. I will not be responsible for any loss of data.
- Download ROM
- Reboot the device to Recovery mode by powering off the device and then by holding Power button and Volume UP key together
- Format data
- Flash the ROM
- Make sure to enable the checkbox "Automatically reflash Twrp after flashing a Rom"
- Flash Firmware
- Reboot and voila!

# Flash using awakenOS recovery
- You must have a working PC and a type C data cable
- Download the ROM file to your PC
- Reboot into recovery as mentioned above
- Connect device to your PC and make sure you have all the necessary drivers installed
- Apply Update> Apply via adb sideload
- adb sideload rom.zip
- Format data
- Reboot and voila!

# Dirty Flash / Update
There will be no loss of data if everything goes well. Keep backups incase of any mishap. I will not be responsible for any loss of data.
- Download ROM file
- Reboot the device to recovery
- Flash the ROM
- Flash magisk (optional)
- Flash the firmware if you are not on the latest firmware
- Reboot and voila!

Note: In case of dirty flash/update you should flash magisk after reboot back to recovery to switch to updated slot a/b.
