![image](infrastructure/docs/logo/swirl.jpg)

# swirlbuild

 *Rudimentary package build system for Debian Sid*

swirlbuild is a thin layer between `dh_make(1)`, `pbuilder(8)` and
`apt-ftparchive(1)` to allow creating and building minimally viable Debian
packages, without the usual paperwork and directory dance that comes with the
official method. It also maintains a local (file:///) repository to install
packages easily. Only Debian Sid (unstable) is supported.

swirlbuild totally integrates itself inside the Debian packages management
system, and does not need a bootstrap, just some Debian packages installed and
the swirlbuild tree.

It is heavily influenced by OpenBSD's ports collection, while some hints were
taken from Alpine's Abuild and CRUX's ports.

## Links

- The better [README](https://mascaldotfr.github.io/swirlbuild) in your browser;
if you are in a terminal and installed `swirlbuild-docs`, use `man 7 swirlbuild`

## Contact

- **IRC** [ircs://irc.oftc.net/#swirlbuild](ircs://irc.oftc.net/#swirlbuild)
- **FEDIVERSE** @mascal@thebus.top
