## dwm - Dynamic Window Manager 

dwm is a dynamic window manager for Xorg. It manages windows in tiled, stacked, and full-screen layouts, as well as many others with 
the help of optional patches. Layouts can be applied dynamically, optimizing the environment for the application in use and the task being performed.

# Patches 
- Vanity Gaps

# Prerequisites
`xorg-server`
`xinit` If you do not want to use a Display Manager. 
`Xft`
`Xinerama` and a few other Xlib header files. 
`Git`
`base-devel`

# Download
```bash
git clone https://github.com/dcodecrzft/dwm.git
```

# Installation
```bash
cd dwm/
sudo make clean install
```

# Running Dwm. 
```bash
touch ~/.xinitrc
echo "exec dwm" >> ~/.xinitrc
```

Then Run:
```bash
startx
```

There You Go! You have succesfully installed dwm. 
