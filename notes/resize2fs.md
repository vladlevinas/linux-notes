# resize2fs

> Source: TLDR (MIT) — from 'vendor/tldr/'

# resize2fs

> Resize an ext2, ext3 or ext4 filesystem.
> Does not resize the underlying partition. The filesystem may have to be unmounted first, read the man page for more details.
> More information: <https://manned.org/resize2fs>.

- Automatically resize a filesystem to its maximum possible size:

`resize2fs {{/dev/sdXN}}`

- Resize the filesystem to a size of 40G, displaying a progress bar:

`resize2fs -p {{/dev/sdXN}} {{40G}}`

- Shrink the filesystem to its minimum possible size:

`resize2fs -M {{/dev/sdXN}}`

---
_Imported: 2026-04-02 19:51:44 UTC_
