# reboot

> Source: TLDR (MIT) — from 'vendor/tldr/'

# reboot

> Reboot the system.
> More information: <https://manned.org/reboot.8>.

- Reboot the system:

`reboot`

- Power off the system (same as `poweroff`):

`reboot {{[-p|--poweroff]}}`

- Halt (terminates all processes and shuts down the CPU) the system (same as `halt`):

`reboot --halt`

- Reboot immediately without contacting the system manager:

`reboot {{[-f|--force]}}`

- Write the wtmp shutdown entry without rebooting the system:

`reboot {{[-w|--wtmp-only]}}`

---
_Imported: 2026-01-26 07:32:29 UTC_
