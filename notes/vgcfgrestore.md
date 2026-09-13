# vgcfgrestore

> Source: TLDR (MIT) — from 'vendor/tldr/'

# vgcfgrestore

> Restore volume group configuration  (not user data) from a text back up file produced by `vgcfgbackup`.
> More information: <https://manned.org/vgcfgrestore>.

- Restore VG metadata from last backup.:

`vgcfgrestore {{vg_name}}`

- Restore VG metadata from specified backup-file:

`vgcfgrestore {{[-f|--file]}} {{path/to/file}} {{vg_name}}`

- List all VG metadata backups:

`vgcfgrestore {{[-l|--list]}} {{vg_name}}`

- List one VG metadata backup file:

`vgcfgrestore {{[-l|--list]}} {{[-f|--file]}} {{path/to/file}} {{vg_name}}`

---
_Imported: 2026-09-13 12:37:31 UTC_
