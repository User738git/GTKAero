# GTKAero
A fork of B00MERANG Project's Windows 7 GTK theme made to integrate better with aerothemeplasma. Also makes thunar look more Windows 7's explorer.
<img src="screenshots/save.png" alt="Desktop"/>
A picture of thunar with this theme and icon theme.

### Installation:
Put this repository into your "themes" folder and enable it in "Application style > Configure Gnome/GTK style" if using KDE.

Copy the "Windows 7 Aero" folder and replace it with aerothemeplasma's icon folder (merge them together).

KDE: To make the transparent background turn into titlebar blur, go into KDE's settings and then go to Window Management > Desktop Effects > Aero Glass Blur > Configure... > Overrides. Type in "thunar" (without the marks) into the "Classes of windows to force blur" class.

Disable inner borders: Go to Colours & Themes > Window Decorations and click on SMOD's "↻". Go to Window-Specific Overrides and add an exeption for thunar. Make sure to mark "hide window inner border"

In Thunar: align the toolbar buttons correctly and uncheck "menubar" (Or "Ctrl" + "M").

### Note:
The commandbar is only a texture and is not clickable in any way. 
Perhaps it might be possible to add such functionality in the future, but I am not considering it now.

### Supported platforms:
- Any GTK-based desktop
- Cinnamon
- Gnome
- MATE
- Xfce
- KDE

### Bugs + issues
- Some buttons might look strange.
- Not able to make the font in Thunar's sidebar normal or "not bold" yet.

### Forked code:
- [Windows 7 GTK](https://github.com/B00merang-Project/Windows-7)
- [Chicago95](https://github.com/grassmunk/chicago95) (Some thunar code).
- [aerothemeplasma](https://gitgud.io/wackyideas/aerothemeplasma/) (Icon theme).
