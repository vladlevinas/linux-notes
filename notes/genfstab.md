# genfstab

> Source: TLDR (MIT) — from 'vendor/tldr/'

# genfstab

> Generate output suitable for addition to the `/etc/fstab` file.
> More information: <https://manned.org/genfstab>.

- Generate the `/etc/fstab` file using volume UUIDs during an Arch Linux installation (requires root permissions):

`genfstab -U {{/mnt}} >> {{/mnt/etc/fstab}}`

- Display fstab-compatible output based on volume labels:

`genfstab -L {{path/to/mount_point}}`

- Display fstab-compatible output based on volume UUIDs:

`genfstab -U {{path/to/mount_point}}`

- Display fstab-compatible output based on the specified identifier:

`genfstab -t {{LABEL|UUID|PARTLABEL|PARTUUID}}`

- Append a volume into the `/etc/fstab` file to mount it automatically:

`genfstab -U {{path/to/mount_point}} | sudo tee -a /etc/fstab`

---
_Imported: 2026-05-31 14:49:03 UTC_
