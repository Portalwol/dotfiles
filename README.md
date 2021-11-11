# dotfiles

![image](https://user-images.githubusercontent.com/88345210/141351126-927340f1-9798-43c9-8718-95212b1e182a.png)

Thanks flameshot for destroyingn the image anyways.

These are my dotfiles Ill put instructions on how to download them but they might not work the best for other people so sorry if any issues arrive unless im in a good mood Because I never planned too release this lmao.


Alright how to install

clone this repo
then install these packages with whatever aur helper you use im gonna use pacman for this example oh yeah if you want to install this on a distro than arch / archbased distro's you gotta find the packages names for you package manager. **pacman -S --needed alacritty neofetch awesome rofi picom nerd-fonts-jetbrains-mono**

after that to install better discord do
**curl -O https://raw.githubusercontent.com/bb010g/betterdiscordctl/master/betterdiscordctl
**chmod +x betterdiscordctl
**mv betterdiscordctl /usr/local/bin

**betterdiscordctl install

alright from here shove everything in your .config except readme.md dumbas
I dont provide dispplay manager and xorg server setup so you do that on your own.










Keybinds
Keybinds you can change them in keys.lua

Keyboard

mod + enter: Spawn terminal

mod + s: Show help menu

mod + d: Spawn rofi (an application menu)

mod + F11: Make client fullscreen

mod + m: Maximize client

mod + n: Minimize client

mod + shift + n: Unminimize client

mod + [1-9]: Switch to tag [1-9]

mod + shift + [1-9]: Move client to tag [1-9]

mod + space: Change the tag layout, alternating between tiled, floating, and maximized

mod + [up / down / left / right / h / j / k / l]: Change client by direction

mod + Control + [up / down / left / right / h / j / k / l]: Resize client by direction

mod + Escape: Show exit screen


Mouse

mod + drag with left click: Move client

mod + drag with right click: Resize client
