# Jocadbz's Arch Repo

## About This Repository

Welcome to joca-arch-repo! This is a personal Arch Linux repository where I host various packages that I maintain or find useful.

Feel free to explore the packages section and follow the installation instructions to add this repository to your system.

## Packages

- ### example-package
  A sample package demonstrating the listing format.
  [source](#) | [pkgbuild](#)

- ### another-package
  Description for another package you might host.
  [source](#) | [pkgbuild](#)

*(More packages will be listed here soon!)*

## Installation Instructions

To add joca-arch-repo to your system, follow these steps:

```bash
sudo pacman-key --recv-key B1836DCE2F50BDF7 --keyserver keyserver.ubuntu.com
sudo pacman-key --lsign-key B1836DCE2F50BDF7
```
This will add all the necessary keys.

Then, add the following to your `/etc/pacman.conf`:

```
[joca-arch-repo]
Server = https://repo.jocadbz.xyz/x86_64
```

Finally, synchronize your package databases and upgrade your system:

```bash
sudo pacman -Syu
```
