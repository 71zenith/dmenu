# This repo contains my personal build of Dmenu

## Custom keybindings :-

- `C-j` Down
- `C-k` Up
- `C-u` Home
- `C-d` End
- `C-o` Return

## Installation :-

To install make sure to have gcc, make, and pkgconfig and libxft-bgra(needed for proper rendering of emojis). These are the names of packages in Arch Linux that are required to build dmenu and make it work. Go and search what these packages are called in your distro if you aren't running something Arch-based.

```sh
git clone https://github.com/71zenith/dmenu.git
cd dmenu
make
doas make install
```

Run the above command in the terminal and if everything goes right, then dmenu will be on your system.

