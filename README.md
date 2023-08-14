# dotfiles

1. Do void linux base install 
2. Install xorg and dbus
3. Enable and simlink dbus (sudo sv up dbus && sudo ln -s /etc/sv/dbus /var/service)
4. Install bspwm sxhkd polybar picom dmenu dunst kitty thunar pywal neofetch nitrogen git
5. Clone this repo
6. Copy all folders to ~/.config then copy parentrc/.xinitrc to ~/.xinitrc and parentrc/.bashrc to ~/.bashrc
7. Do startx