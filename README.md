
# Arch linux

# Packages

## Update

sudo pacman -Syu

sudo pacman -Syy

## Install Packages 

sudo pacman -S name.of.package

## To install a local package, or from a website:

sudo pacman -U /path/to/the/package

## To remove the package and those of its dependencies that aren’t needed by any other application, do

sudo pacman -Rs

## Finally, to remove the package, avoid orphaned dependencies and erase its global configuration, type

sudo pacman -Rns package_name

### which in most cases is the proper command to remove software.


## Info about an installed package:

pacman -Qi package_name

### Queries the repo about a package:

pacman -Ss package_name

## Queries the repo about a packages, and all that depend on it:

pacman -Sii package_nam

## Howto List Installed Packages that are not in the Official Repositories:

### If you want a list of the packages you build and installed locally or packages that are no longer in the official repositories:

pacman -Qm

### Make sure to check this regularly, preferably monthly but at least every three months. KaOS repositories are always moving so you don’t want to keep unmaintained and possibly conflicting packages in your install.

## Pacman is completely broken! How do I reinstall it?
### In the case that pacman is broken beyond repair, manually download the necessary packages (openssl, libarchive, and pacman) and extract them. The pacman binary will be restored along with its default configuration file. Afterwards, reinstall these packages with pacman to maintain package database integrity. You can use this command to extract them.

sudo tar -xwvpf <i>package_name-version.tar.xz</i> -C / --exclude .PKGINFO --exclude .INSTALL

## Package List

` nano man less joe neovim emacs screen git fish base-devel fzf neofetch tmux htop gnupg `

# Directories

gh


projects

# Files

