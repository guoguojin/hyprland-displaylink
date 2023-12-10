# Hyprland with Displaylink patch

The AUR package that this was updated from hyprland-displaylink-git has been orphaned and stuck on version 0.30.0. As I do not have the time or sufficient knowledge to maintain and support an AUR package, I have simply updated the PKGBUILD for my own personal use on my machines and make this available in a public repo should anyone have use for it.

**BE WARNED** while this works on my machine, I provide no guarantees it will work for anyone else, I provide no support and am not available to answer any questions regarding why it is not working on your machine.

## CHANGE LOG

### 2023-12-10

 - Update to v0.33.1
    - Changed the `pkgver` to 0.33.1
    - Updated the sha256sum for the hyprland package downloaded
    - Removed `make fixwlr` from the build steps as that command is no longer available in the Hyprland source Makefile any longer
    - In the package install function update the libwlroots.so shared library version number from 12028 to 13.
