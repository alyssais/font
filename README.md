font
====

A command-line font manager.

Installing
----------

```
$ git clone ttps://github.com/rosspenman/font.git
$ cd font/
```

Usage
-----

### Show all available fonts

`$ ./font list`

### Show information for a particular font

`$ ./font show "Droid Sans"`

### Install fonts

Fonts will be installed at `~/Library/Fonts`, but this will soon be configurable.

`$ ./font install "Droid Sans"`

You can specify a variant (available variants are shown with `$ ./font show <name>`).

`$ ./font install "Droid Sans" 700`

You can also install all fonts. (May take a while).

`$ ./font install all`

### Uninstall fonts

`$ ./font uninstall "Droid Sans"`

You can specify a variant (available variants are shown with `$ ./font show <name>`).

`$ ./font uninstall "Droid Sans" 700`

You can also uninstall all fonts.

`$ ./font uninstall all`
