# qm-shutdown

> Source: TLDR (MIT) — from 'vendor/tldr/'

# qm shutdown

> Shutdown a virtual machine on QEMU/KVM Virtual Machine Manager.
> More information: <https://pve.proxmox.com/pve-docs/qm.1.html>.

- Shutdown a virtual machine:

`qm {{[shu|shutdown]}} {{VM_ID}}`

- Shutdown a virtual machine after wait for at most 10 seconds:

`qm {{[shu|shutdown]}} --timeout {{10}} {{VM_ID}}`

- Shutdown a virtual machine and do not deactivate storage volumes:

`qm {{[shu|shutdown]}} --keepActive {{true}} {{VM_ID}}`

- Shutdown a virtual machine and skip lock (only root can use this option):

`qm {{[shu|shutdown]}} --skiplock {{true}} {{VM_ID}}`

- Stop and shutdown a virtual machine:

`qm {{[shu|shutdown]}} --forceStop {{true}} {{VM_ID}}`

---
_Imported: 2026-02-24 07:53:17 UTC_
