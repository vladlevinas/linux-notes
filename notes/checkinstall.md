# checkinstall

> Source: TLDR (MIT) — from 'vendor/tldr/'

# checkinstall

> Track the local installation of a software package, and produce a binary package which can be used with a system's native package manager.
> More information: <https://checkinstall.izto.org/docs.php>.

- Create and install a package with default settings:

`sudo checkinstall {{[-y|--default]}}`

- Create a package but don't install it:

`sudo checkinstall --install={{no}}`

- Create a package without documentation:

`sudo checkinstall --nodoc`

- Create a package and set the name:

`sudo checkinstall --pkgname {{package}}`

- Create a package and specify where to save it:

`sudo checkinstall --pakdir {{path/to/directory}}`

---
_Imported: 2026-11-04 15:15:01 UTC_
