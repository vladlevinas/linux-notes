# mkfs.ext4

> Source: TLDR (MIT) — from 'vendor/tldr/'

# mkfs.ext4

> Create an ext4 filesystem inside a partition.
> More information: <https://manned.org/mkfs.ext4>.

- Create an ext4 filesystem inside partition Y on device X:

`sudo mkfs.ext4 {{/dev/sdXY}}`

- Create an ext4 filesystem with a volume-label:

`sudo mkfs.ext4 -L {{volume_label}} {{/dev/sdXY}}`

---
_Imported: 2026-09-03 12:00:07 UTC_
