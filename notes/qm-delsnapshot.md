# qm-delsnapshot

> Source: TLDR (MIT) — from 'vendor/tldr/'

# qm delsnapshot

> Delete virtual machine snapshots.
> More information: <https://pve.proxmox.com/pve-docs/qm.1.html>.

- Delete a snapshot:

`qm {{[del|delsnapshot]}} {{vm_id}} {{snapshot_name}}`

- Delete a snapshot from a configuration file (even if removing the disk snapshot fails):

`qm {{[del|delsnapshot]}} {{vm_id}} {{snapshot_name}} --force 1`

---
_Imported: 2026-02-05 14:06:47 UTC_
