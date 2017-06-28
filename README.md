# lpebutton

1. After copying files to BOOT, remember to set new ID number in "config" file.
2. You may also want to change other parameter setting, such as "IMAGE_ENCRYPTION 1".
3. Use sudo to copy start_app to rootfs/etc/init.d, this will replace old start_app file
4. Finally, for new sdcard, serial console on ebutton has to be used to update file system service under init.d folder using "sudo update-rc.d start_app defaults")
