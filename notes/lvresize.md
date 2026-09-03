# lvresize

> Source: TLDR (MIT) — from 'vendor/tldr/'

# lvresize

> Change the size of a logical volume.
> See also: `lvm`.
> More information: <https://manned.org/lvresize>.

- Change the size of a logical volume to 120 GB:

`lvresize {{[-L|--size]}} 120G {{volume_group}}/{{logical_volume}}`

- Extend the size of a logical volume as well as the underlying filesystem by 120 GB:

`lvresize {{[-L|--size]}} +120G {{[-r|--resizefs]}} {{volume_group}}/{{logical_volume}}`

- Extend the size of a logical volume to 100% of the free physical volume space:

`lvresize {{[-l|--extents]}} 100%FREE {{volume_group}}/{{logical_volume}}`

- Reduce the size of a logical volume as well as the underlying filesystem by 120 GB:

`lvresize {{[-L|--size]}} -120G {{[-r|--resizefs]}} {{volume_group}}/{{logical_volume}}`

---
_Imported: 2026-09-03 21:35:35 UTC_
