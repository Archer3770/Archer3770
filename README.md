# My TWRP Build Check (SM8550)

Blocking checks
- [x] Correct screen/recovery size
- [x] Working Touch, screen
- [x] Backup to internal/microSD
- [x] Restore from internal/microSD
- [x] reboot to system
- [x] ADB

Medium checks
- [x] update.zip sideload
- [ ] UI colors (red/blue inversions)
- [x] Screen goes off and on
- [x] F2FS/EXT4 Support, exFAT/NTFS where supported
- [x] all important partitions listed in mount/backup lists
- [x] backup/restore to/from external (USB-OTG) storage (not supported by the device)
- [ ] backup/restore to/from adb (https://gerrit.omnirom.org/#/c/15943/)
- [ ] decrypt /data
- [ ] Correct date

Minor checks
- [x] MTP export
- [ ] reboot to bootloader
- [x] reboot to recovery
- [x] poweroff
- [x] battery level
- [x] temperature
- [ ] encrypted backups
- [x] input devices via USB (USB-OTG) - keyboard, mouse and disks (not supported by the device)
- [x] USB mass storage export
- [x] set brightness
- [ ] vibrate
- [x] screenshot
- [ ] partition SD card
- [x] fastbootd
- [x] download mode (samsung)
