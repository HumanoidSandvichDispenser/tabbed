 Serhan's tabbed

## This build mainly includes these features

* Live reloading colors from Xresources on fly with `kill -s USR1 $(pidof tabbed)`.
* Hiding tabs on key release.

And many more customizations, tiny features and optimizations. I tried to make all these features highly customizable on fly with live Xresources reloading. Check my [dotfiles](https://github.com/serhanekicii/dotfiles). This is suckless software, commits and source code is your documentation check them for more info about what this build includes.

## Dependencies

In order to build tabbed you need the Xlib header files.

## Build & Install

```Shell
make
make install
```
