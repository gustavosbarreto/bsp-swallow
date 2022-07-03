# bsp-swallow

Used to swallow a terminal window with another application window
exactly over the terminals you start them from.

This project is based on [bspswallow](https://github.com/JopStro/bspswallow).

## Dependencies

* bspwm
* xprop

## Install

Copy [bsp-swallow](https://github.com/gustavosbarreto/bsp-swallow/blob/master/bsp-swallow) script to your PATH
and add the following line to your bspwmrc:

```
pgrep bsp-swallow || bsp-swallow &
```

## Usage

```
$ bsp-swallow command [args]
```



