### About Zephyr

Zephyr is a synonym for Breeze, the default theme in most KDE distros. I made Zephyr mainly because I kinda liked the default theme, but the tray icons are ugly and there is usually no way to change tray icons without changing theme (they are bundled together). With Zephyr, almost everything will fallback to your chosen theme, except for desktop/tray icons (and optional color schemes) which are replaced with Materia/Papirus icons (slightly modified). This ensures minimal maintenance if changes are made upstream..

### Color Schemes

There are 2 color schemes, see screenshots below.

1. Zephyr Dark, a dark theme based on the Materia (Dark) color scheme. Replaced some of the grayish color with a darker one.
2. Zephyr Darker, a variant of Zephyr Dark where some elements are even darker (reduced background color variation).

### Screenshots

<p align="center">
  <img src="https://raw.githubusercontent.com/AndhikaWB/Zephyr-KDE/master/_docs/preview1.png" alt="Zephyr Dark Preview 1"/>
  <sup>Color Scheme: Zephyr Dark | Icon: Zephyr (Tray), Papirus (App) | Window Decoration: Klassy</sup>
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/AndhikaWB/Zephyr-KDE/master/_docs/preview2.png" alt="Zephyr Dark Preview 2"/>
  <sup>Color Scheme: Zephyr Dark (with Start Menu) | Icon: Zephyr (Tray), Papirus (App) | Window Decoration: Klassy</sup>
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/AndhikaWB/Zephyr-KDE/master/_docs/preview3.png" alt="Zephyr Darker Preview 1"/>
  <sup>Color Scheme: Zephyr Darker (with Start Menu) | Icon: Zephyr (Tray), Papirus (App) | Window Decoration: Klassy</sup>
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/AndhikaWB/Zephyr-KDE/master/_docs/preview4.png" alt="Breeze Dark Preview 1"/>
  <sup>Color Scheme: Breeze Dark | Icon: Zephyr (Tray), Papirus (App) | Window Decoration: Klassy</sup>
</p>

### Install Directories

Choose what you need:

- For plasma (desktop/tray) icons, copy matching folder to `~/.local/share/plasma`. For application icons, just use Papirus icons.
- For color scheme (bonus, optional), copy matching folder to `~/.local/share/color-schemes`
- For konsole theme (bonus, optional), copy matching folder to `~/.local/share/konsole`

### Change Start Menu Icon

The default start menu icon is Manjaro logo. Simply replace `~/.local/share/plasma/desktoptheme/Zephyr/icons/start.svg` with something else. The default KDE logo is also supplied, rename `start_kde.svg` to `start.svg` (replace if needed).