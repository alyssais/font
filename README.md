font
====

A command-line font manager for Google Web Fonts.

Installing
----------

```sh
$ git clone https://github.com/rosspenman/font.git
$ cd font/
$ sudo rake # May not need to sudo, but it can't hurt.
```

Uninstalling
------------

```sh
$ rake uninstall
```

Usage
-----

### Show all available fonts

```sh
$ font list
```

You can also show the fonts you currently have installed:

```sh
$ font list installed
```

Or fonts that are currently not installed.

```sh
$ font list not_installed
```

### Show information for a particular font

```sh
$ font show "Droid Sans"
```

### Preview a font in a web browser

```sh
$ font preview "Droid Sans"
```

### Install fonts

Fonts will be installed at `~/Library/Fonts` by default, but this can be changed by setting the `FONT_PATH` environment variable.

The default font path is compatible with OS X.

```sh
$ font install "Droid Sans"
```

You can specify a variant (available variants are shown with `$ font show <name>`).

```sh
$ font install "Droid Sans" 700
```

You can also install all fonts. (May take a while).

```sh
$ font install all
```

### Uninstall fonts

```sh
$ font uninstall "Droid Sans"
```

You can specify a variant (available variants are shown with `$ font show <name>`).

```sh
$ font uninstall "Droid Sans" 700
```

You can also uninstall all fonts.

```sh
$ font uninstall all
```
