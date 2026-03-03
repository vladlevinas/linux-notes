# systemctl-is-system-running

> Source: TLDR (MIT) — from 'vendor/tldr/'

# systemctl is-system-running

> Check the current state of the system.
> More information: <https://www.freedesktop.org/software/systemd/man/systemctl.html#is-system-running>.

- Check whether the system is operational and print the current state:

`systemctl is-system-running`

- Check and print the current state quietly (no output, only exit status):

`systemctl is-system-running --quiet`

- Wait until the boot process is completed before printing the current state:

`systemctl is-system-running --wait`

---
_Imported: 2026-03-03 07:45:21 UTC_
