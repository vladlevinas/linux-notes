# systemctl-thaw

> Source: TLDR (MIT) — from 'vendor/tldr/'

# systemctl thaw

> Thaw (resume) one or more frozen units.
> Units can be frozen with `systemctl freeze`.
> More information: <https://www.freedesktop.org/software/systemd/man/systemctl.html#thaw%20PATTERN%E2%80%A6>.

- Thaw a specific unit:

`systemctl thaw {{unit}}`

- Thaw multiple units:

`systemctl thaw {{unit1 unit2 ...}}`

- Thaw all currently frozen units:

`systemctl thaw '*'`

---
_Imported: 2026-05-20 10:25:38 UTC_
