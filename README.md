## Minimalistic rEFInd theme (Modified)

[rEFInd](http://www.rodsbooks.com/refind/) is an easy to use boot manager for UEFI
based systems. This is a clean and minimal theme for it.

![Preview](https://i.ibb.co/ChT1PTm/refind.png)

### Usage

 1. Locate your refind EFI directory. This is commonly `/boot/EFI/refind`
    though it will depend on where you mount your ESP and where rEFInd is
    installed. `fdisk -l` and `mount` may help.

 2. Create a folder called `themes` inside it, if it doesn't already exist. Then create a folder called `rEFInd-minimal` in the themes folder.

 3. Clone all contents of this repository into the `rEFInd-minimal` directory.

 4. To enable the theme add `include themes/rEFInd-minimal/theme.conf` at the end of
    `refind.conf`.

Entries that are autodetected should also show the proper icons.

### Attribution

The OS icons are from [refind-theme-dark] by samuelmeuli.


[refind-theme-dark]: https://github.com/samuelmeuli/refind-theme-dark
