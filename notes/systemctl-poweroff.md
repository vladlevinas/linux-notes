# systemctl-poweroff

> Source: TLDR (MIT) — from 'vendor/tldr/'

# systemctl-poweroff

> Power off the system.
> See also: `poweroff`.
> More information: <https://www.freedesktop.org/software/systemd/man/systemctl.html#poweroff>.

- Power off the system:

`systemctl poweroff`

- Power off the system immediately without asking services to stop gracefully:

`systemctl poweroff --force`

- Power off the system immediately without sending notifications to logged-in users:

`systemctl poweroff --force --no-wall`

---
_Imported: 2026-11-14 22:53:45 UTC_
