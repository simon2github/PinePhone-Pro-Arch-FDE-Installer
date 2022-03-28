# PinePhone-Pro-Arch-FDE-Installer

SHORT:
Script to install Arch Arm with full disk encryption on a PinePhone Pro.
Adapted from: dreemurrs-embedded
https://github.com/dreemurrs-embedded/archarm-mobile-fde-installer

NOTE:
Only works with fresh build;
https://github.com/dreemurrs-embedded/archarm-mobile-fde-installer/pull/14

CHANGES:
- Add PinePhone PRO support
- Removed Pinephone support

INSTALL:
1. Run Arch on your Desktop
2. Install deps
3. Connect PinePhone Pro with Two-Boot as Mass Storage Device (If you want to flash to Phone Storage)
4. sudo ./installer.sh
5. Follow instructions, choose Image and Device
6. Set FDE Passphrase
7. Boot your PinePhone Pro from MMC (Two-Boot: just power on)

Default credentials:
alarm/123456

