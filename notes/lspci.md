# lspci

> Source: TLDR (MIT) — from 'vendor/tldr/'

# lspci

> List all PCI devices.
> More information: <https://manned.org/lspci>.

- Show a brief list of devices:

`lspci`

- Display [v]erbose information (Note: the `-v` flag can be repeated to increase verbosity):

`lspci -v`

- Display [k]ernel drivers and modules handling each device:

`lspci -k`

- [s]elect a specific device:

`lspci -s {{00:18.3}}`

- Dump info in a ([m]achine) readable form:

`lspci -vm`

- Show PCI vendor and device codes as both [n]umbers and [n]ames:

`lspci -nn`

---
_Imported: 2026-02-10 20:01:07 UTC_
