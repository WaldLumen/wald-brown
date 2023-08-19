# wald-brown
Brown [i3] rice.



---------------------------------

Wallpapers and polybar
![Wallpapers and polybar]()
Firefox start page and theme
![Firefox start page and theme]()
Just cool screenshot
![Just cool screnshoot]()

---------------------------------

Dependencies:
```
sudo pacman -S alacritty picom polybar rofi zathura python-pywal ttf-jetbrains-mono alsa-utils flameshot
yay -S cava
```

---------------------------------

Installing
```
git clone https://github.com/WaldLumen/wald-brown.git $HOME/Downloads/wald-brown
cp -r $HOME/Downloads/wald-brown/wald-brown/* $HOME/.config
chmod +x .config/polybar/cava.sh
```
---------------------------------

Keybindings:
```
Win+q - kill window
Win+f - fullscren toggle
Win+r - resize mode(works on arrows)

Win+Shift+r restart i3

Win+j focus left
Win+k focus down
Win+l focus up
Win+semicolon focus right

Win+Shift+j move left
Win+Shift+k move down
Win+Shift+l move up
Win+Shift+semicolon move right

Win+F8 - -5% volume
Win+F9 - +5% volume

Win+d - rofi
Win+p - flameshot
