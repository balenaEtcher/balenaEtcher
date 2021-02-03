![1](https://balenaetcher.eu/wp-content/uploads/2020/12/balenaetcher-do-pobrania-za-darmo-s.jpeg)

**balenaEtcher (Etcher)** is a free utility for Windows, MacOS and Linux that helps you quickly and easily create bootable USB flash drives and SD cards from installation images of operating systems


The main feature of the program is that it supports the three most common operating systems: Windows, Linux and MacOS. So, for example, in the Windows environment, you can create a bootable USB flash drive for MacOS. At the same time, the program has extremely limited functionality, however, not all users like the abundance of unnecessary functions. The interface itself is simple and not overloaded with unnecessary elements. Despite the absence of a Russian-language version, the program is intuitive.

# Features:

## Validated Flashing
No more writing images on corrupted cards and wondering why your device isn’t booting.

## Hard Drive Friendly
Makes drive selection obvious to avoid wiping your entire hard-drive.

## Beautiful Interface
Who said flashing SD cards has to be an eyesore.

## Open Source
Made with JS, HTML, node.js and Electron. Dive in and contribute!

## Cross Platform
Works for everyone,
no more complicated install instructions.

## More on the way
50% faster flashes, simultaneous writing for multiple drives.

# Supported operating systems
- Microsoft Windows 7 and later
- MacOS 10.10 (Yosemite) and later
- Linux (most distributions)

# Supported image formats
- IMG       
- ISO
- ZIP
- BZ2
- DMG
- DSK
- ETCH
- GZ
- HDDIMG
- RAW
- SDCARD
- XZ
- RPI-SDIMG

# Why BalenaEtcher?
Here at balena, thousands of users are working on our initial stage of work, and until recently we were shy about the steps involved in flashing the SD card. For each Mac / Windows / Linux, there was a separate track and a few manual and error-prone steps along the way.

To our surprise, nothing was found to meet our needs. Therefore, we created Etcher, an SD card flashing application that is easy for users, extensible for developers and works on any platform.

# Change Log
**v1.5.113**
- Shows the first error for each disk (not the last)
- docs: add links to documentation
- docs: macOS version update
- Improved hover message when disk is too small
- Electron update to V9.4.0
- NPM update to V6.14.8
- RGB LED color update
- Removed unmountOnSuccess setting
- Shows only automatic update settings for supported targets
- Removed dead code in modal settings
- Fixed efficient calculation of blinking speed for compressed images
- Changed some border colors to get higher contrast

**v1.5.112**
- Added representation and sys-class-rgb-led to repo. in YML format
- Sys-class-rgb-led update from 2.1.0 to 2.1.1
- Fixed layout (when shown project is not displayed)
- Improved handling of blinking errors
- Fixed height of modal content on Windows
- Set useContentSize to true so the size is the same across all platforms

**v1.5.111**
- Uses a different icon when the source disk is not available
- Allowed selection of locked SD card as source disk
- Removed «check if write was successful» option. The check is always on, click the «Skip» button to skip it.
- Electron updated to V9.3.3
- Upgrade engraver-SDK to version 5.1.1, use WASM module and ext2fs

**v1.5.110**
- Removed console.log in tests
- Fixed url selected using custom protocol
- Added skip function for check
- Success screen redesigned

**v1.5.109**
- Fixed elevation bug on Windows when username contains ampersand

**v1.5.108**
- Fixed content not loading when app path contains special characters

**v1.5.107**
- Re-enabled trimming ext partitions on 32-bit Windows
- Rework system and large disk processing logic
- Added clone disk workflow

**v1.5.106**
- Disabled trimming ext partitions in 32-bit windows until it is fixed
- Fixed opening zip files from servers accepting range headers

**v1.5.105**
- Etcher-sdk updated to version 4.1.26
- URL selector cancel button overrides persistent URL selection

**v1.5.104**
- Fixed error writing configuration file
- Electron update to V9.2.1

**v1.5.103**
- Upgrade version to ^ 17
- Electron update to 9.2.0
- Etcher-sdk update to version ^ 4.1.23
- Install module: es2015 in tsconfig.json
- Replaced native elevator with sudo-prompt on windows
- Don’t import the WeakMap polyfill into Deep-map-keys
- Don’t use lodash in child-writer.js
- Optimize svgs

**v1.5.102**
- Fixed truncated images blinking, fix big dmgs blinking
- Electron 9.1.1
- Removed bluebird from main process, reduce lodash usage
- Centralize imports in child-writer
- Removed Font awesome unused icons from generated package
- Use tslib
- Strict typewritten compiler is used
- Version upgrade to ^ 16.1.1


