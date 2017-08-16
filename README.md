# My i3wm desktop config

> Initially made for personal use, but released to encourage me to keep maintaining this theme and learn more about __i3wm__.
> I use these theme in the __arch linux__, but also used it in the __fedora 24__

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
Change the wallpaper and enjoy
