# vgextend

> Source: TLDR (MIT) — from 'vendor/tldr/'

# vgextend

> Add one or more physical volumes to an existing volume group.
> More information: <https://manned.org/vgextend>.

- Add a physical volume to an existing volume group:

`vgextend {{vg1}} {{/dev/sda1}}`

- Add multiple physical volumes to an existing volume group:

`vgextend {{vg1}} {{/dev/sda1 /dev/sda2 ...}}`

---
_Imported: 2026-10-10 13:26:00 UTC_
