# Hackintosh configuration (with MacOS 26 Tahoe) for the Lenovo Thinkbook 15 G3 ACL

This repository contains the OC folder that allows boot and installation of a "working" MacOS Tahoe installation.

## Things that are not working

- Analog audio (AppleHDA not available anymore in MacOS Tahoe. It is suggested that you use MacOS Sequoia for this to work without installing VoodooHDA.
- Bluetooth

- Google Chrome browser AND any other Chromium-based browser (Vivaldi, Opera, Brave, etc) (GPU issues)

Everything else is pretty much fine!

## My configuration (to check if yours is good)

- Ryzen 7 5700U with Vega GPU
- WD PC SN530 (512GB) (MacOS installation disk)
- Samsung 980 (secondary disk, doesn't matter)
- 16GB RAM, 2 of those are dedicated as UMA buffer


## How to use it

1. Create your MacOS hackintosh installer using [Dortania's OpenCore install guide](https://dortania.github.io/OpenCore-Install-Guide/installer-guide/)
2. Ensure that you have MacOS Tahoe downloaded using `macrecovery.py`
3. Replace the `OC` folder in `EFI/` with the one provided in the repository.

When booting up the USB, press Space and select the USB to boot into the recovery.
Format your drives and install normally.
