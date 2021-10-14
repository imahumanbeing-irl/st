# gooogle dark st
## recommendations
- install artix linux
- install my dwm fork too (if you do this dont follow the repeated steps from the dwm fork)
- be me, the creator

## key bindings
- ctrl+shift+c to copy
- ctrl+vshift+v to paste
- alt+shift+k to zoom out
- alt+shift+j to zoom in

## installation
NOTE: this assumes you are using an arch derivative or arch itself and assumes you have yay installed
```
sudo pacman -S awesome-terminal-fonts
yay -S nerd-fonts-fira-code
git clone https://github.com/imahumanbeing-irl/st
cd st
mv .fonts.conf ~
sudo make install
```
## more
this is the same as lukesmiths st, i only changed the color scheme, some key bindings and made the terminal opaque
