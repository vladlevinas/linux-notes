# openrc

> Source: TLDR (MIT) — from 'vendor/tldr/'

# openrc

> The OpenRC service manager.
> See also: `rc-status`, `rc-update`, `rc-service`.
> More information: <https://wiki.gentoo.org/wiki/OpenRC>.

- Change to a specific runlevel:

`sudo openrc {{runlevel_name}}`

- Change to a specific runlevel, but don't stop any existing services:

`sudo openrc {{[-n|--no-stop]}} {{runlevel_name}}`

---
_Imported: 2025-11-15 13:27:41 UTC_
