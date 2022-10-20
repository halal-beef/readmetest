## Running Windows 11 On The Poco X3 Pro

<img align="center" src="https://github.com/halal-beef/res/blob/main/vayuwindows.png" height="550">

## Project Status

We're trying to porting drivers from Xiaomi Pad 5 in hope that it will work on the Poco X3 Pro.

## Hardware status
- [x] USB(Note: powered hub needed)
- [x] UFS
- [x] Display
- [x] UEFI buttons
- [ ] Touchscreen
- [x] WiFi ```I Get Random Reboots, This Could Be The WiFi Drivers Fault But I'm Not Sure```
- [x] Bluetooth
- [ ] Battery
- [ ] Charge
- [ ] Virtualization ```it's impossible for this to work```
- [x] GPU
- [ ] LTE ```Nearly Working```
- [ ] Audio ```only if it is by usb, in theory with more acpi edits audio can work driverless```
- [ ] Location
- [ ] Sensors
- [ ] Camera ```it is almost impossible in this project```
- [ ] NFC ```Note: does not work on any device```

## Disclaimer

We're not responsible for bricked devices, dead microSD cards, dead cats or dogs, nuclear wars or you getting fired because u forgot to boot back in to android for the alarm.

This project is in an early stage, all the files here have been contributed by other users, here you will find a guide with the working files we managed to get. This is a delicate process, do it under your own risk and follow all the steps carefully.


Many information here was provided thanks to Renegade Project Discord server members.

Some drivers in this project belong to gus33000 [here](https://github.com/WOA-Project/SurfaceDuo-Drivers) you can see his project.

Some drivers in this project belong to map220v [here](https://github.com/map220v/MiPad5-Drivers) you can see his project.

## Installation instruction Windows ARM on Poco X3 Pro(WIP)

## Required files

You will need the [Windows ARM image](https://uupdump.net/)(11 is Recommended)

[UEFI image for Poco X3 Pro](https://github.com/Icesito68/Port-Windows-11-Poco-X3-pro/tree/main/Uefi)

[TWRP](https://twrp.me/xiaomi/xiaomipocox3pro.html) for Poco X3 Pro

[Magisk](https://github.com/topjohnwu/Magisk)

[Termux](https://f-droid.org/en/packages/com.termux/)

[Magisk module](https://github.com/evdenis/disk) for disk partitioning in Termux.

On PC you will need the [platform-tools](https://developer.android.com/studio/releases/platform-tools)

We will need [parted](https://drive.google.com/file/d/1e8kDC2fylkvJuHimlViHOuHyk8xljr6p/view) for dualboot

### Commands to partitioning flash storage on Termux

Commands for Termux available [here](https://github.com/Icesito68/Port-Windows-11-Poco-X3-pro/tree/main/commands/termux)

This file is required to continue with the installation, you can download [here](https://www.mediafire.com/file/bvibrl34nawl2wg/msc.sh/file) ```This file belongs to gus33000```

You need a [program](https://github.com/WOA-Project/DriverUpdater/releases/) to install the [drivers](https://github.com/halal-beef/Vayu-Drivers)

## Credits

[Icesito68](https://github.com/Icesito68) ```Made Windows Partitioning Commands And Made This Repo```

[Map220v](https://github.com/map220v) ```Provided Help And Parts Of Vayu UEFI Uses Nabu UFS Patches, ACPI```

[Degdag](https://github.com/degdag) ```Improves UEFI And Ported Drivers```

[Halal-Beef](https://github.com/halal-beef) ```Built EDK2 And Modified It Enough To Boot Windows, Also Ported Drivers```

[Renegade Project](https://github.com/edk2-porting) ```Making The Core Of This Project```

[gus33000](https://github.com/gus33000) ```Providing Help, Also Made Base Install Guide```
