# swapoff

> Source: TLDR (MIT) — from 'vendor/tldr/'

# swapoff

> Disable devices and files for swapping.
> Note: `path/to/file` can either point to a regular file or a swap partition.
> More information: <https://manned.org/swapoff.8>.

- Disable a given swap area:

`sudo swapoff {{path/to/file}}`

- Disable all swap areas in `/proc/swaps`:

`sudo swapoff {{[-a|--all]}}`

- Disable a swap partition by its label:

`sudo swapoff -L {{label}}`

---
_Imported: 2025-12-29 19:20:10 UTC_
