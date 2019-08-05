# aur-get
Very basic AUR handler.

## Configuration
`aur-get` looks towards $HOME/.aur-get for configuration. The current accepted variables are:
- aurdir: This is the directory aur-get clones AUR repositories into. This defaults to $HOME/aur
- desktopType: This defines the desktop environment you're choosing to use. Currently, only `plasma` is a valid value and invokes `kbuildsycoca5` at the end of an installation.

```# This defines the directory that aur-get will use to store AUR repos. Defaults to "~/aur".
aurdir="$HOME/aur"

# What type of desktop environment do you have? Valid values are "plasma". Used to rebuild icon cache after installation of a new package.
desktopType="plasma"```
