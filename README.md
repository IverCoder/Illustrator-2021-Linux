<sup>SPDX-FileCopyrightText: 2022 MiMillieuh <https://github.com/MiMillieuh>, 2024 IverCoder <https://github.com/IverCoder></sup>

<sup>SPDX-License-Identifier: BSD-3-Clause</sup>

# Adobe Illustrator 2021 installer

A script that installs Illustrator 2021 (v25) on Linux via Wine. Originally developed by [@MiMillieuh](https://github.com/MiMillieuh) [here](https://github.com/LinSoftWin/Illustrator-CC-2021-Linux), modified with working links.

## Requirements

Make sure the following packages are installed:

- Application Menu GTK+ Module (`appmenu-gtk3-module` on Ubuntu; `unity-gtk3-module` on Fedora; `appmenu-gtk-module` on Arch)
- Curl (`curl` on Ubuntu, Fedora, and Arch)
- Tar (`tar` on Ubuntu, Fedora, and Arch)
- Wget (`wget` on Ubuntu, Fedora, and Arch)
- Zenity (`zenity` on Ubuntu, Fedora, and Arch)

You can install them through these commands:

- Ubuntu: `sudo apt update && sudo apt install appmenu-gtk3-module curl tar wget zenity`
- Fedora: `sudo dnf install unity-gtk3-module curl tar wget zenity`
- Arch: `sudo pacman -S appmenu-gtk-module curl tar wget zenity`

## Usage

Download the installer script from the [latest release](https://github.com/IverCoder/Illustrator-2021-Linux/releases/latest), and run it via the terminal.

By default, Illustrator will be installed on `~/.WineApps`. If you want to change this, simply add your desired path as an argument. For example, `install-illustrator-2021.sh ~/.local/share/Adobe/Illustrator2021/`.

## Acknowledgements

Special thanks to:

- [@Gictorbit](https://github.com/Gictorbit)'s [Illustrator CC Installer for Linux](https://github.com/Gictorbit/illustratorCClinux) for an inspiration
- The WineHQ team for developing an outstanding emulation layer
- Adobe for developing Ilustrator