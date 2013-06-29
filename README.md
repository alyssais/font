font
====

A command-line font manager
Fonts will be installed at `~/Library/Fonts`, but this will soon be configurable.

Usage
-----

### Show all available fonts

`$ ./font list`

### Show information for a particular font

`$ ./font show "Droid Sans"`

### Install fonts

`$ ./font install "Droid Sans"`

You can specify a variant (available variants are shown with `$ ./font show <name>`.

`$ ./font install "Droid Sans" 700`

You can also install all fonts. (May take a while).

`$ ./font install all`

### Uninstall fonts

`$ ./font uninstall "Droid Sans"`

You can specify a variant (available variants are shown with `$ ./font show <name>`.

`$ ./font uninstall "Droid Sans" 700`

You can also uninstall all fonts.

`$ ./font uninstall all`
