# ARK-OS

Welocme to the only and official ARK-OS Repository hosted on github!

> [!NOTE]
>
> It is recommended to use ssh to clone the repo!

You can sync via:
```bash
repo init -u git@github.com:ARK-OS-Swift-and-Linux/main.git
repo sync
```
## What is it?

It's a Linux-based operating system built from scratch — designed to be easy to use, easy to compile, and open for customization.

> [!DISCLAMER]
>
> Building now requires a Stable Internet Connection!
> Only on the first build since after that downloads are cached
> If you rerun a Fresh build you will need a Internet Connection!
> This is to reduce the size of the project on github!

## Compiler ([aake](https://github.com/ARK-OS-Swift-and-Linux/aake))

The compiler for ark-os so you can build and test it!

Current Stuff to Implement: Allow the Compiler to compile for arm64 (rasberiPi4)

## Components

### [arkrt](https://github.com/ARK-OS-Swift-and-Linux/ark-os-arkrt)

The init System for ARK-OS... it's not only then init system but a main part of the OS:
 - It manages Services
 - Provides Terminal through TTY (sash (using libark))

### [System](https://github.com/ARK-OS-Swift-and-Linux/ark-os-system)

For now this only has the sysroot's... but with later comprise of system-apps and other modules!

### [Vendor](https://github.com/ARK-OS-Swift-and-Linux/ark-os-vendor)

This where all the signing keys and vendor data goes into... though it's not yet implemted properly and there is still a doubt of encryption and boot verification at startup!

### [Kernel](https://github.com/ARK-OS-Swift-and-Linux/ark-os-kernel)

This is where the kernel's (LINUX) live for x86_64 (7.0.0) and the arm64 (rpi4, 6.18.40) and all the dtb and dtbo files of the rpi4!

### [Prebuilts](https://github.com/ARK-OS-Swift-and-Linux/ark-os-prebuilts)

This is where all the prebuilts lie!

### [Boot](https://github.com/ARK-OS-Swift-and-Linux/ark-os-boot)

The bootloader for ARK-OS with that expanding dot animation!

### [Frameworks](https://github.com/ARK-OS-Swift-and-Linux/ark-os-frameworks)

The frameworks for ARK-OS! DRM and a swift libc.a

Comming Soon: Swift Compiler and gcc!

## Tools

These are a part of ARK-OS but can also be used elsewhere!

 - [libark](https://github.com/ARK-OS-Swift-and-Linux/libark)

## Website

https://ark-os-swift-and-linux.github.io/ARK-OS-Website/
