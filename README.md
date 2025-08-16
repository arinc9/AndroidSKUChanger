# AndroidSKUChanger

Currently the module changes Nothing Phone (3a)'s SKU to Japan (JPN). To change the SKU to another region for any other device:

- Install the module without rebooting.
- Modify /data/adb/modules/com.arinc9.skuchanger/system.prop accordingly with /odm/etc/build_<3-letter-region-code>.prop on your device. Rest of world or global (ROW) SKU may be just called build.prop.
- Reboot.
