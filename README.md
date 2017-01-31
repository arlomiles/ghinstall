# GHInstall
An installer for GitHub

## How to install
Ironically, this repository doesn't support GHInstall as an installation method (yet). To install, clone this repository and copy ```ghinst``` into your ```$PATH```.

## How to use
```ghinst <github repository>```
For example, if this repository supported GHInstall, you could run ```ghinst arlomiles/ghinstall```.

## How to set up your packages to use GHInstall
Put an ```install.sh``` file in the root directory of your GitHub repository. That's it. Any command-line arguments after the repository will be passed to ```install.sh```.

## TODO
- Come up with a standard for installation options (local/user/system, etc.)
- Allow the user to change the download location
- Uninstaller standard
- GHInstall support for this repository