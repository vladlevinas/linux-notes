# systemctl-enable

> Source: TLDR (MIT) — from 'vendor/tldr/'

# systemctl enable

> Enable systemd services.
> More information: <https://www.freedesktop.org/software/systemd/man/systemctl.html#enable%20UNIT%E2%80%A6>.

- Enable a service to run on boot:

`systemctl enable {{unit}}`

- Enable a service to run on boot and start it now:

`systemctl enable {{unit}} --now`

- Enable a user unit to run on login:

`systemctl enable {{unit}} --user`

---
_Imported: 2026-10-06 00:40:50 UTC_
