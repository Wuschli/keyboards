# Planck
edit & compile via QMK WSL https://wsl.qmk.fm/guide

qmk fork at https://github.com/Wuschli/qmk_firmware

```
wsl -d QMK
cd qmk_firmware
qmk compile -km wuschli
```
flash via qmk toolbox or `qmk flash -km wuschli` (might require different drivers)

if qmk toolbox has wrong driver (libusb) use zadig to install WinUsb for **bootloader (not the Planck device itself!)** https://github.com/qmk/qmk_firmware/blob/master/docs/driver_installation_zadig.md
