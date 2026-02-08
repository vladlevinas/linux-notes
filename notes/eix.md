# eix

> Source: TLDR (MIT) — from 'vendor/tldr/'

# eix

> Utilities for searching local Gentoo packages.
> Update local package cache using `eix-update`.
> More information: <https://wiki.gentoo.org/wiki/Eix>.

- Search for a package:

`eix {{query}}`

- Search for installed packages:

`eix --installed {{query}}`

- Search in package descriptions:

`eix --description "{{description}}"`

- Search by package license:

`eix --license {{license}}`

- Exclude results from search:

`eix --not --license {{license}}`

---
_Imported: 2026-02-08 07:40:31 UTC_
