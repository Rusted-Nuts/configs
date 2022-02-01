# Features (WIP)

## Terminal (alacritty)
- Fish shell
- pacman aliases
  - pu = sudo pacman -Syu
  - ps = sudo pacman -S
  - pq = sudo pacman -Qq
  - pr = sudo pacman -Rns

## Window Manager (i3-gaps)
- uses i3blocks for the status bar. which shows
  - weather (wttr.in)
  - disk space (/)
  - CPU temp/usage
  - RAM usage
  - Volume
  - Date and time
  - System Tray

- Keybindings 
  - Super+Shift+H = rotate screen left
  - Super+Shift+L = lock keyboard+touchpad
  - Super+Shift+J = restore screen rotation
  - Super+Shift+D = enter docked mode (for multi monitor setup)
  - Super+Enter = open alacritty
  - Super+Q = Close
  - Super+Space = open rofi
  - Super+F = open pcmanfm
  - win+shift+s = open htop (in alacritty)
  - win+shift+u = system update (in alacritty)
  - win+shift+enter = open alacritty as root
  - win+shift+r = restart i3
  - win+shift+e = exit i3
  - win+0 = shutdown mode
  - mod+d = open discord
  - mod+b = open brave
  - mod+s = take screenshot (with flameshot)

# Installation
give install.sh execute permissions with chmod +x install.sh

run ./install.sh

# Requirements
A collection of cofiguration files for software I use (will update often, i think?)
software required: i3-gaps, i3blocks, alacritty, brave, discord, flameshot, pcmanfm, vim, htop, rofi, neofetch, fish, starship, volumeicon, easystroke, onboard, networkmanager, nm-connection-editor, nm-applet, dunst, xfce4-power-manager, lightdm, lightdm-gtk-greeter, lightdm-gtk-greeter-settings, lxsession, lxappearance, picom-jonaburg, blueman-applet (and all dependencies of course)

# About .scripts
this folder contains scripts that are used with i3, mostly for tablet PC usage

at the moment, every file except keyslist is designed to be used with my tablet PC (Acer Spin 3), but they can be edited for your hardware
