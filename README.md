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

In order to test this sound theme, click on "clone or download" then "Download Zip". You'll get a zip file with a folder named "WoodenBeaver-master" inside it. Just put this folder inside `.local/share/sounds/` and rename it `WoodenBeaver`. After that, to change your current desktop sound theme, you will need `dconf-editor` to change the setting key `/org/gnome/desktop/sound/theme-name/` to `WoodenBeaver`

### Testing input feedback sounds

In `dconf-editor`, change the key `/org/gnome/desktop/sound/input-feedback-sound` to `true` and enjoy more sounds to test.

---

This project is licensed under CC-BY-SA 3.0.
