# systemctl-stop

> Source: TLDR (MIT) — from 'vendor/tldr/'

# systemctl stop

> Stop systemd units.
> More information: <https://www.freedesktop.org/software/systemd/man/systemctl.html#stop%20PATTERN%E2%80%A6>.

- Stop a unit:

`systemctl stop {{unit}}`

- Stop a service and suppress warnings:

`systemctl stop {{unit}} --no-warn`

- Stop a user unit:

`systemctl stop {{unit}} --user`

---
_Imported: 2026-05-08 08:22:51 UTC_
