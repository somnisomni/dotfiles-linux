somni.dotfiles.linux
====================
This repository contains my personal dotfiles and configuration files for Linux systems.  
*(especially for Arch Linux or Arch-based distributions)*

Dotfiles are bootstrapped using [Dotbot](https://github.com/anishathalye/dotbot).

Bootstrap
---------
Make sure to have clone this repository with Dotbot submodule:

```sh
git clone --recurse-submodules
```

To bootstrap the dotfiles after clone, run the following command in the root of the repository:

```sh
./install
```

This will execute Dotbot's bootstrap script. For bootstrap configurations, refer to the [`install.conf.yaml`](install.conf.yaml) file.
