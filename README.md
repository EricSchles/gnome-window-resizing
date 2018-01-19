# gnome-window-resizing

First you'll need to look at this guide for [Gnome Extensions](https://itsfoss.com/gnome-shell-extensions/).

Next you'll need to install [put windows](https://extensions.gnome.org/extension/39/put-windows/) which will allow you to recover all window moving hotkey functionality you are used to in ubuntu.

Also, for some reason (at least with HP machines) the screen randomly flips?  Seems like a hardware bug.  [This solution](https://askubuntu.com/questions/968169/screen-randomly-rotates-on-ubuntu-17-10) appears to fix it.  

Run the following two commands at the terminal:

`gsettings set org.gnome.settings-daemon.peripherals.touchscreen orientation-lock true`

&&

`gsettings set org.gnome.settings-daemon.plugins.orientation active false`
