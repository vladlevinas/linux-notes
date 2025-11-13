# systemd-ac-power

> Source: TLDR (MIT) — from 'vendor/tldr/'

# systemd-ac-power

> Report whether the computer is connected to an external power source.
> More information: <https://www.freedesktop.org/software/systemd/man/systemd-ac-power.html>.

- Silently check and return a 0 status code when running on AC power, and a non-zero code otherwise:

`systemd-ac-power`

- Additionally print `yes` or `no` to `stdout`:

`systemd-ac-power {{[-v|--verbose]}}`

---
_Imported: 2025-11-13 19:19:23 UTC_
