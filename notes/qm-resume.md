# qm-resume

> Source: TLDR (MIT) — from 'vendor/tldr/'

# qm resume

> Resume a virtual machine.
> More information: <https://pve.proxmox.com/pve-docs/qm.1.html>.

- Resume a specific virtual machine:

`qm {{[resu|resume]}} {{vm_id}}`

- Resume a specific virtual machine ignoring locks (requires root):

`sudo qm {{[resu|resume]}} {{vm_id}} --skiplock true`

---
_Imported: 2026-01-18 07:24:22 UTC_
