# qm-showcmd

> Source: TLDR (MIT) — from 'vendor/tldr/'

# qm showcmd

> Show command-line which is used to start the VM (debug info).
> More information: <https://pve.proxmox.com/pve-docs/qm.1.html>.

- Show command-line for a specific virtual machine:

`qm {{[sho|showcmd]}} {{vm_id}}`

- Put each option on a new line to enhance human readability:

`qm {{[sho|showcmd]}} --pretty {{true}} {{vm_id}}`

- Fetch configuration values from a specific snapshot:

`qm {{[sho|showcmd]}} --snapshot {{string}} {{vm_id}}`

---
_Imported: 2025-11-22 19:17:40 UTC_
