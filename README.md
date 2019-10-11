# My build of the [suckless terminal (st)](https://st.suckless.org/)
This build doesnt fetch the color theme from the Xressource. If you want to change it, you'll have to modify the `config.h`. This build use the [Nord Theme](https://www.nordtheme.com/).
## How to install
```
git clone https://github.com/Polensky/st
cd st
sudo make clean install
```

## How to use
|  Keybinding | Description |
| --- | --- |
|`alt-j/k` | zoom out/in |
|`alt-0` | reset zoom |
|`alt-l` | open urls in default browser with dmenu |
|`alt-c/v` | copy/paste |
|`alt-pageup/pagedown` | scroll up/down |
