# mkisofs

> Source: TLDR (MIT) — from 'vendor/tldr/'

# mkisofs

> Create ISO files from directories.
> Also aliased as `genisoimage`.
> More information: <https://manned.org/mkisofs>.

- Create an ISO from a directory:

`mkisofs -o {{filename.iso}} {{path/to/source_directory}}`

- Set the disc label when creating an ISO:

`mkisofs -o {{filename.iso}} -V "{{label_name}}" {{path/to/source_directory}}`

---
_Imported: 2026-04-10 08:21:52 UTC_
