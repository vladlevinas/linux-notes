# systemctl-try-restart

> Source: TLDR (MIT) — from 'vendor/tldr/'

# systemctl try-restart

> Restart one or more units only if they are currently running.
> More information: <https://www.freedesktop.org/software/systemd/man/systemctl.html#try-restart%20PATTERN%E2%80%A6>.

- Restart a specific unit if it is running:

`systemctl try-restart {{unit}}`

- Restart multiple units if they are running:

`systemctl try-restart {{unit1 unit2 ...}}`

- Restart all units matching a pattern if they are running:

`systemctl try-restart '{{pattern}}'`

---
_Imported: 2026-03-01 07:35:32 UTC_
