# pvesh

> Source: TLDR (MIT) — from 'vendor/tldr/'

# pvesh

> Interface with the Proxmox VE API.
> More information: <https://pve.proxmox.com/pve-docs/pvesh.1.html>.

- List available nodes:

`pvesh {{[g|get]}} /nodes`

- Display detailed information about containers or virtual machines:

`pvesh {{[g|get]}} /nodes/{{node_name}}/{{lxc|qemu}}`

- Discover API paths:

`pvesh {{[l|ls]}} {{/}}`

- Display API path usage instructions:

`pvesh {{[u|usage]}} {{/pools}}`

---
_Imported: 2026-07-13 15:43:10 UTC_
