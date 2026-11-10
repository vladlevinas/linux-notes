# vgscan

> Source: TLDR (MIT) — from 'vendor/tldr/'

# vgscan

> Scan for volume groups on all supported Logical Volume Manager (LVM) block devices.
> See also: `lvm`, `vgchange`.
> More information: <https://manned.org/vgscan>.

- Scan for volume groups and print information about each group found:

`sudo vgscan`

- Scan for volume groups and add the special files in `/dev`, if they don't already exist, needed to access the logical volumes in the found groups:

`sudo vgscan --mknodes`

---
_Imported: 2026-11-10 15:28:13 UTC_
