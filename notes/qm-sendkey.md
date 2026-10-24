# qm-sendkey

> Source: TLDR (MIT) — from 'vendor/tldr/'

# qm sendkey

> Send QEMU monitor encoding key event to a virtual machine.
> More information: <https://pve.proxmox.com/pve-docs/qm.1.html>.

- Send the specified key event to a specific virtual machine:

`qm {{[sen|sendkey]}} {{vm_id}} {{key}}`

- Allow root user to send key event and ignore locks:

`qm {{[sen|sendkey]}} --skiplock {{true}} {{vm_id}} {{key}}`

---
_Imported: 2026-10-24 16:27:58 UTC_
