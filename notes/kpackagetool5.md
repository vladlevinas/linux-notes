# kpackagetool5

> Source: TLDR (MIT) — from 'vendor/tldr/'

# kpackagetool5

> KPackage Manager: install, list, remove Plasma packages.
> More information: <https://manned.org/kpackagetool5>.

- List all known package types that can be installed:

`kpackagetool5 --list-types`

- Install the package from a directory:

`kpackagetool5 {{[-t|--type]}} {{package_type}} {{[-i|--install]}} {{path/to/directory}}`

- Update installed package from a directory:

`kpackagetool5 {{[-t|--type]}} {{package_type}} {{[-u|--upgrade]}} {{path/to/directory}}`

- List installed plasmoids (`--global` for all users):

`kpackagetool5 {{[-t|--type]}} Plasma/Applet {{[-l|--list]}} {{[-g|--global]}}`

- Remove a plasmoid by name:

`kpackagetool5 {{[-t|--type]}} Plasma/Applet {{[-r|--remove]}} "{{name}}"`

---
_Imported: 2025-11-17 19:19:02 UTC_
