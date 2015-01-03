---
permalink: /projects/auryea/
title: auryea
layout: default
---

# auryea

[github.com/darvid/auryea](http://github.com/darvid/auryea) --
[PKGBUILD](https://aur.archlinux.org/packages/auryea-hg/)

*auryea* is a package management tool for [Archlinux][3]. It wraps [pacman][1]
and provides the ability to search user packages in [AUR][2], download their
PKGBUILDs, and build and install them automatically.

*auryea* is written in bash so it requires zero dependencies.

**Please note that  *auryea* is not actively maintained.**


## Usage
Exactly as you would [pacman][1]. *auryea* can be configured to wrap pacman or
behave as a standalone package manager of sorts entirely for [AUR][2].

## Configuration
*auryea* is configured entirely through environment variables. To make settings
persist, simply ``export`` the variables in your ``~/.bash_profile``,
``~/.zshrc``, ``~/.profile``, or ``/etc/profile``.

[1]: https://wiki.archlinux.org/index.php/Pacman
[2]: http://aur.archlinux.org
[3]: http://archlinux.org
