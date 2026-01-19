## i3 WM Configuration

A simple and minimal i3 window manager configuration.

### Requirements

- i3
- picom
- polybar
- alacritty
- neofetch
- rofi
- feh

### Installation

#### Ubuntu / Debian-based Distributions

```bash
sudo apt-get update
sudo apt-get install i3 feh polybar rofi alacritty picom neofetch
```
#### Arch-based Distributions
```bash
sudo pacman -S i3 polybar feh rofi alacritty picom neofetch
```
### Setup

Copy all configuration files (except the screenshots directory) into your ~/.config directory.
```bash
cp -r * ~/.config
```
Make sure to back up your existing configuration files before copying.

### Usage

- **Mod key:** Super (Windows key)
- **Super + X:** Open rofi
- **Super + Enter:** Open alacritty
- **Super + Shift + Q:** Close the currently focused application
- **Super + Shift + Number:** Move the focused application to the specified workspace
- **Super + Shift + E:** Log out
- **Super + Shift + R:** Restart i3
- **Super + Shift + Arrow Keys:** Move the focused window

I hope you enjoy using this configuration.❤️

