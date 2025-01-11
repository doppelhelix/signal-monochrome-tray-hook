## signal-monochrome-tray-hook
#### (for arch based systems only)

This script will change the tray-icons of [signal-desktop](https://archlinux.org/packages/extra/x86_64/signal-desktop/)
 to monochrome.

Unfortunately this is now limited to dark themes. see github issues [7082](https://github.com/signalapp/Signal-Desktop/issues/7082)
 and [7095](https://github.com/signalapp/Signal-Desktop/issues/7095)

This script depends on

- [asar](https://archlinux.org/packages/extra/any/asar/)
- [librsvg](https://archlinux.org/packages/extra/x86_64/librsvg/)
- [papirus-icon-theme](https://archlinux.org/packages/extra/any/papirus-icon-theme/)

There is also a [pacman hook](https://wiki.archlinux.org/title/Pacman#Hooks) for automating this process on every update of [signal-desktop](https://archlinux.org/packages/extra/x86_64/signal-desktop/)

