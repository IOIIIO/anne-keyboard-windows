ObinsKit absolutely sucks, so I am reviving this until proven otherwise.

# Anne Keyboard Windows
A Universal Windows App for controlling the Obins Anne Pro keyboard over Bluetooth Low Energy.  

## Requirements
This app has been tested against Windows 10. Other version of Windows is not supported due to Universal Windows App (UWP) platform only supporting Windows 10.
The keyboard has to be in L0 mode by: pressing ```Fn+B, Fn+0, ESC, Fn+B, +```

## Installation
* Enable Development mode on your Windows 10 machine by following the [instructions here](https://msdn.microsoft.com/windows/uwp/get-started/enable-your-device-for-development).
* Download the latest binary files from [Github](https://github.com/ethanmsmith/anne-keyboard-windows/releases). 
* Install the app by extracting the zip file, and right-clicking on ```Add-AppDevPackage.ps1``` and select ```Run with PowerShell```. 
* The app should now be installed and will be on Start menu.

## Features 
### Core
- [x] Automatic keyboard pairing
- [x] Create and manage profiles
- [x] Set keyboard backlight colours
- [x] Set keyboard layout

### Sharing
- [x] .kpi file extension
- [x] Export profile
- [x] Opening profiles
- [x] Choosing export location
- [x] Importing profiles in app
- [X] .kpis

### Statistics
- [ ] Logging (Debugging)
- [ ] Metrics (Performance, crashing, versions, etc.)

### Versioning
- [ ] Automatic updating

## Bugs
See GitHub issue tracker

## License
The codebase and the project are released under the permissive MIT License. 
The images and icons are generated using the Font Awesome font released under the [OFIL license](http://scripts.sil.org/OFL), and the font can be found on [Github](http://scripts.sil.org/OFL). 
