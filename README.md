# The WoodenBeaver sound theme

![Wooden](/banner.jpg)

The WoodenBeaver sound theme is a proposal for new default system sounds for Ubuntu 18.04. 
The intention was to create a cohesive set of sounds that will enhance the user experience without getting in the way.
The WoodenBeaver sounds are played on a wooden percussion instrument to give the theme an african feeling. 
To make the theme feel light and responsive, the sounds are short and there's no reverb or delay added.

Enjoy!
_MadsRH_

---

## How to test it

### Installation instruction

You can install WoodenBeaver from source using the Meson build system.

````
meson builddir --prefix=/usr
sudo ninja -C builddir install
````

### How to activate the theme

To change your current desktop sound theme, you can use `dconf-editor` to change the setting key `/org/gnome/desktop/sound/theme-name/` to `WoodenBeaver`

### Testing input feedback sounds

In `dconf-editor`, change the key `/org/gnome/desktop/sound/input-feedback-sound` to `true` and enjoy more sounds to test.

---

This project is licensed under CC-BY-SA 3.0.

The meson script and the build instruction are taken from the [Suru icon theme](https://github.com/snwh/suru-icon-theme)
