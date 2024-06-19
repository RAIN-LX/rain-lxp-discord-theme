[light]:        https://user-images.githubusercontent.com/29710355/229367843-ad03f107-ad47-4c63-9692-89cd781d40f8.png
[dark]:         https://user-images.githubusercontent.com/29710355/229367846-78bf3675-a091-4f60-8ff0-4427697a2ef2.png
[customised]:   https://github.com/Saltssaumure/xp-discord-theme/assets/29710355/e076daf4-23d5-40f2-9a86-ca3fdf0e251c

[bsod-text]:    https://github.com/Saltssaumure/xp-discord-theme/blob/main/scss/top/_vars-scss.scss
[addons]:       https://github.com/Saltssaumure/xp-discord-theme/tree/main/addon

[css-color]:        https://developer.mozilla.org/en-US/docs/Web/CSS/color_value
[discord]:          https://discord.gg/uy8nKQVatp

[BetterDiscord]:    https://betterdiscord.app/
[Replugged]:        https://replugged.dev/
[Vencord]:          https://github.com/Vendicated/Vencord

[shield-donate]:    https://img.shields.io/badge/Donate-ko--fi-orange?style=flat-square&logo=kofi&logoColor=orange
[ko-fi]:            https://ko-fi.com/saltssaumure "Buy me a coffee!"

[shield-bd-dl]:     https://img.shields.io/github/downloads/Saltssaumure/xp-discord-theme/Exponent.theme.css?color=purple&label=Downloads&style=flat-square
[shield-asar-dl]:   https://img.shields.io/github/downloads/Saltssaumure/xp-discord-theme/net.saltssaumure.Exponent.asar?color=purple&label=Downloads&style=flat-square
[shield-repo-size]: https://img.shields.io/github/repo-size/Saltssaumure/xp-discord-theme?label=Repository&style=flat-square "Total size"

[github]:           https://github.com/Saltssaumure/xp-discord-theme
[license]:          https://github.com/Saltssaumure/xp-discord-theme/blob/main/LICENSE
[issues]:           https://github.com/Saltssaumure/xp-discord-theme/issues
[.theme.css]:       https://github.com/Saltssaumure/xp-discord-theme/blob/main/Exponent.theme.css

[release-bd]:       https://betterdiscord.app/theme/?id=823 "BetterDiscord store page"
[release-bd-gh]:    https://github.com/Saltssaumure/xp-discord-theme/releases/latest/download/Exponent.theme.css "Get latest release"
[release-rp]:       https://replugged.dev/store/net.saltssaumure.Exponent "Replugged store page"
[release-rp-gh]:    https://github.com/Saltssaumure/xp-discord-theme/releases/latest/download/net.saltssaumure.Exponent.asar "Get latest release"

# Exponent Discord Theme
[![Buy me a coffee on ko-fi][shield-donate]][ko-fi]
[![BetterDiscord GitHub downloads][shield-bd-dl]][release-bd-gh]
[![Replugged GitHub downloads][shield-asar-dl]][release-rp-gh]
[![Total repository size][shield-repo-size]][github]

***A Windows XP style Discord theme.***

| Light mode                                                      | Dark mode                                                    |
| --------------------------------------------------------------- | ------------------------------------------------------------ |
| ![Screenshot of Exponent light mode applied to Discord ][light] | ![Screenshot of Exponent dark mode applied to Discord][dark] |

## Installation

### [BetterDiscord][BetterDiscord]
1. Download `Exponent.theme.css`:
    - [BetterDiscord store][release-bd]
    - [GitHub][release-bd-gh]
2. Place the file in the themes folder:
    - `Settings` > `BetterDiscord` > `Themes` > `Open Themes Folder`
3. Toggle on the theme card.

### [Replugged][Replugged]
#### Automatic
1. Click to install:
    - [Replugged store][release-rp]
#### Manual
1. Download `net.saltssaumure.Exponent.asar`:
    - [GitHub][release-rp-gh]
2. Place the file in the themes folder:
    - `Settings` > `Replugged` > `Themes` > `Open Themes Folder`
3. Click `Load Missing Themes` and toggle on the theme card.

### [Vencord][Vencord]
#### Local
1. Download `Exponent.theme.css`:
    - [BetterDiscord store][release-bd]
    - [GitHub][release-bd-gh]
2. Place the file in the themes folder:
    - `Settings` > `Vencord` > `Themes` > `Local Themes` > `Open Themes Folder`
3. Click `Load missing Themes` and toggle on the theme card.
#### Online
1. Paste the link in `Settings` > `Vencord` > `Themes` > `Online Themes`:
    - `https://saltssaumure.github.io/xp-discord-theme/Exponent.theme.css`

