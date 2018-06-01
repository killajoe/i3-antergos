# i3-antergos
![i3-antergos](https://i.imgur.com/XjIf9Ag.png "i3-antergos")

My modifications to Antergos styled i3 installation (sudo pacman -S [antergos-i3-meta](https://github.com/Antergos/antergos-packages/blob/master/antergos/antergos-i3-meta/PKGBUILD))

* adding polkit-gnome to get athentification for gui apps working.
* change from kalu to pamac, and adding pamac-tray to autostarting.
* fixed time and date to look more clean.
* change volume icons to speaker from bell.
* bind F4 to kill focused windows
* standard workspace_layout tabbed

To use it simple follow this steps:

* [install antergos with XFCE Desktop](https://antergos.com/wiki/install/installing-antergos-2/)

* `sudo pacman -S antergos-i3-meta`

* clone the repository:
`git clone https://github.com/killajoe/i3-antergos.git`

* Copy the two folder **i3** and **i3status** under your `~.config` directory.
