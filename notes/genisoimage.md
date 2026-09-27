# genisoimage

> Source: TLDR (MIT) — from 'vendor/tldr/'

# genisoimage

> Pre-mastering program to generate ISO9660/Joliet/HFS hybrid filesystems.
> More information: <https://manned.org/genisoimage.1>.

- Create an ISO image from the given source directory:

`genisoimage -o {{myimage.iso}} {{path/to/source_directory}}`

- Create an ISO image with files larger than 2GiB by reporting a smaller apparent size for ISO9660 filesystems:

`genisoimage -o -allow-limited-size {{myimage.iso}} {{path/to/source_directory}}`

---
_Imported: 2026-09-27 17:36:29 UTC_
