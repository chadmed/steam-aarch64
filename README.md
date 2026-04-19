# Steam AArch64 wrapper

Very basic and thin launcher for Steam on AArch64 platforms. 

## Dependencies
- zenity for displaying messages to users
- [FEX-Emu/FEX](https://github.com/FEX-Emu/FEX)
- [AsahiLinux/muvm](https://github.com/AsahiLinux/muvm) on systems that do not use 4K memory pages
- Steam - we are not redistributing this

## Installation
1. Install Steam's bootstrap launcher
2. Overwrite `/usr/share/applications/steam.desktop` with the desktop entry in this repo
3. `update-desktop-database /usr/share/applications/`
4. Copy `steam-aarch64` and `steam-muvm` to `/usr/bin/` and `chmod a+x` them
