# Disable Rotation Suggest
Permanently disables the rotate screen suggestion feature in Android P+ AOSP-Like roms
works in LOS, Pixel Experience and other AOSP roms.

## How it Works?
Android secure settings has a key called `show_rotation_suggestions` and it has True value by default

You can turn this Feature off using this command:
```
settings put secure show_rotation_suggestions 0
```
But after each restart, this value RESETs to Default value. This module changes that setting to `0` after Boot Complete to keep this feature off.

## Installation
This module is compatible to Magisk v20.4+ and it have UpdateJson api for Updating within Magisk Manager.
 
## Credits 

- [Magisk](https://github.com/topjohnwu/Magisk/): makes all these possible
- [MMT-Extended](https://github.com/Zackptg5/MMT-Extended/): created base installer scripts

This module created with the [Magisk-Module-Template](https://github.com/SAPTeamDEV/Magisk-Module-Template) automation engine v1.3.

## License

This Project is licensed under the **GNU General Public License v2 (GPL-2)** (https://www.gnu.org/licenses/old-licenses/gpl-2.0.html).
