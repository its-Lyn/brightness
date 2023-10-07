# Brightness

Brightness is a small bash script I wrote to change the brightness of all connected monitors.

## Usage:
```bash
brightness up
```
or
```bash
brightness down
```

## Installation:

### Dependencies:
xrandr and bc
For arch based systems:
```bash
sudo pacman -S xorg-xrandr bc
```
For debian/ubuntu based systems:
```bash
sudo apt-get install x11-xserver-utils bc
```
### Downloading:
```bash
git clone https://github.com/its-Lyn/brightness.git
cd brightness

chmod +x brightness
./brightness
```