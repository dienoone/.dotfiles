# .dotfiles

### Prerequisties:
1. `JetBrainsMono` (you can change it in the **fonts.ini** file), you can download and install from [NerdFonts](https://www.nerdfonts.com/font-downloads) or, you can use this script [font-installation](https://gist.github.com/Elteoremadebeethoven/8309ab77a24b77cbb3f3a253c3ede0d4). `Don't forget to change the font and version`.

2. Also you'll need [MaterialIcons](https://github.com/google/material-design-icons) and [Feather](https://feathericons.com/).
You can move both **MaterialIcons** and **feather** inside **fonts** to **$HOME/.local/share/fonts/** and run: 

```bash
mv fonts/feather/Feather.ttf $HOME/.local/share/fonts/
mv fonts/MaterialIcons/Mat* $HOME/.local/share/fonts/ 
fc-cache -fv
```
