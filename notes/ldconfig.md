# ldconfig

> Source: TLDR (MIT) — from 'vendor/tldr/'

# ldconfig

> Configure symlinks and cache for shared library dependencies.
> More information: <https://manned.org/ldconfig>.

- Update symlinks and rebuild the cache (usually run when a new library is installed):

`sudo ldconfig`

- Update the symlinks for a given directory:

`sudo ldconfig -n {{path/to/directory}}`

- Print the libraries in the cache and check whether a given library is present:

`ldconfig {{[-p|--print-cache]}} | grep {{library_name}}`

---
_Imported: 2025-11-28 13:33:17 UTC_
