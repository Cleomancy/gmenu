# Glorious Dmenu

## Rice:
I use DWM with slstatus, st is my terminal and dmenu is my god.
This is my build of dmenu with mouse support included.

## Prerequisites:
I use arch btw,
```
pacman -Sy base-devel xorg-server xorg-xinit libxinerama libxft feh unclutter ttf-font-awesome ttf-hack
```
You can already guess my dotfiles.

## Patches:

- [mouse support](https://tools.suckless.org/dmenu/patches/mouse-support/)
- [highlight](https://tools.suckless.org/dmenu/patches/highlight/)

## Install:
```
cd gmenu/
sudo make clean install
```

## Credits:

- [dmenu](https://tools.suckless.org/dmenu/) obviously