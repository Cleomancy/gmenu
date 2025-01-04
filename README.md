# Glorious Dmenu

## Rice:
I use DWM with dwmblocks, st is my terminal and dmenu is my god.
This is my build of dmenu with mouse support included.

## Prerequisites:
I use arch btw,
```
pacman -Sy base-devel xorg-server xorg-xinit libxinerama
```

## Patches:

- [mouse support](https://tools.suckless.org/dmenu/patches/mouse-support/)
- [highlight](https://tools.suckless.org/dmenu/patches/highlight/)
- [border](https://tools.suckless.org/dmenu/patches/border/)
- [lines below prompt](https://tools.suckless.org/dmenu/patches/lines-below-prompt/)

## Install:
```
cd gmenu/
sudo make clean install
```

## Credits:

- [dmenu](https://tools.suckless.org/dmenu/) obviously
