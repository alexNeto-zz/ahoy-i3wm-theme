# My i3wm desktop config

> Initially made for personal use, but released to encourage me to keep maintaining this theme and learn more about __i3wm__.

> I use these theme in the __arch linux__, but also used it in the __fedora 24__.

## Dependencies

### Font-awesome
Used for incons in the bar
1. Download the [Font-awesome](https://github.com/FortAwesome/Font-Awesome)
2. Copy the .ttf file:
    * Move the Fonts/font-awesome.ttf to the /usr/share/fonts/ to make it globally available.
    * Or create a .font to make it available just for one user.
3. Use the [Cheatsheet](http://fontawesome.io/cheatsheet/) to select a icon
 ### Font Muli
 Main font of the system, you can change to any other font
 1. Download the [Muli](https://fonts.google.com/specimen/Muli)
 2. Do the same as you did with font-awesome
 ### i3blocks
 Used instead of i3bar
 1. Install it
    * `# pacman -S i3blocks` for Arch linux based
    * `# apt-get install i3blocks` for Debian GNU/Linux based
 ### feh
 Used to set a wallpaper
 1. Install it
    * `# pacman -S feh` for Arch linux based
    * `# apt-get install feh` for Debian GNU/Linux based
 ### compton
 Allow transparency and effects
 1. Install it
    * `# pacman -S compton` for Arch linux based
    * `# apt-get install compton` for Debian GNU/Linux based

## Using it
just put the content of the i3 folder in the i3 config file. It can be in `~/.config/i3/` or `~/.i3/`.
I'm using the gnome-terminal, if you use other, change the name in the config file.
> I strongly recommend to rename the standard i3 to old_i3 and have a terminal open. Just in case something goes wrong.

Change the wallpaper and enjoy.

### controls

$mod may be the windows key or the alt key

Command | Effect
------------ | -------------
 **$mod + Enter** | start terminal
 **$mod + a** | focus the parent container
 **$mod + b** | start firefox in private mode
 **$mod + c** | start chromium
 **$mod + d** | start dmenu
 **$mod + e** | change container layout to split)
 **$mod + f** | enter fullscreen mode for the focused container
 **$mod + g** |
 **$mod + h** | split in horizontal orientation
 **$mod + i** |
 **$mod + j** |
 **$mod + k** |
 **$mod + l** |
 **$mod + m** |
 **$mod + n** | start nautilus
 **$mod + o** |
 **$mod + p** |
 **$mod + q** |
 **$mod + r** | resize windows
 **$mod + s** | change container layout to stacked
 **$mod + t** | start thunderbird
 **$mod + u** |
 **$mod + v** | split in vertical orientation
 **$mod + w** |change container layout to tabbed
 **$mod + x** | locks the screen
 **$mod + y** | start virtualbox
 **$mod + z** |
 **$mod + Shift + a** |
 **$mod + Shift + b** |
 **$mod + Shift + c** | reload the configuration
 **$mod + Shift + d** |
 **$mod + Shift + e** | exit i3
 **$mod + Shift + f** |
 **$mod + Shift + g** |
 **$mod + Shift + h** |
 **$mod + Shift + i** |
 **$mod + Shift + j** |
 **$mod + Shift + k** |
 **$mod + Shift + l** |
 **$mod + Shift + m** |
 **$mod + Shift + n** |
 **$mod + Shift + o** |
 **$mod + Shift + p** |
 **$mod + Shift + q** | kill focused window
 **$mod + Shift + r** | restart i3 inplace (preserves your layout/session)
 **$mod + Shift + s** |
 **$mod + Shift + t** |
 **$mod + Shift + u** |
 **$mod + Shift + v** |
 **$mod + Shift + w** |
 **$mod + Shift + x** |
 **$mod + Shift + y** |
 **$mod + Shift + z** |
 **$mod + Ctrl + a** |
 **$mod + Ctrl + b** |
 **$mod + Ctrl + c** |
 **$mod + Ctrl + d** |
 **$mod + Ctrl + e** |
 **$mod + Ctrl + f** |
 **$mod + Ctrl + g** |
 **$mod + Ctrl + h** |
 **$mod + Ctrl + i** |
 **$mod + Ctrl + j** |
 **$mod + Ctrl + k** |
 **$mod + Ctrl + l** |
 **$mod + Ctrl + m** |
 **$mod + Ctrl + n** |
 **$mod + Ctrl + o** |
 **$mod + Ctrl + p** |
 **$mod + Ctrl + q** |
 **$mod + Ctrl + r** |
 **$mod + Ctrl + s** |
 **$mod + Ctrl + t** |
 **$mod + Ctrl + u** |
 **$mod + Ctrl + v** |
 **$mod + Ctrl + w** |
 **$mod + Ctrl + x** |
 **$mod + Ctrl + y** |
 **$mod + Ctrl + z** |
 **$mod + 1** |
 **$mod + 2** |
 **$mod + 3** |
 **$mod + 4** |
 **$mod + 5** |
 **$mod + 6** |
 **$mod + 7** |
 **$mod + 8** |
 **$mod + 9** |
 **$mod + 0** |
 **$mod + Shift + 1** |
 **$mod + Shift + 2** |
 **$mod + Shift + 3** |
 **$mod + Shift + 4** |
 **$mod + Shift + 5** |
 **$mod + Shift + 6** |
 **$mod + Shift + 7** |
 **$mod + Shift + 8** |
 **$mod + Shift + 9** |
 **$mod + Shift + 0** |
 **$mod + Pause** | Open a menu to to logout, end session, restart or poweroff
 **$mod + Space** | change focus between tiling / floating windows
 **$mod + Shift + Space** | toggle tiling / floating
 **$mod + PrtSc** | Screenshot the focused window
 **$PrtSc** | Screenshot
 **$Shitf + PrtSc** | Screenshot a selection
 **$mod + f1** |
 **$mod + f2** |
 **$mod + f3** |
 **$mod + f4** |
 **$mod + f5** |
 **$mod + f6** |
 **$mod + f7** |
 **$mod + f8** |
 **$mod + f9** |
 **$mod + f10** |
 **$mod + f11** |
 **$mod + f12** |
 **$mod + Shift + f1** |
 **$mod + Shift + f2** |
 **$mod + Shift + f3** |
 **$mod + Shift + f4** |
 **$mod + Shift + f5** |
 **$mod + Shift + f6** |
 **$mod + Shift + f7** |
 **$mod + Shift + f8** |
 **$mod + Shift + f9** |
 **$mod + Shift + f10** |
 **$mod + Shift + f11** |
 **$mod + Shift + f12** |
 **$mod + Ctrl + f1** |
 **$mod + Ctrl + f2** |
 **$mod + Ctrl + f3** |
 **$mod + Ctrl + f4** |
 **$mod + Ctrl + f5** |
 **$mod + Ctrl + f6** |
 **$mod + Ctrl + f7** |
 **$mod + Ctrl + f8** |
 **$mod + Ctrl + f9** |
 **$mod + Ctrl + f10** |
 **$mod + Ctrl + f11** |
 **$mod + Ctrl + f12** |
 **$mod + Left** | focus left
 **$mod + Right** | focues right
 **$mod + Up** | focus up
 **$mod + Down** | focus down
 **$mod + Shift + Left** | move left
 **$mod + Shift + Right** | move right
 **$mod + Shift + Up** | move up
 **$mod + Shift + Down** | move down
 **$mod + Ctrl + Left** |
 **$mod + Ctrl + Right** |
 **$mod + Ctrl + Up** |
 **$mod + Ctrl + Down** |
