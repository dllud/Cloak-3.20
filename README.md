# Cloak 3.20 with dark blue selection

[Original Cloak](https://killhellokitty.deviantart.com/art/Cloak-3-20-6-05052016-603341133) highlights selections with black text on light blue background. I found this contrasted too much with the surrounding deep dark background. Thus I switched it for white text on a dark blue background copied from [Dorian 3.14](https://github.com/dllud/Dorian-3.14/).

## ROOT-THEME

1. Open ROOT-THEME folder and copy or symlink `Cloak-3.20` folder inside to Root`s home folder, in the `.themes` folder (`/root/.themes/`).
2. The Normal `Cloack-3.20` theme must then be installed to your home folder inside the `.themes` (`$HOME/.themes`) folder for this to work.

If there is no `.themes` folder please create them.

## Firefox

1. Open Firefox folder and copy or symlink `chrome` folder located inside `$HOME/.mozilla/firefox/xSomeNumbers.default`.
2. Restart Firefox for the changes to take effect.

This theme displaying correctly depends on `Cloak-3.20` being selected as Gtk theme.

To Remove:  
Simply move the `chrome` folder inside `$HOME/.mozilla/firefox/xSomeNumbers.default` to the trash.

## gnome-shell-GDM

1. Open `/usr/share/gnome-shell/` and backup the `gnome-shell-theme.gresource` file.
2. Open `gnome-shell-GDM` folder inside `Cloak-3.20` folder and copy or symlink `gnome-shell-theme.gresource` file to `/usr/share/gnome-shell/`.
3. The new theme will be installed when you restart.

Notes:

- Any update to Gnome-Shell will erase the theme file and return it to the Adwaita default, you will need to reinstall.

- If you would like to change the background of the GDM screen to match you wallpaper or other, please refer to https://bbs.archlinux.org/viewtopic.php?id=197036
