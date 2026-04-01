# blkid

> Source: TLDR (MIT) — from 'vendor/tldr/'

# blkid

> List all recognized partitions and their Universally Unique Identifier (UUID).
> More information: <https://manned.org/blkid>.

- List all partitions:

`sudo blkid`

- List all partitions in a table, including current mountpoints:

`sudo blkid {{[-o|--output]}} list`

- Get the UUID of the filesystem on a partition:

`sudo blkid {{[-s|--match-tag]}} UUID {{[-o|--output]}} value {{/dev/sdXY}}`

---
_Imported: 2026-04-01 19:58:23 UTC_
