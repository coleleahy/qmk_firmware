To update keymap:
```
emacs ~/qmk_firmware/keyboards/massdrop/ctrl/keymaps/coleleahy/keymap.c
cd ~/qmk_firmware && qmk compile
cd ~/massdrop && ./mdloader_mac --first --download ~/qmk_firmware/.build/massdrop_ctrl_coleleahy.bin --restart
```