## Customisation

![Screenshot of Exponent with customised colours][customised]

| Description                 | Variable name                      | Valid values                                     | Default value                                                         |
| --------------------------- | ---------------------------------- | ------------------------------------------------ | --------------------------------------------------------------------- |
| Background image            | `--xp-background-image`            | Any image link encased in `url()`.               | `url(https://saltssaumure.github.io/xp-discord-theme/img/bliss.avif)` |
| Background colour           | `--xp-background-color`            | Any [colour][css-color].                         | `#003300`                                                             |
| Window titlebar colours     | `--xp-window-color-1`, `-2`        | Any [colour][css-color].                         | `#005AE7`, `#0372FF`                                                  |
| Taskbar control colours     | `--xp-taskbar-color-1`, `-2`, `-3` | Any [colour][css-color].                         | `#108CE4`, `#578CD0`, `#1665CA`                                       |
| Start button colours        | `--xp-start-color-1`, `-2`         | Any [colour][css-color].                         | `#008000`, `#38C438`                                                  |
| Shortcut icon colours       | `--xp-shortcut-color-1`, `-2`      | Any [colour][css-color].                         | `#0CA80C`, `#008000`                                                  |
| Ping bubble colour          | `--xp-ping-color`                  | Any [colour][css-color].                         | `#E64D1C`                                                             |
| BSOD background colour      | `--bsod-color`                     | Any [colour][css-color].                         | `navy`                                                                |
| BSOD text                   | `--bsod-text`                      | Any quoted text. Use `\A` for new lines.         | [Read here][bsod-text].                                               |
| Panel background colour     | `--xp-bg-color`                    | Any [colour][css-color].                         | `#000` (dark) / `#FFF` (light)                                        |
| Panel settings icon colour  | `--xp-set-color`                   | Any [colour][css-color], preferably translucent. | `#FFFFFFB3` (dark) / `#000000B3` (light)                              |
| Panel hovered item colour   | `--xp-hover-color`                 | Any [colour][css-color].                         | `#102030` (dark) / `#D3D3D3` (light)                                  |
| Panel top decoration colour | `--xp-zing-color`                  | Any [colour][css-color].                         | `#A05000` (dark) / `#FFA500` (light)                                  |
| Panel text colour           | `--xp-txt-color`                   | Any [colour][css-color].                         | `#FFF` (dark) / `#000` (light)                                        |
| Button highlight colour     | `--xp-bg-bright-color`             | Any [colour][css-color].                         | `#203040` (dark) / `#F0EFED` (light)                                  |
| Button background colour    | `--xp-bg-tint-color`               | Any [colour][css-color].                         | `#202020` (dark) / `#EBE8D7` (light)                                  |
| Button shadow colour        | `--xp-bg-shade-color`              | Any [colour][css-color].                         | `#101010` (dark) / `#808080` (light)                                  |
| Button/panel border colour  | `--xp-border-color`                | Any [colour][css-color].                         | `#1665CA` (dark) / `#000000` (light)                                  |

### BetterDiscord
1. Open `Settings` > `BetterDiscord` > `Themes`.
2. Click the pencil icon on this theme.
3. Edit the variable values and save changes.

### Replugged
1. Enable `Automatically Apply Quick CSS` in `Settings` > `Replugged` > `General`.
1. Open `Settings` > `Replugged` > `Quick CSS`.
3. Copy and paste lines 15-57 of [`Exponent.theme.css`][.theme.css].
3. Edit the variable values and save.

### Vencord
#### Local
2. `Open Themes Folder` in `Settings` > `Vencord` > `Themes` > `Local Themes`
3. Open `Exponent.theme.css` with your favourite text editor.
4. Edit the variable values and save.
#### Online
1. `Enable Custom CSS` in `Settings` > `Vencord` > `Vencord` and click `Open QuickCSS File`.
2. Copy and paste lines 15-57 of [`Exponent.theme.css`][.theme.css].
3. Edit the variable values.

## Addons
See [Addons][addons] for mini-themes designed to be used alongside Exponent to add extra optional features.

## License
Copyright (c) 2022-2024 Saltssaumure

This theme is free software: you can redistribute it and/or modify it under the terms of the GNU Affero General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This theme is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the [GNU Affero General Public License][license] for more details.

## Credits
### Assets
[bliss]:    https://archive.org/details/windows-xp-bliss-wallpaper

- [Bliss][bliss] by Microsoft (Charles O'Rear)

## Questions or suggestions?
- Post [an issue][issues] on GitHub.
- Post in `#theme-support` on [my support server][discord].