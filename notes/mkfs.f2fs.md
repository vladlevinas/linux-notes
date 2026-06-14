# mkfs.f2fs

> Source: TLDR (MIT) — from 'vendor/tldr/'

# mkfs.f2fs

> Create an F2FS filesystem inside a partition.
> More information: <https://manned.org/mkfs.f2fs>.

- Create an F2FS filesystem inside partition Y on device X:

`sudo mkfs.f2fs {{/dev/sdXY}}`

- Create an F2FS filesystem with a volume label:

`sudo mkfs.f2fs -l {{volume_label}} {{/dev/sdXY}}`

---
_Imported: 2026-06-14 10:26:55 UTC_
