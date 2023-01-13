# Unmaintained swirls

They are kept as examples or tests and may not build in the future, or may
clash with future Debian packages.

Also many design changes occurred and some build files are not up to the
current standard seen in swirlbuild/swirls.

## badwolf
F: patch, rules
Used as a demo in swirlbuild.5, a privacy oriented browser
## emote
F: python, patch, install, dh-python
An emoji picker written in python
## findfiles
F: rust, Makefile injection, prebuild hook
Find files according to a given pattern
## gawk-timex
F: test
The timex extension for gawk; first dlopen()'d library built with swirlbuild. Notably add sleep and strptime to gawk.
## golang-helloworld
F: prebuild hook, golang, dh-golang
A simple hello world web app listening on port 9100
## justsomefiles
F: download hook, arbitrary files install
Installing arbitrary files. This one is frequently asked for according to $SEARCHENGINE. Used in swirlbuild.5
