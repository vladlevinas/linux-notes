# pvcreate

> Source: TLDR (MIT) — from 'vendor/tldr/'

# pvcreate

> Initialize a disk or partition for use as a physical volume.
> See also: `lvm`.
> More information: <https://manned.org/pvcreate>.

- Initialize the `/dev/sda1` volume for use by LVM:

`pvcreate {{/dev/sdXY}}`

- Force the creation without any confirmation prompts:

`pvcreate {{[-f|--force]}} {{/dev/sdXY}}`

---
_Imported: 2026-02-25 07:55:04 UTC_
