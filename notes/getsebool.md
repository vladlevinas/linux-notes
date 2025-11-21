# getsebool

> Source: TLDR (MIT) — from 'vendor/tldr/'

# getsebool

> Get SELinux boolean value.
> See also: `semanage-boolean`, `setsebool`.
> More information: <https://manned.org/getsebool>.

- Show the current setting of a boolean:

`getsebool {{httpd_can_connect_ftp}}`

- Show the current setting of [a]ll booleans:

`getsebool -a`

- Show the current setting of all booleans with explanations:

`sudo semanage boolean {{[-l|--list]}}`

---
_Imported: 2025-11-21 19:19:49 UTC_
