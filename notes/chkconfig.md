# chkconfig

> Source: TLDR (MIT) — from 'vendor/tldr/'

# chkconfig

> Manage the runlevel of services on CentOS 6.
> More information: <https://manned.org/chkconfig>.

- List services with runlevel:

`chkconfig --list`

- Show a service's runlevel:

`chkconfig --list {{ntpd}}`

- Enable service at boot:

`chkconfig {{sshd}} on`

- Enable service at boot for runlevels 2, 3, 4, and 5:

`chkconfig --level {{2345}} {{sshd}} on`

- Disable service at boot:

`chkconfig {{ntpd}} off`

- Disable service at boot for runlevel 3:

`chkconfig --level {{3}} {{ntpd}} off`

---
_Imported: 2026-04-07 19:58:04 UTC_
