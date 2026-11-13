# ShiftSync firmware releases

Released firmware for ShiftSync units. The ShiftSync app and the [shiftsync.tech firmware page](https://shiftsync.tech/pages/current-firmware) read the latest release from here. The source code isn't published.

## What's here

Each [release](https://github.com/kcorbett95/shiftsync-firmware/releases) is one firmware version:

- **Tag:** the firmware version. `v1.x.y` is for V1 units (the 1.32" round display). `v2.x.y` will be for V2 units. Install only the line that matches your unit.
- **Release text:** the release notes for that version, including how to update.
- **`shiftsync_<version>_firmware.bin`:** the file to install. GitHub shows its size and SHA-256 next to the download.

Only final releases are published here; release candidates aren't.

## Installing

The easiest way is the ShiftSync app: **Firmware Update** installs the latest release. Without the app:

1. Download `shiftsync_<version>_firmware.bin` from the latest release for your unit's line.
2. On ShiftSync, open the **Upload** app.
3. On your phone or computer, join the Wi-Fi network **SHIFTSYNC** (password `12345678`).
4. Open **http://192.168.4.1/ota** in a browser and upload the file. Keep ShiftSync powered until it restarts by itself.

Each release's notes cover anything specific to that version, such as updating from the firmware ShiftSync shipped with.
