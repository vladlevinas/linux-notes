# systemctl-soft-reboot

> Source: TLDR (MIT) — from 'vendor/tldr/'

# systemctl soft-reboot

> Shut down and reboot userspace, leaving the kernel running.
> More information: <https://www.freedesktop.org/software/systemd/man/systemctl.html#soft-reboot>.

- Perform a soft reboot immediately:

`systemctl soft-reboot`

- Force a soft reboot:

`systemctl soft-reboot --force`

- Schedule a soft reboot for a specific time:

`systemctl soft-reboot --when "{{timestamp}}"`

- Cancel a scheduled soft reboot:

`systemctl soft-reboot --when cancel`

---
_Imported: 2026-05-13 15:44:39 UTC_
