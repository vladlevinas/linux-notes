# grubby

> Source: TLDR (MIT) — from 'vendor/tldr/'

# grubby

> Tool for configuring `grub` and `zipl` bootloaders.
> More information: <https://manned.org/grubby.8>.

- Add kernel boot arguments to all kernel menu entries:

`sudo grubby --update-kernel=ALL --args '{{quiet console=ttyS0}}'`

- Remove existing arguments from the entry for the default kernel:

`sudo grubby --update-kernel=DEFAULT --remove-args {{quiet}}`

- List all kernel menu entries:

`sudo grubby --info=ALL`

---
_Imported: 2026-09-01 17:14:14 UTC_
