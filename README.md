## Tela Icon Theme
A flat colorful Design icon theme

![Tela](../master/tela-dark.png)
![Tela](../master/tela-light.png)
![Tela](../master/folders.png)
## Installation

Usage:  `./install.sh`  **[OPTIONS...]** **[COLOR VARIANTS...]**

eg.. to install noctis color variant `./install.sh noctis`


|  OPTIONS: |                                                                               |
|:----------|:------------------------------------------------------------------------------|
| -a        | Install all color versions                                                    |
| -d        | Specify theme destination directory (**Default:** _$HOME/.local/share/icons_) |
| -n        | Specify theme name (**Default:** _Tela_)                                      |
| -h        | Show this help                                                                |

|  COLOR VARIANTS |                                       |
|:----------------|:--------------------------------------|
| standard        | Standard color folder version         |
| black           | Black color folder version            |
| blue            | Blue color folder version             |
| brown           | Brown color folder version            |
| green           | Green color folder version            |
| grey            | Grey color folder version             |
| noctis          | Noctis color folder version           |
| orange          | Orange color folder version           |
| pink            | Pink color folder version             |
| purple          | Purple color folder version           |
| red             | Red color folder version              |
| yellow          | yellow color folder version           |
| manjaro         | Manjaro default color folder version  |
| ubuntu          | Ubuntu default color folder version   |

By default, only **the standard one** is selected.

### On Snapcraft

<a href="https://snapcraft.io/tela-icons">
<img alt="Get it from the Snap Store" src="https://snapcraft.io/static/images/badges/en/snap-store-black.svg" />
</a>

You can install the theme from the Snap Store оr by running:

```
sudo snap install tela-icons
```
To connect the theme to an app run:
```
sudo snap connect [other snap]:icon-themes tela-icons:icon-themes
```

### On Gentoo Linux

First, you can add [Beatussum's overlay](https://github.com/beatussum/beatussum-overlay) by using [Layman](https://wiki.gentoo.org/wiki/Layman):

```bash
layman --list
layman --add  beatussum-overlay
layman --sync beatussum-overlay
```

And install the _x11-themes/tela-icon-theme_ package.
