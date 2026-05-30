# fadvise

> Source: TLDR (MIT) — from 'vendor/tldr/'

# fadvise

> Control Linux file caching behavior.
> See also: `fincore`.
> More information: <https://manned.org/fadvise>.

- Preload a file or directory into cache:

`fadvise {{[-a|--advice]}} willneeded {{path/to/file_or_directory}}`

- Suggest dropping a file from cache:

`fadvise {{path/to/file}}`

- Display help:

`fadvise {{[-h|--help]}}`

---
_Imported: 2026-05-30 14:42:03 UTC_
